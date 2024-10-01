# Text Summarization Project 📝

Welcome to the **Text-Summarization** repository! This project aims to build a robust text summarization model using advanced NLP techniques and leveraging the mT5 model for multilingual summarization tasks.

## 📖 Project Overview

Text summarization is the process of creating a shortened version of a document that retains its key points. This project implements extractive and abstractive summarization methods using state-of-the-art models like **mT5** and evaluates performance with **ROUGE** scores.

### Key Features
- **Abstractive Summarization** using mT5.
- **ROUGE** metric evaluation for summary quality.
- Multilingual support for summarization tasks.
  
## 🛠️ Technologies Used

- **Python**
- **mT5 Model**: Multilingual version of T5 (Text-to-Text Transfer Transformer).
- **ROUGE**: Metric to evaluate summarization performance.
- **Hugging Face Transformers**: For model implementation.
- **Pandas**: For data handling and manipulation.
- **Jupyter Notebook**: For coding and experimenting with the models.


## 🚀 How to Run the Project

### Prerequisites

Ensure you have the following installed:
- Python 3.7+
- Jupyter Notebook
- Hugging Face Transformers
- Pandas


## Installation

Clone the repository:

git clone https://github.com/dhruv7539/Text-Summarization.git
cd Text-Summarization

### Running the Code
Open mt5forsummary.ipynb in Jupyter Notebook or JupyterLab.
Run the notebook to preprocess the dataset and generate text summaries using the mT5 model.
For evaluating the generated summaries using ROUGE scores, open and run mt5forrouge.ipynb.

## 📊 Results
The summarization model provides high-quality summaries for [list languages], and performance is evaluated using the ROUGE metric, showcasing significant improvements over traditional methods.

## 🧪 Testing
For testing the performance and accuracy of the model, ensure you run the evaluation notebook:

bash
Copy code
pytest tests/

## 🛠️ Future Improvements
Add more languages for multilingual support.
Enhance the model's efficiency for long documents.
Explore alternative evaluation metrics to complement ROUGE.

##💡 Contributing
Contributions are welcome! Feel free to:

Fork the repository.
Create a new branch (git checkout -b feature/new-feature).
Commit your changes (git commit -m 'Add feature').
Push to the branch (git push origin feature/new-feature).
Open a Pull Request.

## 📜 License
This project is licensed under the MIT License. See the LICENSE file for more details.

👤 Contact
Author: Dhruv
Email: [Your Email]

