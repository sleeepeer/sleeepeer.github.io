---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* **Ph.D. in Informatics**, Pennsylvania State University, Aug 2024 – May 2028 (Expected)
  * Research focusing on LLM Security, AI agents and Evaluation
* **B.Eng. in Computer Science**, Wuhan University, Sep 2020 – Jun 2024

Research Experience
======
My research focuses on developing secure and reliable LLMs and AI agents. I study both the vulnerabilities and defense / alignment of LLMs, with a particular focus on prompt injection. I also work on evaluating LLMs and AI agents under realistic and comprehensive settings.

* **Prompt Injection Attacks and Defenses:** I study how prompt injection affects LLM behavior and design efficient and effective defenses against these attacks.
* **LLM Alignment and Post-Training:** I have hands-on experience with reinforcement learning (RL) finetuning methods such as Direct Preference Optimization (DPO) and Group Relative Policy Optimization (GRPO). My research leverages post-training to further improve LLM robustness without degrading utility.
* **Evaluation and Benchmarking:** I build systematic evaluation pipelines to assess LLMs and AI agents. I am a co-author of a widely-used benchmark: Open-Prompt-Injection and I'm working on the next-gen evaluation benchmark on trustworthy LLMs and AI agents.


Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Open Source Projects
======
* **PoisonedRAG** - 200+ GitHub Stars, lead contributor and co-first author
* **Open-Prompt-Injection** - 300+ GitHub Stars, co-author
