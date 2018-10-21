---
title: The Master Algorithm - How the Quest for the Ultimate Learning Machine Will Remake Our World
category: books
permalink: /:categories/:title/
author:  Pedro Domingos
layout: bookpost
tags:
- booknotes
---

>  Symbolists view learning as the inverse of deduction and take ideas from philosophy, psychology, and logic. Connectionists reverse engineer the brain and are inspired by neuroscience and physics. Evolutionaries simulate evolution on the computer and draw on genetics and evolutionary biology. Bayesians believe learning is a form of probabilistic inference and have their roots in statistics. Analogizers learn by extrapolating from similarity judgments and are influenced by psychology and mathematical optimization.

>  Read mlre into inverse deduction.

>  An algorithm is a sequence of instructions telling a computer what to do.

>  The second simplest algorithm is: combine two bits. Claude Shannon, better known as the father of information theory, was the first to realize that what transistors are doing, as they switch on and off in response to other transistors, is reasoning. (That was his master’s thesis at MIT—the most important master’s thesis of all time.) If transistor A turns on only when transistors B and C are both on, it’s doing a tiny piece of logical reasoning. If A turns on when either B or C is on, that’s another tiny logical operation.

>  Believe it or not, every algorithm, no matter how complex, can be reduced to just these three operations: AND, OR, and NOT. Simple algorithms can be represented by diagrams, using different symbols for the AND, OR, and NOT operations.

>  Michelangelo said that all he did was see the statue inside the block of marble and carve away the excess stone until the statue was revealed. Likewise, an algorithm carves away the excess transistors in the computer until the intended function is revealed, whether it’s an airliner’s autopilot or a new Pixar movie.

>  Learning algorithms are the seeds, data is the soil, and the learned programs are the grown plants.

>  This is because computer science has traditionally been all about thinking deterministically, but machine learning requires thinking statistically. If a rule for, say, labeling e-mails as spam is 99 percent accurate, that does not mean it’s buggy; it may be the best you can do and good enough to be useful.

>  With Google’s annual revenue of $ 50 billion, every 1 percent improvement in click prediction potentially means another half billion dollars in the bank,

>  new type of network effect takes hold: whoever has the most customers accumulates the most data, learns the best models, wins the most new customers, and so on in a virtuous circle (or a vicious one, if you’re the competition).

>  To see the future of science, take a peek inside a lab at the Manchester Institute of Biotechnology, where a robot by the name of Adam is hard at work figuring out which genes encode which enzymes in yeast.

>  In contrast, President Obama hired Rayid Ghani, a machine-learning expert, as chief scientist of his campaign, and Ghani proceeded to put together the greatest analytics operation in the history of politics. They consolidated all voter information into a single database; combined it with what they could get from social networking, marketing, and other sources; and set about predicting four things for each individual voter: how likely he or she was to support Obama, show up at the polls, respond to the campaign’s reminders to do so, and change his or her mind about the election based on a conversation about a specific issue. Based on these voter models, every night the campaign ran 66,000 simulations of the election and used the results to direct its army of volunteers: whom to call, which doors to knock on, what to say.

>  There’s a further twist: once a learned program is deployed, the bad guys change their behavior to defeat it. This contrasts with the natural world, which always works the same way. The solution is to marry machine learning with game theory, something I’ve worked on in the past: don’t just learn to defeat what your opponent does now; learn to parry what he might do against your learner. Factoring in the costs and benefits of different actions, as game theory does, can also help strike the right balance between privacy and security.

>  The question then becomes: How weak can the assumptions be and still allow all relevant knowledge to be derived from finite data? Notice the word relevant: we’re only interested in knowledge about our world, not about worlds that don’t exist.

>  Here, then, is the central hypothesis of this book: All knowledge—past, present, and future—can be derived from data by a single, universal learning algorithm.

