# Efficient Continuous Pareto Exploration in Multi-Task Learning (ICML 2020)

## Recommended Configuration
- Ubuntu 18.04 or higher;
- conda 4.8 or higher.

## Installation
We will use `$ROOT` to refer to the root folder of this project, i.e., the folder that contains this `README` file.
After downloading the source code, navigate to the root folder and create a conda environment:
```
cd $ROOT
conda env create -f environment.yml
conda activate cpmtl
```

## Examples
Open up a terminal to launch Jupyter:
```
jupyter notebook
```
You can run the following Jupyter script to reproduce figures in the paper:
```
fig2.ipynb
fig3.ipynb
fig4.ipynb
fig5_multimnist.ipynb
fig5_uci.ipynb
```

## Contact
If you have any questions about the paper or the codebase, please feel free to contact pcma@csail.mit.edu or taodu@csail.mit.edu.

## Citation
```
@inproceedings{icml2020_ma,
    title={Efficient Continuous Pareto Exploration in Multi-Task Learning},
    author={Ma, Pingchuan and Du, Tao and Matusik, Wojciech},
    booktitle={International Conference on Machine Learning},
    year={2020},
}
```
