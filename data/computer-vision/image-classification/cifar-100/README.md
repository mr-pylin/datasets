# 🗃️ CIFAR-100 Dataset

- A classic dataset used for image classification, containing **color images** of 100 classes representing common objects.
- The CIFAR-100 is a labeled subset of the [**80 million tiny images**](https://people.csail.mit.edu/torralba/tinyimages/) dataset. They were collected by [Alex Krizhevsky](https://scholar.google.com/citations?user=xegzhJcAAAAJ&hl=en&oi=ao), [Vinod Nair](https://scholar.google.com/citations?user=RnoIxUwAAAAJ&hl=en), and [Geoffrey Hinton](https://scholar.google.com/citations?user=JicYPdAAAAAJ&hl=en&oi=ao).
- Sadly, the **80 million tiny images** dataset has been thrown into the memory hole by its authors.
- **Reference Paper**:
  - [**Learning Multiple Layers of Features from Tiny Images**](https://www.cs.toronto.edu/~kriz/learning-features-2009-TR.pdf) by [*Alex Krizhevsky*](https://scholar.google.com/citations?user=xegzhJcAAAAJ&hl=en&oi=ao) in 2009.
- **Creators**:
  - [Alex Krizhevsky](https://scholar.google.com/citations?user=xegzhJcAAAAJ&hl=en&oi=ao)

## 🔍 More Details

- **Total Number of Images**: 60,000
- **Classes**: 100 (fine-grained classes) grouped into 20 superclasses
- **Train Set Size**: 50,000 images
- **Test Set Size**: 10,000 images
- **Image Size**: 32x32 pixels
- **Image Format**: RGB (3 channels)
- **Pixel Values**: Integer values between 0 and 255 (`uint8`)

### 🆔 Dataset Distribution

<table style="margin:0 auto; border: 1px solid;">
  <thead>
    <tr>
      <th style="text-align: center;">Dataset</th>
      <th style="text-align: center;">Fine-Grained Classes</th>
      <th style="text-align: center;">Images Per Class</th>
      <th style="text-align: center;">Total</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align: center;"><strong>Train Set</strong></td>
      <td>100</td>
      <td>500</td>
      <td><strong>50,000</strong></td>
    </tr>
    <tr>
      <td style="text-align: center;"><strong>Test Set</strong></td>
      <td>100</td>
      <td>100</td>
      <td><strong>10,000</strong></td>
    </tr>
  </tbody>
</table>

## 📥 Access the Dataset

- The CIFAR-100 dataset is not directly included in this repository due to its size **[~170 MB]**.
- You can download the dataset from the following link:
  - Original site: [**cs.toronto.edu/~kriz/cifar.html**](https://www.cs.toronto.edu/~kriz/cifar.html)
  - Alternatively, it can be accessed through [**kaggle.com/datasets/fedesoriano/cifar100**](https://www.kaggle.com/datasets/fedesoriano/cifar100)
  - This dataset is also available via popular libraries like **TensorFlow** and **PyTorch** with built-in loaders.
    - **TensorFlow**:

      ```python
      from tensorflow.keras.datasets import cifar100
      (train_images, train_labels), (test_images, test_labels) = cifar100.load_data()
      ```

    - **PyTorch**:

      ```python
      from torchvision.datasets import CIFAR100
      train_dataset = CIFAR100(root="./data", train=True, download=True)
      test_dataset = CIFAR100(root="./data", train=False, download=True)
      ```

- ⚠️ **Known Issues**:
  - The images are low resolution, which may limit their use for advanced tasks.
- ✍️ **Notes**:
  - The dataset is preprocessed and available in different formats (raw images, binary, etc.).
  - Images are uniformly cropped to 32x32 pixels.

### 📄 Contents within the Dataset [Binary Files]

- **train.bin**
  - Binary file containing training images (50,000 images).
- **test.bin**
  - Binary file containing test images (10,000 images).
- ✍️ **Notes**:
  - Use `pickle` to load the data as a python dictionary:

    ```python
    with open(file_name, 'rb') as f:
        dict = pickle.load(f, encoding='latin1')
    ```

  - Labels include:
    - **Fine-grained labels**: 0–99 (specific classes)
    - **Coarse labels**: 0–19 (superclasses)

## 📄 License

This dataset does not appear to have a specific license or formal usage agreement provided by its creators or maintainers.  
Users are encouraged to verify usage terms if needed.

## ©️ Credit

Visit [**CIFAR-100 Dataset**](https://www.cs.toronto.edu/~kriz/cifar.html) or [**Kaggle**](https://www.kaggle.com/datasets/fedesoriano/cifar100) for more information.
