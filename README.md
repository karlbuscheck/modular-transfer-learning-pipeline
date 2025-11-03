# Modular Pipeline for Transfer Learning With Pretrained Computer Vision Models

In this project, we build a modular deep learning pipeline for transfer learning with pretrained computer vision models in [Keras Applications](https://keras.io/api/applications/). This notebook features the workflow for utilizing `VGG16`, a deep convolutional neural network with 16 layers -- [a classic architecture](https://keras.io/api/applications/vgg/) for image recognition tasks. But what makes the pipeline powerful is that it can easily be adapted for any of the commonly used models in Keras.

View the full notebook in Google Colab:

[![Open In Colab](https://colab.research.google.com/drive/1NjZ7cLypzr5ppp150ZH7oU51q0b2MQPN?usp=sharing)

---


### **Project Workflow**

- Load and prepare the data
- Customize and train `VGG16`
- Evaluate the model's performance
- Visualize the predictions
- Deploy the pipeline

---

### **Tools & Libraries Used**

- **Google Colab** — for GPU access and seamless notebook execution
- **Python 3.12.12** — base language for all model building
- **TensorFlow/Keras** — for model building and training
- **NumPy** — for numerical operations and array manipulation
- **Pandas** — for managing and inspecting data structures
- **Matplotlib (PyPlot)** — for visualizing training performance and model predictions

---

### **Acknowledgments**: 

Before diving in, it's important to note that this project was inspired by a lecture notebook in Mohammad Amin Morid's Deep Learning class at the Leavey School of Business at Santa Clara University. Morid is an an Assistant Professor at the school's Information Systems & Analytics department.
