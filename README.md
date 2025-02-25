This Jupyter Notebook, demonstrates various image processing techniques and operations using the `numpy` library. It also includes examples of vectorization, rotation, and graph theory concepts. The notebook is divided into several sections, each focusing on a specific topic:

1. **Image Processing**: 
   - Loading and converting images to grayscale.
   - Applying operations like brightness adjustment, inversion, and splitting images.
   - Concatenating and mirroring image parts.

2. **Vector Similarity**:
   - Calculating the similarity between vectors using a custom metric.

3. **Shear Transformation**:
   - Applying shear transformations to images and comparing the similarity between the original and sheared images.

4. **Graph Theory**:
   - Demonstrating graph operations like tensor (category) and Cartesian products using adjacency matrices.

5. **Vectorization and Rotation**:
   - Rotating facial data points using rotation matrices.
   - Comparing execution times of vectorized operations versus loops.

6. **Pandas Integration**:
   - Loading a CSV file, calculating student averages, and sorting the data.

## Dependencies
To run this notebook, you need the following Python libraries installed:

- `numpy`
- `opencv-python` (for image processing)
- `matplotlib` (for plotting images and graphs)
- `networkx` (for graph theory operations)
- `pandas` (for data manipulation and CSV handling)

## Usage
1. **Running the Notebook**:
   - Open the notebook in Jupyter or Google Colab.
   - Ensure all dependencies are installed.
   - Run each cell sequentially to see the output.

2. **Image Processing**:
   - Replace the image path `./R.jpeg` with the path to your own image if needed.
   - The notebook demonstrates grayscale conversion, brightness adjustment, inversion, and splitting of images.

3. **Graph Theory**:
   - The notebook includes examples of tensor and Cartesian products of graphs using adjacency matrices.
   - Visualizations of the graphs are provided using `networkx` and `matplotlib`.

4. **Vectorization and Rotation**:
   - The notebook demonstrates how to rotate facial data points using rotation matrices.
   - It also compares the performance of vectorized operations versus loops.

5. **Pandas Integration**:
   - The notebook loads a CSV file (`grades.csv`), calculates student averages, and saves the sorted results to `sorted_grades.csv`.

## Notes
- If you encounter the `ModuleNotFoundError` for `google.colab`, ensure you are running the notebook in Google Colab or remove the `cv2_imshow` dependency and use `matplotlib` for displaying images instead.
- The notebook assumes the presence of specific files (e.g., `grades.csv`). Replace these with your own files as needed.
