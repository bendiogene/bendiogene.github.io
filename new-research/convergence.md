---
layout: page
title: Human-inspired AI
subtitle: Towards AI with cognitive-dissonance and novelty-aware continual learning of episodic events
permalink: /new-research/convergence/
---

<style>
  .wip-banner {
    background-color: #f5f5f5; /* Subtle neutral background */
    color: #333; /* Darker, more neutral text color */
    padding: 1rem;
    border-radius: 0.5rem;
    margin: 0 auto 1.5rem;
    max-width: 600px;
    text-align: center;
  }
  .wip-banner h2 {
    font-size: 1.5rem;
    font-weight: bold;
    margin-bottom: 0.5rem;
  }
  .coming-soon {
    border: 1px solid #ccc; /* Soft, neutral border */
    padding: 1rem;
    border-radius: 0.5rem;
    margin-bottom: 1rem;
    background-color: #fafafa; /* Light neutral background */
  }
  .coming-soon h3 {
    font-size: 1.25rem;
    font-weight: 600;
    margin-bottom: 0.5rem;
    color: #333; /* Neutral text color */
  }
  .stay-tuned {
    margin-top: 1rem;
    color: #555; /* Subtle color for "stay tuned" */
    font-weight: 500;
  }
</style>

<div class="wip-banner">
  <h2>🚧 Work in Progress 🚧</h2>
  <p> I believe that Large Language Models (LLMs) led us to discover a powerful approach to implement conceptual simulation over possible worlds. I believe that the fundamental technology exists and argue that only a bit more work is needed to align these models with our world. This year, I began focusing on episodic memory as a key missing ability in current AI systems. This page outlines my approach and serves as a placeholder for ongoing work.</p>
</div>

## 1. Why are LLMs so powerful? 
### My answer is: conceptual simulation over possible worlds

<div style="width: 70%; margin: 0 auto; text-align: center;">
  <img src="/assets/img/conceptual_possible_worlds.png" alt="Navigating through possible worlds" style="width: 100%;">
  <p style="font-style: italic;">From a given context, a Large World Model can sample possible futures, some are "real" and some are "imaginary"</p>
</div>


Large language models have shown remarkable ability in building world models (multi-modal models are likely to be even more effective in this regard). Their power lies in their capacity to produce plausible outputs given a context, allowing them to explore possibilities and even creatively combine unrelated concepts.

## 2. Two main drawbacks:

<div style="width: 70%; margin: 0 auto; text-align: center;">
  <img src="/assets/img/problems_epmem_solution.png" alt="The two big problems of current LLMs" style="width: 100%;">
  <p style="font-style: italic;">The two major problems of current Large World Models</p>
</div>

When LLMs "generate possible futures", they struggle to distinguish between what is real and what is false. Additionally, while humans engage in step-by-step trial and error processes, LLMs can do this today but forget beyond their context window.

## 3. A "hippocampus" is a key missing piece towards AGI

### 3.1. Episodic memory is the solution to confabulations

<div style="width: 70%; margin: 0 auto; text-align: center;">
  <img src="/assets/img/star_wars.png" alt="Star wars in a box man" style="width: 100%;">
  <p style="font-style: italic;">The star-wars-in-a-box man</p>
</div>

Imagine a person locked inside a closed box, and who has only seen Star Wars movies since its birth. For this individual, wouldn't Star Wars be their reality? Similarly, LLMs are trained on both fiction and reality without necessarily an explicit, native distinction between the two. They can recite knowledge, but they don't know how and where they acquired it.

#### Episodic grounding into space and time are what make real events real. 

I propose a simple, perhaps bold claim:

> Grounding in space and time is what allows us to distinguish between what is real and what is wrong. Everything that happened in our space and time is real, and everything else is imaginary. The *cue* of space and time is what allows us to simply distinguish between both.

Unlike LLMs, human learning is constantly grounded in continuous space and time signals. We always know our location, date, and time while we think, learn and recall memories.

<div style="width: 70%; margin: 0 auto; text-align: center;">
  <img src="/assets/img/hippocompass.png" alt="Hippocompass" style="width: 100%;">
  <p style="font-style: italic;">The hippocampus should have been better called the hippocompass! Somewhat our coordinate system in time and space, and the corresponding index with which we can access our memories.</p>
</div>

### 3.2. Episodic memory is also the solution to coherent system 2 thinking

I also think that episodic memory is crucial for enabling what is called "system 2" thinking in AI systems.

<div style="width: 70%; margin: 0 auto; text-align: center;">
  <img src="/assets/img/epmemagent.png" alt="An episodic memory augmented LLM" style="width: 100%;">
  <p style="font-style: italic;">A schematic view of how a system 2 thinking approach could be enabled if we solve the problem of ingesting episodic memory inside Large World Models. A similar approach could be implemented with today's technology/engineering, but would be too costly.</p>
</div>

If we can quickly update LLM parameters coherently with the results of the intermediate thinking steps, we can enable true system 2 thinking, allowing models to remember and build upon their recent thoughts and actions.

## 4. Current work-in-progress

*As the principal investigator, I crafted the research framework and guided the project from its inception to execution. However, the concrete progress we're making wouldn't be possible without the invaluable contributions of my dedicated colleagues, whose insights continue to enrich and refine these ideas. Below is what we will deliver soon.*

<div class="coming-soon">
  <h3>🔜 Coming Soon: Episodic-memory benchmarks</h3>
  <p>A benchmark to evaluate LLMs on their ability to recall episodic events. This involves a generic framework to represent episodic events that happen in time and space, and a systematic list of episodic recall tasks.</p>
  <div class="stay-tuned">Stay tuned!</div>
</div>

<div class="coming-soon">
  <h3>🔜 Coming Soon: Empirical investigations on cognitive dissonance-aware incremental update of knowledge inside LLMs.</h3>
  <p> An LLM blindly believes its training data even if it contradicts its prior knowledge, while a human detects when something contradicts their prior beliefs. When such cognitive dissonance occurs, the human actively engages in resolving it. Additionally, implementing a form of stubbornness, where neurons full of knowledge become stubborn, and weights that don't activate clearly enough are reset to zero, could be beneficial.</p>
  <div class="stay-tuned">Stay tuned!</div>
</div>





