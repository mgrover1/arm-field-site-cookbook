# ARM Field Site Cookbook

<img src="images/arm_logo.png" alt="thumbnail" width="300"/>

[![nightly-build](https://github.com/ProjectPythia/arm-field-site-cookbook/actions/workflows/nightly-build.yaml/badge.svg)](https://github.com/ProjectPythia/arm-field-site-cookbook/actions/workflows/nightly-build.yaml)
[![Binder](https://binder.projectpythia.org/badge_logo.svg)](https://binder.projectpythia.org/v2/gh/ProjectPythia/arm-field-site-cookbook/main?labpath=notebooks)
[![DOI](https://zenodo.org/badge/475509405.svg)](https://zenodo.org/badge/latestdoi/475509405)


This Project Pythia Cookbook covers how to work with ARM Field Campaign datasets, leveraging previous training and outreach event materials.

## Motivation

We consolidate computational workflow training materials from previous summer school and workshop events. There is a foundations section which details the core open-source tools, and a projects section showcasing previous students' workflows with the associated citation information.

## Authors

[Max Grover](https://github.com/mgrover1)

### Contributors

<a href="https://github.com/ProjectPythia/arm-field-site-cookbook/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=ProjectPythia/arm-field-site-cookbook" />
</a>

## Structure

### Foundations

This section is dedicated to the core open-source tools which are used in the associated projects. We also include data access information in this section.

### Projects

Project notebooks from previous training events are included in this section. We apply additional cleaning and reproducibility work that could not be finalized during the week-long events.

## Running the Notebooks

You can either run the notebook using [Binder](https://binder.projectpythia.org/) or on your local machine.

### Running on Binder

The simplest way to interact with a Jupyter Notebook is through
[Binder](https://binder.projectpythia.org/), which enables the execution of a
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

Note, not all Cookbook chapters are executable. If you do not see
the rocket ship icon, such as on this page, you are not viewing an
executable book chapter.


### Running on Your Own Machine

If you are interested in running this material locally on your computer, you will need to follow this workflow:

(Replace "cookbook-example" with the title of your cookbooks)

1. Clone the `https://github.com/ProjectPythia/arm-field-site-cookbook` repository:

   ```bash
    git clone https://github.com/ProjectPythia/arm-field-site-cookbook.git
   ```

1. Move into the `arm-field-site-cookbook` directory
   ```bash
   cd arm-field-site-cookbook
   ```
1. Create and activate your conda environment from the `environment.yml` file
   ```bash
   conda env create -f environment.yml
   conda activate arm-field-site-cookbook-dev
   ```
1. Move into the `foundations` directory and start up Jupyterlab
   ```bash
   cd foundations
   jupyter lab
   ```
