# LocalGLMnet 的 group LASSO 与变量选择（任务 22）

- [任务书](第22题%20LocalGLMnet的LASSO正则化%20综合性研讨题（学生版·任务书）.md)
- [实现与延伸追问答案](任务22_LocalGLMnet_GroupLASSO.ipynb)

数据位于 `data/freMTPL2freq.csv` 和 `data/freMTPL2sev.csv`，来自 [CASdatasets](https://github.com/dutangc/CASdatasets)。运行 notebook 需要 Python 的 `numpy`、`pandas`、`scikit-learn`、`torch`、`matplotlib` 和 `nbformat`。建议使用本机 `/opt/anaconda3/envs/myenv/bin/python` 内核。默认使用全部保单；首次调试可设置 `MAX_ROWS=20000`。

notebook 包含教材 Listing 13.1 对应的索赔次数修正、38×9 组矩阵、三档正则拟合、测试集重要性图、`Region` 置换阴性对照及 10 道延伸追问答案。训练时长随硬件变化。
