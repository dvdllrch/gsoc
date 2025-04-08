#  Title 
Tools for Quantum State Distinguishability and Exclusion

## Abstract

My project focuses on enhancing the is_separable function in the toqito library, starting with constructive checks for the separability of low-rank density matrices. In addition to strengthening separability detection, I plan to implement a new feature for the computation of k-incoherence, a property closely related to k-entanglement, which has applications in quantifying coherence and entanglement hierarchies. This will open up new avenues for analyzing quantum resources within the framework. My work will support broader state discrimination and exclusion tasks, particularly under separable measurement constraints. Over time, I also aim to extend functionality to non-bipartite systems, making the tools more general and powerful.

## Technical Details

Regarding the separability of low-rank density matrices: this refers to the implementation of the paper "Operational criterion and constructive checks for the separability of low-rank density matrices." by P. Horodecki et al. Giving sufficient criteria for PPT states when RANK(rho)+RANK(rho^TA) ≤ 2M N − M − N + 2.

Regarding the k-incoherence: This would be implementation of https://arxiv.org/pdf/2205.05110 and https://arxiv.org/abs/2311.17047. 

## Schedule of Deliverables

Here should come a list of your milestones. This list is a start based on the
difference phases of GSoC. Use it as a start. You can/should add more details
for each phase by breaking it down into weeks or set specific targets for each
phase. Each target should be split into sub task with a time estimate, [work
breakdown structures][wbs] are helpful here.

### **Community Bonding Period**

This phase is to get to know the community better. Check that your build
environment is setup. This time should also be used to discuss your project in
more detail with the community and in general introduce it. 

*Note:* We require you to write regular blog posts. Now is a good time to make
sure your blog works and send us the link.

### **Phase 1**

Implement k-incoherence.

### **Phase 2**

Implement separability of of low-ranks.

### **Phase 3**

Add more functions of QETLAB and extend functionality to non-bipartite systems.

### **Final Week**

At this stage you should finish up your project. At this stage you should make
sure that you have code submitted to your organization. Our criteria to mark
your project as a success is to submit code before the end of GSoC.

## Development Experience

Do you have code on github? Can you show previous contributions to other projects?
Did you do other code related projects or university courses?

## Other Experiences
I study Quantum Information Science in Copenhagen. I have won 2 Quantum Hackthon (out of the two I have participated in if I may say). I'm currently working together with Anna Sanpera to publish our work on a "Two-dimensional electro-mechanical Quantum Dot Quantum Simulator"

## Why this project?

Ever since I was confronted with the separability problem in Anna's group I've been fascinated by it and decided to do my master because of it.

## Appendix

Extra content

[wbs]: https://en.wikipedia.org/wiki/Work_breakdown_structure
