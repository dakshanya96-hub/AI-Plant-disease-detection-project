### AI-Plant-disease-detection-project

Tomato Disease Detection 🍅

# About My Project

I created this project as a beginner to learn how AI can be used to identify plant diseases from leaf images. I used Python and TensorFlow to build a CNN model that can classify tomato leaves into four categories.
I also wanted to make my project easy to use, so I used Gradio to create an app where we can upload a tomato leaf image and see what disease the model predicts. And I used AI tools to help me understand concepts and debug errors while developing this project. I tested the code and learned how the different parts work.

# What My Project Can Do

My model can identify these four categories:

- Tomato Healthy
- Tomato Early Blight
- Tomato Late Blight
- Tomato Leaf Mold

# Tools I Used

- Google colab
- Python
- TensorFlow and Keras
- NumPy
- Matplotlib
- Pillow
- Gradio
- Plant village dataset from Github


# How I Built It

First, I used the PlantVillage dataset and selected four tomato leaf categories. Then, I resized the images to 180 × 180 pixels and used data augmentation to create variations of the training images.

After that, I built a CNN model using TensorFlow and trained it to recognize the different categories. I checked its training and validation accuracy to understand how well it was learning.

Finally, I used Gradio to make an app where users can upload a leaf image and see the predicted category.

# My Learning

While building this project, I learned how image classification works, how CNN models learn from images, and how to train and evaluate a model using TensorFlow. I also learned how Gradio can be used to turn a trained model into an interactive app.

# Limitations

This project only recognizes four tomato leaf categories. Its predictions may not always be correct, especially for images that are different from the training dataset.

# Future Improvements

I would like to improve the model's performance, test it with more real-world leaf images, and add more plant disease categories in the future.

# Dataset

"PlantVillage Dataset on GitHub" (https://github.com/spMohanty/PlantVillage-Dataset)
