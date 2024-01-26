# Qt RHI

## 项目名称

使用Qt RHI的接口，实现计算给定图片的主色调。

## 项目描述

输入数据为png或jpg格式的图片，通过使用 Qt RHI 提供的计算 shader 的支持，在着色器中计算出输入图片中的主颜色（即被大范围使用的颜色区间），程序输出一个 RGB 颜色值

1. 使用 Qt6.6版本
2. 无需精准判断颜色，比如一张图片上有 25%的部分用了纯红色，25%的部分用了稍微淡一点的红色，剩下50%是丰富多彩的其它颜色，则输出的颜色可以处于纯红色和淡红色之间（比如进行加权平均计算）

## 项目导师

张丁元 `<zhangdingyuan@uniontech.com>`

## 难度

低

## 参考文档

1. https://doc.qt.io/qt-6/qrhi.html

## 预期目标

必须使用 Qt 完成目标，并且计算过程必须在 GPU 内执行，对 CPU 的消耗可以忽略不计。输入为一个图片路径，输出为一个 ARGB 的颜色值

## 从题目中能学到什么

1. Qt 库的使用方式
2. Qt RHI 框架
3. GPU 计算
4. 颜色相关概念和知识

## 涉及领域

1. Qt 开发库
2. 着色器语言
