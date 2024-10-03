# GAN-Face-Detection
Computer Vision Masters Project for GAN face detection

# Folder structure:

    .
    ├── deep learning notebooks (Contains DL model model and notebook for ResNet50)
    ├── notebooks (Contains all the ML related work)
    │   ├── catboost_info        (CATBoost related initialization)
    │   ├── final_ml_model_pickles (contains all the final pkl files for trained ML models)
    │   └── ipynb files and haar cascade files and csv files
    ├── paper references (All the paper references)
    ├── project references (All the paper references)
    ├── python-codes (Contains DL model python code for XceptionNet)         
    └── README.md
    
    
# Dataset Links:
FFHQ Dataset : https://www.kaggle.com/datasets/arnaud58/flickrfaceshq-dataset-ffhq
<br>
StyleGAN25k : Provided by Yang Kaicheng. 
<br>

# Code Execution
## notebooks folder:
Run the Jupyter notebook cell by cell

## deep learning notebooks folder:
ResNet50 model.
Run the Jupyter notebook cell by cell

## python-codes
XceptionNet model
Run the file using: python fine_tune.py data_folder_path classes.txt_path result_folder_path.
example: python fine_tune.py "D:\spring 23\computer vision\project\data" "E:\xception-2\Xception-with-Your-Own-Dataset-master\classes.txt" "E:\xception-2\Xception-with-Your-Own-Dataset-master\result"

The h5 model (for the XceptionNet) is saved on IU onedrive: https://indiana-my.sharepoint.com/:f:/g/personal/sghouji_iu_edu/Er1EpV4kvmZJhJYPXMIg5eoBLEHPm5YeI0odYzUQDtBgSA?e=ZhyqUL


