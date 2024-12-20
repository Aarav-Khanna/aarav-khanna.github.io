---
layout: default
title: Mentis.ai
permalink: /mentisai/
---

# mentis.ai

An AI-powered tutor that generates live, adaptive lessons using both visuals and audio.

<div style="max-width: 560px; margin-bottom: 1.5em;">
  <iframe width="560" height="315" src="https://www.youtube.com/embed/AoTd_J_dEXY" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
</div>

## Inspiration

We envisioned Mentis at the intersection of accessibility, interactivity, and audiovisual learning:

<img src="/pages/work/mentis-venn.png" alt="Mentis.ai venn diagram" style="max-width: 100%; height: auto; margin: 1.5em 0;" />

The inspiration behind Mentis emerged from a realization of the vast potential that a personalized learning AI platform holds in transforming education. We wanted to build something that can adapt to individual learning styles and backgrounds, ensuring accessibility and engagement for every learner.

## What it does

Mentis is an AI-powered educational platform that offers personalized learning experiences across a wide range of topics. It generates animated lesson plans with visuals and audio, while adapting its teaching to a user’s input. This could range from basic math for younger students to more advanced subjects like linear algebra:

<img src="/pages/work/mentis-interface.png" alt="Mentis.ai Linear Algebra Teaching Screenshot" style="max-width: 100%; height: auto; margin: 1.5em 0;" />

Whether it’s mathematics, science, or economics, Mentis provides tailored guidance, ensuring that users not only receive answers to their questions but also a deeper understanding of the subject matter.

## How we built it

At its core, a fast API backend powers Mentis’ intelligent processing and dynamic delivery of educational content. Our advanced Large Language Models (LLMs) were fine-tuned to interpret and generate content, both in text and code form, leading to rich animated lessons. Using the manim library, combined with ElevenLabs for audio, and orchestrated by Bun and Next.js on the front end, Mentis delivers a cohesive, interactive experience.

- [Fine tuned open source model](https://huggingface.co/generaleoley/mixtral-8x7b-manim-lora/tree/main)  
- [Curated custom dataset](https://huggingface.co/datasets/generaleoley/manim-codegen)

## Challenges we ran into

We faced hurdles in setting up environments, managing dependencies, and refining complex LLM-driven workflows. Every step, from generating dynamic video scripts to ensuring correct code execution for animations and integrating text-to-speech, required careful tuning and numerous adjustments.

Balancing multiple API calls to maintain low latency was a persistent challenge. With so many moving parts, ensuring a fluid user experience demanded meticulous planning and constant refinement.

## Accomplishments we're proud of

- **Technical Overcomes:** We solved challenging integration problems, growing our problem-solving capabilities.
- **Versatile System:** Covering a broad array of topics, Mentis makes diverse educational content accessible.
- **Adaptive Learning:** Mentis genuinely adapts to each user’s unique learning style and needs.
- **User-Friendly UI:** We focused on accessibility and clarity in design to create an inviting learning environment.
- **API Management:** We streamlined numerous API calls for improved reliability and responsiveness.
- **Fine-Tuned Models:** We successfully navigated data exploration, model selection, and fine-tuning to achieve more accurate and efficient models.

## What we learned

Fine-tuning an LLM for the first time taught us about model selection, dataset curation, and prompt engineering. We grew to appreciate the researchers who paved the way in this field and learned how meticulous tuning can vastly improve efficiency and accuracy.

Coordinating multi-agent systems and running them concurrently was another key learning experience. Through testing various architectures, we found an approach that prioritized accuracy first, then speed, enabling asynchronous queries and reducing wait times.

## What's next for Mentis.ai

- **Reducing Latency:** We plan to further enhance efficiency to minimize latency.
- **Innovative Features:** We hope to integrate cutting-edge capabilities, such as natural video generation with HeyGen API, to produce personalized tutor videos.
- **Classroom Integration:** We aim to bring Mentis into real-world educational settings, tailoring it to help teachers and students alike.

---
