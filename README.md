The code of article: Adaptive Spatio-Temporal Causal Graph Neural Network for Traffic Flow

 Prediction.

---

Article：Adaptive Spatio-Temporal Causal Graph Neural Network for Traffic Flow

 Prediction

Project Brief Introduction

This is a project for traffic flow forecasting, based on the Python programming language and machine learning techniques. The code is encrypted, but it can run on Linux systems, and it is recommended to use a cloud server for deployment and operation.

Environmental requirements

- Operating system: Linux
- Python version: Python 3.10
- Recommended operating environment: cloud servers (such as AutoDL, etc.)

Data preparation

1. Download the traffic data file (e.g. PEMS08.npz):
   - The data file can be downloaded from the following link: Baidu Netdisk Link
2. Place the downloaded data file in the data folder at the root of the project.

Run steps

1. Download and upload data files：
   Upload to the data/ folder. Take PEMS08.npz as an example, After the file is uploaded, the path is: data/PEMS08.npz.
2. Generate training, validation, and test sets：
   Enter the folder where generate.py or generate_training_data.py is located and run the following command to generate the data set.
       python generate.py or python generate_training_data.py
   The generated data will be saved in the data/PEMS08/ folder with the file names train.npz, val.npz, and test.npz.
3. Run the training script：
   Enter the folder where train.py is located and run the following command in the folder to start training the model.
       python train.py

Precautions

- Make sure the Python version is 3.10 and the Linux system, otherwise it may cause operation errors.
- If you encounter problems during operation, please check whether all dependent packages are correctly installed in the Python environment.
- Dependencies：
                  scipy
                  numpy=1.23.5
                  pandas
                  torch
                  argparse
                  tensorboardx
- The data file must be complete and in the correct format, otherwise it may not be possible to generate training data.

structure

    ├── pems08/
    │   ├── data/
    │   │   ├── PEMS08/
    │   │   │   ├── train.npz
    │   │   │   ├── val.npz
    │   │   │   └── test.npz
    │   ├── generate_training_data.py
    │   └── train.py
    └── README.md

Contact Details

If you encounter any problems during use, please feel free to contact the project maintainer.

---

I hope this README.md is useful for you! If there is anything else I can add, please let me know.
