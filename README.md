# Deep-Faseeh-resources

Here you can fine the genertaed word embeddings for Deep Faseeh project from King Saud University Corpus of Classical Arabic (KSUCCA) :
https://mahaalrabiah.wordpress.com/2012/07/20/king-saud-university-corpus-of-classical-arabic-ksucca/

### We trained KSUCCA with unsupervised and supervised word embeddings models

## Unsupervised models:

These are unsupervised word embeddings that were generated using CBOW and SG from Word2Vec. They were trained with different hyperparameters ranges: (2,4,5,8,16) for window size, (150, 300, 600) for dimensions, and (5 to 50) epochs. 
Model        	  | Dim No.             | wnidow size.    | Vec-Size		| Download      |
CBOW          | 150           | 2 | **150**	        | [Download](https://www.dropbox.com/s/a4qtazrlub6ue1n/KSU_150_2.rar?dl=0) |



Model        	  | Dim No.              | wnidow size.        		| Download      |
-----        	  | --------             | ----------          	    | --------- 	|
CBOW          | **150**           | 2 	        | [Download](https://bakrianoo.sfo2.digitaloceanspaces.com/aravec/full_grams_cbow_300_twitter.zip) |
Twitter-CBOW          | **150**          | 4 | **100**	        | [Download](https://bakrianoo.sfo2.digitaloceanspaces.com/aravec/full_grams_cbow_100_twitter.zip) |
Twitter-SkipGram          | **150**           | 5 | **300**	        | [Download](https://bakrianoo.sfo2.digitaloceanspaces.com/aravec/full_grams_sg_300_twitter.zip) |
Twitter-SkipGram          | **150**           | 8 | **100**	        | [Download](https://bakrianoo.sfo2.digitaloceanspaces.com/aravec/full_grams_sg_100_twitter.zip) |
Wikipedia-CBOW          | **150**           | 16 | **300**	        | [Download](https://bakrianoo.sfo2.digitaloceanspaces.com/aravec/full_grams_cbow_300_wiki.zip) |
Wikipedia-CBOW          | **300**           | 662,109 | **100**	        | [Download](https://bakrianoo.sfo2.digitaloceanspaces.com/aravec/full_grams_cbow_100_wiki.zip) |
Wikipedia-SkipGram          | **300**           | 662,109 | **300**	        | [Download](https://bakrianoo.sfo2.digitaloceanspaces.com/aravec/full_grams_sg_300_wiki.zip) |
Wikipedia-SkipGram          | **300**           | 662,109 | **100**	        | [Download](https://bakrianoo.sfo2.digitaloceanspaces.com/aravec/full_grams_sg_100_wiki.zip) |
