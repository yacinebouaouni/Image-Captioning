# Image-Captioning


## 1.Vocabulary Object:
--------------------------------------------------------------

* Attributes:

  1.  start_word :refers to the beginning of the sentence (encoded as 0)
  2.  end_word :refers to the end of the sentence. (encoded as 1)
  3.  unk_word:refers to an unknown word in the vocabulary (encoded as 2)
  4.  vocab_threshold:the minimum of repetitions for a word to add it to the vocabulary
  5.  vocab_file:a pickle file for a vocabulary saved before .To use it set vocab_from_file=True
  6.  annotations_file:This file contains the annotations of COCO dataset.To create a vocabulary from scratch using this captions set vocab_from_file=False.
  7.  word2idx :a dictionary of words and their corresponding encoding integer 
