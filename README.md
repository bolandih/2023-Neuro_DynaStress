# 2023-Neuro_DynaStress
## Neuro-DynaStress: Predicting Dynamic Stress Distributions in Structural Components
##### Code will be released upon paper acceptance: Neuro-DynaStress: Predicting Dynamic Stress Distributions in Structural Components, preprint avilable on [arXiv](https://arxiv.org/abs/2301.02580)

#### Authors: [Hamed Bolandi](https://bolandih.github.io/), Gautam Sreekumar, Xuyang Li, Nizar Lajnef, Vishnu Boddeti

### Abstract
Structural components are typically exposed to dynamic loading, such as earthquakes, wind, and explosions. Structural engineers should be able to conduct real-time analysis in the aftermath or during extreme
disaster events requiring immediate corrections to avoid fatal failures. As a result, it is crucial to predict dynamic stress distributions during highly disruptive events in real time. Currently available high delity methods, such as Finite Element Models (FEMs), suer from their inherent high complexity and are computationally prohibitive. Therefore, to reduce computational cost while preserving accuracy, a deep learning model, Neuro-DynaStress, is proposed to
predict the entire sequence of stress distribution based on nite element simulations using a partial diferential equation (PDE) solver. The model was designed and trained to use the geometry, boundary conditions and sequence of loads as input and predict the sequences of high-resolution stress contours. The proposed framework's performance is compared to finite element simulations using a PDE solver.

### Neuro-DynaStress
![Neuro-DynaStress](https://github.com/bolandih/bolandih.github.io/blob/gh-pages/Images/Neuro-DynaStress_Page_02.png)
