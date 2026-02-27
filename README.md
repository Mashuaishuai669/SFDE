## SFDE 2025 [[paper](https://arxiv.org/abs/2502.11381)][[model](#pre-trained-checkpoints)] [[Cite](#Citation)]
<h1 align="center">MultiLevel Joint Learning with Spatial and Frequency Domain Enhancement for Cross-View Geo-Localization</h1>
<h3 align="center"><strong>Hongying Zhang *</strong>, <strong>Shuaishuai Ma</strong>

<div align="center">
  </sup>School of Electronic Information and Automation, Civil Aviation University of China<br>
</div>

## <a id="table-of-contents"></a> 📚 Table of contents

- [Dataset Access](#dataset-access)
- [Dataset Structure](#dataset-structure)
- [Train and Test](#train-and-test)
- [Pre-trained Checkpoints](#pre-trained-checkpoints)
- [License](#license)
- [Acknowledgments](#acknowledgments)
- [Citation](#citation)

## <a id="dataset-access"></a> 💾 Dataset Access
Please prepare [University-1652](https://github.com/layumi/University1652-Baseline), [SUES-200](https://github.com/Reza-Zhu/SUES-200-Benchmark), [DenseUAV](https://github.com/Dmmm1997/DenseUAV)
## <a id="dataset-structure"></a> 📁 Dataset Process

### Process University-1652 Dataset  
```
run process_data/porcess_U1652.py
```
### Process SUES-200 Dataset  
```
run process_data/porcess_SUES-200.py
```
### Process DenseUAV Dataset 
```
run process_data/porcess_SUES-200.py
```
## <a id="train-and-test"></a> 🚀 Train and Test

#### University-1652 Dataset Configuration
```
# 3. train.py — Global dataset directory (used for testing)
parser.add_argument(
    '--data_dir',
    default='/your/path/dataset',
    type=str
)

2. Training and Testing

python train.py --only_test False

python train.py --only_test True --ckpt_path /path/to/your/checkpoint.pth
```

#### SUES-200 Dataset Configuration
```
The remaining code is scheduled to be updated in the near future.
```
#### DenseUAV Dataset Configuration
```
The remaining code is scheduled to be updated in the near future.
```
## <a id="pre-trained-checkpoints"></a> 🤗 Pre-trained Checkpoints
We provide the trained models in the link below:

https://pan.baidu.com/s/151fhP4kwW4rTXqjRRlSM6Q 提取码: sm8s 

We will update this repository for better clarity ASAP, current version is for quick research for researchers interested in the cross-view geo-localization task.

## <a id="license"></a> 🎫 License
This project is licensed under the [Apache 2.0 license](LICENSE).
