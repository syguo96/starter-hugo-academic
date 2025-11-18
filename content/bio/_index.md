---
title: "Invited Talk · Bio & Abstract"
type: page
---

## Bio for Invited Talk (for organisers)

Siyuan Guo (she/her) is a Ph.D. in Machine Learning at the University of Cambridge, UK and Max Planck Institute for Intelligent Systems, Germany. 
She is curious to understand intelligence and learning. In 2025 she released the Physics of Learning preprint - demonstrating learning
follows the principle of least action. Within a week of its arXiv release, the work prompted a fireside-chat invitation, multiple talk invitations and collaboration
discussions with infrastructure support. Her work spans theory to application, most recently advancing pretrained foundation models on in-context causal inference for real-world scientific use cases.
She has published in top-tier ML venues such as NeurIPS and ICLR with 1 oral and 2 spotlights acceptance. 
Her research is recognized through MIT EECS Rising Star, G-research PhD prize, and wins MPI-IS Outstanding Female Doctoral Award. 
Her current research is supported under the Cambridge-Tübingen Fellowship and Premium Research Studentship. 


## Talk Abstract

*Title:* Physics of Learning – Towards a Unified View of Intelligence  

In physics, light traveling and Newtonian mechanics follow the principle of least action -- the true path follows stationary trajectories in the Lagrangian. 
I hypothesize in our new work [1] that learning, too, follows the laws of physics - the principle of least action. 
We model learning as \emph{stationary-action} dynamics on information fields. Concretely, we derive classical learning algorithms at stationary points of information-field Lagrangians, recovering Bellman optimality from a reward-based Hamiltonian and Fisher-information–aware updates for estimation. This yields a unifying variational view across reinforcement learning and supervised learning and suggests optimizers with testable properties. Conceptually, it treats training of a learning system as the evolution of a physical system in an abstract information space.
Structure is also a key aspect in learning to enable interventional effect propagation and scientific understanding. 
Causality studies structure discovery from data with the hypothesis that causal mechanisms are independent. 
I will discuss past work [2] that formalizes independent mechanisms as independent latent variables controlling each mechanism, with its understanding extending to different fields, e.g., effect estimation, counterfactual reasoning, representation learning, and reinforcement learning. 
Methodologically, we, in collaboration with Prior Labs, develop Do-PFN [3], a pre-trained Prior Fitted Network to enable in-context causal inference predictions. This serves as a promising out-of-the-box tool for practitioners working in diverse scientific fields. 

[1] Siyuan, Guo and Bernhard Schölkopf. "Physics of Learning: A Lagrangian perspective to different learning paradigms." arXiv preprint arXiv:2509.21049 (2025).

[2] Siyuan Guo*, Viktor Tóth*, Bernhard Schölkopf, and Ferenc Huszár. "Causal de finetti: On the identification of invariant causal structure in exchangeable data." In NeurIPS (2023).

[3] Jake Robertson*, Arik Reuter*, Siyuan Guo, Noah Hollmann, Frank Hutter, and Bernhard Schölkopf. Do-pfn: In-context learning for causal effect estimation. In NeurIPS (2025). (spotlight with acceptance rate 3.19%.)
