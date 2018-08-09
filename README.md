tea classifier

## data

serial data collected with 8 e-noses from 7 classes of boiled tea

data augmentation by slicing

## model

- svm
- random forest
- multi-layer peceptron
- lstm
- 1d-conv cnn

the first 3 models were built with `scikit-learn` and optimized with `GridSearchCV` in it, the last 2 models were built with `tensorflow` and tuned manually

see the details in `main.ipynb`

> BTW, this repo is for learning models and toolkits. My college has built a better model with different preprocessing on data