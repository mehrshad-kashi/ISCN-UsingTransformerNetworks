# ISCN-UsingTransformerNetworks

## Introduction
This repository contains the code and instructions to reproduce the results presented in the paper 
*"Comprehensive Analysis of Transformer Networks in Identifying Informative Sentences Containing Customer Needs"* 
(currently under review at *Expert Systems With Applications* journal).

The study focuses on using Transformer-based architectures to identify informative sentences that capture customer needs from Amazon product reviews. The experiments are conducted across five distinct Amazon product domain reviews:
- Oral-Care Products
- Electronics
- Sport & Outdoors
- Baby Products
- Books

The research evaluates these models' ability to generalize across domains, highlighting their strengths and limitations. Through various experimental setups, it addresses key challenges in adopting Transformer-based models for customer needs analysis, such as task complexity and handling diverse datasets effectively.

## Repository Structure
- `Notebooks/`
  - Contains three Colab notebooks, each corresponding to a specific experiment in the study:
    - **Table 3 Experiment:** [Notebook link or name]
    - **Figure 4 Experiment:** [Notebook link or name]
    - **Table 5 Experiment:** [Notebook link or name]
- `README.md`: This file explains the repository structure and usage.

## Data Access
To reproduce the results, the following datasets are required:

1. **Oral-Care Products Dataset**: Instructions for accessing this dataset are provided in the paper.
2. **Other Domains (Electronics, Sport & Outdoors, Baby, Books)**: These datasets are available on their respective GitHub pages:
https://github.com/SvenStahlmann/HICSS-2023-Benchmarking-Machine-Learning-Models-for-Need-Identification/

Please ensure you comply with the licensing and terms of use for each dataset.

## Experimental Setup
All experiments were conducted in a Google Colab environment with the following configurations:
- **GPU**: NVIDIA A100
- **RAM**: 40 GB

## Usage Instructions
1. Clone the repository:
   git clone https://github.com/github.com/mehrshad-kashi/ISCN-UsingTransformerNetworks.git
3. Navigate to the `Notebooks` folder and open the desired Colab notebook.
4. Follow the instructions in the notebook to reproduce the results.

**Note**: Ensure you have access to the required datasets before running the experiments.

## Results
The key findings of this study are summarized in:
- **Table 3**: Performance comparison of models across domains.
- **Figure 4**: Visualization of model performance trends.
- **Table 5**: Analysis of the impact of various hyperparameters.

For detailed results and discussions, please refer to the paper.

## License
This code is licensed under the [MIT License](LICENSE). 

**Disclaimer**: The datasets used in this study are not included in this repository. Please ensure you comply with their respective licenses and terms of use.
