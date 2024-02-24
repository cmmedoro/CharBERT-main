<p align="center">
  <br>
    <img src="data/CharBert_logo.png" width="500" />  
  <br>
</p>
 
# Neural Contextual Embedding: CharBERT study and extensions 

This repository contains resources of the following [COLING 2020](https://www.coling2020.org) paper and the notebook (CharBERT_experiments) for reproducing the experiments of our work.  


## Models
The original work primarily provided two models. Here are the download links:   
pre-trained CharBERT based on BERT [charbert-bert-wiki](https://drive.google.com/file/d/1rF5_LbA2qIHuehnNepGmjz4Mu6OqEzYT/view?usp=sharing)    
pre-trained CharBERT based on RoBERTa [charbert-roberta-wiki](https://drive.google.com/file/d/1tkO7_EH1Px7tXRxNDu6lzr_y8b4Q709f/view?usp=sharing)  
Here our checkpoints:

pre-trained CharBERT on English Wikipedia (3 epochs) [en_wiki_3epochs](https://drive.google.com/file/d/1niddqAc5yfnjyqQRCBlEWe2aKt-4Gsfn/view?usp=sharing)

pre-trained CharBERT on English Wikipedia (6 epochs) [en_wiki_6epochs](https://drive.google.com/file/d/1SwGVWVSiH9_ugoymzmZi0j0EgoW4EznI/view?usp=sharing)

fine-tuned CharBERT on English Twitter [twitter_charbert](https://drive.google.com/file/d/1vJgMe4sOa5BWllNFrnUqQgxquu4BErbg/view?usp=sharing)

multilingual CharBERT on English and Italian Wikipedia [it_en_multilingual](https://drive.google.com/file/d/1h9plzoZtPcy6exUFWOko_-ZiE90jM1Xs/view?usp=sharing)

pre-trained CharBERT with different concatenation at character level [no_concat_wiki](https://drive.google.com/file/d/1VrfcXmN--hLRJohuS535O8OauSsYeswH/view?usp=sharing) (experiments on the different concatenation were performed in the no_concatenation branch of this GitHub Repository)


## Usage
You may use CharBERT_experiments to reproduce the experiments we did. Note that the majority of the datasets are dowloadable from HuggingFace, whereas the Twitter dataset used for fine-tuning the model is available here [Twitter_dataset](https://drive.google.com/file/d/1KdX3DOmJZj5m_AmwAZWNfGiUumdgTx2t/view?usp=sharing) and CoNLL-2003 is available here [CoNLL-2003](https://drive.google.com/file/d/10POkHvLQyTqVp-twG7SqDdFCy1weWfLe/view?usp=sharing).


