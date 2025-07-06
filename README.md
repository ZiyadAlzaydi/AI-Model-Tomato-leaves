# AI-Model-Tomato-leaves
This project is an AI-powered image classification model developed using Teachable Machine by Google. The model is trained to detect and classify tomato leaf conditions into four categories.
![2025-07-07](https://github.com/user-attachments/assets/c73c70a1-3cb3-4fdb-93f6-13f99e2bf1b9)

Classification Categories:
Healthy –
Leaves without any signs of disease, showing uniform green color and natural texture.

Late Blight –
Characterized by large, dark, greasy-looking spots with yellow halos, often caused by Phytophthora infestans.

Early Blight –
Identified by concentric rings in brown spots on older leaves, caused by Alternaria solani.

Bacterial Spot –
Small, water-soaked lesions that enlarge and become dark brown with a yellow halo, caused by Xanthomonas species.

Model Development Using Teachable Machine:
Platform Used: Teachable Machine

Model Type: Image Classification

Input Method: Upload images or use a live webcam

Training Dataset: Images of tomato leaves for each category, collected from plant disease databases or captured using smartphone cameras.

Process:

Four classes were created (Healthy, Late Blight, Early Blight, Bacterial Spot).

50–100 images were uploaded per class for initial training.

The model was trained in-browser using transfer learning with a pre-trained neural network.

Model accuracy and loss were monitored, and retraining was done to improve performance.

Output & Usage:
The trained model can classify new tomato leaf images in real-time.

It is exported as:

A TensorFlow model for use in Python or web applications.

A web link for browser-based testing and deployment.

Applications:
Early and accurate disease detection in tomato plants.

Helps farmers and agricultural experts take timely action.

Useful in smart farming systems or mobile apps for plant health monitoring.

