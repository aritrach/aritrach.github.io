---
layout: page
permalink: /coursework/
title: Coursework
description: Coursework and related projects that I have completed during my Master's 🎓
nav: true
nav_order: 3
---

<div class="coursework-intro">
  In order to avoid hampering my professors who may re-use some of the assignments, I have only provided some examples of my programming work. Please reach out if you want to see more in detail!
</div>


<div class="course">
  <h2 class="course-title">CSCI 5302 - Advanced Robotics</h2>
  <div class="course-topics">
    <em>Topics Learned:</em> Robot Operating System (ROS), Kinematics and Controls, Motion Planning, Convex Optimization, Function Approximation, State Estimation (Bayes Filters, Kalman Filters, EKF, UKF), SLAM (Simultaneous Localization and Mapping), Partial Observability, Deep Reinforcement Learning, Safe Task and Motion Planning, Explainable AI, Intelligent Tutoring, Human-Agent Teaming, Collaborative AI
  </div>
  <div class="row mt-1">
    <div class="col-md-4 text-center">
      {% include figure.liquid 
        loading="eager" 
        path="/coursework_samples/IMG_5119-ezgif.com-video-to-gif-converter.gif" 
        class="img-fluid rounded z-depth-1 mx-auto" 
        width="100%" 
        height="auto" 
      %}
      <div class="caption">
        The final AWS Deepracer navigating a hallway, as fast as it can without crashing!
      </div>
    </div>
    <div class="col-md-8">
      <h3>Assignments & Project</h3>
      <ul class="assignments-list">
        <li>
          Implemented Rapidly-Exploring Random Trees (RRT) algorithm for motion planning in high-dimensional spaces, and enhanced it with RRT* to optimize paths and reduce travel distance, handling both holonomic and non-holonomic motion.
        </li>
        <li>
          Configured ROS2 environment, explored nodes, topics, services, and actions. Developed and tested publisher/subscriber nodes and service/client nodes using Python.
        </li>
        <li>
          Implemented value iteration and policy iteration algorithms for tabular cases in grid-world environments. Applied nearest-neighbor and n-linear interpolation methods for value iteration in continuous state spaces, specifically the MountainCar domain.
        </li>
        <li>
          Utilized an AWS DeepRacer equipped with ROS2 Foxy on Ubuntu 20.04 to autonomously navigate a square hallway. Processed LIDAR data for obstacle detection and navigation, communicating with a PID controller via ROS2. Implemented camera data processing using YOLOv3 for stop sign recognition and response. Addressed challenges such as SLAM implementation, system memory management, and network communication issues.
        </li>
      </ul>
    </div>
  </div>
</div>


<div class="course">
  <h2 class="course-title">CSCI 7000 - Transformer-Based Robotic AI</h2>
  <div class="course-topics">
    <em>Topics Learned:</em> Transformers for Robotics, Large Language Models (LLMs), Vision-Language Models (VLMs), Vision-Language-Action Models (VLAs), Multi-Modal Learning
  </div>

  <h3>Research & Blog Posts</h3>
  <ul class="assignments-list">
    <li>
      Published <a href="https://medium.com/correll-lab/clip-implementation-with-pre-trained-embeddings-9b2eca91dc22">an article</a> implementing CLIP with pre-trained embeddings for robotic perception.
    </li>
    <li>
      Analyzed Deep Transformer Q-Networks (DTQN) in reinforcement learning, detailing findings in <a href="https://medium.com/correll-lab/deep-transformer-q-networks-a-paper-analysis-e7efd9379e5f">this article</a>.
    </li>
    <li>
      Analyzed cutting-edge transformer applications in robotics, including Open X-Embodiment, OK-Robot, Manipulate-Anything, and Vision Transformers (ViTs).
    </li>
    <li>
      Explored scalability of VLMs and VLAs for real-world robotic tasks, evaluating architectures like CLIP, GPT, and diffusion models.
    </li>
  </ul>
</div>



