---
title: projects
subtitle: 
description: 
featured_image: /images/profilepic/geometry_of_logic_2.jpg
---

## - newer stuff -

Some recent projects that I've worked on...

*For a more frequently updated list of projects, see [my Github repo here](https://github.com/mundyreimer).

---

<a href="http://math2code.com/">
    <img src="/images/project_pics/math2code.png"
        style="float: right"
        width="350" 
        height="300"
        >
</a>

### math to code converter {#math2code} 

[Math2Code](http://math2code.com/): Engineered the core architecture and [led a team of fellow machine learning & data science students](http://math2code.com/about) in designing a web application that takes in a *picture* of a math equation / notation and automatically converts that into its Python/Numpy equivalent of *working code*.  Presented a working version and demo in front of a VC panel along with 5 other finalists and their products from [our masters program](https://www.usfca.edu/arts-sciences/graduate-programs/data-science).  Code documentation [found here](https://mundyreimer.github.io/math2code_sphinx_docs/).

Used: Optical Character Recognition (OCR), Mathematical Syntax Analysis, Lexical Analysis & Parsing, Code-Generation & Templating, AWS (S3, RDS, ElasticBeanstalk, CodePipeline, Route53), Flask, Bootstrap4, Jinja2, Sphinx Documentation, Javascript, HTML, CSS, Google Analytics, Git Continuous Integration   

---

<a href="https://github.com/mundyreimer/RL-Sepsis-Prediction">
    <img src="/images/project_pics/sepsis_timeseries.png"
        style="float: right"
        width="400" 
        height="350"
        >
</a>

### medical diagnosis {#medicaldiagnosis} 

 [Built a custom reinforcement learning environment + series of models](https://github.com/mundyreimer/RL-Sepsis-Prediction) that predicts and classifies hospital-acquired Sepsis (aka - [blood-poisoning](https://en.wikipedia.org/wiki/Sepsis)) in patients at each hour using multivariate timeseries data of patient vital signs and lab results (ex - heart rate, O2 saturation, temperature, mean arterial pressure, serum white blood cell count, etc) using [OpenAI Gym](https://github.com/openai/gym).  
 
 [Sepsis](https://en.wikipedia.org/wiki/Sepsis) is a life-threatening condition that arises when the body's response to infection causes injury to its tissues and organs. It is the most common cause of death for people who have been hospitalized, and results in a $15.4 billion annual cost in the US. Early detection and treatment are essential for prevention and a 1-hour delay in antibiotic treatment can lead to 4% increase in hospital mortality. 
 
 Project was built with my multi-talented partner, [Zachary Barnes](https://zacharybarnes.org/about/). Some of the algorithms and policies we tried include: Proximal Policy Optimization Algorithm + Multi-Layer Perceptron, Proximal Policy Optimization Algorithm + LSTM, Synchronous, deterministic variant of Asynchronous Advantage Actor Critic + LSTM, and Deep Q-Networks + LSTM. [See here](https://github.com/mundyreimer/RL-Sepsis-Prediction) for our code, analysis, and tutorial on how to setup and run this on your local machine.

 Used: OpenAI Gym, TensorFlow, Bayesian Optimization, Keras Preprocessing

---

<a href="https://towardsdatascience.com/analyzing-microbiome-data-320728b56b8e">
    <img src="/images/project_pics/geneticalignment.jpeg"
        style="float: right"
        width="350" 
        height="300"
        >
</a>

### bioinformatics {#bioinformatics} 

 As part of our [Genomic Data Science Series](https://towardsdatascience.com/analyzing-microbiome-data-320728b56b8e) of tutorials, my friend [Nick Parker](https://www.linkedin.com/in/nicholas-j-parker) and I analyzed microbiome genetic sequencing data from simple swabs of surfaces in different cities to reverse engineer the location of where these swabs came from without knowing the location beforehand.  We investigated the genetic differences of these communities of microorganisms using unsupervised machine learning and visualization methods based on various [dimensionality reduction techniques](https://towardsdatascience.com/visualizing-high-dimensional-microbiome-data-eacf02526c3a).

 Used:  Uniform Approximation and Projection (UMAP), t-Distributed Stochastic Neighbor Embedding (t-SNE), Principal Component Analysis (PCA) 

---

<a href="https://github.com/mundyreimer/argo_sensor_clustering">
    <img src="/images/project_pics/argo_clustering.png"
        style="float: right"
        width="350" 
        height="300"
        >
</a>

### oceanography {#oceanography} 

 [Project Argo](https://github.com/mundyreimer/argo_sensor_clustering):  Built various machine learning models such as spectral clustering, k-means, & gaussian mixture models ran on PySpark's distributed computing framework to cluster temperature profiles of the fleet of [Argo floating buoys](https://en.wikipedia.org/wiki/Argo_(oceanography)) around the world.  This network of floats monitors temperature, salinity, currents, and bio-optical properties of the world's oceans, providing sensor measurements for climate and oceanographic research.  [Data set found here](http://www.argo.ucsd.edu/Argo_data_and.html).  Our team's initial project [slide-deck found here](https://docs.google.com/presentation/d/1yQh4USQ-taN2zQ36ukN4ExVCNp2EwumFjSiDIEPRv0s/edit?usp=sharing).  

 Used:  PySpark, AWS EMR/S3, Spectral Clustering, K-Means, Gaussian-Mixture Models, PCA

---

<a href="https://github.com/mundyreimer/iambic_songs">
    <img src="/images/project_pics/iambic_pentameter.jpeg"
        style="float: right"
        width="400" 
        height="350"
        >
</a>

### music & linguistics {#musiclinguistics} 

[Experimented with different machine learning classifiers](https://github.com/mundyreimer/iambic_songs) for determining iambic pentameter in song lyrics and sonnets.  [Iambic Pentameter](https://en.wikipedia.org/wiki/Iambic_pentameter) is a type of rhythm or meter in which five small groups of syllables called *Iambs* or "feet", which in English are unstressed followed by stressed syllables, are found coupled together.  Poem and sonnet data were obtained and cleaned from a variety of sources like Shakespeare, Keats, Frost, Shelley, and Jackson -scraped texts available on the web, while songs from artists such as Taylor Swift and the Backstreet Boys were obtained from [Data.World](https://data.world/).  

Used:  Text-Parsing, Natural Language Processing, Logistic Regression, Step-Wise Regression, Akaike Information Criteria + Bayesian Information Criteria, Wald Test, Deviance Chi-Squared Test, Cross-Validation, DFFITS, Cook's Distance, Variance Inflation Factor, ROC Curves 

---

<a href="https://github.com/mundyreimer/school_donations_project">
    <img src="/images/project_pics/donorschoose.jpeg"
        style="float: right"
        width="350" 
        height="300"
        >
</a>

### charity {#charity} 

[Designed a recommendation system](https://github.com/mundyreimer/school_donations_project) in conjunction with PySpark's Distributed Computing framework that matches classroom charity projects (teachers and their classroom requests) to the most probable donors nationwide.  [DonorChoose.org](https://www.donorschoose.org/about) in partnership with Google helped provide this [data set](https://www.kaggle.com/donorschoose/io) freely available on Kaggle.  Our team's [project slide-deck can be found here](https://docs.google.com/presentation/d/1FJU4YzjeObEk91HBzrgQ4pBWyNjErIMun06r4PqKwWI/edit?usp=sharing).

Used:  PySpark, AWS EMR/S3, Plotly

---

<a href="https://github.com/mundyreimer/dark_market_ml">
    <img src="/images/project_pics/darkmarketcocaine.png"
        style="float: right"
        width="375" 
        height="325"
        >
</a>

### dark web markets {#darkweb} 

[Dark Market Cocaine Price Prediction](https://github.com/mundyreimer/dark_market_ml): Used various machine learning models to predict the bitcoin price of dark market cocaine.  The [data set](https://www.kaggle.com/everling/cocaine-listings) was scraped by a third party and contains approximately 1,400 standardized product listings from Dream Market's *Cocaine* category.  Our team's [project slide-deck can be found here](https://docs.google.com/presentation/d/1adchsYpdnYrKG_umUR0ZynxtBRWPtUcGAgySLA2iRbA/edit?usp=sharing).

Used:  Text Extraction, Feature Engineering, Simple Linear Regression, LASSO Regression (L1), Ridge Regression (L2), Random Forest Regressor, Cross-Validation, Scikit-learn's Data Pipeline

---

## - older stuff -

A hodge-podge of former stuff that I've been involved in...

*(I mainly use this page to connect all the disparate links on the interwebs to one central location)*

---

<a href="https://www.researchgate.net/publication/325676679_Computational_Model_of_Induced_Alteration_of_Synaptic_Activity_in_Medial_Pre-Frontal_Cortex_Mechanistic_Implications_for_Schizophrenia_Psychosis">
    <img src="/images/project_pics/spikingneurons.png"
        style="float: right"
        width="375" 
        height="325"
        >
</a>

### computational neuroscience {#computationalneuroscience} 

[Built and ran simulations](https://github.com/mundyreimer/spiking_neuralnet) of a spiking neural network modeled with endocannabinoid retrograde signaling, GABA-mediated inhibitory, and excitatory Glutamate pathways found in the medial prefrontal cortex of mice.  Attempted to investigate the changes in synaptic activity and firing patterns associated with cannabis use, brain development, and psychosis.  This was done at the Hungarian Academy of Science as part of the Theoretical Neuroscience and Complex Systems group ran by Dr. Péter Érdi and mentored by both Dr. Zoltán Somogyvári and Mihály Bányai.  See my [undergraduate honors thesis here](https://www.researchgate.net/publication/325676679_Computational_Model_of_Induced_Alteration_of_Synaptic_Activity_in_Medial_Pre-Frontal_Cortex_Mechanistic_Implications_for_Schizophrenia_Psychosis).  

I also took part in the separate [BSCS program](http://www.bscs-us.org/) studying neuroscience, cognitive science, and philosophy (as well as the Hungarian language) at Eötvös Loránd University.  This experience allowed me to study, live, and explore Budapest and other European countries ([my old travel blog can be found here](http://baskinginbudapest.blogspot.com/)). 

Used:  MATLAB, Spiking Neural Networks (from scratch)

---

<a href="https://www.researchgate.net/publication/325676679_Computational_Model_of_Induced_Alteration_of_Synaptic_Activity_in_Medial_Pre-Frontal_Cortex_Mechanistic_Implications_for_Schizophrenia_Psychosis">
    <img src="/images/project_pics/ecb_transmission.png"
        style="float: right"
        width="350" 
        height="300"
        >
</a>

### electrophysiology {#electrophysiology} 

Researched endocannabinoid signaling mechanisms through recording and analyzing the electrical activity of populations of neurons in the brain slices of mice as part of the Korzus lab under the excellent mentorship of Dr. Jonny Lovelace.  Also wrote a paper and did [my undergraduate honors thesis](https://books.google.com/books/about/Computational_Model_of_Induced_Alteratio.html?id=SjZlswEACAAJ) that is now preserved in the school library's cold dark basement.

Used:  Population-level Electrophysiological Recording, MATLAB, ANOVA, Immunohistochemistry, Neuropharmacology, Behavioral Experiments

---

<a>
    <img src="/images/project_pics/MCP_neuron.png"
        style="float: right"
        width="350" 
        height="300"
        >
</a>

### neural networks {#neuralnetworks} 

Gave talks about the mathematics of neural nets and tapped into the collective hive-mind of people writing proofs.  These [Pacific Summer Unsolved Math Seminars](https://sites.google.com/site/fullertoncollegemathevents/) are ran by [Dr. Dana Clahane](http://staffwww.fullcoll.edu/dclahane/index.html), a kind-hearted and inspiring mathematician who works on cultivating the mathematical curiosity in the surrounding Fullerton, CA community.  He hosts talks given by both students, colleagues, and professional mathematicians.  He also heads the local community college Putnam exam math training on a volunteer basis.

Used:  LaTeX, Mathematical Proofs, Classical Neural Networks

---

<a href="https://www.researchgate.net/publication/265531333_Steric_Interactions_between_sp_and_sp_3_Carbons_in_Acyclic_Alkynes_and_Nitriles">
    <img src="/images/project_pics/synclinal.png"
        style="float: right"
        width="375" 
        height="325"
        >
</a>

### theoretical chemistry {#theoreticalchemistry} 

Explored stable molecular geometries and the steric interactions of sp and sp3 carbons in acyclic alkynes and nitriles as part of a group led by Dr. Thomas Morton.  [Performed the data analysis and wrote the methods and results sections of the paper](https://www.researchgate.net/publication/265531333_Steric_Interactions_between_sp_and_sp_3_Carbons_in_Acyclic_Alkynes_and_Nitriles) which was then [published in the undergraduate research journal](https://pdfs.semanticscholar.org/3e22/71786f54953a6d67e220158a3a8f5c138899.pdf) and presented in the symposium talks and poster sessions.   

Used:  Ab Initio Geometric Optimization Methods, sp-sp3 Synclinal + Antiperiplanar Interaction Analysis

---

<a>
    <img src="/images/project_pics/spidervenom.png"
        style="float: right"
        width="375" 
        height="325"
        >
</a>

### neuropharmacology {#neuropharmacology} 

Studied the evolution of neurotoxin proteins in Agelenopsis aperta (the desert grass / funnel weaving spider) under the guidance of Dr. Michael Adams.  Also [assisted in the research](https://escholarship.org/uc/item/3162w51t#page-1) of Dr. Do Hyoung Kim by dissecting fruit fly brains(!) as part of the effort to analyze the peptidergic neural networks underlying ecdysis.  Provided additional help in the milking of neurotoxins produced by the emerald jewel wasp used to make zombie cockroaches ([from which the wasp parasitically reproduces via the cockroaches in the style of the classic Alien movies!](https://youtu.be/qN2XMyxAs5o))   

Used: Immunohistochemistry, Western Blotting, Proteomics, Molecular Biology methods, Invertebrate dissection

---

<a>
    <img src="/images/project_pics/wuschelgeneplant.jpeg"
        style="float: right"
        width="350" 
        height="300"
    >
</a>

### genetics {#genetics} 

Learned common molecular biology and genetics techniques while studying the roles of the agamous transcription factor & wuschel genes in floral stem cell maintenance of the Arabidopsis thaliana (mustard plant) in [Dr. Xuemei Chen](https://iigb.ucr.edu/xchen/)'s lab under the excellent guidance of Rae Yumul.  

Used: PCR, Primer Design, Illumina Sequencing, other basic molecular biology/genetic protocols  

---

<a href="https://pigeonrat.psych.ucla.edu/pigeons/">
    <img src="/images/project_pics/pigeonrat.jpg"
        style="float: right"
        width="350" 
        height="300"
        >
</a>

### behavioral neuroscience {#behavioralneuroscience} 

As part of the [UCLA Comparative Cognition Lab](https://pigeonrat.psych.ucla.edu/) directed by Dr. Aaron Blaisdell, I learned about reward probability and behavioral variability by building my own operant conditioning chamber ("[Skinner box](https://en.wikipedia.org/wiki/Operant_conditioning_chamber)"), [feeding rats cocoa puffs](https://escholarship.org/uc/item/2182x9bc), and [teaching pigeons video games](https://pigeonrat.psych.ucla.edu/pigeons/) :)

Used: Behavioral Experimentation, Instrumental + Operant Conditioning Protocols

---
