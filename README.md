# MetPy Cookbook

<div class="row">
   <div class="column">
      <img src="_static/NSF-Unidata_lockup_horizontal_2023_light.png" alt="NSF-Unidata Logo" width="35%"/>
   </div>
   <div class="column">
      <img src="_static/metpy_150x150.png" alt="MetPy Logo" width="35%"/>
   </div>
</div>

[![nightly-build](https://github.com/ProjectPythia/metpy-cookbook/actions/workflows/nightly-build.yaml/badge.svg)](https://github.com/ProjectPythia/metpy-cookbook/actions/workflows/nightly-build.yaml)
[![Binder](http://binder.projectpythia.org/badge_logo.svg)](http://binder.projectpythia.org/v2/gh/ProjectPythia/metpy-cookbook/main?labpath=notebooks)
[![DOI](https://zenodo.org/badge/620944317.svg)](https://zenodo.org/badge/latestdoi/620944317)

This Cookbook is the oversized recipe book for all your MetPy needs.
We provide a gallery of real workflows centered around meteorological data,
and the building blocks you need to recreate those workflows or cook up brand new ones yourself.
Create the maps and analyses you've seen from class and professional institutions alike!

## Authors

MetPy Maintainers and the MetPy Community.

### Contributors

<a href="https://github.com/ProjectPythia/metpy-cookbook/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=ProjectPythia/metpy-cookbook" />
</a>

## Structure

### The MetPy Example Gallery

## Running the Notebooks

You can either run the notebook using [Binder](https://mybinder.org/) or on your local machine.

### Running on Binder

The simplest way to interact with a Jupyter Notebook is through
[Binder](https://mybinder.org/), which enables the execution of a
[Jupyter Book](https://jupyterbook.org) in the cloud. The details of how this works are not
important for now. All you need to know is how to launch a Pythia
Cookbooks chapter via Binder. Simply navigate your mouse to
the top right corner of the book chapter you are viewing and click
on the rocket ship icon, (see figure below), and be sure to select
“launch Binder”. After a moment you should be presented with a
notebook that you can interact with. I.e. you’ll be able to execute
and even change the example programs. You’ll see that the code cells
have no output at first, until you execute them by pressing
{kbd}`Shift`\+{kbd}`Enter`. Complete details on how to interact with
a live Jupyter notebook are described in [Getting Started with
Jupyter](https://foundations.projectpythia.org/foundations/getting-started-jupyter).

### Running on Your Own Machine

If you are interested in running this material locally on your computer, you will need to follow this workflow:

1. Clone the `https://github.com/ProjectPythia/metpy-cookbook` repository:

   ```bash
    git clone https://github.com/ProjectPythia/metpy-cookbook.git
   ```

1. Move into the `metpy-cookbook` directory
   ```bash
   cd metpy-cookbook
   ```
1. Create and activate your conda environment from the `environment.yml` file
   ```bash
   conda env create -f environment.yml
   conda activate metpy-cookbook
   ```
1. Move into the `notebooks` directory and start up Jupyter Lab
   ```bash
   cd notebooks/
   jupyter lab
   ```
