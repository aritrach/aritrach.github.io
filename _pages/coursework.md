---
layout: page
permalink: /coursework/
title: Coursework
description: Selected coursework and projects from my graduate studies.
nav: true
nav_order: 3
---

<div class="course">
  <h2 class="course-title">CSCI 5302 — Advanced Robotics</h2>
  <div class="course-topics">
    <div class="topic-label">Topics</div>
    <div class="topic-tags">
      <span class="topic-tag">ROS2</span>
      <span class="topic-tag">Kinematics & Controls</span>
      <span class="topic-tag">Motion Planning</span>
      <span class="topic-tag">Convex Optimization</span>
      <span class="topic-tag">State Estimation</span>
      <span class="topic-tag">SLAM</span>
      <span class="topic-tag">Deep RL</span>
      <span class="topic-tag">Human-Agent Teaming</span>
    </div>
  </div>
  <button class="course-details-toggle" onclick="this.setAttribute('aria-expanded', this.getAttribute('aria-expanded') === 'true' ? 'false' : 'true'); this.nextElementSibling.style.display = this.getAttribute('aria-expanded') === 'true' ? 'block' : 'none';" aria-expanded="false">
    <span class="toggle-icon">&#9654;</span> <span>Assignments & Project</span>
  </button>
  <div class="course-details" style="display:none;">
    <div class="row mt-1">
      <div class="col-md-4 text-center course-media">
        {% include figure.liquid 
          loading="eager" 
          path="/coursework_samples/IMG_5119-ezgif.com-video-to-gif-converter.gif" 
          class="img-fluid rounded z-depth-1 mx-auto" 
          width="100%" 
          height="auto" 
        %}
        <div class="caption">
          AWS DeepRacer navigating a hallway autonomously.
        </div>
      </div>
      <div class="col-md-8">
        <ul class="assignments-list">
          <li>Implemented RRT and RRT* for motion planning in high-dimensional spaces, handling both holonomic and non-holonomic motion.</li>
          <li>Configured ROS2 environment and developed publisher/subscriber and service/client nodes in Python.</li>
          <li>Implemented value iteration and policy iteration for grid-world environments; applied interpolation methods for continuous state spaces (MountainCar).</li>
          <li>Built an autonomous navigation system on AWS DeepRacer using LIDAR-based obstacle avoidance with PID control and YOLOv3 for stop sign recognition.</li>
        </ul>
      </div>
    </div>
  </div>
</div>

<div class="course">
  <h2 class="course-title">CSCI 7000 — Vision Language Models for Robots</h2>
  <div class="course-topics">
    <div class="topic-label">Topics</div>
    <div class="topic-tags">
      <span class="topic-tag">VLAs</span>
      <span class="topic-tag">VLMs</span>
      <span class="topic-tag">Sense-Plan-Act to Represent-Reason-Execute</span>
      <span class="topic-tag">Transformers</span>
      <span class="topic-tag">Embodied AI</span>
    </div>
  </div>
</div>

<div class="course">
  <h2 class="course-title">CSCI 7000 — Transformer-Based Robotic AI</h2>
  <div class="course-topics">
    <div class="topic-label">Topics</div>
    <div class="topic-tags">
      <span class="topic-tag">Transformers for Robotics</span>
      <span class="topic-tag">LLMs</span>
      <span class="topic-tag">VLMs</span>
      <span class="topic-tag">VLAs</span>
      <span class="topic-tag">Multi-Modal Learning</span>
    </div>
  </div>
  <button class="course-details-toggle" onclick="this.setAttribute('aria-expanded', this.getAttribute('aria-expanded') === 'true' ? 'false' : 'true'); this.nextElementSibling.style.display = this.getAttribute('aria-expanded') === 'true' ? 'block' : 'none';" aria-expanded="false">
    <span class="toggle-icon">&#9654;</span> <span>Research & Blog Posts</span>
  </button>
  <div class="course-details" style="display:none;">
    <ul class="assignments-list">
      <li>Published <a href="https://medium.com/correll-lab/clip-implementation-with-pre-trained-embeddings-9b2eca91dc22">an article</a> implementing CLIP with pre-trained embeddings for robotic perception.</li>
      <li>Analyzed Deep Transformer Q-Networks (DTQN) in reinforcement learning, detailing findings in <a href="https://medium.com/correll-lab/deep-transformer-q-networks-a-paper-analysis-e7efd9379e5f">this article</a>.</li>
      <li>Analyzed transformer applications in robotics including Open X-Embodiment, OK-Robot, Manipulate-Anything, and Vision Transformers.</li>
      <li>Explored scalability of VLMs and VLAs for real-world robotic tasks, evaluating architectures like CLIP, GPT, and diffusion models.</li>
    </ul>
  </div>
