# Possion_Image_Editing

Poisson image editing is a method of seamless cloning. The core of Poisson image editing is to modify the gradients of an image and then recover the modified image from the new gradients by solving the optimisation problem with Poisson's equations. This repository is an implementation of this paper: https://www.cs.jhu.edu/~misha/Fall07/Papers/Perez03.pdf

## Results

### Solving Euler-Lagrange equation with Dirichlet boundary conditions

- Result in a high-frequency region
<img src="https://github.com/Lixiyao-meow/Possion_Image_Editing/blob/main/results/1_hf_solution.png" width="960">

- Result is a smooth region
<img src="https://github.com/Lixiyao-meow/Possion_Image_Editing/blob/main/results/1_smooth_solution.png" width="640">

### Seamless cloning

- Importing gradients
<img src="https://github.com/Lixiyao-meow/Possion_Image_Editing/blob/main/results/2_Importing_gradients.png" width="300">

- Mixing gradients
<img src="https://github.com/Lixiyao-meow/Possion_Image_Editing/blob/main/results/2_mixing_gradients.png" width="640">

### Seamless cloning for color image
<img src="https://github.com/Lixiyao-meow/Possion_Image_Editing/blob/main/results/3_rgb.png" width="300">

### Application: Texture flattening
<img src="https://github.com/Lixiyao-meow/Possion_Image_Editing/blob/main/results/4_texture_flattening.png" width="560">
