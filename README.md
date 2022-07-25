# 📑 Awesome Graph PDE <a href="https://github.com/cbhua/awesome-graph-pde" target="_blank"><img alt="Awesome List" src="https://img.shields.io/badge/-Awesome_List-fc60a8?&style=flat&logo=Awesome-Lists&logoColor=white"/></a>


A collection of resources about partial differential equations, deep learning, graph neural networks, dynamic system simulation.


We also roughly categorize the resources into the following categories under "contents" - note that this is a work in progress and relies on contributions. Feel free to suggest additions via `Issues` or `Pull Requests`!


## 🗂  Contents

- Graph Neural Network Models

- Physics System Simulation

## 📖 Theory

### Graph Neural Network Models

**Graph Element Networks: adaptive, structured computation and memory**. ICML19. 

<a href="http://arxiv.org/abs/1904.09019" target="_blank"><img alt="link" src="https://img.shields.io/badge/-Link-informational?&style=flat&logoColor=white"/></a> <a href="http://arxiv.org/abs/1904.09019" target="_blank"><img alt="Arxiv" src="https://img.shields.io/badge/-1904.09019-b31b1b?&style=flat&logo=arXiv&logoColor=white"/></a> <a href="http://arxiv.org/abs/1904.09019" target="_blank"><img alt="ICML19" src="https://img.shields.io/badge/ICML-2019-orange?&style=flat&logoColor=white"/></a> <a href="https://github.com/FerranAlet/graph_element_networks" target="_blank"><img alt="Github" src="https://img.shields.io/badge/-Code-black?&style=flat&logo=github&logoColor=white"/></a>

> Traditional applications of GNNs assume an *a priori* notion of entity (such as bodies, links or particles) and match every node in the graph to an entity. We propose to apply GNNs to the problem of modeling transformations of functions defined on continuous spaces, using a structure we call *graph element networks* (GENs). Inspired by finite element methods, we use graph neural networks to mesh a continuous space and define an iterative computation that propagates information from some sampled input values in the space to an output function defined everywhere in the space. 


<br>

**Deep Graph Infomax**. ICLR19. 

<a href="http://arxiv.org/abs/1809.10341" target="_blank"><img alt="link" src="https://img.shields.io/badge/-Link-informational?&style=flat&logoColor=white"/></a> <a href="http://arxiv.org/abs/1809.10341" target="_blank"><img alt="Arxiv" src="https://img.shields.io/badge/-1809.10341-b31b1b?&style=flat&logo=arXiv&logoColor=white"/></a> <a href="http://arxiv.org/abs/1809.10341" target="_blank"><img alt="ICLR21" src="https://img.shields.io/badge/ICLR-2019-brightgreen?&style=flat&logoColor=white"/></a> <a href="https://github.com/PetarV-/DGI" target="_blank"><img alt="Github" src="https://img.shields.io/badge/-Code-black?&style=flat&logo=github&logoColor=white"/></a>


> We present *Deep Graph Infomax* (DGI), a general approach for learning node representations within graph-structured data in an unsupervised manner. DGI re- lies on maximizing mutual information between patch representations and corre- sponding high-level summaries of graphs—both derived using established graph convolutional network architectures. 


<br>

**Multipole Graph Neural Operator for Parametric Partial Differential Equations**. NeurIPS20. 

<a href="http://arxiv.org/abs/2006.09535" target="_blank"><img alt="link" src="https://img.shields.io/badge/-Link-informational?&style=flat&logoColor=white"/></a> <a href="http://arxiv.org/abs/2006.09535" target="_blank"><img alt="Arxiv" src="https://img.shields.io/badge/-2006.09535-b31b1b?&style=flat&logo=arXiv&logoColor=white"/></a> <a href="http://arxiv.org/abs/2006.09535" target="_blank"><img alt="Nips20" src="https://img.shields.io/badge/NeurIPS-2020-blueviolet?&style=flat&logoColor=white"/></a> <a href="https://github.com/zongyi-li/graph-pde" target="_blank"><img alt="Github" src="https://img.shields.io/badge/-Code-black?&style=flat&logo=github&logoColor=white"/></a>

