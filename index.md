
**Table of contents** 
* TOC
{:toc}

## Overview

This course is an exploration of the philosophical applications of Bayesian networks (perhpas more aptly called, probabilistic graphical models). The course consists of three parts (see details below): 

  1. Probability refresher
  2. Intro to Bayesian networks
  3. Philosophical applications 

## Coursework
To get credit for this course, students will be expected to: 

  - take a probability exam (Pass/Fail -- to obtain a pass in this exam is a necessary condition to pass the course); 
  - construct a Bayesian network about a phenomenon of interest (20% of final grade); 
  - write a research-level paper that applies a Bayesian network to a philosophical question, broadly understood (60% of final grade); and
  - partcipare regukarly to class discussions (20% of final grade).

Students are encouraged to pursue their own interest and line of research. Emphasis is on conceptual understanding rather than computations. 


## Course topics and schedule

### PART 1: Probability refresher (Weeks 1--4)

#### Sample space and probability axioms 
(most videos below are by [John Tsitsiklis](https://scholar.google.com/citations?user=bWTPrLEAAAAJ&hl=en) from MIT)
   * [Sample Space](https://www.youtube.com/watch?v=iQ2edOqEQAs&list=PLUl4u3cNGP60hI9ATjSFgLZpbNJ7myAg6&index=2)
       * Sample space, random experiments, events
   * [Sample Space Examples](https://www.youtube.com/watch?v=__T3eJtjoic&list=PLUl4u3cNGP60hI9ATjSFgLZpbNJ7myAg6&index=3)
   * [Probability Axioms](https://www.youtube.com/watch?v=pA83XtLeVig&list=PLUl4u3cNGP60hI9ATjSFgLZpbNJ7myAg6&index=4)
       * Three probability axioms
   * [Simple Properties of Probabilities](https://www.youtube.com/watch?v=WTyLg_I1oFY&list=PLUl4u3cNGP60hI9ATjSFgLZpbNJ7myAg6&index=5)
       * Lemmas/theorems that can be derived from the axioms
   * [More Properties of Probabilities](https://www.youtube.com/watch?v=N3I2ZLbh6zQ&list=PLUl4u3cNGP60hI9ATjSFgLZpbNJ7myAg6&index=6)
       * More lemmans/theorems that can be derived from the axioms
   * [A Discrete Example](https://www.youtube.com/watch?v=AsSQdpZdP8U&list=PLUl4u3cNGP60hI9ATjSFgLZpbNJ7myAg6&index=7)
   * [A Continuous Example](https://www.youtube.com/watch?v=NbYB0fiHoCs&list=PLUl4u3cNGP60hI9ATjSFgLZpbNJ7myAg6&index=8)
   * [Countable Additivity](https://www.youtube.com/watch?v=mUxg3j_h5GM&list=PLUl4u3cNGP60hI9ATjSFgLZpbNJ7myAg6&index=9)
   * [Interpretations & Uses of Probabilities](https://www.youtube.com/watch?v=uGGTX2ypzKI&list=PLUl4u3cNGP60hI9ATjSFgLZpbNJ7myAg6&index=10)
       * Frequentist vs. subjective (betting) interpretation of probability
   * Mathemathical background:
       * [Sets](https://www.youtube.com/watch?v=47W1ApSRUqs&list=PLUl4u3cNGP60hI9ATjSFgLZpbNJ7myAg6&index=12)
            * Set operations, intersectionl, union, complementation
       * [De Morgan's Laws](https://www.youtube.com/watch?v=pdR9hV8mRWE&list=PLUl4u3cNGP60hI9ATjSFgLZpbNJ7myAg6&index=13)
       * [Countable and Uncountable Sets](https://www.youtube.com/watch?v=MqocbJ-FPo0&list=PLUl4u3cNGP60hI9ATjSFgLZpbNJ7myAg6&index=19)
   * Summary of key definitions in Chapter 1, sections 1.1 and 1.2 [here](https://ocw.mit.edu/resources/res-6-012-introduction-to-probability-spring-2018/part-i-the-fundamentals/MITRES_6_012S18_Textbook.pdf)
            
#### Conditional probability and Bayes's rule
   * [Conditional Probabilities](https://www.youtube.com/watch?v=MPRKc4UPoJk&list=PLUl4u3cNGP60hI9ATjSFgLZpbNJ7myAg6&index=23)
   * [A Die Roll Example](https://www.youtube.com/watch?v=YenDB3yOfDc&list=PLUl4u3cNGP60hI9ATjSFgLZpbNJ7myAg6&index=24)
   * [Conditional Probabilities Obey the Same Axioms](https://www.youtube.com/watch?v=L_pEeYLGaP0&list=PLUl4u3cNGP60hI9ATjSFgLZpbNJ7myAg6&index=25)
   * [A Radar Example and Three Basic Tools](https://www.youtube.com/watch?v=uL31gpFdarc&list=PLUl4u3cNGP60hI9ATjSFgLZpbNJ7myAg6&index=26)
       * [First tool:The Multiplication Rule](https://www.youtube.com/watch?v=ugzs7dgQ-JE&list=PLUl4u3cNGP60hI9ATjSFgLZpbNJ7myAg6&index=27)
       * [Seciond tool: Total Probability Theorem](https://www.youtube.com/watch?v=8odFouBR2wE&list=PLUl4u3cNGP60hI9ATjSFgLZpbNJ7myAg6&index=28)
       * [Third tool: Bayes' Rule](https://www.youtube.com/watch?v=kz2tvO_ZAKI&list=PLUl4u3cNGP60hI9ATjSFgLZpbNJ7myAg6&index=29)
   * [Bayes' rule - an intuitive explanation](https://www.youtube.com/watch?v=EbyUsf_jUjk&list=PLFDbGp5YzjqXQ4oE4w9GVWdiokWB9gEpm&index=14)
       *  Video above is by [Ben Lambert](https://ben-lambert.com/) from Imperial College London 
   * [A visual guide to Bayesian thinking](https://www.youtube.com/watch?v=BrK7X_XlGB8&t=228s)
       * Interesting examples of applications of Bayes' thorem by [Julia Galef](https://en.wikipedia.org/wiki/Julia_Galef), co-founder of the [Center for Applied Rationality](https://rationality.org/)
   * [Everything You Ever Wanted to Know About Bayes' Theorem But Were Afraid To Ask](https://www.youtube.com/watch?v=BcvLAw-JRss)
   * Summary of key definitions in Chapter 1, sections 1.3 and 1.4 [here](https://ocw.mit.edu/resources/res-6-012-introduction-to-probability-spring-2018/part-i-the-fundamentals/MITRES_6_012S18_Textbook.pdf)

#### Independence
   * [A Coin Tossing Example](https://www.youtube.com/watch?v=rZKUmNvCjis&list=PLUl4u3cNGP60hI9ATjSFgLZpbNJ7myAg6&index=31)
   * [Independence of Two Events](https://www.youtube.com/watch?v=w423ypsUHf0&list=PLUl4u3cNGP60hI9ATjSFgLZpbNJ7myAg6&index=32)
   * [Independence of Event Complements](https://www.youtube.com/watch?v=JZkT3NU2mPM&list=PLUl4u3cNGP60hI9ATjSFgLZpbNJ7myAg6&index=33)
   * [Conditional Independence](https://www.youtube.com/watch?v=7B3cDe39lwY&list=PLUl4u3cNGP60hI9ATjSFgLZpbNJ7myAg6&index=34)
   * [Independence Versus Conditional Independence](https://www.youtube.com/watch?v=TAyA-rjmesQ&list=PLUl4u3cNGP60hI9ATjSFgLZpbNJ7myAg6&index=35)
   * [Independence of a Collection of Events](https://www.youtube.com/watch?v=UbQcqFH33G0&list=PLUl4u3cNGP60hI9ATjSFgLZpbNJ7myAg6&index=36)
   * [Independence Versus Pairwise Independence](https://www.youtube.com/watch?v=aJXfyfQs2Mc&list=PLUl4u3cNGP60hI9ATjSFgLZpbNJ7myAg6&index=37)
   * [Reliability](https://www.youtube.com/watch?v=UDkq_cLVSmc&list=PLUl4u3cNGP60hI9ATjSFgLZpbNJ7myAg6&index=38)
   * [The King's Sibling](https://www.youtube.com/watch?v=iPWyElxtk-8&list=PLUl4u3cNGP60hI9ATjSFgLZpbNJ7myAg6&index=39)
   * Summary of key definitions in Chapter 1, section 1.5 [here](https://ocw.mit.edu/resources/res-6-012-introduction-to-probability-spring-2018/part-i-the-fundamentals/MITRES_6_012S18_Textbook.pdf)
    
#### Other important concepts 
   - [Definition of Random Variables](https://www.youtube.com/watch?v=vfqPpai_9jI&list=PLUl4u3cNGP60hI9ATjSFgLZpbNJ7myAg6&index=50)
   - [Probability Mass Function](https://www.youtube.com/watch?v=zW1_iugJvF0&list=PLUl4u3cNGP60hI9ATjSFgLZpbNJ7myAg6&index=51)
   - [Probability distribution](https://www.youtube.com/watch?v=jbhi96p4mwI&list=PLFDbGp5YzjqXQ4oE4w9GVWdiokWB9gEpm&index=5)
       - Probability mass function (PMF) vs. probability density function (PDF)
       - [The Distribution Zoom](https://ben18785.shinyapps.io/distribution-zoo/)
   - [Marginal probability](https://www.youtube.com/watch?v=r27mouuyFQk&list=PLFDbGp5YzjqXQ4oE4w9GVWdiokWB9gEpm&index=6)
       - Joint probability vs. marginal probability, examples and general formulas 
       - Two videos above are by [Ben Lambert](https://ben-lambert.com/) from Imperial College London  
   - [Conditional probability and chain rule](https://www.youtube.com/watch?v=B020i4yW1tc)
   - [Expectation](https://www.youtube.com/watch?v=GARQ31BrKQA&list=PLUl4u3cNGP60hI9ATjSFgLZpbNJ7myAg6&index=57)    - [Joint PMFs](https://www.youtube.com/watch?v=7nu97OYx4X4&list=PLUl4u3cNGP60hI9ATjSFgLZpbNJ7myAg6&index=67)
   - Summary of key defintions in Chapter 2, sections 2.1, 2.2, 2.4 and 2.5 [here](https://ocw.mit.edu/resources/res-6-012-introduction-to-probability-spring-2018/part-i-the-fundamentals/MITRES_6_012S18_Textbook.pdf)
    

### PART 2: Bayesian Networks (Weeks 5--6)

#### Basic idea
   - [Simple introduction to Bayesian Networks with the classic ‘Asia’ model](https://www.youtube.com/watch?v=v00gk1_DI9M)
   - [Bayesian network model for personalised COVID19 risk assessment and contact tracing](https://www.youtube.com/watch?v=3KGYuLFMRSY)
        - Videos above are by [Norman Fenton](http://probabilityandlaw.blogspot.com/) from Queen Mary University of London
        - The key message here is that Bayesian networks are compact representations of joint probability distributions 
        - Bayesian networks consist of (i) a graphical part (called Directed Acyclic Graph, DAG) and probability assignments (called Conditional Probability Tables, CPTs).
          
#### More in depth (different introductions to Bayesian networks)
   - [Bayesian Networks](https://scholar.google.com/citations?user=AwP_bbsAAAAJ)
        - Introduction by [Sudeshna Sarkarm](https://scholar.google.com/citations?user=AwP_bbsAAAAJ) from the Indian Institute of Technology 
   - [Bayesian networks](https://www.youtube.com/watch?v=HJ6p6bsJkXE&t=78s)
   - Introduction by [Richard Neapolitan](https://scholar.google.com/citations?user=E9_aqCoAAAAJ&hl=en) from Northeastern Illinois University     
   - [Bayesian Networks](https://www.youtube.com/watch?v=5s7XdGacztw)
        - Introduction by [Francisco Iacobelli](https://scholar.google.com/citations?user=XD7tOsUAAAAJ&hl=en) from Northeastern Illinois University  
  - [Bayesian Networks](http://www.cs.technion.ac.il/~dang/journal_papers/friedman1997Bayesian.pdf) 
        - Introduction (slides) by [Pedro Domingos](https://twitter.com/pmddomingos) from the University of Washington   
  - Bayesian Networks ([part 1](https://www.cs.cmu.edu/~mgormley/courses/10601-s17/slides/lecture22-bayesnet1.pdf) and [part 2](https://www.cs.cmu.edu/~mgormley/courses/10601-s17/slides/lecture23-bayesnet2.pdf)) 
  - Introduction (slides) by [Matt Gormley](http://www.cs.cmu.edu/~mgormley/) from Carnegie Mellon University
  - [Understanding Bayesian Networks with Examples in R](https://www.bnlearn.com/about/teaching/slides-bnshort.pdf)
        - Introduction (slides) by [Marco Scutari](https://scholar.google.com/citations?user=aDR3mgIAAAAJ&hl=en) from Istituto Dalle Molle di Studi sull'Intelligenza Artificiale 
      
     
#### Related topics      
   - [Neural Networks](https://www.youtube.com/watch?v=CqOfi41LfDw)
           - Explanation by [Josh Starmer](https://twitter.com/joshuastarmer?lang=en) from [StatQuest](https://statquest.org/studyguides/)
           - Introduction to neural networks (as opposed to Bayesian networks) 
     - [Naive Bayes](https://www.youtube.com/watch?v=O2L2Uv9pdDA)
           - Explanation by [Josh Starmer](https://twitter.com/joshuastarmer?lang=en) from [StatQuest](https://statquest.org/studyguides/)
           - A naive Bayesian classifier is a Bayesian network with a particular structure as explained in section 1, figure 1 of this [paper](http://www.cs.technion.ac.il/~dang/journal_papers/friedman1997Bayesian.pdf)  
#### Bayesian network software
   - [JavaBayes](https://www.cs.cmu.edu/~javabayes/)
   - [Bayesia](https://www.bayesia.com/)
   - [AgenaRisk](https://www.agenarisk.com/)
   - [BayesianFusion](https://www.bayesfusion.com/)

#### Benchmark examples of Bayesian networks     
   - [Small](https://www.bnlearn.com/bnrepository/discrete-small.html) (less than 20 nodes)
   - [Medium](https://www.bnlearn.com/bnrepository/discrete-medium.html) (20-50 nodes
   - [Large](https://www.bnlearn.com/bnrepository/discrete-large.html)(50-100 nodes) 
   - [Very Large](https://www.bnlearn.com/bnrepository/discrete-verylarge.html)(100-1000 nodes)
   - [Massive](https://www.bnlearn.com/bnrepository/discrete-massive.html) (more than 1000 nodes)

### PART 3: Philosophical applications (Weeks 7--14)

#### Evidence assessment
   
   - Luc Bovens and Stephan Hartmann, [Bayesian Networks in Philosophy](https://sas-space.sas.ac.uk/1074/1/S_Hartmann_Networks.pdf)
   - Luc Bovens and Stephan Hartmann, [Bayesian Networks and the Problem of Unreliable Instruments](https://core.ac.uk/download/pdf/72823.pdf)
 
#### Legal argumentation  

  - Norman Fenton, Martin Neil and David A. Lagnado, [A General Structure for Legal Arguments About Evidence
Using Bayesian Networks](https://www.ucl.ac.uk/lagnado-lab/publications/lagnado/legal_arguments.pdf)
      - The paper argues for using Bayesian Networks as a framework to model legal arguments. The paper describes 
      a method for building useful legal arguments by means of Bayesisn Networks in a consistent and repeatable way. 
      - Backgroung readings
        -  The Story Model 
      
      - Fenton, Biedermann, Lagnado, Vlek
   
#### Coherence
   
   - Rafal Urbaniak?

#### Causality

   - [Causality and manipulation](https://plato.stanford.edu/entries/causation-mani/)
   - Judeal Pearl's works: 
        - [Simposon'paradox](http://bayes.cs.ucla.edu/jp_home.html)
        - [The book of why](http://bayes.cs.ucla.edu/WHY/) 
        - [video](https://www.youtube.com/watch?v=ZaPV1OSEpHw)
  - [J. Sprenger](http://www.laeuferpaar.de/index.html), [Foundations of a Probabilistic Theory of Causal Strength](http://philsci-archive.pitt.edu/14108/7/GradedCausation-v7.pdf)

#### Fairness

   - [causality background](https://fairmlbook.org/causal.html)
   - Jonathan Herington, [Measuring Fairness in an Unfair World](https://jherington.com/docs/Herington_AIES-2020.pdf)

#### Voting, judgment aggregation

   - [Luc Bovens](https://philpeople.org/profiles/luc-bovens) and Claus Beisbart, [Measuring voting power for dependent voters through causal models](https://www.researchgate.net/publication/225126745_Measuring_voting_power_for_dependent_voters_through_causal_models)
    
#### Philosophy of science 

   - Discussion of some work by Stephan Hartman 
        - [Bayesian Philosophy Of Science](http://www.laeuferpaar.de/Papers/BookFrame_v1.pdf)
        - [theory reduction](http://www.stephanhartmann.org/wp-content/uploads/2016/01/Aberdeen_2.pdf)
        - other [topics](http://www.stephanhartmann.org/publications/): judgement aggregation, deliberation, truth, democracy
