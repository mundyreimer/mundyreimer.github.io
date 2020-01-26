---
title: 'Representation, Notation, & Thought'
date: 2018-12-10 00:00:00
featured_image: 
excerpt: Compilation of resources featuring the interplay of mathematics, language, and notation
---
*Updated: 2019-08-23*  
*Topics: [Mathematics](https://mundyreimer.github.io/archive), [Computer Science](https://mundyreimer.github.io/archive), [Linguistics](https://mundyreimer.github.io/archive), [Philosophy](https://mundyreimer.github.io/archive), [Cognitive Science](https://mundyreimer.github.io/archive)*  
*Confidence: Speculative*

### resources & ruminations

In the spirit of [Gottfried Leibniz](https://en.wikipedia.org/wiki/Gottfried_Wilhelm_Leibniz), the following is a compilation of resources featuring the interplay of mathematics, language, and notation.  This is a curated collection of people's work and my musings regarding how the way we represent concepts and communicate via symbolic notation or graphical means may influence the way we think about these concepts.  This line of thinking is commonly called the *Sapir-Whorfian Hypothesis* or [*Linguistic Determinism*](https://en.wikipedia.org/wiki/Linguistic_determinism).  

Another way of viewing this is to interpret notation as one's UI of sorts, where certain capabilities are enhanced or diminished, and certain lines of thought are made more conducive and are much more likely to occur upon the use of a particular interface or tool, or in this case notation.

*Note - The following curated collection is a work-in-progress and will be continually updated*

-----

* [On the Existence of Powerful Natural Languages](https://www.gwern.net/Language)  

It might be prudent to first link to the somewhat opposing perspective from Gwern, in which he talks about the *Existence of Powerful Natural Languages* and how the quest to find them is doomed from the start because languages inherently gain power from specialization. 

*"Designed formal notations & distinct vocabularies are often employed in STEM fields, and these specialized languages are credited with greatly enhancing research & communication.*

*Many philosophers and other thinkers have attempted to create more generally-applicable designed languages for use outside of specific technical fields to enhance human thinking, but the empirical track record is poor and no such designed language has demonstrated substantial improvements to human cognition such as resisting cognitive biases or logical fallacies. I suggest that the success of specialized languages in fields is inherently due to encoding large amounts of previously-discovered information specific to those fields, and this explains their inability to boost human cognition across a wide variety of domains."*

-----

* [Graphical Linear Algebra](https://graphicallinearalgebra.net/2016/08/26/30-the-essence-of-graphical-linear-algebra/)  

[Index of Series](https://graphicallinearalgebra.net)  

This series of blog posts was fun & interesting.  The author creatively recasts Linear Algebra into a graphically-based _circuit-like_ or _string-diagram_ language.  It might get a tad polemic when talking about the history of math and the Bourbakian movement towards abstraction, but either way, I thought his work might harness our native visual processing wetware and intuition a bit more.

I recommend starting with post #3, but if you want to go straight to the meat of it, start at post #11.  Other than that, it starts out really basic (using Lego examples) but depending upon how far you get, I particularly found the parts regarding Frobenius monoids, diagram compositionality + concurrency, feedback + control theory, and PROPs + symmetric monoidal categories especially fascinating.

See my extended ~~rant~~ argument[^footnote] for the acceptance and adoption of diagrammatic languages and visual reasoning tools like the aforementioned Graphical Linear Algebra and how they are not necessarily less rigorous as some may have you believe.

-----

* [Notation and Thinking](https://rjlipton.wordpress.com/2010/11/30/notation-and-thinking/) by rjlipton  
* [Notation as a Tool of Thought](https://drive.google.com/file/d/10O2VotO3ssRHerVkUvgMq0jeBgaH0kCz/view?usp=sharing) by Kenneth Iverson  

The aforementioned article gives a brief run down of notation invented throughout history.  Iverson's paper is given in the context of the history and design of APL.

*"Kenneth Iverson was a mathematician who is most famous for designing APL. This was the name of his programming language, and it cleverly stood for “A Programming Language.” The language is unique—unlike almost any other language—and contains many powerful and interesting ideas. He won the 1979 Turing Award for this and related work.*
 
*Today I want to talk about notation in mathematics and theory, and how notation can play a role in our thinking.*

*When I was a junior faculty member at Yale University, in the early 1970’s, APL was the language we used in our beginning programming class. The reason we used this language was simple: Alan Perlis, the leader of the department, loved the language. I was never completely sure why Alan loved it, but he did. And so we used it to teach our beginning students how to program.*

*Iverson had created his language first as a notation for describing complex digital systems. The notation was so powerful that even a complex object like a processor could be written in his language in relatively few lines of code: the lines might be close to unreadable, but they were few. Later the language was implemented and had a small but strong set of believers. Clearly, Alan was one of them who once said:*

*A language that doesn’t affect the way you think about programming, is not worth knowing.*

*The importance of nomenclature, notation, and language as tools of thought has long been recognized. In chemistry and in botany, for example, the establishment of systems of nomenclature by Lavoisier and Linnaeus did much to stimulate and to channel later investigation. Concerning language, George Boole in his Laws of Thought asserted 'That language is an instrument of human reason, and not merely a medium for the expression of thought, is a truth "generally admitted."'*

*Mathematical notation provides perhaps the best-known and best-developed example of language used consciously as a tool of thought. Recognition of the important role of notation in mathematics is clear from the quotations from mathematicians given in Cajori’s A History of Mathematical Notations. They are well worth reading in full, but the following excerpts suggest the tone:*

*"By relieving the brain of all unnecessary work, a good notation sets it free to concentrate on more advanced problems, and in effect increases the mental power of the race."   
—A.N. Whitehead*

*"The quantity of meaning compressed into small space by algebraic signs, is another circumstance that facilitates the reasonings we are accustomed to carry on by their aid."    
—Charles Babbage"*

-----

* ArcScript  
[Video explanation](https://youtu.be/IFVKSOC6iCY)  
[PDF](http://www.dscript.org/ascript.pdf)  

What if our writing system had evolved from a tool with 2 points instead of 1? (ie - a compass-like device similar to what you used in geometry class instead of a pencil/nib)

A neat idea coming from the creative mind of Matthew Deblock.  

Now you might not think much of his one-to-one mapping of these circular pictures to our modern day alphabet, but I would argue that's the wrong thing you should be taking away from this idea. We don't have to necessarily map this to an alphabet like he does...

Instead, the questions / concepts that I do think are interesting to think about are:  

1. How would *any* resulting alphabet, abjad, abugida, syllabary, or logographic system then develop?   

2. Would writing like this for years on end somehow influence the way you think, or make certain thoughts more likely to occur? ...Similar to how the Roman numeral system (I, II, IV, X, etc) being a non-positional numeral system made certain arithmetical calculations rather difficult and time/memory consuming compared to our current day Hindu-Arabic system (1,2,3,4,…)  

3. This system is both rotational and mirror symmetry invariant (and if you are clever enough, it can be scale-invariant as well). What this means is that whatever way you look at it, either backwards, through a mirror, upside down, etc, the character is still the same if you apply the same rules to make it (ex - draw clockwise, change pivot, draw counterclockwise, change pivot, cross lines, etc). Could we harness this symmetry to solve some problems in our own current writing systems? (ex - dyslexia?)[^2]  

4. Instead of naively mapping circular symbols to the English alphabet like in Deblock's paper, could we rather map a logical system to these circular symbols such that the linguistic system overlaps with built-in expressions of mathematics like unit circle concepts, sin waves for music / physics of waves-type phenomena, modular arithmetic, clock/time representations (yay for sexagesimal/base-60 and duodecimal/base-12 number systems of which I am a huge fan!!), recursive algorithms, or other geometric concepts? ...in essence, harnessing the natural symmetry of the tool to intuitively express other physical and mental concepts that invoke symmetry?  

5. Could we now imagine different mechanical writing tools and constructs and how their various geometries might have influenced our writing systems if they happened to have been chosen in our past?  

    (I can easily think up various *rocking/teetering* type stamp devices that could make writing rather quick, while still being rather weird but logical in its design, for example, imagine writing not with a pen, but holding and rolling a ball-shaped stamp or a reverse-crescent/moon shaped stamp underneath one's palms/fingertips. How about a stamp in the shape of something like the Hungarian Gömböc and its various iterations?)  

Another project designed by DeBlock featuring an attempt at a Universal Logographic Physics-based language can be [found here](http://www.dscript.org/uscript.pdf) called *DScript*.  I particularly like this conlanger's symbol for 2D, 3D, and 4D, etc.  His use of set-theoretic-like bracketing might also be of use for alternative conscripts that I'm personally entertaining, although there is also something to be said about doing away with this foundational notion altogether and switching to something similar to the category-theoretic diagrams in the aforementioned Graphical Linear Algebra link.

Also, [DeBlock's latest conscript](http://www.dscript.org/bscript.pdf) was developed for encryption & cipher use-cases.  The mapping might be a tad 'hacky', but I really enjoyed the *bitwise operator* potential. The *operation-chaining* & choice of *operation density* stands out to me as potentially useful concepts, even outside of his intended use-cases.  I also found the ability to switch between binary / trinary systems rather neat as well, & the ease+fluidity of writing it first-class when compared to other scripts which would otherwise force one's physical movements to become stilted and staccato-like when writing.   

-----

* [Notation & Thought Compilation](https://github.com/hypotext/notation) by Katherine Ye

Katherine seems to have similar shared interests and she's put together an excellent compilation of various notational systems and how they may influence the ways people think.  I highly recommend checking out her thoughts and [talks](https://youtu.be/Wahc9Ocka1g).

-----

* [Artifexian & Alternative Numeral Notation](https://youtu.be/EyS6FfczH0Q)

One of the coolest numeral systems I've ever seen! Developed by Kaktovik Iñupiaq middle school kids (all 9 of them in their entire Alaskan town) & their linguist-trained teacher, it's like Korea's featural Hangul but for numbers (ie - the shape of the characters tells you something). I especially the inuituitive (😅) and simple rotational + overlapping way of computing w/ it. (It's what I've always wanted in a numeral system!) 

-----

* [3Blue1Brown & Triangle of Power](https://youtu.be/sULa9Lc4pck)

Intuitive notation developed for linking together the concepts of logarithms, exponents, and roots explained by 3Blue1Brown.  I do like the mention of the new 'O-plus' operation that might need to be introduced as this might possibly indicate that some ways of thinking might indeed be more/less conducive depending upon the notation we use, and thus suggesting that we might be possibly ignoring some pretty low-hanging conceptual fruit due to something as simple as having the wrong notation at hand for it.    

It also might be wise to link to an article from *The Reference Frame* arguing for [why the Triangle of Power notation might be misguided](https://motls.blogspot.com/2016/07/why-triangle-notation-for-powers-is.html).  Good points against the new notation are made in here as well.  

-----

* [Hangul](https://www.quora.com/Its-said-written-language-was-invented-three-or-four-times-How-does-Korean-Hangul-fit-in-to-this)

The Korean script, *Hangul*, is a featural writing system, which means the shapes of the symbols are not random/arbitrary but rather they encode phonological / physical movements you make with parts of your mouth (for example the placement of your tongue matching what the symbol looks like). I call this concept *embodiment* or making language aligned much more closely to our intuition, body, and gut-level feeling of meaning, which might make  things easy to learn, pick up, or decipher if you are an foreigner / alien with respect to the language (or even a linguist in the far far future trying to piece together fragments of culture from our language). 

Now imagine taking that *embodied* aspect, but now applying it such that we update our mathematical symbols to become a lot more intuitive, easy to learn, easy to pick up after years of non-use, etc. Designing our numbers + algebraic symbols such that they actually *look like* how we would physically compute the equation and shuffle around the bits of meaning.

Taking it a step further, what if we even transcend our algebraic symbol shuffling so that instead it just becomes a language of *graphs, networks, circuits, diagrams, and pictures*, such that mathematical reasoning becomes as intuitive as looking at for instance a plumbing layout and immediately knowing the consequences of some blocking of water in a pipe from just a glance. In essence, computing and reasoning with intuitive pictures instead of 'dry' symbols. How might this change our relationship with maths and possibly make certain thoughts about difficult-to-reason concepts like higher dimensions as intuitive as counting on one's fingers? Would this possibly induce the creation of new branches of mathematics and physics? 

*"Writing was invented three/four times, and the alphabet was invented only once. Korean is the crown jewel of the alphabet world, but it wasn’t a separate instance of the invention of writing, nor an exception to the sole invention of the alphabet.*

*Plenty of people have invented their own writing systems before - chances are you’ve at least tried to create your own cryptic system of doodles. These wouldn’t be considered separate inventions of the system of writing. Similarly, if you created an alphabet, well, you’ve based it on previous alphabetic systems, so your system isn’t an original idea.*

*Hangul, then, is unextraordinary: it wasn’t a new invention of writing, nor even an independent creation of the alphabet. To say its invention was at all uninteresting, though, would be a gross injustice to its creation.*

*King Sejong, better known as Sejong the Great, lived in a time when scholars and few others could read - something that upset Sejong, especially since he wanted to spread Confucianism to a population primarily illiterate in the 15th century.*

*The solution, he decided, would be to create an entirely new writing system. It would have to be easy to learn, easy to read and write, and, out of tradition-required necessity, derived in some way from Chinese.*

*The researchers Sejong sent out were led by Sin Suk-ju, who spoke - along with Korean, Chinese, and Japanese - the language of an empire that had only a few centuries earlier conquered China and Korea (as well as roughly half the entire continent of Eurasia): Mongolian.*

*After several trips, Sin returned with bad news and good news. The bad news was that there was apparently no way to conform Chinese orthography to Sejong’s wishes; the good news was that they’d come across the perfect system: the alphabet.*

*There were few alphabets in east Asia at the time: hanzi dominated, in varying forms and under different names across many different language families; Japanese supplemented the kanji with its kana syllabaries. Assorted Brahmic abugidas had come from India with the spread of Buddhism, but that was about it.*

*The idea of the alphabet was perfect for Sejong’s dream: while not the most efficient system in terms of space, alphabetic systems use fewer characters than syllabaries, and certainly fewer than logographic systems. One character for each individual sound? Perfect! It wouldn’t be based on Chinese, but that was a small price to pay for the ease the alphabet offered.*

*Hangul was based on Asian alphabets in idea, but not form, which turned out to be one of its stronger points. The basic consonants were based on the mouth shape used to make it: ㄱ is “g”, because you lift the back of your tongue to the back of your mouth to make it; ㄴ is “n”, because you lift the tip of your tongue to the front of your mouth; ㅅ, “s”, is made by putting your tongue at the front of your mouth and “hissing” air through it.*

*Want their voiceless forms? No problem! Add another stroke to ㄱ (“g”) for ㅋ (“k”), another stroke to ㄷ (“d”) for ㅌ (“t”), and another stroke to ㅈ (“j”) for ㅊ (“ch”). Want to lengthen the consonant? All you have to do is double it: ㄲ (“kk”), ㄸ (“tt”), ㅃ (“pp”).*

*Sejong named it the Hunminjeongeum, the “right sounds for teaching the people”.*

*King Sejong, for all his authority and his system’s practicality, didn’t see the alphabet catch on before his death from diabetes in 1450. Tradition’s grasp on the society was so great that it wasn’t until 1896, over four hundred years later, that the first newspaper was published in it.*

*It would take two world wars, Japanese suppression of the language, and a division of the country before Kim Il-Sung declared it the official script of North Korea, banning hanja in 1949. A new name had been given to it: 한글 han geul, literally “great script”.*

*South Korea held out with its hanja (now in serious decline) for a few decades longer, but in the 1990s, after five and a half centuries, Sejong’s Hangul became the official alphabet."*[^3] 

-----

* [*Words* by Radiolab](https://www.wnycstudios.org/story/91725-words)

Relevant podcast regarding the nature of language and how we internally organize the structure of our world with words.  Features a 27-year old guy who comes to learn the very first words in his entire life.  Incredibly fascinating story told in the brilliant narrative style of Radiolab.

-----

#### footnotes

[^footnote]: So these last couple of years got me thinking when was the last time I actually *felt* math, and *created* it like how one would create art or music. When did I last *play* with it. And for me, that was Geometry (and much much later Graph Theory). It might be because evolution and natural selection have biased us in favor of being predominately visual creatures, but I felt the closest affinity to mathematics when I could actually visualize and *see* things happening. Languages, grammar, and symbols are flippin' hard to learn, but pictures, heck, those are actually easy and fun.

    Now I totally understand the common criticism of a need for rigor and not getting led astray by one's visual intuition, but I don't think that's necessarily mutually exclusive with using pictures and diagrams *as a language itself*. Let me repeat that - Using pictures does NOT mean you have to give up rigor! The Greeks achieved great feats using just their lines and curves, Leonardo da Vinci himself relied upon visual perspective + proportion and did not know much 'symbolic math' at all, electrical engineers reason using pictures all the time with circuit diagrams, chemists with stereochemical+molecular diagrams, physicists with feynman diagrams, and sheesh, if we really want to generalize, then algebraic manipulation of letters and numbers is still a graphically-based reasoning process we do on paper and chalkboards (why else would teachers keep emphasizing that you physically go through the motions of writing and solving a problem on paper). Many of us don't realize that this symbolic manipulation game that characterizes the vast majority of mathematics education today is really a byproduct of the historical notation introduced by Francois Viete (I highly recommend his Wiki page!) who claimed that "all problems could be solved with it", and whose 'Algebra' only actually started taking off and being used from 1638 onwards. Does that mean that all math done before that was never really considered math? I don't think so. As Judea Pearl puts it, "To proclaim algebra the UNIVERSAL language of science, would sound today like proclaiming Esperanto the language of economics. Why would Nature agree to speak Algebra? Of all languages? ...[However], you can't argue with [its] success."

    Regardless of success, what we can argue is that the cognitive overhead required by Algebra and the language of symbols that we partake in today is still quite demanding in that we have to keep much of the actual semantics and meaning of what we are doing in our heads (in addition to storing the vast majority of 'what-this-all-means' in a collectively agreed-upon mathematics pedagogical culture). As a result of this, we suffer by blindly becoming machines manipulating symbols who consequently experience a loss as to how to relate this all back to reality. Think about all the students who often complain about when they will ever use this. And any parent helping their child with homework knows that without practice this symbol manipulation ability that they were drilled in when younger inevitability gets eroded by the ravages of time and memory loss. Historically the symbols may have freed some of our short term memory when compared to before, but they left most of us with our motivation and insight left beaten and blindfolded in the dark. Many of us never partake in recreational math for fun and many of us have trouble picking the symbolic language up again. And yet many of us will still play graphically-based logic games like the various incarnations of 'Bejeweled' on our phones everyday, so it's not for lack of our inner desire for puzzle-solving, but instead maybe the problem lies with the symbolic script-centric education itself.

    While it could be argued that things may indeed have improved intuition-wise with the marriage of algebraic symbols (from the Arabic 'al-jabr'), Indian numerals, and the Greek geometry united by Descartes and his Cartesian coordinate system which ultimately led to the birth of what we now popularly call Trigonometry, I would argue that while innovative, this was more a temporary band-aid than an actual cure for our loss of visual insight and feeling for meaning.

    So instead of this loss of meaning from using 'dry' symbols, maybe we could alternatively be using symbols or glyphs that are a lot more graphically intuitive and ease the learning process for the first time, as well as making the process easier to 'pick-up-again' after extended periods of non-use. For instance, we can adopt mathematical symbols that actually visually embody or 'look like' pictures that are closer to their underlying conceptual mechanisms, analogous to how for instance the Korean script, Hangul, was creatively designed such that their basic consonants visually mimic the shape of the speaker's throats when pronouncing each (gosh do I envy their script!) This ability to visualize processes is important. I don't think it's just a coincidence that those 'human-calculators' we see in competitions were originally trained on a physical abacus and still mentally visualize one when performing their seemingly superhuman feats of numerical performance (it is interesting to note the historical conflicts between the abacists and the algorists back in Fibonacci's time; only finally getting resolved sometime around the 16th century in favor of the algorists). Anybody who has studied the brain or knows how competitive memory champions undergo massive amounts of memorization would know how powerful our internal visual system is if used properly.

    In addition to adopting intuitively looking glyphs, this collective grouping of images could also be designed such that the *computation is embedded* in the process of making/reading the picture itself, similar to the causal logic embedded in electrical circuit diagrams. On a relevant note, it's interesting how Pearl's probabilistic graphical modeling that is revolutionizing the study of causality and statistics was also inspired by electronic circuitry pictures. In fact, Pearl champions the view that pictures give one the sense of how each part or component fits into the whole and how its logical relationship with every other part is made much more explicit, allowing us to intuit at-a-glance any possible scenarios where the logic might break (think of a plumbing layout for a house and how you could intuitively figure out the consequences of hypothetical scenarios where one plumbing line might break), compared to if we used a language like algebra which requires us to serially read line-by-line, further demanding us to mentally build up and imagine the conceptual architecture in our heads while maintaining that mental construct in our short term memory and while still being able to manipulate it (in addition to Pearl's argument that these equations don't fully capture the causal network of reality, but that's beside the point).

    For example, I remember this one time where my younger sister asked me for help understanding this equation and I was like 'oh, there's some energy or cost minimization occurring there and also some barrier causing it to rise steeply here', and she was like 'huh, what???', to which I further explained 'that's a hyperbolic looking curve shifted over this much with these oblique / slanted asymptotes here', and she responded with 'I don't remember how to do my graph shifting by reading these equations and our teacher only taught us how to find vertical and horizontal asymptotes not diagonally looking ones, how did you know that?', to which I yacked off something about the degrees of the polynomials in the numerator and denominator and how she can also figure out stuff by the symmetries inherent in the even-ness or odd-ness of the equation. Anyways my point is that if you didn't memorize these ritualistic procedures and esoteric facts or yet alone given the opportunity to learn these concepts from a gifted teacher, all of these symbols are basically gobbledygook to you (and I can definitely say are still considered chicken scratch most of the time for me too unless I constantly review and practice my fundamentals). Why can't something like this be more visually intuited from a more mindfully designed set of graphical symbols rather than an often scary looking equation?

    So rather than viewing our picture-oriented intuition as an innate bug embedded in our native visual wetware of a brain, maybe we can explicitly design our linguistic tools such that this visual intuition is seen as a feature instead. Shift our view from our visual intuition being an error-prone biological burden, to it being a champion GPU-like stallion. Where we see flaws, Mother Nature saw finely-tuned instruments and sharpened tools. Let's work with Her, shall we?

    And this is why I applaud brilliantly creative efforts like this one person's series of blog posts on creating a graphical version of linear algebra similar to the circuit diagrams found in electronics. To see the concepts behind these symbols, distill out their essence, and then recast it into an intuitive picture-based language. Linear algebra is a beautifully geometric subject (and arguably the most useful), and I'm glad this person is trying to free it from its currently dry symbolic representation and definition-centric pedagogy (from which they argue is partly the result of the Bourbakian move towards abstractionism in mathematics). And through this newer visual representation, maybe even new insights could be gleaned that were not cognitively readily available before...

    So my fundamental message is thus: Our written scripts and languages are tools. We don't make tools ignoring how the end user will be using them. So why do these linguistic tools which are used not to carve wood or hammer nails, but arguably more importantly used to expand our minds and parse reality in ways that transcend our physical bodily limits, mostly ignored for improvement? We can mindfully design these tools with the end user experience in mind.

[^2]: Did you know that "as late as the 19th century, some writers suggested that negative numbers should be written as positive numbers flipped horizontally"?  See [The Guardian review](https://www.theguardian.com/science/alexs-adventures-in-numberland/2014/may/21/notation-history-mathematical-symbols-joseph-mazur?) of the book *Enlightening Symbols: A Short History of Mathematical Notation and its Hidden Powers* by Joseph Mazur. 

    Now obviously there are downsides to this using our Hindu-Arabic derived characters for our numbers (for example, 0 and 8 are symmetrical when flipped), but it's this kind of thinking that I'd like to propose in re-designing our math symbolic manipulation system to become more aligned with our visual intuitions.

[^3]: Oscar Tay, M.A. in Linguistics, *Quora* reply to the question *"[It's said written language was invented three or four times. How does Korean Hangul fit in to this?](https://qr.ae/TWy7DP)*

-----