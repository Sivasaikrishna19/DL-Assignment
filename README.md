# MultiModalClassifier

**MultiModalClassifier** is a deep learning project repository featuring popular models from both TensorFlow and PyTorch. This project serves as a template for developing multi-modal classification systems and can be a starting point for experimenting with new ideas or applications in machine learning and deep learning.

For beginners looking to understand the basics of Machine Learning (ML) and Deep Learning (DL), please refer to this repository: [DeepDataMiningLearning](https://github.com/lkk688/DeepDataMiningLearning).

## Package Setup

To install this project in development mode, execute the following command within your virtual environment:

```bash
(venv38) MyRepo/MultiModalClassifier$ python setup.py develop
>>> import TFClassifier
>>> import TFClassifier.Datasetutil
>>> import TFClassifier.Datasetutil.Visutil
(venv38) lkk@cmpeengr276-All-Series:~/Developer/MyRepo/MultiModalClassifier$ python setup.py develop --uninstall
python myTorchTrainer.py --data_name 'CIFAR10' --data_type 'torchvisiondataset' --data_path "E:\\Dataset" --model_name 'cnnmodel1' --learningratename 'ConstantLR' --optimizer 'SGD'
(mycondapy310) [010796032@g4 TorchClassifier]$ python myTorchTrainer.py --data_name 'tiny-imagenet-200' --data_type 'trainonly' --data_path "/data/cmpe249-fa23/ImageClassData" --model_name 'resnetmodel1' --learningratename 'StepLR' --lr 0.1 --momentum 0.9 --wd 1e-4 --optimizer 'SGD'
TorchClassifier/outputs/tiny-imagenet-200_resnetmodel1_0910
$ python myTorchEvaluator.py --data_name 'tiny-imagenet-200' --data_type 'trainonly' --data_path "/data/cmpe249-fa23/ImageClassData" --model_name 'resnet50' --checkpoint 'outputs/tiny-imagenet-200_resnet50_0328/checkpoint.pth.tar' --classmap 'TorchClassifier/Datasetutil/tinyimagenet_idmap.json' --gpuid 0
converter_int8.inference_input_type = tf.int8  # or tf.uint8
converter_int8.inference_output_type = tf.int8  # or tf.uint8

This version of the README file is complete and can be directly pasted into your Markdown file to serve as a comprehensive guide for your MultiModalClassifier repository. Adjust the content as needed to fit your specific project details and directory structure.
