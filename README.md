# Intro to Python, NumPy, and PyTorch

This repository contains introductory Jupyter notebooks for learning computational methods essential for modern economic research.

## 🎯 Learning Objectives

By the end of this course, you will be able to:
- **Python Fundamentals**: Write clean, efficient Python code for data manipulation
- **Numerical Computing**: Use NumPy for fast array operations and mathematical computations
- **Deep Learning**: Implement neural networks and optimization algorithms with PyTorch
- **Research Applications**: Apply these tools to economic modeling and data analysis

## 📋 Prerequisites

- Basic familiarity with programming concepts
- High school mathematics (calculus, linear algebra)
- No prior Python experience required

## 📚 Course Structure

### Lecture 0: Python Fundamentals
- **Data Types**: Numbers, strings, booleans, and floating-point arithmetic
- **Data Structures**: Lists, tuples, dictionaries, and their performance characteristics
- **Control Flow**: Loops, conditionals, and basic algorithms
- **Functions**: Definition, scope, and best practices

### Lecture 1: NumPy for Numerical Computing
- **Array Operations**: Creation, indexing, slicing, and reshaping
- **Mathematical Operations**: Broadcasting, aggregation, and linear algebra
- **Performance**: Vectorization and memory efficiency
- **Random Number Generation**: Statistical distributions and reproducibility

### Lecture 2: PyTorch for Deep Learning
- **Tensors**: Creation, manipulation, and memory layout
- **Automatic Differentiation**: Gradients, Jacobians, and computational graphs
- **Optimization**: Gradient descent and advanced optimizers
- **Neural Networks**: Building and training models for economic applications

## 🚀 Quick Start

### Setup Instructions

```bash
# Create virtual environment
python3 -m venv myenv
source myenv/bin/activate  # On Windows: myenv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Install Jupyter kernel
python -m ipykernel install --user --name=intro-python --display-name "Intro Python"

# Launch Jupyter
jupyter notebook notebooks/
```

### Alternative: Using Conda

```bash
# Create conda environment
conda create -n intro-python python=3.9
conda activate intro-python

# Install packages
conda install numpy pytorch torchvision torchaudio -c pytorch
pip install torchviz graphviz jupyter ipykernel
```

## 📦 Dependencies

All required packages are listed in `requirements.txt`:
- `numpy` - Numerical computing
- `torch`, `torchvision`, `torchaudio` - PyTorch ecosystem
- `torchviz`, `graphviz` - Computational graph visualization
- `jupyter`, `ipykernel` - Jupyter notebook environment

## 🔧 Additional Setup

- **Graphviz**: For visualizing computational graphs with `torchviz`
  - **macOS**: `brew install graphviz`
  - **Ubuntu**: `sudo apt-get install graphviz`
  - **Windows**: Download from [graphviz.org](https://graphviz.org/download/)

## 📖 How to Use This Course

1. **Sequential Learning**: Work through notebooks in order (0 → 1 → 2)
2. **Interactive Practice**: Run all code cells and experiment with modifications
3. **Application Focus**: Pay attention to economic examples and use cases
4. **Self-Assessment**: Review concepts and verify your understanding

## 🎓 Learning Assessment

Each lecture includes:
- **Concept Checks**: Quick questions to verify understanding
- **Economic Applications**: Real-world examples from economic research
- **Interactive Examples**: Hands-on code demonstrations
- **Best Practices**: Tips for efficient and clean code

## 🤝 Contributing

This course is part of the **Data and Computation** course in the NYU Economics PhD program. 

## 📄 License

This material is provided for educational purposes as part of the NYU Economics PhD program.

---

