# head

## 描述

用于显示文件的开头的内容.在默认情况下，head命令显示文件的头**10**行内容.

## 格式

    head [OPTION]... [FILE]...

## 选项

- -n<数字> ： 指定显示头部内容的行数
- -c<字符数> ： 指定显示头部内容的字符数
- -v ： 总是显示文件名的头信息
- -q ： 不显示文件名的头信息

## 例

    # head -10 2016.txt <=> head -10 2016.txt # 前10行