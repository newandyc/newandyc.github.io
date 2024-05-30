---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

I received double Ph.D. degrees from Harbin Institute of Technology, China, and University of Groningen, the Netherlands. Before joining SYSU, I worked successively in City University of Hong Kong, Southeast University, China, and Delft University of Technology, the Netherlands.

***Postdoc openings are always available largely in systems and control !***

<span class='anchor' id='research'></span>
# 💡 Research Interests
My curent research interests include cooperative localization 8t guidance 8 control, enhanced observer design, LMl techniques, sbREtechniques, and their applications in multi-robot systems.

- **Cooperative pointing control**
  -  Cooperative pointing control of coplanar multi-robot systems via distributed target estimation
  - Cooperative concurrent targeting for planar arrays of point sources

- **Enclosing Control for Multiagent Systems**
  - Distributed collaborative encirclement of unicycles
 

  <video src="/videos/circle.mp4" autoplay ></video>
  <video src="/videos/circle_distances.mp4"  autoplay></video>

<span class='anchor' id='publications'></span>
# 📝 Publications 

<p><strong>Journal Articles</strong></p>

<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
       <div class="badge">Cooperative pointing control</div>
       <img src='/images/animation1.2.gif' alt="sym" width="100%">
      </div>
    </div>
 <div class='paper-box-text' markdown="1">

