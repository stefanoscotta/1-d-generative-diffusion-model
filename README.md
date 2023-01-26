# 1-d generative diffusion model explained

The aim of this notebook is to make more understandable the generative diffusion models explicated in {link to be inserted} showing its properties with a simple 1-d toy model. 

We show how it is built the forward "noising" process which starting from a given distribution $p(x_0)$ converges to a final distribution $p(x_T)$ which is a $\mathcal{N}(0,1)$. 

Then we built some functions needed to estimate the elements caracterizing the reverse process and we estimate the reverse process itself showing how tis distribution evolves in reverse time starting from random elements taken from $p(x_T)$.

Lastly we analyze some interesting properties of this kind of process that are evident in one dimension:
- Conditional probability densities;
- Joint empirical probabilities;
- GMM for modeling joint probabilities...



















