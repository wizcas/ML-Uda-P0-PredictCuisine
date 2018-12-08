# 机器学习工程师纳米学位 P0 预测料理
## 项目0：预测你的下一道世界料理

### 准备工作

这个项目需要安装 **Python3** 和以下的 Python 函数库：

- [Pandas](https://pandas.pydata.org/)
- [NumPy](http://www.numpy.org/):数值计算
- [matplotlib](http://matplotlib.org/): 用于画图
- [nltk](https://www.nltk.org/): 用于处理单词文本
- [scikit-learn](http://scikit-learn.org/stable/): 用于模型训练和分析
- [jupyter,notebook](http://jupyter.org/): 实验基本环境，以运行和编辑 `.ipynb`

```bash
conda install nltk
python -c "import nltk; nltk.download('wordnet')"
```

### 运行

```jupyter notebook PredictYourCuisine.ipynb```

### 数据

此项目的数据集来自[Kaggle What's Cooking](https://www.kaggle.com/c/whats-cooking/data) 竞赛。共 39774/9944 个训练和测试数据点，涵盖了中国菜、越南菜、法国菜等的信息。

### 提交说明

课程项目提交文件位于*submission*目录下
