# WEEK 1

### Approaches to Study the brain

* Experiment - observe

  * Normal brain - genes to behavior 
  * Diseased brain - toxin, drugs, lesions, mutations, degeneration

* Theory - hypothesize

  * Informatics - trends, correlations and patterns in data.

  * Theoretical neuroscience - explain data, predicts outcomes

  * Computational Neuroscience - minimal models that fits specific experimental data.

  * Applied neuroscience - use it in medicine and engineering.

* Simulation - unify

  * Consider every detail of the brain

  * Integrate data according to current knowledge

  * Fill gaps using hypotheses

##### 

##### QUIZ

##### What are the main approaches to study the brain?

* Observe via experements
* Hypothesize by creating theories 
* Unify the knowledge by simulation 

##### What is measured by experimental neuroscience?

Everything from micro-components of the cells to higher order properties such as behavior.

**Which of the following are part of theoretical neuroscience?**

* computational neuroscience: creating minimal model that fit specific experimental data 
* Informatics neuroscience: looking at trend and patterns in data

**What is the main caveat of individual research?**

Difficulty to produce experimental results

**Which of the following assertions about large scale brain mapping projects \(e.g. Allen institute, human connectome project\) are true?**

* Large scale brain mapping project data is generated using standardize methods to measure components of the cell. 
* Large scale brain mapping project data span the whole brain 
* Large scale brain mapping project data can be used for simulation neuroscience 

**Which is the best approach to study the brain?**

All approaches are extremely valuable and form a global approach to study the brain

**Why are simulations so important in engineering?**

Because they allow to bypass costly and often unfeasible run test

**Why is understanding the brain a big data problem that requires simulations?**

Because all the above interact in extremely complex ways.

#### **The principles of simulation neuroscience**

#### 1 \) Dense Reconstruction from sparse data

The first important principle is that we have to do dense reconstructions dense, very detailed reconstructions and we have to do it from spares data. So, we will forever have spares data. No matter how much data we collect, it will forever be spare in terms of experimental. So, the problem we have to solve is how do we get a complete picture from spares data . So the first principles of simulation neuroscience is we have to establish the strategy from going to a little bit of datato using whatever knowledge we have of how the pieces fit together to build algorithms and algorithmically build the circuit.

* Spares Biological Data \(ideally Strategic data\).

* Constraints and principles

* Algorithms

Random System

* Need to measure every pixel 
* no principles needed 
* Blind/ explicit reconstruction

Organized System

* Do not need to measure every pixel 
* Principles needed 
* Algorithmic reconstruction 

The challenge is to find the minimum data you need. The smallest data set, not the largest data set. The real science is to say what is the least amount of data that I need to be able to reconstruct it. That is a **compression algorithm. **To reconstruct an image, In this case you wont need to measure everything, but you will need the principles an dthat is what drives simulation neuroscience. And the you algorithmically reconstruct it.

2\) Reconstruct bottom up

* Follow biological principles 
* Build the smallest components first
* Freeze components 
* Combine components
* Validate again emergent properties 
* Never fit to emergent properties and if you have to then only the very next level up. 
* If you build it right it will automtically behave right.

  So in order to build a simulation you cannot change the biological order of it, so you should not change the brain behavior, shape or etc.

Example: The guiding principle here is that if you build it right it will automatically behave right. So you build from the bottom up. You build the components you freeze them. If this is valid in therms of the behavior even if you don't know all the pieces. But if a neuron behaves right, and you put in a circuit, you can talk about about what neurons do. If the circuit behaves right and you put it into a brain, you can talk abut what the circut does and not the brain. So you don't try and tweak the model to beahve right. If the neurons, If you build it right it automatically behaves right. The last, the third principle is that iterative reconstruction and testing. SO you get your experimental data, you get your literature, you go and find all the papers you can, you mind all the facts you possibly can, and you try and build the unifying model of a neuron.  You find the eye channels, you find the morphologies, the structures, the physiology, any data that you have about the neuron, you collect. And then the challenge is how do you package that into the simplest algorithm that will reconstruct it. Tha is consistent with all the data that you gathered?

You obtain your model and then you interrogate it anatomically, you look at it and you see: "It looks like a neuron! ". And then you simulate it to see if it behaves the correct way, as it does in the real tissue. And then you do an analysis, you do the system comparison and you get your errors.

**Iteratively reconstruct and test**

* New understanding when you  succeed

* New knowledge when you fail

What is the first principle of simulation neuroscience?

* Dense reconstruction from sparse data

Which of the following assertion about transmitting information based on random systems or on organized systems is true?

* In organized systems, because relationships exist between different parts of information you do not need to measure everything to transmit the full information. 

What is the second principle of simulation neuroscience?

* One should validate in an upward direction, validate the emerging properties of the system. 

What is the expectation of reconstruction bottom-up ?

