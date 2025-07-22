---
title: "Li Group - Research"
layout: textlay
excerpt: "Li Group -- Research"
sitemap: false
permalink: /research/
---

# Research

Our overarching goal is to develop theory, algorithms, models, and software for optimization and machine learning. 

Here are several research areas that we currently work on:

**Novel Deep Learning Models Informed by Physics and Domain Knowledge**
Machine learning, especially deep neural networks, has transformed how we approach complex problems, from recognizing images to understanding natural language. In chemical engineering and process systems engineering (PSE), these models have shown promise in tasks ranging from discovering new molecules to optimizing large-scale industrial processes. However, a major challenge remains: neural networks often behave like “black boxes,” producing results that may violate fundamental physical laws, which is unacceptable in safety-critical applications like process design and control. To overcome this, we are developing optimization-inspired neural networks (OINNs), a new class of models that go beyond traditional physics-informed neural networks (PINNs). While PINNs embed physical laws as soft constraints, OINNs rigorously enforce both physical and logical constraints by integrating principles from mathematical optimization directly into the network architecture. This approach ensures models remain interpretable, reliable, and consistent with domain knowledge, even under uncertainty. By combining optimization theory with modern machine learning, we aim to create trustworthy AI tools for engineering applications—tools that can safely design processes, predict system behaviors, and support decision-making in critical industrial environments. We are collaborating with experts in various fields, including biomedical researchers, reaction engineers, to apply these models to real-world challenges.

**Explain Optimization and Machine Learning Models Using Generative AI**
Optimization and machine learning models are powerful tools used in industries ranging from energy systems to manufacturing. They help engineers and decision-makers design better processes, reduce costs, and improve safety. However, these models are often difficult for non-technical stakeholders—such as plant operators, managers, or policymakers—to understand or interact with. This “language gap” between humans and mathematical models can lead to confusion, mistrust, and inefficient decision-making. To bridge this gap, we are developing systems powered by large language models (LLMs) that act as natural-language interfaces for optimization and machine learning. Our first-of-its-kind approach allows users to ask questions, diagnose issues like infeasible models, and interpret model outputs using everyday language rather than complex technical jargon. By making these models explainable and accessible, we enable better collaboration between technical and non-technical teams, ensuring that advanced AI tools can truly support practical decision-making in real-world engineering settings.

**Machine Learning for Discrete and Global Optimization**
Many decision-making problems in process systems engineering involve complex combinations of yes/no choices, logical rules, and nonlinear relationships—commonly known as mixed-integer nonlinear programming (MINLP) problems. These problems are notoriously hard to solve because the number of possibilities grows exponentially as the system becomes larger, a challenge often called the “curse of dimensionality.” While traditional optimization algorithms can guarantee the best solution, they are often too slow for large-scale industrial problems. On the other hand, machine learning models can make fast predictions but cannot ensure those predictions are truly optimal. Our research seeks to combine the best of both worlds by using machine learning to accelerate discrete and global optimization. We explore techniques like deep learning and reinforcement learning to predict promising solutions, guide traditional solvers more efficiently, and reduce computational effort without sacrificing reliability. This synergy between machine learning and optimization opens new possibilities for tackling large-scale engineering problems that were previously intractable.

**Data Sharing for Decarbonization** 
Reducing carbon emissions in industrial ecosystems—clusters of interconnected plants like steel mills, chemical factories, and energy providers—requires collaboration beyond individual companies. Today, each stakeholder optimizes its own operations, but this “local optimization” misses opportunities for system-wide CO₂ reductions. We focus on enabling secure, privacy-preserving data sharing between stakeholders to unlock these opportunities. By safely sharing production plans, energy use, and emission data, companies can jointly optimize energy consumption, integrate renewables, and cut emissions more effectively. Our research develops federated data-sharing frameworks that protect confidentiality while enabling global optimization of industrial networks. This approach builds trust, enhances resource efficiency, and drives decarbonization that no single company could achieve alone.

We would like to acknowledge the support from the following funding agencies:
<img src="{{ site.url }}{{ site.baseurl }}/images/respic/sponsors.pdf" width="70%" style="display:block; margin-left: auto; margin-right: auto;">

