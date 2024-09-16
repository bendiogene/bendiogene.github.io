---
layout: page
title: From bits to brains
subtitle: My Journey as a Computational Thinker
cover-img: /assets/img/Zied_SA1.jpg
---

# Short bio

I define myself best as a computational thinker, in that I use data-driven and symbolic methods to observe and understand phenomena, and to imagine and build systems with pre-defined behaviors. I am equally interested in the computational foundations of thinking. Currently a Principal Researcher at Huawei Technologies, much of my previous work has been driven by employer interests (aligned research), spanning various aspects of distributed computer networks (routing, internet economy, automated reasoning, language modelling for cybersecurity), AI/ML, and computational social science. In parallel, I conduct what I call "free research" in my spare time, focusing on computational neuroscience and philosophy/epistemology.

My work on automated reasoning about networks (2014~2017) led me to realize the role of offline conceptual simulation in solving general offline-reasoning tasks for both artificial and biological agents. Inspired by Leibniz's dream of a characteristica universalis, I demonstrated that conceptual simulation (even using first-order logic) could reinvent Internet standards and generate patentable network solutions. This thinking opened new pathways in my free investigations, leading me to develop the [backpropagation-based recollection](https://www.biorxiv.org/cgi/content/short/2024.02.05.578854v1) theory, which explains how explicit memories are retrieved "offline" in the brain, including during imaginative mind-wandering.

Today, I'm both excited and concerned about the power of Large Language (World) Models. I believe their strength stems from their accidental ability to perform conceptual simulation over possible worlds - a concept dating back, again, to Leibniz. My current focus is on augmenting LLMs with episodic memory, including in continual learning settings, a crucial step, I believe, towards the imminent Artificial General Intelligence.

<button id="bioButton">Read My Full Story</button>

<div id="longBio" style="display: none;">

<p>September 8th, 2024</p>

<p>As a younger, more introverted version of myself, I had valid (and less valid) reasons for not having a personal page. 
I recognized that many of my perspectives were unconventional, and I initially hesitated to share them widely. Over time, I embraced the value of diverse viewpoints and the constructive dialogues they can spark. In any case, things have changed, though I must disclaimer that all opinions expressed here are mine, not those of my past, present, or future employers :-) Moreover, it's clear to me that Artificial General Intelligence (AGI) is imminent, and things will never be the same again. As thinkers, we will soon be outpaced. This website, therefore, serves primarily as an archive of my journey. As you'll read below, AGI and the foundations of thinking were a nice - perhaps the nicest - carrot on the stick in my life as a thinker.</p>

