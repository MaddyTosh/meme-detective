# Meme-Detective
This project aims to detect hateful content in memes

## Project Structure

## Setup

1. **Clone the repository**:
    ```bash
    git clone https://github.com/MaddyTosh/Meme-Detective.git
    cd Meme-Detective
    ```

2. **Create a virtual environment and activate it**:
    ```bash
    python -m venv venv
    source venv/bin/activate   # On Windows: venv\Scripts\activate
    ```

3. **Install the required dependencies**:
    ```bash
    pip install -r requirements.txt
    ```



4. **Run the application**:
    ```bash
    python app.py


5. **Libraries used /## Dependencies**

The project requires the following :

    ```Streamlit,
    PIL,
    Tensorflow,
    Tensorflow Hub,
    shutil,
    Numpy,
    Beautifulsoap,
    re,
    webBrowser


## Usage

1. **Upload a Meme**: Use the web interface to upload a meme image.
2. **Classify Meme**: The application will use the BERT-Encoder , ResNet-152 Encoder , RNN Decoder and DNN classifier models to classify the meme as hateful or not-hateful.



## Data

The `data/` directory contains the following files:
- `labels.csv`: Contains labels for the training data.
- `slang.txt`: A list of slang words and their meanings.
- Example images for testing.
