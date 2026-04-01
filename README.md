# AbsVLA: Learning Robust Primitive Manipulation Skills for VLA Models in Object-Centric Abstracted States

Paper under review at **IROS 2026**.

## Abstract
Vision–Language–Action (VLA) models have recently emerged as a promising paradigm for general robotic manipulation. However, under limited demonstrations, these policies often exhibit brittle behavior and degrade sharply under visual or linguistic distribution shifts. 

We propose **AbsVLA**, a framework that integrates vision–language grounding with VLA policies to learn manipulation skills in an object-centric abstract state space. AbsVLA maps language instructions to predefined primitive skills and constructs object-centric observations that remove irrelevant appearance variations while preserving task-relevant spatial structure.

We consider 7 primitive skills spanning *open*, *put*, *push*, and *turn on*, covering 20 LIBERO tasks, and train on 200k step-level samples. Experiments show that AbsVLA improves robustness to visual and language perturbations compared to standard VLA baselines and enables zero-shot sim-to-real transfer to a real robot with a different embodiment. A supplementary video demonstrating the experiments is included with this repository.

## Paper
[Download PDF](AbsVLA.pdf)

## Project
- Status: Under review at IROS 2026
- [Video Demo](Demo.mp4)
- [Code Repository](Coming Soon)

## Contact
For questions or requests for the preprint, please contact:
- Maggie Shao: maggiesh@andrew.cmu.edu
