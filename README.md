<img src="ANL_RGB-01.png" alt="thumbnail" width="300"/>

# (Hyperlocal Precipitation Observations) Cookbook

[![nightly-build](https://github.com/EVS-ATMOS/hyperlocal-observations/actions/workflows/nightly-build.yaml/badge.svg)](https://github.com/EVS-ATMOS/hyperlocal-observations/actions/workflows/nightly-build.yaml)

This Project Pythia Cookbook covers working with precipitation data transmitted via LoRaWAN. 

## Motivation

The spatial scale of preciptiation within an urban environment is difficult to observe due to the heteorgenius nature of the environment and phenomenon. 
To accurately observe precipitaiton at the street scale within an urban environment, a distributed network of sensors is needed.

This Summer 2024 Student Undergraduate Laboratory Internship (SULI) project aims to update the Community Research on Climate and Urban Science (CROCUS) in-situ 
instrumentation to transmit via the LoRaWAN protocol, a Low Power Wide Area Networking communication protocol that functions on LoRa to allow for the capability
to transmit data over a dense local network. 

## Authors

[First Author](@first-author), [Second Author](@second-author), etc. _Acknowledge primary content authors here_

### Contributors

<a href="https://github.com/EVS-ATMOS/hyperlocal-observations/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=EVS-ATMOS/hyperlocal-observations" />
</a>

## Structure

### Section 1 ( Replace with the title of this section, e.g. "Foundations" )

(Add content for this section, e.g., "The foundational content includes ... ")

### Section 2 ( Replace with the title of this section, e.g. "Example workflows" )

(Add content for this section, e.g., "Example workflows include ... ")

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
Jupyter](https://foundations.projectpythia.org/foundations/getting-started-jupyter.html).

### Running on Your Own Machine

If you are interested in running this material locally on your computer, you will need to follow this workflow:

(Replace "cookbook-example" with the title of your cookbooks)

1. Clone the `https://github.com/EVS-ATMOS/hyperlocal-observations.git` repository:

   ```bash
    git clone https://github.com/EVS-ATMOS/hyperlocal-observations.git
   ```

1. Move into the `hyperlocal-observations` directory
   ```bash
   cd hyperlocal-observations
   ```
1. Create and activate your conda environment from the `environment.yml` file
   ```bash
   conda env create -f environment.yml
   conda activate hyperlocal-obs-dev
   ```
1. Move into the `notebooks` directory and start up Jupyterlab
   ```bash
   cd notebooks/
   jupyter lab
   ```
