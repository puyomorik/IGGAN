# Evaluation Codes and Pre-trained models of WACV2024 paper ''Improving the Fairness of the Min-Max Game in GANs Training''

We have provided the pre-trained IGGAN models on CIFAR-10 and CIFAR-100 datasets for better obtaining the results we reported in the paper. The code of this module is built by ourselves based on the test codes of the DiffAug-GAN [[link]](https://github.com/mit-han-lab/data-efficient-gans) and NDA-GAN [[link]](https://github.com/ermongroup/NDA). 

# Requirement

PyTorch version==1.7.1.

TensorFlow 1.14 or 1.15 with GPU support (for IS and FID calculation).

Other python libs in DiffAug-GAN [[link]](https://github.com/mit-han-lab/data-efficient-gans) and NDA-GAN [[link]](https://github.com/ermongroup/NDA).


# IGGAN pre-trained models

Pre-trained IGGAN on Unconditional CIFAR-10 dataset [[link]](https://drive.google.com/file/d/1Qscbpb5hiXxmQ_6NrWSCMSU8WjO4sZ1l/view?usp=sharing)

Pre-trained IGGAN on Conditional CIFAR-10 dataset [[link]](https://drive.google.com/file/d/111HomJr-hFHRleP1OFMIGCCx4-I7fZhu/view?usp=sharing) 

Pre-trained IGGAN on Conditional 10% CIFAR-10 dataset [[link]](https://drive.google.com/file/d/191glBA2nS9HLBIT_ah2moWABS204ezHw/view?usp=sharing)

Pre-trained IGGAN on Unconditional CIFAR-100 dataset [[link]](https://drive.google.com/file/d/1DjyPujEf5XAuY7-zJYykCl35CpIu771W/view?usp=sharing)

Pre-trained IGGAN on Conditional CIFAR-100 dataset [[link]](https://drive.google.com/file/d/1AerOct_0j0rSRr68k5rSN2C2Oxx6jBSy/view?usp=sharing)

Pre-trained IGGAN on Conditional 10% CIFAR-100 dataset [[link]](https://drive.google.com/file/d/1HeTEM_kBsZ0pOlPsVMgpOvErxHfWjIJI/view?usp=sharing)

# Evaluation

To evaluate a pre-trained IGGAN model on Unconditional CIFAR-10, run the following command:
```shell
python eval.py --dataset=C10U --network='./pretrained/IGGAN_C10U.pth'
```


# Citation:
```
@inproceedings{zhang2024improving,
  title={Improving the Fairness of the Min-Max Game in GANs Training},
  author={Zhang, Zhaoyu and Hua, Yang and Wang, Hui and McLoone, Se{\'a}n},
  booktitle={Proceedings of the IEEE/CVF Winter Conference on Applications of Computer Vision},
  pages={2910--2919},
  year={2024}
}
```



