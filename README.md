# AI_Final_Project


## Project Steps

### Installation

Make sure you have all the libraries installed in Cgames/Sonic/AI_Fina.ipynb. Then, you need to copy the SonicTheHedghog folder to your Retro Folder in your SitePackages folder from your python install. If you need help, google "where is my sitepackages folder python".


### Run the Optional Code Cell

Run this cell to make sure your sonic game is working.

### Run all other cells till step 6

### Create your architecture

Implement a deep learning model within the self.features block. I gave you the first part of the architecture (nn.Conv2d(input_shape[0],out_channels=, kernel_size=, stride=)), where you determine the number of filters (out_channels), kernel_size, and stride. You can use how many CNN and Activation layers you would like. I implemented the Fully Connected portion for you.

### Train your model

Now you can run the remaining code and train your agent for how many episodes you would like and watch your newly trained agent. Your goal is to achieve at least 2000 in rewards. Notice that the train code will save your model if over 2000 is achieved.

### Loading Models 
I provide code in the last cell for loading a saved model.


# Overall Goal and Deliverables

Your overall goal is to get at least 2000 in rewards with your model. This may take a lot of episodes, so be prepared to leave your computer training for a bit. You will notice that 2000 does not solve the level, and sonic may get stuck certain places. You can make your smart agent may take random actions now and then to achieve 2000 rewards.


Deliverables:

* Jupyter notebook (code and pdf)
* Your saved models
* A short (at most 1page) report describing how you went about designing your model, training parameters, and explaining Sonic's behavior. 


 