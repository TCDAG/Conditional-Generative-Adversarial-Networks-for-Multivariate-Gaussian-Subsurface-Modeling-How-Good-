# Conditional Generative Adversarial Networks for Multivariate Gaussian Subsurface Modeling: How Good They Really Are?
Ahmed Merzouga and Michael Pyrcza,b
a Hildebrand Department of Petroleum and Geosystem Engineering, Cockrell School of Engineering, The University of Texas at Austin, U.S.A
b Department of Earth and Planetary Sciences, Jackson School of Geosciences, The University of Texas at Austin, U.S.A


Abstract
Generative adversarial networks (GANs) are increasingly recognized for their potential in subsurface modeling and uncertainty quantification, thanks to their capability to learn complex geological patterns from spatial training images and their ability to perform rapid local data conditioning in a lower-dimensional latent space compared to the full-dimensional space of the images. However, the performance of these algorithms often receives acceptance based primarily on visual inspection or limited qualitative assessment. To address this, we propose a minimum acceptance criteria workflow designed to quantitatively assess and verify the adequacy of GAN-generated subsurface models. This evaluation is carried out through three key metrics: (1) reproduction of data distribution, (2) reproduction of spatial continuity, and (3) local data conditioning. 
Our proposed workflow applied to GANs trained on a variety of images from sequential Gaussian simulations demonstrates that while data distribution and spatial continuity are consistently well-reproduced, local data conditioning faces several challenges. These include increasing prediction error and the need for more iterations for conditioning as the number of conditioning data increases. Additionally, the conditioning process at these data locations tends to introduce artifacts near the data locations including high local variogram nugget effects. Our minimum acceptance criteria offer a comprehensive framework for evaluating various models ensuring a higher control on modeling quality acceptance and rejection. 
