# Chemoinformatics Tutorials: Generative Models with SELFIES and RNN

This repository contains a collection of Jupyter notebooks and resources for building generative models for molecules using SELFIES and recurrent neural networks (RNNs), with a focus on applications in chemoinformatics and drug discovery.

## Features
- Data loading and preprocessing for molecular datasets
- Conversion between SMILES and SELFIES representations
- Building and training LSTM-based autoencoders in Keras
- Visualization of latent spaces and chemical properties
- Example notebooks for end-to-end workflows

## Repository Structure
- `notebooks/` — Jupyter notebooks for each tutorial (move your `.ipynb` files here for better organization)
- `databases/` — Molecular datasets (SMILES, SDF, CSV)
- `models/` — Saved model weights and pickles
- `images/` — Figures and plots
- `logs/` — Training logs

## Getting Started
1. **Clone the repository:**
   ```bash
   git clone https://github.com/Aouidate/Chemoinformatics-tutos.git
   cd Chemoinformatics-tutos
   ```
2. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```
3. **Launch Jupyter Notebook:**
   ```bash
   jupyter notebook
   ```
4. **Open a notebook and follow the instructions.**

## Example Notebooks
- `ADN_T014_Selfies_based_AE_Generative_model.ipynb`: Main tutorial for building a generative model using SELFIES and LSTM.

## Data Sources
- Datasets are provided in the `databases/` folder. Please cite original sources if you use them in publications.

## Contributing
See [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.

## License
This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.

## Author
Adnane Aouidate

---
For questions or suggestions, please open an issue or submit a pull request.
