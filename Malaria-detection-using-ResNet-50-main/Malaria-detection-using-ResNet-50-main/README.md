# Malar-Ai
Malar-ai is a handy device(based on smartphones) used to detect probable malaria infection using blood smear slides. 

Powered by ResNet-50, cell-phone microscope and a staining kit, this setup is capable of performing at an accuracy of >95%, hence highly useful in remote and inaccessible areas. 

We aim to enhance the ease of Malaria testing in areas where the availability of testing equipments is not adequate. We are building a mobile app using which the health care worker can capture the photo of a blood smear slide of a person, and predict the possibility of Malaria. 

We have developed the machine learning model, and are working on an android app and potentially a lens. This project is maintained by the students Club of Sustainability & Innovation, Indian Institute of Technology(IIT-BHU), Varanasi. For any queries/potential collaborations/opportunites, mail at csi.iitbhu@gmail.com  

## Table of contents

- [Getting started](#getting-started)
	- [Setting up the environment](#setting-up-the-environment)
	- [Using the classifier](#using-the-classifier)
- [Credits](#credits)


## Getting started
### Setting up the environment
1. Clone the repo. 
2. Python version 3.6 or above is recommended. We also recommend you use a virtual environment. To know how to set up a virtual environment in python, click [here](https://youtu.be/N5vscPTWKOk). Once the environment has been created and activated, navigate to the cloned directory using command prompt/terminal and enter the following:
```pip install -r environment.txt```
This will install the dependencies.
If using ```conda```, you can just enter following command to create the environment as well as install the dependencies:
```conda env create -f Malar-AI.yml```

### Using the classifier

Once you have cloned the repo and have the environment set up, navigate to the cloned directory in command prompt/terminal and type this command:
```python "malaria predict.py" -i [IMAGE FILE]```

Two sample images have been provided.

## Credits
The dataset used for training the model was obtained from the website of Lister Hill National Center for Biomedical Communications and can be found [here](https://lhncbc.nlm.nih.gov/publication/pub9932). 
