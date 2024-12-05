

# AI47Labs Assignment: Private GPT Model for Hospital Data

## Project Overview

This project is part of the AI47Labs assignment to build a web scraping pipeline and train a Private GPT model. The goal is to scrape data from the top 50 hospital websites, process and clean this data, and train a GPT model to answer questions about doctors, treatments, and departments.

This repository contains:
- A Python script for data scraping, cleaning, and model training.
- The trained Private GPT model (stored in Google Drive).
- A Google Colab notebook for interacting with the model.
- Documentation on using the model and its limitations.

---

## How to Use

### 1. Clone the Repository
```bash
git clone <your-repository-link>
cd <repository-folder>
```

### 2. Access the Google Colab Notebook
1. Open the Colab notebook: [Google Colab Link](<your-shared-notebook-link>).
2. Mount your Google Drive in the notebook to load the pre-trained model.
   - Follow the prompts to grant access to your Google Drive.

### 3. Load and Test the Model
In the Colab notebook:
1. Run the cells to set up the environment and load the model.
2. Provide an input query, such as:
   ```python
   input_text = "What are the specializations of Dr. Naresh Trehan?"
   ```
3. The model will generate a response based on the training data.

---

## Features

- **Web Scraping**: Extracts hospital, doctor, and treatment data from top 50 hospital websites.
- **Data Cleaning**: Prepares raw data for effective GPT model training.
- **Private GPT Model**: Fine-tuned GPT-2 model on healthcare-specific data.
- **Interactive Colab Notebook**: User-friendly interface to test the model.

---

## Limitations

1. **Limited Training Data**: The model is trained on a small dataset scraped from hospital websites. It may:
   - Produce incomplete or irrelevant answers.
   - Repeat input as the output in some cases.

2. **Model Accuracy**: 
   - Since the model is fine-tuned for a short duration, its accuracy might not meet professional-grade standards.
   - Efforts to improve accuracy will be a focus in future versions.

3. **Bias and Hallucinations**: The model might:
   - Generate biased answers based on the data.
   - Provide fabricated or inaccurate responses.

4. **Scope of Responses**:
   - Restricted to the domain of the training data (hospital-specific information).
   - May not handle out-of-scope questions effectively.

---

## Future Improvements

- **Enhanced Data Collection**: Expanding the dataset by including more hospitals and broader information.
- **Longer Training Time**: Improving the accuracy and quality of responses by training the model for extended periods.
- **Model Evaluation**: Incorporating evaluation metrics to measure performance and identify areas for improvement.
- **Response Validation**: Adding filters to reduce incorrect or repetitive outputs.

---

## How to Contribute

Contributions to improve the model's accuracy, expand its dataset, or refine its training process are welcome! Please fork the repository, make your changes, and submit a pull request.

---

## Contact

For questions or feedback, reach out at saiganeshreddygana@gmail.com.

--- 

