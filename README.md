# [Unsupervised Learning of Object Landmarks through Conditional Image Generation]
Group member: 吴宇恒，徐诚伟，张凯忻

## Requirements
* Linux
* Python 2.7
* TensorFlow 1.10.0.
* Torch 0.4.1
* CUDA cuDNN.
* Python dependecies listed in `requirements.txt`

## Experiment results
We have trained the model on our own machine twice, with ten landmarks, and 300 and 3000 epoch respectively.
The result for 300 epoch:
![300 epoch](results/300times.png)
The result for 3000 epoch:
![3000 epoch](results/3000times.png)

## Notes
The 3000-epoch training result is stored in models/aflw-10pts-finetune. Run examples/visualize.ipynb to see it. (We didn't upload the whole model due to Github file size limit. The content inside this bracket will be removed after we figure out how to circumvent the limit.)
