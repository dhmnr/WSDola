# PhiDola
This repository hosts the code for Phi model implementation for the Dola paper

![GitHub last commit](https://img.shields.io/github/last-commit/username/reponame)
![GitHub issues](https://img.shields.io/github/issues-raw/username/reponame)
![GitHub stars](https://img.shields.io/github/stars/username/reponame?style=social)
![License](https://img.shields.io/badge/license-MIT-green)

## Details

The goal of this project is to assess and enhance the performance of Microsoft's Phi-2 language model on the TruthfulQA task by implementing the a contrasting decoding method which through Jensen-Shannon Divergence of intermediate decoder block outputs, improves the truthfulness of LLM generated text responses. This repository contains all necessary code and documentation to replicate the results. With a straightforward implementation, we achieve a ~9% increase in the TruthfulQA benchmark.

## Installation

To set up this project, clone the repo and install required dependencies:

```bash
git clone https://github.com/username/reponame.git
cd reponame
pip install -r requirements.txt
