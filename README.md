# Named Entity Recognition

  1. Day 1: 
  
    Performing Analysis on Named Entity Recognition over certain datasets to train the model to develop the weights to Recognise all the alma-matter from the sentence/s.
    
    As per the analysis, when commonly applied en_core_web_sm/lg models fine-tuned over NER dataset, gives the recognizable entities in single read, as per Date, ORG, GPE however, relationships over the context to train the model to understand the pairing entities over a commonly said relationship.
  
  For example,
  
  FIRST AMENDMENT TO ASSET PURCHASE AGREEMENT (this "Amendment") is made and entered into as of January __, 2018, by and between (i) DEXTERA SURIGCAL, INC., a Delaware corporation formerly known as "Cardica, Inc." ("Seller") and (ii) AESCULAP, INC.
  
  I had couple of options as in fine-tuning over the en_core_web models with the NER Dataset as well as the labelled data I've for further finetuning to recognise the general and near about words forming good relations under the hood (It's vectors, which is beyond the scope to discuss here). 
  
  To generalise the context and find objects mapping with the words as per the events, I'll be fine-tuning pre-trained models over NLP Architecture with NER Dataset for Entity Recognition with BERT. 
  
  Explaining about BERT is beyond the scope of this analysis, I'll however align whatever possible in the current analysis.
  Please refer to https://arxiv.org/abs/1810.04805 for the paper on BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding
 
 
  2. Day 2:
