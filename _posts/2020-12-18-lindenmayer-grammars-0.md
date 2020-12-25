---
title: An Introduction to Lindenmayer Grammars
date: 2020-12-18 00:00:00
featured_image: '/images/post_pics/lindenmayer/biblebook_0.jpg'
excerpt: Part 0 of my Rewriting Systems Sequence. An introduction to abstract rewriting systems, lindenmayer systems, and formal grammars, covering the philosophical motivation, mathematical theory, practical applications, and major assumptions. 
---
*Updated: 2020-12-24*  
*Topics: [Biology](https://mundyreimer.github.io/archive), [Cognitive Science](https://mundyreimer.github.io/archive), [Physics](https://mundyreimer.github.io/archive), [Mathematics](https://mundyreimer.github.io/archive), [Philosophy](https://mundyreimer.github.io/archive), [History](https://mundyreimer.github.io/archive)*  
*Confidence: Probable*  
*Status: Still in progress* 
## Rewriting Systems Sequence - Part 0

TL;DR - An introduction to abstract rewriting systems, lindenmayer systems, and formal grammars, covering the philosophical motivation, mathematical theory, practical applications, and major assumptions.  

---

### Motivation

Could simple rules govern how living structures build themselves out of non-living structures?  Can these simple rules generate much of the biological, chemical, and physical phenomena we see today?  In other words, can these complex systems be reduced to just the interaction of simple rules?  More generally, could these rules allow us to blur the arbitrary Newtonian distinction made between objects and the background from which they are situated in, such that the objects are *composed of* the background itself?

<br/>

<center>
<a href="https://en.wikipedia.org/wiki/Drawing_Hands">
    <img src="/images/post_pics/lindenmayer/escher_hands.jpeg"
        width="400" 
        height="400"
        >
    <em>Drawing Hands is a lithograph by the Dutch artist M. C. Escher.  It is referenced in the book Gödel, Escher, Bach, by Douglas Hofstadter, who calls it an example of a strange loop.</em>
</a>
</center>

<br/> 

Questions like these might help prime your intution for the [Church-Turing-Deutsch Principle](https://en.wikipedia.org/wiki/Church%E2%80%93Turing%E2%80%93Deutsch_principle), which roughly states that *every finitely realizable physical system can be perfectly simulated by a universal computing machine operating by finite means*.  It is effectively viewing the various systems and phenomena found in Nature as a sort of *computation* being *enacted* out, a type of [Digital Physics](https://en.wikipedia.org/wiki/Digital_physics) or [Pancomputationalist](https://en.wikipedia.org/wiki/Digital_physics#Pancomputationalism) perspective.  

It is key to note that we are not envisoning all of Nature as literally a computer like you might have on your desk or in your pocket, but rather trying to be more general and viewing Nature as following a well-defined set of steps such that any one particular system or special configuration of molecular matter is just a particular *instantiation* or substrate for which a more general mechanistic set of relations or rules is being played out on, very similar to how you can do the addition of 5+4=9 with rocks, with sticks, or on a digital calculator, the inputs and outputs are always the same.  In other words, it is the claim that this set of relationships or rules can be imposed on any particular physical material system and the computation would be the same.  Such a broad conception of *computation* tends to be captured by the phrase *substrate independence* or [multiple realizability](https://plato.stanford.edu/entries/multiple-realizability/).

<br/>

<center>
<a href="https://en.wikipedia.org/wiki/Rule_30">
    <img src="/images/post_pics/lindenmayer/conusshell.jpeg"
        width="400" 
        height="400"
        >
    <em>A Conus textile shell similar in appearance to Rule 30. Rule 30 is an elementary cellular automaton that displays complex aperiodic, chaotic behavior, similar to patterns like that of this shell.</em>
</a>
</center>

<br/> 

With that said, without necessarily strongly claiming the truth of such a principle, in this series of articles we will instead seek a more epistemically humble and pragmatic perspective for now, and limit ourselves to the study of a computational concept called *Rewriting Systems* (RS) and the implications they could have in modeling various phenomena.

<br/>

<center>
<a href="https://www.felienne.com/archives/2974">
    <img src="/images/post_pics/lindenmayer/turingmachine.gif"
        width="400" 
        height="400"
        >
    <em></em>
</a>
</center>

<br/> 

### Theory of Rewriting Systems

We all learn that equations are composed of a string of symbols or terms written down.  For example, in the equation *2+3+4=9*, we have seven different symbols or terms: *'2', '+', '3', '+', '4', '=', and '9'*.  We know that we can *simplify* this formula by replacing certain subterms in this formula with equivalent terms, namely by replacing the three symbols of *'2+3'* with the single symbol *'5'*, etc, eventually boiling down to the expression *'9=9'*.  

In essence, what we are doing above is *rewriting* certain terms as other terms, and we are doing this in an attempt to *simplify* things.  But what if we were to reverse our direction and *generate* terms by expanding out our expressions?  Or what if we didn't necessarily care about a particular direction, but rather we just simply keep rewriting or *replacing* certain combinations of terms with other terms and then see how the dynamics of our system eventually play out?[^.]      

For an example of rewrite systems in action, let's imagine we have a set of red and blue candied jelly fish *laid out in a horizontal line* on the table in front of you.  Let's represent that system by the following:

*red red blue blue red red blue blue*

And let's set our rewrite rules as follows:

*blue blue -> red*

*blue red -> blue*

*red blue -> blue*

The above basically states that whenever we see two blue fish in a row, we can replace them both with a single red fish.  Similarly, whenever we see a blue fish and then a red fish, we can replace them both with a single blue fish, etc.  The following shows what happens to our line of fish when applying any one single rule at that stage.

*red red blue* **blue red** *red blue blue*

*red red* **blue blue** *red blue blue*

*red red red* **red blue** *blue*

*red red* **red blue** *blue*

*red* **red blue** *blue*

**red blue** *blue*

**blue blue**

**red**

We can see that with an odd number of blue fish, the sequence will always end in one blue fish.  We can modify the rules so that the outcome is totally independent of the particular rule we choose to apply when.  We can also modify the rules so that as mentioned before, instead of having every rule simplify the line of fish, some rules can generate new fish, etc.  Additionally, we can modify our rules so that they take the form of a *template* such as,

*blue ... blue -> red ...*

where anytime we see an ellipsis, we can fill in that with any number of fish as long as the other ellipsis is the same amount.  These variations upon rules can continue on and on.

To help us generalize, let's define a few *properties* of rewrite systems:

1) **Normal / Canonical / Standard Form**: This basically means that our object composed of a sequence of terms cannot be simplified any further.  An object is said to be **weakly normalizing** if it can be rewritten *somehow* into a normal form, that is, if *some* rewrite sequence of steps starting from it cannot be extended any further.  An object is said to be **strongly normalizing** if it can be rewritten in *any way* into a normal form, that is, if *every* rewrite sequence starting from it eventually cannot be extended any further. 

2) **Confluence**: This describes which terms can be rewritten in more than one way, to yield the same result.  For instance, let's take our rules of addition in multiplication in arithmetic.  We can either evaluate (or rewrite) our equation starting from the left or starting from the right, as shown in the below example.  Since both routes evaluate to the same thing, then we can say that our arithmetic rewriting system is *confluent*.  In other words, no matter how two paths diverge from a common ancestor (w), the paths are joining at some common successor. 

<br/>

<center>
<a href="https://en.wikipedia.org/wiki/Confluence_(abstract_rewriting)">
    <img src="/images/post_pics/lindenmayer/confluence_example.png"
        width="400" 
        height="400"
        >
    <em>In arithmetic we can either simplify our expression via the left path or the right path.</em>
</a>
</center>

<br/> 

3) **Terminating / Noetherian**: A rewrite system (RS) is *terminating* or *noetherian* if there is no infinite chain of rewrite steps.  In other words, in a terminating RS every object is required to have at least one normal form that it reduces to.  This property is crucial if we are to use a RS for computation or as a decision procedure for the validity of identities.   

