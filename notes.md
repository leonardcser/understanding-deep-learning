# Notes

<!-- mtoc-start -->

* [Terminology](#terminology)
  * [Vocabulary](#vocabulary)
  * [Supervised learning](#supervised-learning)
* [Connecting supervised and unsupervised learning](#connecting-supervised-and-unsupervised-learning)
* [Appendix](#appendix)
  * [Mathematics](#mathematics)

<!-- mtoc-end -->

## Terminology

### Vocabulary

- **Discriminative model**: they make output predictions from real-world
  measurements

### Supervised learning

- Inputs and outputs respectively: $\mathbf{x}, \mathbf{y}$
- Training dataset: $\{\mathbf{x}_1, \mathbf{x}_2\}$
- Discriminative model: $\mathbf{y}=\mathbf{f}[\mathbf{x}, \boldsymbol{\phi}]$
- Generative model: $\mathbf{x}=\mathbf{g}[\mathbf{y}, \boldsymbol{\phi}]$
- Loss function minimization:
  $\hat{\boldsymbol{\phi}}=\underset{\boldsymbol{\phi}}{\operatorname{argmin}}[L[\{\mathbf{x}_1, \mathbf{x}_2\}, \boldsymbol{\phi}]]$

> [!NOTE]
> It is common to use $L[\boldsymbol{\phi}]$ instead of
> $L[\{\mathbf{x}_1, \mathbf{x}_2\}, \boldsymbol{\phi}]$

## Connecting supervised and unsupervised learning

As an example, instead of mapping the text input to an image, we create a latent
representations for both the text and the image. We then map the two
representations together.

- We may need fewer examples since the mappings are lower dimensional
- We are more likely to generate plausible images as any sensible values of the
  latent representation should produce something plausible
- We introduce randomness to either the mapping between the two sets of latent
  variables or the mapping from the latent variables to the image, and then
  generate multiple images

## Appendix

### Mathematics
