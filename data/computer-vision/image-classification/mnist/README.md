# 🗃️ MNIST Dataset

- A classic dataset used for handwritten digit classification, containing grayscale images of digits (0-9).
- **Reference Paper**:
  - [**Gradient-Based Learning Applied to Document Recognition**](https://ieeexplore.ieee.org/abstract/document/726791/) by [*Yann LeCun*](https://scholar.google.com/citations?user=WLN3QrAAAAAJ&hl=en&oi=sra) et al. in 1998.
- **Creators**:
  - [Yann LeCun](https://scholar.google.com/citations?user=WLN3QrAAAAAJ&hl=en&oi=sra)
  - [Corinna Cortes](https://scholar.google.com/citations?user=U_IVY50AAAAJ&hl=en&oi=ao)
  - [Christopher J. Burges](https://chrisburges.net/bio/)

## 🔍 More Details

- **Total Number of Images**: 70,000
- **Classes**: 10 (0, 1, 2, 3, 4, 5, 6, 7, 8, 9)
- **Train Set Size**: 60,000 images
- **Test Set Size**: 10,000 images
- **Image Size**: 28x28 pixels
- **Image Format**: Grayscale (single channel)
- **Pixel Values**: Integer values between 0 and 255

### 🆔 Dataset Distribution

<table style="margin:0 auto;">
  <thead>
    <tr>
      <th>Dataset</th>
      <th>Class 0</th>
      <th>Class 1</th>
      <th>Class 2</th>
      <th>Class 3</th>
      <th>Class 4</th>
      <th>Class 5</th>
      <th>Class 6</th>
      <th>Class 7</th>
      <th>Class 8</th>
      <th>Class 9</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align: center;"><strong>Train Set</strong></td>
      <td>5923</td>
      <td>6742</td>
      <td>5958</td>
      <td>6131</td>
      <td>5842</td>
      <td>5421</td>
      <td>5918</td>
      <td>6265</td>
      <td>5851</td>
      <td>5949</td>
    </tr>
    <tr>
      <td style="text-align: center;"><strong>Test Set</strong></td>
      <td>980</td>
      <td>1135</td>
      <td>1032</td>
      <td>1010</td>
      <td>982</td>
      <td>892</td>
      <td>958</td>
      <td>1028</td>
      <td>974</td>
      <td>1009</td>
    </tr>
  </tbody>
</table>

### 📊 Dataset Usage

The MNIST dataset is widely used for:

- **Handwritten Digit Classification**: Identifying digits in images using machine learning models.
- **Feature Extraction**: Extracting features from images to evaluate classifiers.
- **Model Evaluation**: Comparing the performance of various machine learning models for digit recognition.

## 📥 Access the Dataset

- The MNIST dataset is not directly included in this repository due to its size **[~56 MB]**.
- You can download the dataset from the following link:
  - Original site: [**yann.lecun.com/exdb/mnist**](https://yann.lecun.com/exdb/mnist/)
  - Alternatively, it can be accessed through [**kaggle.com/datasets/hojjatk/mnist-dataset/code**](https://www.kaggle.com/datasets/hojjatk/mnist-dataset/code)
  - This dataset is also available via popular libraries like **TensorFlow** and **PyTorch** with built-in loaders.
- ⚠️ **Known Issues**:
  - The images are noisy due to the handwriting variations, which may affect model accuracy.
- ✍️ **Notes**:
  - The dataset is preprocessed and available in different formats (raw images, CSV, etc.).
  - Images are center-cropped to remove unnecessary padding.

### 📄 Contents within the Dataset

- **train-images.idx3-ubyte**
  - Binary file containing the training image data (60,000 images).
- **train-labels.idx1-ubyte**
  - Binary file containing the training labels (60,000 labels).
- **t10k-images.idx3-ubyte**
  - Binary file containing the test image data (10,000 images).
- **t10k-labels.idx1-ubyte**
  - Binary file containing the test labels (10,000 labels).
- ✍️ **Notes**:
  - MNIST files start with a header containing metadata which depends on the type of file:
    - Image files (e.g., train-images.idx3-ubyte):
      - Fixed size: 16 bytes
      - Breakdown:
        - 4 bytes: Magic number
        - 4 bytes: Number of images
        - 4 bytes: Rows per image
        - 4 bytes: Columns per image
    - Label files (e.g., train-labels.idx1-ubyte):
      - Fixed size: 8 bytes
      - Breakdown:
        - 4 bytes: Magic number
        - 4 bytes: Number of labels
  - Use `np.fromfile()` with `dtype=np.uint8` to load the data and skip the header using the `offset` parameter.
  - After loading, **reshape** the flat data into its appropriate dimensions: `(num_images, rows, columns)`.
  - In order to let NumPy decide number of images, use `(-1, rows, columns)` when reshaping.

## 📄 License

This dataset does not appear to have a specific license or formal usage agreement provided by its creators or maintainers.  
Users are encouraged to verify usage terms if needed.

## ©️ Credit

Visit [**THE MNIST DATABASE of handwritten digits**](https://yann.lecun.com/exdb/mnist/) or [**Kaggle**](https://www.kaggle.com/datasets/hojjatk/mnist-dataset/code) for more information.
