## datalab
It has all the files that were used in datalab while making the YOLO function. 
1. Simplified YOLO Estimator.ipynb : Estimator code in python notebook
2. config.yaml : config file needed while submitting a job to AI Platform
3. trainer : setup.py and task.py files needed while submitting a job to AI Platform
4. saved model: exported model


## EAST Cloud Function
It has the main.py which with the function definition and the requirements.py file with the package dependencies. The function is triggered when  file is uploaded to 'indic2019' bucket in Google Cloud Storage

## East Model
1. Saved model taken from [here](https://github.com/kurapan/EAST) and then converted a model from a .json file and the weights from .h5 file into a single .h5 file as it is easier to be imported into tensorflow.
2. EAST_Estimator_1.ipynb : Working on converting the code to an estimator structure. This is an **unfinished file**. 

## License
[MIT](https://choosealicense.com/licenses/mit/)
 
