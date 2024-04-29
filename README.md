# PhiDola
This repository hosts the code for Phi model implementation for the Dola paper

![GitHub last commit](https://img.shields.io/github/last-commit/dhmnr/PhiDola)
![GitHub issues](https://img.shields.io/github/issues-raw/dhmnr/PhiDola)
![GitHub stars](https://img.shields.io/github/stars/dhmnr/PhiDola?style=social)
![License](https://img.shields.io/badge/license-MIT-green)

## Details

The goal of this project is to assess and enhance the performance of Microsoft's Phi-2 language model on the TruthfulQA task by implementing the Dola method. A contrasting decoding method which improves the truthfulness of LLM generated text responses. This method relies on the fact that transformer LMs have been loosely shown to encode “lower-level” information (e.g., part-of-speech tags) in the earlier layers, and more “semantic” information in the later layers. 
This repository contains all necessary code and documentation to replicate the results. With a simple implementation, we achieve a ~9% increase in the TruthfulQA benchmark.


<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!


1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request



<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE` for more information.




<!-- CONTACT -->
## Contact

Dheemanth Manur - dheemanthmanur72@gmail.com

<!-- [@twitter_handle](https://twitter.com/twitter_handle) -->





<!-- ACKNOWLEDGMENTS -->
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