</div>

<div class="course">
  <h2 class="course-title">ASEN/CSCI 5264 — Decision Making under Uncertainty</h2>
  <div class="course-topics">
    <div class="topic-label">Topics</div>
    <div class="topic-tags">
      <span class="topic-tag">Bayesian Networks</span>
      <span class="topic-tag">MDPs</span>
      <span class="topic-tag">Reinforcement Learning</span>
      <span class="topic-tag">Deep Q-Networks</span>
      <span class="topic-tag">Policy Gradient</span>
      <span class="topic-tag">Actor-Critic</span>
      <span class="topic-tag">POMDPs</span>
      <span class="topic-tag">Particle Filters</span>
      <span class="topic-tag">Game Theory</span>
      <span class="topic-tag">Imitation Learning</span>
      <span class="topic-tag">Inverse RL</span>
    </div>
  </div>
  <button class="course-details-toggle" onclick="this.setAttribute('aria-expanded', this.getAttribute('aria-expanded') === 'true' ? 'false' : 'true'); this.nextElementSibling.style.display = this.getAttribute('aria-expanded') === 'true' ? 'block' : 'none';" aria-expanded="false">
    <span class="toggle-icon">&#9654;</span> <span>Assignments & Project</span>
  </button>
  <div class="course-details" style="display:none;">
    <a href="/coursework_samples/DMU_HW5.pdf" class="sample-link"><i class="fa-solid fa-file-pdf"></i>Sample work</a>
    <ul class="assignments-list">
      <li>Implemented online MDP methods using grid-world simulations; developed Monte Carlo Policy Evaluation and MCTS for decision-making optimization.</li>
      <li>Comparative analysis of tabular RL algorithms (Q-Learning, SARSA), crafting learning curves to evaluate efficiencies.</li>
      <li>Modeled a POMDP for cancer monitoring using QuickPOMDPs.jl; integrated neural networks for function approximation in RL.</li>
      <li>Developed QMDP and SARSOP solvers for TigerPOMDP, evaluating heuristic vs. optimal policies.</li>
      <li>Formulated policies and belief updaters for a Lasertag POMDP using deep RL and POMCP.</li>
    </ul>
  </div>
</div>

<div class="course">
  <h2 class="course-title">CSCI 5922 — Neural Networks and Deep Learning</h2>
  <div class="course-topics">
    <div class="topic-label">Topics</div>
    <div class="topic-tags">
      <span class="topic-tag">MLPs</span>
      <span class="topic-tag">Backpropagation</span>
      <span class="topic-tag">CNNs</span>
      <span class="topic-tag">Regularization</span>
      <span class="topic-tag">Data Efficiency</span>
      <span class="topic-tag">Multi-Modal Architectures</span>
      <span class="topic-tag">Visual Question Answering</span>
      <span class="topic-tag">PyTorch</span>
    </div>
  </div>
  <button class="course-details-toggle" onclick="this.setAttribute('aria-expanded', this.getAttribute('aria-expanded') === 'true' ? 'false' : 'true'); this.nextElementSibling.style.display = this.getAttribute('aria-expanded') === 'true' ? 'block' : 'none';" aria-expanded="false">
    <span class="toggle-icon">&#9654;</span> <span>Labs & Project</span>
  </button>
  <div class="course-details" style="display:none;">
    <ul class="assignments-list">
      <li>Built an MLP training framework from scratch with backpropagation on MNIST, then designed and ran custom experiments to evaluate model behavior.</li>
      <li>Investigated how regularization techniques (architectural and data/loss) influence data efficiency in deep models across custom datasets.</li>
      <li>Designed multi-modal VQA architectures for the VizWiz dataset, combining visual and textual inputs for binary classification and text generation challenges.</li>
      <li>Final project: developed a hybrid CNN-ViT model for chest X-ray pneumonia detection, combining CheXNet and MedViT with cross-attention fusion and Grad-CAM explainability — achieving 99.2% accuracy, outperforming standalone models and prior state-of-the-art.</li>
    </ul>
  </div>
