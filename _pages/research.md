---
title: "Research"
layout: splash
permalink: /research/
collection: research
intro:
  - title: "Selected Publications"
    excerpt: "Below is a brief collection of my academic research. For more detailed information, please reference the full papers on my Google Scholar page."
    url: "https://scholar.google.com/citations?user=mgQTjk0AAAAJ&hl=en"
    btn_label: "Google Scholar Link"
feature_row:
  - image_path: images/papers/cospar.png
    title: "Preference-Based Learning for Exoskeleton Gait Optimization"
    excerpt: Maegan Tucker\*, Ellen Novoseller\*, Claudia Kann, Yanan Sui, Yisong Yue, Joel W. Burdick, and Aaron D. Ames (\*Equal Contribution)  <br/> *ICRA 2020 (Best Overall Conference Paper, Best Paper in Human-Robot Interaction)*
    url: https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9196661&casa_token=O8_jDztcpcgAAAAA:TvobDsEUHHz-BvRsVjYnnmDd6KnmsMh-sLF22RciK9N-hfzv9xOPc0Ro8YAbmQjOGfwXyYzc&tag=1
    btn_label: "Paper"
    url2: https://www.youtube.com/watch?time_continue=4&v=-27sHXsvONE&feature=emb_title
    btn_label2: "Video"
    url3: https://sites.google.com/view/cospar/
    btn_label3: "More Info"
  - image_path: images/papers/var_assist.png
    title: "Towards variable assistance for lower body exoskeletons"
    excerpt: Thomas Gurriet, Maegan Tucker, Alexis Duburcq, Guilhem Boeris, Aaron D Ames  <br/> *RA-L with ICRA Option 2020*
    url: https://ieeexplore.ieee.org/abstract/document/8913630
    btn_label: "Paper"
    url2: https://www.youtube.com/watch?v=UJC5j4BFxyo&feature=youtu.be
    btn_label2: "Video"
  - image_path: images/papers/roial.png
    title: "ROIAL: Region of interest active learning for characterizing exoskeleton gait preference landscapes"
    excerpt: Kejun Li, Maegan Tucker, Erdem Bıyık, Ellen Novoseller, Joel W Burdick, Yanan Sui, Dorsa Sadigh, Yisong Yue, Aaron D Ames <br/> *ICRA 2021*
    url: https://arxiv.org/pdf/2011.04812.pdf
    btn_label: "Paper"
    url2: https://www.youtube.com/watch?v=04lMJmKmZrQ
    btn_label2: "Video"
    url3: https://sites.google.com/view/roial-icra2021
    btn_label3: "More Info"
  - image_path: images/papers/icra2021-hzd.png
    title: "Preference-based learning for user-guided HZD gait generation on bipedal walking robots"
    excerpt: Maegan Tucker, Noel Csomay-Shanklin, Wen-Loong Ma, Aaron D Ames <br/> *ICRA 2021*
    url: https://arxiv.org/pdf/2011.05424.pdf
    btn_label: "Paper"
    url2: https://www.youtube.com/watch?v=rLJ-m65F6C4&feature=youtu.be
    btn_label2: "Video"
    url3: https://maegant.github.io/ICRA2021-LearningHZD/
    btn_label3: "More Info"
  - image_path: images/papers/linecospar.png
    title: "Human Preference-Based Learning for High-dimensional Optimization of Exoskeleton Walking Gaits"
    excerpt: Maegan Tucker, Myra Cheng, Ellen Novoseller, Richard Cheng, Yisong Yue, Joel W Burdick, Aaron D Ames <br/> *IROS 2020*
    url: https://arxiv.org/pdf/2003.06495.pdf
    btn_label: "Paper"
    url2: https://www.youtube.com/watch?v=c6a0kXMyML0
    btn_label2: "Video"
  - image_path: images/papers/ral2022.png
    title: "Natural Multicontact Walking for Robotic Assistive Devices via Musculoskeletal Models and Hybrid Zero Dynamics"
    excerpt: Kejun Li, Maegan Tucker, Rachel Gehlhar, Yisong Yue, Aaron D Ames <br/> *In Review RA-L with ICRA Option 2022*
    url: https://arxiv.org/pdf/2109.05113.pdf
    btn_label: "Paper"
    url2: https://www.youtube.com/watch?v=gNL0cG1zqS4&feature=youtu.be
    btn_label2: "Video"
  - image_path: images/papers/spinal.png
    title: "Evaluation of safety and performance of the self balancing walking system Atalante in patients with complete motor spinal cord injury"
    excerpt: Jacques Kerdraon, Jean Gabriel Previnaire, Maegan Tucker, Pauline Coignard, Willy Allegre, Emmanuel Knappen, Aaron Ames <br/> *Spinal Cord Series and Cases 2021*
    url: https://rdcu.be/cr3Lc
    btn_label: "Paper"
  - image_path: images/papers/PBL_control.png
    title: "Learning Controller Gains on Bipedal Walking Robots via User Preferences"
    excerpt: Noel Csomay-Shanklin, Maegan Tucker, Min Dai, Jenna Reher, Aaron D Ames <br/> *In Review ICRA 2022*
    url: https://arxiv.org/pdf/2102.13201.pdf
    btn_label: "Paper"
    url2: https://www.youtube.com/watch?v=wrdNKK5JqJk&feature=youtu.be
    btn_label2: "Video"
  - image_path: images/papers/SA-linecospar.png
    title: "Safety-Aware Preference-Based Learning for Safety-Critical Control"
    excerpt: Ryan K Cosner, Maegan Tucker, Andrew Taylor, Kejun Li, Tamás G. Molnár, Wyatt Ubellacker, Anil Alan, Gábor Orosz, Yisong Yue, and Aaron D Ames <br/> *In Review L4DC 2022*
    url: https://arxiv.org/pdf/2112.08516.pdf
    btn_label: "Paper"
    url2: https://vimeo.com/649746749
    btn_label2: "Video"
