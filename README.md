# End To End ML Projects With KN

## Agenda Of This Particular Project

1. Set up the github {Repository}
    - new envioronment 
    - (conda create -p venv python==3.8 -y)
    - conda activate venv/
    - setup.py (mini project structure)- 
      (Will be responsible in creating my ML App as a project which will be installable on any PC using pip. We will deploy it as a Python Package itself)
    - requirements.txt (pythpn pypi)
    - __init__py file creation.
    - Src folder and build the package
    - Learn more about setup.py**, ie.
2.  Project Structure, Loggin and Exception Handling-
    
    Components(Modules that we are going to specifically use for the project): 
      -> Data Injection - Process of Handling any kind of datasets.
        - data_injection.py will read data from any kinds of datasets (will devide train and test and validation) 
      -> Data Transformation - This is the process after reading the data like (data transformation, validation etc )
        - data_transformation.py will do change the catagorical data to numerical data, handling onehot encoding, level encoding etc 
      -> Model trainer - All kinds of training code will stay here
        - model_trainer.py
    Pipeline(Training and Test Pipleline):
      -> Prediction  
