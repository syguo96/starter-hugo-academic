---
title: "Invited Talk · Bio & Abstract"
type: page
cms_exclude: true
---


**Bio for Invited Talk (for organisers)**: Siyuan Guo (she/her) is a PhD candidate in Machine Learning jointly at the University of Cambridge and the Max Planck Institute for Intelligent Systems. Her research aims to understand intelligence and learning, with a focus on the physics of learning, causal inference, and AI for scientific discovery. In 2025 she released the Physics of Learning preprint, proposing that learning can be viewed as following the principle of least action; within a week of its arXiv release, the work prompted a fireside-chat invitation, multiple academic and industry talks, and collaboration discussions with infrastructure support. Her work spans theory and application, most recently advancing pre-trained foundation models for in-context causal inference in real-world scientific settings. She has published at top-tier venues such as NeurIPS and ICLR, including 1 oral and 2 spotlight presentations, and her research has been recognised by honours such as MIT EECS Rising Star, the G-Research PhD Prize, and the MPI-IS Outstanding Female Doctoral Student Award. Her current work is supported by the Cambridge–Tübingen PhD Fellowship and a Premium Research Studentship.



*Title:* Physics of Learning – Towards a Unified View of Intelligence  

**Talk Abstract**: In physics, phenomena such as light propagation and Newtonian mechanics obey the **principle of least action**: the true trajectory is a stationary point of the Lagrangian. In our recent work [1], we hypothesise that learning, too, follows a least-action principle. We model learning as **stationary-action dynamics on information fields**. Concretely, we derive classical learning algorithms as stationary points of information-field Lagrangians, recovering Bellman optimality from a reward-based Hamiltonian and Fisher-information–aware updates for estimation. This yields a unifying variational view across reinforcement learning and supervised learning, and suggests optimisers with testable properties. Conceptually, it treats the training of a learning system as the evolution of a physical system in an abstract information space.

Structure is also central to learning, enabling interventional reasoning and scientific understanding. Causality provides a framework for discovering structure from data under the hypothesis that causal mechanisms are independent. In earlier work [2], we formalise independent mechanisms as independent latent variables controlling each mechanism, and show how this perspective extends across effect estimation, counterfactual reasoning, representation learning, and reinforcement learning. 

Methodologically, in collaboration with Prior Labs, we develop **Do-PFN** [3], a pre-trained Prior-Fitted Network that performs in-context causal inference. This serves as a promising out-of-the-box tool for practitioners working across diverse scientific domains.

**References**

<div class="talk-refs">
  
[1] Siyuan Guo and Bernhard Schölkopf. *Physics of Learning: A Lagrangian Perspective to Different Learning Paradigms.* arXiv preprint arXiv:2509.21049, 2025.  

[2] Siyuan Guo\*, Viktor Tóth\*, Bernhard Schölkopf, and Ferenc Huszár. *Causal de Finetti: On the Identification of Invariant Causal Structure in Exchangeable Data.* Advances in Neural Information Processing Systems (NeurIPS), 2023.  

[3] Jake Robertson\*, Arik Reuter\*, Siyuan Guo, Noah Hollmann, Frank Hutter, and Bernhard Schölkopf. *Do-PFN: In-Context Learning for Causal Effect Estimation.* Advances in Neural Information Processing Systems (NeurIPS), 2025. (Spotlight; acceptance rate 3.19%.)

</div>
