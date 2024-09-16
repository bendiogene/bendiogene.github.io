---
layout: page
title: From Automated Reasoning about Networks to AGI (2014~2018)
subtitle: How I Realized that Automated Reasoning about Networks Needed AGI Abilities
permalink: /aligned-research/automated-reasoning-agi/
---

While the project began aligned with my employer's objectives, it organically evolved into a personal exploration of Artificial General Intelligence (AGI), opening new avenues for my research interests.
The journey began with a simple yet deep question: What kind of intelligence is required to generate IETF RFCs (Request for Comments) documents? This question led me to explore the roots of AI, including old-fashioned AI (which sparked the first AI spring—and eventually, the subsequent AI winter).

## Conceptual Simulation: An Underestimated Strategy for Supreme Intelligence

> "... a kind of general algebra in which all truths of reason would be reduced to a kind of calculus [...] this would be a kind of universal language or writing..." - Leibniz, 1714

Thinking about how to automate reasoning, I realized that conceptual simulation, the ability to mentally navigate the space of possibilities in our world, **searching** for outcomes that achieve a specific goal, is a key feature of intelligent agents. Inspired by Leibniz's idea of a universal language of thought, I embarked on the quest to build a *characteristica universalis* for network expertise—essentially a universal framework that could solve any network problem.


### Conceptually Simulating a Packet's Life in a Network

To realize this vision, I turned to first-order logic, designing simple axiomatic rules that could conceptually simulate the life of a packet in a network. These rules covered everything from connectivity goals to message transmission and routing as seen in the figure below.

![Thoughts as Graph](/assets/img/thoughts.png)

*Figure: Conceptual simulation using first-order logic to trace possible thought paths for solving networking problems.*

Using a knowledge engine with forward and backward chaining rules, I traced all possible thought paths to solve the problem (satisfy the connectivity goal). This process generated automatically multiple solutions, some aligning with existing IETF standards and others suggesting new approaches. One counter-intuitive solution was interesting enough for us to decide to submit a patent application, which ultimately was granted.

![Generated Patent](/assets/img/generated_patent.png)

*Figure: Lesson 1 - Conceptual simulation is a powerful tool to automate reasoning about networks, allowing the generation of both standard and novel solutions.*

## Discovery: The Concepts Needed to Automate Networks Are Not Specific to Networks

As I analyzed the rules, I realized something profound: these concepts existed long before telecommunications. Concepts like "Send," "Receive," "Transform," "Identify," "Decide," "Enter," and "Exit" exist not only in networking but also in the physical world. Essentially, the invention of telecommunications involved transferring these fundamental concepts from the physical domain to the digital one.

![Semantics of reasoning rules](/assets/img/predated.png)

This realization echoed Leibniz's *Alphabet of Thoughts*—the idea that all thoughts could be reduced to a small number of basic concepts. Solving this problem for good would require an intelligence that can grasp these universal concepts, leading me to the conclusion that achieving this would need something close to Artificial General Intelligence (AGI).

![Transfer of Knowledge from Physical to Digital](/assets/img/transfer.png)

*Figure: Lesson 2 - Solving network automation problems fundamentally requires AGI-like capabilities, as it involves universal concepts that transcend specific domains.*

## The Path to AGI

This realization led me to understand that all thoughts could potentially be reduced to a small number of concepts, reflecting the basic features we extract from the world. This idea echoes Leibniz's concept of an "Alphabet of thoughts" and points towards the fundamental nature of intelligence itself. Leibniz even explicitly thought that such features are visual related to objects and motion. 

Believing that conceptual simulation is a key ability, I got interested into how we simulate with our brains, offline, mental visual images about our world. This led me to enter the world of computational neuroscience in my free research. 
 
My journey from automated reasoning about networks to exploring AGI concepts has shown that the principles underlying complex systems in one domain are often universal. The pursuit of a "characteristica universalis" for network expertise opened up broader questions about the nature of intelligence and the potential for creating truly general artificial intelligence.

## References


1. Ben Houidi, Z. (2016). "A knowledge-based systems approach to reason about networking". *ACM HotNets*.

2. Ben Houidi, Z. (2017). "Towards a Networking Characteristica Universalis". *LINCS Seminar, Paris*.  
   [![Watch on YouTube](https://img.shields.io/badge/Watch_on-YouTube-red?logo=youtube)](https://youtu.be/bs_FodDrYWY)

3. Ben Houidi, Z. (2016). "From Human Networking Experts to Automated Reasoners". *Bell Labs, Holmdel, New Jersey*.  

4. Ben Houidi, Z. (2018). "Concrete challenges on the way of Artificial General Intelligence". *Bell Labs, Unfinished Research Proposal*.  
   [Draft available here](/assets/docs/The__project.pdf)

5. Ben Houidi, Z. (2018). "Finding the missing pieces of true AI: Orchestration, generation/conceptual simulation, and self-observation". *LINCS retreat*.

6. Ben Houidi, Z. (2018). "Bell Labs AI days: What (artificial) intelligence to generate IETF standards (and patents)?". *Bell Labs AI Days*.  
   [Slides available here](/assets/docs/Bell-Labs-AI-day-Nozay-Ben-Houidi.pptx)

*Note. Although this trip was mostly solo, I am grateful to all those who patiently listened to me and gave m feedback. Thankful also to Riadh for help during his internship with the first python knowledge-based system implementation, and Max for the patent.*