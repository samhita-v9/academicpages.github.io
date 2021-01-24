---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a PhD candidate at University of Illinois, Urbana Champaign. Prior to this, I pursued my Dual degree: Masters in Mathematics and Bachelors in Computer Science, from BITS, Pilani, Hyderabad Campus. I am advised by Prof Rakesh Nagi and am a part of the C3SR team, a collaboration with IBM. 

Research Interests
======
My Research is focused on Optimization and Operations Research. I am currently focused on optimization in neural networks. I have worked on formulating real life applications into mixed integer programming problems and then involved in the design and development of accelerated algorithms for these problems. 

1.Multi Target Tracking
-----

Multi-Target Tracking (MTT) is a prominent computer vision/ aerospace/ optimization problem that can be formulated as a Multi-dimensional Assignment Problem (MAP). MAP is a generalization of a Linear Assignment Problem with a k-partite graph as imput. This problem is NP-Hard for k greater than 2. This project is a combination of both theory and computation. I have designed a dual-ascent based algorithm and then developed a GPU-accelerated code, that is enabled to handle about 25 billion variables. A provable optimal solution is found is found for most of the test cases. The code was executed in C++ and CUDA. 

 
2.Entity Resolution and Coreference.
-----
Entity Resolution is an umbrella to many NLP problems such as Entity linking and Coreference resolution. The goal of the problem is to resolve multiple references of the same real world entity. This problem is also used as a precursor for other NLP problems such as Question Answering, Document summarization etc. As a solution approach, I have formulated this problem as an integer programming problems and developing an accelerated algorithm to deak with large scale data. This approach is aimed at overcoming the challenges faced by deep learning techniques. One such major challenge is the violation of "common sense constraints", which because of an optimal solution to a mathematical formulation, will be overcome through this approach. 

3.Generalized Set Packing Problem 
----

The original set packing formulation is cumbersome because of the design of the formulation and the input requirements. I have develped a new formulation that overcomes these issues and reduces the input size for the same problem by an exponential factor. I am currently working on developing a scalable solution that is GPU accelerated and enabled to handle large graphs.  

Academic Projects
======
As a part of some of my courses at UIUC, I have pursued the following projects. 



1. A survey on Visual Question Answering on Medical Datasets
-----

Course: Natural Language Processing Course Project, CS 447, UIUC

As a part of this project, I performed an extensive literature review on Visual Question Answering with a focus on medical data and identified challenges when dealing with medical data. Visual Question Answering is a NLP task that takes images and a question related to that image and outputs an answer to that question.  Visual Question Answering (VQA) in medical data is more complex than general data because the questions are very specific and the answers are highly detailed. I was interested in understanding different kinds of deep learning models that could be used to tackle such issues. I am currently exploring the idea of using Dynamic Neural Modules (DNM) for VQA on medical datasets. 


2. Analysis of the instabilities in neural networks in medical image reconstruction      
-----

Course: Machine Learning in Signal Processing Course Project, CS 598 PS, UIUC

As a part of this project, I analyzed performance of four prominent neural network architectures in presence of adversarial attacks and instabilities. Medical image reconstruction is an inverse problem and lately deep learning models are rising up to show better performance than the traditional models such as compressed sensing, parallel image sensing. However, these models are susceptible to instabilities when faced with adverserial attacks. This project was focused on identifying the instabilities that could be caused and the reaction of four prominent deep learning networks to such instabilities. I am currently exploring tways to make these models robust.  


3. Show and Tell
-----

Course: Deep learning IE 598, UIUC

I worked on building a generative model with a deep recurrent architecture to automatically generate captions for an image using Pytorch. Trained a CNN (ResNet152) as image encoder with LSTM as decoder network and generated captions using beam search with beam size 2. Evaluated the captions using BLEU score, achieving a score of 16.31 as against 27.7 by the paper authors.

Background
=====
I graduated with my M.Sc (Honors) in Mathematics and B.E (Honors) in Computer Science (dual degree) from BITS Pilani, Hyderabad Campus in 2017. I pursued my Masters' thesis externally at IIT Bombay in the Fall Semester of 2016. 


Contact
=====
email: samhita3atillinoisdotedu