<!-- **Sustainable energy systems design** 
The major economies in the world including the U.S., EU, and China all have set their goals to achieve net-zero carbon emission in the next few decades. As process systems engineers, we aim to design
sustainable energy systems to help transition to the carbon-neutral future. The new designs incorporate the chemical industry, the power systems that
have both thermal and renewable generation sources, the natural gas system, etc. The tightly coupled
energy systems could yield significant economic and environmental benefits. In addressing this problem,
large-scale optimization problems have to be solved because of the spatial and temporal complexity of the problems that integrate
design and operating decisions and under high uncertainty. In addition, the huge amount of data from different industries  have to be processed in
 meaningful ways. To develop capabilities for solving these problems, we have to
advance the field of mathematical optimization and machine learning.

<img src="{{ site.url }}{{ site.baseurl }}/images/respic/energy.png" width="95%" style="display:block; margin-left: auto; margin-right: auto;"> -->

<!-- **Data-driven optimization under uncertainty**
Uncertainties are prevalent in real-world decision-making processes due to changing conditions, long-term forecasts, inaccurate measurements, or lack of information. For example, uncertainties in supply chain management can arise from future customer demands, potential network disruptions, or even the spread of a pandemic. Failing to consider uncertainties in the decision-making process may lead to suboptimal or even infeasible solutions. 
Despite the prevalence of uncertainties involved in process systems, very few uncertainty-aware decision support tools have been used in practice. 
To address this challenge, we have been developing algorithms and software for a mathematical framework called <a href="https://en.wikipedia.org/wiki/Stochastic_programming" target="_blank">stochastic programming</a>, which optimizes the expected objective, such as expected cost, over all the possible realizations of the uncertainties.
We are especially interested in problems under the uncertainty of rare events, such as extreme weather including wildfire, hurricanes, and snowstorms, that cause
supply chain disruption or power systems blackout. The aim is to design reliable and economic supply chain and energy infrastructure using these mathematical frameworks.

<img src="{{ site.url }}{{ site.baseurl }}/images/respic/extremeweather.png" width="50%" style="display:block; margin-left: auto; margin-right: auto;"> -->

<!-- **Multi-scale models and algorithms**
Decision-making in process systems engineering involves large temporal and spatial scales. Strategic decisions are made on a yearly basis, e.g., the supply chain design of a large geographical region. Tactical decisions, such as production targets, are made on a monthly or weekly basis. Scheduling and real-time optimization decisions are made on a daily or hourly basis. Process control of a reactor or flowsheet is made every few minutes or seconds. One could spend his/her career in one of the five levels of the decision-making processes. However, making decisions at the strategic level while neglecting the decisions at lower levels can lead to suboptimal or even infeasible supply chain designs. On the other hand, integrating models at various scales prevents information loss and ensures that models are consistent across scales. It also allows uncertainty to be propagated across scales to ensure that both the true uncertainty and the source of that uncertainty are known. We aim to develop a hybrid multi-scale modeling approach that combines data-driven reduced-order models with rigorous optimization algorithms.

<img src="{{ site.url }}{{ site.baseurl }}/images/respic/multiscale.png" width="70%" style="display:block; margin-left: auto; margin-right: auto;">

**Parallel computing and advanced computational architecture**
The current revolution in AI and machine learning is largely driven by advances in hardware. We aim to leverage 
state-of-the-art hardware solving large-scale optimization problems. We plan to develop parallel and distributed algorithms that 
are amenable to be solved using cloud computing. Graphical Processing Units (<a href="https://en.wikipedia.org/wiki/Graphics_processing_unit" target="_blank">GPU</a>) and Tensor Processing Units (<a href="https://en.wikipedia.org/wiki/Tensor_Processing_Unit" target="_blank">TPU</a>) will be used for laborious machine
learning tasks. Quantum computing architecture, such as D-Wave <a href="https://en.wikipedia.org/wiki/Quantum_annealing" target="_blank">quantum annealer</a> will be used for combinatorial optimization problems.

<img src="{{ site.url }}{{ site.baseurl }}/images/respic/hardware.png" width="50%" style="display:block; margin-left: auto; margin-right: auto;"> -->

