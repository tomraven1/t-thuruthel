---
title: Developmental Robotics
summary: Modelling and control with minimal human intervention
tags: 
date: '2019-04-27T00:00:00Z'


    
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


Human develop their perceptive system and motor skills (arguably) in an unsupervised manner, with only high-level feedback. Even in robotic systems that rely on learning-based approaches, human intervention and labelling is required for sensing and control.    

Some of these projects investigate weakly-supervised methods for developing forward models for state estimation and control. 

**_Multi-modal Sensor Fusion for Learning Rich Models for Interacting Soft Robots_**

Soft robots are typically approximated as low-dimensional systems, especially when learning-based methods are used. This leads to models that are limited in their capability to predict the large number of deformation modes and interactions that a soft robot can have. In this work, we present a deep-learning methodology to learn high-dimensional visual models of a soft robot combining multimodal sensorimotor information. The models are learned in an end-to-end fashion, thereby requiring no intermediate sensor processing or grounding of data. The capabilities and advantages of such a modelling approach are shown on a soft anthropomorphic finger with embedded soft sensors. We also show that how such an approach can be extended to develop higher level cognitive functions like identification of the \textit{self} and the external environment and acquiring object manipulation skills. This work is a step towards the integration of soft robotics and developmental robotics architectures to create the next generation of intelligent soft robots. 

{{< youtube 031JQxBirCI >}}

**_Static Shape Control of Soft Continuum Robots using Deep Visual Inverse Kinematic Models_**

Soft continuum robots have immense potential in numerous industrial applications because of their high flexibility and adaptability. This makes them more suited for working in unstructured environments such as the human body, or in agriculture, compared to their traditional rigid-linked counterparts. However, their high compliance and high manoeuvrability also make them hard to model, sense, and control. Existing control strategies focus on the Cartesian space control of the end-effector, whereas there are few works looking into the full-body control of these complex systems. This work presents a novel image-based deep learning approach for closed-loop kinematic shape control of soft continuum robots. The method combines a local inverse kinematics formulation in the image-space with deep convolutional neural networks for accurate shape control that is robust to feedback noise and mechanical changes in the continuum arm. The shape controller is fast and straightforward to implement; it takes only a few hours to generate training data, train the network, and deploy, requiring only a web camera for feedback. We then show that this technique is capable of a highly intuitive and user-friendly form of teleoperated 3D shape/configuration control when given only 2D hand-drawn images of the desired target state.


{{< youtube _Qn3pB-BaWI >}}
