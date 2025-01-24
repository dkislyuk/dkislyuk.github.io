---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
---

## Work

Currently, I am a director of engineering at Pinterest, leading the computer vision team as part of the Advanced Technologies Group. The vision team works on visual search products, large-scale representation learning (e.g. multimodal embeddings), text-to-image diffusion models, core computer vision signals (e.g. detection, segmentation), visual-language models, and more. I lead a mix of ML research, ML engineering, and product teams.

I completed my masters at Stanford University and my undergraduate CS degree at U.C. Berkeley.

You can reach me at `hi@dkislyuk.com`.

## Not work

Outside of my day-job, I enjoy tinkering on open-ended algorithms (as inspired by the work of Ken Stanley, Jeff Clune, etc.), amateur [running](https://www.strava.com/athletes/5235768), deep-diving into history {podcasts, books, essays}, and spending family time with my wife and young son.

Regarding open-ended algorithms, some of the questions that I ponder include:

- What is the _minimum_ amount of structure needed for evolutionary algorithms to work at modern scale? Deep learning has indicated that human-designed components keep getting more high-level; that hints that classic EA concepts such as mutations, crossover, selection, etc. should not be hardcoded, but instead discovered as part of an open-ended algorithm.

- Is there a place for evolutionary algorithms in the current paradigm of frontier models? Supervised, unsupervised, and reinforcement learning allow for optimization of arbitrary feedforward and recurrent computation graphs at _extreme_ scales, but one problem that still has not been elegantly solved is an automatic design of the computation graphs themselves and the modification of the computation graph at test-time. One viewpoint is that the mega-scale models have so much capacity, that every relevant permutation of a computation circuit to achieve an objective can be discovered inside and selected during test-time. The [Hardware Lottery](https://hardwarelottery.github.io/) makes it daunting to seriously explore non-uniform, EA-designed computation graphs, but it is an interesting question nevertheless.