</div>

<div class="course">
  <h2 class="course-title">CSCI 5622 — Machine Learning</h2>
  <div class="course-topics">
    <div class="topic-label">Topics</div>
    <div class="topic-tags">
      <span class="topic-tag">KNN</span>
      <span class="topic-tag">Linear & Logistic Regression</span>
      <span class="topic-tag">Deep Neural Networks</span>
      <span class="topic-tag">Explainable AI (LIME)</span>
      <span class="topic-tag">Decision Trees & Random Forests</span>
      <span class="topic-tag">PCA</span>
      <span class="topic-tag">Clustering</span>
      <span class="topic-tag">Ensemble Methods</span>
    </div>
  </div>
  <button class="course-details-toggle" onclick="this.setAttribute('aria-expanded', this.getAttribute('aria-expanded') === 'true' ? 'false' : 'true'); this.nextElementSibling.style.display = this.getAttribute('aria-expanded') === 'true' ? 'block' : 'none';" aria-expanded="false">
    <span class="toggle-icon">&#9654;</span> <span>Assignments</span>
  </button>
  <div class="course-details" style="display:none;">
    <a href="/coursework_samples/ML_HW2.pdf" class="sample-link"><i class="fa-solid fa-file-pdf"></i>Sample work</a>
    <ul class="assignments-list">
      <li>Predicted patient survival using KNN classifiers on breast cancer data, optimizing distance metrics and K values.</li>
      <li>Built regression and classification models for oceanographic salinity prediction using feature correlation analysis.</li>
      <li>Compared FNNs and CNNs for CIFAR-10 image classification; used LIME for model interpretability.</li>
      <li>Predicted job hireability from physiological measures using Decision Trees and Random Forests, analyzing ethical implications.</li>
      <li>Implemented speech-based depression detection using XGBoost with SMOTE for class imbalance and bias mitigation.</li>
    </ul>
  </div>
</div>

<div class="course">
  <h2 class="course-title">CSCI 5854 — Theoretical Foundations of Autonomous Systems</h2>
  <div class="course-topics">
    <div class="topic-label">Topics</div>
    <div class="topic-tags">
      <span class="topic-tag">Finite State Systems</span>
      <span class="topic-tag">Reachability & Safety</span>
      <span class="topic-tag">Transition Systems</span>
      <span class="topic-tag">Temporal Logic (LTL, CTL)</span>
      <span class="topic-tag">Model Checking</span>
      <span class="topic-tag">Formal Verification</span>
    </div>
  </div>
</div>

<div class="course">
  <h2 class="course-title">CSCI 5254 — Convex Optimization</h2>
  <div class="course-topics">
    <div class="topic-label">Topics</div>
    <div class="topic-tags">
      <span class="topic-tag">Convex Sets & Functions</span>
      <span class="topic-tag">Duality Theory</span>
      <span class="topic-tag">Gradient Descent</span>
      <span class="topic-tag">Newton's Method</span>
      <span class="topic-tag">SOCP & SDP</span>
      <span class="topic-tag">Robust Optimization</span>
    </div>
  </div>
  <button class="course-details-toggle" onclick="this.setAttribute('aria-expanded', this.getAttribute('aria-expanded') === 'true' ? 'false' : 'true'); this.nextElementSibling.style.display = this.getAttribute('aria-expanded') === 'true' ? 'block' : 'none';" aria-expanded="false">
    <span class="toggle-icon">&#9654;</span> <span>Assignments</span>
  </button>
  <div class="course-details" style="display:none;">
    <a href="/coursework_samples/CVX_HW5_Chakrabarty.pdf" class="sample-link"><i class="fa-solid fa-file-pdf"></i>Sample work</a>
    <ul class="assignments-list">
      <li>Formulated and solved constrained optimization problems using CVXPY with interior-point methods.</li>
      <li>Developed Lagrangian relaxation and duality-based solutions, implementing KKT conditions.</li>
      <li>Applied gradient and Newton's methods for large-scale convex problems, analyzing convergence rates.</li>
      <li>Implemented convex formulations for ML models including regression, classification, and structured prediction.</li>
    </ul>
  </div>
</div>

