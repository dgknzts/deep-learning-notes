# Deep Understanding of Deep Learning — Study Notes

Personal reference notebook for the [Deep Understanding of Deep Learning](https://www.udemy.com/course/deeplearning_x/) course by Mike X Cohen.

This repo contains 155 Jupyter notebooks covering deep learning from math foundations through advanced architectures (GANs, RNNs, transfer learning), implemented in Python with PyTorch.

## Tech Stack

- **Python 3.x** with **PyTorch**
- NumPy, Matplotlib, scikit-learn, pandas, scipy
- Cursor (local IDE) / Google Colab (original runtime)

## Repository Structure

```
CohenX_course_content/   # Original course notebooks (21 topic folders)
my_notes/                # My personal notes and experiments
projects/                # Applied projects using course concepts
ROADMAP.md               # Full learning path with all 155 notebooks in order
```

## Course Topics

| # | Topic | Folder | Notebooks | Description |
|---|-------|--------|:---------:|-------------|
| 1 | Python Fundamentals | `python/` | 6 | Variables, data types, flow control, functions |
| 2 | Math Foundations | `math/` | 13 | Derivatives, linear algebra, statistics, entropy, softmax |
| 3 | Gradient Descent | `gradientDescent/` | 5 | 1D/2D gradient descent, experimentation |
| 4 | ANNs | `ANN/` | 12 | Regression, classification, network architecture |
| 5 | Overfitting | `overfitting/` | 5 | Train/dev/test splits, cross-validation, DataLoader |
| 6 | Metaparameters | `metaparams/` | 15 | Optimizers, activations, batch norm, learning rate |
| 7 | Data Handling | `data/` | 9 | Augmentation, loaders, saving/loading models |
| 8 | Performance Metrics | `measurePerformance/` | 5 | Accuracy, precision, recall, F1 |
| 9 | Feed-Forward Networks | `FFN/` | 10 | MNIST classification, weight analysis |
| 10 | FFN Milestones | `FFNmilestone/` | 3 | Milestone projects |
| 11 | Weight Initialization | `weights/` | 8 | Xavier, Kaiming, weight freezing |
| 12 | Regularization | `regularization/` | 8 | L1/L2, dropout, mini-batch |
| 13 | Convolution Operations | `convolution/` | 7 | Conv2d, pooling, transforms, custom datasets |
| 14 | CNNs | `CNN/` | 13 | MNIST, EMNIST, Gaussian classification, autoencoders |
| 15 | CNN Milestones | `CNNmilestone/` | 4 | Milestone projects |
| 16 | RNNs | `RNN/` | 5 | RNN, LSTM, GRU architectures |
| 17 | Autoencoders | `autoencoders/` | 5 | Denoising, latent codes, tied weights, occlusion |
| 18 | GANs | `GANs/` | 7 | Linear and CNN-based GANs |
| 19 | GPU Computing | `GPU/` | 2 | GPU implementation and benchmarking |
| 20 | Transfer Learning | `transferlearning/` | 6 | ResNet, VGG16, fine-tuning, pretraining |
| 21 | Style Transfer | `styletransfer/` | 2 | Neural style transfer |

See [ROADMAP.md](ROADMAP.md) for the recommended learning order with all notebooks listed.

## Setup (Cursor / Local)

```bash
# 1. Clone the repo
git clone https://github.com/<your-username>/deep-learning-notes.git

# 2. Create a virtual environment (optional but recommended)
python -m venv venv
source venv/bin/activate  # or venv\Scripts\activate on Windows

# 3. Install dependencies
pip install -r requirements.txt

# 4. Open in Cursor and run notebooks
# Open any .ipynb file -> select Python kernel -> run cells
```

### Colab Compatibility Note

The course notebooks were originally designed for Google Colab. When running locally:
- **~31 notebooks** reference `sample_data/mnist_train_small.csv` (a Colab-provided file). These cells can be replaced with `torchvision.datasets.MNIST` or you can download the CSV manually.
- **~6 notebooks** use `google.colab` imports for file upload/drive mounting. Skip these cells when running locally.

## Acknowledgments

- **Course**: "A Deep Understanding of Deep Learning" by Mike X Cohen
- **Website**: [sincxpress.com](https://sincxpress.com)
- **Platform**: [Udemy](https://www.udemy.com/course/deeplearning_x/)
