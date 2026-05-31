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

I am Chengjun Pan (潘成骏), a master's student at the [Guanghua School of Management](https://www.gsm.pku.edu.cn/), Peking University, majoring in FinTech. I received my B.S. in Artificial Intelligence from the [School of Data Science](https://sds.fudan.edu.cn/), Fudan University, where I ranked 2nd in my major.

My research focuses on **reinforcement learning for large language models** and **LLM agents**. I am currently working on RL algorithms for multi-turn tool-use settings — mitigating entropy collapse, improving context structure, and boosting training efficiency — advised by Prof. [Zhiyuan Liu](https://nlp.csai.tsinghua.edu.cn/~lzy/). I am also interested in efficient and reliable evaluation of (multimodal) LLMs.

Before that, I spent several years in quantitative finance, working on reinforcement learning, CTA / index-futures strategies, and high-frequency factor mining.

<a href='https://scholar.google.com/citations?user=IlKyHdcAAAAJ'>Google Scholar citations <strong><span id='total_cit'>0</span></strong></a> <a href='https://scholar.google.com/citations?user=IlKyHdcAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>

# 🔥 News
- *2026.01*: &nbsp;🎉🎉 Our paper *AutoJudger: An Agent-Driven Framework for Efficient Benchmarking of MLLMs* was accepted to **ACL 2026 (Main Conference)**.
- *2025.09*: &nbsp;🎓 I started my master's program at the Guanghua School of Management, Peking University, and joined Prof. Zhiyuan Liu's group to work on RL for LLMs.
- *2025.06*: &nbsp;🎉 I graduated from Fudan University and was named a *Shanghai Outstanding Graduate*.

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACL 2026</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[AutoJudger: An Agent-Driven Framework for Efficient Benchmarking of MLLMs](https://arxiv.org/abs/2505.21389)

Xuanwen Ding\*, **Chengjun Pan\***, Zejun Li, Jiwen Zhang, Siyuan Wang, Zhongyu Wei

[**Paper**](https://arxiv.org/abs/2505.21389) <strong><span class='show_paper_citations' data='IlKyHdcAAAAJ:u5HHmVD_uO8C'></span></strong>
- An agent-driven framework that uses Item Response Theory (IRT) to adaptively select a small subset of benchmark items, matching full-benchmark evaluation of MLLMs at a fraction of the cost. (\*co-first author)
</div>
</div>

- [EVPO: Explained Variance Policy Optimization for Adaptive Critic Utilization in LLM Post-Training](https://arxiv.org/abs/2604.19485), **Chengjun Pan**, Shuaijie Liu, Jian Lin, et al., *arXiv preprint, 2026* <strong><span class='show_paper_citations' data='IlKyHdcAAAAJ:d1gkVwhDpl0C'></span></strong>

- [Agentic Harness Engineering: Observability-Driven Automatic Evolution of Coding-Agent Harnesses](https://arxiv.org/abs/2604.25850), Jian Lin, Shuaijie Liu, **Chengjun Pan**, et al., *arXiv preprint, 2026* <strong><span class='show_paper_citations' data='IlKyHdcAAAAJ:9yKSN-GCB0IC'></span></strong>

- [AgentCPM-Explore: Realizing Long-Horizon Deep Exploration for Edge-Scale Agents](https://arxiv.org/abs/2602.06485), Heyang Chen, Xin Cong, ..., **Chengjun Pan**, et al., *arXiv preprint, 2026* <strong><span class='show_paper_citations' data='IlKyHdcAAAAJ:u-x6o8ySG0sC'></span></strong>

- Exploring Systemic Risk Dynamics in the Chinese Stock Market: A Network Analysis with Risk Transmission Index, *Risks*, 2024 (accepted)

# 🎖 Honors and Awards
- *2025* Shanghai Outstanding Graduate.
- *2024* 1st Place, Tencent Kaiwu AI Global Open Competition (Mainland China Finals) — RL agent based on PPO, defeating 100+ finalist teams (¥100,000 prize).
- *2023* National Scholarship (the only recipient in my year within the school).
- *2022 – 2024* Fudan University Outstanding Student (sole school nominee for the 2023 "Model Student" final defense).
- *2022 – 2024* Fudan University Sunshine Sports Star.

# 📖 Educations
- *2025.09 - present*, M.S. in FinTech, Guanghua School of Management, Peking University, Beijing.
- *2021.09 - 2025.06*, B.S. in Artificial Intelligence, School of Data Science, Fudan University, Shanghai. GPA 3.72/4 (2nd in major).

# 🏆 Competitions
- *2024*, 1st Place — Tencent Kaiwu AI Global Open Competition, Mainland China Finals (RL / PPO game-playing agent).
- *2023*, National 2nd Prize — China Undergraduate Mathematical Contest in Modeling (CUMCM).
- *2023*, Shanghai 1st Prize — National Statistical Modeling Competition (QR-Lasso & network analysis of systemic risk).
- *2022*, Shanghai 1st Prize — China Undergraduate Mathematical Contest in Modeling (CUMCM).
- *2022*, National 2nd Prize — 14th China Undergraduate Mathematics Competition.

# 💻 Internships
- *2025.03 - 2025.07*, Huajun Guanghui — Quantitative Research Intern, Shanghai (index-futures strategies, high-frequency factor mining).
- *2024.07 - 2024.11*, Zhanhong Investment — Research Assistant, Shanghai (CTA intraday momentum & index-futures breakout strategies, out-of-sample Calmar > 5).
- *2023.09 - 2024.03*, Jiyou Fund — CTA Quant Strategy Intern, Shanghai (multi-factor strategy framework, regression arbitrage).
- *2023.06 - 2023.08*, Fosun Prudential Asset Management — Summer Intern, Shanghai (REITs volatility & correlation research).
