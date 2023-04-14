# iPOGS Analysis Project
This repository is intended to contain iPOGS analysis related notebooks that support diagnostics by providing regionally specific analysis.

## iPOGS diagnostics webpage
The iPOGS diagnostics webpage with CVDP diagnostics as well as additional diagnostics can be found at the following link: [https://project.cgd.ucar.edu/projects/iPOGS/](https://project.cgd.ucar.edu/projects/iPOGS/).

## Contributing
Clone this repository to your account, then create your own branch to make changes in:
`git checkout -b <nameofyourbranch>`

## Reproducing the environment
`conda env create -f envs/environment.yml`
`conda activate ipogs`
To use the MOCutils, a user will need to clone the POP_MOC repository (https://github.com/sgyeager/POP_MOC) and install MOCutils by going to the POP_MOC directory and running `pip install -e . --user`.  

## MOCutils
To use the AMOC notebooks, one will also need to install MOCutils as described here: https://github.com/sgyeager/POP_MOC#installing-mocutils-used-in-the-jupyter-notebooks
