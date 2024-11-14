# Questions Auto-Complete System

## Authors
- **Arwa Doha** - Department of Computer Engineering, Birzeit University, Ramallah, Palestine
- **Maymona Obaid** - Department of Computer Engineering, Birzeit University, Ramallah, Palestine
- **Rama Abdalrahman** - Department of Computer Engineering, Birzeit University, Ramallah, Palestine

## Abstract
This project aims to build a search bar autocomplete feature using deep learning, specifically with Recurrent Neural Networks (RNN). The objective is to provide autocomplete predictions as the user types in the search bar.

### Key Features:
- **Character-based RNN model**: Trained to predict the next character in a sequence.
- **Dataset**: Kaggle dataset containing questions.
- **Data Preprocessing**: Clean text by converting to lowercase, removing punctuation, null values, etc.
- **Model Training**: Implemented using PyTorch, Adam optimizer, and Cross Entropy loss.
- **WebSockets**: For frontend-backend communication, enabling real-time autocomplete predictions.

## Requirements
- Python 3.6+
- PyTorch
- Flask or Django (for backend)
- WebSockets

## Installation

1. Clone this repository to your local machine:
   ```bash
   git clone https://github.com/your-username/questions-autocomplete.git