> Inspired by the fast multipole method (FMM), we propose a novel hierarchical, and multi-scale graph structure which, when deployed with GNNs, captures global properties of the PDE solution operator with a linear time-complexity. 

<br>

**Neural Operator: Graph Kernel Network for Partial Differential Equations**. ICLR20. 

<a href="http://arxiv.org/abs/2003.03485" target="_blank"><img alt="link" src="https://img.shields.io/badge/-Link-informational?&style=flat&logoColor=white"/></a> <a href="http://arxiv.org/abs/2003.03485" target="_blank"><img alt="Arxiv" src="https://img.shields.io/badge/-2003.03485-b31b1b?&style=flat&logo=arXiv&logoColor=white"/></a> <a href="http://arxiv.org/abs/2003.03485" target="_blank"><img alt="ICLR20" src="https://img.shields.io/badge/ICLR-2020-brightgreen?&style=flat&logoColor=white"/></a> <a href="https://github.com/zongyi-li/graph-pde" target="_blank"><img alt="Github" src="https://img.shields.io/badge/-Code-black?&style=flat&logo=github&logoColor=white"/></a>

> We introduce the concept of Neural Operator and instantiate it through *graph kernel networks*, a novel deep neural network method to learn the mapping between infinite dimensional spaces of functions defined on bounded open subsets of R^d. Unlike existing methods, our approach is demonstrably able to learn the mapping between function spaces, and is invariant to different approximations and grids. 


<br>

**Continuous Graph Flow**. ICLR20

<a href="http://arxiv.org/abs/1908.02436" target="_blank"><img alt="link" src="https://img.shields.io/badge/-Link-informational?&style=flat&logoColor=white"/></a> <a href="http://arxiv.org/abs/1908.02436" target="_blank"><img alt="Arxiv" src="https://img.shields.io/badge/-1908.02436-b31b1b?&style=flat&logo=arXiv&logoColor=white"/></a> <a href="http://arxiv.org/abs/1908.02436" target="_blank"><img alt="ICLR20" src="https://img.shields.io/badge/ICLR-2020-brightgreen?&style=flat&logoColor=white"/></a>  <a href="https://github.com/Lucas2012/ContinuousGraphFlow" target="_blank"><img alt="Github" src="https://img.shields.io/badge/-Code-black?&style=flat&logo=github&logoColor=white"/></a>

> In this paper, we introduce a new class of models – *Continuous Graph Flow* (CGF): a graph gener- ative model based on continuous normalizing flows that generalizes the message passing mechanism in GNNs to continuous time. Specifically, to model continuous time dynamics of the graph variables, we adopt a neural ordinary different equation (ODE) formulation.


<br>

**GRAND: Graph Neural Diffusion**. ICML21

<a href="https://arxiv.org/abs/2106.10934" target="_blank"><img alt="link" src="https://img.shields.io/badge/-Link-informational?&style=flat&logoColor=white"/></a> <a href="https://arxiv.org/abs/2106.10934" target="_blank"><img alt="Arxiv" src="https://img.shields.io/badge/-2106.10934-b31b1b?&style=flat&logo=arXiv&logoColor=white"/></a> <a href="https://arxiv.org/abs/2106.10934" target="_blank"><img alt="ICML21" src="https://img.shields.io/badge/ICML-2021-orange?&style=flat&logoColor=white"/></a>  <a href="https://github.com/twitter-research/graph-neural-pde" target="_blank"><img alt="Github" src="https://img.shields.io/badge/-Code-black?&style=flat&logo=github&logoColor=white"/></a>

> We present Graph Neural Diffusion (GRAND) that approaches deep learning on graphs as a continuous diffusion process and treats Graph Neural Networks (GNNs) as discretisations of an underlying PDE. In our model, the layer structure and topology correspond to the discretisation choices of temporal and spatial operators. Our approach allows a principled development of a broad new class of GNNs that are able to address the common plights of graph learning models such as depth, oversmoothing, and bottlenecks. Key to the success of our models are stability with respect to perturbations in the data and this is addressed for both implicit and explicit discretisation schemes. We develop linear and nonlinear versions of GRAND, which achieve competitive results on many standard graph benchmarks.


