# Correlation between Sentiment and Price Fluctuation of Bitcoin

In this group project, our objective was to analyze if there exists a correlation between sentiment scores, derived from sentiment analysis, and Bitcoin's price fluctuations.

> **Note**: Due to the large size of our models and datasets, we have excluded some content from the zip file.

## Getting Started

To access and run different segments of this project, download the content from our Google Drive:

🔗 [Google Drive Project Folder](https://drive.google.com/drive/folders/1brblSRUy-tGW83oCjk6CW75gtb4agHpK?usp=sharing)

We've modularized the content, ensuring you only download what's necessary. For instance, to run the sentiment predictions in `bertweet_demo.ipynb`, you'd need to download `pre-training_and_fine-tuning_bertweet/best_bertweet.pt`.

## Project Structure

Here's a brief on the organization of the entire folder:

- 📁 `bertweet-retrained`: Contains the re-trained Bertweet model on crypto-tweets.
- 📁 `tweet_datasets`: Houses all tweet datasets used in our analysis.
- 📁 `final_presentation`: Contains the presentation for project submission.
- 📁 `fine-tuning_roberta`: Includes the notebook to fine-tune RoBERTa.
- 📁 `pre-training_and_fine-tuning_bertweet`: Contains notebooks and data for pre-training and fine-tuning Bertweet.
- 📁 `task1`: Resources to predict the sentiment of manually labeled tweets for both Bertweet and RoBERTa.
- 📁 `task2`: Notebooks to predict sentiment over time and analyze its causality with financial data.
- 📁 `price`: Contains financial data used in Task 2.
- 📓 `NLP Group 5 Project (2022).ipynb`: The primary notebook for reproducing our results.
- 📓 `roberta_demo.ipynb`: A demo to predict sentiment using the fine-tuned RoBERTa model.
- 📓 `bertweet_demo.ipynb`: A demo to predict sentiment using the fine-tuned Bertweet model.

## Instructions

1. **Setup**: Extract the zipped file and upload the entire folder to the "My Drive" directory in your Google Drive.
2. **Demos**:
    - Ensure GPU runtime is enabled for optimal model performance.
    - Access the demo notebooks:
      - **BerTweet**: `bertweet_demo.ipynb`
      - **RoBERTa**: `roberta_demo.ipynb`
    - Use the demo functions at the end of each notebook. These functions accept a list of tweets. For example:
      ```python
      ["I love bitcoin HODL", "Why is Elon Musk dissing BTC"]
      ```
      This will output sentiment probabilities and predictions for each tweet.