<div class="course">
  <h2 class="course-title">ASEN/CSCI 5264 - Decision Making under Uncertainty</h2>
  <div class="course-topics">
    <em>Topics Learned:</em> Bayesian Networks, Markov Decision Processes (Value Iteration, Policy Iteration, Policy Evaluation), Reinforcement Learning (Model-based, Tabular, Policy Gradient, SARSA, Q-Learning), Neural Networks, Deep Q-Networks (DQN), Advanced Policy Gradient, Actor-Critic Methods, Entropy Regularization, Partially Observable Markov Decision Processes (Offline & Online solution Methods), Particle Filters, Basic Game Theory, Partially Observable Markov Games, Bayesian Network Learning, Imitation Learning, Inverse RL
  </div>

  <h3>Assignments & Project</h3>
  <a href="/coursework_samples/DMU_HW5.pdf" class="sample-link">Sample of my work</a>
  <ul class="assignments-list">
    <li>
      Implemented Online MDP Methods using Dense Grid World simulations; developed Monte Carlo Policy Evaluation and heuristic policies to enhance baseline performance. Conducted experiments with Monte Carlo Tree Search to optimize decision-making processes.
    </li>
    <li>
      Engaged in the implementation and comparative analysis of tabular reinforcement learning algorithms including Q-Learning and SARSA, crafting learning curves to evaluate efficiencies and computational demands.
    </li>
    <li>
      Modeled a POMDP for cancer monitoring using QuickPOMDPs.jl, executed policy evaluation with Monte Carlo methods, and integrated neural networks to approximate complex functions in reinforcement learning.
    </li>
    <li>
      Developed QMDP and SARSOP solvers for the TigerPOMDP, contrasting heuristic and optimal policies within a cancer monitoring framework to evaluate efficacy and limitations of approximation methods.
    </li>
    <li>
      Formulated high-performance policies and belief updaters for a Lasertag POMDP; employed a combination of heuristic approaches, deep reinforcement learning, and MCTS (Partially Observable Monte Carlo Policy) for adaptive decision-making capabilities.
    </li>
  </ul>
</div>



<div class="course">
  <h2 class="course-title">CSCI 5622 - Machine Learning</h2>
  <div class="course-topics">
    <em>Topics Learned:</em> KNN, Linear Perceptrons, Linear & Logistic Regression, Deep Neural Networks, Explainable AI (LIME), Decision Trees & Random Forests, Dimensionality Reduction (PCA), Clustering, Ensemble Methods (Bagging, Boosting, Combination methods), Model Evaluation & Hyperparameter Tuning
  </div>
  <h3>Assignments</h3>
  <a href="/coursework_samples/ML_HW2.pdf" class="sample-link">Sample of my work</a>
  <ul class="assignments-list">
    <li>
      Analyzed breast cancer data to predict patient survival using K-Nearest Neighbors (K-NN) classifiers, adjusting distance metrics and K values to optimize prediction accuracy based on comprehensive performance metrics (Acc, BAcc, F1).
    </li>
    <li>
      Developed a model to predict salinity levels from oceanographic measurements using linear regression, exploring feature correlations and impacts on model accuracy, and employed logistic regression for binary classification of salinity levels.
    </li>
    <li>
      Implemented machine learning models for object recognition using the CIFAR-10 dataset, comparing the performance of Feedforward Neural Networks (FNNs) and Convolutional Neural Networks (CNNs) on image classification tasks. Also used LIME in order to explain the model.
    </li>
    <li>
      Predicted job hireability from physiological and vocal measures during interviews using Decision Trees and Random Forests, analyzing model decision boundaries and ethical implications of automated hireability assessments.
    </li>
    <li>
      Implemented speech-based ML model to detect depression and classify using XGBoost. Addressed class imbalances by using SMOTE, and mitigated gender bias by removing gender-dependent features.
    </li>
  </ul>
</div>



