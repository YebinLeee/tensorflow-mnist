# 💻 MNIST classification by TensorFlow #

Forked, modified by Yebin Lee <br>
2021.05.21 ~


## [Reference]


- [MNIST For ML Beginners](https://chromium.googlesource.com/external/github.com/tensorflow/tensorflow/+/r0.10/tensorflow/g3doc/tutorials/mnist/beginners/index.md)
- [Deep MNIST for Experts](https://chromium.googlesource.com/external/github.com/tensorflow/tensorflow/+/r0.10/tensorflow/g3doc/tutorials/mnist/pros/index.md)

<br>

- [손으로 쓴 숫자의 DataSet](https://www.tensorflow.org/datasets/catalog/mnist)
- [신경망 훈련 : 옷 이미지를 분류하는 신경망 모델을 훈련](https://www.tensorflow.org/tutorials/keras/classification)

<br>
<hr>

### [View]

![screencast](https://cloud.githubusercontent.com/assets/80381/11339453/f04f885e-923c-11e5-8845-33c16978c54d.gif)

<hr>

## [Requirement]

- Python >=2.7 or >=3.4
  - TensorFlow >=1.0
- Node >=6.9


### How to run ###

    $ pip install -r requirements.txt
    $ npm install
    $ gunicorn main:app --log-file=-


### Deploy to Heroku ###

    $ heroku apps:create [NAME]
    $ heroku buildpacks:add heroku/nodejs
    $ heroku buildpacks:add heroku/python
    $ git push heroku master

or Heroku Button.

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy)
