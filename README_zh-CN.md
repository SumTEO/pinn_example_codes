# PINN 示例代码

[English](README.md) | 简体中文

[`pinn_code_tutorial.ipynb`](pinn_code_tutorial.ipynb) 是《PINN 代码实战》的可运行课件，包含三个由浅入深的例子：

- RC 电路：数据拟合、物理约束与参数反演
- 芯片稳态热分析：二维泊松方程与有限差分对照
- PN 结：电势与电场计算

## 运行

```bash
pip install jupyter torch numpy scipy matplotlib
jupyter notebook pinn_code_tutorial.ipynb
```

从上到下依次运行所有单元格。芯片和 PN 结示例包含 L-BFGS 精修，运行时间取决于硬件。

## 致谢

讲解顺序参考了 Theodore Wolf 的 [PINN PyTorch 教程](https://github.com/TheodoreWolf/pinns) 与 Ben Moseley 的 PINN 工作坊；本课件中的三个算例、代码和配图均由本课件运行生成。
