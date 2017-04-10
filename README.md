# Summary

* GoogleのTensorFlowの[Get Started](https://www.tensorflow.org/get_started/get_started)をやってみた
* 基本的に[Jupyter Notebook](http://jupyter.org/) 上で動作確認
* 2017/04/11現在, Non GPUのMacのみで動作確認

# Setup
* install pyenv
* install pyenv-virtualenv

```
$ bash setup.sh
```

pyenvとpyenv-virtualenvが使える状態で上記コマンドを実行すると、`hello.tensorflow`という名前の隔離されたpythonの環境が作られ、必要なパッケージがインストールされます。

# Notes

### [Hello TensorFlow](./doc/study_tensorflow.ipynb)

* TensorFlowで線形回帰を実装
* Session, placeholder, Variableなどの基本概念の理解
* Low Level APIと High Level APIの理解

### [MNIST](./doc/mnist.ipynb)

* 1層のニューラルネットによる学習(accuracy: 91.6%)
* CNN3層による学習(accuracy: 99.25%)


***
*This code includes the work that is distributed in the Apache License 2.0*
