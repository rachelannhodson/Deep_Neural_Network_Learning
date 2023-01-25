# Deep Neural Network Learning

This is a Jupyter Lab notebook file. This `.ipynb` file utilizes Python to read a `.csv` file and then uses deep neural network learning, through tensorflow and keras, to run machine learning models. These models attempt to get as close to 1.0 accuracy in predicting future outcomes. A data analyst could use these models to test specific target data in an attempt to determine future outcomes and thereby to create company policies in order to promote desirable outcomes. A data analyst would have to use these models and make lots of trial-and-error type changes to the code in order to get as close to 1.0 accuracy as their company is comfortable with. 

---

## Technologies

Please be sure you have Jupyter Lab installed:

* [JupyterLab](https://jupyter.org/)

This application was written in Python 3.9.12. This application is dependent on the following libraries:

* [pandas](https://pandas.pydata.org/)
* [pathlib](https://docs.python.org/3/library/pathlib.html)
* [tensorflow](https://www.tensorflow.org/)
* [tensorflow keras layers](https://www.tensorflow.org/api_docs/python/tf/keras/layers)
* [tensorflow keras models](https://www.tensorflow.org/api_docs/python/tf/keras/Model)
* [sklearn model selection](https://scikit-learn.org/stable/modules/generated/sklearn.model_selection.train_test_split.html)
* [sklearn preprocessing](https://scikit-learn.org/stable/modules/preprocessing.html)

---

## Installation Guide

If you have [Anaconda](https://www.anaconda.com/products/distribution) downloaded, then pandas and matplotlib will be part of your package. You can check that they're ready to use by typing the following in your CLI terminal:

```python
conda list pandas
conda list pathlib
```

You can download the following local machine using this code:
```python
pip install --upgrade tensorflow
pip install -U scikit-learn
```

And check that they've been installed with this code:
```python
python -c "import tensorflow as tf;print(tf.__version__)"
python -c "import tensorflow as tf;print(tf.keras.__version__)"
conda list scikit-learn
```

---

## Usage

Open your CLI terminal and type
```python
jupyter lab
```
then JupyterLab will automatically open in your browswer. Use the left side menu bar to search for the `venture_funding_with_deep_learning.ipynb` file. Open this file. Then you can use the formaulas in the `.ipynb` file to analyze your `.csv` file(s) and analyze your data and create new `.h5` files with your new models.

---

## Contributors

[Rachel Ann Hodson](https://www.linkedin.com/in/rachelannhodson/)
rachelannhodson@gmail.com

---

## License

MIT