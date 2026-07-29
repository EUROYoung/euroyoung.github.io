---
layout: default
title: "Daniel Kuhn"
---

<style>
.speaker-container {
  display: flex;
  flex-wrap: wrap;
  gap: 2em;
  align-items: flex-start;
  margin: 2em 0;
}

.speaker-image {
  flex: 1 1 300px;
  max-width: 300px;
}

.speaker-image img {
  width: 100%;
  border-radius: 12px;
  box-shadow: 0 2px 8px rgba(0,0,0,0.15);
}

.speaker-details {
  flex: 2 1 500px;
}

.speaker-details h1 {
  margin-top: 0;
}

.speaker-details h2 {
  font-size: 1.2em;
  color: #555;
  margin-bottom: 1em;
}

@media (max-width: 768px) {
  .speaker-container {
    flex-direction: column;
    align-items: center;
  }

  .speaker-details {
    text-align: center;
  }
}
</style>

<div class="speaker-container">

  <div class="speaker-image">
    <img src="/assets/images/lugano26/DKhun.jpg" alt="Daniel Kuhn">
  </div>

<div class="speaker-details">
  <h1>Daniel Kuhn
</h1>
  <h2>Full Professor of Operations Research at the College of Management of Technology, Chair of Risk Analytics and Optimization, EPFL, Switzerland</h2>

Daniel Kuhn is Professor of Operations Research at the College of Management of Technology at EPFL, where he holds the Chair of Risk Analytics and Optimization (RAO). His current research interests are focused on data-driven optimization, the development of efficient computational methods for the solution of stochastic and robust optimization problems and the design of approximation schemes that ensure their computational tractability. This work is primarily application-driven, the main application areas being engineered systems, machine learning, business analytics and finance.
Before joining EPFL, Daniel Kuhn was a faculty member in the Department of Computing at Imperial College London (2007-2013) and a postdoctoral research associate in the Department of Management Science and Engineering at Stanford University (2005-2006). He holds a PhD degree in Economics from University of St. Gallen and an MSc degree in Theoretical Physics from ETH Zurich. He is the editor-in-chief of Mathematical Programming.
  <p><strong>Talk Title</strong>: <em>Metrizing Fairness</em></p>

  <p><strong>Abstract:</strong> We study supervised learning problems that have significant effects on individuals from 
two demographic groups, and we seek predictors that are fair with respect to a group fairness criterion such as 
statistical parity (SP). A predictor is SP-fair if the distributions of predictions within the two groups are close in 
Kolmogorov distance, and fairness is achieved by penalizing the dissimilarity of these two distributions in the 
objective function of the learning problem. In this paper, we identify conditions under which hard SP constraints are 
guaranteed to improve predictive accuracy. We also showcase conceptual and computational benefits of measuring 
unfairness with integral probability metrics (IPMs) other than the Kolmogorov distance. Conceptually, we show that 
the generator of any IPM can be interpreted as a family of utility functions and that unfairness with respect to this 
IPM arises if individuals in the two demographic groups have diverging expected utilities. We also prove that the 
unfairness-regularized prediction loss admits unbiased gradient estimators, which are constructed from random 
mini-batches of training samples, if unfairness is measured by the squared L2-distance or by a squared maximum mean 
discrepancy. In this case, the fair learning problem is susceptible to efficient stochastic gradient descent (SGD) 
algorithms. Numerical experiments on synthetic and real data show that these SGD algorithms outperform state-of-the-art 
methods for fair learning in that they achieve superior accuracy-unfairness trade-offs - sometimes orders of magnitude 
faster.</p>


  <p><strong>Website</strong>: <a href="https://people.epfl.ch/daniel.kuhn?lang=en">Personal webpage</a></p>
</div>

</div>