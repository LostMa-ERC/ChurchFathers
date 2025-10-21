This repository is associated with the paper "Transmission and Survival of Iberian Patristic Texts," published in the CHR 2025 conference.

## About This Project

This project contains the data, experimental notebooks (Jupyter Notebooks), and results used for the analysis presented in the aforementioned paper. The primary goal is to study the transmission and survival of Iberian patristic texts using computational methods.

### Repository Structure

The repository is organized as follows:

  - `/data`: Contains the raw or processed datasets used for the experiments.
  - `/figs`: Contains the figures and plots generated for the paper.
  - `/posteriors/hybridBD`: Contains the posterior distributions from the models
  - `/results_BD`: Contains the final results of the analyses.
  - `CHR_experiments_all.ipynb`: Jupyter Notebook containing the experiments conducted for prose and poetry combined.
  - `CHR_experiments_prose.ipynb`: Jupyter Notebook focusing on experiments related to prose.
  - `config_church_fathers.yml`: Configuration used to generate the posterior in posteriors/hybridBD.
  - `config_church_fathers_pretrained.yml`: Configuration file using pre-trained models.

### Dependencies

The code necessitates `python <3.13,>=3.11` and the dependencies can be installed
 in a virtual environment of you choice, by doing:

```bash
# Optional: using virtual env
python3.12 -m venv env
source env/bin/activate
# install
pip install -r requirements.txt
```

The notebooks can then be run with:

```bash
jupyter lab
```

### Acknowledgements

Funded by the European Union (ERC, LostMA, 101117408). 
Views and opinions expressed are however those of the author(s) only and do not necessarily reflect those of the European Union or the European Research Council. 
Neither the European Union nor the granting authority can be held responsible for them.
