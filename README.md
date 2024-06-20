# neural_style_transfer

Neural Style Transfer (NST) is a deep learning technique that combines the content of one image with the style of another to generate visually appealing artistic images. 
This project implements NST using TensorFlow and Keras, with a focus on the VGG19 model for feature extraction and optimization using the Adam optimizer. 
The goal is to provide a flexible and efficient framework for creating stylized images with custom content and style combinations.

## Installation setup
1. Clone the repository:
   ```bash
   git clone https://github.com/username/neural-style-transfer.git
   cd neural-style-transfer
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Download pre-trained VGG19 weights:
   Download the VGG19 weights from [here](https://github.com/fchollet/deep-learning-models/releases/download/v0.1/vgg19_weights_tf_dim_ordering_tf_kernels_notop.h5) and place them in the project directory.

4. Run the code:
   ```bash
   python neural_style_transfer.py --content_img content.jpg --style_img style.jpg --output_img output.jpg --alpha 10 --beta 100 --iterations 250 --lr 0.2
   ```
## To use the code:
1. Prepare a content image (`content.jpg`) and a style image (`style.jpg`).
2. Update the file paths in the Python script (`neural_style_transfer.py`) to point to your images.
3. Adjust hyperparameters such as alpha (content weight) and beta (style weight) as needed.
4. Run the script to generate the stylized image (`output.jpg`).

## Dependencies
- TensorFlow: Deep learning framework for neural network computations.
- Keras: High-level neural networks API, used here for model building and training.
- NumPy: Fundamental package for numerical computations in Python.
- Matplotlib: Visualization library for creating plots and graphs.
- Other dependencies specified in the `requirements.txt` file.


