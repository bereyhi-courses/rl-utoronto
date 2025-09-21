---
layout: page
title: Project
permalink: /project/
---
<p>
<div style="background-color:#f0f0f0; padding:10px; border-radius:10px; text-align:left; width:95%; margin: 0 auto;">
  <h2><strong>Code of Honor</strong></h2>
  This project is intended to deepen your understanding and develop your skills, and it forms a substantial part of your final evaluation. It must be completed collaboratively as a group. Any form of academic dishonesty is a violation of the Code of Honor. You are encouraged to use publicly available resources, provided that all <em>sources are clearly cited</em> and your individual <em>contributions are clearly explained.</em> Failure to properly acknowledge your contribution may be considered a <strong>lack of participation</strong>, and projects without meaningful individual contributions will be deemed <strong>incomplete.</strong>
</div>
</p>

The course project will be seriously started in the second half of the course. In these project, you choose a topic from the list of available topics and work through semester to deliver the requested outcomes of the project. Regardless of topic of the project, you will need to follow the following steps:

1. Make a group of 3 or 4. Due to the course size, smaller group size is only accepted under __special circumstances,__ e.g., working on an open-ended topic of your own or a group member dropping in the middle of semester. 
2. Submit your topic by the end of __Week 5.__ It is strongly suggested to choose _as soon as possible_ to get into the problem and start preliminaries.
2. You will be allocated to a TA, who could help you throughout the project.
3. Deliver initial milestones of the project in a progress briefing by __Week 10__. The progress briefing will serve as the base for your final report.
4. Deliver your final results by the end of semester. This includes the final report, the source codes, and a final presentation in our internal seminar.

<p>
<div style="background-color:#f5dcdc; padding:10px; border-radius:10px; text-align:left; width:95%; margin: 0 auto;">
  <h2><strong>Submission Procedure</strong></h2>
  The main body of work is submitted through Git. In addition, each group submits a final paper and gives a presentation. In this respect, please follow these steps.
  <ul>
    <li>
      Each group must maintain a Git repository, e.g., GitHub or GitLab, for the project. By the time of final submission, the repository should have:
      <ul>
        <li>Well-documented codebase</li>
        <li>Clear <code>README.md</code> with setup and usage instructions</li>
        <li>A <code>requirements.txt</code> file listing all required packages or an <code>environment.yaml</code> file with a reproducible environment setup</li>
        <li>Demo script or notebook showing sample input-output</li>
        <li><em>If applicable,</em> a <code>/doc</code> folder with extended documentation</li>
      </ul>
    </li>
    <li>
      A final report (maximum <em>5 pages</em>) must be submitted in a PDF format. The report should be written in the provided formal style, including an abstract, introduction, method, experiments, results, and conclusion.<br>
      <strong>Important:</strong> Please make sure to complete the section <em>Consent for Information Sharing.</em>
      <strong>Important:</strong> Submissions that do not use template are considered <em>incomplete.</em>
    </li>
    <li>
      A 5-minute presentation (maximum <em>5 slides including the title slide</em>) is given on the internal seminar on Week 14, i.e., <em>Dec 1 to Dec 5,</em> by the group. For presentation, any template can be used.
    </li>
  </ul>
</div>
</p>

## Project Topics


### Category A: _Deep RL from Scratch_ 

#### __Topic A-1: From REINFORCE to Advantage Actor-Critic__
- [See Complete Project Description]({{site.baseurl}}/assets/Project_Materials/CategoryA/TopicA_1.pdf) 
- __Objective:__ Design and implement a progression of policy gradient algorithms starting from REINFORCE, extending it with a baseline, and finally implementing Advantage Actor-Critic (A2C). The project aims to compare the stability, sample efficiency, and learning dynamics across these algorithms in classic control environments.

#### __Topic A-2: Trust Region versus Proximal Policy Optimization__
- [See Complete Project Description]({{site.baseurl}}/assets/Project_Materials/CategoryA/TopicA_2.pdf) 
- __Objective:__ Design and implement two advanced actor–critic policy optimization algorithms: Trust Region Policy Optimization (TRPO) and Proximal Policy Optimization (PPO). Compare their stability, sample efficiency, and robustness in classic continuous control tasks.

#### __Topic A-3: Deterministic versus Stochastic Policy Gradients: DDPG and SAC__
- [See Complete Project Description]({{site.baseurl}}/assets/Project_Materials/CategoryA/TopicA_3.pdf) 
- __Objective:__ Design and implement two advanced actor–critic algorithms for continuous control: Deep Deterministic Policy Gradient (DDPG) and Soft Actor-Critic (SAC). Compare their performance in terms of stability, sample efficiency, and robustness on continuous-action Gym environments.

### Category B: _Applications of RL_ 

#### __Topic B-1: Using RL to Finetune a Language Model__
- [See Complete Project Description]({{site.baseurl}}/assets/Project_Materials/CategoryB/TopicB_1.pdf) 
- __Objective:__ Design and implement a simplified pipeline for RL-based finetuning of language models (LMs). Starting from a small pretrained LM, e.g., DistilGPT2, you will implement a policy optimization method (PPO) to improve LM outputs according to a reward model, e.g., sentiment classifier. The project aims to compare supervised finetuning against RL-based one, and to analyze the effect of different reward models and modifications.

