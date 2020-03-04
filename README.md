# morphology-benchmark
Code for the paper [_A systematic evaluation of interneuron morphology representations for cell type discrimination_](https://www.biorxiv.org/content/10.1101/591370v2.full).

All data for the publication figures can be found here 

## Reproducing the figures

Make sure the following dependecies are installed:
  `numpy [v1.17.3]`, `pandas[v0.24.0]` , `scipy[v1.3.1]`, `sklearn[v0.21.3]` , `matplotlib [v3.0.3]` and `seaborn[v0.8.1]`

Check out the repository via
`git clone https://github.com/berenslab/morphology-benchmark`. 

Download all data from [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.3696638.svg)](https://doi.org/10.5281/zenodo.3696638) and unpack the folder `data` to the location of the repository.
Now you can run all notebooks to generate the published figures.

## Reproducing the study
Since this study has been implemented using [DataJoint](https://datajoint.io/), it cannot be readily executed. The available notebooks are meant to showcase the processing. The exact code can be found in the folder `schemata`. 
Example code on the computation of density maps, 2D persistence diagrams and morphometric statistics is shown in `ROBUSTNESS ANALYSIS data generation.ipynb`. The computation of all features can be found in the DataJoint tables `schema.density`, `schema.morphometry` and `schema.persistence`.  

## Cite the paper ##
```
@article{laturnus2019systematic,
  title={A systematic evaluation of interneuron morphology representations for cell type discrimination},
  author={Laturnus, Sophie and Kobak, Dmitry and Berens, Philipp},
  journal={bioRxiv},
  pages={591370},
  year={2019},
  publisher={Cold Spring Harbor Laboratory}
}
```
