# Color Quantization Compressor

This project implements an image compression application using the K-means clustering algorithm, an unsupervised machine learning technique. The application reduces the number of colors in an image to a specified count, effectively compressing the image while maintaining its visual integrity. In this implementation, the original image is compressed to 16 colors.

## Features

- **Color Reduction**: Compress images by limiting the color palette to a specified number of colors using K-means clustering.
- **Image Processing**: Utilizes OpenCV for image reading and processing.
- **Visualization**: Provides visual comparisons between the original and compressed images.

## Installation

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/swaroopms658/Color-Quantization-Compressor.git
   ```

2. **Navigate to the Project Directory**:

   ```bash
   cd Color-Quantization-Compressor
   ```

3. **Install Dependencies**:

   Ensure you have Python installed. Install the required packages using pip:

   ```bash
   pip install -r requirements.txt
   ```

   *Note: If a `requirements.txt` file is not provided, the primary dependencies are `numpy`, `opencv-python`, and `matplotlib`. Install them using:*

   ```bash
   pip install numpy opencv-python matplotlib
   ```

## Usage

1. **Prepare Your Image**:

   Place the image you want to compress in the `data` directory.

2. **Run the Compression Script**:

   Execute the Jupyter Notebook `C3_W1_KMeans_Assignment.ipynb` to perform color quantization on your image. This notebook contains step-by-step instructions and code explanations.

3. **View Results**:

   The compressed image will be saved in the `images` directory for comparison with the original.

## Example

Below is an example of compressing an image to 16 colors:

| Original Image             | Compressed Image (16 colors)     |
|----------------------------|----------------------------------|
| ![Original Image](images/original_image.png) | ![Compressed Image](images/compressed_image.png) |

*Note: Replace `original_image.png` and `compressed_image.png` with your actual image filenames.*

## Contributing

Contributions are welcome! If you have suggestions for improvements or new features, feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.

## Acknowledgments

This project was inspired by the need for efficient image compression techniques using machine learning algorithms.

---

For any questions or support, please contact [your-email@example.com](mailto:your-email@example.com).
