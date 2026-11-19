# Deep Learning Coursework

Deep learning assignments and individual challenges by me, covering data preparation, neural network fundamentals, model selection, convolutional networks, and residual connections.

The notebooks contain code, written explanations, and saved experiment outputs. Group assignments retain their contributor credits and division of work.

## Assignments

| Project | Focus | My contribution in Group 16 |
| --- | --- | --- |
| [01 — PyTorch fundamentals](assignments/01-pytorch-fundamentals/assignment.ipynb) | Tensors, regression, training loops, and multi-input/multi-output networks | Part 4: adapt the network to two inputs and two outputs |
| [02 — Wine quality](assignments/02-wine-quality/assignment.ipynb) | Regression, uncertainty, binary and multiclass classification, and validation-based grid search | Part 6: multiclass classification with cross entropy |
| [03 — CNNs on CIFAR-10](assignments/03-cifar10-cnns/assignment.ipynb) | Baseline CNNs, dropout, learned downsampling, and final evaluation | Part 3: compare dropout and downsampling |

Group contributors: **Titobiloluwa Odufuye, Logan Yee, and João Pedro Minari**. Detailed responsibilities appear in each assignment. Student identifiers have been removed from these repository copies.

## Individual challenges

| Challenge | Focus |
| --- | --- |
| [Data preparation and learning](challenges/01-data-preparation/challenge.ipynb) | Preprocessing, supervised learning, and K-means clustering |
| [02 — Linear regression from scratch](challenges/02-linear-regression/challenge.ipynb) | Manual gradients, gradient descent, and learning-rate comparison |
| [03 — Shallow vs. deep networks](challenges/03-shallow-vs-deep/challenge.ipynb) | Representational capacity and training under an equal parameter budget |
| [04 — MNIST architectures](challenges/04-mnist-architectures/challenge.ipynb) | Comparing deep fully connected digit classifiers |
| [05 — Initialization and gradient flow](challenges/05-initialization-gradient-flow/challenge.ipynb) | Diagnosing and repairing initialization problems |
| [06 — Conv1D on MNIST-1D](challenges/06-mnist1d-conv1d/challenge.ipynb) | Classifying one-dimensional signals with convolutional networks |
| [07 — Residual connections](challenges/07-residual-connections/challenge.ipynb) | Comparing plain and residual CNNs |

The data-preparation notebook is placed first for navigation; its original file does not specify a challenge number. Other challenge numbers follow the supplied filenames.

## Running the notebooks

Use a local Python environment with Jupyter, or upload a notebook to Google Colab. Open each notebook from its own project folder and run cells in order so relative data and output paths resolve correctly.

Common dependencies:

```bash
python -m pip install jupyterlab ipython numpy pandas matplotlib scikit-learn torch torchvision
python -m jupyterlab
```

These are the libraries used across the collection, not a tested or version-pinned environment. PyTorch installation may need adjustment for your hardware. Some image experiments benefit from a GPU.

### Data and reproducibility notes

- **Assignment 2:** requires `winequality-red.csv` alongside its notebook. This CSV was not included in the supplied coursework folder.
- **Data-preparation challenge:** requires `supervised_student_performance.csv` and `student_learning_profiles.csv` alongside its notebook. Neither CSV was included in the supplied folder.
- Image and signal notebooks contain dataset download/loading code; initial runs may require internet access.
- Saved outputs are retained from the original notebooks. The collection has not been rerun as part of this import, and results may vary across library versions and hardware.
- The data-preparation notebook contains a saved `SyntaxError` in its final reflection cell. Its current source consists of comments, so the error appears to be from an earlier version of that cell. The original saved output is retained for transparency.

Downloaded datasets and generated model checkpoints are excluded from version control.

## Credits

This collection includes course-provided scaffolding and prompts alongside completed student work. Original course references, teammate attribution, and existing AI-use disclosures are retained in the notebooks. No additional reuse license is applied to this collection.
