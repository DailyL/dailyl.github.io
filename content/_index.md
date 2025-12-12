---
title: "Dianzhao Li"
---

<style>

  
/* Publication entry with image on left by default */
.pub-entry {
  display: flex;
  flex-direction: row;
  gap: 20px;
  margin-bottom: 25px;
  align-items: flex-start;
  border-bottom: 1px dashed #e1e4e8;
  padding-bottom: 20px;
}

.pub-entry:last-of-type {
  border-bottom: none;
}

/* For right-aligned images (use class="pub-entry right") */
.pub-entry.right {
  flex-direction: row-reverse;
}

.pub-entry img {
  max-width: 250px !important;
  width: 250px !important;
  height: auto !important;
  border: 2px solid #d0d0d0 !important;
  border-radius: 6px !important;
  padding: 6px !important;
  background: #fff !important; 
  box-shadow: 0 2px 4px rgba(0,0,0,.08) !important;
  flex-shrink: 0;
}

.pub-text {
  flex-grow: 1;
}

.pub-links {
  margin-top: 5px;
}

.pub-links a {
  display: inline-block;
  margin-right: 15px;
  color: #0366d6;
  transition: color 0.2s;
  font-size: 0.9em;
  text-decoration: none;
  font-weight: 500; /* Make bolder */
}

.pub-links a:hover {
  color: #0056b3;
  text-decoration: underline;
}

.pub-links i {
  font-size: 1.1em;
}

@media (max-width: 650px) {
  .pub-entry, .pub-entry.right {
    flex-direction: column;
  }
}
</style>

# About Me {#about-me}

I am a doctoral candidate at <a href="https://rl-dresden.de/"><strong>RL Dresden</strong></a> and Technische Universität Dresden, supervised by Prof. Ostap Okhrin, and a research scientist at <a href="https://scads.ai/"><strong>ScaDS.AI Dresden/Leipzig</strong></a>.

My research focuses on reinforcement learning for autonomous driving: developing RL solutions for diverse driving tasks, closing the sim-to-real gap for small-scale vehicles, and advancing ethical decision-making so autonomous systems are more responsible and reliable in real-world deployments.


