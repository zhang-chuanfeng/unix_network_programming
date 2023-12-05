# unix_network_programming

[参考unpbook源码](https://github.com/unpbook/unpv13e)

1. 自动生成config.h Make.defines Makefile  目的是编译生成libunp.a库
```
./configure
```

2. make生成program
```
make daytimetcpcli

// 公网测试端口13获取时间 time.nist.gov
./daytimetcpcli 128.138.141.172
```

3. make clean

4. make distclean
