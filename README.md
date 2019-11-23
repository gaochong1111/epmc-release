# 运行环境说明
```
操作系统: Linux/Mac
JAVA: >=JDK8
PYTHON: python3
    依赖: numpy, scipy
    安装命令: pip3 install numpy scipy
SPOT:
    下载网址: https://spot.lrde.epita.fr/install.html (包括安装方法)
    设置环境变量保证: ltl2tga 等命令可以在PATH中找到
```

# 测试版本运行
```
1. 解压
tar -xvzf distributions-20191123.tar.gz
2. 运行 run-example.sh
    Usage: 
    ./run-example.sh QCTL [LOOP|SUPERDENSE|DISTRIBUTION]
    or 
    ./run-example.sh QLTL [LOOP|RECURSIVE|EXP6]
```
