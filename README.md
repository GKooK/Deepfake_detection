# Deepfake_detection
This planned to make two versions of models. One for web-server(Pytorch) and one is for Chrome Extension(Tensorflow.js). Chrome Extension's model is shape of JSON format(weight is supported by .bin format) with ml5.js or tf.js.
At first, I planned to use the same model by using [pytorch2keras](https://github.com/gmalivenko/pytorch2keras). Because of the LSTM layer of pytorch model, we can't use pytorch2keras. So, in Chrome Extension version we replaced it into some FC layers.
Trained Models couldn't be upload from the size of the model. so it's replaced by [google drive link](https://drive.google.com/drive/folders/19FNcWPq-6iabzucsRDJPhkD1VJnD9A8S?usp=sharing)
