# minority_game_implemented_concisely

[少数派博弈](https://zh.wikipedia.org/zh-hans/少数派博弈)是`张翼成`等学者受[酒吧问题](https://en.wikipedia.org/wiki/El_Farol_Bar_problem)启发而提出的。
- 在这一博弈中，参与者们拥有两种选择（例如0和1）。
- 所有人都做出选择之后，将参与者按照所做的选择分为两派。
- 人数较少的那一派，也就是少数派，将会获胜。

这里的实现实际是[minority_game](https://github.com/morningmorningwind/minority_game)的一个分支，
只是参考`Wolframe`在处理元胞机时的策略编码技巧，从而简化了代码。
简化后的代码仍包含`策略`，`个体`，`环境`三个类，但总代码量只有60行。
