# Lab 1 - Task 3: Fractals (Barnsley Fern)

This repository contains my implementation of the Barnsley fern fractal 
for COMP3710 Lab 1, Task 3.

---

## Code Overview
- `fern.py` generates the fern using an Iterated Function System (IFS).
- Four transformation rules define the stem, main body, and side leaflets.
- A random rule is chosen at each iteration based on its probability.
- Points are plotted using Matplotlib to display the fractal fern.

---

## AI Assistance
I used ChatGPT to help me understand concepts and debug some code.  
For example, I asked:
> *“Write PyTorch code for the Barnsley fern fractal with comments.”*

It suggested a version with GPU support, but since Colab was on CPU 
I adapted the code by forcing `device="cpu"`.  
I also asked about best practices for probability selection and plotting.

All final code was reviewed and edited by me.  
I added my own comments in a style that makes sense to me, 
so I can present confidently in the demo.

---

## Learning Outcome
This task helped me understand:
- Iterated Function Systems (IFS)
- Affine transformations and probabilities in fractals
- How randomness plus rules can generate structured natural shapes
- How to responsibly use AI for coding: take inspiration but still 
  understand and adapt everything

---

## Running the Code
```bash
python fern.py