---

<!-- My research is centered around human-robot interaction and control of bipedal robotics. More specifically, my research has three different branches: 
- Utilizing preference-based learning to optimize exoskeleton user comfort and characterize the corresponding preference landscapes
- Implementing preference-based learning directly in the gait generation process for bipedal robots
- Control of a 18 degree-of-freedom lower-body exoskeleton, Atalante. 

---
### Preference-Based Learning to Optimize and Characterize Exoskeleton User Preferences
First, we developed a novel algorithm, CoSpar, that utilized methods from preference-elicitation to learn the underlying preference function of exoskeleton users. This framework was first verified in simulation, and then experimentally conducted for 3 able-bodied subjects. The experiments explored obtaining both 1 and 2 dimensional bayesian posteriors. The first publication of this work received Best Overall Paper at ICRA 2020, as well as Best Paper in Human-Robot Interaction. Later, we also extended this work to optimize over higher-dimensional action spaces using dimensionality reduction techniques.

We also extend preference-based learning to an active-learning setting to characterize the entire landscape of exoskeleton user preferences. The result of this method enables a better understanding of the underlying utility function dictating user preferences. This was accomplished by leveraging Information Gain as the method of posterior sampling. The final algorithm was termed Region of Interest Active Learning (ROIAL). ROIAL was first verified in simulation, and then experimentally conducted for 3 able-bodied subjects in which the preference-landscapes were obtained over 4 exoskeleton gait parameters. 

#### Associated Publications:

* **Tucker, M.**, Novoseller, E., Kann, C., Sui, Y., Yue, Y., Burdick, J., & Ames, A. D. (2019). Preference-Based Learning for Exoskeleton Gait Optimization. In 2020 IEEE International Conference on Robotics and Automation (ICRA), 2020.  IEEE ICRA Best Overall Paper Award. IEEE ICRA Best Paper in Human-Robot Interaction Award.
<center>
<iframe width="560" height="315" src="https://www.youtube.com/embed/-27sHXsvONE" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</center>

<br>
* **Tucker, M.**, Cheng, M., Novoseller, E., Cheng, R., Yue, Y., Burdick, J. W., & Ames, A. D. (2020). Human Preference-Based Learning for High-dimensional Optimization of Exoskeleton Walking Gaits. In 2020 IEEE International Conference on Intelligent Robots and Systems (IROS), 2020.  
<center><iframe src="https://player.vimeo.com/video/394608113" width="640" height="360" frameborder="0" allow="autoplay; fullscreen" allowfullscreen></iframe>
</center>

<br>
* Li, K., **Tucker, M.**, Bıyık, E., Novoseller, E., Burdick, J.W., Sui, Y., Sadigh, D., Yue, Y. and Ames, A.D. (2020). ROIAL: Region of Interest Active Learning for Characterizing Exoskeleton Gait Preference Landscapes. Under Review.
<center><iframe src="https://player.vimeo.com/video/473970586" width="640" height="360" frameborder="0" allow="autoplay; fullscreen" allowfullscreen></iframe>
</center>

---
### Preference-Based Learning Towards Gait Generation
Through careful construction of the Hybrid Zero Dynamics (HZD) gait generation framework, preference-based learning can be used to tune various optimization constraints. So far, we have experimentally demonstrated this framework on the planar robot AMBER-3M with two different leg configurations: rigid point feet and compliant point feet. For both leg configurations the model used for gait generation was the rigid point foot model. However, the framework was still capable of realizing dynamic, stable, and robust walking for both leg configurations -- demonstrating the power of utilizing preference-based learning in the gait generation process.

#### Associated Publications:
* **Tucker, M.**, Csomay-Shanklin, N., Ma, W.L. and Ames, A.D. (2020). Preference-Based Learning for User-Guided HZD Gait Generation on Bipedal Walking Robots. Under Review.
<center><iframe src="https://player.vimeo.com/video/473917519" width="640" height="360" frameborder="0" allow="autoplay; fullscreen" allowfullscreen></iframe></center>

---
### Towards Variable Assistance via Controlled Set Invariance
In this work, we proposed and demonstrated a method of acheiving variable assitance on the exoskeleton. This framework used tools from controlled set invariance, specifically control barrier functions. This framework was validated through two separate experiments. The results of these experiments showed that lower levels of exoskeleton assistence resulted in higher metabolic expenditure rates for 8 able-bodied subjects.

#### Associated Publications:
* Gurriet, T., **Tucker, M.**, Duburcq, A., Boeris, G., & Ames, A. D. (2019). Towards Variable Assistance for Lower Body Exoskeletons. IEEE Robotics and Automation Letters, 5(1), 266-273.
<center>
<iframe width="560" height="315" src="https://www.youtube.com/embed/UJC5j4BFxyo" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</center>
-->

{% include feature_row id="intro" type="center" %}

{% include feature_row type="left" %}

<!-- 
{% include feature_row id="feature_row2" type="left" %}

{% include feature_row id="feature_row3" type="left" %}
  -->