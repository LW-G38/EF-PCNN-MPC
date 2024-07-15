# EF-PCNN-MPC

This repository contains the code for the paper "Energy flexibility quantification of a tropical net-zero office building using physically consistent neural network-based model predictive control."

This repository comprises a modified version of Physically Consistent Neural Networks (PCNNs) and associated MPC framework curated for the SDE4 Building at the National University of Singapore.

## Installation
After cloning the repository on your computer, go to the pcnn folder with `cd path_to_the_folder/pcnn`.  

The fastest way to run the code is to use `poetry`, which can be installed from [here](https://python-poetry.org/docs/#installation).  
You can then run `poetry install` to install all the required dependencies.  
Once the dependencies are installed, you can for example run jupyter-lab with `poetry run jupiter lab` or VS code with `poetry run code .`.

Alternatively, you can install requirements from `requirements.txt`.

## Citation
If you find this repo useful, please consider citing the following paper:

```bibtex
@article{liang2024energy,
  title={Energy flexibility quantification of a tropical net-zero office building using physically consistent neural network-based model predictive control},
  author={Liang, Wei and Li, Han and Zhan, Sicheng and Chong, Adrian and Hong, Tianzhen},
  journal={Advances in Applied Energy},
  volume={14},
  pages={100167},
  year={2024},
  publisher={Elsevier},
  issn = {2666-7924},
  doi = {https://doi.org/10.1016/j.adapen.2024.100167},
  url = {https://www.sciencedirect.com/science/article/pii/S2666792424000052},
}
```

To cite the original PCNN models, please see this repo: https://github.com/Cemempamoi/pcnn

## Contact
For additional information, please contact weiliang@andrew.cmu.edu
