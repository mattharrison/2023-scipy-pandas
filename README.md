# 2023-scipy-pandas

This repository contains a Jupyter notebook for the Idiomatic Pandas tutorial. The notebook covers various topics and interactive exercises designed to reinforce your learning. You can run the notebook in a local virtual environment or directly in GitHub Codespaces. 

## Structure of the Repository

- `idiomatic-pandas.ipynb` - This notebook
- `honest.fth` - The data for the tutorial
- `requirements.txt` - This file lists the Python dependencies required to run the notebook.

## Getting Started 

Here's how you can set up and run this project:

### Option 1: Running in Local Virtual Environment 

1. **Clone the Repository** 

    First, clone this repository to your local machine using the following command:

    ```bash
    git clone https://github.com/your_username/your_repository.git
    ```

2. **Create and Activate Virtual Environment** 

    It is always a good practice to create a virtual environment for your Python projects. Here's how you can do it:

    For Windows:

    ```bash
    python -m venv tutorial_env
    tutorial_env\Scripts\activate
    ```

    For macOS/Linux:

    ```bash
    python3 -m venv tutorial_env
    source tutorial_env/bin/activate
    ```

3. **Install Dependencies** 

    Once your virtual environment is activated, you can install the necessary dependencies using pip. Navigate to the directory containing `requirements.txt` file and run:

    ```bash
    pip install -r requirements.txt
    ```

4. **Launch Jupyter Notebook** 

    After you have your environment set up and dependencies installed, you can start Jupyter notebook by running:

    ```bash
    jupyter notebook
    ```

    Then, in your web browser, navigate to the location of the notebook file and click to open it.

### Option 2: Running in GitHub Codespaces 

GitHub Codespaces is a service that allows you to develop in the cloud instead of locally. Here's how you can use it for this project:

1. **Open the Repository in Codespaces** 

    Navigate to this repository in GitHub. Click the `Code` button in the repository header and then select `Open with Codespaces`. 

2. **Wait for a while**

    To let the codespace start

3. **Open the notebook**

4. **Click on "Select Kernel" -> Python Environments... -> Python 3.10**
    
    You should be good to go.

## Visit MetaSnake for Help

We hope you enjoy this tutorial and find it helpful. Visit www.metasnake.com for Python and Data training for your teams. Buy *Effective Pandas* to up your pandas skills.
