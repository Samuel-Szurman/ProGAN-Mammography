<h1>Training ProGAN on VinDr-Mammo</h1> 
<h2>Overview</h2>
This project focuses on training a Progressive Growing GAN (ProGAN) on the VinDr-Mammo dataset to generate realistic mammographic images with a resolution of 512x512 pixels. The goal is to create synthetic mammograms that can aid in medical research and model evaluation. 
<h2>About ProGAN</h2>
ProGAN, or Progressive Growing GAN, is a generative adversarial network architecture designed for generating high-resolution images. The training process begins with a low resolution (e.g., 4x4) and progressively increases to higher resolutions (e.g., 512x512) by adding layers to the generator and discriminator. This approach stabilizes the training process and allows for generating more detailed and realistic images compared to traditional GANs.
<h2>Objective</h2>
The key objectives of the project are: 
<ol>
  <li>
    Train the ProGAN Model: Use the VinDr-Mammo dataset to train a Progressive Growing GAN to generate high-quality mammograms. 
  </li> 
<!--   <li> 
    Evaluate Model Performance: Assess the quality of generated mammograms using evaluation metrics such as FID (Fréchet Inception Distance) and visual inspection. 
  </li>  -->
  <li>
    Generate Synthetic Data: Produce synthetic mammographic images at a resolution of 512x512 that mimic the real data distribution.
  </li> 
</ol>
<h2>Examples of Generated Images</h2>
<p align="center">
  <img src="progan_examples.png" alt="Examples of generated images by ProGAN model" width="100%">
</p>
