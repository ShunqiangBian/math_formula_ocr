# math_formula

数学公式识别，增强：中文公式、手写公式

Seq2Seq + Attention + Beam Search。

## 评价

perplexity    
EditDistance 
BLEU-4    
ExactMatchScore

perplexity 是越接近 1 越好，其余 3 个指标是越大越好。

## 致谢

论文：
1. [Show, Attend and Tell(Kelvin Xu...)](https://arxiv.org/abs/1502.03044)
2. [Harvard's paper and dataset](http://lstm.seas.harvard.edu/latex/)
3. [Seq2Seq for LaTeX generation](https://guillaumegenthial.github.io/image-to-latex.html).