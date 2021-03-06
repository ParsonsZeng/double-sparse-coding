## A Provable Approach for Double-Sparse Coding, AAAI-2018

The arXiv paper is on https://arxiv.org/abs/1711.03638

### Goal
Learn to recover the sparse dictionary $A^*$ from samples $y$ generated by a generative model $y = A^*x + \varepsilon$.

### Data and simulation setting
* Deterministic, sparse, orthonormal dictionary
$A^*$
* Sparse, random and overcomplete dictionary

### Required Matlab packages and/or libraries:
+ gaimc for the bipartite_matchings algorithm
+ To compare our algorithm with Trainlets, you need to download [Trainlets (OSDL) code](http://jsulam.cswp.cs.technion.ac.il/home/software/) and put it inside this folder. Note that some libs (mtimesx, omps and so on) are required to run this program.

### How to run
Set the running mode for algorithm you want to test and run `run_simulation.m`.


## Contact
[Thanh Nguyen](thanhng at iastate dot edu)
