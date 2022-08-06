# Cancer survival prediction and integration of multi-omics integration with Supervised Autoencoders, Stacked Autoencoders and Concrete Supervised Autoencoders for multiple correlated driver genes

 _Performance of multi-omics measurements and prediction for cancer survival integrating harmonized RNA sequencing from the ROSMAP cohort using supervised autoencoders with paralledged generative adversarial networks (GAN) based manifold omics analysis without priors. The most significant parameter during cancer therapy is survival analysis for revealing clinically significant biomarkers to stratify biological agents. Supervised encoders could facilitate accurate diagnosis of complex diseases and survival progression at multiple genetic levels. Multi-stage dimensionality based models may scale up time execution in comparison to state-of-the-art alternatives._


## Table of Contents

- [Content](#Content)
    - [Background](#Background)
    - [Data](#data)
    - [Usage](#usage)
        - [Installation](#installation)
        - [Requirements](#requirements)
    - [Results](#results)
    - [Team Members](#team-members)

## Background
Breast cancer is the second most common cancer among women in the United States. Breast cancer is highly heterogeneous, composed of different subtypes, with different clinical, pathological, and molecular characteristics, as well as prognostic and therapeutic significance. Considering the significant variance in breast cancer outcomes, it is important to accurately predict the survival and prognosis of the breast cancer patients. Prediction of survival or prognosis can facilitate precision medicine of breast cancer. Many deep learning methods have been proposed to cancer prognosis prediction using genomic information, but most of them focus on a single-layer of omics data, where gene expression (mRNA) is most commonly used. Currently, there are some existing tools using autoencoders to intergrate multi-omics data for cancer prognosis prediction. Our team aims to compare these existing algorisms and advance and optimize the methods for better utilities [1].

[1] Chai, H., Zhou, X., Zhang, Z., Rao, J., Zhao, H., & Yang, Y. (2021). Integrating multi-omics data through deep learning for accurate cancer prognosis prediction. Computers in biology and medicine, 134, 104481.

## Framework and workflow

![Workflow](https://github.com/u-brite/team_papaki/blob/main/Pipeline%20Workflow.png)

## Data

The breast cancer datasets are publicly available on the Cancer Genome Atlas (TCGA) (https://tcga-data.nci.nih.gov/tcga/). The datasets could be downloaded through the R package “TCGAassembler 2” v2.0.6. The datasets contained four types of multi-omics data: mRNA, miRNA, DNA methylation, and copy number variation.

## Usage

Feel free to take a look at the jupyter notebook and the instructions of forked repositories.

### Requirements

All the requirements for python scripts are located in `requirements.txt` file.

Has been tested in Linux (ubuntu) and Windows 11.

*Tools:*

- Python
- Jupyter Notebooks
- R 
- DeepProg package
- DCAP autoencoders

## Results
:exclamation: _If your project yielded or intends to yield some novel analysis, please include them in your readme. It can be named something other than results as well._ :exclamation:

## Team Members

- Vasileios Alevizos | vasileios.alevizos@ki.se | Karolinska Institutet, iKnowHow valevizos@iknowhow.com | Team Leader
- Vanessa Xiao | vzxiao@mit.edu | MIT | Team Member
- Yishu Qu | YishuQu2024@u.northwestern.edu | Northwestern University | Team Member
- Alexus Acton | actonam@uab.edu | UAB | Team Member
- Zongliang Yue | zongyue@uab.edu | UAB | Team Member
