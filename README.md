# Interview-Notebook-PDF
https://github.com/CyC2018/Interview-Notebook PDF版本离线阅读

用于提供 https://github.com/CyC2018/Interview-Notebook 项目的离线阅读

本pdf使用 cmd-markdown 的付费工具进行pdf的转换。
目前已经有两个已经转化好的pdf

对于pdf转换需要对原有md文件进行删除

## 1. 删除目录
```
<!-- GFM-TOC -->
***
<!-- GFM-TOC -->
```

## 2. 字符串替换

###2.1 

对于所有的图片地址进行替换

例如：

`src="../pics//f5757d09-88e7-4bbd-8cfb-cecf55604854.png"`

替换为

`src="https://github.com/CyC2018/Interview-Notebook/raw/master/pics/f5757d09-88e7-4bbd-8cfb-cecf55604854.png"`

###2.2 

所有的`width=""`都需要删除
使用正则表达式 `width="[0-9]*"`进行替换