<div class="course">
  <h2 class="course-title">ASEN 5014 — Linear Control Design</h2>
  <div class="course-topics">
    <div class="topic-label">Topics</div>
    <div class="topic-tags">
      <span class="topic-tag">State-Space</span>
      <span class="topic-tag">Controllability & Observability</span>
      <span class="topic-tag">Stability Analysis</span>
      <span class="topic-tag">State Feedback & Observers</span>
      <span class="topic-tag">LQR</span>
    </div>
  </div>
  <button class="course-details-toggle" onclick="this.setAttribute('aria-expanded', this.getAttribute('aria-expanded') === 'true' ? 'false' : 'true'); this.nextElementSibling.style.display = this.getAttribute('aria-expanded') === 'true' ? 'block' : 'none';" aria-expanded="false">
    <span class="toggle-icon">&#9654;</span> <span>Assignments & Project</span>
  </button>
  <div class="course-details" style="display:none;">
    <a href="/coursework_samples/5014_homework5_chakrabarty.pdf" class="sample-link"><i class="fa-solid fa-file-pdf"></i>Sample work</a>
    <ul class="assignments-list">
      <li>Developed state-space models and evaluated controllability, observability, and stability properties.</li>
      <li>Designed and simulated state feedback controllers and observers in MATLAB for aerospace systems.</li>
      <li>Applied least squares and LQR optimization to enhance system performance.</li>
      <li>Modeled a quadcopter system with observer-based state estimation for real-time control.</li>
    </ul>
  </div>
</div>

<div class="course">
  <h2 class="course-title">CSCI 5722 — Computer Vision</h2>
  <div class="course-topics">
    <div class="topic-label">Topics</div>
    <div class="topic-tags">
      <span class="topic-tag">Image Transforms</span>
      <span class="topic-tag">Feature Detection</span>
      <span class="topic-tag">Filtering</span>
      <span class="topic-tag">CNNs</span>
      <span class="topic-tag">ResNet</span>
      <span class="topic-tag">U-Net</span>
      <span class="topic-tag">Autoencoders</span>
      <span class="topic-tag">GANs</span>
      <span class="topic-tag">Transformers & ViT</span>
      <span class="topic-tag">CLIP</span>
      <span class="topic-tag">Diffusion Models</span>
      <span class="topic-tag">Camera Models</span>
    </div>
  </div>
</div>

<div class="course">
  <h2 class="course-title">ECEN 5612 — Random Processes</h2>
  <div class="course-topics">
    <div class="topic-label">Topics</div>
    <div class="topic-tags">
      <span class="topic-tag">Probability</span>
      <span class="topic-tag">Random Variables</span>
      <span class="topic-tag">MMSE Estimation</span>
      <span class="topic-tag">Gaussian Random Vectors</span>
      <span class="topic-tag">Markov Processes</span>
      <span class="topic-tag">Poisson & Wiener Processes</span>
      <span class="topic-tag">Wiener Filtering</span>
      <span class="topic-tag">Markov Chains</span>
    </div>
  </div>
</div>

<div class="course">
  <h2 class="course-title">EMEN 5405 — Fundamentals of Systems Engineering</h2>
  <div class="course-topics">
    <div class="topic-label">Topics</div>
    <div class="topic-tags">
      <span class="topic-tag">Systems Engineering Process</span>
      <span class="topic-tag">Requirements Analysis</span>
      <span class="topic-tag">Functional Analysis</span>
      <span class="topic-tag">Trade Studies</span>
      <span class="topic-tag">Risk Management</span>
      <span class="topic-tag">IPPD</span>
    </div>
  </div>
  <button class="course-details-toggle" onclick="this.setAttribute('aria-expanded', this.getAttribute('aria-expanded') === 'true' ? 'false' : 'true'); this.nextElementSibling.style.display = this.getAttribute('aria-expanded') === 'true' ? 'block' : 'none';" aria-expanded="false">
    <span class="toggle-icon">&#9654;</span> <span>Project</span>
  </button>
  <div class="course-details" style="display:none;">
    <p class="project-description">
      Group project designing a targeting system for the Phalanx Block 1B CIWS, integrating a sensor suite and display/control system to enhance target detection in various environmental conditions.
    </p>
    <ul class="assignments-list">
      <li>Created functional and physical block diagrams, allocated requirements, and developed a specification compliance matrix.</li>
      <li>Conducted a technology readiness assessment, performed trade studies, and identified key performance measures.</li>
      <li>Developed a test plan, risk analysis, program schedule, and work breakdown structure.</li>
    </ul>
  </div>
</div>
