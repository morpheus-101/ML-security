# ML-security

This repository contains code files for ECE-GY 9163 Machine Learning for Cybersecurity.

Steps to run our code:

* Our approach is RAM intensive because it generates 50 perturbations for every input image. We recommend using less than a 1500 clean images and 1500 poisoned images.
* The code inlcuded in the repository uses 1000 clean images and 1000 poisoned images. 
* Also, our approach takes 3 inputs, the badnet model, clean validation set, and poisoned set.
* Evaluate our model by running: %run -i final_code.py <clean validation data> <bad net> <poisoned data>.
* The file 'eval_final_code.py' should be placed in the following location -- /content/drive/MyDrive/CSAW-HackML-2020-master_new/final_code.py
* The file 'final_code_run.ipynb' shows how to run our code on Google Colab. 
* Create a directory with the name 'CSAW-HackML-2020-master_new' in google drive 
* Upload the datasets and the models to google drive in appropriate directories as shown.
![](ml_sec_dir_str.png)
  
  



