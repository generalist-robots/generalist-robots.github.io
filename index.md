---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

permalink: /
title: "Towards Generalist Robots: <br> Learning Paradigms for Scalable Skill Acquisition"
list_title: Home
layout: home
---

We have witnessed very impressive progress in large-scale and multi-modal foundation/generative models in recent months. We believe making use of such models in a reasonable way could really enable robots to acquire diverse skills. In the recent <a href="https://arxiv.org/pdf/2305.10455.pdf">white paper</a>, we discussed how we can automate the whole pipeline for robotic skill learning, from low-level asset generation, texture generation, to high-level scene, task and reward generation. Once we obtain such a diverse suite of tasks and environments, we can offload policy training to RL of trajectory optimization to solve all the generated low-level tasks, and finally distill all the learned closed-loop policy into a unified policy model. Apart from scaling up in simulation, how to use real-world data more effectively is another promising research direction. Real-world human demonstrations can be found at scale, but typically only provides spatial trajectory information and doesn't advise how to recover from error compounding during policy rollout.

![](assets/img/banner.jpg)

Motivated by these observations and thoughts, this workshop seeks to discuss and compare the advantages and limitations of different paradigms for scaling up skill learning: scaling up simulation, leveraging generative models, exploiting unstructured passive human demonstration, scaling up structured demonstration collection in the real world, etc.

We aim to discuss questions including, but not limited to:
- Is automating task and scene generation in simulation a valid paradigm to pursue? 
- Are today's simulators capable of simulating diverse physical phenomena that would be encountered in real-world robotic tasks? 
- Is sim2real transfer a major bottleneck? What are the potential solutions to it? 
- What are the pros and cons of collecting learning from real-world data compared to simulated data? 
- How to make collecting and learning from real-world data more efficient and effective? 
- Is there a way to combine the strengths of both simulated and real-world data for learning generalist robots?



We will be covering the following topics:
- Scaling up robotic data with generative AI
- Exploiting knowledge from vision and language foundation models for robotics
- Scalable skill learning in simulation and sim-to-real transfer
- Scalable real-world data collection and robot learning
- Learning robotic foundation models by leveraging internet-scale data


<!-- The theme is quite easy to use if you're familiar with Jekyll. The following collections are implemented:
1. **Speakers**: Curate a [speaker list like this one](speakers) from a set of markdown files, one per speaker. Crops and displays images if available. Adds a short bio. See files in the `_speakers` directory for examples.
2. **Organizers**: Curate an organizer list from a set of markdown files, one per organizer. See files in the `_organizers` directory for examples.
3. **Schedule**: Curate a [schedule like this](schedule) from a set of markdown files, one per event (talk, panel, break, etc.). See files in the `_schedule` directory for examples. Schedule items are sorted by a `sequence_id` attribute.
4. **Papers**: Curate a [list of papers like this](papers) from a bunch of markdown files, one per paper. See files in the `_papers` directory for examples. Papers are sorted by a `sequence_id` attribute if specifed (else they are listed alphabetically).

> **NOTE:** The best way to use these is to turn feature on or off by editing the `collections` attribute in `_config.yml`.

If you experience issues or have cool features to add, feel free to [fork this template](). -->
