# Requirements:
* Python 3.7.10
* Pytorch 1.7.1
* Numpy 1.21.5
* Tqdm 4.61.2
* Nltk 3.6.2
* Gensim 3.8.3
# Usage:
* Dataset:

  Download the dataset introduced in [1] and put it into "data" folder.

* hyper-parameter tuning:

  Use the training subset and validation subset to finish the hyper-parameter tuning. All the hyper-parameters are decided in this process. Run the code:

  ```python parameter_tuning.py```

* Train the model:
  
  Train the model with the hyper-parameters tuned. Run the code:
  
  ```python classification.py```
  
* Test the model:
  Rename the trained model as "model_best.pth" and put it into the "\attention\models_saved" folder. Then run the code:

  ```python testing.py```

# Reference:

* [1] Xuemeng Song et al. A personal privacy preserving framework: I let you know who can see what. In Proceedings of the International ACM SIGIR Conference on Research and Development in Information Retrieval, pages 295–304, 2018. 