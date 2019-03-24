# FilterReg

[FilterReg](<https://sites.google.com/view/filterreg/home>) is a geometric point-set registration algorithm. By leveraging Gaussian Filter for correspondence search and twist parametrization for kinematic computation, it achieves state-of-the-art robustness and efficiency.

### Video Demo [[Link]](https://youtu.be/k-YQVZfM0qg)

[![FilterReg](./doc/articulated.png)](https://youtu.be/k-YQVZfM0qg)

### Project Page, Paper and Supplemental Document

Project Page: [Link](<https://sites.google.com/view/filterreg/home>)

Paper: [PDF](https://drive.google.com/file/d/1XLCAwkIRqnHFhYMx6hYf8LxN_IeozliZ/view?usp=sharing) [ArXiv](https://arxiv.org/abs/1811.10136)

Supplemental Document: [PDF](https://drive.google.com/file/d/1R_E-v3vh7aq3uwg_EOmZEtItMn649rVI/view?usp=sharing)

### Build Instruction

The code is developed on Ubuntu 16.04. 

### TODO

The code is re-factored from a pretty messy version which is the backbone of all the experiments in our paper. Not all the code has been adapted into this repository and the author is working on it.

- [ ] The GPU implementation of various algorithms
- [ ] Revive the articulated kinematic model using the new MultiBodyTree in drake
- [ ] The deformable kinematic model used in SurfelWarp