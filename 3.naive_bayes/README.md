# 朴素贝叶斯实现

## 使用方式

    cls = NBayes()
    x = [[1, 2], [2, 3], [2, 1]]
    y = [0, 1, 1]
    cls.train(x, y)
    print(cls.predict([2, 1]))

## 模型定义

    利用贝叶斯定理于特征条件独立假设

## 损失函数
    0-1损失函数

