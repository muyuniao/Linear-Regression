# 基于PyTorch的线性回归模型

本项目实现了一个简单的线性回归模型，使用PyTorch框架进行数据生成、模型训练和结果可视化。代码以Jupyter Notebook形式呈现，适合机器学习初学者学习线性回归的基本原理和PyTorch的基本操作。

---

## 项目结构
```python
LinearRegression.ipynb
README.md
```

## 环境依赖

- Python 3.6+
- PyTorch 1.0+
- numpy
- matplotlib

> **注**：代码中`os.environ['KMP_DUPLICATE_LIB_OK']='True'`是为解决某些环境下matplotlib的内核崩溃问题，正常环境可移除。

------

## 注意事项

1. 可调整超参数（学习率、训练轮次）观察模型变化
2. 噪声参数（`noise = np.random.normal(0, 0.01, x_data.shape)`）可修改以生成不同分布数据
3. 理想情况下损失值应随训练逐步下降并最终稳定

------

## 如何运行

1. 安装依赖：`pip install torch numpy matplotlib`
2. 执行Jupyter Notebook：`jupyter notebook LinearRegression.ipynb`