# Transformer-Based Fake News Detection

This project implements a Transformer-based classifier for detecting fake news. The model is trained using a dataset that combines real and fake news, and it includes training, validation, and test splits along with various evaluation metrics and plots.

## Project Structure

project/
│
├── main.ipynb                   # Main script
├── custom.ipynb                 # Custom prompt file
├── requirements.txt             # Python dependencies
├── README.md                    # Detailed instructions for setup & rerun
├── report.pdf                   # Two-page report with block diagram (or report.pdf after conversion)
└── presentation.pptx            # 10-slide presentation outline (or converted to ppt)

## Setup and Installation

1. Download the folder, and open the path in VS Code.

2. Install the required packages by running the below command in the terminal:
   pip install -r requirements.txt

## Running the Project

Open the terminal, and run the following commands:

1. Run the main script which performs training, validation, evaluation, and plotting. If the *transofrmer_fake_news_model.pth* and *vocab.pkl* are doanloaded, running this file is optional:
   python main.ipynb

2. To test the model against a custom input, and on the dataset, run:
   python custom.ipynb


