# Flipkart Product Recommendation Chatbot

Welcome to the Flipkart Product Recommendation Chatbot repository! This project aims to provide users with intelligent product recommendations based on their queries, leveraging machine learning and conversational AI.

## Features

- Conversational interface for product queries
- Personalized recommendations using user preferences and history
- Integration with Flipkart product data
- Scalable backend for handling multiple users
- Modular architecture for easy extension

## Technologies Used

- **Programming Languages:** Python
- **Frameworks:** Flask
- **ML Models:** Freely available open-source models from [Hugging Face](https://huggingface.co/) and [Groq API](https://groq.com/)
- **Database:** Astra DB (for storing vector embeddings)
- **Frontend:** (if applicable) HTML, CSS, JavaScript

> **Note:** No NLP libraries (such as spaCy or NLTK) are used in this project.

## Getting Started

### Prerequisites

- Python 3.x
- [conda](https://docs.conda.io/en/latest/miniconda.html) or [Anaconda](https://www.anaconda.com/products/distribution)

### Setup Instructions

1. **Clone the repository:**
    ```bash
    git clone https://github.com/AnshuVairagade/Flipkart_Product_Recommendation_Chatbot.git
    cd Flipkart_Product_Recommendation_Chatbot
    ```

2. **Create a new conda environment:**
    ```bash
    conda create -n flipkart-chatbot python=3.10
    conda activate flipkart-chatbot
    ```

3. **Install project dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

## Create a .env file for keeping your environment variable.
- GROQ_API_KEY = "GROQ_API_KEY"
- ASTRA_DB_API_ENDPOINT = "ASTRA_DB_API_ENDPOINT"
- ASTRA_DB_APPLICATION_TOKEN = "ASTRA_DB_APPLICATION_TOKEN"
- ASTRA_DB_KEYSPACE = "default_keyspace"
- HF_TOKEN = "HF_TOKEN"


## Use setup.py for installing your local package.
- <either mention -e . inside your requirements.txt Or run python setup.py install >

4. **Run the application:**
    ```bash
    python app.py
    ```

5. **Access the chatbot:**
    - Open your browser and go to [http://localhost:5000](http://localhost:5000) to interact with the chatbot.

**Note:**  
If you need to install conda, see the official [conda installation guide](https://docs.conda.io/en/latest/miniconda.html).

## Usage

- Type your product-related queries in the chat window.
- The chatbot will respond with recommended products based on your preferences and history.

## Project Structure

```
Flipkart_Product_Recommendation_Chatbot/
│
├── app.py                 # Main application file
├── requirements.txt       # Python dependencies
├── model/                 # ML models and scripts
├── data/                  # Sample product and user data
├── static/                # Frontend files (CSS, JS, images)
├── templates/             # HTML templates
└── README.md
```

## Contributing

Contributions are welcome! Please open issues or submit pull requests for improvements or new features.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License.

## Contact

For queries, contact [Anshu Vairagade](https://github.com/AnshuVairagade).