#### __Topic B-2: Using RL for Portfolio Management__
- [See Complete Project Description]({{site.baseurl}}/assets/Project_Materials/CategoryB/TopicB_2.pdf) 
- __Objective:__ Design and implement an RL agent for portfolio management. The agent should allocate capital across a small set of assets, e.g., 3–5 stocks or ETFs, to maximize long-term returns while managing risk. The project aims to compare RL-based strategies, e.g., DQN, PPO, with heuristic baselines such as Buy-and-Hold or Equal Weighting.

#### __Topic B-3: Using RL for Traffic Signal Control__
- [See Complete Project Description]({{site.baseurl}}/assets/Project_Materials/CategoryB/TopicB_3.pdf) 
- __Objective:__ Design and implement an RL agent to optimize traffic signal control at one or more intersections. The agent should minimize congestion and vehicle waiting times by dynamically adjusting traffic light phases. The project aims to compare RL-based policies with simple heuristics such as fixed-time or round-robin controllers.

#### __Topic B-4: Using RL to Build a Recommendation System__
- [See Complete Project Description]({{site.baseurl}}/assets/Project_Materials/CategoryB/TopicB_4.pdf) 
- __Objective:__ Design and implement a reinforcement learning agent for sequential recommendation. The agent should recommend items (e.g., movies or products) to maximize long-term user engagement. The project aims to compare RL-based policies with traditional recommendation baselines such as collaborative filtering or random recommendation.


### Category C: _Robotics and Automation_ 

#### __Topic C-1: Controlling Robotic Arm with RL__
- [See Complete Project Description]({{site.baseurl}}/assets/Project_Materials/CategoryC/TopicC_1.pdf) 
- __Objective:__ Design and implement an RL agent to control a robotic arm in a \textit{reaching task}. The agent should learn to move the robot’s end-effector to a target location in continuous action space. The project aims to compare RL algorithms such as PPO and SAC, and evaluate their robustness under environment modifications.

#### __Topic C-2: RL for Robotic Locomotion__
- [See Complete Project Description]({{site.baseurl}}/assets/Project_Materials/CategoryC/TopicC_2.pdf) 
- __Objective:__ Design and implement RL agents to train a simulated robot to perform locomotion tasks such as hopping or walking. The project should compare algorithms like PPO and SAC in terms of stability, sample efficiency, and robustness. The environment can be selected from lightweight simulators such as PyBullet (Hopper, Ant, or Walker).

#### __Topic C-3: RL for Autonomous Driving__
- [See Complete Project Description]({{site.baseurl}}/assets/Project_Materials/CategoryC/TopicC_3.pdf) 
- __Objective:__ Design and implement an RL agent for basic autonomous driving tasks such as lane-keeping, overtaking, or collision avoidance. The project aims to compare RL-based driving policies with simple rule-based baselines in lightweight simulators such as _Highway-env._

### Category D: _Resource Allocation_ 

#### __Topic D-1: RL for Job Scheduling in a Compute Cluster__
- [See Complete Project Description]({{site.baseurl}}/assets/Project_Materials/CategoryD/TopicD_1.pdf) 
- __Objective:__ Design and implement an RL agent for job scheduling in a simulated compute cluster. The agent should decide which jobs to execute in order to optimize performance metrics such as throughput, average waiting time, or fairness. The project aims to compare RL-based scheduling policies with classical heuristics such as First-Come-First-Served (FCFS) or Shortest-Job-First (SJF).

#### __Topic D-2: RL for Wireless Resource Allocation__
- [See Complete Project Description]({{site.baseurl}}/assets/Project_Materials/CategoryD/TopicD_2.pdf) 
- __Objective:__ Design and implement an RL agent for wireless resource allocation in a small multi-user system. The agent should allocate power or bandwidth among users to maximize throughput while ensuring fairness. The project aims to compare RL-based allocation policies with traditional heuristics such as round-robin or max-SINR scheduling.

#### __Topic D-3: Cache Management via RL__
- [See Complete Project Description]({{site.baseurl}}/assets/Project_Materials/CategoryD/TopicD_3.pdf) 
- __Objective:__ Design and implement an RL agent for cache management in a simulated system. The agent should learn eviction and admission strategies to minimize cache misses given a stream of content requests. The project aims to compare RL-based caching policies with classical baselines such as Least Recently Used (LRU) and Least Frequently Used (LFU).

### Category E: _Open-ended_ 
* You can develop your own proposal 
* The proposal should meet the technical level of pre-defined projects
* Please prepare your proposal in the format other proposals are given
* You may use the [provided proposal template]({{site.baseurl}}/assets/Project_Materials/Proposal_Template.zip)

## Templates for Proposal, Report and Presentation
* [Proposal Template]({{site.baseurl}}/assets/Project_Materials/Proposal_Template.zip) This is the template for project proposal. You _can_ use other template as well
* [Report Template - LaTex]({{site.baseurl}}/assets/Project_Materials/Project_Report_Template.zip): Other templates are __not__ accepted! 
* [Prsentation Template]({{site.baseurl}}/assets/Project_Materials/Template_Slides_Presentation.zip) You _can_ use other template as well