4) **Convergent**: If our RS is *terminating* AND *confluent*, then we can also call it **convergent**.  In other words, every object has a unique normal form.

Rewriting systems can take make forms and act on a number of different objects.  If acting on polygons, they can be used to produce fractal images like the [Koch Snowflake]() where one has two shapes, an *initiator* and a *generator*,

<br/>

<center>
<a href="https://en.wikipedia.org/wiki/Koch_snowflake">
    <img src="/images/post_pics/lindenmayer/kochflake0.png"
        width="400" 
        height="400"
        >
    <em>Construction of the snowflake curve</em>
</a>
</center>

<br/> 

<br/>

<center>
<a href="https://en.wikipedia.org/wiki/Koch_snowflake">
    <img src="/images/post_pics/lindenmayer/kochflake1.gif"
        width="400" 
        height="400"
        >
    <em>The first seven iterations applying the generator</em>
</a>
</center>

<br/> 

Or when the objects are strings in a natural language, they can be used in linguistics as models of [grammatical structure](https://en.wikipedia.org/wiki/Generative_grammar) like [Chomsky](https://en.wikipedia.org/wiki/Noam_Chomsky)'s work in formal grammars,

<br/>

<center>
<a href="https://en.wikipedia.org/wiki/Generative_grammar">
    <img src="/images/post_pics/lindenmayer/grammartree.png"
        width="400" 
        height="400"
        >
    <em>A generative parse tree: the sentence is divided into a noun phrase (subject), and a verb phrase which includes the object.</em>
</a>
</center>

<br/> 

Or when the objects are arrays, like in [Conway's Game of Life](https://en.wikipedia.org/wiki/Conway%27s_Game_of_Life) where they form the cornerstone of the diverse phenomena witnessed,

<br/>

<center>
<a href="https://www.samcodes.co.uk/project/game-of-life/">
    <img src="/images/post_pics/lindenmayer/gameoflife.gif"
        width="400" 
        height="400"
        >
    <em>An interactive implementation of John Conway's Game of Life built in WebGL by Sam Twidale.</em>
</a>
</center>

<br/> 

Or when the objects are graphs, like in Stephen [Wolfram's Physics Project](https://en.wikipedia.org/wiki/Wolfram_Physics_Project) where he is trying to create a new fundamental theory of physics and *derive* physical laws from the bottom-up,

<br/>

<center>
<a href="https://writings.stephenwolfram.com/2020/04/finally-we-may-have-a-path-to-the-fundamental-theory-of-physics-and-its-beautiful/">
    <img src="/images/post_pics/lindenmayer/wolframgraph.png"
        width="400" 
        height="400"
        >
    <em></em>
</a>
</center>

<br/> 

With all that said, we will limit ourselves to the study of a particular type of rewriting system called a *Lindenmayer System*...

<br/>

<center>
<a href="http://algorithmicbotany.org/papers/abop/abop.pdf">
    <img src="/images/post_pics/lindenmayer/nestedrewritesystems.png"
        width="400" 
        height="400"
        >
    <em></em>
</a>
</center>

<br/> 


### Lindenmayer Systems

<br/>

<center>
<a href="https://en.wikipedia.org/wiki/L-system">
    <img src="/images/post_pics/lindenmayer/Lsystem0.jpg"
        width="400" 
        height="400"
        >
    <em>L-system trees form realistic models of natural patterns.</em>
</a>
</center>

<br/> 

A [Lindenmayer System](https://en.wikipedia.org/wiki/L-system) (sometimes called *L-grammars*, *parametric* L-Systems, or *L-systems* for short) is a specific type of rewrite system.  L-systems were created by a Hungarian theoretical biologist and botanist named [Aristid Lindenmayer](https://en.wikipedia.org/wiki/Aristid_Lindenmayer) in 1968, independent of work done in symbolic dynamics at the time.  Aristid originally worked with yeast, fungi, and algae, and studied how they grew into various filamentous patterns, later moving on to more advanced organisms like plants.

<br/>

<center>
<a href="https://en.wikipedia.org/wiki/L-system">
    <img src="/images/post_pics/lindenmayer/Lsystem1.jpg"
        width="400" 
        height="400"
        >
    <em>'Weeds', generated using an L-system in 3D.</em>
</a>
</center>

<br/> 

L-systems grew in popularity due to the beauty of how simple [recursive](https://en.wikipedia.org/wiki/Recursion_(computer_science)) rules can lead to [self-similar](https://en.wikipedia.org/wiki/Self-similarity) objects and thus fractal-like forms resembling seemingly complex shapes of organisms in nature like grasses, ferns, and trees.

<br/>

<center>
<a href="https://en.wikipedia.org/wiki/L-system">
    <img src="/images/post_pics/lindenmayer/Lsystem2.gif"
        width="400" 
        height="400"
        >
    <em>Recursively growing a plant.</em>
</a>
</center>

<br/> 

In particular, an L-system is an RS that can be defined as the tuple:

*G = (V, ω, P)*

Where that tuple consists of 3-4 things:

1) An **Alphabet**, **V**, of symbols that can be used to make [strings](https://en.wikipedia.org/wiki/String_(computer_science)) (a sequence of characters).  This alphabet in turn consists of symbols that can be replaced (*variables*) and symbols that cannot be replaced (*constants* or *terminals*).  Furthermore, we let **V\*** represent the set of all words over **V**, and **V+** represent the set of all non-empty words over **V**.

2) An initial **Axiom** string, **ω**, from which to begin construction from (similar to our starting line of colored fish from above). It defines the *initial state* of the system.

3) A collection of **[Production Rules](https://en.wikipedia.org/wiki/Production_(computer_science))** or *Productions*, **P**, that expand each symbol into some larger string of symbols.  Specifically it is a set of rewrite rules that can be recursively performed to generate new symbol sequences.  In turn, each production rule consists of two strings, the *predecessor* and the *successor*, that string which is to be replaced and that string which it is replaced by respectively.   If no production is explicitly specified for a given predecessor *a ∈ V* , the identity production *a → a* is assumed to belong to the set of productions *P*.

4) A **Mechanism** for translating the generated strings into geometric structures. (This is a weak requirement and only used in the case of visualization or other applied purposes)

From here we apply the production rules to the axiom in an interative fashion, with as many rules as possible being applied simultaneously per iteration.  This latter requirement of applying as many rules as possible per iteration rather than applying only one rule per iteration is what separates L-systems from *formal languages* generated by *formal grammars*, and that is why they are sometimes called *parallel* rewriting systems.  Thus, L-systems are strict *subsets* of languages.  This parallel nature was originally meant to capture the cell divisions that occur in multicellular organisms, where many divisions can occur at the same time.[^1]  *This is a key distinguishing feature going forward.*

Similar to before with the more general rewrite systems, our more specific L-systems have 2 additional properties:

1) An L-system is **Context-free** if each production rule refers only to an individual symbol and not its neighboring symbols.  If a rule requires that it check not only that single symbol, but also that of its neighbors, then we say that it is **context-sensitive**.

2) An L-system is **deterministic** if there is exactly one production rule per symbol.  If there are several rules that can apply to a certain symbol and we choose a particular rule according to some probability each iteration, then we instead call the L-system **stochastic**.  

If an L-system is both *deterministic* and *context-free* then it is called an [DOL System](https://en.wikipedia.org/wiki/Morphic_word#D0L_system).

### Applications

So let's investigate how Lindenmayer originally used his L-systems to model the growth of algae. We can see that he defined his systems components as follows:

**Alphabet**: A B (both variables, no constants)

**Axiom**: A (what we start with)

**Rules**: (A → AB), (B → A)

At each stage of iteration *n* we can see that this produces the following:

n=0:               A             start (axiom/initiator)

n=1:             A   B           initial single A spawned into AB 

n=2:           A B      A        (A → AB), (B → A)

n=3:         A B A       A B     ...

n=4:       A B A A B     A B A   ... 

n=5: ABAABABAABAAB

n=6: ABAABABAABAABABAABABA

...

What's interesting to note is that with these rules if we count the length of each string we get the [Fibonacci sequence](https://en.wikipedia.org/wiki/Fibonacci_sequence) of numbers.  That is why this sequence is sometimes called a sequence of [Fibonacci words](https://en.wikipedia.org/wiki/Fibonacci_word).

1 2 3 5 8 13 21 34 55 89 ...

<br/>

<center>
<a href="https://en.wikipedia.org/wiki/Fibonacci_sequence">
    <img src="/images/post_pics/lindenmayer/fibonaccispiral.png"
        width="400" 
        height="400"
        >
    <em>A tiling with squares whose side lengths are successive Fibonacci numbers: 1, 1, 2, 3, 5, 8, 13 and 21.  An approximation of the golden spiral is created by drawing circular arcs connecting the opposite corners of squares in the Fibonacci tiling.</em>
</a>
</center>

<br/> 

The formalism above is used to capture and simulate the notion of the development of a fragment of a multicellular filament such as that found in the blue-green bacteria *Anabaena catenula* and other various algae.[^1].  

<br/>

<center>
<a href="http://algorithmicbotany.org/papers/abop/abop.pdf">
    <img src="/images/post_pics/lindenmayer/algae.png"
        width="400" 
        height="400"
        >
    <em></em>
</a>
</center>

<br/> 

Where the symbols *a* and *b* represent the different states of the cells (their sizes and readiness to divide), and the subscripts *l* and *r* specify the positions in which daughter cells of type *a* and *b* will be produced.  This particular mapping was chosen because it was observed that underneath a microscope, the filaments appear as a sequence of cylinders of various lengths, with *a*-type cells longer than *b*-type cells.[^1]

So what other phenomena can be captured by this particular L-system formalism? Because L-systems were originally intended to model the growth of systems in a directed, recursive fashion, we know that they can be represented visually by directed graphs in a *tree-like* structure.  As such they can be used to model *dendritic* or *arboreal* geometries found in nature.

<br/>

<center>
<a href="https://www.researchgate.net/figure/Blood-vessels-winter-tree-Amazon-River-delta-leaf-veins-cracked-earth-and-city-plan_fig1_311693712">
    <img src="/images/post_pics/lindenmayer/treepattern0.png"
        width="400" 
        height="400"
        >
    <em>Blood vessels, winter tree, Amazon River delta, leaf veins, cracked earth, and a city plan  </em>
</a>
</center>

<br/> 

These *tree-like* structures are rather ubiquitous in nature.  Obviously, many biological structures like blood vessels, neurons, mycological growth, slime-molds, etc can be at least visually seen to follow this scheme.  

<br/>

<center>
<a href="https://en.wikipedia.org/wiki/Slime_mold">
    <img src="/images/post_pics/lindenmayer/treepattern1.jpeg"
        width="400" 
        height="400"
        >
    <em>Slime mold is a name given to several kinds of unrelated eukaryotic organisms that can live freely as single cells, but can aggregate together to form multicellular reproductive structures. This colony organism can even solve mazes.</em>
</a>
</center>

<br/> 

Similarly, in physics we have lightning and [Lichtenberg figures](https://en.wikipedia.org/wiki/Lichtenberg_figure),  

<br/>

<center>
<a href="https://www.woodworkersjournal.com/evan-blomquist-high-voltage-woodburning/">
    <img src="/images/post_pics/lindenmayer/treepattern2.gif"
        width="400" 
        height="400"
        >
    <em>A Lichtenberg figure is a branching electric discharge that sometimes appears on the surface or in the interior of insulating materials.  It is an example of natural phenomena which exhibit fractal properties.  This particular video was taken by Evan Blomquist from *Electrostatic Wood*.</em>
</a>
</center>

<br/> 

### Major Assumptions

*...in progress*

### Moving Forward

*...in progress*

[See here]() for the next part of this sequence offering a tutorial on how to experiment and simulate L-systems in Python.

---

Resources:
 
[^0]: [Handbook of Theoretical Computer Science, Chapter 6: Rewrite Systems](https://www.cs.tau.ac.il/~nachum/papers/survey-draft.pdf) by Nachum Dershowitz and Jean-Pierre Jouannaud.  This provided much of the theory behind the theory of [Rewriting](https://en.wikipedia.org/wiki/Rewriting) and [abstract rewrite systems](https://en.wikipedia.org/wiki/Abstract_rewriting_system).  It specifically goes into depth on ARSs from algebraic, logical, and operational perspectives.  
 
[^1]: [The Algorithmic Beauty of Plants](http://algorithmicbotany.org/papers/abop/abop.pdf) by [Przemysław Prusinkiewicz](https://en.wikipedia.org/wiki/Przemys%C5%82aw_Prusinkiewicz) (director of the Computer Graphics group studying Fibonacci numbers and modeling using grammars) and [Aristid Lindenmayer](https://en.wikipedia.org/wiki/Aristid_Lindenmayer)(a theoretical biologist studying sequence generators). This textbook is based off Lindenmayer's original notes discusssing the theory and practice of Lindenmayer (L-)Systems for modeling plant growth. It provides much of the theoretical material from which I "draw" from (heh).



[^.]  As a side note, rewrite systems are known to possess the *"full power of Turing machines and may be thought of as non-deterministic Markov algorithms over terms, rather than strings"*[^0].

[^..]: [Math StackExchange](https://math.stackexchange.com/questions/3778087/what-are-the-relations-and-differences-between-formal-systems-rewriting-systems)