>  In April 2000, a team of neuroscientists from MIT reported in Nature the results of an extraordinary experiment. They rewired the brain of a ferret, rerouting the connections from the eyes to the auditory cortex (the part of the brain responsible for processing sounds) and rerouting the connections from the ears to the visual cortex. You’d think the result would be a severely disabled ferret, but no: the auditory cortex learned to see, the visual cortex learned to hear, and the ferret was fine.

>  Thus it seems that evolution kept the cerebellum around not because it does something the cortex can’t, but just because it’s more efficient.

>  All information in the brain is represented in the same way, via the electrical firing patterns of neurons. The learning mechanism is also the same: memories are formed by strengthening the connections between neurons that fire together, using a biochemical process known as long-term potentiation.

>  Either way, if we implement the brain in a computer, that algorithm can learn everything we can. Thus one route—arguably the most popular one—to inventing the Master Algorithm is to reverse engineer the brain.

>  Life’s infinite variety is the result of a single mechanism: natural selection. Even more remarkable, this mechanism is of a type very familiar to computer scientists: iterative search, where we solve a problem by trying many candidate solutions, selecting and modifying the best ones, and repeating these steps as many times as necessary. Evolution is an algorithm. Paraphrasing Charles Babbage, the Victorian-era computer pioneer, God created not species but the algorithm for creating species.

>  How much of the character of physical law percolates up to higher domains like biology and sociology remains to be seen, but the study of chaos provides many tantalizing examples of very different systems with similar behavior, and the theory of universality explains them.

>  Perhaps, then, everything that exists is the progressive solution of an overarching optimization problem, and the Master Algorithm follows from the statement of that problem.

>  In his book Consilience, the distinguished biologist E. O. Wilson makes an impassioned argument for the unity of all knowledge, from science to the humanities. The

>  Bayes’ theorem is a machine that turns data into knowledge. According to Bayesian statisticians, it’s the only correct way to turn data into knowledge.

>  A problem is in P if we can solve it efficiently, and it’s in NP if we can efficiently check its solution. The famous P = NP question is whether every efficiently checkable problem is also efficiently solvable.

>  One definition of artificial intelligence is that it consists of finding heuristic solutions to NP-complete problems. Often, we do this by reducing them to satisfiability, the canonical NP-complete problem: Can a given logical formula ever be true, or is it self-contradictory? If

>  The Master Algorithm is for induction, the process of learning, what the Turing machine is for deduction.

>  Marvin Minsky, an MIT professor and AI pioneer, is a prominent member of this camp. Minsky is not just skeptical of machine learning as an alternative to knowledge engineering, he’s skeptical of any unifying ideas in AI. Minsky’s theory of intelligence, as expressed in his book The Society of Mind, could be unkindly characterized as “the mind is just one damn thing after another.” The Society of Mind is a laundry list of hundreds of separate ideas, each with its own vignette.

>  machine learning speaks probability, and knowledge engineering speaks logic.

>  Most science consists of Brahe-and Kepler-like work; Newton moments are rare. Today, big data does the work of billions of Brahes, and machine learning the work of millions of Keplers. If—let’s hope so—there are more Newton moments to be had, they are as likely to come from tomorrow’s learning algorithms as from tomorrow’s even more overwhelmed scientists, or at least from a combination of the two.

>  To use a technology, we don’t need to master its inner workings, but we do need to have a good conceptual model of it.

>  Every transaction works on two levels: what it accomplishes for you and what it teaches the system you just interacted with.

>  A theory is a set of constraints on what the world could be, not a complete description of it.

>  rival schools of thought that exist within machine learning. The main ones are the symbolists, connectionists, evolutionaries, Bayesians, and analogizers. Each

>  Pundits, lawyers, and mathematicians are rationalists; journalists, doctors, and scientists are empiricists.

>  The rationalist likes to plan everything in advance before making the first move. The empiricist prefers to try things and see how they turn out.

>  The “no free lunch” theorem is a lot like the reason Pascal’s wager fails.

