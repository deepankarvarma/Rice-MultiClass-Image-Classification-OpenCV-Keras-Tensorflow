# Rice Type Detection using Multiclass Classification

This repository contains Python code for a rice type detection project using multiclass classification. The project utilizes MobileNetV2 as the underlying architecture. The dataset used for training and evaluation consists of images of six different rice types: Arborio, Basmati, Ipsala, Jasmine, and Karacadag.

## Dataset

The dataset used for training and evaluation can be found on Kaggle: [Rice Image Dataset](https://www.kaggle.com/datasets/muratkokludataset/rice-image-dataset). It contains images categorized into the following classes:

- `Arborio`: Arborio rice images
- `Basmati`: Basmati rice images
- `Ipsala`: Ipsala rice images
- `Jasmine`: Jasmine rice images
- `Karacadag`: Karacadag rice images

## Dependencies

To run the code in this repository, you'll need the following dependencies:

- Python 3.x
- TensorFlow
- Keras
- NumPy
- Matplotlib

You can install the required packages using `pip`:

```
pip install tensorflow keras numpy matplotlib
```

## Usage

1. Clone this repository to your local machine:

```
git clone https://github.com/your-username/your-repository.git
cd your-repository
```

2. Download the Rice Image Dataset from the provided link and place it in the appropriate directory.

3. Run the script to predict the rice type from an image:

```
python predict_image.py --image path/to/your/image.jpg
```

Make sure to replace `path/to/your/image.jpg` with the actual path to your desired image file.

## Results

The model trained on the Rice Image Dataset can accurately classify the type of rice among Arborio, Basmati, Ipsala, Jasmine, and Karacadag. You can modify the code and experiment with different architectures or hyperparameters to potentially improve the performance.

## Acknowledgments

- The Rice Image Dataset used in this project was sourced from Kaggle: [Rice Image Dataset](https://www.kaggle.com/datasets/muratkokludataset/rice-image-dataset).

## License

This project is licensed under the [MIT License](LICENSE).
