# Dataset Description

This repository directly provides two datasets to cater to different stages of development and evaluation:

1.  **CSL-Web482-Test (3,000 images)**: This version is created by sampling 1 out of every 10 images from the original dataset. It serves as a low-barrier entry point for **quick experiments, algorithm prototyping, and teaching demonstrations**. The data is already split into training, validation, and test sets.
2.  **CSL-Web482-Test(9000) (9,000 images)**: This version is the complete, independent test split from the original dataset. It is specifically intended for **final model performance evaluation and benchmarking**, providing more statistically representative and comparable results.

Furthermore, we provide permanent external download links for all versions to meet needs for archiving, citation, and alternative access.

### 🚀 In-Repository Datasets (Directly Available)
*   **`/CSL-Web482-Test/`** : Lightweight dataset (3,000 images, train/val/test split).
*   **`/CSL-Web482-Test(9000)/`** : Full test set (9,000 images, for evaluation only).

### 📥 Extended Datasets (External Permanent Links)
*   **3,000-image Dataset (Corresponds to the in-repo version)**: Identical to the `CSL-Web482-Test` in this repository, provided for permanent citation.
    *   **Link: [https://doi.org/10.6084/m9.figshare.31218427](https://doi.org/10.6084/m9.figshare.31218427)**
*   **Augmented Large Dataset (30,000 images)**: Has data augmentation applied and a more substantial split, suitable for full-scale training to improve model performance.
    *   Link: [https://doi.org/10.6084/m9.figshare.31220857](https://doi.org/10.6084/m9.figshare.31220857)
*   **Original Complete Dataset (Unsplitted)**: The most original collection of images for researchers who need full control over the processing pipeline.
    *   Link: [https://doi.org/10.6084/m9.figshare.31220788](https://doi.org/10.6084/m9.figshare.31220788)

### 💡 Usage Recommendations
- **For Quick Start & Validation**: Use the in-repository `CSL-Web482-Test` (3,000 images) folder.
- **For Final Evaluation & Paper Reporting**: Use the in-repository `CSL-Web482-Test(9000)` (9,000 images) folder to ensure comparable results.
- **For Full Model Training**: We recommend downloading the external **30,000-image Augmented Dataset** for optimal performance.
- **For Custom Data Processing & Permanent Citation**: Download from the corresponding external dataset links.

### 📄 License and Citation
If you use this dataset, please follow the license agreement of the original dataset. It is recommended to cite the corresponding permanent DOI link (as listed above) based on the specific version used in any related work.

---

# 数据集说明

本仓库直接提供两个数据集，以满足不同阶段的开发与评估需求：

1.  **CSL-Web482-Test（3000张图像）**：此版本通过“10抽1”的方式从原始数据集中采样得到，旨在为**快速实验、算法原型验证和教学演示**提供一个低门槛的起点。数据已划分为训练集、验证集和测试集。
2.  **CSL-Web482-Test(9000)（9000张图像）**：此版本为原始数据集中独立划分出的完整测试集，专用于模型的**最终性能评估与基准测试**，其结果更具统计代表性和可比性。

此外，我们也提供所有版本的永久外部下载链接，以满足存档、引用及不同获取方式的需求。

### 🚀 仓库内数据集（可直接获取）
*   **`/CSL-Web482-Test/`** ：轻量数据集（3000张，训练/验证/测试已划分）。
*   **`/CSL-Web482-Test(9000)/`** ：完整测试集（9000张，仅供评估使用）。

### 📥 扩展数据集（外部永久链接）
*   **3000张数据集（本仓库对应版本）**：与本仓库 `CSL-Web482-Test` 内容一致，提供永久引用地址。
    *   **链接：[https://doi.org/10.6084/m9.figshare.31218427](https://doi.org/10.6084/m9.figshare.31218427)**
*   **增强版大型数据集（30,000张）**：已应用数据增强，划分更充分，适用于需要提升模型性能的完整训练。
    *   链接：[https://doi.org/10.6084/m9.figshare.31220857](https://doi.org/10.6084/m9.figshare.31220857)
*   **原始完整数据集（未划分）**：最原始的图像集合，供需要完全自定义处理流程的研究者使用。
    *   链接：[https://doi.org/10.6084/m9.figshare.31220788](https://doi.org/10.6084/m9.figshare.31220788)

### 💡 使用建议
- **快速启动与验证**：请直接使用仓库内的 `CSL-Web482-Test` (3000张) 文件夹。
- **最终性能评估与论文报告**：请使用仓库内的 `CSL-Web482-Test(9000)` (9000张) 文件夹进行测试，以确保结果的可比性。
- **进行完整模型训练**：建议下载外部的 **30,000张增强版数据集** 以获得最佳性能。
- **自定义数据处理与永久引用**：可下载对应的外部数据集链接。

### 📄 许可与引用
若使用本数据集，请遵循原始数据集的许可协议。建议在相关工作中根据所使用的具体版本，引用对应的永久DOI链接（如上所列）。
