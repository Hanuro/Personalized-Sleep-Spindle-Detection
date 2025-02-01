# Personalized Sleep Spindle Detection

**Authors**: Ivan Duvnjak, Enkh-Oyu Nomin, Oleg Lastocichin

## Overview

This project focuses on the personalized detection of sleep spindles in whole-night polysomnography recordings. Sleep spindles are bursts of oscillatory brain activity visible on an EEG that are important for various aspects of sleep analysis.

## Dataset

The project utilizes the DREAMS database, which can be accessed [here](https://zenodo.org/record/2650146).

## Repository Structure

- `database/`: Contains the dataset used for training and evaluation.
- `final_project.ipynb`: Jupyter Notebook detailing the data analysis, model development, and results.
- `README.md`: Project documentation.
- `.gitignore`: Specifies files to ignore in the repository.
- `.gitattributes`: Attributes for the repository.
- `License.txt`: License information for the project.

## Getting Started

To get started with this project:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/Hanuro/Personalized-Sleep-Spindle-Detection.git
   cd Personalized-Sleep-Spindle-Detection
   ```

2. **Install dependencies**:
   Ensure you have Python installed. Install the required packages using:
   ```bash
   pip install -r requirements.txt
   ```
   *(Note: The `requirements.txt` file is assumed to list all necessary packages.)*

3. **Run the Jupyter Notebook**:
   Launch the notebook to explore the analysis and results:
   ```bash
   jupyter notebook final_project.ipynb
   ```

## Results

Detailed results, including performance metrics and visualizations, are available in the `final_project.ipynb` notebook.

## License

This project is licensed under the terms specified in the `License.txt` file.
