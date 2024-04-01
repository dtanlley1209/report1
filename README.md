# 南華大學Python程式設計-期中報告
11124127 王星圍 11124130 邱述陽
# 生成包含20個亂數的列表
ˋˋˋ
import random

x = [random.randint(0,100) for i in range(20)]
print(x)
ˋˋˋ
# 將前10個元素昇冪排列，後10個元素降冪排列，並輸出結果。
ˋˋˋ
y = x[0:10]
y.sort()
x[0:10] = y
y = x[10:20]
y.sort(reverse=True)
x[10:20] = y
print(x)
ˋˋˋ
![image](https://github.com/dtanlley1209/report1/blob/main/report1-6.png)
