# BergNet: Classifying Harvard Dining Hall Food Using Deep Learning

## Overview
BergNet is a deep learning project which classifies food items served at Harvard University’s Annenberg Hall. This project uses a custom, original dataset of images taken from two days at Annenberg Hall and builds neural networks off of it to analyze and recognize a variety of meals, enhancing meal recommendations and food monitoring in the dining industry. 

## Project Structure
The project folder contains the following components:

- **models/**: This directory contains the trained models and related files used for food classification, in Mathematica object format.
  - `trainedEfficientNet.mx`: The trained EfficientNet model.
  - `trainedBergNetNoAug.mx`: The trained BergNet model without data augmentation.
  - `trainedBergNet.mx`: The trained BergNet model with data augmentation.

- **data/**: This folder includes the datasets used for training and testing the models.
  - `train-set.mx`: The training dataset used to train the models.
  - `test-set.mx`: The testing dataset used to evaluate the models.
  - `augmented-train-set.mx`: The training dataset that includes augmented data for better model generalization.
  - **raw-data-wednesday/**: This folder contains the raw food images and labels collected on Wednesday.
  - **raw-data-thursday/**: This folder contains the raw food images and labels collected on Thursday.

- **BergNet-Report.pdf**: A comprehensive report detailing the project methodology, results, and findings.
- **BergNet-Presentation.pdf**: A presentation summarizing the project.
- **BergNet-MathematicaCode.nb**: A Mathematica notebook containing the code used for training and evaluating the models.

## Usage
To get started with the project, follow these steps:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/lindazeng979/BergNet.git
   cd BergNet
   ```

2. **View Reports and Presentations**:
   Open the `BergNet-Report.pdf` and `BergNet-Presentation.pdf` using any PDF viewer to explore the detailed insights into the project and its findings.

3. **Run Mathematica Code**:
   - Ensure you have **Mathematica** installed on your computer.
   - Open the `BergNet-MathematicaCode.nb` notebook in Mathematica.
   - Ensure that the notebook is in the same directory as the `models` and `data` folders.
   - To run the code, click on the "Evaluate" menu and choose "Evaluate Notebook" or use the keyboard shortcut `Shift + Enter` for each selected cell.
   - You can also modify the code and parameters as needed to experiment with the model training and evaluation.
     
## Contact
For any questions or inquiries, please contact:
**Linda Zeng**  
Email: [26lindaz@students.harker.org](mailto:26lindaz@students.harker.org)

## Acknowledgments
Thanks to Harvard University's Pre-College Program for providing the opportunity to explore this project.
 
