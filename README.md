# Multimodal-Pedestrian-Detection-System
Multimodal Pedestrian Detection System using LLVIP Dataset

**多模态行人检测系统（LLVIP Dataset）**
Python / PyTorch / Faster R-CNN

基于可见光与红外图像融合的人体目标检测系统，实现低光环境下的行人检测。

**项目内容：**

使用 PyTorch 构建目标检测模型

基于 Faster R-CNN + ResNet50-FPN 实现行人检测

使用 LLVIP 可见光-红外数据集进行训练

解析 XML 标注文件生成检测框数据

**技术实现：**

自定义 Dataset 类加载多模态图像数据

实现 RGB + 红外图像融合算法

使用 DataLoader 与自定义 collate_fn 处理检测任务数据

构建完整训练流程（train / evaluate）
