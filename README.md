# Portafolio: Simulation of physical and not physicial systems
- Kennet Julian Rueda Espinosa
- Undergraduate program: Physics (Computer science)
- Explora UN Mundo - Group 3
- Professor: Andres Mican
- 2020-2
## About the project
This project is part of the asignature of Explora English at the National University of Colombia. I selected 6 documents between videos, books and articles which i think, are informative and useful for persons interested in simulations and modeling. I wrote a brief review or synopsis of each document. Also, i attached some simple simulations that i have make it for ilustrate part of the content. I hope you enjoy it.
*Links of each documents are atached in the tittle*

# [Synopsis: Simulation - Concepts and Applications](https://www.researchgate.net/publication/221002969_Simulation_-_Concepts_and_Applications) 

<p>This article is a review of the principal concepts related with simulations and possible fields of application. The first discussion is what a simulation is. The authors say that there is not an universal definition, in consequence, they opted to use a general concept and say that a simulation is an imitation of a system. In consequence it is necessary to talk about what a system is. Systems are collections of entities that can interact with their environment; they have input variables that are modified over the process and produce output variables. The state of a system is described by state variables which are a set of elements and variables that can describe the entities in each moment. The evolution and relations between variables can be defined throughout a model which is a simplification of a system. Models are created based on our knowledge of the real world, and in consequence follows mathematical,  physical, and biological rules. They can also be classified according to its relation with the time in static and dynamic. If the output variables are described by “exact” values we say that the model is deterministic, if the variables are given in probabilities, the model is probabilistic which is the case of stochastic models that use random variables for calculating probabilities over the time. A last classification is given by considering integer values for the output variables, which are called discrete models, if the variables take continuous values are called continuous. To end, the article proposes some examples to represent the classifications. In a predator-prey system, animals are the entities. The state variables are the number of predators and prey, and the model can be developed using, for example, experimental biological rules, or mathematicals rules for the growth in a population. This is, usually, a deterministic model which can be modeled in a discrete way.</p>

![](/images/positions_by_state.png)
---
# [Review: A Random Walk & Monte Carlo Simulation || Python Tutorial || Learn Python Programming](https://www.youtube.com/watch?v=BfS2H1y6tzQ&t=20s) 

<p>The Random walk is a mathematical modeling problem when we have to make predictions over the path that follows an object which makes successive random steps. In this video, there is a simulation of the problem made in Python by a team of graduates of Caltech who have a YouTube channel called Socratica. Socratica is a channel which is known for its high quality educational resources and this video is not an excepcion. It has a clear presentation about the problem of the “Random Walk” with a visualization of what it looks like. Also, the development line by line of the code for a MonteCarlo simulation is elegant, organized and concise, each line is explained in syntax and purpose. Besides, the video uses the code to solve a question (about the longest random walk that we can make for obtaining, on average, a final position four units further than the starting position) and proposes us to solve a related problem. This is productive and challenging. Finally, it is to highlight the artistic taste and the work of production and edition of the video that seems to emulate a futuristic scenario with a robotized voice.</p>

<p>The ease and clarity with which the content is presented, added to the good production make this video ideal to introduce those interested to the area of simulation. As an aggregate, I would recommend all the series of videos about Python. Like the video, these lessons are seven or eight minutes and have the essential points for introducing any person to this language with which we can make more complex simulations later.<p>
  
![](/images/imagerandomwalk.png)
[You can see the whole code here](/Codes/Random_Walk1.py)

---
# [Synopsis: Evacuation Modeling Trends: Basic Concepts and Modelling Methods - Enrico Ronchi and Daniel Nilsson](https://www.springer.com/gp/book/9783319207070)

<p>This article starts refuting some misconceptions about the behaviour of persons in fire emergencies: Evacuations normally occur in a rational form, panic is not the normal feeling (more normal are stress and anxiety) and people do not lose their understanding about the situation. That notion of evacuation as a rational process makes possible the construction of mathematical models for predicting results,  improving protocols, and adapting spaces. The works in Evacuation Modeling started between the 70s and 80s when the engineers realized that structures had to support the fire more than the time that people needed to evacuate. The first models utilized for calculating these times were based on the fluid dynamics when persons were considered a particle from a fluid. This type of model called the Macroscopic models does not take into account the human factors like time of reaction and decision in front of the situation. Currently most models are based in Microscopics models when the persons are modeled like individual agents which follow a determined set of rules that establish the behavior and the interactions with other person (agent-to-agent models) or with the environment (agent-to-environment model). </p>

<p>There are many representations for this agents and environments ranging from spheres for the body and squares cells for the buildings, to compositions of circles for bodies and shoulders with nodes schemes  representations for the places of the building. The quality and validation of the model is determined by the similarities of the simulations with the experimental data. The author emphasizes in the necessity or validating the model because in each simulation there are conditions which are (or not) assumed and decided by the researcher which play an important role in the results.</p>

![](/images/positions_by_state.png)
---
# [Review: What is Simulation?](https://www.youtube.com/watch?v=OCMafswcNkY&t=81s) 

