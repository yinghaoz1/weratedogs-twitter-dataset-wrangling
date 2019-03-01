## Introduction
weratedogs-twitter-dataset-wrangling is a project which utilizes pandas to wrangle the WeRateDogs Twitter Dataset and Matplotlib and StatsModels to visualize and model the cleaned dataset. The dataset consists of three parts: 1)  df: The WeRateDogs Twitter archive dataset named `twitter-archive-enchanced.csv`; 2) df2: The tweet image prediction from the neural network named `image-predictions.tsv`; 3) df3: The additional dataset from the Twitter API including the retweet and favorite count named `tweet-json.txt`.

## Table of Contents
- `twitter-archive-enchanced.csv`: The uncleaned WeRateDogs Twitter archive dataset
- `image-predictions.tsv`: The uncleaned dataset of tweet image prediction from the neural network downloaded from https://d17h27t6h515a5.cloudfront.net/topher/2017/August/599fd2ad_image-predictions/image-predictions.tsv
- `tweet-json.txt`: The additional uncleaned dataset from the Twitter API including the retweet and favorite count
- `twitter-archive-master.csv`: The cleaned dataset which combines the data from `twitter-archive-enchanced.csv` and `tweet-json.txt`
- `wrangle-act.ipynb`: The Jupyter Notebook version of the process of data wrangling, analyzing, and visualization
- `wrangle-act.html`: The html version of the process of data wrangling, analyzing, and visualization
- `wrangle-report.ipynb`: The Jupyter Notebook version of the documentation of data wrangling
- `wrangle-report.html`: The html version of the documentation of data wrangling
- `act-report.ipynb`: The Jupyter Notebook version of the documentation of data analysis and visualization
- `act-report.html`: The html version of the documentation of data analysis and visualization
- `img1.png`, `img2.png`, `img3.png`, `img4.png`, `img5.png`, `img6.png`: The images of visualizaition and statistical result in `act-report.ipynb`
