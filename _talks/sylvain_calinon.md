---
layout: talk
type: "Talk"
date: 2022-11-02
name: "Sylvain Calinon"
teaser: "Robot learning from few examples by exploiting the structure and geometry of data"
link: "/talks/sylvain_calinon" 
---

### Speaker
Dr Sylvain Calinon is a Senior Research Scientist at the Idiap Research Institute and a Lecturer at the Ecole Polytechnique Fédérale de Lausanne (EPFL). He heads the Robot Learning & Interaction group at Idiap, with expertise in human-robot collaboration, robot learning from demonstration and model-based optimization. The approaches developed in his group can be applied to a wide range of applications requiring manipulation skills, with robots that are either close to us (assistive and industrial robots), parts of us (prosthetics and exoskeletons), or far away from us (shared control and teleoperation). Website: https://calinon.ch 

Speaker links: [Website](https://calinon.ch/) - [Google Scholar](https://scholar.google.com/citations?user=t7VnipMAAAAJ&hl=en)


<iframe width="560" height="315" src="https://www.youtube.com/embed/zpSQTsJemg8" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

---
### Abstract

A wide range of applications can benefit from robots acquiring manipulation skills by interaction with humans. In this presentation, I will discuss the challenges that such a learning process encompasses, including representations for manipulation skills that can exploit the structure and geometry of the acquired data, the development of optimal control strategies that can exploit variations in manipulation skills, and the development of intuitive interfaces to acquire meaningful demonstrations.

From a machine learning perspective, the core challenge is that robots can only rely on a small number of demonstrations. The good news is that we can exploit bidirectional human-robot interaction as a way to collect better data. We can also rely on various structures that remain the same within a wide range of robotic tasks. Such structures include geometrical aspects, by extending learning strategies that have been originally developed for standard Euclidean space to Riemannian manifolds. In robotics, these manifolds include orientation, manipulability ellipsoids, graphs and subspaces. Another type of structure that we study relates to the organization of data as multidimensional arrays (also called tensors). These data appear in various robotic tasks, either as the natural organization of sensorimotor data (tactile arrays, images, kinematic chains), or as the result of preprocessing steps (moving time windows, covariance features). Tensor factorization techniques (also called tensor methods or multilinear algebra) can be used to learn from only few tensor datapoints, by exploiting the multidimensional nature of the data.

Another key challenge in robot skill acquisition is to link the learning aspects to the control aspects. Optimal control provides a framework that allows us to take into account the possible variations of a task, the uncertainty of sensorimotor information, and the movement coordination patterns, by relying on well grounded control techniques such as linear quadratic tracking and differential dynamic programming. The formulation draws explicit links with learning techniques, as we can recast these techniques as Gauss-Newton optimization problems formulated at trajectory level (in both control space and state space), which facilitates the links to probabilistic approaches.

---