<p>This video is the result of the experience of Richard Gran as Engineer in Matlab and worker of the aerospace sector.
Gran expresses the necessity of making simulations throughout examples of his career. The first one  was his work as a designer of the control system for the lunar module of Apollo missions. It was impossible to build an entire lunar module to test the systems, as it would be extremely expensive. In consequence, he organized a simulation using analog computers and a recreation of a lunar segment. Practical necessities are evident here and most of the actual technologies follow these difficulties, constructing whole systems only for make testing works is a cost that most of the enterprises can not assume.
Next example is also related to aerospace,  Gran also was the creator of the control system for the Grumman x29, an experimental airplane with a particular aerodynamic design with a feature: the airplane was inherently unstable. For this reason, the x29 could not be built or fly it without an automatic control system. He said that the design of this system was made with the same methodology of the lunar module, simulate, design, test the design in the simulation.</p>

<p>The answer to the question of title, according to him, becomes clear: simulate is “The creation of a model that can be manipulated logically to decide how the physical world works”. But, for certain people this can be inexact. Scientists consider models as simplified representations of the world and simulation as the implementation of a model in determined situations, these are the cases where it is impossible or difficult to give an exact solution, and Gran mixes both concepts without distinction. Also, he refers to Newton’s gravitational theory and the experiments of Galileo like examples of simulation, ideas that ignore the concepts of theory and analyticity.  The presentation of the doctor Gran offers a good perspective about the importance of simulation in the industry and the necessities of advances in the techniques and methods, but it  creates a debate around the question of the title, what is simulation?</p>

![](/images/lunar.jpg)
---
# [Synopsis: The Universe Is Not a Simulation, but We Can Now Simulate It ](https://www.quantamagazine.org/coder-physicists-are-simulating-the-universe-to-unlock-its-secrets-20180612/) 

<p>This article is a brief resume of the history of computer galaxy simulations and it also, makes an overview of the actual paradigms of this field. 
According to the article, the first computer simulations for the formations of galaxies were made in the 2000’s and they were a big failure. During 5 years the galaxies of the simulations were not realistic, the difficulty for work with all the interactions of the matter obliged the researchers to start working with an easier type of matter, the dark matter which in the normal hypothesis only interact gravitationally which avoids the problems of work with electromagnetic, atomic and even quantum effects. When the simulation’s  results coincided with theory, researchers started to work with visible or “normal” matter; immediately they took into account the complexity of the problem, to solve it, they simplified and divided their work. Each research group created models which included their hypothesis of the key parts of the galaxy formations. The results were also a problem, when a study convinced the groups of work with the same galaxy, all the simulations of the formation for that galaxy were different, that result was a signal of the absence of some elements in the simulations. The answer came some years ago: It was strictly necessary to include the effects of black holes and supernovas (and the superbubbles which are a combination of hundreds of supernovas) , that was a big challenge for the scientifics but they got it. Currently, simulations make realistic galaxies and offer possibilities of exploring the problems in the universe. Hypothesis of the distributions of black holes at the birth of the universe have been developed by simulations and look realistic. The existence of dark matter could be confirmed by the computers and even the conception of new theories which excluded  dark energy, like the modified Newtonian dynamics, or MOND has been developed with the computer simulations as laboratories.</p>

![](/images/universe.jpg)
---
# [Review: Hands-On Simulation Modeling with Python](https://www.amazon.com/Hands-Simulation-Modeling-Python-decision-making-ebook/dp/B087Q8YRZ3) 
<p>One of the most common problems at the moment of starting to work with simulations is the absence of theory or computational tools. Persons who have just a little background in statistics, probability or do not know simpler models usually are overwhelmed by the complexity of their models and, even if they have clear the syntax of the programming language they use, they can not present in a valid way their results. In the other extreme are the persons who have all of this methodological content clear but do not have enough practice in their programming language. The results are rough implementations with high computation times and difficulties at the moment of making changes. </p>

<p>Having those issues in mind Giuseppe Ciaburro (PhD) , who has more than 18 years of professional experience programming in R, Matlab and Python, wrote this book to offer an integral approach to the development of simulations. As its title indicates, the principal characteristic of this book is his practical methodology. Each chapter is full of examples, exercises and lines of code, the student starts programming since the first lecture and the examples are written in a clear and elegant way. Furthermore, the topics that are covered in this book provide the most common theoretical tools for creating simulations in all the levels. The first three chapters make a review over the probability theory, the statistics and stochastics models and the concept and implementations of randomness processes. With these theoretical aspects covered, the students have all the tools for work and process in an advanced form their data, they also can present their results and make inferences of them. The next four chapters covered different methods for creating simulations: Monte-Carlo method, Markov-based processes, Resampling Methods and the optimize approach, and all the mathematical aspects behind them are described in a clear language. The above is one of the most attractive aspects of this book, we can say that it is ‘self-contained’, and the people with a basic mathematical background can understand the most important aspects of the theory without having to take a course in each topic. The last three chapters show us applications of the simulations methods to financial engineering, project management and physical phenomena. </p>

<p>To end, we could say that this book is one of the most complete books in the simulations field which has a great variety of topics, and examples to put in practice all the learnings.</p>

![](/images/Amazon_Price.png)
[You can see the whole code here](/Codes/AmazonStockMontecarloSimulation.py)
