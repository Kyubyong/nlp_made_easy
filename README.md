# NLP Made Easy

Simple code notes for explaining NLP building blocks

* [Subword Segmentation Techniques](Subword%20Segmentation%20Techniques.ipynb)
  * Let's compare various tokenizers, i.e., nltk, BPE, SentencePiece, and Bert tokenizer.
* [Beam Decoding](Beam%20Decoding.ipynb)
  * Beam decoding is essential for seq2seq tasks. But it's notoriously complicated to implement. Here's a relatively easy one, batchfying candidates.
* [How to get the last hidden vector of rnns properly](How%20to%20get%20the%20last%20hidden%20vector%20of%20rnns%20properly.ipynb)
  * We'll see how to get the last hidden states of Rnns in Tensorflow and PyTorch.
* [Tensorflow seq2seq template based on the g2p task](Tensorflow%20seq2seq%20template%20based%20on%20g2p.ipynb)
  * We'll write a simple template for seq2seq using Tensorflow. For demonstration, we attack the g2p task. G2p is a task of converting graphemes (spelling) to phonemes (pronunciation). It's a very good source for this purpose as it's simple enough for you to up and run.
* [PyTorch seq2seq template based on the g2p task](PyTorch%20seq2seq%20template%20based%20on%20the%20g2p%20task)
  * We'll write a simple template for seq2seq using PyTorch. For demonstration, we attack the g2p task. G2p is a task of converting graphemes (spelling) to phonemes (pronunciation). It's a very good source for this purpose as it's simple enough for you to up and run.
* [Attention mechanism](Work in progress)
* [POS-tagging with BERT Fine-tuning](Pos-tagging%20with%20Bert%20Fine-tuning.ipynb)
  * BERT is known to be good at Sequence tagging tasks like Named Entity Recognition. Let's see if it's true for POS-tagging.
* [Dropout in a minute](Dropout%20in%20a%20minute.ipynb)
  * Dropout is arguably the most popular regularization technique in deep learning. Let's check again how it work.
* Ngram LM vs. rnnlm(WIP)
