# Bounty_StackUp_Sentiment_Analysis_With_Llama2_Huggingface
👉 Link to [notebook](https://colab.research.google.com/drive/1uZRaJ6tfEOPXsb9APniA-GFTAp-1ZHOx#scrollTo=MZLZ1MAJIQ6T)
## Project Overview
This cutting-edge chatbot leverages sentiment analysis and the capabilities of Llama 2, a cutting-edge language model, to deliver emotionally and contextually sensitive responses. This project was created to demonstrate how conversational AI incorporates cutting-edge NLP approaches.

### Features
- **Sentiment Analysis Integration:** I've included a Hugging Face sentiment analysis model. This enables the chatbot to detect your emotional state and modify its responses accordingly. Are you getting annoyed? It could require a more encouraging voice. At ease? The answer remains impartial.
- **Llama 2 Integration:** Initially, the chatbot looks for pre-loaded datasets with known answers. If the response is not present, it generates one dynamically using the Llama 2 model.
- **Dynamic QA Dataset:** Maintains and updates a CSV-based question-answer dataset for quick responses to common queries.
- **Gradio Web Interface:** Offers an intuitive and interactive web interface for easy interaction with the chatbot.
- **Expandable knowledge base:** Knowledge of chatbot grows with time.

### Technical Details
- **Model:**** NousResearch/Llama-2-7b-chat-hf
- **Sentiment Analysis:** Hugging Face Transformers pipeline
- **Frontend:** Gradio
- **Data Storage:** CSV file for QA pairs
