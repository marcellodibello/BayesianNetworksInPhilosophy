
**Table of contents** 
* TOC
{:toc}

# Course overview

*Bayesian Networks in Philosophy* (PHI420/PHI555, 3 credits, Spring 2021) is an exploration of the philosophical applications of Bayesian networks (perhpas more aptly called, probabilistic graphical models). The course consists of three parts (see details below): 

  1. Probability theory refresher
  2. Intro to Bayesian networks
  3. Philosophical applications 
  
### Instructor 

[Marcello Di Bello](https://isearch.asu.edu/profile/3706519) -- *email*: mdibello AT asu DOT edu

### Class meetings

Class meets every Monday, 3:00-5:45 PM

### Learning outcomes

At the completion of the course, you will have:

- mastered the basics of probability theory and Bayesian networks
- constructed a Bayesian network
- critically engaged with contemporary philosophical research on Bayesian networks 
- conducted independent research in philosophy using Bayesian networks

### Coursework and major assignments
You will be expected to: 

  - take a probability exam (Pass/Fail)
  - construct a Bayesian network about a phenomenon of interest (20% of final grade)
  - write a research paper that applies Bayesian networks to a philosophical question, broadly understood (60% of final grade)
  - participate regularly to class discussions (20% of final grade)

You are encouraged to pursue your own interests and lines of research. Emphasis is on conceptual understanding, not computations. 

#### Assignment submissions

*All assignments must be submitted in Canvas* by the due date. Please check Canvas for details. 

### Final Grade

Your final grade will be the weighted average of the letter grades you received on individual assignments. You must pass the probability exam in order to pass the course.  

# Course topics and schedule

## PART 1: Probability theory refresher 

### January 11 - Introduction

 * Course mechanics, assignments, topics
 
### January 18 - MLK day - no class
 
### January 25 and February 1

(most videos below are by [John Tsitsiklis](https://scholar.google.com/citations?user=bWTPrLEAAAAJ&hl=en) from MIT)

#### Sample space and probability axioms 

   * [Sample Space](https://www.youtube.com/watch?v=iQ2edOqEQAs&list=PLUl4u3cNGP60hI9ATjSFgLZpbNJ7myAg6&index=2)
       * Sample space, random experiments, events
   * [Sample Space Examples](https://www.youtube.com/watch?v=__T3eJtjoic&list=PLUl4u3cNGP60hI9ATjSFgLZpbNJ7myAg6&index=3)
   * [Sample Space and Counting](https://www.youtube.com/watch?v=KbB0FjPg0mw&list=EC2SOU6wwxB0uwwH80KTQ6ht66KWxbzTIo)
       * Video above by Joseph K. Blitzstein from Harvard
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
            * Set operations, intersection, union, complementation
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

### February 8

(most videos below are by [John Tsitsiklis](https://scholar.google.com/citations?user=bWTPrLEAAAAJ&hl=en) from MIT)

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
    

## PART 2: Bayesian networks 

### February 15

#### Basic idea
   - [Simple introduction to Bayesian Networks with the classic ‘Asia’ model](https://www.youtube.com/watch?v=v00gk1_DI9M)
   - [Bayesian network model for personalised COVID19 risk assessment and contact tracing](https://www.youtube.com/watch?v=3KGYuLFMRSY)
        - Videos above are by [Norman Fenton](http://probabilityandlaw.blogspot.com/) from Queen Mary University of London
        - The key message is that Bayesian networks are compact representations of joint probability distributions 
        - Bayesian networks consist of (i) a graphical part (called Directed Acyclic Graph, DAG) and probability assignments (called Conditional Probability Tables, CPTs).
   - [Naive Bayes](https://www.youtube.com/watch?v=O2L2Uv9pdDA)
        - Explanation by [Josh Starmer](https://twitter.com/joshuastarmer?lang=en) from [StatQuest](https://statquest.org/studyguides/)
        - A naive Bayesian classifier is a Bayesian network with a particular structure as explained in section 1, figure 1 of this [paper](http://www.cs.technion.ac.il/~dang/journal_papers/friedman1997Bayesian.pdf)  

        
### February 22
          

#### Confounding and Simpon's Paradox     
  - Judea Pearl's works: 
       - [The book of why, Chapters 4 and 6](http://bayes.cs.ucla.edu/WHY/) 
       - [Video](https://www.youtube.com/watch?v=ZaPV1OSEpHw)
       - [Causal Inference in Statistics (with Glymour and Jewell](http://bayes.cs.ucla.edu/PRIMER/)        
       - [Simpson'paradox](http://bayes.cs.ucla.edu/jp_home.html)

### March 1 

#### More in depth 
(videos below are by [Adnan Darwiche](https://scholar.google.com/citations?user=NzyvbZoAAAAJ&hl=en) from UCLA)
  - [Bayesian Networks: Syntax and Semantics](https://www.youtube.com/watch?v=dkjZuRBkwg8&list=PLlDG_zCuBub6ywAIrM1DfJp8xaeVjyvwx&index=5)
  - [Bayesian Networks: Independence and d-Separation](https://www.youtube.com/watch?v=oHfkTtcD5Ro&list=PLlDG_zCuBub6ywAIrM1DfJp8xaeVjyvwx&index=6)

The videos above are based on Chapter 4 of Darwiche's book, *Modeling and Reasoning with Bayesian Networks*. 

#### Other introductions to Bayesian networks 
   - [Bayesian Networks](https://www.youtube.com/watch?v=480a_2jRdK0)
      - Introduction by [Sudeshna Sarkarm](https://scholar.google.com/citations?user=AwP_bbsAAAAJ) from the Indian Institute of Technology 
   - [Bayesian networks](https://www.youtube.com/watch?v=HJ6p6bsJkXE&t=78s)
      - Introduction (video) by [Richard Neapolitan](https://scholar.google.com/citations?user=E9_aqCoAAAAJ&hl=en) from Northeastern Illinois University     
   - [Bayesian Networks](https://www.youtube.com/watch?v=5s7XdGacztw)
      - Introduction (video) by [Francisco Iacobelli](https://scholar.google.com/citations?user=XD7tOsUAAAAJ&hl=en) from Northeastern Illinois University  
   - [Bayesian Networks]() 
      - Introduction (slides) by [Pedro Domingos](https://twitter.com/pmddomingos) from the University of Washington   
   - Bayesian Networks ([part 1](https://www.cs.cmu.edu/~mgormley/courses/10601-s17/slides/lecture22-bayesnet1.pdf) and [part 2](https://www.cs.cmu.edu/~mgormley/courses/10601-s17/slides/lecture23-bayesnet2.pdf)) 
      - Introduction (slides) by [Matt Gormley](http://www.cs.cmu.edu/~mgormley/) from Carnegie Mellon University    
   - [Understanding Bayesian Networks with Examples in R](https://www.bnlearn.com/about/teaching/slides-bnshort.pdf)
       - Introduction (slides) by [Marco Scutari](https://scholar.google.com/citations?user=aDR3mgIAAAAJ&hl=en) from Istituto Dalle Molle di Studi sull'Intelligenza Artificiale 
   - [Artificial Intelligence with Bayesian Networks](https://www.youtube.com/watch?v=F34tkpJIg7w)
        - Talk (video) by Dr. Lionel Jouffe from [Bayesia](https://www.bayesia.com/)     


#### Bayesian network software
   - [Hugin](https://www.hugin.com/index.php/hugin-lite/) -- free version with limited functionality, needs Java, runs on PC, Linux and Mac
   - [OpenMarkov](http://www.openmarkov.org/users.html) -- free, needs Java, runs on both Mac and Windows
   - [JavaBayes](https://www.cs.cmu.edu/~javabayes/)
   - [BayesianFusion](https://www.bayesfusion.com/) - free, but needs Windows 
   - [Bayesia](https://www.bayesia.com/) - not free
   - [AgenaRisk](https://www.agenarisk.com/) - not free 
   
#### Benchmark examples of Bayesian networks     
   - [Small](https://www.bnlearn.com/bnrepository/discrete-small.html) (less than 20 nodes)
   - [Medium](https://www.bnlearn.com/bnrepository/discrete-medium.html) (20-50 nodes
   - [Large](https://www.bnlearn.com/bnrepository/discrete-large.html)(50-100 nodes) 
   - [Very Large](https://www.bnlearn.com/bnrepository/discrete-verylarge.html)(100-1000 nodes)
   - [Massive](https://www.bnlearn.com/bnrepository/discrete-massive.html) (more than 1000 nodes)

#### Related topics      
   - [Neural Networks](https://www.youtube.com/watch?v=CqOfi41LfDw)
        - Explanation by [Josh Starmer](https://twitter.com/joshuastarmer?lang=en) from [StatQuest](https://statquest.org/studyguides/)
        - Introduction to neural networks (as opposed to Bayesian networks) 

## PART 3: Philosophical applications 

### March 8 - Evidence assessement and legal argumentation 

  - Luc Bovens and Stephan Hartmann, [Bayesian Networks in Philosophy](https://sas-space.sas.ac.uk/1074/1/S_Hartmann_Networks.pdf)
  - Luc Bovens and Stephan Hartmann, [Bayesian Networks and the Problem of Unreliable Instruments](https://core.ac.uk/download/pdf/72823.pdf)
  - Norman Fenton, Martin Neil and David A. Lagnado, [A General Structure for Legal Arguments About Evidence
Using Bayesian Networks](http://www.eecs.qmul.ac.uk/~norman/papers/legal_arguments_for_web.pdf)
      - The paper argues for using Bayesian Networks as a framework to model legal arguments. The paper describes 
      a method for building useful legal arguments by means of Bayesisn Networks in a consistent and repeatable way. 
      - Backgroung readings
        - Pennington and Hastie, [The Story Model for Juror Decision-making](http://www.pages.drexel.edu/~shs62/cj243/juryreadings/Pennington-Story%20Model.PDF) 
        - Di Bello and Urbaniak, Legal Probabilism

### March 15 - Guest speaker: [Chad Lee-Stronach](https://philpeople.org/profiles/chad-lee-stronach), Statistical Evidence and Hidden Markov Models

This lecture is about the problem of bare statistical evidence (e.g. Smith 2017 below) as an objection to the claim put forward by legal probabilists that thresholds of legal proof can be represented by thresholds of evidential probability. Cases of bare statistical evidence should be understood as instances of Hidden Causal Markov Models. Once we understand them as such, it becomes clear that bare statistical evidence in general does not justify an assignment of probability above the relevant thresholds (or if it justifies it, then legal proof is established). In this way, legal probabilist can avoid the problem of bare statistical evidence.  

Preparatory readings:

- Martin Smith, [When Does Evidence Suffice For Conviction?](https://academic.oup.com/mind/article/127/508/1193/4555414)
- JM Joyce, [How Probabilities Reflect Evidence](https://www.semanticscholar.org/paper/HOW-PROBABILITIES-REFLECT-EVIDENCE-Joyce/6a7e396bf24e21200bb15e9593dcc2f86a05c2e4)
- Vlek et al, [A method for explaining Bayesian networks for legal evidence with scenarios](https://link.springer.com/content/pdf/10.1007%2Fs10506-016-9183-4.pdf)
- [Hidden Markov Models](https://web.stanford.edu/~jurafsky/slp3/A.pdf)


### March 22 - Guest speakers: [Alicja Kowalewska](https://www.cmu.edu/dietrich/philosophy/people/phd/alicja-kowalewska.html) and [Rafal Urbaniak](https://scholar.google.com/citations?user=LOtWV_0AAAAJ&hl=en), Coherence and Bayesian Networks

Preparatory readings:

- [Probabilistic Measures of Coherence](https://plato.stanford.edu/entries/justep-coherence/?fbclid=IwAR2NCF7UkzzN8h6S0rLUneVGneRnBgXlNMrSzrqCyk_25D23c5_O-yqVDqk#ProMeaCoh)
- Koscholke, [Evaluating Test Cases for Probabilistic Measures of Coherence](https://link.springer.com/article/10.1007/s10670-015-9734-1)
 

### Mach 29 - Guest speaker: [Stephan Hartmann](http://www.stephanhartmann.org/), Bayesian Networks in Philosophy of Science

**Note the change of time: the talk by Stephan Hartman starts at 10 AM (AZ time) and will end at 11:15 AM. Class will reconvene at 3PM and end at 4PM for a discussion among ourselves about the talk**.  

Preparatory readings:

- Dawid, Hartmann and Sprenger, [The No Alternatives Argument](https://academic.oup.com/bjps/article-abstract/66/1/213/1530635?redirectedFrom=PDF)

- Hartmann, [Bayes Nets and Rationality](http://philsci-archive.pitt.edu/16937/)

- Dardashti and Hartmann, [Assessing Scientific Theories: The Bayesian Approach](http://www.stephanhartmann.org/wp-content/uploads/2019/04/DardashtiHartmann_Assessing.pdf)

Extra readings:

- Hartman and Sprenger, [Bayesian Philosophy Of Science](http://www.laeuferpaar.de/Papers/BookFrame_v1.pdf)
   
- Hartman, [Theory reduction](http://www.stephanhartmann.org/wp-content/uploads/2016/01/Aberdeen_2.pdf)

### April 5 - Guest speaker: [Jonathan Herington](https://jherington.com/), Causal Models and Algorithmic Fairness

Preparatory readings:

- Richard Scheines, [An Introduction to Causal Inference](https://www.cmu.edu/dietrich/philosophy/docs/scheines/introtocausalinference.pdf)

- Jonathan Herington, [Measuring Fairness in an Unfair World](https://jherington.com/docs/Herington_AIES-2020.pdf)

- [Causality background](https://fairmlbook.org/causal.html)

### April 12 - Guest speaker: [Jan Sprenger](http://www.laeuferpaar.de/), Probabilistic Theory fo Causal Strength

**Note the change of time: the talk by Jan Sprenger starts at 10 AM (AZ time) and will end at 11:15 AM. Class will reconvene at 3PM and end at 4PM for a discussion among ourselves about the talk**.

Preparatory readings:

- Jan Sprenger, [Foundations of a Probabilistic Theory of Causal Strength](http://philsci-archive.pitt.edu/14108/)

- [Causality and manipulation](https://plato.stanford.edu/entries/causation-mani/)
   
### April 19 - Voting

   - [Luc Bovens](https://philpeople.org/profiles/luc-bovens) and Claus Beisbart, [Measuring voting power for dependent voters through causal models](https://www.researchgate.net/publication/225126745_Measuring_voting_power_for_dependent_voters_through_causal_models)
    

## Syllabus Disclaimer
The syllabus is a statement of intent and serves as an implicit agreement between the instructor and the student. Every effort will be made to avoid changing the course schedule but the possibility exists that unforeseen events will make syllabus changes necessary. Remember to check your ASU email and the course site often.

## Title IX
Title IX is a federal law that provides that no person be excluded on the basis of sex from participation in, be denied benefits of, or be subjected to discrimination under any education program or activity.  Both Title IX and university policy make clear that sexual violence and harassment based on sex is prohibited.  An individual who believes they have been subjected to sexual violence or harassed on the basis of sex can seek support, including counseling and academic support, from the university.  If you or someone you know has been harassed on the basis of sex or sexually assaulted, you can find information and resources at https://sexualviolenceprevention.asu.edu/faqs 

As a mandated reporter, I am obligated to report any information I become aware of regarding alleged acts of sexual discrimination, including sexual violence and dating violence.  [ASU Counseling Services](https://eoss.asu.edu/counseling) is available if you wish to discuss any concerns confidentially and privately. ASU online students may access [360 Life Services](https://goto.asuonline.asu.edu/success/online-resources.html). 
