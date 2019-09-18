# persist
code


|         模型         | CTB5/dev  | CTB5/test  | PD1/dev | PD1/test  |
|:--------------------:|:---------:|:----------:|:-------:|:---------:|
|   Baseline BiLSTM    | 94.87 | 94.33 | **96.20** | 96.16 |
| Neural Coupled Model | **95.81** | **95.45** | 96.07 | **96.19** |

|         模型         | CTB5/dev  | CTB5/test  | PD2/dev | PD2/test  |
|:--------------------:|:---------:|:----------:|:-------:|:---------:|
|  Multi-Task Learning | 95.95 | 95.89 | 97.53 | 97.42 |
| Neural Coupled Model | **95.99** | **95.96** | **97.64** | **97.56** |

|         模型         | CTB5-test/P  | CTB5-test/R  | CTB5-test/F | PD1-test/P  | PD1-test/R  | PD1-test/F |
|:--------------------:|:---------:|:----------:|:-------:|:---------:|:---------:|:---------:|
|   Baseline BiLSTM    | 88.96 | 89.66 | 89.31 | **92.77** | **92.65 | **92.71** |
| Neural Coupled Model | **90.66** | **90.66** | **90.51** | 92.28 | 92.28 | 92.37 |


|         模型         | PD-to-CTB 转化准确率 |
|:--------------------:|:-------------------:|
|   Baseline BiLSTM    | 91.49 |
| Neural Coupled Model(with PD1) | 93.36 |
| Neural Coupled Model(with PD2) | **94.54** |
