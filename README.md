# FashionMNIST Softmax 线性分类
## 模型说明
手动从零实现 Softmax 回归（单层线性多分类模型），无隐藏层、无卷积层。
1. 图像预处理：28*28灰度图展平为784维向量
2. 网络：单层线性变换 XW + b + Softmax
3. 损失：手动实现交叉熵损失 cross_entropy
4. 优化：手写SGD随机梯度下降
## 训练参数
epochs=10，学习率lr=0.1
## 结果
训练集准确率约0.848，测试集泛化准确率约0.83

## 训练可视化
![训练曲线](<"https://github.com/user-attachments/assets/28b2ebf0-1311-40f5-a1f9-76d7766bbac4" />
)