>  This was a remarkably sophisticated argument for the time, but as Diderot pointed out, an imam could make the same argument for believing in Allah. And if you pick the wrong god, the price you pay is eternal hell.

>  In ordinary life, bias is a pejorative word: preconceived notions are bad. But in machine learning, preconceived notions are indispensable; you can’t learn without them. In fact, preconceived notions are also indispensable to human cognition, but they’re hardwired into the brain, and we take them for granted. It’s biases over and beyond those that are questionable.

>  Newton’s Principle: Whatever is true of everything we’ve seen is true of everything in the universe.

>  The key is to realize that induction is just the inverse of deduction, in the same way that subtraction is the inverse of addition, or integration the inverse of differentiation.

>  Most famously, integrating the derivative of a function only recovers the function up to a constant.

>  More generally, inverse deduction is a great way to discover new knowledge in biology, and doing that is the first step in curing cancer. According to the Central Dogma, everything that happens in a living cell is ultimately controlled by its genes, via the proteins whose synthesis they initiate.

>  One salient question is how to pick the best attribute to test at a node.

>  So to learn a good decision tree, we pick at each node the attribute that on average yields the lowest class entropy across all its branches, weighted by how many examples go into each branch.

>  Having a branch for each value of an attribute is fine if the attribute is discrete, but what about numeric attributes?

>  A simple solution is to pick a few key thresholds by entropy and use those.

>  The symbolists’ core belief is that all intelligence can be reduced to manipulating symbols.

>  The psychologist David Marr argued that every information processing system should be studied at three distinct levels: the fundamental properties of the problem it’s solving; the algorithms and representations used to solve it; and how they are physically implemented.

>  Hebb’s rule, as it has come to be known, is the cornerstone of connectionism. Indeed, the field derives its name from the belief that knowledge is stored in the connections between neurons. Donald Hebb, a Canadian psychologist, stated it this way in his 1949 book The Organization of Behavior: “When an axon of cell A is near enough cell B and repeatedly or persistently takes part in firing it, some growth process or metabolic change takes place in one or both cells such that A’s efficiency, as one of the cells firing B, is increased.” It’s often paraphrased as “Neurons that fire together wire together.”

>  Neurons that excite one another form what Hebb called a cell assembly. Concepts and memories are represented in the brain by cell assemblies. Each of these can include neurons from different brain regions and overlap with other assemblies. The cell assembly for “leg” includes the one for “foot,” which includes assemblies for the image of a foot and the sound of the word foot.

>  Another difference between symbolist and connectionist learning is that the former is sequential, while the latter is parallel. In inverse deduction, we figure out one step at a time what new rules are needed to arrive at the desired conclusion from the premises. In connectionist models, all neurons learn simultaneously according to Hebb’s rule. This mirrors the different properties of computers and brains.

>  In a perceptron, a positive weight represents an excitatory connection, and a negative weight an inhibitory one. The perceptron outputs 1 if the weighted sum of its inputs is above threshold, and 0 if it’s below. By varying the weights and threshold, we can change the function that the perceptron computes.

>  To decide whether the perceptron fires or not, we multiply each weight by the corresponding input and compare the sum of all of them with the threshold.

>  Since perceptrons can only learn linear boundaries, they can’t learn XOR. And if they can’t do even that, they’re not a very good model of how the brain learns, or a viable candidate for the Master Algorithm.

>  Spin glasses are not actually glasses, although they have some glass-like properties. Rather, they are magnetic materials. Every electron is a tiny magnet by virtue of its spin, which can point “up” or “down.”

>  Look into what a spin glass loos like and how it woks.

>  Hopfield noticed an interesting similarity between spin glasses and neural networks: an electron’s spin responds to the behavior of its neighbors much like a neuron does. In the electron’s case, it flips up if the weighted sum of the neighbors exceeds a threshold and flips (or stays) down otherwise. Inspired by this, he defined a type of neural network that evolves over time in the same way that a spin glass does and postulated that the network’s minimum energy states are its memories. Each such state has a “basin of attraction” of initial states that converge to it, and in this way the network can do pattern recognition: for example, if one of the memories is the pattern of black-and-white pixels formed by the digit nine and the network sees a distorted nine, it will converge to the “ideal” one and thereby recognize it.

