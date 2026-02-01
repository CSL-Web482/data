# data
CSL-486 Dataset Data Warehouse
数据集说明

本仓库提供了一个包含3000张图像的轻量数据集，适用于快速实验、算法验证或教学演示等场景。

数据集来源与背景：
该数据集源于一个大规模原始数据集。由于原数据集体积过大，不便直接存储与传播，我们通过10抽1的方式从中均匀采样，构建了这个小型数据集，便于用户轻量、快速地使用。

数据集下载：
根据你的需要，可选择以下不同版本的数据集：

- 小型数据集（本仓库推荐）：3000张，未增强，已划分（训练/验证/测试）
  获取地址：https://doi.org/10.6084/m9.figshare.31218427

- 增强版大型数据集：30000张，已增强，已划分
  获取地址：https://doi.org/10.6084/m9.figshare.31220857

- 原始完整数据集：约30,000+张，未增强，未划分
  获取地址：https://doi.org/10.6084/m9.figshare.31220788

使用建议：
- 如果你希望快速运行实验、测试流程或进行初步验证，建议直接下载3000张已划分数据集。
- 如果需要更多数据以提升模型性能或进行更充分的训练，请下载30000张增强版数据集。
- 如需获取最原始、未经任何处理的全部图像，可通过原数据集链接下载。

许可与引用：
若使用本数据集（包括其原始或增强版本），请遵循原始数据集的许可协议，并建议在相关工作中注明出处（如DOI链接）。
# Dataset Description

This repository provides a lightweight dataset containing **3000 images**, suitable for quick experiments, algorithm validation, or teaching demonstrations.

## Dataset Source and Background
This dataset originates from a large-scale original dataset. Due to the large size of the original dataset, which makes direct storage and distribution inconvenient, we constructed this smaller dataset by uniformly sampling **1 out of every 10 images** from the original set. This allows for lightweight and quick usage.

## Dataset Download
Depending on your needs, you can choose from the following different versions of the dataset:

- **Small Dataset (Recommended for this repository)**: 3000 images, not augmented, **already split** (train/validation/test)
  Download link: https://doi.org/10.6084/m9.figshare.31218427

- **Augmented Large Dataset**: 30000 images, augmented, already split
  Download link: https://doi.org/10.6084/m9.figshare.31220857

- **Original Complete Dataset**: Approximately 30,000+ images, not augmented, not split
  Download link: https://doi.org/10.6084/m9.figshare.31220788

## Usage Recommendations
- If you want to quickly run experiments, test pipelines, or conduct preliminary validation, we recommend downloading the **3000-image split dataset**.
- If you need more data to improve model performance or conduct more comprehensive training, please download the **30000-image augmented dataset**.
- If you need the most original, unprocessed complete set of images, you can download it via the original dataset link.

## License and Citation
If you use this dataset (including its original or augmented versions), please follow the license agreement of the original dataset, and it is recommended to cite the source (such as the DOI link) in any related work.
