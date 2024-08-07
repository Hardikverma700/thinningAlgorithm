# Zhang-Suen Thinning Algorithm

## Description

This project implements the **Zhang-Suen thinning algorithm** in Python to convert grayscale images to binary and thin them to their skeletal forms. The goal is to simplify complex images to single-pixel skeletons, enabling advanced image analysis such as pattern recognition and shape analysis.

## Technologies Used

- **Pillow (PIL)**: For image processing tasks, including converting JPEG to grayscale BMP.
- **Matplotlib**: For visualizing the original and skeletonized images.
- **skimage**: For applying Otsu's method to convert grayscale images to binary.

## Features

- 🖼️ **Grayscale Conversion**: Convert JPEG images to grayscale BMP using Pillow.
- 📏 **Binary Conversion**: Apply Otsu's method for converting grayscale images to binary.
- ✂️ **Image Skeletonization**: Implement the Zhang-Suen thinning algorithm for skeletonizing binary images.
- 📊 **Visualization**: Visualize the original and skeleton images using Matplotlib.

## Workflow

1. **Grayscale Conversion**: Convert JPEG images to grayscale BMP using Pillow.
2. **Binary Conversion**: Apply Otsu's method to convert grayscale images to binary format.
3. **Thinning Algorithm**: Implement the Zhang-Suen thinning algorithm to thin the binary images to their skeletal forms.
4. **Visualization**: Use Matplotlib to display the original and skeletonized images side by side.

## Outcome

The project successfully simplifies complex images to single-pixel skeletons. This simplification is crucial for advanced image analysis tasks such as pattern recognition and shape analysis.

## How to Use

1. Clone or download the repository.
2. Ensure you have the required libraries installed:
    ```bash
    pip install pillow matplotlib scikit-image
    ```
3. Run the Python script:
    ```bash
    python zhang_suen_thinning.py
    ```
4. The script will process the images and display the original and skeletonized versions using Matplotlib.

## Files Included

- `zhang_suen_thinning.py`: The main Python script containing the implementation of the Zhang-Suen thinning algorithm.
- `example.jpg`: Sample JPEG image to be processed.

## Example

Here is an example of the process:

![Original and Skeleton Images]( https://github.com/Hardikverma700/thinningAlgorithm/blob/main/Screenshot%20(265).png )

## Contributing

Feel free to fork this project, make enhancements, and submit pull requests. Contributions are welcome!

---

Enjoy working with image skeletonization! If you have any questions or feedback, please open an issue or reach out.

