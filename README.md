# tr-tweets-hate-speech

description
----------------
People have a free platform to openly express their emotions thanks to social media. On social media, users may react on other posts and give their opinions. Social media platforms are used for both encouraging remarks and upsetting hate speech. One of the main causes of the rise in hate speech is the daily large density of shares and interactions on social media, as well as the decentralized nature of these platforms. The rise in online insults directed towards other countries, ethnicities, faiths, and other groups has an effect and disturbs social peace.    

ML approaches are widely used in comparison to rule-based systems to detect abusive language. The Turkish language’s grammar makes it difficult to complete this project, in addition to the challenges this area faces. The aim of this project is to detect hate speech on Twitter and help the literature to find a way to deal with mislabeled data. So I gathered some public datasets and include particular parts of them to overcome some imbalanced-label problems.


cleaning datasets
----------------
In collecting datasets.ipynb, the format of the datasets are arranged and some unallowed characters are removed.    
All datasets converted into .csv file format.  

dataset
----------------
In concat dataset.ipynb I took, 
2000 non-offensive and 2000 offensive instagram comments from "HATC" dataset which includes total 31,290 instances.  
2000 non-offensive and 2000 offensive tweets from "The OffensEval-2020" dataset which includes total 35,284 instances.  
1000 non-offensive and 1000 offensive tweets from "5k Turkish tweets w/incivil content" dataset from Kaggle which includes total 5,054 instances.  
I created a dataset called "ensemble.csv" which includes 10k instances. (5000 offensive/5000 non-offensive).   


model
---------------
In order to compute tw-hate-speech.ipynb, I personally used kaggle's environment since the model is computaionally expensive. You can use TPU v3-8 as Accelerator.  

You should also include the ensemble.csv dataset in the same directory as your notebook.  

You should have tensorflow and transformers installed in your kaggle environment. You can use these commands in your notebook:


`pip install tensorflow`  
`pip install tranformers`

