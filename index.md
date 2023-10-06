---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

permalink: /
title: "Towards Generalist Robots: <br> Learning Paradigms for Scalable Skill Acquisition"
list_title: Home
layout: home
---
<p style="text-align: center;"><font size="5">Conference on Robot Learning 2023, Atlanta, USA</font></p>
<p style="text-align: center;"><font size="5">Monday, Nov 6th, 2023
</font></p>

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


&nbsp;
&nbsp;


### Call for papers

We invite submissions including but not limited to the following topics:

- Scaling up robotic data with generative AI

- Exploiting knowledge from vision and language foundation models for robotics

- Scalable skill learning in simulation and sim-to-real transfer

- Scalable real-world data collection and robot learning

- Learning robotic foundation models by leveraging internet-scale data


**Important Dates**
- **Paper submission open**: 2023/09/07

- **Paper submission deadline**: 2023/10/06 (Extended to 2023/10/08 AoE)

- **Notification of acceptance**: 2023/10/16

- **Workshop date**: 2023/11/06

- **Submission portal**: [CoRL 2023 Workshop TGR (OpenReview)](https://openreview.net/group?id=robot-learning.org/CoRL/2023/Workshop/TGR).

We expect submissions with 4 - 8 pages for the main content, with no limit on references/appendices. Submissions are suggested to use the [CoRL template](https://drive.google.com/file/d/1Ksqw_9OMiCKEiGmoaqn3QCuqcRpgtZ5a/view) and must be anonymized. All papers will be peer-reviewed in a double-blind manner. We welcome both unpublished original contributions and recently published relevant works. Accepted papers will be presented in the form of posters, with several papers being selected for spotlight sessions. 

**Contact**

If you have any questions, please contact us at: generalistrobots@gmail.com.

&nbsp;
&nbsp;
### Invited Speakers
&nbsp;

<div class="grid">
    <div class="grid-item">
        <figure>
        <img src="assets/img/speakers/shuran_song.jpeg" width="200"/>
        <figcaption><b><a href="https://shurans.github.io/">Shuran Song</a></b><br>Stanford University</figcaption>
        </figure>
    </div>
    <div class="grid-item">
        <figure>
        <img src="assets/img/speakers/sergey_levine.png" width="200" /> 
        <figcaption><b><a href="https://people.eecs.berkeley.edu/~svlevine/">Sergey Levine</a></b><br>UC Berkeley</figcaption>
        </figure>
    </div>
    <div class="grid-item">
        <figure>
        <img src="assets/img/speakers/abhinav_gupta.jpeg" width="200" />
        <figcaption><b><a href="http://www.cs.cmu.edu/~abhinavg/">Abhinav Gupta</a></b><br>CMU</figcaption>
        </figure>
    </div>
    <div class="grid-item">
        <figure>
        <img src="assets/img/speakers/dhruv_batra.jpeg" width="200" />
        <figcaption><b><a href="https://faculty.cc.gatech.edu/~dbatra/">Dhruv Batra</a></b><br>Georgia Tech & Meta AI</figcaption>
        </figure>
    </div>
    <div class="grid-item">
        <figure>
        <img src="assets/img/speakers/ming_lin.jpeg" width="200" />
        <figcaption><b><a href="https://www.cs.umd.edu/~lin/">Ming C. Lin</a></b><br>University of Maryland, College Park</figcaption>
        </figure>
    </div>
    <div class="grid-item">
        <figure>
        <img src="assets/img/speakers/karen_liu.png" width="200" />
        <figcaption><b><a href="https://profiles.stanford.edu/c-karen-liu">Karen Liu</a></b><br>Stanford University</figcaption>
        </figure>
    </div>
    <div class="grid-item">
        <figure>
        <img src="assets/img/speakers/chuang_gan.jpeg" width="200" />
        <figcaption><b><a href="https://people.csail.mit.edu/ganchuang/">Chuang Gan</a></b><br>UMass Amherst & MIT-IBM AI Lab</figcaption>
        </figure>
    </div>
    <div class="grid-item">
        <figure>
        <img src="assets/img/speakers/he_wang.jpeg" width="200" />
        <figcaption><b><a href="https://hughw19.github.io/">He Wang</a></b><br>Peking University</figcaption>
        </figure>
    </div>
    <div class="grid-item">
        <figure>
        <img src="assets/img/speakers/dieter.jpg" width="200" />
        <figcaption><b><a href="https://homes.cs.washington.edu/~fox/">Dieter Fox</a></b><br>University of Washington & Nvidia</figcaption>
        </figure>
    </div>
    <div class="grid-item">
        <figure>
        <img src="assets/img/speakers/davide_scaramuzza.jpeg" width="200" />
        <figcaption><b><a href="https://rpg.ifi.uzh.ch/people_scaramuzza.html">Davide Scaramuzza</a></b><br>University of Zurich</figcaption>
        </figure>
    </div>
</div>

&nbsp;


### Organizers
&nbsp;


<div class="grid">
    <div class="gridorg-item">
        <figure>
        <img src="assets/img/organizers/zhou_xian.webp" width="200"/>
        <figcaption><b><a href="https://www.zhou-xian.com/">Zhou Xian</a></b><br>CMU</figcaption>
        </figure>
    </div>
    <div class="gridorg-item">
        <figure>
        <img src="assets/img/organizers/theophile_gervet.jpeg" width="200" /> 
        <figcaption><b><a href="https://theophilegervet.github.io/">Theophile Gervet</a></b><br>CMU</figcaption>
        </figure>
    </div>
    <div class="gridorg-item">
        <figure>
        <img src="assets/img/organizers/zhenjia_xu.jpeg" width="200" />
        <figcaption><b><a href="https://www.zhenjiaxu.com/">Zhenjia Xu</a></b><br>Columbia University</figcaption>
        </figure>
    </div>
    <div class="gridorg-item">
        <figure>
        <img src="assets/img/organizers/yi_ling_qiao.jpeg" width="200" />
        <figcaption><b><a href="https://ylqiao.net/">Yi-Ling Qiao</a></b><br>UMD, College Park</figcaption>
        </figure>
    </div>
    <div class="gridorg-item">
        <figure>
        <img src="assets/img/organizers/tsun_hsuan_wang.jpeg" width="200" />
        <figcaption><b><a href="https://zswang666.github.io/">Tsun-Hsuan Wang</a></b><br>MIT</figcaption>
        </figure>
    </div>
    <div class="gridorg-item">
        <figure>
        <img src="assets/img/organizers/yian_wang.JPG" width="200" />
        <figcaption><b><a href="https://generalist-robots.github.io/">Yian Wang</a></b><br>UMass Amherst</figcaption>
        </figure>
    </div>
    <div class="gridorg-item">
        <figure>
        <img src="assets/img/organizers/chen_wang.jpeg" width="200" />
        <figcaption><b><a href="https://www.chenwangjeremy.net/">Chen Wang</a></b><br>Stanford University</figcaption>
        </figure>
    </div>
    <div class="gridorg-item">
        <figure>
        <img src="assets/img/organizers/katerina_fragkiadaki.png" width="200" />
        <figcaption><b><a href="https://www.cs.cmu.edu/~katef/">Katerina Fragkiadaki</a></b><br>CMU</figcaption>
        </figure>
    </div>
    <div class="gridorg-item">
        <figure>
        <img src="assets/img/organizers/david_held.png" width="200" />
        <figcaption><b><a href="https://davheld.github.io/">David Held</a></b><br>CMU</figcaption>
        </figure>
    </div>
    <div class="gridorg-item">
        <figure>
        <img src="assets/img/organizers/chris_atkeson.jpeg" width="200" />
        <figcaption><b><a href="http://www.cs.cmu.edu/~cga/">Chris Atkeson</a></b><br>CMU</figcaption>
        </figure>
    </div>
    <div class="gridorg-item">
        <figure>
        <img src="assets/img/organizers/josh_tenenbaum.jpeg" width="200" />
        <figcaption><b><a href="http://web.mit.edu/cocosci/josh.html">Josh Tenenbaum</a></b><br>MIT</figcaption>
        </figure>
    </div>
    <div class="gridorg-item">
        <figure>
        <img src="assets/img/organizers/daniela_rus.jpeg" width="200" />
        <figcaption><b><a href="https://danielarus.csail.mit.edu/">Daniela Rus</a></b><br>MIT</figcaption>
        </figure>
    </div>
</div>

