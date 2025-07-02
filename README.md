# SRGAN_enhance_images
Upscaling low resolution images up to 4 times using SRGAN technique

So far, we have used patching method on the images as they are of different dimensions and to reduce the load on GPU.
We extract random patches and then feed them to the models.
We are using SRGAN-lite for enhancing the images by 4x times.

### Tools used:
  - Dataset : DIV2K
  - jupyter-notebook
  - wsl2
  - GPU (nvidia Geforce RTX 4060)
  - libraries : requirements.txt