[Cooperative concurrent targeting for planar arrays of point sources](https://www.sciencedirect.com/science/article/pii/S000510982300523X)

Pouria Ramazi , **Fan Zhang**, Ming Cao

**Automatica, 2023** <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>

+  We have formulated the distributed concurrent targeting problems for planar arrays of point sources and proposed a novel coordination strategy to solve the problem, where the planar and solid geometry has been used to achieve the design and analysis. There are several possible future directions. One is to consider point sources that are distributed in the space rather than a plane. Another is to consider more detailed rotational dynamics of the point sources, such as double integrators. The target point may also be considered moving rather than fixed in the space.
 </div>
</div>


<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
       <div class="badge">Robust Distributed Interval Observer</div>
       <img src='/images/J22.png' alt="sym" width="100%">
      </div>
    </div>
 <div class='paper-box-text' markdown="1">

[ A robust distributed interval observer for LTI systems](https://ieeexplore.ieee.org/document/9713996/figures#figures)

Xiaoling Wang, Housheng Su, **Fan Zhang**, Guanrong Chen

**ISA Transactions, 2023** <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>

 + A robust distributed interval observer is designed, which consists of a group of sensors communicating with others through a directed graph where each sensor can only access partial information from the output of the plant. The communication among the sensors together with the heterogeneity and undetectability of the sensors result in some stringent requirements on the robust distributed interval observer construction. To resolve these restrictions, the internally positive representation originated from a single agent system is introduced into the robust distributed interval observer. 
 </div>
</div>

[J29] **F. Zhang**, C.L. Jin*, W.G. Xia, X.M. Sun, H. Bai. Cooperative pointing control of coplanar multi-robot systems via distributed target estimation. Automatica, <em>submitted</em>, 2024

[J28] H.X. Hu, G.H. Wen*, Y. Chen,**F. Zhang**, T.W. Huang. Social power evolution analysis for Friedkin-Johnsen model with oblivious individuals. IEEE Transactions on Cybernetics, <em>submitted</em>, 2023

[J27] S.Y. Meng, F.W. Meng*, **F. Zhang**, Q. Li, Y. Zhang, A. Zemouche. Observer design method for nonlinear generalized systems with nonlinear algebraic constraints with applications. Automatica <em>regular paper</em>, <em>online</em>, 2023

[J26] P. Ramazi*, **F. Zhang**, M. Cao. Cooperative concurrent targeting for planar arrays of point sources. Automatica, online, 2023

[J25] **F. Zhang**, Y.L. Li*, W.G. Xia, T. Liu, W.W. Yu. Synchronization of Lur’e networks via heterogeneous unknown interconnections. IEEE Transactions on Circuits and Systems II: Express Briefs, 71(2):807-811, February 2024

[J24] J.Z. Wu, S. Yuan, Q.Q. Dang, **F. Zhang***, W.W. Yu. Cooperative pointing control of collinear double-integrators without angular velocity. Journal of the Franklin Institute, 360(12):9050-9064, August 2023

[J23] T.T. Zhang, S.J. Zhang*, F.Z. Guo, X.T. Zhao, **F. Zhang**. Prescribed time attitude containment control for satellite cluster with bounded disturbances. ISA Transactions, 137:160-174, June 2023

[J22] X.L. Wang, H.S. Su*, **F. Zhang**, G.R. Chen. A robust distributed interval observer for LTI systems. IEEE Transactions on Automatic Control <em>full paper</em>, 68(3):1337-1352, March 2023

[J21] N. Wang, G.H. Wen*, Y. Wang,**F. Zhang**, A. Zemouche. Fuzzy adaptive cooperative consensus tracking of high-order nonlinear multi-agent networks with guaranteed performances. IEEE Transactions on Cybernetics, 52(9):8838-8850, September 2022

[J20] N. Wang, Y. Wang, G.H. Wen*, M.L. Lv, **F. Zhang**. Fuzzy adaptive constrained consensus tracking of high-order multi-agent networks: A new event-triggered mechanism. IEEE Transactions on Systems, Man and Cybernetics: Systems, 52(9):5468-5480, September 2022

[J19] R.W. Zuo, Y.H. Li*, M.L. Lv, Z.C. Liu, **F. Zhang**. Fuzzy adaptive output-feedback constrained trajectory tracking control for HFVs with fixed-time convergence. IEEE Transactions on Fuzzy Systems, 30(11): 4828-4840, September 2022

[J18] **F. Zhang**, G.H. Wen, A. Zemouche, W.W. Yu*, J.H. Park. Output feedback self-synchronization of directed Lur’e networks via global connectivity. IEEE Transactions on Cybernetics, 52(7):6490-6503, July 2022

[J17] S.J. Zhang*, T.T. Zhang, H.B. Guo, **F. Zhang**. General attitude cooperative control of satellite formation by set stabilization. Acta Astronautica, 191:125-133, February 2022

[J16] S. Li, W.G. Xia*, **F. Zhang**. Synchronization of continuous-time linear systems with time-varying output couplings. IEEE Transactions on Industrial Informatics, 18(1):143-152, January 2022

[J15] J.Z. Wu, W.H. Pu, **F. Zhang***, W.W. Yu. Decentralized targeting control of collinear agents. Asian Journal of Control, 24:782–793, 2022

[J14] X.L. Wang, H.S. Su*, **F. Zhang**, A. Zemouche, G.R. Chen. Interval observer design and consensus of multi-agent systems with time-varying interval uncertainties. SIAM Journal on Control and Optimization, 59(5):3392-3417, 2021

[J13] N. Wang, Y. Wang, J.H. Park*, M.L. Lv, **F. Zhang**. Fuzzy adaptive finite-time consensus tracking control of high-order nonlinear multi-agent networks with dead-zone. Nonlinear Dynamics, 106:3363–3378, 2021

[J12] P.F. Lu, H. Wang, **F. Zhang**, W.W. Yu*, G.R. Chen. Formation control of nonholonomic mobile robots using distributed estimators. IEEE Transactions on Circuits and Systems II: Express Briefs, 67(12):3162-3166, 2020

[J11] G.H. Wen*, P.J. Wang, T.W. Huang, J.H. Lv, **F. Zhang**. Distributed consensus of layered multi-agent systems subject to attacks on edges. IEEE Transactions on Circuits and Systems I: Regular Papers, 67(9):3152-3162, 2020

[J10] F.Z. Guo, T.T. Zhang, **F. Zhang**, L. Gao, Z.P. Wang, S.J. Zhang*. Event-triggered coordinated attitude control for satellite formation under switching topology. Advanced Control for Applications: Engineering and Industrial Systems, 2(2):e34, 2020.

[J9] A. Zemouche, **F. Zhang**, F. Mazenc, R. Rajamani*. High-gain nonlinear observer design with lower tuning parameter. IEEE Transactions on Automatic Control <em>full paper</em>, 64(8):3194-3209, 2019

[J8] X.D. Chen*, J.M.A. Scherpen, **F. Zhang**. Model reduction of synchronized Lur’e networks with incrementally sector-bounded nonlinearities. European Journal of Control, 50:11-19, November 2019

[J7] S. Baldi*, **F. Zhang**, T.L. Quang, P. Endel, O. Holu. Passive versus active learning in operation and adaptive maintenance of heating, ventilation, and air conditioning. Applied Energy, 252:113478, October 2019

[J6] S. Yuan*, **F. Zhang**, S. Baldi. Adaptive tracking of switched nonlinear systems with prescribed performance using a reference-dependent reparametrization approach. International Journal of Control, 92(6): 1243-1251, 2019

[J5] **F. Zhang**, H.L. Trentelman*, G. Feng, J.M.A. Scherpen. Absolute stabilization of Lur’e systems via dynamic output feedback. European Journal of Control, 44:15-26, November 2018

[J4] **F. Zhang***, H.L. Trentelman, J.M.A. Scherpen. Robust cooperative output regulation of heterogeneous Lur’e networks. International Journal of Robust and Nonlinear Control, 27(16):3061-3078, 2017

[J3] **F. Zhang***, H.L. Trentalman, J.M.A. Scherpen. Dynamic feedback synchronization of Lur’e networks via incremental sector boundedness. IEEE Transactions on Automatic Control, 61(9):2579-2584, September 2016

[J2] **F. Zhang**, H.L. Trentelman*, J.M.A. Scherpen. Fully distributed robust synchronization of networked Lur’e systems with incremental nonlinearities. Automatica <em>regular paper</em>, 50(10):2515-2526, October 2014<

[J1] S.J. Zhang*, X.B. Cao, **F. Zhang**, L. He. Monocular vision-based iterative pose estimation algorithm from corresponding feature points. Science China Information Sciences, 53(8):1682-1696, August 2010

<hr />
<p><strong>Book Chapters</strong></p>

<div style="display: flex; align-items: flex-start;">
  <img src="/images/book.png" alt="书籍封面" style="width:100px; margin-right: 20px;">
  <div>
<p><strong>Book Title:</strong> Security and Resilience in Cyber-Physical Systems: Detection, Estimation and Control</p>
    <p><strong>Description:</strong> This book covers various aspects of security and resilience in cyber-physical systems, focusing on detection, estimation, and control.</p>
    <p><strong>Publisher:</strong> Springer, 2022</p>
    <p><strong>Citation:</strong> [B1] J.J. Fu, G.H. Wen, Y.J. Xu, A. Zemouche, F. Zhang. Resilient cooperative control of input constrained networked cyber-physical systems. <em>Security and Resilience in Cyber-Physical Systems: Detection, Estimation and Control</em>, Springer, 2022.</p>
  </div>
</div>

<hr />
<p><strong>Conference Proceedings</strong></p>

[C11] S.Y. Meng, F.W. Meng, **F. Zhang**, M. Alma, M. Haddad, A. Zemouche. Nonlinear observer design for vehicle lateral load transfer ratio estimation. American Control Conference, <em>to appear</em>, Toronto, Canada, July 8-12, 2024.

[C10] H. Arezki, **F. Zhang**, A. Zemouche. A HG/LMI-based observer for a tumor growth model. European Control Conference, pp. 259-263, London, UK, July 12-15, 2022

[C9] **F. Zhang**, H.L. Liang, G.H. Wen, A. Zemouche, W.W. Yu. Absolute stabilization of Lur’e systems by periodically intermittent control. IEEE International Conference on Control and Automation invited session, pp. 1102-1107, Edinburgh, Scotland, July 16-19, 2019

[C8] **F. Zhang**, W.W. Yu, G.H. Wen, A. Zemouche. Practical absolute stabilization of Lur’e systems via periodic event-triggered feedback. China-Qatar International Workshop on Artificial Intelligence and Applications to Intelligent Manufacturing, pp. 42-47, Doha, Qatar, January 1-4, 2019

[C7] H.L. Liang, Z. Zhou, **F. Zhang**, C. Peng, Y.L. Wang. Stochastic stability of evolutionary prisoner’s dilemma. Australian &amp; New Zealand Control Conference, pp. 1-6, Melbourne, Australia, December 6-8, 2018

[C6] P.F. Lu, W.W. Yu, **F. Zhang**. Leader-follower formation control with mismatched compasses. Chinese Control Conference invited session, pp. 8821-8826, DaLian, China, July 26-28, 2017

[C5] **F. Zhang**, M. Mazo Jr., N. van de Wouw. Absolute stabilization of Lur’e systems under event-triggered feedback. IFAC World Congress open invited session, pp. 15866-15871, Toulouse, France, July 9-14, 2017

[C4] A.V. Proskurnikov, **F. Zhang**, M. Cao, J.M.A. Scherpen. A general criterion for synchronization of incrementally dissipative nonlinearly coupled agents. European Control Conference, pp. 581-586, Linz, Austria, July 15-17, 2015

[C3] **F. Zhang**, W.G. Xia, H.L. Trentelman, K.H. Johansson, J.M.A. Scherpen. Robust synchronization of directed Lur’e networks with incremental nonlinearities. IEEE Multi-Conference on Systems and Control, pp. 276-281, Antibes, France, October 8-10 2014

[C2] **F. Zhang**, P. Ramazi, M. Cao. Distributed concurrent targeting for linear arrays of point sources. IFAC World Congress, pp. 8323-8328, Cape Town, South Africa, August 24-29, 2014

[C1] Y.H. Geng, W. Lu, **F. Zhang**. Robust sliding mode control for attitude control of small satellite. IAA Symposium on Small Satellites for Earth Observation, Berlin, Germany, April 2011


<span class='anchor' id='projects'></span>
# 👨‍💻 Projects
+ 2020.12 - 2025.11, **Multi-DOF Control of Electrostatic Suspension Systems**

+ 2018.1 - 2020.12, **Cooperative Control of Lur’e Networks Over Dynamic Topologies**


<span class='anchor' id='professional-Service'></span>

# 💼 Professional Service

## Associate Editor:

+ European Journal of Control, IET Control Theory &amp; Applications

## Program Committee Member:

+ 20th International Conference on Control, Automation and Systems, BEXCO, Busan, Korea, October 13-16, 2020

## Reviewer:

+ IEEE Transactions on Automatic Control, Automatica
+ IEEE Transactions on Control of Network Systems
+ Journal of Robust and Nonlinear Control,
+ Systems &amp; Control Letters,
+ International Journal of Control
+ European Journal of Control
+ Nonlinear Analysis: Hybrid Systems
+ IEEE Transactions on Cybernetics
+ IEEE Transactions on Systems, Man and Cybernetics: Systems,
+ Journal of The Franklin Institute
+ Asian Journal of Control
+ IEEE Control Systems Letters
+ Optimal Control Applications and Methods
+ International Journal of Adaptive Control and Signal Processing
+ IEEE Systems Journal
+ IEEE Internet of Things Journal
+ IEEE Conference on Decision and Control
+ IFAC World Congress, American Control Conference
+ European Control Conference
+ Asian Control Conference
+ IEEE International Conference on Control &amp; Automation
+ Chinese Control Conference
+ Chinese Control and Decision Conference


<span class='anchor' id='courses'></span>

# 📖 Courses

<div style="display: flex; align-items: flex-start;">
  <img src="/images/matlab1.png" alt="MATLAB Logo" style="width:40px; margin-right: 20px;">
  <div>
      <strong>Undergraduate Courses: MATLAB with Applications</strong>
  </div>
</div>
<br />

<div style="display: flex; align-items: flex-start;">
  <img src="/images/Robust.png" alt="Robust Logo" style="width:40px; margin-right: 20px;">
  <div>
      <strong>Postgraduate Courses: Robust and Adaptive Control</strong>
  </div>
</div>


<span class='anchor' id='group-Members'></span>

# 🧑‍🎓 Group Members

<p><strong><em>Current Postdocs</em></strong></p>

<p>2023.8 - : HongFu Wang</p>

<p><strong><em>Current Ph.D. students</em></strong></p>

<p>2024.9 - : ZhiMing Yang, DanYu Li</p>

<p><strong><em>Current master students</em></strong></p>

<p>2024.9 - : Hao Chen, QinTao Lai, RuTao Zhong</p>

<p>2023.9 - : YuAng Ke, YaChuan Li</p>

<p>2022.9 - : Cheng Liu, JiaBo Liu, Hao Xu</p>

<p>2021.9 - ：ZhiMing Yang, HongJie Fang</p>

<p><strong><em>Former master students</em></strong></p>

<p>2020.9 - 2022.6: Xin Deng (CaiNiao Network Technology Co., Ltd, HangZhou, China)</p>

<p>2019.9 - 2022.6: JinZe Wu (Southern University of Science and Technology, ShenZhen, China &amp; Politecnico di Torino, Turin, Italy)</p>

<p><strong><em>Former undergraduates</em></strong></p>

<p>2023.11 - 2024.5: ZhiYang Sun (master student, SYSU)</p>

<p>2022.11 - 2023.5: YuAng Ke (master student, SYSU), MingShuai Wu (master student, SYSU), Ke Xu (master student, PKU)</p>

