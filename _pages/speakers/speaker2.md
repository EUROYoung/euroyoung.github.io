---
layout: default
title: "Dolores Romero Morales"
permalink: /speakers/speaker2/
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
    <img src="/assets/images/DoloresRomeroMorales2.jpg" alt="Dolores Romero Morales">
  </div>

<div class="speaker-details">
  <h1>Dolores Romero Morales</h1>
  <h2>Copenhagen Business School, Denmark</h2>
  
Dolores Romero Morales is a professor of Operations Research at Copenhagen Business School, Denmark. Her areas of expertise include explainability and fairness in data science as well as sustainable supply chain management. Dolores currently serves as the Editor-in-Chief of <em>TOP</em> and as an associate editor of the <em>Journal of the Operational Research Society</em> as well as the <em>INFORMS Journal on Data Science</em>. Moreover, she is an <em>Honorary SAS Fellow</em> and a member of the <em>SAS Academic Advisory Board</em>.

Among her recent achievements, Dolores (together with her co-authors) was awarded the 2024 <em>Spanish Society of Statistics and Operations Research — BBVA Foundation Award</em> for the best contribution in statistics and operations research applied to data science and big data published in the <em>European Journal of Operational Research</em>. Beyond research, Dolores actively supports early-career researchers through initiatives such as <em>YoungWomen4OR</em>, a program within the <em>EURO WISDOM Forum</em> that aims at increasing the visibility of young female researchers in operations research across <em>EURO</em>.
 
  <p><strong>Talk Title</strong>: <em>"Local Explainability in Machine Learning: A collective framework"</em></p>

  <p>State-of-the-art Artificial Intelligence (AI) and Machine Learning (ML) algorithms 
have become ubiquitous across industries due to their high predictive performance. However, despite their widespread deployment, these models are often criticized for their lack of transparency and accountability. Their “black-box” nature obscures the reasoning behind decisions, limiting trust and hindering their integration in critical, data-driven decision-making processes. Moreover, algorithmic decisions can perpetuate or even amplify societal biases, leading to unfair and discriminatory outcomes. This concern is especially pressing in high-stakes domains such as healthcare, criminal justice, and credit scoring, where unfair model behavior can significantly impact individuals' lives.
</p>

  <p>In the burgeoning field of Explainable Artificial Intelligence, the goal is to shed light on black-box machine learning models. Local Interpretable Model-Agnostic Explanations (LIME) is a popular tool, that, given a prediction model and an instance, builds a surrogate linear model which yields similar predictions around the instance. When LIME is applied to a group of instances, independent linear models are obtained, which may hinder overall explainability.</p>

  
<p>
In this talk we propose a novel framework, called Collective LIME (CLIME), where the surrogate models built for the different instances are linked, being smooth with respect to the coordinates of the instances. With this collective approach, CLIME enables one to control global sparsity, i.e., which features are used ever, even if sparse models are built for each instance. In addition, CLIME builds Generalized Linear Models as surrogates, enabling us to address with the very same methodology different prediction tasks: classification, regression, and regression of counting data. We will show how classic Operations Research models, such as the Knapsack Problem, are relevant to obtain satisfactory CLIME solutions. We will end the talk illustrating our approach on a collection of benchmark datasets.</p>

  <hr>

  <p><strong>Website</strong>: <a href="https://www.cbs.dk/en/research/departments-and-centres/department-of-economics/staff/drmeco">University Webpage</a></p>
</div>

</div>

