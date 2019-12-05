# Network-Speed-and-Compression
### Network-acceleration
- https://github.com/yihui-he/channel-pruning

### Network Compression
- [awesome-model-compression-resource](https://github.com/ChanChiChoi/awesome-model-compression)
- [Learning both Weights and Connections for Efficient Neural Network.](https://arxiv.org/pdf/1506.02626.pdf)
- [Deep Compression: Compressing Deep Neural Networks with Pruning, Trained Quantization and Huffman Coding.](http://arxiv.org/abs/1510.00149)
- [SqueezeNet: AlexNet-level accuracy with 50x fewer parameters and <0.5MB model size.](http://arxiv.org/abs/1602.07360)
- [8-Bit Approximations for Parallelism in Deep Learning.](http://arxiv.org/abs/1511.04561)
- [Neural Networks with Few Multiplications.](https://arxiv.org/abs/1510.03009)
- [Compression of Deep Convolutional Neural Networks for Fast and Low Power Mobile Applications.](http://arxiv.org/abs/1511.06530) 
- [Hardware-oriented Approximation of Convolutional Neural Networks.](https://arxiv.org/abs/1604.03168)
- [Reduced-Precision Strategies for Bounded Memory in Deep Neural Nets.](https://arxiv.org/abs/1511.05236)
- [Quantized Neural Networks: Training Neural Networks with Low Precision Weights and Activations.](http://arxiv.org/abs/1609.07061)
- [DoReFa-Net: Training Low Bitwidth Convolutional Neural Networks with Low Bitwidth Gradients.](http://arxiv.org/abs/1606.06160)
- [Deep Learning with Limited Numerical Precision.](https://arxiv.org/abs/1502.02551)
- [Dynamic Network Surgery for Efficient DNNs.](http://arxiv.org/abs/1608.04493)
- [Understanding the Impact of Precision Quantization on the Accuracy and Energy of Neural Networks.](https://arxiv.org/abs/1612.03940) 
- [Variational Dropout Sparsifies Deep Neural Networks](https://arxiv.org/pdf/1701.05369.pdf) https://github.com/ars-ashuha/variational-dropout-sparsifies-dnn
- [Soft Weight-Sharing for Neural Network Compression](https://arxiv.org/pdf/1702.04008.pdf)
- [LCNN: Lookup-based Convolutional Neural Network](https://arxiv.org/pdf/1611.06473.pdf)
- [Bayesian Compression for Deep Learning](https://arxiv.org/pdf/1705.08665.pdf)
- [ThiNet: A Filter Level Pruning Method for Deep Neural Network Compression](https://github.com/Roll920/ThiNet)

### Network quantization
- https://petewarden.com/2016/05/03/how-to-quantize-neural-networks-with-tensorflow/
- https://github.com/aaron-xichen/pytorch-playground#quantization
- [Quantizing deep convolutional networks for
efficient inference: A whitepaper](https://arxiv.org/pdf/1806.08342.pdf)
- https://nervanasystems.github.io/distiller/quantization/

### Binary networks
- [XNOR-Net: ImageNet Classification Using Binary Convolutional Neural Networks.](http://arxiv.org/abs/1603.05279)
- [Binarized Neural Networks: Training Deep Neural Networks with Weights and Activations Constrained to +1 or -1.](http://arxiv.org/abs/1602.02830)
- [BMXNet: An Open-Source Binary Neural Network Implementation Based on MXNet](https://github.com/hpi-xnor/BMXNet)
- [Optimize Deep Convolutional Neural Network with Ternarized Weights and High Accuracy](https://arxiv.org/pdf/1807.07948.pdf)
- [Trained Ternary Quantization](https://arxiv.org/pdf/1612.01064.pdf) [2017]
- [Training wide residual networks for deployment using a single bit for each weight](https://arxiv.org/pdf/1802.08530.pdf) [2018]
    + https://github.com/szagoruyko/binary-wide-resnet
    
### Convolution decomposition
- [Flattened convolutional neural networks for feedforward acceleration](https://arxiv.org/pdf/1412.5474.pdf) [2015]
- [Speeding-up Convolutional Neural Networks Using Fine-tuned CP-Decomposition](https://arxiv.org/pdf/1412.6553.pdf) [2015]
    + https://github.com/vadim-v-lebedev/cp-decomposition
    + https://github.com/jacobgil/pytorch-tensor-decompositions
    + https://medium.com/@keremturgutlu/tensor-decomposition-fast-cnn-in-your-pocket-f03e9b2a6788
- [Compression of Deep Convolutional Neural Networks for Fast and Low Power Mobile Applications](https://arxiv.org/pdf/1511.06530.pdf) [2016]

### Pruning
- [Pruning Convolutional Neural Networks for Resource Efficient Inference](https://arxiv.org/pdf/1611.06440.pdf) [2017]
    + https://jacobgil.github.io/deeplearning/pruning-deep-learning
- Pruning in tensorflow
    + https://github.com/ex4sperans/pruning_with_tensorflow

### Frameworks
- https://github.com/Tencent/PocketFlow
- https://code.fb.com/ml-applications/qnnpack/
- https://developer.nvidia.com/tensorrt
- https://github.com/NervanaSystems/distiller
- https://github.com/tensorflow/tensorflow/tree/master/tensorflow/contrib/quantize

### Network models for mobile devices
- [Mobilenet](https://arxiv.org/pdf/1704.04861.pdf)
- [CondenseNet](https://arxiv.org/pdf/1711.09224.pdf)
- [NASNet](https://arxiv.org/pdf/1707.07012.pdf)
  + https://github.com/tensorflow/models/tree/master/research/slim/nets/nasnet
- [ShuffleNet](https://arxiv.org/pdf/1707.01083.pdf)
- [SqueezeNet](https://arxiv.org/pdf/1602.07360.pdf)
- [FD-MobileNet](https://arxiv.org/pdf/1802.03750.pdf)[2018]
- [ProxylessNAS](https://openreview.net/pdf?id=HylVB3AqYm)[2019]
  + https://github.com/MIT-HAN-LAB/ProxylessNAS
- [MnasNet](https://arxiv.org/pdf/1807.11626.pdf)[2018]
- [ESPNetv2](https://arxiv.org/pdf/1811.11431.pdf)[2018]
  + https://github.com/sacmehta/ESPNetv2
- [SqueezeNext](https://arxiv.org/pdf/1803.10615.pdf) [2018]

### Training smaller model based on existing one
- Data-Free Knowledge Distillation for Deep Neural Networks (https://arxiv.org/pdf/1710.07535.pdf) [2017]
  + https://github.com/iRapha/replayed_distillation
- Stealing Machine Learning Models via Prediction APIs (https://arxiv.org/pdf/1609.02943.pdf) [2016]

### Face recognition
- [MobiFace](https://arxiv.org/pdf/1811.11080.pdf) [2018]

To look at:
~~~
https://github.com/wpf535236337/real-time-network
https://github.com/dkozlov/awesome-knowledge-distillation
https://github.com/memoiry/Awesome-model-compression-and-acceleration
https://github.com/ljk628/ML-Systems/blob/master/dl_cnn.md
https://github.com/songhan/SqueezeNet-Deep-Compression
https://github.com/jiaxiang-wu/quantized-cnn
https://github.com/andyhahaha/Convolutional-Neural-Network-Compression-Survey
https://github.com/Zhouaojun/Efficient-Deep-Learning
https://github.com/ZFTurbo/Keras-inference-time-optimizer
https://github.com/becauseofAI/MobileFace
~~~
