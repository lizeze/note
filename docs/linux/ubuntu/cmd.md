# 命令行的历史记录
## 按顺序查找
* 向上键：按使用顺序向前查找用过的命令，每按一次就前进一个命令。
* 向下键：按使用顺序向后查找用过的命令，每按一次就前进一个命令。
> 虽然简单但是使用起来并不是很方便，找之前的命令时会花费大量的时间，这个时候可以使用查找的方法

##  查找使用过的命令
 比如我查看过某个文件，想再次修改时就可以使用`Ctrl
 `+`R`组合直接输入文件的名称，就会自动补全命令，如下图
  ![](https://p6-juejin.byteimg.com/tos-cn-i-k3u1fbpfcp/b76fc240717c4ec3abeb769efcaf925e~tplv-k3u1fbpfcp-zoom-1.image)

  输入`sys`自动补全
## 查看历史记录
   `history`,用于列出之前使用过的命令，如下图
  ![](https://p1-juejin.byteimg.com/tos-cn-i-k3u1fbpfcp/a9659a075a1a4523bf1137e171755c6a~tplv-k3u1fbpfcp-zoom-1.image)

  使用过的命令都是有编号的，可以使用`!编号`的方式调用命令
  ```shell
  $ history
  $ !1
  ```
## 一些常用的快捷键

 * `Ctrl+L` 清理终端内容

 * `Ctrl + A` 光标跳到一行命令的开头
 
 * `Ctrl + E` 光标调到一行命令的结尾
 
 * `Ctrl + U` 删除所有在光标左侧的命令字符
 
 * `Ctrl + K` 删除所有在光标右侧的命令字符
 
 * `Ctrl + W` 删除光标左侧的一个单词，这里的单词指的是用空格隔开的一个字符串
 
 * `Ctrl + Y` 粘贴上面命令删除的内容