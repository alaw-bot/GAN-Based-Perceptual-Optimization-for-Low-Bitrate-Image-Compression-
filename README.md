# GAN-Based-Perceptual-Optimization-for-Low-Bitrate-Image-Compression-
Individual Research
🔥 GAN-Based Image Compression with Saliency-Aware Bit Allocation
This project implements a GAN-based image compression system that leverages MobileNetV2-based saliency maps to prioritize perceptually important regions. The architecture uses an encoder generator discriminator setup and compresses images into a compact latent representation with intelligent, saliency-weighted bit allocation.

🧠 Key Features
✅ End-to-End Image Compression using deep convolutional encoder and decoder (generator)

✅ GAN Training with PatchGAN discriminator for realistic reconstructions

✅ Saliency-Aware Compression: Uses MobileNetV2 to compute saliency maps, guiding attention and bit allocation

✅ Perceptual Loss: Uses VGG19 for perceptual quality enhancement

✅ Binary Compression: Stores latent vectors as binary .npy files

✅ Colab Friendly: One-click run on Google Colab with minimal setup

📸 Architecture
<img width="577" height="446" alt="image" src="https://github.com/user-attachments/assets/2bfdaa99-f46c-47a4-a8fc-51c12fce1759" />



🧪 Datasets
Kodak Image Dataset
CLIC (optional for large-scale training)

📌 Goals
Improve perceptual quality at very low bitrates
Explore adaptive bitrate allocation using learned saliency
Enable real-time decoding for edge applications




