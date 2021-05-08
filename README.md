# 场景图生成

## 依赖
- [Python 2.7](https://www.python.org/)
- [tensorflow-gpu 1.0.1](https://www.tensorflow.org/)
- [matplotlib 2.0.2](http://matplotlib.org/)
- [h5py 2.7.0](http://www.h5py.org/)
- [numpy 1.12.1](http://www.numpy.org/)
- [pyyaml 3.12](https://pypi.python.org/pypi/PyYAML)

## 使用说明
1. Run `"python Run.py download"` 下载数据集
2. Run `"python Run.py eval gpi_linguistic_pretrained <gpu-number>"` 评估预训练模型
3. Run `"python Run.py train gpi_linguistic <gpu-number>"` 训练模型
4. Run `"python Run.py eval gpi_linguistic_best <gpu-number>"` 评估新模型