# 📰 News {#news}
- *2025.12* : An interview with me was published in NASW (National Association of Science Writers), where I discussed about how small robot vehicles can drive research and education innovation. The article is available here: [NASW Interview](https://www.nasw.org/article/small-robot-vehicles-drive-research-and-education-innovation).  
- *2025.11* : I gave a talk at Safe Autonomy Seminar hosted by [xLAB](https://xlab.upenn.edu/) at the University of Pennsylvania, lead by Prof. [Rahul Mangharam](https://www.seas.upenn.edu/~rahulm/). The recording of the talk is available here: [video link](https://www.youtube.com/watch?v=h4BPvnphF8E).   
- *2025.08* : Our paper on ethical and responsible autonomous driving agents is now online.
- *2025.06* : Our survey paper focus on autonomous driving research for small-scale cars have been accepted for publication by **IEEE TITS**.
- *2024.10* : Our research was featured by [Duckietown news ](https://contact.duckietown.com/duckietown-newsletter-update-october-2024?ecid=ACsprvtA3PlMo41ijBjESipUOlcj4-qu1bx0yEvcIOXGfqr5P8lQCALi5sh2ymNLrcsRbO3QA75s&utm_campaign=Mailing%20List&utm_medium=email&_hsenc=p2ANqtz-_6xVoHlLWkJ6aQZZvPXRu6d2v6IQfJHqDBHVq7NFg7Sfa73ClCYNeH44aSvyD2pwpb-b_DIRUZen7JB3hCqw0hGhzEapX_4p8dAmLBsKJANr7xj5M&_hsmi=328126945&utm_content=328126945&utm_source=hs_email).
- *2024.10* : Our paper with platform-agnostic DRL framework for Sim2Real transfer  have been accepted for publication by **Communications Engineering**.
- *2023.09* : Our paper focus on vision-based DRL car following with Sim2Real transfer have been accepted for **IEEE ITSC**.
- *2023.04* : I am offcialy a doctoral candidate in TU Dresden. 
- *2023.02* : Our paper *Modified DDPG car-following model with a real-world human driving experience with CARLA simulator* have been accepted for publication by **TRC**.
- *2022.10* : I attend the [27th Young Scientists Workshop](https://statistische-woche.de/en/startseite-en) in Statistical Week 2022.
- *2022.09* : We successfully hosted the [Conference on Reinforcement Learning 2022 Dresden](https://sites.google.com/view/rlconferencedresden/home). A big thank you to all who attended and contributed to making it a success!

# 📝 Publications {#publications}

<div class="pub-entry">
  <img src="/images/ethic.png" alt="Sim2Real Pipeline">
  <div class="pub-text">
    <span class="pub-title">
      <strong><em>Learning to Drive Ethically: Embedding Moral Reasoning into Autonomous Driving</em></strong>
    </span><br>
    <span><strong>Dianzhao Li</strong>, Ostap Okhrin</span><br>
    <span class="pub-venue">Under review (Nature Communications), 2025.</span>
    <div class="pub-links">
    <a href="https://arxiv.org/abs/2508.14926" target="_blank" title="Paper"><strong>Paper</strong></a>
    <a href="https://github.com/DailyL/EDRL" target="_blank" title="Code"><i class="fab fa-github"></i></a>
     </div>
  </div>
</div>



<div class="pub-entry">
  <img src="/images/survey.png" alt="Sim2Real Pipeline">
  <div class="pub-text">
    <span class="pub-title">
      <strong><em>Autonomous Driving Small-Scale Cars: A Survey of Recent Development</em></strong>
    </span><br>
    <span><strong>Dianzhao Li</strong>, Paul Auerbach, Ostap Okhrin</span><br>
    <span class="pub-venue">IEEE Transactions on Intelligent Transportation Systems (IEEE TITS), 2025.</span>
    <div class="pub-links">
    <a href="https://ieeexplore.ieee.org/abstract/document/11034663" target="_blank" title="Paper"><strong>Paper</strong></a>
    <a href="https://github.com/DailyL/small-scale-autonomous-cars" target="_blank" title="Project Page"><strong>Project</strong></a>
     </div>
  </div>
</div>


<div class="pub-entry">
  <img src="/images/ot.png" alt="Sim2Real Pipeline">
  <div class="pub-text">
    <span class="pub-title">
      <strong><em>A platform-agnostic deep reinforcement learning framework for effective sim2real transfer towards autonomous driving</em></strong>
    </span><br>
    <span><strong>Dianzhao Li</strong>, Ostap Okhrin</span><br>
    <span class="pub-venue">Communications Engineering, 2024.</span>
    <div class="pub-links">
      <a href="https://www.nature.com/articles/s44172-024-00292-3" target="_blank" title="Paper"><strong>Paper</strong></a>
      <a href="https://dailyl.github.io/sim2realVehicle.github.io/" target="_blank" title="Project Page"><strong>Project</strong></a>
      <a href="https://github.com/DailyL/Sim2Real_autonomous_vehicle" target="_blank" title="Code"><i class="fab fa-github"></i></a>
    </div>
  </div>
</div>


<div class="pub-entry">
  <img src="/images/cf_duckie.png" alt="Sim2Real Pipeline">
  <div class="pub-text">
    <span class="pub-title">
      <strong><em>Vision-based DRL Autonomous Driving Agent with Sim2Real Transfer</em></strong>
    </span><br>
    <span><strong>Dianzhao Li</strong>, Ostap Okhrin</span><br>
    <span class="pub-venue">IEEE 26th International Conference on Intelligent Transportation Systems (IEEE ITSC), 2023.</span>
    <div class="pub-links">
      <a href="https://ieeexplore.ieee.org/abstract/document/10422677" target="_blank" title="Paper"><strong>Paper</strong></a>
      <a href="https://github.com/DailyL/Sim2Real_autonomous_vehicle" target="_blank" title="Code"><i class="fab fa-github"></i></a>
    </div>
  </div>
</div>


<div class="pub-entry">
  <img src="/images/cf.png" alt="Sim2Real Pipeline">
  <div class="pub-text">
    <span class="pub-title">
      <strong><em>Modified DDPG car-following model with a real-world human driving experience with CARLA simulator</em></strong></a>
    </span><br>
    <span><strong>Dianzhao Li</strong>, Ostap Okhrin</span><br>
    <span class="pub-venue">Transportation research part C: emerging technologies (TRC), 2023.</span>
    <div class="pub-links">
      <a href="https://www.sciencedirect.com/science/article/pii/S0968090X22004004" target="_blank" title="Paper"><strong>Paper</strong></a>
      <a href="https://github.com/DailyL/Modified-DDPG-car-following-model" target="_blank" title="Code"><i class="fab fa-github"></i></a>
    </div>
  </div>
</div>




<!-- - ***[Learning to Drive Ethically: Embedding Moral Reasoning into Autonomous Driving](https://ieeexplore.ieee.org/abstract/document/11034663)*** <br>
  **Dianzhao Li**, Ostap Okhrin, under review, 2025. <br>

- ***[Autonomous Driving Small-Scale Cars: A Survey of Recent Development](https://ieeexplore.ieee.org/abstract/document/11034663)*** <br>
  **Dianzhao Li**, Paul Auerbach, Ostap Okhrin in *IEEE Transactions on Intelligent Transportation Systems* (**IEEE TITS**), 2025. <br>



- ***[A platform-agnostic deep reinforcement learning framework for effective sim2real transfer towards autonomous driving](https://www.nature.com/articles/s44172-024-00292-3)*** <br>
  **Dianzhao Li**, Ostap Okhrin in *Communications Engineering*, 2024. <br>

- ***[Vision-based DRL Autonomous Driving Agent with Sim2Real Transfer](https://ieeexplore.ieee.org/abstract/document/10422677)*** <br>
  **Dianzhao Li**, Ostap Okhrin in *IEEE 26th International Conference on Intelligent Transportation Systems* (**IEEE ITSC**), 2023. <br>

- ***[Modified DDPG car-following model with a real-world human driving experience with CARLA simulator](https://www.sciencedirect.com/science/article/pii/S0968090X22004004)*** <br>
  **Dianzhao Li**, Ostap Okhrin in *Transportation research part C: emerging technologies* (**TRC**), 2023. <br> -->

<!-- # 🎖 Honors and Awards {#honors-and-awards}
- *2021.10* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.09* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
 -->

# 💼 Research Experience {#internships}

<div style="display:flex;align-items:center;gap:28px;margin-bottom:18px;">
  <div style="text-align:center;display:flex;flex-direction:column;justify-content:center;align-items:center;min-width:170px;">
    <img src="/images/logos/ScaDS.AI_Logo.png" alt="ScaDS.AI Logo" style="height:90px;width:160px;object-fit:contain;display:block;margin:auto;">
    <div style="font-size:1em;margin-top:4px;"><em>2021.05 - Present</em></div>
  </div>
  <div style="display:flex;flex-direction:column;justify-content:center;">
    <strong style="font-size:1.1em;">Research Scientist</strong>
    <span style="font-weight:600;">ScaDS.AI Dresden/Leipzig, Germany</span>
    Developed and evaluated reinforcement learning algorithms for autonomous driving, advancing robust policy transfer, cross-framework benchmarking, and simulation-to-real adaptability in high-fidelity environments.
  </div>
</div>

<hr style="border:0;border-bottom:1px dashed #e1e4e8;margin:18px 0;">

<div style="display:flex;align-items:center;gap:28px;margin-bottom:18px;">
  <div style="text-align:center;">
  <img src="/images/logos/precitec_kg_logo.jpeg" alt="Precitec Logo" style="height:90px;width:170px;object-fit:contain;display:block;margin:auto;">
    <div style="font-size:1em;margin-top:4px;"><em>2019.06 - 2019.12</em></div>
  </div>
  <div>
    <strong>Research Intern</strong><br>
    <strong>Precitec GmbH &amp; Co. KG, Germany</strong><br>
    Developed an end-to-end machine learning toolchain with visualization tools, applied to quality monitoring in laser material processing using self-learning vision and multi-sensor systems, including feature engineering and data augmentation.
  </div>
</div>

# 📖 Educations {#educations}

<div style="display:flex;align-items:center;gap:18px;margin-bottom:8px;">
  <div style="text-align:center;">
  <img src="/images/logos/TUD_Logo.svg" alt="TU Dresden Logo" style="height:100px;width:160px;object-fit:contain;display:block;margin:auto;">
    <div style="font-size:1em;margin-top:4px;"><em>2023.05 - Present</em></div>
  </div>
  <div>
    <strong>PhD</strong><br>
    <strong>Technische Universität Dresden</strong><br>
    <em>Advisor: <a href="https://tu-dresden.de/bu/verkehr/ivw/osv/die-professur/inhaber-in"> Prof. Ostap Okhrin </a></em>,  <em><a href="https://liampaull.ca/"> Prof. Liam Paull </a></em>, <em> <a href="https://www.mtreiber.de/"> Dr. Martin Treiber </a> </em><br>
    Dissertation: <strong>Deep Reinforcement Learning for Autonomous Driving: Human-Informed, Ethical, and Transferable Agents</strong>
  </div>
</div>

<hr style="border:0;border-bottom:1px dashed #e1e4e8;margin:18px 0;">

<div style="display:flex;align-items:center;gap:18px;margin-bottom:8px;">
  <div style="text-align:center;">
  <img src="/images/logos/Logo_KIT.svg" alt="KIT Logo" style="height:100px;width:160px;object-fit:contain;display:block;margin:auto;">
    <div style="font-size:1em;margin-top:4px;"><em>2017.03 - 2021.02</em></div>
  </div>
  <div>
    <strong>M.Sc.</strong><br>
    Mechanical Engineering (<em>Mechatronics</em> & <em>Information Technology</em>)<br>
    <strong>Karlsruher Institut für Technologie</strong><br>
    <em>Advisor: <a href="https://www.fast.kit.edu/mobima/mitarbeiter_Geimer.php"> Prof. Marcus Geimer </a></em><br>
    Master Thesis: <a href="https://www.mdpi.com/2624-8921/4/2/31">Where Am I? SLAM for Mobile Machines on a Smart Working Site</a>
  </div>
</div>

<hr style="border:0;border-bottom:1px dashed #e1e4e8;margin:18px 0;">

<div style="display:flex;align-items:center;gap:18px;margin-bottom:8px;">
  <div style="text-align:center;">
  <img src="/images/logos/UPC_logo.png" alt="China University of Petroleum Logo" style="height:100px;width:160px;object-fit:contain;display:block;margin:auto;">
    <div style="font-size:1em;margin-top:4px;"><em>2012.09 - 2016.06</em></div>
  </div>
  <div>
    <strong>B.Sc.</strong><br>
    Mechanical Engineering and Automation (<em>Control Technology</em> & <em>Micro Control Technology</em>)<br>
    <strong>China University of Petroleum (East China)</strong><br>
    <em>Advisor: Prof. Leilei Gao </em><br>
  </div>
</div>

# 📚 Referee for Journals and Conferences {#referee}
- *Since 2024*, IEEE Transactions on Intelligent Transportation Systems
- *Since 2024*, SoftwareX
- *Since 2024*, Scientific Reports
- *Since 2023*, Engineering Applications of Artificial Intelligence
- *Since 2022*, Mathematical Biosciences and Engineering
-  2025 23rd European Control Conference (ECC) 
- Transportation Research Board (TRB) Annual Meeting, Paper Reviewer for: AED30 Standing Committee on Information Systems and Technology and AED50 Standing Committee on Artificial Intelligence and Advanced Computing Application 





# 💻 Teaching {#teaching}
- Theoretical Multivariate Statistics (Master)
- Applied Multivariate Statistics (Master)
- Data-Driven Multivariate Statistics (Master)

<img src="https://counter5.optistats.ovh/private/freecounterstat.php?c=jz6qgzpza7cjpkfhd9uwumf9k5eu42tu" border="0" title="hit counter" alt="hit counter">