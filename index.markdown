---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
---

## Work

<img src="assets/dkislyuk.png" alt="Dmitry Kislyuk" style="float: right; width: 200px; margin: 0 0 20px 20px;">

Currently, I am a director of engineering at Pinterest, leading the visual AI team as part of the Advanced Technologies Group. Our team works on visual search products, large-scale representation learning (e.g. multimodal embeddings and VLMs), diffusion models, core computer vision signals (e.g. detection, segmentation), agentic search, and more. I lead a mix of ML research, ML engineering, and product teams. Before that, I was at Stanford University for my masters, and U.C. Berkeley for my undergraduate CS education.

You can reach me at `hi@dkislyuk.com`.

## Not work

Outside of my day-job, I enjoy tinkering on open-ended algorithms (as inspired by the work of Ken Stanley, Jeff Clune, etc.), amateur running, and deep-diving into history {podcasts, books, essays}.

Regarding open-ended algorithms, some of the questions that I ponder include:

- What is the _minimum_ amount of structure needed for evolutionary algorithms to work at modern scale? Deep learning has indicated that human-designed components keep getting more high-level; that hints that classic EA concepts such as mutations, crossover, selection, etc. should not be hardcoded, but instead discovered as part of an open-ended algorithm.

- Is there a place for evolutionary algorithms in the current paradigm of frontier models? Supervised, unsupervised, and reinforcement learning allow for optimization of arbitrary feedforward and recurrent computation graphs at _extreme_ scales, but one problem that still has not been elegantly solved is an automatic design of the computation graphs themselves and the modification of the computation graph at test-time. One viewpoint is that the mega-scale models have so much capacity, that every relevant permutation of a computation circuit to achieve an objective can be discovered inside and selected during test-time. The [Hardware Lottery](https://hardwarelottery.github.io/) makes it daunting to seriously explore non-uniform, EA-designed computation graphs, but it is an interesting question nevertheless.

- To what extent can agentic systems replace various EA components: for example, can LLM-guided permutations of computation graphs result in a more interesting open-ended computation system?