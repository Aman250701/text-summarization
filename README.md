# text-summarization

Installation of Necessary Packages
Use following pip commands to install the following libraries:

1. pip install pytorch_pretrained_bert
   For loading the bert model
   
2. pip install pandas
   For creating and preprocessing dataframes
   
3. pip install nltk
   For doing the preprocessing and tokenization
   
4. pip install rouge
   We've used python package along with the Java file to calculate the rouge score
   
5. pip install bert_score
   This is used to calculate the BERT Score
   

After doing this we can set the relative path of the validation folder directly in the second cell of the .ipynb file

Run all the cells to generate summary and it will be automatically saved in a directory named "gen_sum" which will be automatically created.