<br>

**Beltrami Flow and Neural Diffusion on Graphs**. NeurIPS21

<a href="https://arxiv.org/abs/2110.09443" target="_blank"><img alt="link" src="https://img.shields.io/badge/-Link-informational?&style=flat&logoColor=white"/></a> <a href="https://arxiv.org/abs/2110.09443" target="_blank"><img alt="Arxiv" src="https://img.shields.io/badge/-2110.09443-b31b1b?&style=flat&logo=arXiv&logoColor=white"/></a> <a href="https://arxiv.org/abs/2110.09443" target="_blank"><img alt="NIPS21" src="https://img.shields.io/badge/NeurIPS-2022-blueviolet?&style=flat&logoColor=white"/></a>  <a href="https://github.com/twitter-research/graph-neural-pde" target="_blank"><img alt="Github" src="https://img.shields.io/badge/-Code-black?&style=flat&logo=github&logoColor=white"/></a>

> We propose a novel class of graph neural networks based on the discretised Beltrami flow, a non-Euclidean diffusion PDE. In our model, node features are supplemented with positional encodings derived from the graph topology and jointly evolved by the Beltrami flow, producing simultaneously continuous feature learning and topology evolution. The resulting model generalises many popular graph neural networks and achieves state-of-the-art results on several benchmarks.

<br>

### Physics System Simulation

**Combining Differentiable PDE Solvers and Graph Neural Networks for Fluid Flow Prediction**. ICML20. 

<a href="http://arxiv.org/abs/2007.04439" target="_blank"><img alt="link" src="https://img.shields.io/badge/-Link-informational?&style=flat&logoColor=white"/></a> <a href="http://arxiv.org/abs/2007.04439" target="_blank"><img alt="Arxiv" src="https://img.shields.io/badge/-2007.04439-b31b1b?&style=flat&logo=arXiv&logoColor=white"/></a> <a href="http://arxiv.org/abs/2007.04439" target="_blank"><img alt="ICML20" src="https://img.shields.io/badge/ICML-2020-orange?&style=flat&logoColor=white"/></a> <a href="https://github.com/locuslab/cfd-gcn" target="_blank"><img alt="Github" src="https://img.shields.io/badge/-Code-black?&style=flat&logo=github&logoColor=white"/></a>


> In this paper, we explore a hybrid approach that combines the benefits of (graph) neural networks for fast predictions, with the physical realism of an industry-grade CFD simulator.


<br>

**Learning to Simulate Complex Physics with Graph Networks**. ICML20. 

<a href="http://arxiv.org/abs/2002.09405" target="_blank"><img alt="link" src="https://img.shields.io/badge/-Link-informational?&style=flat&logoColor=white"/></a> <a href="http://arxiv.org/abs/2002.09405" target="_blank"><img alt="Arxiv" src="https://img.shields.io/badge/-2002.09405-b31b1b?&style=flat&logo=arXiv&logoColor=white"/></a> <a href="http://arxiv.org/abs/2002.09405" target="_blank"><img alt="ICML20" src="https://img.shields.io/badge/ICML-2020-orange?&style=flat&logoColor=white"/></a> <a href="https://github.com/deepmind/deepmind-research/tree/master/learning_to_simulate" target="_blank"><img alt="Github" src="https://img.shields.io/badge/-Code-black?&style=flat&logo=github&logoColor=white"/></a>

> We present a powerful machine learning framework for learning to simulate complex systems from data “Graph Network-based Simulators” (GNS). Our framework imposes strong inductive biases, where rich physical states are represented by graphs of interacting particles, and complex dynamics are approximated by learned message-passing among nodes. 


<br>

**Learning Mesh-Based Simulation with Graph Networks**. ICLR21. 

