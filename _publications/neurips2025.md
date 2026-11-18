---
title: "Predicting Partially Observable Dynamical Systems via Diffusion Models with a Multiscale Inference Scheme"
collection: publications
category: manuscripts
permalink: /publication/neurips2025
date: 2025-12-01
venue: 'Advances in Neural Information Processing Systems 38 (NeurIPS 2025), Main Track'
authors: 'R. Morel, F. P. Ramunno, J. Shen, A. Bietti, K. Cho, M. Cranmer, S. Golkar, et al., D. Fouhey, S. Ho'
paperurl: 'https://arxiv.org/abs/2511.19390'
citation: 'Morel, R., Ramunno, F. P., Shen, J., Bietti, A., Cho, K., Cranmer, M., Golkar, S., Gugnin, O., Krawezik, G., Marwah, T., McCabe, M., Meyer, L., Mukhopadhyay, P., Ohana, R., Parker, L., Qu, H., Rozet, F., Leka, K. D., Lanusse, F., Fouhey, D., & Ho, S. (2025). "Predicting partially observable dynamical systems via diffusion models with a multiscale inference scheme." <i>Advances in Neural Information Processing Systems 38</i>, 66787–66805. <a href="https://arxiv.org/abs/2511.19390">arXiv:2511.19390</a>.'
---

Conditional diffusion models provide a natural framework for probabilistic prediction of dynamical systems and have been successfully applied to fluid dynamics and weather prediction. However, in many settings, the available information at a given time represents only a small fraction of what is needed to predict future states, either due to measurement uncertainty or because only a small fraction of the state can be observed. This is true for example in solar physics, where we can observe the Sun's surface and atmosphere, but its evolution is driven by internal processes for which we lack direct measurements. In this paper, we tackle the probabilistic prediction of partially observable, long-memory dynamical systems, with applications to solar dynamics and the evolution of active regions. We show that standard inference schemes, such as autoregressive rollouts, fail to capture long-range dependencies in the data, largely because they do not integrate past information effectively. To overcome this, we propose a multiscale inference scheme for diffusion models, tailored to physical processes. Our method generates trajectories that are temporally fine-grained near the present and coarser as we move farther away, which enables capturing long-range temporal dependencies without increasing computational cost. When integrated into a diffusion model, we show that our inference scheme significantly reduces the bias of the predicted distributions and improves rollout stability.
