# Twitter_Sentiment_Analysis

This project is a Sentiment Analysis Tool designed to classify tweets into:
	•	Positive
	•	Neutral
	•	Negative

It uses DistilBERT, a lightweight and efficient version of BERT, to analyse sentiment in tweets. The project runs on Google Colab and comes with a sample dataset (obtained from Abhishek Shrivastava's Kaggle page: https://www.kaggle.com/datasets/abhi8923shriv/sentiment-analysis-dataset/code) 

**Features**

	•	Fine-tunes a pretrained DistilBERT model for sentiment analysis.
	•	Provides predictions for custom inputs.
	•	Visualises class probabilities as a heatmap, pointing out if your input is positive / neutral or negative.

 **TO RUN:**

1. Open it directly in Google Colab, or clone the repository to run on your local machine. To achieve this, open a terminal and run:
   git clone https://github.com/your-username/twitter-sentiment-analysis.git
   cd twitter-sentiment-analysis

2. Install the required libraries by running:
   pip install -r requirements.txt

3. If you have a GPU, you should install CUDA support:
   pip install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu117
