# math_formula

数学公式识别，增强：中文公式、手写公式

Seq2Seq + Attention + Beam Search。

## 评价

|      指标       | 训练分数 | 测试分数 |
| :-------------: | :------: | :------: |
|   perplexity    |   1.12   |   1.13   |
|  EditDistance   |  94.16   |  93.36   |
|     BLEU-4      |  91.03   |  90.47   |
| ExactMatchScore |  49.30   |  46.22   |

perplexity 是越接近1越好，其余3个指标是越大越好。

其中 EditDistance 和 BLEU-4 已达到业内先进水平

将 perplexity 训练到 1.03 左右，ExactMatchScore 还可以再升，应该可以到 70 以上。

机器不太好，训练太费时间了。

## 致谢

论文：
1. [Show, Attend and Tell(Kelvin Xu...)](https://arxiv.org/abs/1502.03044)
2. [Harvard's paper and dataset](http://lstm.seas.harvard.edu/latex/)
3. [Seq2Seq for LaTeX generation](https://guillaumegenthial.github.io/image-to-latex.html).