* If you build it right, it will automatically behave corret. 

What is the third principle of simulation neuroscience?

* Iteratively reconstruct and test

Five steps of model building as guided by the third principle of simulation neuroscience:

1. Experimental data gathering/ Literature mining 
2. Build a model
3. Simulate 
4. Model validation 
5. Refinement of model 

![](/assets/Screen Shot 2017-12-24 at 8.06.54 PM.png)

##### Data strategies

The first approach to build circuits of the brain is to establish a data hierarchy and there is a reason that we actually approach simulation neuroscience at the micro circuit level.

It is because it kind of is in the middle between brain regions and the whole brain, and cells and molecules and so you actually capture how do you integrate the components into higher level components. So it is relatively simple rules for how do you approach data. You establish a data hierarchy.

Start with the Ion which are membrane protein that allow specific ions to flow through and in either directions or whichever directions, and as they try to flow through, they change the voltage of the membrane of the neuron and collectively they will shape the way that the neurons behaves.

What is the integration hierarchy from low to high, of data for simulation neuroscience?

* Ion channels are present in neurons; synaoses connect neurons; connect neurons form microcircuit

What type of data are recorded when analyzing ion channels for simulation neuroscience?

* The dynamics of their opening and closing. 
* The location of the different channels in the cell.
* The amount of current that can pass through each channel type.

Wha kind of techniques are not used to record data about whole single neurons?

* Paired recording 
* Biophysical screening 

**Informatics strategies **

The main goal for neuroinformatics is to build an infrastructure to compare experimental data with simulation data. This is essential to test and validate the results of simulation. To do so, mining of data is essential.

1. Easily compare experimental and simulation Data. 
2. Find all papers and associated data.
3. Organize the papers and the data for easy access. 
4. Ultimately have it mapped to a brain atlas. 

**Reconstruct Strategies**

1. Build components
2. Build workflows
3. Validate 

Find all your types of neurons, and then you work out how to position them together and then you find out how to connect them together and then you add the physiology and how do they behave, every neuron behaves. And then how every synapse behaves and then you have a circuit.

**Simulation strategies **

* Computing Requirements

  * Need a supercomputer.

  * Parallel code for simulation

  * Challenges  
    1. Algorithmic efficiency  
    2. Resource management  
    3. Data management

* Value of Simulations

  * Behavior as expected?

  * Reproduces biological experiments?

What is the main reason behind the need for workflows in the effort to reconstruct brain tissue?

* Because it allows to automate the testing and validation process 

Why does brain simulation need to be done on a supercomputer rather than on a grid \(an ensemble of computers connected over LAN/internet\)?

* Because the simulation would process as slow as the slowest connection. 

What is not an advantage of simulation of the brain tissue over experiments with brain tissues?

* The measurements made on virtual tissue are more valid than when experimenting on brain tissue. 

**Caveats **

1. Critical data may be missing
2. Biological data often contains mistakes 
3. Needs knowledge across many disciplines.

**Approach to study single neurons **

1. Electrical profile 
2. Morphological profile 
3. Molecular profile 

**IR-DIC stands for?**

Infrared Differential Contrast Microcopy

IR-DIC allows to get very high depth view into tissue

IR-DIC requires polarized light

**What do you need for a whole cell patch clamp?**

A microscope and a glass micropipette

What can be measured using a whole cell patch clamp - in conjunction with other techniques?

* The morphological profile, i.e the 3rd structure of a neuron.
* The electrophysiological profile, i.e a recording of the voltage of the cell under different stimuli.
* The molecular profile, i.e the expression of different genes.

Inter neurons - typically inhibitory inter neurons and PYR these are excitatory, typically parametal cells.

**Morphological profiles **

What kind of features can you get from morphological studies?

* Volume of the soma 
* Dendrites horizontal extend
* Dendrite branching angle
* Frequency of branching

The following statements about morphological studies are incorrect?

* The name of the different morphological classes were only recently defined 
* Local morphology always covers the full neuron
* Classification are based on global morphology of the cells 
* Morphological studies are only possible on complete neurons 

What can you do from the averaged features of one neuron class?

* The averaged features can be used to clone statistically similar neurons 
* The averaged features can be used to repair the morphology of sliced neurons 
* The averaged features can be used to define rules used to synthetize new neurons 



**Electrical Features**

* AP amplitude 
* AP halfwidth 
* After hyperpolorization
* Spike train accommodation

**Electrophysiological profiles **

How are the electrical types of neurons characterized using a whole cell patch-clamp experiment?

* By using multiple patterns of electrical stimuli

For a given electrical type it is...

* ... in most cases, it is possible to predict when the cell reacts with an action potential to a stimulus

From the 55 morphological types and the 11 electrical types, how many electro-morphological  types exist?

* 207 morpho-electrotypes

 



