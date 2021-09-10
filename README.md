# Final-Project
LSB&amp;NN of  Steganography
**********************************************************************

Steganography

The project contain two tasks, first the LSB, and second the neural network.

All steps work on the google colab. 

Way to run the code:
Upload the unzipped data sets to the colab root directory, named that file "data". Upload the model "modelsEpoch N110.pkl" to the colab root directory.
Run the code step by step, and the result will display in the commend window. 

(modelsEpoch N110.pkl Is the model we trained out. See more in WriteUp.pdf)
Path:

Under # Hyper Parameters
data_path = "/content/data"
checkpoints_path = "/content/modelsEpoch N110.pkl"

Also:
model.load_state_dict(torch.load('/content/modelsEpoch N110.pkl'))

Please change these path If you want


Group Member:
Haodong Hu, Hao Zheng, Shanglin Li, Kaihao Zhang 

Contact Email:
haodonh1@uci.edu
zhengh14@uci.edu
shanglil@uci.edu
kaihaz1@uci.edu

Project Date:
2021/9/9

**********************************************************************
