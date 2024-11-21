# Neural Style Transfer

Neural Style Transfer is a fascinating deep learning technique that allows you to blend the **content structure** of one image with the **artistic style** of another to create a unique, stylized image. This project demonstrates the implementation of Neural Style Transfer using TensorFlow in Google Colab, leveraging a **pre-trained convolutional neural network (CNN)** to extract the necessary features from the images.

## How It Works

The technique relies on a pre-trained model, such as **VGG19**, which has been trained on the **ImageNet dataset** to recognize and extract hierarchical features from images. Neural Style Transfer uses this pre-trained model to decompose an image into two distinct components:
1. **Content**: The high-level structure and layout of the image.
2. **Style**: The texture, patterns, and color distributions that give an image its artistic essence.

By iteratively optimizing a generated image, the algorithm minimizes a combined loss function:
- **Content Loss**: Measures how closely the content of the generated image matches the content of the input content image.
- **Style Loss**: Measures how closely the texture and patterns of the generated image resemble the style of the input style image.

  
## How to Use

1. **Upload the Notebook**  
   Open the file `Style_Transfer.ipynb` in your Google Colab environment.

2. **Add Images**  
   Upload your content and style images to the Colab environment. You can upload them using the file upload option in Colab or provide image URLs in the notebook.

3. **Modify Parameters**  
   In the notebook, you can adjust the following parameters to customize the output:
   - `content_weight`: Weight for preserving content details.
   - `style_weight`: Weight for transferring artistic style.
   - `epochs`: Number of optimization steps.

4. **Run the Notebook**  
   Execute each cell sequentially to generate the stylized output image.

5. **Download the Result**  
   The final stylized image will be displayed in the notebook and can be saved locally.

## Features

- Combines artistic styles with real-world content using deep learning.
- Fully customizable weights for content and style loss.
- Outputs high-quality stylized images.

## Example Results


![download (2)](https://github.com/user-attachments/assets/f010953b-e67e-468b-918d-7ccec90ec789)

 
## Notes

- Ensure your images are in supported formats like `.jpg` or `.png`.
- You can experiment with different images and parameters to see varied results.

Enjoy creating art with Neural Style Transfer!
