# Blood Cell Cancer Detection Using Deep Learning Techniques

Deep learning experiments for classifying blood-cell images to help detect blood cancer (end-semester Deep Learning project).

## Notebooks

| Notebook | Framework | Description |
|----------|-----------|-------------|
| `DL_ENDSEM.ipynb` | TensorFlow / Keras | CNN-based classifier with checkpointing, learning-rate scheduling and early stopping; reports accuracy, AUC, precision and recall, plus classification report and confusion matrix |
| `dl_end.ipynb` | PyTorch | Image-folder pipeline comparing a ResNet-18 baseline with custom lightweight blocks (Ghost-style modules), evaluated with accuracy, precision, recall, F1, training curves and confusion matrix |

## Setup

```bash
pip install tensorflow torch torchvision scikit-learn numpy matplotlib seaborn
```

The notebooks were written for Google Colab (Google Drive is mounted for data). Put your blood-cell image dataset in class-labelled folders (the `ImageFolder` layout), update the dataset path in the first cells, and run the notebooks top to bottom. The dataset is not included in this repository.

## Tech stack

Python, TensorFlow/Keras, PyTorch, scikit-learn, Matplotlib, Seaborn

## Author

Sai Swaroop Talasu – [@saiswaroop25-pixel](https://github.com/saiswaroop25-pixel)
