# C语言 Code Golf 题库

这是一个 C 语言 Code Golf 题库，包含 10 道难度递增的编程题目，旨在帮助同学们更有趣味地学习 C 语言。

## 什么是 Code Golf？

Code Golf 是一种编程竞赛，目标是用最短的代码解决给定的问题。这不仅考验编程能力，还能锻炼对语言特性的深入理解和创造性思维。

## 题目列表

| 编号 | 题目 | 难度 | 关键词 |
|------|------|------|--------|
| 01 | [数字根](problems/01_digital_root/01_digital_root.md) | 1/10 (入门) | 数学技巧, 循环优化, 模运算 |
| 02 | [回文数判断](problems/02_palindrome_number/02_palindrome_number.md) | 2/10 (简单) | 回文, 数学运算, 逻辑判断 |
| 03 | [质数判断](problems/03_prime_checker/03_prime_checker.md) | 3/10 (中等偏易) | 质数, 数论, 算法优化 |
| 04 | [二进制表示](problems/04_binary_representation/04_binary_representation.md) | 4/10 (中等) | 进制转换, 位运算, 递归 |
| 05 | [斐波那契取模](problems/05_fibonacci_mod/05_fibonacci_mod.md) | 5/10 (中等偏难) | 斐波那契数列, 动态规划, 矩阵快速幂 |
| 06 | [矩阵旋转](problems/06_matrix_rotate/06_matrix_rotate.md) | 6/10 (困难) | 矩阵操作, 空间优化, 就地算法 |
| 07 | [最长递增子序列](problems/07_longest_increasing_subsequence/07_longest_increasing_subsequence.md) | 7/10 (困难偏上) | 动态规划, 二分查找, LIS算法 |
| 08 | [表达式求值](problems/08_expression_evaluation/08_expression_evaluation.md) | 8/10 (很困难) | 栈, 表达式解析, 递归下降 |
| 09 | [最短路径](problems/09_shortest_path/09_shortest_path.md) | 9/10 (地狱) | 图论, Dijkstra算法, 最短路 |
| 10 | [背包问题优化](problems/10_knapsack_optimization/10_knapsack_optimization.md) | 10/10 (地狱级别) | 动态规划, 背包问题, 空间优化 |

## 目录结构

```
problems/
├── 01_digital_root/
│   ├── 01_digital_root.md          # 题目描述
│   └── testcases/                   # 测试用例
│       ├── input1.txt
│       ├── output1.txt
│       ├── input2.txt
│       └── output2.txt
├── 02_palindrome_number/
│   ├── 02_palindrome_number.md
│   └── testcases/
│       └── ...
...
```

## 题目格式

每道题目的 Markdown 文件包含以下部分：

1. **标题**：题目名称
2. **关键词**：题目涉及的核心概念和技术
3. **难度**：1-10 的难度评级
4. **题面**：完整的问题描述，包括输入输出格式
5. **示范样例**：多个测试样例及其预期输出
6. **提示**（可选）：对于特别困难的题目，提供解题思路

## 测试用例

每道题目的 `testcases` 目录包含多组测试用例：
- `input1.txt`, `input2.txt`, ... - 输入数据
- `output1.txt`, `output2.txt`, ... - 对应的预期输出

## 使用建议

1. **循序渐进**：从难度 1 开始，逐步挑战更高难度
2. **追求极致**：尝试用最少的字符数解决问题
3. **学习技巧**：研究各种 C 语言的简写技巧和特性
4. **测试验证**：使用提供的测试用例验证你的解答
5. **交流分享**：与同学讨论不同的解法和优化思路

## Code Golf 技巧

- 使用单字母变量名
- 利用 C 语言的运算符优先级减少括号
- 善用三元运算符 `? :`
- 利用逗号运算符组合语句
- 使用递归代替循环（在某些情况下）
- 了解标准库函数的简写形式
- 利用位运算进行数学优化

祝你在 Code Golf 的旅程中收获满满，编程愉快！
