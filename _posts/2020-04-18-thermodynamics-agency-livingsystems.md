---
title: 'On Thermodynamics, Agency, and Living Systems'
date: 2020-04-18 00:00:00
featured_image: '/images/post_pics/thermodynamics_agency_livingsystems/hopf_fibration.jpg'
excerpt: Discussing the nature of Life vs. Non-Life, Abiogenesis, and the origin of a Proto-Self using concepts such as dissipative systems, toroidal geometries, and variational free energy.   
---
*Created: 2013-06-15*  
*Updated: 2020-11-08*  
*Topics: [Physics](https://mundyreimer.github.io/archive), [Mathematics](https://mundyreimer.github.io/archive), [Computer Science](https://mundyreimer.github.io/archive), [Philosophy](https://mundyreimer.github.io/archive), [Cognitive Science](https://mundyreimer.github.io/archive)*  
*Confidence: Highly Speculative*  
*Status: Still in progress* 

(Originally written on 2013-06-15.  Currently just using this to sketch my thoughts and it is still a work in progress.  Will be adding diagrams, graphs, and code when I can.)  

---

TL;DR - Discussing the nature of Life vs. Non-Life, Abiogenesis, and the origin of a Proto-Self using concepts such as dissipative systems, toroidal geometries, and variational free energy[^0]

<br/>

<center>
<a href="https://en.wikipedia.org/wiki/What_Is_Life">
    <img src="/images/post_pics/thermodynamics_agency_livingsystems/what_is_life_book.jpeg"
        width="400" 
        height="400"
        >
</a>
</center>

<br/>

To answer the question of *What is Life?* we need to address a few language quirks first, since similar to many philosophers I think a sizable majority of our problems usually derive from our underlying use of language.  Probably the most basic thing we can do to add nuance to any situation is to not necessarily classify things in binary fashion such as Living versus Non-Living, but instead think of things lying on a spectrum.  Furthermore, we can obtain additional nuance by changing our view of Life as a noun, morphing it into something more similar to that of a verb, like a process or an algorithm, or even a collection of properties which are processes themselves.  Additionally, we can view this set of properties as not needing to all be present for something to be said to be "undergoing the process of living".  It could very well be the case that any subset of these properties when present at an arbitrarily chosen anthropic time-span & measurement-contingent granularity can qualify as good enough for us at our high-level human perspective to then pattern match and recognize and say "oh, okay, that's Life!"  The entire set of living properties need not all be necessary and it may even be the case that any combinatorial subset of them is sufficient to bootstrap the others in existence.[^4]  

For right now, I'm going to focus on one of the properties which I think is the most essential, that of the ability to distinguish self from non-self.  If a system possesses a (self-organizing) mechanism that can distinguish the external environment from its own internal environment and possess this ability for some length of time, then we can say that the system persists through time and thus has a very primitive form of Identity.

So let's start with what I think of as Proto-Life or super primitive living systems.  Let's take something known as a Bernard Cell (or [Rayleigh-Bernard Convection](https://en.wikipedia.org/wiki/Rayleigh%E2%80%93B%C3%A9nard_convection)).  

<br/>

<center>
<a href="https://en.wikipedia.org/wiki/Rayleigh%E2%80%93B%C3%A9nard_convection">
    <img src="/images/post_pics/thermodynamics_agency_livingsystems/bernard_cell.jpg"
        >
</a>
</center>

<br/>

To aid your visual intuition think of a pot of boiling water on your stove.  Now take a cross-section of it.  From this perspective, we can see that as cool water is heated up from below it rises to the top, is momentarily cooled, moves to the left and the right and then sinks down below to be heated again and the cycle renewed.  


<br/>

<center>
<a href="https://en.wikipedia.org/wiki/Rayleigh%E2%80%93B%C3%A9nard_convection">
    <img src="/images/post_pics/thermodynamics_agency_livingsystems/convection_0.png"
        width="400" 
        height="400"
        >
</a>
</center>

<br/>


It is key to note that this *self-organized* behavior occurs naturally in the presence of a thermal difference (more heat at the bottom and less-so at the top), and more broadly this structure can arise in the abstract from many various potential differences of one thing being more present in one area than another.  

<br/>

<center>
<a href="https://en.wikipedia.org/wiki/Diffusion">
    <img src="/images/post_pics/thermodynamics_agency_livingsystems/diffusion_0.png"
        width="400" 
        height="400"
        >
</a>
</center>

<br/>


This is called a [dissipative system](https://en.wikipedia.org/wiki/Dissipative_system) and is essentially the 2nd Law of Thermodynamics in action.  

<br/>

<center>
<a href="https://en.wikipedia.org/wiki/Diffusion">
    <img src="/images/post_pics/thermodynamics_agency_livingsystems/DiffusionMicroMacro.gif"
        width="400" 
        height="400"
        >
</a>
</center>

<br/>

Basically, whenever you have stuff (like heat) that is clumped or bunched up in small areas relative to other areas, this stuff tends to disperse and spread out on average.

<br/>

<center>
<a href="https://en.wikipedia.org/wiki/Diffusion">
    <img src="/images/post_pics/thermodynamics_agency_livingsystems/diffusion_1.png"
        width="400" 
        height="400"
        >
</a>
</center>

<br/>

 This phenomenon comes from the *statistical* argument that we are more likely to see stuff all spread out rather than all clumped together...similar to how it's more difficult to take a picture of a group of friends all jumping in the air at once, than it is to take a picture of them all at various heights.  There are just many more different combinations or arrangements of people that consists of them jumping at various heights and only one combination in which they are all jumping in the air at once.  As such, it is statistically more likely at any arbitrary snapshot in time to see them all jumping in the air at once.

<br/>

<center>
<a href="https://en.wikipedia.org/wiki/Rayleigh%E2%80%93B%C3%A9nard_convection">
    <img src="/images/post_pics/thermodynamics_agency_livingsystems/convection_2.png"
        width="400" 
        height="400"
        >
</a>
</center>

<br/>

Anyways, what's interesting to note about this structure though is its geometry.  This cyclic upwelling from the center and sinking back down at the sides creates these two loops, and if you view this from the 3D perspective is really a donut-shaped object we call a Torus[^1].  We can see that *order and structure arises spontaneously in the presence of diffusion!*  And why?  Because it speeds up the spread of the quantity that is clumped (like thermal energy), or in other words, it is more likely for it to occur than for it not to occur.  

<br/>

<center>
<a href="https://www.pinterest.com.mx/pin/567242515552500565/?nic_v2=1a1j5R4AC">
    <img src="/images/post_pics/thermodynamics_agency_livingsystems/torus_0.gif"
        width="400" 
        height="400"
        >
</a>
</center>

<br/>

Furthermore, you often see this torus-shaped Bernard cell packed up against other Bernard cells next to each other.  

<br/>

<center>
<a href="https://en.wikipedia.org/wiki/Rayleigh%E2%80%93B%C3%A9nard_convection">
    <img src="/images/post_pics/thermodynamics_agency_livingsystems/convection_1.png"
        width="400" 
        height="400"
        >
</a>
</center>

<br/>

It is key to note that these isolated pockets of internal and external environments are naturally created in the presence of thermal differences (and more broadly-speaking, differences of things being more present in one area than another). These cells persist to the extent of metastability (a small disturbance won't erase their existence) and they also exhibit hysteresis or "lag" (which can be seen as a primitive form of physical *memory* for a system, in that the current system's state depends on its history).  And from this we will say that the system possesses a primitive form of *Identity*.  We can also call this a primitive *self-loop* if you will.  

Now if you are creative enough you can begin to see this torus-like structure throughout nature.  Whirlpools and cyclones for one.  If you also look at it carefully, any dendritic or arboreal ("tree-like") structure is also torus-like (from the side-ways perspective, similar to the cross-section of the boiling pot).  Trees in a jungle, growing plants, blood vessels, river deltas, iron filings sprinkled around a magnetic dipole, droplets of ink in water, etc, are tori nested within tori (plural of torus).  

<br/>

<center>
<a href="https://www.dailymail.co.uk/sciencetech/article-2141291/The-stunning-blood-vessels-planet-How-river-deltas-change-world--lives-500million-people-reside-shores.html">
    <img src="/images/post_pics/thermodynamics_agency_livingsystems/dendriticstructure_0.jpg"
        width="400" 
        height="400"
        >
</a>
</center>

<br/>

If we generalize, which we should since we will eventually be dealing with systems with many more variables and hence dimensions, we can have hypertori (multi-dimensional or n-dimensional tori), etc.  

<br/>

<center>
<a href="https://en.wikipedia.org/wiki/Torus">
    <img src="/images/post_pics/thermodynamics_agency_livingsystems/torus4D.gif"
        width="400" 
        height="400"
        >
</a>
</center>

<br/>

And I'm not necessarily saying that all of life is just nested tori within tori, but we can indeed more broadly have a category or family of shapes, a taxonomy of geometric objects (maybe like [Hopf fibrations](https://youtu.be/AKotMPGFJYk)?) that arise naturally in the presence of gradients (like heat flow) or differences of arrangements of stuff (potential energy).[^2]  

<br/>

<center>
<a href="https://en.wikipedia.org/wiki/Hopf_fibration">
    <img src="/images/post_pics/thermodynamics_agency_livingsystems/hopf_fibration.jpg"
        width="400" 
        height="400"
        >
</a>
</center>

<br/>

However, let's stick to the simple torus for visualization purposes for now.

Let me briefly digress into another property that might bootstrap living systems into existence:  the evolutionary process.  We can think of evolution from a very broad perspective as a process that just consists of three requirements: two strong requirements being a selection mechanism + presence of variation of choices to select from, and one weak requirement being a physical state of memory (which can be as broad as any deformation of an object...ie, something that records state).  This last point is important to remember if I later mention something about this acting as a markov blanket, or this memory state acting as an evolutionary racheting mechanism, or more importantly claiming that the memory state is the torus).

Anyways, as we can see, our selection mechanism can be quite broad.  In fact, I'd like to claim that the change in the gradient (which can be due to something as simple as a pulsating or oscillatory action) is what acts as the selection mechanism.  What can this correspond to physically?  Think of a pool of water in which you have waves lapping upon the shore, momentarily wetting it, then receeding and drying it, then wetting it, then drying it, etc.  As a wave recedes, any structures (let's assume molecules, but it can be anything) present on the shore that are not able to persist in their forms without water are eliminated from the pool of options.  This is then followed up by another wave washing over, and another and another, with each new time we get new structural options to select among, trying out or testing their hand at momentarily becoming desiccated or drying out, etc.  From just a simple oscillatory action present in the environment, we can begin the process of rolling the evoluationary dice over and over again.

<br/>

<center>
<a href="https://www.britannica.com/science/abiogenesis">
    <img src="/images/post_pics/thermodynamics_agency_livingsystems/pool_of_water.jpg"
        width="400" 
        height="400"
        >
</a>
</center>

<br/>

As always, the neat thing comes from when we generalize this notion of "waves washing upon the shore" as a gradient that changes or pulsates or oscillates in a somewhat predictable fashion.  This gradient can take the form of wet-to-dry in our pool example or this can take the form of underwater hydrothermal vents pulsating and giving brief moments of either heat or chemically-enriched broth, etc.  At this stage, all that we require is that the pulsating be "consistent enough" (we can tighten that rate empirically).  This oscillation in the gradient is like running many experiments or rolls of the dice over and over and over, to see which structures persist or not.

<br/>

<center>
<a href="https://en.wikipedia.org/wiki/Abiogenesis">
    <img src="/images/post_pics/thermodynamics_agency_livingsystems/hydrothermalvent.jpg"
        width="400" 
        height="400"
        >
</a>
</center>

<br/>

Now let's get back to the torus and the persisting of state through time, otherwise known as possessing Identity.  There's something called the [Good Regulator theorem](https://en.wikipedia.org/wiki/Good_regulator) which states that *every good regulator of a system must be a model of that system*.  This is derived by considering that under very general conditions, the entropy of the variation of the output of that system is minimized when there is a mapping from the states of the system to the states of the regulator (or in other words, the regulator is isomorphic to the system being regulated).  To again put this another way, to increase the output of a system (or more precisely, decrease its variation in output), the system must model itself.  We know it is statistically likely that the system will further increase the spread of thermal energy from the environment. We can combine this with the Free-Energy Principle[^0] which states that those systems which define their boundaries with a [Markov blanket](https://en.wikipedia.org/wiki/Markov_blanket) also try to minimize the difference between their model of the world and their sensory perception of the environment (in which this difference is called "surprise"), and is a form of error correction.  In other words, biological systems maintain their order or non-equilibrium steady-state by minimizing or restricting themselves to a limited number of states.  Formally this is an implicit minimization of *variational free energy*[^0] and for those in the field of neuroscience this is known as active inference.[^3]

<br/>

<center>
<a href="https://en.wikipedia.org/wiki/Markov_blanket">
    <img src="/images/post_pics/thermodynamics_agency_livingsystems/markovblanket.png"
        width="400" 
        height="400"
        >
</a>
</center>

<br/>

So a little less formally, what does this mean physical intuition-wise?  To further perpetuate its identity through time (ie - remain stable, or in other words, maintain homeostasis), the system of nested tori among tori must be able to stabilize the changes in the rates at which energy is passing through the system (or in the pot example, heat flowing from the bottom of the pot to the top), and in order to stabilize these changes in flow it can do one of two things.  The first is that the system can metabolize, or very generally, consume ordered structures (like sugars) to convert that to waste heat, and in the process of doing so obtain the byproduct of maintaining internal order of the system.  In other words, to increase the stability of something like a whirlpool, we can increase the flow or make it stronger.  

Essentially, biological systems maintain their internal order by furthering the disorder of their environment (such that they are similar to glorified refrigerators) and become excellent dissipative systems.  And what's amazing is that this is statistically what the environment favors according to The 2nd Law of Thermodynamics!  It's really the environment (the presence of the gradient and its changes) that drive the formation of these structures.  Thus, it would be potentially likely that the environment is also statistically favoring and driving the formation of the second thing that biological systems can do to maintain internal structure, which is *to expand itself* or in other words, begin to model the changes in the environment to a greater extent.  And because of the Good Regulator Theorem and Free-Energy Principle[^0], we know that this is also equivalent to modeling itself to finer and finer degrees of precision.  To put it simply, for a system to regulate or better control itself, it needs to model itself/environment in order to predict any disturbances or irregularities that might occur to disrupt the system.  And we know this is potentially statistically likely to occur.                  

So how can we test this?  Especially if this is an artificial system in silico, how do we think in terms of something similar to thermal energy?  Well, we can borrow some insights from machine learning.  We know that this system must model or predict its own and the environment's future states.  And we know that the concept of prediction or pattern recognition is analogous to taking a system that has a higher number of variables and reducing that system to one that has a fewer number of variables.  Finding a pattern is the same thing as finding a *regularity* in the data...a series of simple relationships.  Systems are driven to describe themselves and their environment in a few "words" as possible.  In other words, systems possess a drive to data compress!  As such, we can use tools from information theory like that of lossy vs lossless compression to start measuring the number of bits retained, lost, flipped, etc.  And concepts like error correction and prediction error fit quite nicely here.  

<br/>

<center>
<a href="https://en.wikipedia.org/wiki/Free_energy_principle">
    <img src="/images/post_pics/thermodynamics_agency_livingsystems/freeenergyprinciplecellbrain.jpg"
        width="400" 
        height="400"
        >
</a>
</center>

<br/>

Going back, what does this correspond to physically?  This higher number of variables is analogous to having a higher number of states at which that system can be arranged in.  And according to the Free-Energy principle[^0] we know systems are driven to minimize this number of internal states (because the opposite of maximizing the number of states is equivalent to disintegrating or maximally rearranging their constituent molecular parts).  And how do systems maintain this internal order?  They metabolize or consume ordered stuff!  Thus, the drive to consume ordered molecules like sugars is isomorphic to the drive to consume information or model itself / the environment!  Prediction is related to finding regularities is related to data compression is related to metabolism is related to homeostasis is related to maintaining internal order is related to persisting one's identity through time is related to increasing the spread of thermal energy from one point to another.  According to the 2nd Law this is statistically inevitable.  

From the aforementioned, you can now see how in my mind, the question of *What is Life?* is similar to the question of *What is Consciousness?* or more specifically if you'll allow me to narrow it down, is similar to the question of Agency or Awareness of the Self or Identity.  And we know empirically that we don't necessarily need brains to have very primitive forms of awareness and perception.  Evidence of learning in things without brains like amoebas (which by definition are single cellular and cannot possess neurons), means that there is something to be said about the fundamental processes underlying both questions.  We must not need to privilege brains in our explanatory frameworks of how Agency or Self-Awareness might work.  

<br/>

<center>
<a href="https://en.wikipedia.org/wiki/Slime_mold">
    <img src="/images/post_pics/thermodynamics_agency_livingsystems/slimemold_maze.gif"
        width="400" 
        height="400"
        >
</a>
</center>

<br/>

Now remember our humble little torus structure?  Instead of a thermal gradient, let's say we now have an information gradient or a flow of information from one point to another.  We can imagine the information flow from that of your sensory information into your head as a certain torus shape, or maybe some geometric shape in our taxonomy of torus-like shapes.  What's neat is that we can translate this language of shapes into the language of harmonics or resonances, where harmonics represent consistent patterns in the environment and hence stable torus structures.  Analyzing the brain from this brain rhythm or oscillatory or electrochemical neuroacoustic analysis allows us to bring in much of the existing neuroscience literature we have as well as form somewhat of a potentially interesting framework.  Similar to when a rock is dropped in the middle of a pool and the waves propagate outward, hit the perimeter, and then bounce back to interfere with the newly outgoing waves to create interference patterns, so too does the brain's rhythms do something similar.  

<br/>

<center>
<a href="https://en.wikipedia.org/wiki/Wave_interference">
    <img src="/images/post_pics/thermodynamics_agency_livingsystems/water_ripples.jpg"
        width="400" 
        height="400"
        >
</a>
</center>

<br/>

And because we know that the shape of the container and medium of propagation matters a lot to what interference patterns arise and what natural harmonics this system possesses, we can also further classify the possible shapes our tori can take (very similar to the [Chladni patterns](https://en.wikipedia.org/wiki/Ernst_Chladni#Chladni_figures) that arise when you sprinkle sand on vibrating plates, or the famous math problem, *["Can One Hear the Shape of a Drum?"](https://en.wikipedia.org/wiki/Hearing_the_shape_of_a_drum)*).

<br/>

<center>
<a href="https://pensar.com/chladni-plate/">
    <img src="/images/post_pics/thermodynamics_agency_livingsystems/chladni_plates.png"
        width="400" 
        height="400"
        >
</a>
</center>

<br/>

And the potential phenomena of our internal informational flow dynamics might be even more rich than this!  Borrowing concepts from fluid dynamics and dynamical systems theory, in addition to Bernard Cells, we can have [Karman Vortex Streets](https://en.wikipedia.org/wiki/K%C3%A1rm%C3%A1n_vortex_street), [Coandă effects](https://en.wikipedia.org/wiki/Coand%C4%83_effect), [Maragoni effects](https://en.wikipedia.org/wiki/Marangoni_effect), etc, and each of these have associated harmonics and hence metabolic geometries that characterize their internal informational processing dynamics.  

<br/>

<center>
<a href="https://en.wikipedia.org/wiki/K%C3%A1rm%C3%A1n_vortex_street">
    <img src="/images/post_pics/thermodynamics_agency_livingsystems/vortex-street-animation.gif"
        width="400" 
        height="400"
        >
</a>
</center>

<br/>

And these little internal eddy currents and miniature tori nested among tori allow us to hypothesize a few things.  Remember when I talked about the evolutionary algorithm from before only needing a selection mechanism + variation in choices + memory state?  And how this can occur any time you have a "wave-like washing upon the shore" or more broadly changes in the gradient?  These neural oscillations themselves are the waves, and hence can act as selection mechanisms selecting for miniature tori-like structures or self-loops within the brain over and over again.  

<br/>

<center>
<a href="https://en.wikipedia.org/wiki/Neural_oscillation">
    <img src="/images/post_pics/thermodynamics_agency_livingsystems/neural_oscillations.png"
        width="400" 
        height="400"
        >
</a>
</center>

<br/>

It's key to note that there are probably a multitude of tori and nested tori at any one time in one's brain, always competing and cooperating for resources, forking or coalescing (again, think whirlpools or eddy currents) and as such I also think that there are multiple miniature "selves" at any given time running on the wetware of your brain.

<br/>

<center>
<a href="https://phys.org/news/2018-07-gulf-stream-eddies-source-iron.html">
    <img src="/images/post_pics/thermodynamics_agency_livingsystems/gulfstream.jpg"
        width="400" 
        height="400"
        >
</a>
</center>

<br/>

It is only due to the fact that all these miniature selves co-inhabit the same host body and have on average access to the relatively same memories that they are all under the collective illusion that they individually are the True and only Self.  It is only from the fact that they are all in the same host body that when reflecting upon itself like looking in a mirror, it is much easier to attribute a singular Mind as responsible for everything that that body does (which is your body).  In essence, they all fall for the illusion of a being Singular Self, when in fact the 'I' contains multitudes.

<br/>

<center>
<a href="https://en.wikipedia.org/wiki/Phrenology#/media/File:Phrenology_journal_(1848).jpg">
    <img src="/images/post_pics/thermodynamics_agency_livingsystems/individual_minds.jpg"
        width="400" 
        height="400"
        >
</a>
</center>

<br/>

And it is only by deep reflection that we can hypothesize that we as a single brain are really a community of selves all vying for control and the "strength to perpetuate as the sole whirlpool in one's mind".  I think the multiple selves theory fits quite nicely as an explanatory framework for how we make choices, how we are indecisive at times, how we come to regret certain actions, how we have competing drives and motives, how we have the stories of [split-brain patients](https://en.wikipedia.org/wiki/Split-brain)(!), and the nature of dreams, etc.

And I'm not necessarily trying to portray that this is everything there is.  There can also potentially exist internal reference frame effects, where similar to relativity theory each torus is modeling/simulating what it sees to be the environment at different speeds depending upon the rate of information flow arriving at that torus. Basically, each internal metabolism/compression algorithm is running on different clock speeds, allowing effects such as boosted reference frames, time dilations, Lorentz transformations, etc.  And there can be many more effects that we aren't currently taking into account in modeling the nature of the Self (or more precisely, *Selves*).

<br/>

<center>
<a href="https://en.wikipedia.org/wiki/Time_dilation">
    <img src="/images/post_pics/thermodynamics_agency_livingsystems/time_dilation.gif"
        width="400" 
        height="400"
        >
</a>
</center>

<br/>

This is why I think current artificial neural network research should start moving towards [spiking neural network](https://en.wikipedia.org/wiki/Spiking_neural_network) architectures or more broadly the dynamical systems paradigm (like homeostatic learning) where time-varying phenomena play a role.  Not only does it fit with all of the aforementioned theory I posited, but it would also allow us to potentially create a whole new field that explains more of the higher level subjective qualia and emotions we feel by bringing in insights from such disparate fields as music theory where time-varying phenomena are directly connected to emotional expressiveness.

<br/>

<center>
<a href="https://en.wikipedia.org/wiki/Spiking_neural_network">
    <img src="/images/post_pics/thermodynamics_agency_livingsystems/spiking_nn.png"
        width="400" 
        height="400"
        >
</a>
</center>

<br/>

Now where can we start?  We know that our framework must be grounded[^3] in the laws of thermodynamics and potentially the free-energy principle framework[^0].  A good first step would be to start with defining our taxonomy of geometric objects, or alternatively, what kind of geometric spaces do these objects live in?  Is it Euclidean Space? Is it Hyperbolic Space? Does it use some Fractal Dimension?  Fleshing that out will then inform us of how the laws of thermodynamics operate on such an environment and how information can flow or propagate throughout the system.  This would then allow us to talk about saddle points, curvatures in information space, geodesics, local minima, and later on what effects (like those fluid dynamics ones from before) can we make testable physiological or behavioral predictions on.

<br/>

<center>
<a href="https://pointatinfinityblog.wordpress.com/2018/02/19/life-on-the-poincare-disk/">
    <img src="/images/post_pics/hyperbolic_geometry/poincare_disc.png"
    width="400" 
    height="400"
    >
</a>
</center>

<br/>

These geometric objects can then help us arrive at potential geometric architectures that self-organize.  Self-organization in a way can be deterministically "locked-in" further and further by the system's own creation of its interactive network of [affordances](https://en.wikipedia.org/wiki/Affordance) / [constraints](https://en.wikipedia.org/wiki/Constraint_(mathematics)) that begin to [tile](https://en.wikipedia.org/wiki/Tessellation) and constrain the future solution space of possible architectures.  Furthermore, we might begin to be able to use these self-organization algorithms as *learning* algorithms.  The state of artificial neural network architectures now are pretty much all static, rely on fixed sizes of information for input, and information is all propagated and then back-propagated at once, fixed at one speed.  There is no notion of time-varying inputs, speeds, resonances, harmonics, etc (hence my call for more spiking net research).  I argue that without the ability to handle and model asynchronous computation (which from another perspective is the ability to integrate both local and global information), we're still stuck in an old paradigm because we can't exhibit time-varying phenomena and hence lack the necessary conditions for these geometric structures like tori and self-loops to exist, restricting our architecture's ability to even possess rich higher-ordered psychological phenomena like motivation, choice, and self-awareness.[^5]

----

Resources:

[^0]: Much of this post is influenced by ideas falling underneath the general framework known as the *Free Energy Principle*.  [See my post](https://mundyreimer.github.io/blog/free-energy-principle) that reviews the history, current literature, mathematics, and philosophical implications surrounding this principle.  

[^1]: [The Shape of Space: Visualizing Surfaces & Three-Dimensional Manifolds](https://www.goodreads.com/review/show/3404405359): My review of the excellent book by [Jeffrey Weeks](https://en.wikipedia.org/wiki/Jeffrey_Weeks_(mathematician)) that discusses non-Euclidean and toroidal geometries and the topological properties associated with the surfaces of these. See my review for more information, but it's nice to note that prerequisites are kept minimal for this book. I also made [spaced-repetition flashcards](https://www.brainscape.com/p/212G3-LH-9EJ5Y) for the entire book.

[^2]: My post on the potential use of [Hyperbolic Geometry in modeling our internal mental space](https://mundyreimer.github.io/blog/hyperbolic-geometry-mental-space)

[^3]: Besides my post reviewing the FEP, for a neutral-ish perspective as well as an excellent explanation of the history and formal details of the Free-Energy Principle, I'd highly recommend a paper by Mel Andrews, [The Math is not the Territory: Navigating the Free Energy Principle](http://philsci-archive.pitt.edu/18315/). Regardless of your underlying metaphysical beliefs with respect to models, maps, and territories, I think this is one of the best places to start digging into these concepts.  Another paper that might bring clarity between different uses of Markov blankets in the philosophy of mind can be found in the paper *[The Emperor's New Markov Blankets](http://philsci-archive.pitt.edu/18467/)*. 

[^4]: Some books that I reference (from which I still have to clean up and properly cite) are Schrodinger's *[What is Life?](https://www.goodreads.com/book/show/162780.What_Is_Life_with_Mind_and_Matter_and_Autobiographical_Sketches)*, Hoffman's *[Life's Rachet](https://www.goodreads.com/book/show/16691583-life-s-ratchet)*, Strogatz's *[Sync](https://www.goodreads.com/book/show/354421.Sync)*, Loewenstein's *[Physics in Mind](https://www.goodreads.com/en/book/show/13587153)*, Mitchell's *[Complexity](https://www.goodreads.com/book/show/5597902-complexity)*, and Kauffman's *[Origins of Order](https://www.goodreads.com/book/show/783559.The_Origins_of_Order)* among a few others.

[^5]: Also special thanks to an undergrad colleague of mine, [Nicole de Silva](https://www.history.ucsb.edu/graduate-student/nicole-de-silva/).  Though our interactions were short, this article was originally inspired from an email exchange between us forcing me to distill my thoughts.  Nicole herself is a talented academic possessing an excellent mind for history, one of the most gracious people I've met, and a charmingly aesthetic individual to boot.  Also thanks to the myriad of other friends over the years who've granted me their patience during my long lectures on incredibly speculative (and perhaps crackpot?) theories and for reading and helping shape my thoughts with their questions and comments :)  