# nielsen
Product Classification Demo

This repository is a public demo of a product classification system developed by Lemay.ai as a proof of concept.

The code runs on GPU, using a pretrained XLNet case sensitive version, keras/tensorflow, pytorch, sklearn, spacy, and a few other libraries.

The model was trained on 29,651 samples, and validated on 3,295 samples.

For this task, the model achieved a peak validation accuracy of 95%. That means that 95% of the predicted segments were correct. Deeper analysis with pandas profiling and sklearn metrics reports are a good idea, to reveal the per-class f1-score. 
