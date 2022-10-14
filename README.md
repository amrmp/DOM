# DOM

Deep Neural Network-Based On-device Malware Detection (DOM)

# What is DOM?

DOM is a deep learning-based on-device malware detection application for Android devices that employs transfer learning and model personalization to improve a global deep neural network (DNN) across smartphones. DOM is lightweight, robust, and does not need to have smartphones rooted. 

DOM analyzes applications on smartphones without a need for a remote server and trains a neural network on the device with the help of a generic DNN for labeling. DOM employs two on-device machine learning models called generic and personalized models and dynamically analyzes applications to extract a comprehensive set of features. The generic model is used to label applications whose ground truth is unavailable. In contrast, the personalized model is a lightweight trainable model created by retaining most of the generic DNN layers and trainable parameters and adding a new lightweight neural network, which is further improved with the help of federated learning.

# Contribution

DOM is an ongoing project and new features and improvements will be added. The current version is DOM-1.0.0. 

# Acknowledgment

If you use DOM or any parts of the DOM project, you must cite the following paper [DOM's paper](https://ieeexplore.ieee.org/document/9826004).

```bash

A. Pasdar, Y. C. Lee, T. Liu and S. -H. Hong, "Train Me to Fight: Machine-Learning Based On-Device Malware Detection for Mobile Devices," 2022 22nd IEEE International Symposium on Cluster, Cloud and Internet Computing (CCGrid), 2022, pp. 239-248, doi: 10.1109/CCGrid54584.2022.00033.
```
