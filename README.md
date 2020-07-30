Lisp-Calculator
===

![Language](https://img.shields.io/badge/Language-Common&nbsp;Lisp-blue.svg?style=flat-square) ![Compiler](https://img.shields.io/badge/Compiler-CLISP&nbsp;2.49-alice.svg?style=flat-square)

[![Gitee](https://img.shields.io/badge/Gitee-辰落火辉Haceau-red.svg?style=flat-square)](https://gitee.com/haceau/Lisp-Calculator)
[![Github](https://img.shields.io/badge/Github-HaceauZoac-skyblue.svg?style=flat-square)](https://github.com/Haceau-Zoac/Lisp-Calculator)

简介
---
该项目为练习Common Lisp写的计算器，输入格式同Common Lisp。当前版本为v1.0.0。开源许可证为WTFPL。

使用
---
加：(+ 12 23 -5) => 30

减：(- (+ 100 200) (- 300 400) 100) => 300

乘：(* (- (+ -1 +1) -100) 100) => -10000

除：(/ 10086 681) => 3362/227

数字：123456 => 123456

退出：(exit) 或 (quit) => 退出

* 大部分的结果都和CLISP 2.49的结果一样。

待办清单
---
|完成版本|内容|
|-------|---|
|1.0.x|长期维护|