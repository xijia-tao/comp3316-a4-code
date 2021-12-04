# COMP3316 Assignment 4: Quantum Fourier Transform

This repository contains code for our group assignment in the course COMP3316 (Quantum Information and Computation) @HKU.  We ([Jiayu](https://github.com/vega-arclight) and I) designed a lecture in quantum fourier transform, introducing its theoretical foundation and one of the most prominent applications, namely the quantum phase estimation algorithm.

✔️ Download our lecture notes [here](https://wwwcielwww.github.io/files/comp3316_gp.pdf).

## Usage
You can choose to view the code in the format of jupyter notebooks `.ipynb` directly on the GitHub website. But because GitHub does not support LaTeX rendering, you might find the markdown sections of the code rather difficult to read.

Alternatively, you can (clone the repository then) view the notebooks in Google Colab, which naturally supports the `.ipynb` format. If you've installed Anaconda, VS code or other editors in your local computer, you might be able to open the notebooks with them as well.

- `qft.ipynb`: demonstrate how quantum fourier transform works with examples visually;
- `phase_est.ipynb`: demonstrate how the phase estimation algorithm works and its accuracy visually.


## Motivation
Throughout the last decades, classical Fourier transform has gained widespread popularity in areas ranging from analysis of differential equations to signal processing. In the quantum computing, a quantum version of the transform was also devised, playing a key role in numerous quantum algorithms, including but not limited to Shor's algorithm for factoring, algorithms for the hidden subgroup problem and phase estimation. 

In this lecture, we'll explore the theory behind quantum Fourier transform as well as its circuit implementation. As a motivating example, we will look into the phase estimation algorithm where the transform is applied. 

## Questions that I wish to address later
Classical Fourier transform has many real-world applications other than those in solving maths / theoretical computer science problems, like image processing, where image is decomposed into its sine and cosine components. The output of the transformation represents the image in the Fourier or frequency domain, while the input image is the spatial domain equivalent. A natural question followed is that, what are the quantum analogue of these application tasks? This question should be equivalent to, what are the implications when we transform a state from a basis to another? 

Considering from a different perspective, instead of using quantum techniques to solve quantum problems, can we use quantum techniques to directly solve classical problems? If that's possible, how should we formulate the classical problems in the language of qubits? But would that really be better than solving a new (but somehow equivalent) quantum problem at the very beginning? Is there a general answer to all these questions?