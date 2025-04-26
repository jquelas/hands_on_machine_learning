# Hands-On Machine Learning (2nd Edition) - Code Repository

## Overview
This repository contains the code and exercises for studying *Hands-On Machine Learning with Scikit-Learn, Keras, and TensorFlow (2nd Edition)* by Aurélien Géron. Each chapter's code is organized in separate folders to facilitate structured learning.

## Repository Structure
Each folder corresponds to a chapter from the book, following the naming convention:

```
CX - Name of the Chapter
```

where `X` represents the chapter number, starting from Chapter 2 (as the first chapter is theoretical). Currently, the repository includes code for the first 8 chapters, with the goal of covering all chapters eventually.

Each chapter folder also contains a dedicated virtual environment (`env`) for dependency management.

### Completed Chapters
- **C2 - End-to-End Machine Learning Project**
- **C3 - Classification**
- **C4 - Training Models**
- **C5 - Support Vector Machines**
- **C6 - Decision Trees**
- **C7 - Ensemble Learning and Random Forests**
- **C8 - Dimensionality Reduction**
- **C9 - Unsupervised Learning Techniques**
- **C10 - Artificial Neural Networks with Keras**
- **C11 - Training Deep Neural Networks** *(Work in Progress)*

## Getting Started
To use this repository, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/jquelas/hands_on_machine_learning.git
   cd hands_on_machine_learning
   ```
2. **Activate the virtual environment:**
   ```bash
   .\env\Scripts\activate  # Windows
   ```
   ```bash
   source env/bin/activate  # Linux/macOS
   ```
3. **Navigate to a specific chapter folder:**
   ```bash
   cd "C2 - End-to-End Machine Learning Project"
   ```
4. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```
5. **Configure Jupyter Kernel (Optional but Recommended):**
   ```bash
   python -m ipykernel install --user --name=env --display-name "Python (env)"
   ```
6. **Run the code within the chapter folder.**

## Dependencies
The repository requires the following Python libraries:
- `scikit-learn`
- `tensorflow`
- `keras`
- `scikeras`
- `numpy`
- `pandas`
- `matplotlib`
- `jupyter`
- `scipy`
- `ipykernel`
- `xgboost`

Ensure all dependencies are installed using:
```bash
pip install -r requirements.txt
```

## License
This project follows the book's licensing guidelines. The code is intended for educational purposes.

---

Happy coding and learning! 🚀