>  Most importantly for us, S curves lead to a new solution to the credit-assignment problem. If the universe is a symphony of phase transitions, let’s model it with one.

>  Backpropagation, as this algorithm is known, is phenomenally more powerful than the perceptron algorithm. A single neuron could only learn straight lines. Given enough hidden neurons, a multilayer perceptron, as it’s called, can represent arbitrarily convoluted frontiers. This makes backpropagation—or simply backprop—the connectionists’ master algorithm.

>  Linear models are blind to phase transitions; neural networks soak them up like a sponge.

>  So autoencoders didn’t really catch on. The trick that took over a decade to discover was to make the hidden layer larger than the input and output ones. Huh? Actually, that’s only half the trick: the other half is to force all but a few of the hidden units to be off at any given time.

>  Worse than that, even if we had a complete map of the brain, we would still be at a loss to figure out what it does. The nervous system of the C. elegans worm consists of only 302 neurons and was completely mapped in 1986, but we still have only a fragmentary understanding of what it does. We need higher-level concepts to make sense of the morass of low-level details, weeding out the ones that are specific to wetware or just quirks of evolution. We don’t build airplanes by reverse engineering feathers, and airplanes don’t flap their wings. Rather, airplane designs are based on the principles of aerodynamics, which all flying objects must obey. We still do not understand those analogous principles of thought.

>  In the same way that DNA encodes an organism as a sequence of base pairs, we can encode a program as a string of bits. Instead of 0 and 1, the DNA alphabet has four characters—the four bases adenine, thymine, cytosine, and guanine—but that’s a superficial difference. Variations, whether in DNA sequences or bit strings, can be generated in several ways. The simplest approach is point mutation, flipping a random bit in the string or changing a single base in a stretch of DNA.

>  In 1972, Niles Eldredge and Stephen Jay Gould proposed that evolution consists of a series of “punctuated equilibria,” alternating long periods of stasis with short bursts of rapid change, like the Cambrian explosion.

>  Suppose that a hypothesis’s probability of surviving into the next generation is proportional to its fitness. Holland showed that, in this case, the fitter a schema’s representatives in one generation are compared to the average, the more of them we can expect to see in the next generation. So, while the genetic algorithm explicitly manipulates strings, it implicitly searches the much larger space of schemas. Over time, fitter schemas come to dominate the population, and so unlike the drunkard, the genetic algorithm finds its way home.

>  bit strings

>  Figure outwht this means.

>  And the “building blocks” intuition is appealing but quickly runs into trouble, even when genetic programming is used. As larger blocks evolve, crossover also becomes increasingly likely to break them up. Also, once a highly fit individual appears, its descendants tend to quickly take over the population, crowding out potentially better schemas that were trapped in overall less fit individuals.

>  “Nature” for a computer is the program it runs, and “nurture” is the data it gets.

>  The molecular biology of living cells is such a mess that molecular biologists often quip that only people who don’t know any of it could believe in intelligent design.

>  At heart, Bayes’ theorem is just a simple rule for updating your degree of belief in a hypothesis when you receive new evidence: if the evidence is consistent with the hypothesis, the probability of the hypothesis goes up; if not, it goes down. For

>  We call this the prior probability that the sun will rise, since it’s prior to seeing any evidence. It’s not based on counting the number of times the sun has risen on this planet in the past, because you weren’t there to see it; rather, it reflects your a priori beliefs about what will happen, based on your general knowledge of the universe.

>  But now the stars start to fade, so your confidence that the sun does rise on this planet goes up, based on your experience on Earth. Your confidence is now a posterior probability, since it’s after seeing some evidence. The sky begins to lighten, and the posterior probability takes another leap.

