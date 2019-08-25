# ANLY580: Natural Language Processing
## Author Identification for NLP

### The Paper:
The final [pdf](https://github.com/kateschulz/ANLY580/blob/master/Schulz_NLP_Paper.pdf) for this project, including background, methodology, data processing, model development, and findings. 

### The Code:
This repo contains three .ipynb that were run in Google Colab. 

### The Data: 
The large datasets for these files can be found on my Google Drive.

* txt -- This folder contains 3,036 [text files](https://drive.google.com/open?id=1t5sPmb3DxLiA_xcTVGCMPVg4NOy4G5b7), which I took a subset from.
* txt_data -- This folder contains 1,601 [csv files](https://drive.google.com/open?id=1llmGgiuBqv9KMPXbInX2-nl7v7iGIGqX), which were processed using Stanford POS Tagger. 
* list of authors -- This repo also contains a [csv](https://github.com/kateschulz/ANLY580/blob/master/author_bin_df.csv) that contains a list of author names and their corresponding bins. 

### The Images:
Finally, this repo also contains images of outputs from the .ipynb files, including the validation accuracies of the tokens and tages

![token accuracy](https://github.com/kateschulz/ANLY580/blob/master/Tokens_Accuracy.png)
![tag accuracy](https://github.com/kateschulz/ANLY580/blob/master/Tags_Accuracy.png)

and a dendrogram of the authors classified using Ward's Method.

![dendrogram](https://github.com/kateschulz/ANLY580/blob/master/Ward_Dendrogram_Authors.png)
