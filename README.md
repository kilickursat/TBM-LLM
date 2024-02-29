# TBM Knowledge Generator with LLaMA 2

This project leverages the power of the LLaMA 2 model, fine-tuned on a specialized corpus of scientific papers related to Tunnel Boring Machine (TBM) tunneling, to generate insights, answer questions, and provide recommendations. It includes a comprehensive pipeline from data collection using an API, preprocessing, hyperparameter tuning with Optuna, and a Streamlit application for easy interaction with the model.

## Features

- **Data Collection**: Automated script to fetch relevant scientific articles using an API.
- **Data Preprocessing**: Preprocess and tokenize articles for model consumption.
- **Hyperparameter Tuning**: Utilize Optuna for finding the best model training hyperparameters.
- **Model Training**: Fine-tune the LLaMA 2 model on the TBM dataset.
- **Streamlit Application**: A user-friendly web app to interact with the fine-tuned model.

## Installation

1. Clone this repository.
   ```
   git clone https://github.com/yourusername/tbm-knowledge-generator.git
   ```
2. Install required packages.
   ```
   pip install -r requirements.txt
   ```

## Usage

To run the Streamlit application:
```
streamlit run streamlit_app.py
```

## Contributing

Contributions are welcome! Please feel free to submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
