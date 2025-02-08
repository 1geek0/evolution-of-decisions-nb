# Evolution of Decision

This project explores the evolution of decision-making processes in clinical settings, particularly focusing on the management of meningiomas. It utilizes machine learning models and clinical decision support systems to generate clinical notes and visualize decision trees.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Contributing](#contributing)

## Installation

To set up the project, ensure you have [Conda](https://docs.conda.io/en/latest/miniconda.html) installed. Then, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/1geek0/evolution-of-decision-nb.git
   cd evolution-of-decision-nb
   ```

2. Create a new Conda environment and install the required packages:
   ```bash
   conda create --name evolution-of-decision-nb python=3.11
   conda activate evolution-of-decision-nb
   conda install numpy pandas
   pip install anthropic
   ```

3. Ensure you have the necessary API key for Anthropic:
   - Set the `ANTHROPIC_API_KEY` environment variable with your API key.

## Usage

1. Open the Jupyter Notebook:
   ```bash
   jupyter notebook evolution_of_decision.ipynb
   ```

2. Follow the instructions in the notebook to run the analyses and generate clinical notes and decision trees.

## Project Structure

- `evolution_of_decision.ipynb`: Main Jupyter Notebook containing the code for generating clinical notes and decision trees.
- `profiles_with_prompts.csv`: CSV file containing patient profiles used in the analysis.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request for any improvements or bug fixes.