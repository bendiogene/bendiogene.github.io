---
layout: page
title: A selection of older themes
permalink: /aligned-research/older-aligned/
---

Below are brief overviews of select research themes that I engaged in, aligning both with my employers' strategic interests.

## 1. Data-driven Network Control (2019~2022)

In the context of Wireless Local Area Networks as an application, I led a project on data-driven control of networks where the idea was to continuously monitor the network state and take resource allocation decisions accordingly.

There, I proposed to get inspiration from seminal work on deep reinforcement learning based combinatorial optimization, and use sequential models with reinforcement learning to learn policies to control networks. The resulting collective work, together with my colleagues, involved designing (i) data collection infrastructures to collect input data, (ii) network configuration API to take actions on production networks (iii) objective functions to guide the learner and of course (iv) Neural network architectures.

I also explored the use of GNNs and transformer-inspired encoder-decoder architectures to learn how to sequentially solve combinatorial optimization problems, with a particular focus on generalization.

### References

Here is the list sorted by date from newer to older:

1. Krolikowski, J.*, & Ben Houidi*, Z. & Rossi, D.  (2023). "User-aware WLAN Transmit Power Control in the Wild". [*arXiv preprint arXiv:2302.10676*](https://arxiv.org/abs/2302.10676). *equal contribution

2. PCT/EP2023/050709. (2023). "A data-driven WLAN topology-related KPIs query system & estimation method". *Patent*

3. Fernandes, D. M., Krolikowski, J., Ben Houidi, Z., Chen, F., & Rossi, D. (2022). "Cross-network transferable neural models for WLAN interference estimation". *Proceedings of ACM CoNext GNNet*.

4. Iacoboaiea, O., Krolikowski, J., & Ben Houidi, Z. (2022). "From design to deployment of zero touch deep reinforcement learning WLANs". [*IEEE Communications Magazine*, 61(2), 104-109](https://ieeexplore.ieee.org/document/9697857).

5. PCT/EP2022/051624. (2022). "Network resource control based on neighborhood measurements". *Patent*

6. Boffa, M., Ben Houidi, Z., Krolikowski, J., & Rossi, D. (2022). "Neural combinatorial optimization beyond the TSP: Existing architectures under-represent graph structure". [*arXiv preprint arXiv:2201.00668*](https://arxiv.org/abs/2201.00668).

7. Iacoboaiea, O., Krolikowski, J., & Ben Houidi, Z. (2021). "Real-time channel management in WLANs: Deep reinforcement learning versus heuristics". *2021 IFIP Networking Conference (IFIP Networking), IEEE*

8. Krolikowski, J., Iacoboaiea, O., & Ben Houidi, Z. (2021). "WiFi Dynoscope: Interpretable Real-Time WLAN Optimization". *IEEE INFOCOM 2021-IEEE Conference on Computer Communications Workshops (INFOCOM WORKSHOPS)*

## 2. Data2$ and Experiments with Social computing/Computational Social Science (2013~2017)

Right after working on Internet interconnection business models, and realizing that carriers' value was diminishing, I moved to the problem of extracting rich insights from network data. This was before the advent of encryption, that killed many of the ideas of this project and further limited the usefulness of network data and its value. 

### 2.1. Uncovering human behavior from network traces
The most memorable outcome from this line of work was, while studying news consumption behavior, finding empirical evidence, based on more than a year of data from tens of thousands of households that there is a considerable difference between what people think they like to consume (e.g. science, politics) and what they actually consume in terms of news (e.g. crime, sport etc.). 

On a personal level, this was also the first time I get exposed to [K.C. Berridge's work ](https://scholar.google.com/citations?user=WIRQRN8AAAAJ&hl=en) on the neural correlates of like and want, and his interpretation of the role of dopamine (incentive salience) in the brain. His work was one major inspiration and his papers were my entry point to the world of neuroscience. 


![News Consumption Analysis (picture from AAAI ICWSM'19)](/assets/img/news_consumption.jfif)

*Picture from my presentation at ICWSM'19 at Munich*

### 2.2. A reddit-like system with no user engagement or input

Another piece of work I initiated, back in the time, was at the intersection of information overload, crowdsourcing, content curation and network traffic analysis. I noticed that systems like reddit were powerful because of the work of their users who select content, and others who actually rate it. So I wondered if one could simulate the same thing starting just from the clicks of a community of users as observed in network traffic or enterprise logs. This led to the birth of WeBrowse, the unique attempt I am aware of to simulate the output of a social computing system passively from user clicks. We implemented and deployed WeBrowse in a large campus and in a research center. This experience was documented in a research paper at ACM CSCW 2017.

![WeBrowse (picture from ACM CSCW'17)](/assets/img/webrowse.jfif)

*Picture from my presentation at ACM CSCW'17, Jersey city*


Methodology-wise, this is when I started applying classification, clustering, and this is when I started my first experiences with old-fashion Natural Language Processing (keyword-based, tf-idf, LDA topic modeling etc..)


*Note. I am grateful for the collaborative efforts of Giuseppe, Renata, Stefano, and Marco. Working together, we learned a lot exploring the fascinating intersection of human behavior and network data. I keep good memories from this adventure.*

### Pointers

1. Houidi, Z. Ben, Scavo, G., Traverso, S., Teixeira, R., & Mellia, M. (2019). "The news we like are not the news we visit: News categories popularity in usage data". *Proceedings of the International AAAI Conference on Web and Social Media*, 13, 91–102.

2. Houidi, Z. Ben. (2018). "LINCS workshop 'Beyond Surveys and Social Media: Understanding Online News Consumption Habits from Usage Data'". *Socialcomputing, talk*.

3. Vassio, L., Drago, I., Mellia, M., Houidi, Z. Ben, & Lamali, M. L. (2018). "You, the Web, and Your Device: Longitudinal Characterization of Browsing Habits". [*ACM Trans. Web*, 12(4), Article 24](https://doi.org/10.1145/3231466).

4. Scavo, G., Houidi, Z. Ben, Traverso, S., Teixeira, R., & Mellia, M. (2017). "WeBrowse: Leveraging User Clicks for Content Discovery in Communities of a Place". [*Proc. ACM Hum.-Comput. Interact.*, 1(CSCW), Article 93](https://doi.org/10.1145/3134728) [*Arxiv1602.06678*](https://arxiv.org/abs/1602.06678).

5. Houidi, Z. Ben. (2015). "How to be well-informed for entertainment and work". *Bell Labs Annual Meeting*.

## 3. Inter-domain Interconnection Business Models (2011~2012)

Having worked on BGP in the past, I was assigned as soon as I joined Bell Labs to this big European project which aimed at building new interconnection models in which each carrier got its fair share in the "cake". This project was an opportunity to conceptually simulate other software-defined alternatives to BGP (implementations, testbeds etc). It was also an opportunity to deepen my knowledge about the tussles between content providers and carriers: who has more value? how to share the revenues? Those who possess the interesting content? or those who carry it? My position about these tussles was summarized in the following paper.

Houidi, Z. Ben, & Pouyllau, H. (2012). "The price of tussles: bankrupt in cyberspace?". [*ACM SIGMETRICS Performance Evaluation Review*](https://dl.acm.org/doi/10.1145/2381056.2381065), 40(2), 34–37.


## 4. Data-driven Routing Protocols Design and Evaluation

This was my first research project, the theme was heavily-influenced by my PhD advisor.  Here, the input was network-wide muti-vendor router configurations, together with routing logs. As an output, we did characterize the networks at hand, uncover multi-vendor misbehavior in BGP implementations, and designed a new route distribution architecture for MPLS VPNs.

### Pointers

1. Ben Houidi, Z. (2010). "Understanding Slow BGP Routing Table Transfers". *NANOG 2010, Atlanta; LIP6, Paris; Thomson Paris Research Lab; IMC 2009, Chicago*.
   - [![Watch on YouTube](https://img.shields.io/badge/Watch_on-YouTube-red?logo=youtube)](https://youtu.be/nCQ7T1Pg8jU?t=3498)

2. Ben Houidi, Z., Meulle, M., & Teixeira, R. (2009). "Understanding slow BGP routing table transfers". *Proceedings of the 9th ACM SIGCOMM conference on Internet measurement*, 350–355.

3. Ben Houidi, Z. (2010). "A new VPN routing approach for large scale networks". *ICNP 2010, Kyoto*.


