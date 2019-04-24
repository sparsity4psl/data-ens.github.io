---
layout: page
title: "Program"
description: "<b>Sparsity for Physics, Signal and Learning <br> June 24th - 27th 2019</b>"
header-img: "img/inria.png"
---

The given titles are preliminary, the definitive program is coming soon.

## Courses
* [Yohann De Castro](https://ydecastro.github.io/) (ENPC)  
**Measures estimation with moments, off-the-grid inverse problems**

* [Emilie Chouzenoux](http://www-syscom.univ-mlv.fr/~chouzeno/) (Paris Est Marne-la-Vallée)  
**Optimisation and applications in imaging**

* [Karen Veroy-Grepl](https://www.aices.rwth-aachen.de/en/about-aices/people/principal-investigators/details-zur-person/veroy-grepl) (RWTH-Aachen)  
**Introduction to Reduced Basis Methods: Theory and Applications**  
*Abstract*: This three-part course aims to provide an introduction to the theory and applications of model order reduction (MOR) techniques for parametrized partial differential equations, with a particular focus on reduced basis methods.  Part I begins with the basic aims of MOR for parametrized systems.  After a brief overview of different parametric MOR techniques, we introduce the basic elements of reduced basis (RB) methods — approximation, error estimation, sampling, and implementation — for different types of parametrized PDEs.  In Part II, we focus on RB methods for optimal control and variational data assimilation.  Here, we use the reduced order models as surrogates in the resulting optimization problem, and detail how the RB spaces and error estimates are developed for this particular setting.  In Part III, we discuss different application settings, particularly in medicine and the geosciences, as well as current research directions.  
*Joint works with:* M. Grepl, S. Boyaval, M. Kärcher, N. Nellesen, Z. Tokoutsi and D. Degen.



* [Bernard Haasdonk](https://www.ians.uni-stuttgart.de/institute/team/Haasdonk-00005/) (Stuttgart University)  
**Kernel Methods for Surrogate Modelling**  
 *Abstract*: Kernel methods are a very efficient class of algorithms
 in numerical analysis and machine learning.
 For example they allow function interpolation or approximation,
 PDE solution by collocation, data analysis by
 classification, regression and novelty detection.
 From a theoretical viewpoint they have a functional analytical
 background in Reproducing Kernel Hilbert Spaces (RKHS), that allows
 error and convergence analysis.
 Common goal for efficiency is sparsity in the kernel expansions.
 Apart from well known sparsity-inducing optimization targets, also
 greedy techniques are of high interest.
 We will present the theory and application of such methods,
 with particular focus on surrogate modelling.

## Talks
* [Albert Cohen](https://www.ljll.math.upmc.fr/cohen/) (Sorbonne Université)  
**Optimal non-intrusive methods in arbitrary dimension**  
 *Abstract*: Motivated by non-intrusive approaches for high-dimensional parametric PDEs, as well as other applications, we consider the approximation of an unknown arbirary function in any dimension from the data of point samples, where the approximants are picked from given or adaptively chosen finite dimensional spaces. One principal objective is to obtain an approximation which performs as good as the orthogonal projection using a sampling budget that is linear in the dimension of the approximating space. Using a particular sampling measure, this objective turns out to be met by both weighted least-squares and pseudo-spectral methods in some probabilistic sense, however with some notable distinctions that will be discussed in this talk. We also discuss how optimality can be maintained in an adaptive framework where the sampling measure needs to be updated together with the approximation space.

* [Yvon Maday](https://www.ljll.math.upmc.fr/maday/) (Sorbonne Universités)  
**Mixing data and reduced models for rapid predictions and control**  
 *Abstract*: Reconstruction of unknown functions from data has become one of the hottest problems in sciences and industry, especially that plethora of data are now available and people would like to use this amount to get more knowledge. Recent advances in AI (artificial intelligence) provided e.g. by deep neural network incite to get rid on profound understanding of the phenomenon and rely on the neural network to find the information by it self. If this may be true for many problems, in most situations the data are polluted with errors, are not structured enough or are incomplete. In these numerous cases, there is still need to HI (human intelligence) to provide the backbone of the data assimilation and/or treatment and help in getting stability and robustness. We shall present in this talk various applications of the use of reduced basis methods as such a backbone in case of different sizes of available data, and also of different noise level in these data.

* [Laure Blanc-Féraud](http://www-sop.inria.fr/members/Laure.Blanc_Feraud/) (CNRS I3S)  
**On sparse-l0 solutions of least-square fitting : on-grid methods, algorithms, and some results on image processing**
*Abstract*: The talk will be focused on minimization of criteria involving a least-square data term which links the solution to the noisy measurements and a l0-term  imposing sparsity to the solution, minimizing or constraining the number of non-zero components of the solution. In some real problems of signal and image processing, the sparsity cannot be imposed via convex l1-term but needs to be imposed by non-convex, non-continuous l0-term. The optimization problem is known to be NP hard. Several approaches will be presented with algorithms and results will be shown  especially on  super-resolution  microscopy.

* [Rémi Gribonval](https://people.irisa.fr/Remi.Gribonval/) (INRIA Rennes)  
**Learning from random moments**
*Abstract*: The talk will outline the main features of a recent framework for large‐scale learning called compressive statistical learning. Inspired by compressive sensing, the framework allows drastic volume and dimension reduction to learn from large/distributed/streamed data collections . Its principle is to compute a low‐dimensional (nonlinear) sketch (a vector of random empirical generalized moments), in essentially one pass on the training collection. For certain learning problems, small sketches have been shown to capture the information relevant to the considered learning task, and empirical learning algorithms have been proposed to learn from such sketches. As a proof of concept, more than a thousand hours of speech recordings can be distilled to a sketch of only a few kilo‐bytes, while capturing enough information to estimate a Gaussian Mixture Model for speaker verification. The framework, which is endowed with statistical guarantees in terms of learning error, will be illustrated on sketched clustering and sketched PCA, using empirical algorithms inspired by sparse recovery algorithms used in compressive sensing. Finally, we will discuss the potential of the framework for privacy-aware learning, and its connections with information preservation along pooling layers of certain convolutional neural networks.
