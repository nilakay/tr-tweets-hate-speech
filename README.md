# tr-tweets-hate-speech

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

