<!-- Added instructions for installing Miniconda3, scikit-learn, jupyter-lab, seaborn and plotly -->
<!-- PROJECT SHIELDS -->
<!--
*** Thanks for checking out the README Template. If you have a suggestion
*** that would make this better, please fork the repo and create a pull request
*** or simply open an issue with the tag "enhancement".
*** Don't forget to give the project a star!
*** Thanks again! Now go create something AMAZING! :D
-->
<a name="readme-top"></a>

<p align="center">
  <h1 align="center">Setting up linux machine for machine learning with latest Miniconda3</h1>
  <p align="center">
    A guide to setup a Linux machine with Miniconda3 and popular data science libraries
    <br />
  </p>
</p>
<!-- TABLE OF CONTENTS -->
<h2>Table of Contents</h2>


<details open="open">
  <summary>Table of Contents</summary>
  <ol>
    <li><a href="#prerequisites">Prerequisites</a></li>
    <li><a href="#installation">Installation</a></li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
    <li><a href="#script">Script</a></li>
  </ol>
</details>
<!-- PREREQUISITES -->
<strong>Prerequisites</strong>

- A Linux machine
- Internet connection

<!-- INSTALLATION -->
<h3>Installation</h3>

Download the latest Miniconda3 bash installer for Linux 64-bit from https://docs.conda.io/en/latest/miniconda.html.

Run the downloaded script and follow the prompts to complete the installation.

```bash 
Miniconda3-latest-Linux-x86_64.sh
```

Open a new terminal or type source ~/.bashrc to activate the changes.
Install scikit-learn using the following command.

```bash 
conda create -n sklearn-env -c conda-forge scikit-learn
```

Activate the environment.

```
conda activate sklearn-env
```

Install JupyterLab using the following command.

```
conda install jupyter-lab
```

Install seaborn using the following command.

```
conda install seaborn -c conda-forge
```

Install plotly using the following command.

```
conda install plotly -c plotly
```

<!-- USAGE -->
<h3>Usage</h3>

Open JupyterLab by running the following command and create a new notebook to start using the installed libraries.

```
jupyter-lab
```

<!-- ACKNOWLEDGMENTS -->
<h3>Acknowledgments</h3>

 - Miniconda
 - scikit-learn
 - JupyterLab
 - seaborn
 - plotly
 
<!--Script-->
<h3>Script</h3>

Here is a sample bash script that you can use to install scikit-learn, JupyterLab, seaborn, and Plotly:

```
#!/bin/bash

# Create conda environment for scikit-learn
conda create -y -n sklearn-env -c conda-forge scikit-learn

# Activate scikit-learn environment
conda activate sklearn-env

# Install JupyterLab using conda
conda install -y jupyterlab

# Install seaborn using conda
conda install -y seaborn -c conda-forge

# Install Plotly using conda
conda install -y -c plotly plotly

```

You can save this script as install.sh and run it using the command bash install.sh in your terminal. Note that this assumes that you have conda installed on your system.