>  According to Bayes’ theorem, the more likely the effect is given the cause, the more likely the cause is given the effect:

>  P( cause | effect) = P( cause) × P( effect | cause) / P( effect).

>  one has a problem with the formula itself. The controversy is in how Bayesians obtain the probabilities that go into it and what those probabilities mean.

>  For most statisticians, the only legitimate way to estimate probabilities is by counting how often the corresponding events occur.

>  What exactly justifies assuming a priori that the probability the sun will rise is one-half, or two-thirds, or whatever? Bayesians’ answer is that a probability is not a frequency but a subjective degree of belief.

>  A very simple and popular assumption is that all the effects are independent given the cause. This means that, for example, having a fever doesn’t change how likely you are to also have a cough, if we already know you have the flu. Mathematically, this is saying that P( fever, cough | flu) is just P( fever | flu) × P( cough | flu). Lo

>  Notice that we’re only saying that fever and cough are independent given that you have the flu, not overall. Clearly, if we don’t know whether you have the flu, fever and cough are highly correlated, since you’re much more likely to have a cough if you already have a fever. P( fever, cough) is not equal to P( fever) × P( cough). All we’re saying is that, if we know you have the flu, knowing whether you have a fever gives us no additional information about whether you have a cough.

>  A learner that uses Bayes’ theorem and assumes the effects are independent given the cause is called a Naïve Bayes classifier.

>  But machine learning is the art of making false assumptions and getting away with it. As the statistician George Box famously put it: “All models are wrong, but some are useful.”

>  It all began when David Heckerman, a prominent Bayesian researcher who is also a medical doctor, had the idea of treating spam as a disease whose symptoms are the words in the e-mail: Viagra is a symptom, and so is free, but your best friend’s first name probably signals a legit e-mail. We can then use Naïve Bayes to classify e-mails into spam and nonspam, provided spammers generate e-mails by picking words at random.

>  In it, he modeled a classic of Russian literature, Pushkin’s Eugene Onegin, using what we now call a Markov chain. Rather than assume that each letter was generated at random independently of the rest, he introduced a bare minimum of sequential structure: he let the probability of each letter depend on the letter immediately preceding it.

>  PageRank, the algorithm that gave rise to Google, is itself a Markov chain. Larry Page’s idea was that web pages with many incoming links are probably more important than pages with few, and links from important pages should themselves count for more.

>  The states form a Markov chain, as before, but we don’t get to see them; we have to infer them from the observations. This is called a hidden Markov model, or HMM for short. (Slightly misleading, because it’s the states that are hidden, not the model.)

>  speech recognition, the hidden states are written words, the observations are the sounds spoken to Siri, and the goal is to infer the words from the sounds. The model has two components: the probability of the next word given the current one, as in a Markov chain, and the probability of hearing various sounds given the word being pronounced.

>  HMMs are also a favorite tool of computational biologists. A protein is a sequence of amino acids, and DNA is a sequence of bases. If we want to predict, for example, how a protein will fold into a 3-D shape, we can treat the amino acids as the observations and the type of fold at each point as the hidden state.

>  the states and observations are continuous variables instead of discrete ones, the HMM becomes what’s known as a Kalman filter. Economists use Kalman filters to remove noise from time series of quantities like GDP, inflation, and unemployment. The “true” GDP values are the hidden states; at each time step, the true value should be similar to the observed one, but also to the previous true value, since the economy seldom makes abrupt jumps.

>  HMMs are good for modeling sequences of all kinds, but they’re still a far cry from the flexibility of the symbolists’ If… then… rules, where anything can appear as an antecedent, and a rule’s consequent can in turn be an antecedent in any downstream rule. If we allow such an arbitrary structure in practice, however, the number of probabilities we need to learn blows up.

>  The first law of ecology, according to biologist Barry Commoner, is that everything is connected to everything else. That may be true, but it would also make the world impossible to understand, if not for the saving grace of conditional independence: everything is connected, but only indirectly.

