# Transformers
#Attention is all you need
Transformers are language models used for NLP. But they are no more confined to language domain. Furture image processing is going to be done with transformers.
They are called vision transformers(ViTs).

General architecture of Transformer contains,
  -given input text is split into set of words called tokens.(Word Tokens)
  -each token is encoded into vector(word2vec) 
  -Position of word in the sequence is encoded using position embedding and integrated with word embediding(Token Embedding)
  -These embeddings are fed into transformer encoder
  -Transformer encoder contains multiple Multi-Layer Self-Attention Network(MSP)+Multi-layer Perceptron(MLP)+Norm
  -Finally a MLP-Head is present outside the transformer encoder with provides logits.These logits can be conveted into probabilites using softmax layer.
  
 ViTs are used for vision problems.
 
 Transformers has MLP which is general purpose head and can be trained to perform different tasks in NLP and CV.
 
 some example appications of Transformers are 
  -Language translation
  -Image classification
  -Image captioning
  -Text to image generation
