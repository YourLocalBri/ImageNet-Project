# ImageNet-Project
# ImageNet Classification on Jetson Nano (jetson-inference)

This is a quick demo project using the `imageNet` model from NVIDIA's `jetson-inference` library to perform image classification on a Jetson Orin Nano. It uses pre-trained ImageNet models to classify images and output the predicted labels.

---

# What is ImageNet?

ImageNet is a large-scale image classification dataset used to train deep learning models to recognize and classify images into thousands of categories. The `jetson-inference` framework includes pre-trained ImageNet models that can classify input images directly on Jetson devices.

---

# Hardware & Tools Used

- NVIDIA Jetson Orin Nano
- JetPack SDK (with TensorRT, CUDA, cuDNN)
- `jetson-inference` library
- Visual Studio Code (optional, for editing)

---

# Dataset Location

The input image(s) used are located in the `jetson-inference/data/images/` folder. You can add more images here for classification testing.

---

# Run Image Classification

### Example Command:

```bash
imagenet /home/nvidia6/jetson-inference/data/images/humans_9.jpg /home/nvidia6/jetson-inference/data/images/output10.jpg
