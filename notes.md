# Notes

<!-- mtoc-start -->

* [Connecting supervised and unsupervised learning](#connecting-supervised-and-unsupervised-learning)
* [Appendix](#appendix)
  * [Mathematics](#mathematics)

<!-- mtoc-end -->

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
