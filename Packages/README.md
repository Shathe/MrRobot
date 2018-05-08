# Packages on virtual enviroments
For using packages on virtual enviroments, you only have to activate the enviroment of the desired package to use:
```
source enviroment_to_activate/activate
```

## [Tensorflow](https://www.tensorflow.org/)
```
source /opt/venvs/tensorflow-venv/bin/activate
```
Now you are free to work with Tensorflow:
```
python tensorflow_program.py
```

If you are using a new account, there can be packages or dependecies not yet installed and that you will have to install in order to make it run.

Easy example:
If tensorflow gives this error:
```
ImportError: No module named mock
```
It means the _mock_ package is not installed, so run:
```
pip install mock
```
and that is!


## [Caffe2](https://caffe2.ai/)
Enviroment activation:
```
source /opt/venvs/caffe2-venv/bin/activate
```
