# JTExe
Jar GUI 文件转 Exe 程序

# 注意事项

bin 文件夹要和 src 文件夹的结构保持一致，如果是 out 文件，就请改成 bin，并且结构保持和 src 文件夹一样。例如：

正确：
```
-src
  -cn
    -bug
      -jtexe
        -文件名1
        -文件名n
-bin
  -cn
    -bug
      -jtexe
        -文件名1
        -文件名n
```


错误：

```
-src
  -cn
    -bug
      -jtexe
        -文件名1
        -文件名n
-bin
  -cn
      -jtexe
        -文件名1
        -文件名n
```

```
-src
    -bug
      -jtexe
        -文件名1
        -文件名n
-bin
  -cn
    -bug
      -jtexe
        -文件名1
        -文件名n
```

```
-src
  -cn
    -bug
      -jtexe
        -文件名1
        -文件名n
-out
  -cn
    -bug
      -jtexe
        -文件名1
        -文件名n
```
**bin 文件夹结构必须和 src 保持一致！！！**
