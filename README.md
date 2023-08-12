# Identity Recognition For Facial StO2

# Supplemental Files Explanation
  The file is composed of the dataset and model code.
# Dataset
  The dataset is divided into a training set and a testing set, each set consisting of face images and facial StO2 images. The naming rule for each image is "identity_sample".（e.g. "m_n" refers to the n-th sample of the m-th identity.）
# Code
## Required Package:
	tqdm 4.64.1
	torchvision 0.10.1+cu111
	torchaudio 0.9.1
	scipy 1.7.1
	pytorch 1.9.1
	python 3.8.11
	pillow 8.3.1
	opencv 4.0.1
	numpy 1.18.5
	
## File instructions:
	cnn_model.py:  Model of the 2-layer CNN.
	first_stage_train.py: code of the first stage training.
  second_stage_train.py: code of the second stage training.
  test: StO2 open-set identification task testing(imposter-to-genuine ratio of 1:1). We are currently organizing the code and will release the testing interface for other tasks in the future.

