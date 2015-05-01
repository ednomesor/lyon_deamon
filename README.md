# Lyon Deamon

Le principe de ce modèle est d'explorer les comportment sociaux dès lors qu'un [Démon de Maxwell](http://fr.wikipedia.org/wiki/D%C3%A9mon_de_Maxwell) permet d'accès a des charges sociales enviable.

## Le principe du Démon de Maxwell ##

D'après [Wikipédia](http://fr.wikipedia.org/wiki/D%C3%A9mon_de_Maxwell), "L'expérience du démon de Maxwell consiste en une boîte contenant un gaz, à deux compartiments (A et B) séparés par une porte P à l'échelle moléculaire ; un « démon » commande la porte. Le fonctionnement de la porte ne dépense pas d'énergie. Maxwell suppose, comme on commençait à l'admettre à l'époque, que le gaz est constitué de molécules en mouvement. Le démon est capable de déterminer la vitesse des molécules, et commande l'ouverture ou la fermeture de la porte en fonction de l'état des molécules."

## ODD ##
ODD is a framework to describe SMA developped from [Grimm et al. 2006](http://www.ufz.de/export/data/1/19520_ODD_Update.pdf) 


### Purpose ###
Question: What is the purpose of the model?

### Entities, state variables, and scales ###
Questions : What kinds of entities are in the model? By what state variables, or attributes, are these entities characterized? What are the temporal and spatial resolutions and extents of the model? 

### Process overview and scheduling ###
Questions : Who (i.e., what entity) does what, and in what order? When are state variables updated? How is time modeled, as discrete steps or as a continuum over which both continuous processes and discrete events can occur? Except for very simple schedules, one should use pseudo-code to describe the schedule in every detail, so that the model can be reimplemented from this code. Ideally, the pseudo-code corresponds fully to the actual code used in the program implementing the ABM. 

### Design concepts ###
Questions : There are eleven design concepts. Most of these were discussed extensively by Railsback (2001) and Grimm and Railsback (2005; Chapter. 5), and are summarized here via the following questions:   

 * **Basic principles**. Which general concepts, theories, hypotheses, or modeling approaches are underlying the model’s design?
 * **Emergence**. What key results or out puts of the model are modeled as emerging from the adaptive traits, or behaviors, of individuals?
 * **Adaptation**. What adaptive traits do the individuals have? What rules do they have for making decisions or changing behavior in response to changes in them selves or their environment? 
 * **Objectives**. If adaptive traits explicitly act to increase some measure of the individual's success at meeting some objective, what exactly is that objective and how is it measured? 
 * **Sensing**. What internal and environmental state variables are individuals assumed to sense and consider in their decisions?
 * **Stochasticity**. What processes are modeled by assuming they are random or partly random?
 * **Observation**. What data are collected from the ABM for testing, understanding, and analyzing it, and how and when are they collected?

### Initialization ###
Questions : What is the initial state of the model world, i.e., at time `t = 0` of a simulation run? 

### Input data ###
Question : Does the model use input from external sources such as data files or other models to represent processes that change over time? 

### Submodels ###
Questions : What, in detail, are the submodels that represent the processes listed in ‘Process overview and scheduling’? What are the model parameters, their dimensions, and reference values? How were submodels designed or chosen, and how were they parameterized and then tested? 