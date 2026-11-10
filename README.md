# IITM_GenAI

A collection of Jupyter notebooks, course notes, and visualizations covering generative AI and related topics. This repository is associated with IITM’s Mathematical Foundations for Generative AI course and includes practical explorations of classic and modern generative modeling techniques.

## Contents

This repository covers:

- Generative Adversarial Networks (GANs)
- Variational Autoencoders (VAEs)
- Diffusion models
- Conditional and advanced GAN variants
- U-Net and attention-based architectures
- Noise estimation, sampling, and denoising workflows
- Course notes and visual explanations

## Repository structure

```text
IITM_GenAI/
├── IITM_DGM_Vanilla_GAN.ipynb
├── IITM_DGM_Conditional_GAN.ipynb
├── IITM_DGM_Bi_GAN.ipynb
├── IITM_DGM_DC_GAN.ipynb
├── IIT_DGM_WGAN.ipynb
├── IITM_DGM_Beta_VAE.ipynb
├── IITM_DGM_VQ_VAE.ipynb
├── IITM_DGM_UNET.ipynb
├── IITM_DGM_DDPM.ipynb
├── IITM_DGM_DDPM_Mean_estimate.ipynb
├── IITM_DGM_DDPM_Noise_Estimate.ipynb
├── IITM_DGM_DDPM_Sample_estimate.ipynb
├── IITM_DGM_DDPM_Score_Estimate.ipynb
├── IITM_DGM_DDPM_Guided_Diffusion.ipynb
├── IITM_DGM_DDIM.ipynb
├── IITM_DGM_MHA.ipynb
├── IITM_DGM_Gen_AI_Demo.ipynb
├── IIT_DGM_UDA.ipynb
├── Notes/
├── Notes_Part1_GAN-1.pdf
├── Notes_Part2_GAN-2.pdf
├── Notes_Part3_GAN-3.pdf
├── Notes_Part4_VAE-1.pdf
├── Notes_Part5_VAE-2.pdf
├── Notes_Part6_Diffusion_model-1.pdf
├── Notes_Part7_Diffussion_models-2.pdf
├── Notes_Part8_DDIMs.pdf
├── Notes_Part9_AR_Models.pdf
├── gan_training.gif
├── vae_training.gif
├── wgan_gp_training.gif
├── ddpm_forward_noising_medium.gif
├── ddpm_reverse_denoising_medium.gif
├── ddpm_training_convergence.gif
└── README.md
```

## Topics covered

### GANs
- Vanilla GAN
- Conditional GAN
- BiGAN
- DCGAN
- WGAN

### VAEs
- Beta-VAE
- VQ-VAE

### Diffusion models
- DDPM
- Noise estimation
- Mean estimation
- Sample estimation
- Score estimation
- Guided diffusion
- DDIM

### Other models and topics
- U-Net
- Multi-head attention
- Unsupervised domain adaptation
- Generative AI demo

## Course notes

The repository includes lecture-style notes in PDF format as well as a `Notes/` directory. These materials complement the notebooks and provide additional conceptual background.

Examples:
- `Notes_Part1_GAN-1.pdf`
- `Notes_Part2_GAN-2.pdf`
- `Notes_Part4_VAE-1.pdf`
- `Notes_Part6_Diffusion_model-1.pdf`
- `Notes_Part8_DDIMs.pdf`

## Visualizations

The repository also includes animated GIF files showing model behavior and training evolution:

- `gan_training.gif`
- `vae_training.gif`
- `wgan_gp_training.gif`
- `ddpm_forward_noising_medium.gif`
- `ddpm_reverse_denoising_medium.gif`
- `ddpm_training_convergence.gif`

## Getting started

Clone the repository and open the notebook you want to study:

```bash
git clone https://github.com/Chandan-IISc/IITM_GenAI.git
cd IITM_GenAI
```

Then open the relevant notebook in Jupyter Notebook or JupyterLab:

```bash
jupyter lab
```

or

```bash
jupyter notebook
```

You may need to install additional Python libraries depending on the notebook, such as:
- PyTorch
- NumPy
- Matplotlib
- Pandas
- tqdm
- torchvision

## Notes

This repository is primarily educational and research-oriented. Some notebooks may require GPU resources and longer runtime depending on model complexity and data size.

## License

No explicit license file is currently present in the repository. Please check the repository before reusing or redistributing the materials.

## Repository

https://github.com/Chandan-IISc/IITM_GenAI
