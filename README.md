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

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/othneildrew/Best-README-Template.svg?style=for-the-badge
[contributors-url]: https://github.com/othneildrew/Best-README-Template/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/othneildrew/Best-README-Template.svg?style=for-the-badge
[forks-url]: https://github.com/othneildrew/Best-README-Template/network/members
[stars-shield]: https://img.shields.io/github/stars/othneildrew/Best-README-Template.svg?style=for-the-badge
[stars-url]: https://github.com/othneildrew/Best-README-Template/stargazers
[issues-shield]: https://img.shields.io/github/issues/othneildrew/Best-README-Template.svg?style=for-the-badge
[issues-url]: https://github.com/othneildrew/Best-README-Template/issues
[license-shield]: https://img.shields.io/github/license/othneildrew/Best-README-Template.svg?style=for-the-badge
[license-url]: https://github.com/othneildrew/Best-README-Template/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/othneildrew
[product-screenshot]: images/screenshot.png
[Next.js]: https://img.shields.io/badge/next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white
[Next-url]: https://nextjs.org/
[React.js]: https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB
[React-url]: https://reactjs.org/
[Vue.js]: https://img.shields.io/badge/Vue.js-35495E?style=for-the-badge&logo=vuedotjs&logoColor=4FC08D
[Vue-url]: https://vuejs.org/
[Angular.io]: https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white
[Angular-url]: https://angular.io/
[Svelte.dev]: https://img.shields.io/badge/Svelte-4A4A55?style=for-the-badge&logo=svelte&logoColor=FF3E00
[Svelte-url]: https://svelte.dev/
[Laravel.com]: https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white
[Laravel-url]: https://laravel.com
[Bootstrap.com]: https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white
[Bootstrap-url]: https://getbootstrap.com
[JQuery.com]: https://img.shields.io/badge/jQuery-0769AD?style=for-the-badge&logo=jquery&logoColor=white
[JQuery-url]: https://jquery.com 
