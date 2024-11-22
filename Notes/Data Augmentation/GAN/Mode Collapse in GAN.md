Blogpost Link : https://spotintelligence.com/2023/10/11/mode-collapse-in-gans-explained-how-to-detect-it-practical-solutions/#What_is_mode_collapse_in_Generative_Adversarial_Networks_GANs


In the case of GANs, mode collapse can happen when 

the discriminator becomes too good at distinguishing between real and generated samples. 

As a result, the generator may find it easier to produce a limited set of samples 

that can consistently fool the discriminator 

rather than explore the full distribution of the training data.

Example Video: https://youtu.be/TLc6u8jwt7M?si=-_oP0Sjhc5YAhP3i
1.GAN produces good image
2.Discriminator Gets Fooled a number of times
3.That Image is a mode now
4.Discriminator Quickly Tracks it as Fake Next Time its generated
because it is sensitive to small variations

5.Generator switches to another mode
6.Keeps switching between them
7.The training inherently Doesn't stop Mode Collapse