# AFACNet: Adaptive Frequency Learning Network With Anti-aliasing Complex Convolutions For Colon Diseases Subtypes (JBHI)

# Requirements
Our code is based on python and pytorch1.8.

# Training the Model
python train_test.py

train_dataset-root: Folder to which you downloaded and extracted the training data

val_datapath-root: Folder to which you downloaded and extracted the val data

record_path: The path where the training results are stored

model_path = The path where the model is stored

best_path = The path where the model with the best result on the validation set is stored

First go into the train_test and adapt all the paths to match your file system and the download locations of training and test sets.

Then python train_test.py to train your dataset.

# Citation

If you find the code useful for your research, please cite our paper.

@ARTICLE{10229145,
  author={Wang, Kaini and Zhuang, Shuaishuai and Miao, Juzheng and Chen, Yang and Hua, Jie and Zhou, Guang-Quan and He, Xiaopu and Li, Shuo},
  journal={IEEE Journal of Biomedical and Health Informatics}, 
  title={Adaptive Frequency Learning Network With Anti-Aliasing Complex Convolutions for Colon Diseases Subtypes}, 
  year={2023},
  volume={27},
  number={10},
  pages={4816-4827},
  doi={10.1109/JBHI.2023.3300288}}




