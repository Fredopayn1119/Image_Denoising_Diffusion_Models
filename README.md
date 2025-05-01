# Image Denoising Diffusion Models: A School Assignment

The implementation of two types of deep learning models able to denoise images iteratively.

1. **DDPM (Denoising Denoising Probabilistic Model)**
  - Noise is iteratively added to images until they appear indistinguishable from pure Gaussian noise.
  - The model then learns to do the reverse - denoise images until they are legible.
  

2. **DDIM (Denoising Diffusion Implicit Model)**
  - Solves the problem of long training time taken by DDPM from needing thousands of model passes to generate one image.
  - With a quality tradeoff, allows for some of the image denoising steps to be skipped.

## Run Instructions
1. Select the file 'hw3_prob2_diffusion.ipynb'
2. Select 'Download raw file'
3. Go to Google Colab
4. Create a new Google Colaboratory
5. Once created, go to File > Import notebook
6. Import the downloaded file
7. Run each of the cells in the notebook in order
    
## More Details to be Added Here Soon
