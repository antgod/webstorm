- 显示行号
```
vim ~/.vimrc
加一行 set number
```

- 光标
```
 gg              移动光标到文档首行.
 G               移动光标到文档尾行.
 :n              跳至第n行
 H               移动光标到屏幕的首行.
 M               移动光标到屏幕的中间一行.
 L               移动光标到屏幕的尾行.
```

- 翻页
```
 ctrl + f        向下翻页 同 page down.
 ctrl + b        向上翻页 同 page up.
 ctrl + d        向下翻半页 此比较有用
 ctrl + u        向上翻半页 此比较有用
 ctrl + e        向下翻一行
 ctrl + y        向上一行
```
- 快速跳转
```
 ''   两个单引号 此命令相当有用, 它移动光标到上一个标记处, 比如用 gd, * 等查找到某个单词后, 再输入此命令则回到上次停留的位置.
 '.   一单一点   此命令相当好使, 它移动光标到上一次的修改行.
```

- 查找
```
 [[              转到上一个位于第一列的“{”
 ]]              转到下一个位于第一列的“}”
 {               转到上一个空行
 }               转到下一个空行
```

- 多文件
```
vim FILE1 FILE2 FILE3
:next 切换至下一个文件
:prev 切换至前一个文件
:last 切换至最后一个文件
:first 切换至第一个文件
:q退出当前文件
:qa 全部退出
```

- 编辑
```
yy|2yy 复制行
dd|2dd 删除、剪切行
p粘贴到下一行
P粘贴到上一行
^|$定位到行首，行尾
dG从当前行删到文档最后一行
```

