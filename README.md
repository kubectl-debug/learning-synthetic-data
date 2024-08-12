# Learning Synthetic Data Generation

This project focuses on synthetic data generation techniques across two key domains: Credit and Insurance. The goal is to create high-quality synthetic datasets that can be used for various purposes, including machine learning model training.

## Table of Contents
- [Introduction](#introduction)
- [Installation](#installation)
- [Usage](#usage)
- [Credit Domain](#credit-domain)
  - [Overview](#overview)
  - [Data Generation Techniques](#data-generation-techniques)
- [Insurance Domain](#insurance-domain)
  - [Overview](#overview)
- [Contributing](#contributing)
- [License](#license)

## Introduction
Synthetic data generation is a powerful tool that allows the creation of artificial datasets that retain the statistical properties of real-world data while preserving privacy and enabling the testing of models and algorithms. This project explores synthetic data generation in the domains of credit and insurance.

## Usage
This is an educational project. Code is organized in notebooks. We use the Kaggle dataset [`parisrohan/credit-score-classification`](https://www.kaggle.com/datasets/parisrohan/credit-score-classification). To download the dataset, please export the following environmental variables in the `.env`, located in the root of the project:
```bash
KAGGLE_USERNAME=<Kaggle Username>
KAGGLE_KEY=<Kaggle API Key>
```

## Credit Domain
### Overview
In the credit domain, synthetic data is generated to simulate various credit scenarios. This includes data related to credit scoring, loan applications, and customer credit behavior. In the credit scoring context, a common problem is the unbalance of the classes (i.e. the instances of default individuals are only a minority percentage compared to _in bonis_ positions in the dataset). The project's goal is to generate syntethic data for such use case, in order to mitigate the class imbalance.

### Data Generation Techinques
The techniques used in the credit domain include:

- **GANs (Generative Adversarial Networks)**: Used to generate realistic credit profiles and transaction histories.
- **Variational Autoencoders (VAEs)**: Employed to create diverse synthetic datasets that retain the statistical properties of the original data.
- **Random Sampling and Perturbation**: Simple yet effective methods to create variations in the data while preserving key characteristics.

In this project we use GANs.

## Insurance Domain
### Overview
TODO

## Contributing
Contributions to this project are welcome! Please fork the repository and submit a pull request with your changes. Ensure your code adheres to the project's coding standards and is well-documented.

