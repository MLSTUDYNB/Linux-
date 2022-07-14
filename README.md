# Linux

[TOC]



# Linux基本命令

使用命令的基本形式：

`命令 选项 参数`注意要有空格

## ls

+ 显示文件或目录

选项：

```
-a 	隐藏文件也显示出来
-l	显示详细信息
-i	列出inode号码
```

![image-20220714183717134](https://s2.loli.net/2022/07/14/bqI9rQZ5msJBldG.png)

## pwd

+ 显示当前用户所在的目录

![image-20220714184113773](https://s2.loli.net/2022/07/14/M2uRwDSFO4xtsbh.png)

## cd

+ 切换到某一目录下

![image-20220714185213929](https://s2.loli.net/2022/07/14/HdpYNvQy9PZX1LG.png)

### 路径

+ 绝对路径：从根目录开始到指定的目录
+ 相对路径：从当前路径下到指定目录

## touch

+ 创建一个普通文件，或者更改文件或目录的信息

![image-20220714185653435](https://s2.loli.net/2022/07/14/zxteGngHukOyS7U.png)



## stat

+ 显示文件或文件系统状态

![image-20220714192311946](https://s2.loli.net/2022/07/14/KVTOWnMASkBZE9L.png)

## mkdir

+ 创建一个目录

选项：

`-P`：可递归创建目录

<img src="https://s2.loli.net/2022/07/14/TQRiruUy1L4jK3c.png" alt="image-20220714192813952"  />

## rmdir

+ 删除一个空目录

选项：`-p`：如果删除目录的父目录也是空目录，也把该父目录也删去。

![image-20220714201016100](https://s2.loli.net/2022/07/14/2kuTifo8AngwQ9d.png)

## rm

+ 删除目录或者文件

选项：

`-r`：递归式删除，删除目录及以下文件

`-f`：强制删除

![image-20220714201919300](https://s2.loli.net/2022/07/14/BRjgWYU5coAvwd1.png)

## man

+ 查询手册

`man+指令`

例如：`man ls`

<img src="https://s2.loli.net/2022/07/14/iHtabr8vLn5pxgw.png" alt="image-20220714202201135" style="zoom:50%;" />

## cp



## mv

## cat

## more

## less

## head

## tail

## find

## grep

## zip/unzip

## tar

## uname -r





