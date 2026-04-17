# WACAD
This repo contains resources for working with **Web Archive Collections as Data (WACAD)**. WACAD is largely inspired by [Collections as Data](https://collectionsasdata.github.io/) and by the efforts of the International GLAM Labs community to facilitate computational approaches to cultural heritage data.

The notebooks are work in progress and, for the moment, includes a few Jupyter notebooks to demonstrate how you can work with WACAD data.

## Requirements & Setup
The notebooks can be run in several ways, e.g.:
1. Locally on your machine, using Jupyter Lab or Jupyter Notebook.
2. In the cloud, using a platform like Google Colab. 

While running the notebooks in the cloud is easier, it may not be suitable for all use cases, especially if you need to work with large datasets, have sensitive data, or require specific software packages. Running the notebooks locally gives you more control over your environment and allows you to work with larger datasets.

### For local execution
To run the notebooks locally, you need to have e.g. python3 or [Anaconda](https://www.anaconda.com/download)/[Miniconda](https://www.anaconda.com/docs/getting-started/miniconda/main) installed.

#### python3
In your terminal, from the repo root, run:
```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
jupyter notebook
```

#### miniconda
In your terminal, from the repo root, run:
```
conda create -n myenv
conda activate myenv
pip install -r requirements.txt
jupyter notebook
```

#### Anaconda GUI
Open Anaconda Navigator:
- Go to **Environments**.
- Click **Create** and name it, e.g. "wacad"
- Add the packages listed in `requirements.txt`

### For Google Colab notebooks
--> Here goes descriptions of how to find the Colab notebooks.

## Usage: How to run notebooks
Notebooks consist of cells that can be executed, one by one. These cells are either *code* cells, which contain executable code, or *markdown* cells, which contain descriptive or narrative text, such as comments or instructions.

### Markdown cells
Markdown cells support various formatting options, including headings, lists, links, images, and code snippets. To learn more about formatting text with markdown, visit [Markdown Guide](https://www.markdownguide.org/basic-syntax/).

### Code cells
Code cells contain executable code. We outline some basic operations below, while a thorough guide to running notebooks is available in the [Jupyter Notebook Documentation](https://jupyter-notebook.readthedocs.io/en/stable/). (For Google Colab, see their ["Getting started"](https://colab.research.google.com/?utm_source=scs-index#scrollTo=GJBs_flRovLc) section.)

#### Editing code cells
The prepared notebooks have examples and can be run as they are. You can also modify them to fit your own needs.

To edit a cell, simply click on it and start typing.

Lines starting with `#` are comments and will not be executed. If you wish to make commented lines executable, simply remove the `#` at the beginning of the line. You can modify these comments to add your own explanations or instructions.

#### Running code cells
To execute the script in a code cell, make sure it is active and press `Shift + Enter`. You can also click the "Run" button in the toolbar. After execution, the output of the cell will be displayed below.

#### Run order
The notebooks are structured in a way that the cells should be executed in order, as some cells depend on the output of previous cells. If you run a cell out of order, you may encounter errors or unexpected results.

It is recommended to run the cells sequentially, from top to bottom, ensuring that dependencies are met and that the notebook functions as intended.

#### Restarting the kernel
If you encounter errors or want to start fresh, you can restart the kernel. This will clear all variables and outputs, allowing you to run the notebook from the beginning.

To restart the kernel, go to the "Kernel" menu and select "Restart". After restarting, you will need to run the cells again in order to execute the code and generate outputs.



