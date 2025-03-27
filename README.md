# LoD2 to LoD1 Conversion – TU Delft Assignment

This repository contains a Jupyter Notebook implementation for converting LoD2 building models to LoD1. The code has been written in **Python** inside a **Jupyter Notebook** for better documentation and code readability. Therefore, the file format is `.ipynb` instead of `.py`.

---

## Instructions: How to Run the Notebook

Follow these steps to properly set up and run the code on your local machine:

### Step 1: Download Anaconda

Download the appropriate version of **Anaconda** for your operating system from the official website:

[https://www.anaconda.com/download/success](https://www.anaconda.com/download/success)

---

### Step 2: Launch Anaconda Prompt

After the installation is complete, start the **Anaconda Prompt** application.

<img src="readme_images/anaconda_prompt.png" width="350"/>

---

### Step 3: Install Required Libraries

Run the following commands in the Anaconda Prompt to install the necessary Python libraries:

```bash
pip install open3d
pip install numpy
pip install matplotlib
pip install scipy
```
---

### Step 4: Start Jupyter Notebook

Once the required libraries are installed, launch Jupyter Notebook by entering the following command in the Anaconda Prompt:

```bash
jupyter notebook
```
---

### Step 5: Open the Notebook File

A localhost web page will open in your browser. Download the **Berk_KIVILCIM_TU_Delft_LoD2_to_LoD1_Assignment.ipynb** file and locate the file in the directory where you downloaded it. 

<img src="readme_images/locate_the_file.png" width="1000"/>

---

### Step 6: Defining the folder path where .obj files are stored

Store your `.obj` files inside a dedicated folder on your computer.

Then, in the notebook, go to the second cell and update the variable **`folder_path`** by assigning it the path to the folder where your `.obj` files are stored. For example:

<img src="readme_images/define_folder_path.png" width="1000"/>
