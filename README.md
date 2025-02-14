# Data Science Lab Machine Learning with scikit-learn course

## Getting the material

To get the course material (notebooks and data) you can download (green "Code" button) this entire repository or, if you are familier with git, clone it. When downloading the repository, it comes as a zip file. Do not forget to **unzip the folder** (especially on Windows which allows to browse through zip files).   

## Setting up an environment

A series of packages is necessary to run the content of this course. We highly recommend to install packages within an environment such as provided by conda. There are multiple ways to install conda and if you don't yet have a version installed we **strongly recommend to use miniforge**. You can find installers at [this link](https://github.com/conda-forge/miniforge?tab=readme-ov-file#install).

Once you have conda installed, open a terminal where you have access to conda (you should see ```(base)``` at the beginning of the line on your terminal window). On MacOS or Linux, your regular terminal should work. On Windows, depending how you installed conda, you might only have access to it from a terminal called "XXX Prompt" where XXX stands for your conda distribution e.g. "Miniforge Prompt".

Then in that terminal head to the folder of the repository you downloaded previously. In the main folder you will find an [environment.yml](environment.yml) file that contains infos about all packages to install. You can simply create the necessary environment using:

    conda env create -f environment.yml

This creates an environment called ```dslsklearn``` that you then need to activate:

    conda activate dslsklearn

Finally you can start Jupyterlab using:

    jupyter lab

This should automatically open a Jupyterlab session in your favorite browser. If not, copy the address appearing in the terminal starting with ```http://localhost:8888...``` in your browser.

## Reporting issues

If you notice any error or have questions, please open an issue.
