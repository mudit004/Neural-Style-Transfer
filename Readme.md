# Neural Style Transfer with PyTorch

This project demonstrates the implementation of Neural Style Transfer (NST) using PyTorch and a pre-trained VGG19 model. The objective is to apply the artistic style of one image to another image while preserving the content of the latter.

## Tech Used

- Python
- PyTorch
- Torchvision
- PIL (Python Imaging Library)
- Matplotlib

---

## Setup

To run this project in Google Colab, follow these steps:

1. Clone the repository `git clone <https/ssh link to repo>`.
2. Upload the provided `.ipynb` file to Google Colab.
3. Update `path/to/content_image` and `path/to/style_image` in the `content_route` and `style_route` variables.
4. Run each cell sequentially to preprocess images, extract features, compute losses, and generate the final stylized image.