<div class="course">
  <h2 class="course-title">CSCI 5254 - Convex Optimization</h2>
  <div class="course-topics">
    <em>Topics Learned:</em> Convex Sets & Functions, Duality Theory, Optimization Algorithms (Gradient Descent, Newton’s Method), Second-Order Cone & Semidefinite Programming, Robust & Stochastic Optimization, Applications in Machine Learning & Control
  </div>

  <h3>Assignments</h3>
  <a href="/coursework_samples/CVX_HW5_Chakrabarty.pdf" class="sample-link">Sample of my work</a>
  <ul class="assignments-list">
    <li>
      Formulated and solved constrained optimization problems using CVXPY, implementing interior-point methods for high-dimensional convex problems.
    </li>
    <li>
      Developed Lagrangian relaxation and duality-based solutions, proving optimality conditions and implementing KKT conditions in real-world applications.
    </li>
    <li>
      Applied gradient and Newton’s methods for solving large-scale convex problems, analyzing convergence rates and performance in constrained settings.
    </li>
    <li>
      Implemented convex formulations for machine learning models, including regression, classification, and structured prediction using convex relaxations.
    </li>
  </ul>
</div>



<div class="course">
  <h2 class="course-title">ASEN 5014 - Linear Control Design</h2>
  <div class="course-topics">
    <em>Topics Learned:</em> State-Space Representation, Controllability & Observability, Stability Analysis, State Feedback & Observer Design, Linear Quadratic Regulation (LQR), Controls Optimization
  </div>

  <h3>Assignments & Project</h3>
  <a href="/coursework_samples/5014_homework5_chakrabarty.pdf" class="sample-link">Sample of my work</a>
  <ul class="assignments-list">
    <li>
      Developed state-space models for dynamic systems and evaluated controllability, observability, and stability properties.
    </li>
    <li>
      Designed and simulated state feedback controllers and observers in MATLAB for estimation and control of aerospace systems.
    </li>
    <li>
      Applied optimization techniques, including least squares and LQR, to enhance system performance.
    </li>
    <li>
      Modeled and analyzed a quadcopter system, implementing observer-based state estimation for real-time control.
    </li>
  </ul>
</div>




<div class="course">
  <h2 class="course-title">ECEN 5612 - Random Processes</h2>
  <div class="course-topics">
    <em>Topics Learned:</em> Probability, Discrete Random Variables, Continuous Random Variables, Cumulative Distribution Functions, Bivariate Random Variables, Random Vectors, Minimum Mean-Square Error Estimation, Gaussian Random Vectors, Markov Processes, Poisson Processes, Wiener Processes, Linear Systems with Random Inputs, Wiener Filtering, Convergence of Random Sequences, Markov Chains
  </div>
</div>

<div class="course">
  <h2 class="course-title">EMEN 5405 - Fundamentals of Systems Engineering</h2>
  <div class="course-topics">
    <em>Topics Learned:</em> The Systems Engineering Process, System Design Requirements, Engineering Design Methods and Tools, Design Review and Evaluation, System Engineering Program Planning, Organization for Systems Engineering, System Engineering Program Evaluation, Life Cycle of Systems, Requirements Analysis, Functional Analysis, Trade Studies, Risk Management, Integrated Product and Process Development (IPPD), Benchmarking Best Practices, Program Reporting and Feedback
  </div>
  <h3>Project</h3>
  <p class="project-description">
    The class culminated with a final project where we worked in groups to design a system. We chose to design a targeting system for the Phalanx Block 1B Close-In Weapon System (CIWS) used by the U.S. Navy, focusing on integrating a sensor suite and display/control system to enhance target detection and tracking capabilities in various environmental conditions.
  </p>
  <ul class="assignments-list">
    <li>
      Created functional and physical block diagrams, allocated requirements to subsystems, and developed a specification compliance matrix to ensure all requirements were met.
    </li>
    <li>
      Conducted a technology readiness assessment (TRA) for the tracking software, performed a trade study for the best display option, and identified key performance measures (TPM) to monitor design maturity.
    </li>
    <li>
      Developed a detailed test plan, analyzed potential risks, and created a comprehensive program schedule and work breakdown structure (WBS) to manage the project timeline and tasks.
    </li>
  </ul>
</div>





