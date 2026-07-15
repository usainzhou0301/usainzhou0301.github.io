---
layout: home
title: "Quanxi ZHOU"
permalink: /
---

<style>
/* ============ Quanxi Zhou — homepage theme (UTokyo blue) ============ */
:root{
  --ink:#1a1a1a;
  --muted:#5b6472;
  --line:#e4e8ee;
  --blue:#1B3A6B;        /* deep academic blue */
  --blue-mid:#2E6BB8;    /* accent / links */
  --blue-soft:#eef3fb;   /* card / chip background */
  --blue-bar:#2E6BB8;    /* left accent bar */
}

.qz{
  font-size:15px;
  line-height:1.65;
  color:var(--ink);
}
.qz a{ color:var(--blue-mid); text-decoration:none; }
.qz a:hover{ text-decoration:underline; }

/* ---- Hero / intro ---- */
.qz-hero{
  display:flex;
  gap:22px;
  align-items:flex-start;
  padding:4px 0 6px;
}
.qz-hero img{
  width:118px;
  height:118px;
  object-fit:cover;
  border-radius:14px;
  border:3px solid var(--blue-soft);
  box-shadow:0 4px 14px rgba(27,58,107,.14);
  flex:0 0 auto;
}
.qz-hero .qz-bio{ font-size:14.5px; line-height:1.7; color:#2b2f36; }
.qz-hero .qz-bio strong{ color:var(--blue); }

/* ---- Section heading ---- */
.qz h2{
  font-size:20px !important;
  color:var(--blue) !important;
  border:0 !important;
  padding:0 0 8px 0 !important;
  margin:34px 0 16px 0 !important;
  position:relative;
  letter-spacing:.2px;
}
.qz h2::after{
  content:"";
  position:absolute;
  left:0; bottom:0;
  width:52px; height:3px;
  background:var(--blue-mid);
  border-radius:2px;
}

/* subheading inside a section (e.g. Honors tiers, Journal/Conf) */
.qz h3{
  font-size:15px !important;
  color:var(--blue-mid) !important;
  margin:18px 0 10px 0 !important;
  font-weight:700 !important;
}

/* remove the raw <hr> monotony — hide markdown --- rules */
.qz + hr, .qz hr{ display:none; }

/* ---- Chips (research interests) ---- */
.qz-chips{
  display:flex;
  flex-wrap:wrap;
  gap:9px;
  margin:2px 0 6px;
}
.qz-chips span{
  background:var(--blue-soft);
  color:var(--blue);
  border:1px solid #d7e2f4;
  border-radius:999px;
  padding:5px 13px;
  font-size:13px;
  font-weight:500;
  transition:all .15s ease;
}
.qz-chips span:hover{
  background:var(--blue-mid);
  color:#fff;
  border-color:var(--blue-mid);
}

/* ---- Card grid (experience-type sections) ---- */
.qz-cards{
  display:grid;
  grid-template-columns:repeat(auto-fill,minmax(300px,1fr));
  gap:12px;
}
.qz-card{
  background:#fff;
  border:1px solid var(--line);
  border-left:4px solid var(--blue-bar);
  border-radius:10px;
  padding:12px 15px;
  font-size:13.5px;
  line-height:1.55;
  box-shadow:0 1px 3px rgba(20,40,80,.05);
  transition:transform .14s ease, box-shadow .14s ease, border-color .14s ease;
}
.qz-card:hover{
  transform:translateY(-2px);
  box-shadow:0 6px 18px rgba(27,58,107,.13);
  border-left-color:var(--blue);
}
.qz-card .qz-date{
  display:inline-block;
  color:var(--blue-mid);
  font-weight:700;
  font-size:12.5px;
  margin-bottom:3px;
  letter-spacing:.3px;
}
.qz-card .qz-body{ color:#2b2f36; }
.qz-card .qz-sub{ color:var(--muted); font-size:12.5px; }

/* single-column card list (e.g. student union — longer text) */
.qz-cards.one{ grid-template-columns:1fr; }

/* ---- Publication list ---- */
.qz-pub{
  list-style:none;
  padding:0;
  margin:0;
}
.qz-pub li{
  position:relative;
  padding:10px 14px 10px 16px;
  margin:0 0 8px 0;
  font-size:13.5px;
  line-height:1.6;
  background:#fbfcfe;
  border:1px solid var(--line);
  border-left:3px solid var(--blue-mid);
  border-radius:8px;
  transition:background .14s ease, border-color .14s ease;
}
.qz-pub li:hover{
  background:var(--blue-soft);
  border-left-color:var(--blue);
}
.qz-pub li i{ color:var(--blue); font-style:italic; }
.qz-pub .tag{
  display:inline-block;
  font-size:11px;
  font-weight:700;
  color:#fff;
  background:var(--blue-mid);
  border-radius:5px;
  padding:1px 7px;
  margin-left:4px;
  vertical-align:middle;
  letter-spacing:.3px;
}
.qz-pub .tag.review{ background:#8a6d1f; }
.qz-pub .tag.writing{ background:#7a828c; }
.qz-pub .tag.award{ background:#b23b3b; }

/* ---- Compact two-column lists (reviewer / awards / honors) ---- */
.qz-list{
  columns:2;
  column-gap:36px;
  font-size:13px;
  list-style:none;
  padding:0;
  margin:0;
}
.qz-list li{
  break-inside:avoid;
  padding:4px 0 4px 16px;
  position:relative;
  color:#2b2f36;
}
.qz-list li::before{
  content:"";
  position:absolute;
  left:0; top:11px;
  width:6px; height:6px;
  border-radius:50%;
  background:var(--blue-mid);
}
.qz-list li b{ color:var(--blue); font-weight:700; }

/* ---- Contact ---- */
.qz-contact{
  display:flex;
  gap:22px;
  flex-wrap:wrap;
  font-size:14px;
  padding:4px 0 20px;
}

@media (max-width:640px){
  .qz-hero{ flex-direction:column; align-items:center; text-align:left; }
  .qz-list{ columns:1; }
}
</style>

<div class="qz" markdown="0">

<div class="qz-hero">
  <img src="usain.jpg" alt="Quanxi Zhou" />
  <div class="qz-bio">
    Quanxi Zhou (Usain, 周泉锡) is a Ph.D. student at
    <a href="https://tlab.hongo.wide.ad.jp/ja/">Tsukada Lab</a> of <strong>School of Information Science and Technology, The University of Tokyo</strong>.
    He received the B.Eng. degree from the <strong>College of Information and Electrical Engineering</strong>,
    <strong>China Agricultural University</strong>, Beijing, China, in 2021 in Computer Science and Technology of the Honors Program,
    and received the M.Eng. degree from the <strong>School of Cyber Science and Technology</strong>,
    <strong>Beihang University</strong>, Beijing, China, in 2024, majoring in Cyberspace Security.
  </div>
</div>

<h2>🔬 Research Interests</h2>
<div class="qz-chips">
  <span>Wireless Communication</span>
  <span>Reinforcement Learning</span>
  <span>UAV Trajectory Optimization</span>
  <span>UAV Resource Allocation</span>
  <span>Machine Learning</span>
  <span>Computer Vision</span>
  <span>Remote Sensing</span>
  <span>Homomorphic Encryption</span>
  <span>Privacy-Preserving Computation</span>
  <span>Secure Multi-Party Computation</span>
</div>

<h2>🎓 Educational Experience</h2>
<div class="qz-cards">
  <div class="qz-card"><span class="qz-date">2024.10 – present</span><div class="qz-body">Ph.D. Student, University of Tokyo</div></div>
  <div class="qz-card"><span class="qz-date">2024.04 – 2024.10</span><div class="qz-body">Research Student, University of Tokyo</div></div>
  <div class="qz-card"><span class="qz-date">2021.09 – 2024.01</span><div class="qz-body">M.Eng., Beihang University</div></div>
  <div class="qz-card"><span class="qz-date">2017.09 – 2021.07</span><div class="qz-body">B.Eng., China Agricultural University</div></div>
</div>

<h2>👩‍🏫 Teaching Assistant Experience</h2>
<div class="qz-cards">
  <div class="qz-card"><span class="qz-date">2026.04 – 2027.04</span><div class="qz-body">New Student Tutor, The University of Tokyo</div></div>
  <div class="qz-card"><span class="qz-date">2023.03 – 2023.07</span><div class="qz-body">Research Seminar, Beihang University</div></div>
  <div class="qz-card"><span class="qz-date">2022.03 – 2022.07</span><div class="qz-body">Computer Network Experiment, Beihang University</div></div>
  <div class="qz-card"><span class="qz-date">2020.09 – 2021.07</span><div class="qz-body">Undergraduate Research Program, China Agricultural University</div></div>
</div>

<h2>🏛️ Student Union Roles</h2>
<div class="qz-cards one">
  <div class="qz-card"><span class="qz-date">2022.03 – 2023.09</span><div class="qz-body">President, Graduate Student Union, School of Cyberspace Security, Beihang University</div></div>
  <div class="qz-card"><span class="qz-date">2019.09 – 2020.09</span><div class="qz-body">Minister of Academic Development, Student Union, China Agricultural University</div></div>
</div>

<h2>🛠️ Project Experience</h2>
<h3>National Level</h3>
<div class="qz-cards one">
  <div class="qz-card"><span class="qz-date">2022.10 – 2024.01</span><div class="qz-body">Fully Homomorphic Encryption Core Algorithms and Trustworthiness Verification Methods</div><div class="qz-sub">National Key R&amp;D Program Youth Scientist Project — Beihang University, Grant No. 2023YFB3106200</div></div>
  <div class="qz-card"><span class="qz-date">2019.12 – 2021.03</span><div class="qz-body">Autonomous Transportation Robot for Solar Greenhouse Based on ROS System</div><div class="qz-sub">National College Student Innovation and Entrepreneurship Training Program — China Agricultural University, Grant No. 202010019049</div></div>
</div>
<h3>University Level</h3>
<div class="qz-cards one">
  <div class="qz-card"><span class="qz-date">2019.01 – 2020.03</span><div class="qz-body">System Integration of Shellfish Object Detection Methods Based on Deep Convolutional Networks</div><div class="qz-sub">Undergraduate Research and Training Program — China Agricultural University</div></div>
  <div class="qz-card"><span class="qz-date">2018.12 – 2020.03</span><div class="qz-body">Raspberry System and Intelligent Vehicle with Binocular Recognition Technology</div><div class="qz-sub">Undergraduate Research and Training Program — China Agricultural University</div></div>
</div>

<h2>💼 Internship Experience</h2>
<div class="qz-cards">
  <div class="qz-card"><span class="qz-date">2019.03 – 2019.06</span><div class="qz-body">Chinese Academy of Sciences</div></div>
  <div class="qz-card"><span class="qz-date">2019.10 – 2020.09</span><div class="qz-body">CNPC Research Institute of Petroleum Exploration and Development</div></div>
  <div class="qz-card"><span class="qz-date">2020.12 – 2021.03</span><div class="qz-body">Eastsoft Technology Co., Ltd.</div></div>
  <div class="qz-card"><span class="qz-date">2021.09 – 2021.12</span><div class="qz-body">China Academy of Information and Communications Technology</div></div>
</div>

<h2>📚 Publications</h2>

<h3>Journal</h3>
<ul class="qz-pub">
  <li>"Uncertainty-Aware Multi-Agent Reinforcement Learning for Anti-Interference Trajectory Planning of Cellular-Connected UAVs", Quanxi Zhou, Wencan Mao, Jin Nakazato, Yusheng Ji and Manabu Tsukada, <i>IEEE Transactions on Vehicular Technology</i>, DOI: 10.1109/TVT.2025.3606201.</li>
  <li>"A Feature-Aware Elite-Imitation MARL for Multi-UAV Trajectory Optimization in Mountain Terrain Detection", Quanxi Zhou, Ye Tao, Qianxiao Su, Manabu Tsukada, <i>Drones</i>, DOI: 10.3390/drones9090645.</li>
  <li>"Multi-Modal Trajectory Planning for Emergency-Oriented Air-Ground Collaborative Sensing and Communication", Yaxi Liu, Quanxi Zhou, Wencan Mao, Xulong Li, Wei Huangfu, Manabu Tsukada, Yusheng Ji, Keping Long, <i>IEEE Transactions on Cognitive Communications and Networking</i>, DOI: 10.1109/TCCN.2025.3585254.</li>
  <li>"Cellular Connected UAV Anti-Interference Path Planning Based on PDS-DDPG and TOPEM", Quanxi Zhou, Yongjing Wang, Ruiyu Shen, Jin Nakazato, Manabu Tsukada, Zhenyu Guan, <i>IEEE Journal on Miniaturization for Air and Space Systems</i>, DOI: 10.1109/JMASS.2024.3490762.</li>
  <li>"Research and Analysis of Data Value of Online Shopping Platform", Quanxi Zhou, Computer Programming Skills and Maintenance, 2019(01): 87–89.</li>
  <li>"Analysis of Common Data Preprocessing Technology", Quanxi Zhou, Communications World, 2019, 26(01): 17–18.</li>
  <li>"Analysis of Key Technologies of Internet Information Security in the Data Era", Quanxi Zhou, Information Recording Materials, 2019, 20(01): 115–116.</li>
</ul>

<h3>Conference Paper</h3>
<ul class="qz-pub">
  <li>"Joint Capacity Planning and Resource Allocation for UAV-Assisted Vehicular Fog Computing Using Deep Reinforcement Learning", Quanxi Zhou, Wencan Mao, Manabu Tsukada, Yu Xiao,<i> IEEE FMLDS</i> <span class="tag review"></span></li>
  <li>"Deep Reinforcement Learning for Automated Guided Vehicle Trajectory Planning in Industry 4.0", Quanxi Zhou, Wencan Mao, Yu Xiao, Manabu Tsukada, Yusheng Ji, 2026 <i>IEEE International Conference on Computer Communications (Infocom Workshop)</i> <span class="tag award">Best Paper Runner-Up</span></li>
  <li>"Trajectory Planning for UAV-Based Smart Farming Using Imitation-Based Triple Deep Q-Learning", Wencan Mao*, Quanxi Zhou*, Tomás Couso Coddou, Manabu Tsukada, Liu Yunling, Yusheng Ji, 2026 <i>IEEE International Conference on Robotics &amp; Automation (ICRA)</i> <span class="tag">Co-first Author</span></li>
  <li>"Priority-Aware Flexible Actor-Critic for Task Scheduling of UAV-Assisted Edge Computing", Yunfei Chen, Quanxi Zhou, Wencan Mao, Ye Tao, Guanzhi Liu, Manabu Tsukada, 2026 <i>International Conference on Future and Intelligent Networking (FINE)</i></li>
  <li>"Design of Anti-Interference Path Planning for Cellular-Connected UAVs Based on Improved DDPG", Quanxi Zhou, Yongjing Wang, 2024 <i>10th IEEE International Conference on High Performance and Smart Computing (HPSC)</i>, pp. 71–76, IEEE, May 2024, DOI: 10.1109/HPSC62738.2024.00020.</li>
  <li>"Design of Enterprise Reputation Evaluation Framework Based on Encrypted Decision Tree Algorithm", Quanxi Zhou, Ruiyu Shen, <i>IOS Press</i>, November 21, 2024, DOI: 10.3233/FAIA241133.</li>
</ul>

<h3>Works on arXiv</h3>
<ul class="qz-pub">
  <li>"EIA-SEC: Improved Actor-Critic Framework for Multi-UAV Collaborative Control in Smart Agriculture", Quanxi Zhou, Wencan Mao, Yilei Liang, Manabu Tsukada, Yunling Liu, Jon Crowcroft.</li>
  <li>"FM-EAC: Feature Model-based Enhanced Actor-Critic for Multi-Task Control in Dynamic Environments", Quanxi Zhou, Wencan Mao, Manabu Tsukada, John C.S. Lui, and Yusheng Ji.</li>
  <li>"Trajectory Planning for UAV-Based Smart Farming Using Imitation-Based Triple Deep Q-Learning", Wencan Mao, Quanxi Zhou, Tomás Couso Coddou, Manabu Tsukada, Yunling Liu, Yusheng Ji. <span class="tag">Co-first Author</span></li>
</ul>

<h3>Ongoing Works</h3>
<ul class="qz-pub">
  <li>"CLIFF: A Multi-Modal Remote Sensing Model for Geological Hazard Monitoring Based on Bitemporal UAV Images", Quanxi Zhou, Qianxiao, Xinran Wei, Wencan Mao, Yili Ren, Yunfei Chen, Jianzhong Bi, Mingjun Zhao, and Manabu Tsukada, <i>Remote Sensing</i>. <span class="tag review">Major Revision</span></li>
  <li>"ComLLM: Towards A General Large Language Model for Semantic-Aware Network Optimization", Wencan Mao, Quanxi Zhou, Yilei Liang, Yaxi Liu, Wei Huangfu, Manabu Tsukada, Jon Crowcroft, and Yusheng Ji, <i>IEEE Network Magazine</i>. <span class="tag review">Major Revision</span></li>
  <li>"Feature-Driven Multi-Agent Reinforcement Learning for UAV Trajectory Planning and Resource Allocation in Dynamic Environments", Quanxi Zhou, Wencan Mao, Yilei Liang, Yixuan Liu, Manabu Tsukada, Jon Crowcroft, John C.S. Lui, and Yusheng Ji, <i>IEEE Transactions on Mobile Computing</i>. <span class="tag review">Under Review</span></li>
  <li>"Privacy-Preserving UAV-Assisted Secure Wireless Communication and Computing System Based on Full Homomorphic Encryption", Quanxi Zhou, Wencan Mao, Ye Tao, Manabu Tsukada, Kensuke Fukuda, and Yusheng Ji, <i>IEEE GLOBECOM </i> <span class="tag review">Under Review</span></li>
  <li>"Environment-Aware Multi-UAV Trajectory Planning for Connected Agricultural IoT Systems Using Feature-Driven Reinforcement Learning", Quanxi Zhou, Wencan Mao, Byungjin Cho, Ye Tao, Manabu Tsukada, <i>IEEE Transactions on Vehicular Technology</i> <span class="tag review">Under Review</span></li>
  <li>"Energy Harvesting UAV-Enabled Mobile Edge Computing with Sustainable Wireless Power Transfer Scheme", Jue Wang, Quanxi Zhou, Wencan Mao, Yaxi Liu, Xulong Li, Boxin He, Manabu Tsukada, Wei Huangfu, Keping Long, <i> IEEE Transaction on Sustainable Computing</i><span class="tag review">Under Review</span></li>
  <li>"Automated Guided Vehicle-Enabled Industry 4.0: A Deep Reinforcement Learning Approach", Quanxi Zhou, Wencan Mao, Manabu Tsukada, Yusheng Ji,<i>IEEE Transactions on Industrial Informatics</i> <span class="tag writing">Under Writing</span></li>
</ul>

<h2>📖 External Reviewer</h2>
<ul class="qz-list">
  <li><b>2024</b> IEEE Internet of Things Journal (IOTJ)</li>
  <li><b>2025</b> IEEE Internet of Things Journal (IOTJ)</li>
  <li><b>2025</b> IEEE Vehicular Technology Conference (VTC)</li>
  <li><b>2025</b> The Pacific Rim International Conference on Artificial Intelligence (PRICAI)</li>
  <li><b>2025</b> IEEE International Conference on Communications (ICC)</li>
  <li><b>2026</b> IEEE International Conference on Computer Communications (Infocom)</li>
  <li><b>2026</b> IEEE Transactions on Cognitive Communications and Networking (TCCN)</li>
  <li><b>2026</b> Frontiers in Physics (Front. Phys.)</li>
  <li><b>2026</b> IEEE Global Communications Conference (GLOBECOM)</li>
  <li><b>2026</b> Neural Information Processing Systems (NeurIPS)</li>
  <li><b>2026</b> Intelligent Unmanned Technologies and Systems (IUTS)</li>
</ul>

<h2>🏆 Awards</h2>
<ul class="qz-list">
  <li><b>2026.05</b> Best Paper Runner-Up Award, Infocom Workshop 2026</li>
  <li><b>2024.10</b> SpringGX Award of Utokyo</li>
  <li><b>2024.01</b> Outstanding Graduate of BUAA</li>
  <li><b>2024.01</b> Outstanding Student Leader of BUAA</li>
  <li><b>2022.09</b> Learning Excellence Scholarship of BUAA</li>
  <li><b>2021.03</b> Outstanding Graduation Internship of CAU</li>
  <li><b>2020.03</b> Outstanding Student Leader of CAU</li>
  <li><b>2020.09</b> Social Work Scholarship of CAU</li>
  <li><b>2019.11</b> Graduation from Elite Cadre Training Program</li>
  <li><b>2019.09</b> Learning Excellence Scholarship of CAU</li>
  <li><b>2019.09</b> Social Work Scholarship of CAU</li>
  <li><b>2018.09</b> Learning Excellence Scholarship of CAU</li>
  <li><b>2017.12</b> Outstanding Student Officer of CAU</li>
</ul>

<h2>🥇 Honors</h2>
<h3>National Level Awards</h3>
<ul class="qz-list">
  <li>2021.06 — First Prize, Chinese College Student Agricultural Robot Competition</li>
  <li>2018.10 — Third Prize, Chinese College Students' Advanced Mathematics Competition</li>
</ul>
<h3>Municipal / Provincial Level Awards</h3>
<ul class="qz-list">
  <li>2023.09 — Second Prize, Beijing Round of the China "Internet+" Innovation and Entrepreneurship Competition</li>
  <li>2021.04 — Second Prize, Beijing Round of the Chinese College Student Artificial Intelligence Competition</li>
  <li>2019.11 — Second Prize, Mathematical Modeling and Computer Application Competition</li>
  <li>2018.10 — Second Prize, Beijing College Students' Advanced Mathematics Competition</li>
</ul>
<h3>University Level Awards</h3>
<ul class="qz-list">
  <li>2020.06 — Third Prize, "Xingnong Cup" Innovation and Entrepreneurship Competition</li>
  <li>2020.06 — Bronze Medal, Innovation and Entrepreneurship Competition of CAU</li>
  <li>2020.06 — Bronze Medal, Internet of CAU Competition</li>
  <li>2020.04 — First Prize, Advanced Mathematics Competition</li>
  <li>2019.04 — Second Prize, Advanced Mathematics Competition</li>
  <li>2018.06 — Third Prize, "Minsheng Cup" Modeling Competition</li>
  <li>2018.06 — Excellent Award, Physics Experiment Competition</li>
</ul>

<h2>📬 Contact With Me</h2>
<div class="qz-contact">
  <span>📧 <a href="mailto:usainzhou@g.ecc.u-tokyo.ac.jp">usainzhou@g.ecc.u-tokyo.ac.jp</a></span>
  <span>🔗 <a href="https://scholar.google.com/citations?hl=en&user=P2mHCpgAAAAJ" target="_blank">Google Scholar</a></span>
</div>

</div>
