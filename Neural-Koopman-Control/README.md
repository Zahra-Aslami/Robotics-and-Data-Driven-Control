# Neural Koopman Control for Soft Robots (Research Proposal)

**Status:** Literature Review & Planning Phase 
**Author:** Zahra Aslami (B.Sc. Student in Mechanical Engineering, Sharif University of Technology)

##  Project Overview
Modeling and controlling soft robots is a significant challenge due to their continuous, highly nonlinear, and infinite-dimensional dynamics. Standard local linearization methods often fail when the robot moves across a wide workspace.

This repository documents my ongoing Bachelor's research project, which aims to apply **Koopman Operator Theory** combined with **Deep Learning** to control soft robotic systems. Instead of deriving complex analytical equations, the goal is to use a neural network (in PyTorch) to lift the nonlinear state measurements into a higher-dimensional latent space where the dynamics behave linearly. Once a linear representation is learned, a standard **Linear Quadratic Regulator (LQR)** will be designed for closed-loop stabilization.

##  Research Objectives
1. Review recent literature on Neural Koopman operators and their application in soft robotics.
2. Formulate a PyTorch-based Multi-Layer Perceptron (MLP) to learn optimal observable functions.
3. Identify the linear state-space matrices (\(A, B\)) in the latent space.
4. Design and test an LQR controller based on the learned linear model.

##  Roadmap (Next Steps)
- [x] Literature review and defining the problem statement.
- [ ] Formulating the theoretical framework (Koopman theory & MLP).
- [ ] Python implementation of the Neural Koopman architecture.
- [ ] Generating simulation data from a soft robotic arm model.
- [ ] Extracting the linear model and validating the LQR controller.
- [ ] Writing the final thesis report.

##  Key References
1. Lusch, B., Kutz, J. N., & Brunton, S. L. (2018). *Deep learning for universal linear embeddings of nonlinear dynamics*. Nature Communications.
2. Bruder, D., et al. (2021). *Koopman-based control of a soft continuum manipulator under variable loading conditions*. IEEE Robotics and Automation Letters.
3. Strasser, R., et al. (2026). *An overview of Koopman-based control: From error bounds to closed-loop guarantees*. Annual Reviews in Control.

---
*This repository represents the initial planning phase of my ongoing research in data-driven control at Sharif University of Technology.*
