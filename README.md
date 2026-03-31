# AbsVLA: Learning Robust Primitive Manipulation Skills for VLA Models in Object-Centric Abstracted States

Paper under review at **IROS 2026**.

## Abstract
Vision–Language–Action (VLA) models have recently emerged as a promising paradigm for general robotic manipulation.
However, under limited demonstrations, these policies often exhibit brittle behavior and degrade sharply under visual or linguistic distribution shifts.
We propose \textsc{AbsVLA}, a framework that integrates vision--language grounding with VLA policies to learn manipulation skills in an object-centric abstract state space, aiming to better align demonstration and execution distributions.
Concretely, \textsc{AbsVLA} maps language instructions to predefined primitive skills and uses grounding to construct object-centric observations that remove appearance variations while preserving task-relevant spatial structure.
We consider 7 primitive skills spanning \textit{open}, \textit{put}, \textit{push}, and \textit{turn on}, covering 20 LIBERO tasks (Table~\ref{tab:primitive_skill}), and train on 200k step-level samples.
Experiments on LIBERO show that \textsc{AbsVLA} improves robustness to both visual and language perturbations compared to standard VLA baselines, and further enables goal-type transfer from object-specified goals to region-specified targets.
Moreover, we demonstrate zero-shot sim-to-real transfer to a real robot with a different embodiment. A supplementary video demonstrating the experiments is included with the submission.

## PDF
[Download PDF](AbsVLA.pdf)

## Project
- Status: Under review at IROS 2026

## Additional Resources 
- [Video Demo](Demo.mp4)
- [Code Repository](Coming Soon)

## Contact
For questions or requests for the preprint, please contact:
- Maggie Shao: maggiesh@cmu.edu
