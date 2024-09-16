---
layout: page  
title: NLP for Networks and Cybersecurity  
subtitle: Words Beyond Natural Language  
permalink: /aligned-research/nlp-language-modelling/  
---

When I joined the Datacom AI team at Huawei to work on AI for networks, my first question was: What would the **network visual cortex** look like? How can we represent network data akin to how we represent images in computer vision? This led to a focus on finding the best representation learning strategy for heterogeneous network data.

During my time at Huawei, I promoted two main lines of work that applied natural language processing (NLP) techniques to network and cybersecurity data:

1. **Multi-modal Network Data**: I observed a bimodal nature in network data: sequences of *entities* (e.g., IP addresses, domain names) and *quantities* (e.g., measurements). I proposed applying NLP-based representation learning techniques to encode sequences of entities, similar to how words are represented in a language; in addition to classic representation learners to learn from quantities. This approach has proven effective across various use cases and fruitful collaborations I had on the topic.

2. **Non-Language Logs**: Applying language modeling to logs that are not traditional language, such as shell/bash commands, firewall logs and network configurations.

---

## 1. Generic multi-modal representation learning from network Data
### Entities and Quantities

In my work, I observed that network data naturally consists of a mixture of entities (e.g., IP addresses, DNS names) and quantities (e.g., measurements). Traditionally, these data types were treated separately or simplified into single modalities, which limited the potential of machine learning models. To address this, I proposed a multi-modal approach, systematically applying language models to encode sequences of entities and augment quantity-based features.


![Joint learning from Entities and Quantities](/assets/img/entity_quantity.png)

### Why It Mattered 
For AI to autonomously drive future networks, handling hybrid data effectively is crucial. By integrating both entities and quantities into a unified learning strategy, I aimed to improve network management, anomaly detection, and threat intelligence.


### Key Papers
1. **i-DarkVec: Incremental Embeddings for Darknet Traffic Analysis**  
   *Gioacchini, L., Vassio, L., Mellia, M., Drago, I., Houidi, Z. B., & Rossi, D. (2023). ACM Transactions on Internet Technology.*  
   **Word = IP address**  
   Focus: Using NLP techniques for analyzing darknet traffic and identifying clusters of malicious activity.

2. **Cross-network Embeddings Transfer for Traffic Analysis**  
   *Gioacchini, L., Mellia, M., Vassio, L., Drago, I., Milan, G., & Houidi, Z. B. (2023). IEEE Transactions on Network and Service Management.*  
   **Word = IP address (translation between network domains)**  
   Focus: Applying transfer learning for traffic analysis across different networks.

3. **Towards a Systematic Multi-modal Representation Learning for Network Data**  
   *Houidi, Z. B., Azorin, R., Gallo, M., Finamore, A., & Rossi, D. (2022). ACM HotNets.*  
   **Word = DNS, word = Access Point name**  
   Focus: Developing multi-modal representation learning strategies for network data.

4. **DarkVec: Automatic Analysis of Darknet Traffic with Word Embeddings**  
   *Gioacchini, L., Vassio, L., Mellia, M., Drago, I., Ben Houidi, Z., & Rossi, D. (2021). ACM CoNEXT.*  
   **Word = IP address**  
   Focus: Clustering darknet traffic sources using word embeddings.

5. **A Method for Movement Prediction Combining Supervised and Unsupervised Learning**  
   *Houidi, Z. B., Krolikowski, J., & Iacoboaiea, O. C. (2021). Patent PCT/EP2021/057178.*  
   **Word = Access Point name**  
   Focus: Predicting user movement in wireless networks by combining RSSI and Access Point embeddings.

6. **Network Device and Method for Host Identifier Classification**  
   *Houidi, Z. B., & Shihao. (2020). Patent PCT/CN2020/102259, 86637592EP03.*  
   **Word = DNS name**  
   Focus: Classification of network traffic based on DNS names and host identifiers.

---

## 2. Logs that Are Not Natural Language 
### (Shell/Bash, Network Configurations, Firewall logs)

I also promoted the application of NLP language modeling techniques to logs that are not traditional language but still contain structured patterns, such as shell/bash scripts, network configurations. Through fruitful collaborations, we managed to build and evaluate methods to apply language models to these logs to extract meaningful representations and detect patterns, which could support security analysis and network automation.

### Why It Mattered for my employer
Automating the analysis of non-language logs with NLP techniques reduces the burden on human analysts and enhances threat detection. This approach proved particularly valuable in cybersecurity, where large volumes of logs need to be processed quickly and accurately.

### Key Papers
1. **LogPrécis: Unleashing Language Models for Automated Malicious Log Analysis**  
   *Boffa, M., Drago, I., Mellia, M., Vassio, L., Giordano, D., Valentim, R., & Ben Houidi, Z. (2024). Elsevier Computers & Security.*  
   **Word = bash command**  
   Focus: Automating Unix shell attack log analysis using language models.

2. **Towards NLP-based Processing of Honeypot Logs**  
   *Boffa, M., Vassio, L., Mellia, M., Drago, I., Milan, G., & Ben Houidi, Z. (2022). IEEE EuroS&P Workshops.*  
   **Word = bash logs**  
   Focus: Clustering and analyzing SSH/Telnet honeypot logs using NLP techniques.

3. **On Using Pretext Tasks to Learn Representations from Network Logs**  
   *Boffa, M., Vassio, L., Mellia, M., Drago, I., & Houidi, Z. B. (2022). 1st International Workshop on Native Network Intelligence.*  
   **Word = bash script**  
   Focus: Applying NLP-based approaches to analyze and cluster attack patterns in network logs.

4. **Neural Language Models for Network Configuration: Opportunities and Reality Check**  
   *Houidi, Z. B., & Rossi, D. (2022). Elsevier Computer Communications.*  
   **Word = configuration language**  
   Focus: Applying language models to network configuration languages for tasks like verification and translation.

5. **Neural Combinatorial Optimization Beyond the TSP: Existing Architectures Under-represent Graph Structure**  
   *Boffa, M., Houidi, Z. B., Krolikowski, J., & Rossi, D. (2022). arXiv preprint.*  
   **Word = network node**  
   Focus: Exploring neural architectures for graph-based optimization problems.

---

## Keynotes and talks

1. **From Perception to Reflection: The Future of Networks in the Era of Artificial General Intelligence**  
   *Keynote at IP Day, South Africa (2024)*

2. **Towards a Systematic Multi-modal Representation Learning for Network Data**  
   *Paper Presentation at ACM HotNets (2022)*

3. **The Unreasonable Effectiveness of Word Embeddings in Learning from Categorical Network Data**  
   *Keynote at WTMC2022, Genoa (2022)*

---

*This line of work was greatly enriched (actually wouldn't have been possible without) by the collaboration with my long-time colleagues from Politecnico di Torino—including Idilio Drago, Marco Mellia, Luca Vassio, Luca Gioacchini, Matteo Boffa—as well as many others. I am also equally grateful to my colleagues at Huawei.*