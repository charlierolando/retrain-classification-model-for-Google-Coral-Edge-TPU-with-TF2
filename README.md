# retrain-classification-model-for-Google-Coral-Edge-TPU-with-TF2

>This code is an implementation of [google-coral/retrain_classification_tf2](https://github.com/google-coral/tutorials/blob/master/retrain_classification_ptq_tf2.ipynb) with [Shabrina](https://github.com/ShabrinaRachmawatiA27)

![Result](https://github.com/charlierolando/retrain-classification-model-for-Google-Coral-Edge-TPU-with-TF2/blob/main/images/images1.png)

>click [this](https://github.com/charlierolando/retrain-classification-model-for-Google-Coral-Edge-TPU-with-TF2/blob/main/images/images1.png) when the image doesn't appear

## [Code:](#code)

>click [this](https://github.com/charlierolando/retrain-classification-model-for-Google-Coral-Edge-TPU-with-TF2/blob/main/source/train.ipynb) to see the full code

## [How to use:](#how-to-use)

- Put images data that you want to train into the 'train_data' directory with configuration, one folder for one classification data (create names of folders according to classification). click [this](https://github.com/charlierolando/retrain-classification-model-for-Google-Coral-Edge-TPU-with-TF2/blob/main/source/train_data/) to see the example.

- For your non-Colab code, be sure you have tensorflow==1.15

- If there are any errors with numpy, be sure you have numpy==1.19

- Run [this](https://github.com/charlierolando/retrain-classification-model-for-Google-Coral-Edge-TPU-with-TF2/blob/main/source/train.ipynb)

- After compile the tflite file, run [this code](https://github.com/charlierolando/retrain-classification-model-for-Google-Coral-Edge-TPU-with-TF2/blob/main/source/classify_image_test.py) to test the classification. Read [this notes](https://github.com/charlierolando/retrain-classification-model-for-Google-Coral-Edge-TPU-with-TF2/blob/main/source/note_for_classify_image_test.py.txt).

```python
# Example
python classify_image_test.py \ --model tflite_name.tflite \ --labels labels.txt \ --input test_data/Clip.jpg
```

## [References:](#references)

[google-coral/retrain_classification_tf2](https://github.com/google-coral/tutorials/blob/master/retrain_classification_ptq_tf2.ipynb)
