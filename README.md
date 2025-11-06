
# LBA-Alcohol_Social_Choice
LBA Model scripts in python used to model decision-making in choice between alcohol and social reward. Used in paper titled "Anterior insula activity during alcohol and social reward self-administration and choice in male and female rats" Submitted October, 2025

> **Associated Publication:**
> DOI coming

This repository contains the analysis code and figures for the publication listed above. 
1. The primary analysis is conducted in the `1_model_build` Jupyter Notebook.
2. The output models are then compared in the `2_compare_models` Jupyter Notebook - and the winning model is used for subsequent analysis
3. The 'winning' model should be defined, and from this the parameter estimates are derivied in the `3_model_analysis` script

---
This analysis script was developed by Nathan Marchant, PhD. The logical structure, custom PyMC log-likelihood, and documentation were refined through collaboration with Google's Gemini, which served as a thought partner and coding assistant.
---


## 🚀 Getting Started

This project uses [Python](https://www.python.org/) and [Anaconda](https://www.anaconda.com/) for environment management. Follow these steps to set up your local environment and run the analysis.

### Prerequisites

You must have **Anaconda** or **Miniconda** installed on your system.

### Installation & How to Run

1.  **Clone this repository:**
    ```bash
    git clone https://github.com/njmarchant/LBA-Alcohol_Social_Choice.git
    ```

2.  **Navigate to the project directory:**
    ```bash
    cd LBA-Alcohol_Social_Choice
    ```

3.  **Create and activate the Conda environment:**
    This command will automatically create a new environment named `LBA_-_env` using the included `environment.yml` file and install all necessary libraries.

    ```bash
    conda env create -f environment.yml
    conda activate LBA_env
    ```
    > **Note:** The exact environment name is specified at the top of the `environment.yml` file.

4.  **Launch Jupyter Lab:**
    ```bash
    jupyter lab
    ```

5.  Once Jupyter Lab opens in your browser, open the `LBA_Soc_Hierarchical_v3.ipynb` file to view and run the analysis.

---

## 💾 Data

The raw data used in this analysis is stored in this repository.


To run the analysis, please download the data and place it in a folder named `/data/` in the root of this project directory. (This folder is specified in the `.gitignore` and will not be tracked by Git).

---

## ✍️ Authors & Citation

This code was primarily written by Nathan Marchant. 
The logical structure, custom PyMC log-likelihood, and documentation were refined through collaboration with Google's Gemini, which served as a thought partner and coding assistant.

If you use this code or the findings from our paper, please cite the original publication:


### Acknowledgments

