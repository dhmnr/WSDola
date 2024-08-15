![GitHub last commit](https://img.shields.io/github/last-commit/dhmnr/PhiDola)
![GitHub issues](https://img.shields.io/github/issues-raw/dhmnr/PhiDola)
![GitHub stars](https://img.shields.io/github/stars/dhmnr/PhiDola?style=social)
![License](https://img.shields.io/badge/license-MIT-green)

# WSDola
This repository hosts the code for Phi model implementation for the [Dola paper](https://arxiv.org/abs/2309.03883) and the weighted sum extension of the DOLA method 

## Details

The goal of this project is to assess and enhance the performance of language model on the TruthfulQA task by implementing the Dola method. We also present an extension of this method, where we use weighted combination of hidden logits. Dola is contrasting decoding method which improves the truthfulness of LLM generated text responses. This method relies on the fact that transformer LMs have been loosely shown to encode “lower-level” information (e.g., part-of-speech tags) in the earlier layers, and more “semantic” information in the later layers. 
This repository contains all necessary code and documentation to replicate the results. 

## References
```
@misc{chuang2024dola,
      title={DoLa: Decoding by Contrasting Layers Improves Factuality in Large Language Models}, 
      author={Yung-Sung Chuang and Yujia Xie and Hongyin Luo and Yoon Kim and James Glass and Pengcheng He},
      year={2024},
      eprint={2309.03883},
      archivePrefix={arXiv},
      primaryClass={cs.CL}
}
```
