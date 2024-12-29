# ISCN-UsingTransformerNetworks

## Introduction

This repository provides the code and instructions needed to reproduce the results presented in the paper  
*"Comprehensive Analysis of Transformer Networks in Identifying Informative Sentences Containing Customer Needs"*  
(currently under review at *Expert Systems With Applications*).

The study focuses on using Transformer-based architectures to identify sentences containing customer needs (informative sentences) from Amazon product reviews. Experiments are conducted across five Amazon product domains at the sentence level:  
- **Oral-Care Products**  
- **Electronics**  
- **Sport & Outdoors**  
- **Baby**  
- **Pet Supplies**  

The research evaluates the generalization capabilities of these models across domains, shedding light on their strengths and limitations. By employing various experimental setups, it addresses critical challenges in adopting Transformer-based models for customer needs analysis, including task complexity and the effective handling of diverse datasets.


## Repository Structure
- `Notebooks/`
  - This directory contains four Colab notebooks, each corresponding to a specific experiment presented in the study. The results of these experiments are associated with the following:
    - **Table 3:** [Notebook link or name]
    - **Figure 4:** [Notebook link or name]
    - **Figure 7:** [Notebook link or name]
    - **Table 5:** [Notebook link or name]
- `README.md`: This file explains the repository structure and usage.

## Data Access
To reproduce the results, the following datasets are required:

1. **Oral-Care Products Dataset**: Instructions for accessing this dataset are provided in the paper.
2. **Other Domains**: These datasets are available on their respective GitHub pages:
https://github.com/SvenStahlmann/HICSS-2023-Benchmarking-Machine-Learning-Models-for-Need-Identification/

Please ensure that you comply with the licensing and terms of use for each dataset and cite the relevant publications if you use these data.

## Experimental Setup
All experiments were conducted in a Google Colab environment with the following configurations:
- **GPU**: NVIDIA A100
- **RAM**: 40 GB
  
**Important**: Using a different GPU or settings may affect the results.

## Usage Instructions
1. Clone the repository:
   git clone https://github.com/mehrshad-kashi/ISCN-UsingTransformerNetworks.git
3. Navigate to the `Notebooks` folder and open the desired Colab notebook.
4. Follow the instructions in the notebook to reproduce the results.

**Note**: Ensure you have access to the required datasets before running the experiments.

## Results
The key findings of this study are summarized below:
- **Table 3**: Performance comparison of models on the Oral-Care dataset.
- **Table 4**: Assessment of model generalizability based on semantical appearance levels of samples during training.
- **Figure 4**: Robustness analysis of models against unseen, informative samples in the Oral-Care dataset.
- **Figure 7**: Sample efficiency of models across all datasets.
- **Table 5**: In-domain and cross-domain classification results across all datasets.

For a detailed discussion of the results, please refer to the [paper](#).

## License
This repository's code is licensed under the [MIT License](LICENSE). 

**Note**: The datasets used in this study are not included in this repository. If you plan to use these datasets, please ensure compliance with their respective licenses and terms of use.  
