

## Installation & Setup


1. create_model.py – creates a model model.ckpt file based on the expert tutorial.
2. predict.py – uses the model.ckpt file to predict the correct integer form a handwritten number in a .png file.



## Running
Running is based on the steps:

1. create the model file
2. create an image file containing a handwritten number
3. predict the integer 

### 1. create the model file
The easiest way is to cd to the directory where the python files are located. Then run:

```python create_model_1.py```

### 2. create an image file
You have to create a PNG file that contains a handwritten number. The background has to be white and the number has to be black. Any paint program should be able to do this. Also the image has to be auto cropped so that there is no border around the number.

### 3. predict the integer

The predict scripts require one argument: the file location of the image file containing the handwritten number. For example when the image file is ‘number1.png’ and is in the same location as the script, run:

```python predict.py ‘number1.png’```
