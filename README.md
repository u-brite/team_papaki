# Cancer survival prediction and integration of multi-omics integration with Supervised Autoencoders, Stacked Autoencoders and Concrete Supervised Autoencoders for multiple correlated driver genes

:exclamation: _This top heading should be the name of your project i.e. BiocSwirl or SNVariome. Anything between 2 exclamation marks is intended to be deleted. Any content that isn't a heading or an optional heading can be deleted as well. The structure of this readme is open to any creative changes, but the main components of Background/Data/Usage/Team Members should remain. You're free to add images and get creative about how you want your readme to look._ :exclamation:

:exclamation: _The `configs` and `notebooks` directories are also optional. We recommend taking a look at [cookiecutter for datascience](https://github.com/drivendata/cookiecutter-data-science) or [cookiecutter for computational biology](https://github.com/drivendata/cookiecutter-data-science) to get ideas on structuring your projects. Also, use a `.gitignore` that fits the main programming language of your project._ :exclamation:

## Table of Contents

- [Template](#team-repo-template)
    - [Background](#Background)
    - [Data](#data)
    - [Usage](#usage)
        - [Installation](#installation)
        - [Requirements](#requirements) _Can be named Dependencies as well_
        - [Activate conda environment](#activate-conda-environment) _Optional_
        - [Steps to run ](#steps-to-run) _Optional depending on project_
            - [Step-1](#step-1)
            - [Step-2](#step-2)
    - [Results](#results) _Optional depending on project_
    - [Team Members](#team-members)

## Background
Breast cancer is the second most common cancer among women in the United States. Breast cancer is highly heterogeneous, composed of different subtypes, with different clinical, pathological, and molecular characteristics, as well as prognostic and therapeutic significance. Considering the significant variance in breast cancer outcomes, it is important to accurately predict the survival and prognosis of the breast cancer patients. Prediction of survival or prognosis can facilitate precision medicine of breast cancer. Many deep learning methods have been proposed to cancer prognosis prediction using genomic information, but most of them focus on a single-layer of omics data, where gene expression (mRNA) is most commonly used. Currently, there are some existing tools using autoencoders to intergrate multi-omics data for cancer prognosis prediction. Our team aims to compare these existing algorisms and advance and optimize the methods for better utilities. 

## Framework and workflow

![Workflow](https://github.com/u-brite/team_papaki/blob/main/Pipeline%20Workflow.png)

## Data

The datasets are freely available on https://tcga-data.nci.nih.gov/.

## Usage

:exclamation: _How will someone not involved in your project be able to run the code or use it._ :exclamation:

### Installation

:exclamation: _If installation is required, please mention how to do so here._ :exclamation:

Installation simply requires fetching the source code. Following are required:

- Git

To fetch source code, change in to directory of your choice and run:

```sh
git clone -b main \
    git@github.com:u-brite/team-repo-template.git
```

### Requirements

All the requirements for python scripts are located in `requirements.txt` file.

Has been tested in Linux (ubuntu) and Windows 11.

Currently works only in Linux OS. Docker versions may need to be explored later to make it useable in Mac (and
potentially Windows).

*Tools:*

- Python
- Jupyter Notebooks
- R 
- DeepProg package
- DCAP autoencoders

### Activate conda environment
:exclamation: _Optional: Depends on project._ :exclamation:

Change in to root directory and run the commands below:

```sh
# create conda environment. Needed only the first time.
conda env create --file configs/environment.yaml

# if you need to update existing environment
conda env update --file configs/environment.yaml

# activate conda environment
conda activate testing
```

### Steps to run
:exclamation: _Optional: Depends on project._ :exclamation:

#### Step 1

```sh
python src/data_prep.py -i path/to/file.tsv -O path/to/output_directory
```

#### Step 2

```sh
python src/model.py -i path/to/parsed_file.tsv -O path/to/output_directory
```

Output from this step includes -

```directory
output_directory/
├── parsed_file.tsv               <--- used for model
├── plot.pdf- Plot to visualize data
└── columns.csv - columns before and after filtering step

```

**Note**: The is an example note with a [link](https://github.com/u-brite/team-repo-template).


## Results
:exclamation: _If your project yielded or intends to yield some novel analysis, please include them in your readme. It can be named something other than results as well._ :exclamation:

## Team Members

- Vasileios Alevizos | vasileios.alevizos@ki.se | Karolinska Institutet, iKnowHow valevizos@iknowhow.com | Team Leader
- Vanessa Xiao | vzxiao@mit.edu | MIT | Team Member
- Yishu Qu | YishuQu2024@u.northwestern.edu | Northwestern University | Team Member
- Alexus Acton | actonam@uab.edu | UAB | Team Member
- Zongliang Yue | zongyue@uab.edu | UAB | Team Member
