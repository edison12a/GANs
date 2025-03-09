# **CycleGAN Monet Painting Generator**

## _You see, I’m Something of a Painter Myself_


This project trains a **CycleGAN** to convert real-world photos into **Monet-style paintings** using the **Kaggle "GAN Getting Started" dataset**.

## **Pipeline**
1. **Data Preprocessing** – Load, normalize, and batch images.
2. **Model Architecture** – CycleGAN with:
   - **Generator**: Photo → Monet
   - **Discriminator**: Monet vs. Fake Monet
3. **Training** – Adversarial & cycle-consistency losses.
4. **Results** – Generate Monet-style images from real photos.

## **Usage**
- Run `cycleGAN_monet_project_fixed.ipynb` in Jupyter Notebook.
- Generates Monet-style images and saves them in `/images/`.

## **Future Improvements**
- Longer training for better details.
- Improved hyperparameter tuning.
- Perceptual loss for texture enhancement.