<a href="http://arxiv.org/abs/2010.03409" target="_blank"><img alt="link" src="https://img.shields.io/badge/-Link-informational?&style=flat&logoColor=white"/></a> <a href="http://arxiv.org/abs/2010.03409" target="_blank"><img alt="Arxiv" src="https://img.shields.io/badge/-2010.03409-b31b1b?&style=flat&logo=arXiv&logoColor=white"/></a> <a href="http://arxiv.org/abs/2010.03409" target="_blank"><img alt="ICLR21" src="https://img.shields.io/badge/ICLR-2021-brightgreen?&style=flat&logoColor=white"/></a> <a href="https://github.com/deepmind/deepmind-research/tree/master/meshgraphnets" target="_blank"><img alt="Github" src="https://img.shields.io/badge/-Code-black?&style=flat&logo=github&logoColor=white"/></a>

> We introduce a method for predicting dynamics of physical systems, which capitalizes on the advantages of adaptive mesh representations. Our method works by encoding the simulation state into a graph, and performing computations in two separate spaces: the mesh-space, spanned by the simulation mesh, and the Euclidean world-space in which the simulation manifold is embedded. By passing messages in mesh-space, we can approximate differential operators that underpin the internal dynamics of most physical systems. 


<br>

**Learning continuous-time PDEs from sparse data with graph neural networks**. ICLR21. 

<a href="http://arxiv.org/abs/2006.08956" target="_blank"><img alt="link" src="https://img.shields.io/badge/-Link-informational?&style=flat&logoColor=white"/></a> <a href="http://arxiv.org/abs/2006.08956" target="_blank"><img alt="Arxiv" src="https://img.shields.io/badge/-2006.08956-b31b1b?&style=flat&logo=arXiv&logoColor=white"/></a> <a href="http://arxiv.org/abs/2006.08956" target="_blank"><img alt="ICLR21" src="https://img.shields.io/badge/ICLR-2021-brightgreen?&style=flat&logoColor=white"/></a> <a href="https://github.com/yakovlev31/graphpdes_experiments" target="_blank"><img alt="Github" src="https://img.shields.io/badge/-Code-black?&style=flat&logo=github&logoColor=white"/></a>


> In this paper we propose to learn free-form, continuous-time, a priori fully unknown PDE model F from sparse data measured on arbitrary timepoints and locations of the coordinate domain Ω with graph neural networks (GNN).


<br>

**Learning the Dynamics of Physical Systems from Sparse Observations with Finite Element Networks**. ICLR22

<a href="https://arxiv.org/abs/2203.08852" target="_blank"><img alt="link" src="https://img.shields.io/badge/-Link-informational?&style=flat&logoColor=white"/></a> <a href="https://arxiv.org/abs/2203.08852" target="_blank"><img alt="Arxiv" src="https://img.shields.io/badge/-2203.08852-b31b1b?&style=flat&logo=arXiv&logoColor=white"/></a> <a href="https://arxiv.org/abs/2203.08852" target="_blank"><img alt="ICLR22" src="https://img.shields.io/badge/ICLR-2022-brightgreen?&style=flat&logoColor=white"/></a>  <a href="https://github.com/martenlienen/finite-element-networks" target="_blank"><img alt="Github" src="https://img.shields.io/badge/-Code-black?&style=flat&logo=github&logoColor=white"/></a>

> We propose a novel class of graph neural networks based on the discretised Beltrami flow, a non-Euclidean diffusion PDE. In our model, node features are supplemented with positional encodings derived from the graph topology and jointly evolved by the Beltrami flow, producing simultaneously continuous feature learning and topology evolution. The resulting model generalises many popular graph neural networks and achieves state-of-the-art results on several benchmarks.


## 📬 Feedback

If you have some ideas or any other suggestions, just feel free to rise via `Issues` or `Pull Requests`. 

## 📜 License

<a href="https://github.com/cbhua/awesome-graph-pde" target="_blank"><img alt="awesome-graph-pde" src="https://img.shields.io/badge/License-MIT-brightgreen?&style=flat&logoColor=white"/></a>