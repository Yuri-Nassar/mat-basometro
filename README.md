# 🌳📊 mat-basometro

mat-basometro is a Python-based project that provides the data and code necessary to reproduce the findings of a study published in EPJ Data Science. This project facilitates the exploration and analysis of the research, allowing users to delve into the data, replicate the experiments, and potentially extend the work with their own analysis.

![Version](https://img.shields.io/badge/version-1.0.0-blue)
![License](https://img.shields.io/badge/license-MIT License-green)
![Stars](https://img.shields.io/github/stars/Yuri-Nassar/mat-basometro?style=social)
![Forks](https://img.shields.io/github/forks/Yuri-Nassar/mat-basometro?style=social)

## ✨ Features

*   ✨ **Interactive Jupyter Notebooks**: Explore the data analysis and modeling steps in a clear, reproducible format using `mattree_basometro.ipynb`.
*   📈 **Comprehensive Data Preprocessing**: Utilize dedicated scripts within the `preprocessing` directory to prepare raw datasets for analysis.
*   📄 **EPJ-Data Science Journal Companion**: This repository directly complements the research published in the EPJ-Data Science journal, providing all necessary code and data.
*   🔍 **Transparent Methodology**: Every step, from initial data ingestion to final results, is meticulously documented, ensuring full transparency and verifiability.
*   ⚙️ **Easy Environment Setup**: Get started quickly with a streamlined dependency management system via `requirements.txt`.


## 🚀 Installation Guide

To set up the `mat-basometro` project locally, follow these steps. This project primarily uses Python and its ecosystem.

### Prerequisites

Ensure you have Python 3.8+ and `pip` installed on your system.

### Step-by-Step Installation

1.  **Clone the Repository**:
    First, clone the `mat-basometro` repository to your local machine:

    ```bash
    git clone https://github.com/Yuri-Nassar/mat-basometro.git
    cd mat-basometro
    ```

2.  **Create a Virtual Environment (Recommended)**:
    It's highly recommended to create a virtual environment to manage project dependencies.

    ```bash
    python -m venv venv
    ```

3.  **Activate the Virtual Environment**:
    *   **On macOS/Linux**:
        ```bash
        source venv/bin/activate
        ```
    *   **On Windows**:
        ```bash
        .\venv\Scripts\activate
        ```

4.  **Install Dependencies**:
    Once the virtual environment is active, install all required packages using `pip`:

    ```bash
    pip install -r requirements.txt
    ```

5.  **Install Jupyter Kernel (Optional but Recommended)**:
    If you plan to run the Jupyter Notebooks, it's good practice to install a kernel for your virtual environment:

    ```bash
    pip install ipykernel
    python -m ipykernel install --user --name=mat-basometro --display-name="Python (mat-basometro)"
    ```

You are now ready to use the project!


## 💡 Usage Examples

This project's core analysis is contained within the `mattree_basometro.ipynb` Jupyter Notebook.

### Running the Jupyter Notebook

1.  **Start Jupyter Lab/Notebook**:
    Ensure your virtual environment is activated, then launch Jupyter:

    ```bash
    jupyter lab
    # or
    jupyter notebook
    ```

2.  **Navigate and Open**:
    In your browser, navigate to the `mat-basometro` directory and open `mattree_basometro.ipynb`.

3.  **Execute Cells**:
    You can now run the cells sequentially to reproduce the data loading, preprocessing, analysis, and visualization steps.

### Exploring Datasets

The `datasets` directory contains the raw and processed data used in the analysis.

## 📝 License

This project is released under the [MIT License](https://opensource.org/licenses/MIT).

## Authors

- Yuri Santos, UFSC, Brazil.
- Marcus Torres, UFPE, Brazil.
- Tarlis Portela, UFPR, Brazil.
- Jonathan Silva, LSESP, United Kingdom.
- Jônata Tyska, UFSC, Brazi.