---
layout: post
title: "Writing textbooks for oneself"
date: 2026-02-02
tags: [general]
subtitle: ""
---


When I took technical courses in my undergraduate and graduate years, in an era before language models, my learning process was bounded by the syllabus, office hours, and an assigned textbook or some supplemental publications. This was a hit-or-miss process for me. If the syllabus moved on to the next subject without a satisfying understanding of some prerequisite concept, or the explanation provided in the textbook was insufficient, or the TA was simply not available during a moment of curiosity, the rest of the course could quickly degrade into unsatisfying rote memorization on sandy foundations. Luckily, these days, the process of learning is far more pleasant and self-sufficient with the help of language models. LLMs themselves are not a substitute for learning, but they can be the most patient and ever-knowing intellectual partner for a back-and-forth dialogue where you state your assumptions, explain the extent of your knowledge, and ask questions with that context.

One observation I've had is that the act of writing down interconnected and detailed technical notes of all of my current relevant knowledge (some people refer to this as a personal knowledge graph), has a compounding positive effect for how effectively this process works. In the same way that so much of agentic coding is about effective context management, learning with LLMs is more effective when one injects just the right amount of rigor and context into the conversation. If I ask a model about a topic involving information theory, or reinforcement learning, or another topic that I have spent a lot of time thinking about, I want it to reference my own thinking structure, my preferred notation, and so on. I ideally want to bring along a tiny textbook which describes exactly how I learned about the subject, and have the LLM adjust its response accordingly, even if that response ends up poking holes in my own framework [1].

This only seems to work well if my notes are indeed a faithful representation of my current state of knowledge. That means that I have to follow a strict rule about not allowing LLM outputs directly into my note system. Whatever insight I glean from the LLM's output, I rewrite in my own words. The language model is a co-editor and an ever-present collaborator, but I have trust that if I come across an explanation in my personal walled garden of notes at some later point, that explanation previously made sense to me and was written by me. No thinking-slop.

Keeping detailed wiki-like notes purely for one's own learning process is not at all novel. But what feels different about learning new subjects now is the loop of getting instant critique of your thinking process. It feels rewarding to have the ability to ask questions, in a form of Socratic dialogue with an LLM, and have answers calibrated to just the right level of difficulty.

Writing notes is time-consuming, and I generally have more motivation to invest in this process when there are verifiable results of some sort. The best scenarios are those where there is a known result or proof, or a piece of code I can run for myself. But even in more abstract settings, good explanations, including those from LLMs, have a kind of revealing quality that suddenly link some latent knowledge that was already floating around, in a kind of "aha!" moment.

This all leads to a different style of pedagogy, particularly well-suited for a messy learning process full of curious detours and depth-first searches, and re-entering the knowledge graph from different nodes. Static textbooks fall short in this setting, because the learning path is so non-linear. And for whatever limitations one could articulate about LLMs hallucinating or being creative in new fields, education and learning about known subjects is clearly a winning use-case, because the task is essentially "translate this well-grounded explanation from one understanding level to another". And so as long as I bring my own detailed context, a kind of tiny textbook for [an audience of one](https://kk.org/thetechnium/an-audience-of-one/), the model can meet me at the edge of my current knowledge, which is exactly where it is most helpful.

---

[1] Actually, this is the preferred outcome. One of my favorite new activities when new frontier models come out is to copy-paste subgraphs of my Obsidian notes into the LLM and ask it to find inconsistencies or gaps or areas for improvement. I'm usually surprised about the non-trivial improvements it finds.
