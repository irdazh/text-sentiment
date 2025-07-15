# NLP on Blibli App's Reviews
A web-based ML app (?), which built using Flask, that predicts sentiments of Blibli application based on given text. 

## Project Overview
Perform sentiment analysis on 
Blibli application reviews in Google Play using NLP techniques. Build a model, evaluate it, and deploy a minimalistic app with Flask.

## ML Phase
- Explore & preprocess data
- Modeling & evaluation
- Deployment & documentation

## Dataset
This project uses the [Reviews of Indonesian Startup Apps on Playstore Dataset](https://www.kaggle.com/datasets/rezkyyayang/reviews-of-indonesian-app-startups-on-playstore?select=blibli.csv) from Kaggle, only focusing on Blibli application. It consists of 117k instances and 5 features: id, review date, rating, user review, and thumbs up count. 

## Tools
- Language: Python
- Libraries: Pandas, Matplotlib, Seaborn, WordCloud, Scikit-Learn, XGBoost, TensorFlow, PyTorch (?)
- Version Control: Git, GitHub
- Deployment: Flask (?) Hugging Face (?)

## Key Results
### Preprocess & EDA

### Model Comparison

### Final Model

## Project Structure
- `notebooks/`: EDA & modeling notebooks, also contains colab notebooks that shouldn't be run
- `models/`: Several useless models, final trained model (`joblib`)
- `data/`: Raw and cleaned data files
- `outputs/`: Generated charts and figures
- `app/`: Streamlit app
- `requirements.txt`: Python dependencies

## How to Run This Project
```bash
# Clone this repo
git clone https://github.com/irdazh/text-sentiment.git

# Create a virtual env and install requirements
python -m venv .venv
source .venv/bin/activate #or .venv\Scripts\activate on Windows
pip install -r requirements.txt 

# Run notebooks in order
jupyter notebook

# Run the flask app (?)
```

## Web App
Follow this link:

<!-- ![Input](assets/input.jpg)  
*Input Page*   

![Predict](assets/predict.jpg)  
*Prediction Result*

![Vizs](assets/viz.jpg)  
*Plot for Visualization*    -->

## About Me
This is a part of my data science portfolio -- 
built during my free time as a jobless loafer. More projects or anything else, proceed:
[GitHub](https://github.com/irdazh) |
[Kaggle](https://www.kaggle.com/irdazh) |
[LinkedIn](https:///www.linkedin.com/in/daud-ma)

#### Author's Note (Just Ignore)
- Create folders and files: gitignore, readme
- Create .venv
- Launch git
- Create GitHub repo; add as a remote; then do push there.  
