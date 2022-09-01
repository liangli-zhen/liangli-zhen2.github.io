---
layout: page
title: research
permalink: /research/
description: My research interests include <i>machine intelligence</i> and <i>evolutionary computation</i>. Currently, I focus on machine learning, multi-objective optimisation, and their applications in real-world systems.
nav: true
nav_order: 2
display_categories: [work, fun]
horizontal: false
---

<strong>machine learning</strong>

Machine learning is the science of getting computers to act without being explicitly programmed. For a learning system, the experience is the process of analysing the collected data (and providing predictions to interact with the environment). From this perspective, machine learning is learning from the data. Prof. Tom M. Mitchell provided a widely quoted definition of learning$$^1$$.

<i>Definition: A computer program is said to learn from experience $$\mathcal{E}$$ with respect to some class of tasks $$\mathcal{T}$$and performance measure $$\mathcal{P}$$, if its performance at tasks in $$\mathcal{T}$$, as measured by $$\mathcal{P}$$, improves with experience $$\mathcal{E}$$.</i>

<p>
Our work in machine learning includes manifold learning, sparse representation, kernel methods, and deep neural networks.</p>

<i>Manifold learning and subspace analysis</i>
<ul>
<li>[<a href="https://arxiv.org/abs/1705.05108">INS20</a>] A kernel-based method for subspace clustering</li>
<li>[<a href="https://doi.org/10.1016/j.measurement.2019.107268">Measurement20</a>] A method for estimating the mixing matrix of underdetermined systems</li>
<li>[<a href="http://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=7583658">TNNLS17</a>] An application of sparse coding technique</li>
<li>[<a href="http://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&amp;arnumber=8081738">Access17</a>] A method by combining sparsity and independence of source for underdetermined blind source separation</li>
<li>[<a href="http://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=6838846/">EL14</a>] A manifold learning method for image clustering</li>
<li>[<a href="http://www.jsoftware.us/vol8/jsw0802-21.pdf">JSW13</a>] A manifold learning method for dimension reduction</li>
</ul>

<i>Multimodal learning</i>
<ul>
<li>[SIGIR21] A multimodal learning method for natural language video localisation</li>
<li>[TPAMI21] A multimodal learning method for video moment retrieval</li>
<li>[TNNLS20] A multimodal transfer learning method</li>
<li>[TCYB20] A multi-view hashing method</li>
<li>[<a href="https://liangli-zhen.github.io/papers/CVPR2019_Deep_Supervised_Cross_modal_Retrieval.pdf">CVPR19</a>] A deep supervised cross-modal retrieval method</li>
<li>[<a href="https://liangli-zhen.github.io/papers/SIGIR2019_Scalable_Deep_Multimodal_Learning_for_Cross-Modal_Retrieval.pdf">SIGIR19</a>] A scalable deep multimodal learning method for cross-modal retrieval</li>
<li>[<a href="https://liangli-zhen.github.io/papers/SVHN.pdf">MM19</a>] A separated variational hashing method for cross-modal retrieval</li>
<li>[<a href="https://www.sciencedirect.com/science/article/pii/S0950705118300595">KBS18</a>] A local feature-based method for multi-view analysis</li>
</ul>

<i>Safe and robust machine learning</i>
<ul>
<li>[MedIA22] An adversarial multimodal learning method for automated skin lesion classification</li>
<li>[ICLR22] A robust optimisation method for deep neural networks</li>
<li>[CVPR21] A robust learning method for handling noisy labels</li>
<li>[TBD22] A secure multi-party learning method for federated learning</li>
</ul>

<sup id="fn1">1. Machine Learning, Tom Mitchell, McGraw Hill, 1997.</sup><br><br>


<strong>multi-objective optimisation</strong>


Multi-objective optimisation, which addresses optimisation problems involving multiple (conflicting) objective functions to be optimized simultaneously, has attracted increasing interest in the evolutionary computation community. A multi-objective optimisation problem (MOP) can be generally 
formulated as follows:

$$
  \begin{aligned} 
  \min\limits_{\mathbf{x}} ~~& \mathbf{f}(\mathbf{x}) = (f_1(\mathbf{x}), f_2(\mathbf{x}), ..., f_m(\mathbf{x}) ), \\ 
  \text{s.t.}  ~~ & \mathbf{x} \in \Omega,\\ 
  & g_i(\mathbf{x}) \le 0, i = 1,..., p, \\  
  & h_j(\mathbf{x}) = 0, j = 1,..., q,  
  \end{aligned} 
$$

where $$\mathbf{x} = (x_1, x_2, \dots, x_d) \in \Omega$$ is the decision vector; $$\mathbf{f} \in \Re^m$$ is the objective vector. The decision vector $$\mathbf{x}$$ is composed of $$d$$ decision variables and the objective vector $$\mathbf{f}$$ is composed of $$m$$ objective functions, and the objective function $$f_i(\mathbf{x})$$ maps $$\mathbf{x}$$ from $$\Omega$$ to a scaler. $$g_i(\mathbf{x})$$ and $$h_j(\mathbf{x})$$ are known as the inequality and equality constraints, respectively.
	
If a MOP has more than three objectives, it is called a <em>many-objective optimisation problem</em> (MaOP). Our work in many-objective optimisation includes the design of many-objective evolutionary algorithms, test problem construction, and visualisation.</p>

<i>Multi-objective optimisation in deep learning</i>
<ul>	
<li>[<a href="https://ieeexplore.ieee.org/abstract/document/9492169/">CIM21</a>] An evolutionary multiobjective model compression method for deep neural networks</li>
</ul>
	
<i>Test problems for many-objective optimisation</i>
<ul>
<li>[<a href="https://arxiv.org/abs/1806.02706">ArVix22</a>] A benchmark for multiobjective optimisation</li>
</ul>

<i>Visualisation for many-objective optimisation</i>
<ul>
<li>[<a href="https://authors.elsevier.com/c/1aA174ZQDzkdh">INS20</a>] A visualisation method for multiobjective solution sets using objective reduction</li>
<li>[<a href="http://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=8065139">CIM17</a>] A guide on how to read many-objective solution sets in parallel coordinates</li>
<li>[<a href="https://liangli-zhen.github.io/papers/APC.pdf">SEAL17</a>] Adjusting parallel coordinates for more explicit observation of many-objective search</li>
</ul><br>
