---
title: Control of Soft Robots
summary: Learning based control strategies for soft robots.
tags:
date: '2016-04-27T00:00:00Z'


    
# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: 
  focal_point: Smart


url_code: ''
url_pdf: ''
url_slides: ''
url_video: ''


---


Soft robots are high-dimensional dynamical systems that exhibit complex nonlinear behaviors. Modelling and control of these systems is a challenging task and some of these projects investigate the use of Machine Learning techniques for this problem. 




**_Static Shape Control of Soft Continuum Robots using Deep Visual Inverse Kinematic Models_**

Soft continuum robots have immense potential in numerous industrial applications because of their high flexibility and adaptability. This makes them more suited for working in unstructured environments such as the human body, or in agriculture, compared to their traditional rigid-linked counterparts. However, their high compliance and high manoeuvrability also make them hard to model, sense, and control. Existing control strategies focus on the Cartesian space control of the end-effector, whereas there are few works looking into the full-body control of these complex systems. This work presents a novel image-based deep learning approach for closed-loop kinematic shape control of soft continuum robots. The method combines a local inverse kinematics formulation in the image-space with deep convolutional neural networks for accurate shape control that is robust to feedback noise and mechanical changes in the continuum arm. The shape controller is fast and straightforward to implement; it takes only a few hours to generate training data, train the network, and deploy, requiring only a web camera for feedback. We then show that this technique is capable of a highly intuitive and user-friendly form of teleoperated 3D shape/configuration control when given only 2D hand-drawn images of the desired target state.


{{< youtube _Qn3pB-BaWI >}}


**_Model-Based Reinforcement Learning for Closed-Loop Dynamic Control of Soft Robotic Manipulators_**

Dynamic control of soft robotic manipulators is an open problem yet to be well explored and analyzed. Most of the current applications of soft robotic manipulators utilize static or quasi-dynamic controllers based on kinematic models or linearity in the joint space. However, such approaches are not truly exploiting the rich dynamics of a soft-bodied system. In this paper, we present a model-based policy learning algorithm for closed-loop predictive control of a soft robotic manipulator. The forward dynamic model is represented using a recurrent neural network. The closed-loop policy is derived using trajectory optimization and supervised learning. The approach is verified first on a simulated piecewise constant strain model of a cable driven under-actuated soft manipulator. Furthermore, we experimentally demonstrate on a soft pneumatically actuated manipulator how closed-loop control policies can be derived that can accommodate variable frequency control and unmodeled external loads.

{{< youtube VkhXT-1XFSo >}}

