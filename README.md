# transformer-based-language-translator

A project using a transformer architecture to implement machine translation, for the purpose of learning how to use transformer models.

- Applies word-level keras tokenization over an english-hindi dataset, and uses a custom encoder-decoder model with multi-head attention.
- Uses a custom learning rate - consisting of a linearly increasing LR for a warmup period of 4000 steps, followed by a decaying LR.
- The model then trains for 10 epochs, and is finally used to translate text.
- Sparse categorical cross-entropy loss is used to calculate the loss.

## Acknowledgments

This project makes use of the code and dataset, as given in 'English-To-Hindi-Translation-Using-Transformers'.

## Resources

- English-To-Hindi-Translation-Using-Transformers. https://www.kaggle.com/code/ashishsingh226/english-to-hindi-translation-using-transformers/notebook
- The Illustrated Transformer. https://jalammar.github.io/illustrated-transformer/
- Transformers : Language Translator Eng to French. https://www.kaggle.com/code/sani84/transformers-language-translator-eng-to-french
- Tab-delimited Bilingual Sentence Pairs. http://www.manythings.org/anki/
- English to Hindi Neural Machine Translation. https://www.kaggle.com/code/aiswaryaramachandran/english-to-hindi-neural-machine-translation/notebook
- Tensorflow transformer tutorial. https://www.tensorflow.org/text/tutorials/transformer
- Illustrated Guide to Transformers Neural Network: A step by step explanation. https://www.youtube.com/watch?v=4Bdc55j80l8