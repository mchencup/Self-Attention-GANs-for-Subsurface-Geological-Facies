# Self-Attention GANs for Subsurface Geological Facies
Simple implementation for subsurfacie geological facies of ["Self-Attention Generative Adversarial Networks" (SAGAN)](https://arxiv.org/pdf/1805.08318.pdf)


## Requirements
* Tensorflow 1.8
* Python 3.6


## Usage

### dataset
* `https://github.com/SCRFpublic/Stanford-VI-E/tree/master/Facies` are used inside

### train
* python main.py --phase train --dataset TraingImages --gan_type hinge

### test
* python main.py --phase test --dataset TraingImages --gan_type hinge
