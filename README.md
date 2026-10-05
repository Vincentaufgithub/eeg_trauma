# eeg_trauma
This pipeline provides multiple functionalities for cleaning and analyzing EEG-data. Specifically, it is used to apply Machine Learning for classification of trauma-related studies. We are using the datasets of (Chouinard-Gaouette & Blanchette, 2025) and (Leblanc-Sirois et al., 2021). For protection of privacy, the data is not available on this git. (We might include a sample tho?)


## setup instructions
To reproduce the environment used in this project, install [Miniconda](https://docs.conda.io/en/latest/miniconda.html) or [Anaconda](https://www.anaconda.com/) if you haven’t already.

Then, create the environment using the provided `environment.yml` file:

```bash
conda env create -f environment.yml
conda activate eeg_ml_env
