
# Cross-Domain Named Entity Recognition: Enhancing Transfer Learning with Span-level Masking

## Overview
This project explores CrossNER, a specialized framework for Named Entity Recognition (NER) that adapts NER systems to different domains, especially when labeled data is scarce. Developed by Alain Chirino Trujillo under the guidance of Anna Feldman at Montclair State University, this project leverages domain-adaptive pre-training (DAPT) and various fine-tuning methods to improve performance across diverse domains.

## Project Structure
The project is structured around several Jupyter notebooks, each focusing on different aspects of the NER system development:

- **Base_Line.ipynb:** Establishes a baseline model for NER across different domains.
- **DAPT_Span_Level_Masking.ipynb:** Implements DAPT with span-level masking to enhance domain adaptivity.
- **Direct_Fine_Tuning.ipynb:** Applies direct fine-tuning techniques to improve model performance.
- **Level_Corpora_Create.ipynb:** Handles the creation of corpora for DAPT.
- **Validate_&_Test_|_Direct_Fine_Tuning.ipynb:** Conducts validation and testing of the fine-tuned models.

## Dataset
The dataset used in this project includes five distinct domains: Politics, Science, AI, Music, and Literature. Each domain's dataset is used to train, validate, and test the effectiveness of the CrossNER system. The data, sourced from Medium using the Beautiful Soup scraper, comprises articles that collectively represent a rich corpus for training and evaluation.

## Models and Techniques
The project utilizes a BERT-based model architecture, leveraging techniques such as:
- **Domain-Adaptive Pre-Training (DAPT):** Focuses on learning domain-specific features.
- **Span-Level Masking:** Enhances model understanding of context within and around spans of text.
- **Direct Fine-Tuning:** Adjusts model parameters specifically for NER tasks across different domains.

## Results
The project's findings demonstrate that the CrossNER framework, equipped with DAPT and fine-tuning techniques, significantly outperforms baseline models. This is evident in the improved F1 scores and precision in entity recognition across varied domains.

## How to Use
To replicate or extend the experiments:
1. Clone the repository and navigate to the respective notebook.
2. Ensure all dependencies are installed and the runtime environment (e.g., Google Colab, Jupyter) is correctly set up.
3. Run the notebooks in sequence to train and evaluate the models.

## Dependencies
- Python 3.x
- Jupyter Notebook or Google Colab
- PyTorch
- Transformers
- Beautiful Soup for data scraping

## Citation
If you use the contents of this project or the CrossNER framework in your research, please cite:

## Contact
For any queries regarding the project, contact Alain Chirino Trujillo at chirinotruja1@montclair.edu

