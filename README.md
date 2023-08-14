# <span style="font-size: 28px; font-weight: bold; color: red;">News Summarization using Pre-trained Language Models</span>

This project aims to <span style="font-weight: bold;">automatically generate concise and coherent summaries of news articles</span> using pre-trained Large Language Models (LLMs). By utilizing powerful language models like T5 and GPT-3, we can <span style="font-weight: bold;">extract the most important information</span> from lengthy news articles and present it in a condensed form.

## Table of Contents

- [Project Overview](#project-overview)
- [Technologies Used](#technologies-used)
- [How to Use](#how-to-use)
- [Project Impact](#project-impact)
- [Author](#author)

## Project Overview

The goal of this project is to create a <span style="font-weight: bold;">user-friendly interface</span> where users can input news articles, and the system will provide a summarized version of the article as output. We achieve this through the following steps:

1. **Data Collection:** We collect a dataset of news articles and their corresponding summaries (I used a dataset from Kaggle). These articles are then preprocessed and tokenized to make them suitable for input to the language model.

2. **Fine-tuning the Model:** We fine-tune a pre-trained Large Language Model 'T5' using the collected dataset. This process involves training the model on the task of summarization to adapt it specifically for generating news summaries.

3. **User Interface:** We create a user interface using the Gradio library, allowing users to instantly input news articles and receive summarized versions.

4. **Summarization:** When a user inputs a news article, the fine-tuned language model generates a summary by identifying the text's key information and main points.

5. **Output:** The generated summary is presented to the user, providing them with a concise overview of the article's content.

## Technologies Used

- Python
- PyTorch (or TensorFlow, depending on the LM used)
- Transformers Library (for pre-trained models)
- Gradio (for creating the user interface)

## How to Use

1. Install the required libraries by running `pip install transformers gradio`.

2. Run the provided code to fine-tune the language model and create the Gradio interface.

3. Access the user interface by opening the provided link in your web browser.

4. Input a news article into the provided text box and click the "Summarize" button.

5. View the summarized version of the article provided by the system.

## Project Impact

This project makes news consumption more efficient by providing users with <span style="font-weight: bold;">concise summaries</span>, allowing them to quickly understand the content of news articles without having to read through lengthy texts. It can be particularly useful for staying updated on various news topics in a time-effective manner.

Feel free to contribute, modify, or expand upon this project to explore different pre-trained language models and further enhance the summarization capabilities.

## Author

<span style="font-weight: bold;">Vivek Kumar</span>  
Contact: <span style="font-weight: bold;">vivekvivekvivekvi@gmail.com</span>  
GitHub: [<span style="font-weight: bold;">Vivek-Kumar-9554</span>](https://github.com/Vivek-Kumar-9554)

---

*Disclaimer: This project is developed for educational purposes and may require fine-tuning or customization for specific use cases.*
