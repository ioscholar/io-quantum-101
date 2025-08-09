# IO Quantum 101 Labs

Welcome to the **IO Quantum Summer School 2025** at [IO Scholar Community](https://ioscholar.com)! 🚀

This repository contains hands-on laboratory exercises designed to provide you with a foundational understanding of Quantum Computing, with a particular focus on designing and implementing quantum algorithms using [Qiskit SDK](https://github.com/Qiskit/qiskit).

## 🎯 Program Overview

The IO Quantum Summer School is a comprehensive program that bridges theory and practice in quantum computing. Each lab exercise has been carefully developed to help you apply concepts from reading materials and lectures, ensuring a comprehensive learning experience grounded in practical quantum programming using Qiskit.

## 📚 Lab Exercises

### Lab 01 - Building "Hello Quantum" Programs with Qiskit
**File:** `Lab01/Lab01.ipynb`

**Topics Covered:**
- Setting up your local quantum development environment
- Introduction to Qiskit framework
- Building your first quantum program
- Constructing quantum circuits for true random number generation
- Understanding quantum randomness principles

**Prerequisites:**
- Python 3.8+ installed
- Virtual environment setup (venv or Conda)
- Basic understanding of Python programming

## 🛠️ Getting Started

### 1. Clone the Repository

First, clone this repository to your local machine:

```bash
git clone https://github.com/ioscholar/io-quantum-101.git
cd io-quantum-101
```

### 2. Environment Setup

Create and activate a virtual environment:

**Using venv:**
```bash
python -m venv ioq
source ioq/bin/activate  # On macOS/Linux
# or
ioq\Scripts\activate     # On Windows
```

**Using Conda:**
```bash
conda create -n ioq python=3.9
conda activate ioq
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

**Main Dependencies:**
- `qiskit==2.1.1` - Quantum computing framework
- `qiskit-aer==0.17.1` - High-performance quantum circuit simulator
- `qiskit_ibm_runtime==0.41.0` - IBM Quantum runtime services
- `matplotlib==3.10.5` - Plotting and visualization
- `pylatexenc==2.10` - LaTeX encoding support

### 4. Launch Jupyter Notebook
Navigate to the lab directory and open the desired notebook file.

**Recommended IDEs:**
- [Visual Studio Code](https://code.visualstudio.com/) - Free, powerful code editor with excellent Jupyter notebook support
- [Cursor](https://cursor.sh/) - AI-powered code editor built on VS Code with enhanced coding assistance

## 📝 Working with the Labs

### Notes:

1. **Kernel Management:** If you restart the kernel, re-run all code cells from top to bottom
2. **Pre-filled Code:** Do not modify cells with pre-written code in assignment section if you're unsure
3. **Your Code Areas:** Look for comments like `### WRITE YOUR CODE BELOW THIS CELL ###`
4. **Local Simulation:** Due to regional restrictions, we run quantum simulations locally instead of on IBM's cloud hardware

### Lab Structure:
- **Markdown cells:** Explanations and instructions
- **Code cells:** Hands-on quantum programming exercises
- **Visualization:** Quantum circuit diagrams and result plots

## 📖 Additional Resources

- [IBM Quantum Documentation](https://quantum.cloud.ibm.com/docs/en/guides)
- [IBM Quantum Learning](https://quantum.cloud.ibm.com/learning/en)
- [Python Virtual Environments Guide](https://docs.python.org/3/library/venv.html)
- [Conda Environment Guide](https://docs.conda.io/projects/conda/en/latest/user-guide/install/index.html)

## 🤝 IO Scholar Community

This program is part of the IO Scholar Community's educational initiatives. Learn more and join our community at [https://www.ioscholar.com](https://www.ioscholar.com) for additional learning materials, discussions, and support.

## 📄 License

This educational content is provided for learning purposes as part of the IO Quantum Summer School program.

---

**Happy Quantum Programming!** 🌌✨