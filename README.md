->Neural Style Transfer using PyTorch
This project demonstrates a simple implementation of Neural Style Transfer using a pre-trained VGG19 model in PyTorch.  
It combines the content of one image and the style of another image to create a new, stylized result.
->Overview
Neural Style Transfer is a computer vision technique that applies the artistic style of one image (like a painting) to the content of another image (like a photo).  
It works by minimizing two losses:
1. Content Loss – keeps the target image similar to the content image.
2. Style Loss – makes the target image adopt the style (texture and colors) of the style image.
->Key Steps in the Code
1. Import Libraries – PyTorch, PIL, and Matplotlib.
2. Load and Preprocess Images– resize, convert to tensors, normalize for the network.
3. Load Pre-trained Model – use VGG19 convolutional layers for feature extraction.
4. Extract Features – get content and style features; compute Gram Matrix for style representation.
5. Define Loss and Optimizer – calculate content and style loss; optimize the target image using Adam.
6. Training Loop – update the target image for multiple iterations, printing total loss periodically.
7. Display Result – show the final stylized image with Matplotlib.
->Technologies Used
- Python
- PyTorch
- Torchvision
- PIL
- Matplotlib
-> How to Run
1. Open the notebook in Google Colab or a local Python environment.
2. Install required libraries if not already installed.
3. Replace the content and style image paths with your own.
4. Run the code cells sequentially to generate the stylized image.
