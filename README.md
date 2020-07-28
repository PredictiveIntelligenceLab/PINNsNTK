## When and why PINNs fail to train: A neural tangent kernel perspective

Code and data (available upon request) accompanying the manuscript titled "When and why PINNs fail to train: A neural tangent kernel perspective", authored by Sifan Wang, Xinling Yu, and Paris Perdikaris.

## Abstract

Physics-informed neural networks (PINNs) have lately received great attention thanks to their flexibility in tackling a wide range of forward and inverse problems involving partial differential equations. However, despite their noticeable empirical success, little is known about how such constrained neural networks behave during their training via gradient descent. More importantly, even less is known about why such models sometimes fail to train at all.
In this work, we aim to investigate these questions through the lens of the Neural Tangent Kernel (NTK); a kernel that captures the behavior of fully-connected neural networks in the infinite width limit during training via gradient descent. Specifically, we derive the NTK
of PINNs and prove that, under appropriate conditions, it converges to a deterministic kernel that stays constant during training in the infinite-width limit. This allows us to analyze the training dynamics of PINNs through the lens of their limiting NTK and find a remarkable discrepancy in the convergence rate of the different loss components contributing to the total training error. To address this fundamental pathology, we propose a novel gradient descent algorithm that utilizes the eigenvalues of the NTK to adaptively calibrate the convergence rate of the total training error. Finally, we perform a series of numerical experiments to verify the correctness of our theory and the practical effectiveness of the proposed algorithms. 

## Citation

TBA
