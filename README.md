# asm-practice
8086汇编小程序，键盘控制。

## 运行环境
代码在`pce/ibmpc`以及`DOSBox`中测试有效。

## 功能描述
程序运行后：
- 前`10`秒，界面变为红底白字，键盘输入被禁止
- 后`10`秒，界面变为绿底白字，允许键盘输入，但对键入的字母进行了凯撒加密，例如，键入'a'得到的是'b'，键入'Z'得到的是'A'
- 上述过程一直循环交替出现，直到用户键入`F4`，退出循环，界面恢复原来的黑底白字