<p>I obtained my PhD in December 2010 from UPMC (Université Pierre et Marie Curie) in Paris under the supervision of Renata Teixeira (UPMC) and Michael Meulle (Orange Labs), working on BGP and data-driven evaluation and design of L3/L2VPN routing protocols (let's say routing of Internet traffic). Back then, I spent most of my time at Orange Labs, also interacting with operationals from Orange Business Services. One of the main lessons I learned (also inspired by some great people I met and who mentored me) is the spectacular mismatch between the imaginary world of research I was reading about and the reality of production networks I was observing.</p>

<p>Then I joined Bell Labs as member of technical staff, where I was first appointed for a couple of years to work on novel Internet interconnection technical and business models. My team was leading a large European project whose goal was to give the carriers (my employer's customers) a fairer share in the value chain (following feelings that content providers were "free-riding" the network). I led the effort of harmonizing the outputs of the 3 main technical work packages of the project, an experience that revealed to me the vertiginous prevalence of underestimated misunderstandings that permeate every bit of human interaction :-) </p>

<p>At the end of the two years, I concluded that (i) (Internet) "content was king" because irreplaceable and that (ii) the innovation potential of carriers was unavoidably limited to merely moving bits from one point to another: after all, if you don't like your carrier, you can easily find another one, but if you don't like your social network provider, you can leave but you cannot take your friends with you. My findings were summarized in the paper <a href="https://dl.acm.org/doi/10.1145/2381056.2381065">"The price of tussles: bankrupt in cyberspace?"</a>. There, "bankrupt in cyberspace" was a reference to ISPs that will lose value in the future. From there on, a big part of my research efforts moved away, as much as I could afford, from classic performance-oriented networking problems: I believed that no protocol-level improvements to networks will lead to essential advances that would change the life of the real users of the network.
For me, such research problems provided a fertile ground to produce research papers. But that was not my objective at the time (nor that of Bell labs, which to be honest encouraged us to limit publications and be ambitious in the problems that we choose). Working on physical layer improvements could have been useful, but I felt the space was too crowded and the evolution too incremental and predictable.</p>

<p>First, for what I thought was the sake of my employer's interests, I defended the idea that telcos and vendors could attempt to  monetize one of their unique remaining assets: the network data. There (with the help of some brilliant colleagues I enjoyed working with), I explored the value of human-level behavior analytics from network data and I invented (probably the first and last) network-data based reddit-like social computing platform, which we called WeBrowse. WeBrowse leveraged the collective click behavior of a community to "automatically curate content" with no explicit human intervention or contribution. Unfortunately, a couple of years later, the whole enterprise was rendered obsolete with the advent and generalization of traffic encryption. As part of the same project, we explored the opportunity of using network data to measure various aspects about human behavior, which exposed me to the computational social science community. Initially, I was captivated by the potential of leveraging online human behavioral traces to gain insights into society. 
Reflecting on this journey, I recognize that while the field holds promise, aligning expectations with practical outcomes is essential.
At the personal level, the only memorable finding we could reach in this space was to empirically measure, based on behavior of tens of thousands of households, that self-reported preferences of news consumption were actually different from the actual actions or click behavior, hinting towards an addictive nature of news, where the want and preference or value systems are disconnected from each other: what we want is different from what we value.</p>

<p> Concurrently, my belief that significant advancements in network performance might be reaching saturation prompted me to explore new frontiers in AI and automated reasoning. I set as an ultimate (crazy) goal (i) either to automate the reasoning about all networking problems, hence sparing human efforts (useful goal if you ask me), or (ii) understand what intelligence was needed to do so. I remember an "aha moment" in which I realized how conceptual simulation was a fundamental feature of our intelligence: this thing that allows us to explore the space of possibilities, with our imagination, searching for sequences of future events that would satisfy our goals, and then following them each time we wanted to solve the same problem again.</p>

<p>To implement this principle in practice, I proposed first to use first-order logic to represent chains of events and explore the design space of some network solutions. Concretely, my project showed that it is possible to automatically regenerate all L3/L2/L1VPN solutions (and more) using first-order logic to represent axiomatic networking knowledge, and conceptually explore the possibilities looking for feasible solutions. "Worse", one of the programmatically-generated solutions was inventive enough that we patented it (granted end 2021). A brilliant intern has helped me exploring the first implementation issues.</p>

<p>Unfortunately, such knowledge needed for first-order logic conceptual simulation has to be written manually, by introspection, in a tedious process similar to the one Leibniz imagined to build his universal alphabet of thoughts: the characteristica universalis. Furthermore, analyzing the axiomatic rules of the reasoner we built, I sadly noticed that they semantically mirrored our general knowledge about the physical world (e.g. send, receive, enter, exit, identify, transform): I inferred that automatically solving all network problems needed something roughly as powerful as Artificial General Intelligence: I learned the hard way why old-fashion rule-based AI has failed many years before, despite its power. </p>

<p>At this stage, I could have started an exploitation phase, re-applying my conceptual simulation with first-order logic methodology on dozens of similar problems in networks, and write "as many papers as possible" about it. But making such papers was neither my objective nor  in my employer's KPIs. So I decided to start over again from zero, moving to the bigger problem of automatically acquiring knowledge (instead of manually writing it down): exit automated reasoning and enter the world of deep learning, NLP word embeddings, and computational neuroscience in which I sought inspiration. By my last year at Bell Labs, I had few ideas on how to approach AGI by implementing conceptual simulation. 
I began formulating a research agenda aimed at Artificial General Intelligence. While it was challenging to align this vision within existing frameworks—given that most people thought it was a long-term horizon—I continued to explore foundational aspects independently, contributing incrementally to the field.
And this is when, after taking online computational neuroscience courses, I started exploring unsupervised representation learning with artificial spiking neural networks and exploring the first problem of multi-modal representations and conceptual simulation in the brain: how are we able to generate plausible thoughts or memories offline. This led me later to my candidate backpropagation-based recollection theory about how explicit cue-based recall and imagination might be implemented in our neurons in the brain. I kept working on improving this theory during my holidays and spare time, for 5 or 6 years after, until today, 2024. </p>

<p>During my long stay at Bell Labs, I was also exposed, by duty rather than conviction, to various emerging technologies and areas. These included Information Centric Networking, Software Defined Networking, and Network Function Virtualization, among other trending topics across the years. While each had its proponents, I often found myself profoundly skeptical about their long-term impact and transformative potential.</p>

<p>By the end of 2018, Huawei convinced me to give networks a second chance by revisiting them through the lens of more recent advances in AI. I joined the company early 2019 to fully apply my AI knowledge, daily, on exploring the potential of AI applications to networks and beyond. There, I promoted self-supervised representation learning, and the idea that each type, or modality of input data, had a best representation learning strategy. In particular, I pioneered and promoted the systematic use of language modeling approaches to learn, through self supervised pretraining, rich features from sequences of categorical entities that often co-occur in network data and logs. I applied the concept to sequences of visited domain names or IP addresses in network traffic, sequences of traversed Access Points in wifi networks. I promoted the principal also in network security where I am managing for Huawei a fruitful, humanly and technically enjoyable, technical cooperation with Politecnico di Torino. I also worked on other AI-based inference and control problems, e.g. using Deep RL to learn how to control networks or more generally sequential models and transformers to learn to solve combinatorial optimization problems. </p>

<p>Recently, LLMs succeeded where I failed earlier at Bell Labs: to perform conceptual simulation with no need for manually written rules, strongly renewing my interest in AGI, which I believe is imminent and inevitable, marking probably the most important event in the history of mankind.</p>

<p>December 2022 marked a pivotal moment in my research journey. The launch of ChatGPT dramatically accelerated AGI timelines, bringing it even closer than I had anticipated. This shift justified my quick return to AGI research within the scope of my "aligned research" work. Recognizing episodic memory as a critical missing component in the path to AGI, I proposed an ambitious project: augmenting Large Language Models (LLMs) and Large World Models (LWMs) with a 'hippocampus' - an index of episodic memories coupled with a continuously updated cognitive map of the world.</p>

<p>In 2024, I began actively pursuing this project. The work focuses on developing human-inspired approaches to integrate episodic memory capabilities into existing language models. Key aspects include exploring methods to create and maintain a dynamic cognitive map, and investigating human-inspired continual learning techniques that preserve previously acquired knowledge.</p>

<p>In parallel, I am still happily continuing my computational philosophical inquiries in my spare time, competing with AGI/ASI, which will be way more powerful than I am.</p> 

<p> That's almost all about me as a thinker. Please reach out if you have shared interests.</p>

<p><em> Note: Throughout my career, I've had the privilege of working with numerous brilliant minds whose insights and collaboration have been inspiring. I extend my sincere gratitude to all my colleagues and collaborators. </em></p>

</div>

## Selected recent work

1. Ben Houidi, Z. (2024). "Evaluating the computational efficiency of a biologically plausible action potential backpropagation mechanism for memory retrieval and generative cognition". *Society for Neuroscience Annual Meeting*, Chicago.
   - [Extended version available on bioRxiv](https://www.biorxiv.org/cgi/content/short/2024.02.05.578854v1)

2. Boffa, M., Drago, I., Mellia, M., Vassio, L., Giordano, D., Valentim, R., & Ben Houidi, Z. (2024). "LogPrécis: Unleashing Language Models for Automated Malicious Log Analysis". *Elsevier Computers & Security*.

3. Ben Houidi, Z., Azorin, R., Gallo, M., Finamore, A., & Rossi, D. (2022). "Towards a systematic multi-modal representation learning for network data". *ACM HotNets*.

4. Gioacchini, L., Vassio, L., Mellia, M., Drago, I., Ben Houidi, Z., & Rossi, D. (2021). "DarkVec: Automatic Analysis of Darknet Traffic with Word Embeddings". *ACM CoNEXT*.

5. Ben Houidi, Z. (2016). "A knowledge-based systems approach to reason about networking". *ACM HotNets*.

[Full publication list on DBLP](https://dblp.org/pid/64/2520.html)
<script>
document.getElementById("bioButton").addEventListener("click", function() {
  var longBio = document.getElementById("longBio");
  if (longBio.style.display === "none") {
    longBio.style.display = "block";
  } else {
    longBio.style.display = "none";
  }
});
</script>