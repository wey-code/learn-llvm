# learn-llvm

基于[https://llvm.org/docs/tutorial/MyFirstLanguageFrontend/index.html](https://llvm.org/docs/tutorial/MyFirstLanguageFrontend/index.html)编写的一个小demo。

编译chapter2的命令为：
```bash
clang++ -g -O3 xxx.cpp `llvm-config --cxxflags`
```

编译chapter3的命令为：
```bash
clang++ -g -O3 xxx.cpp `llvm-config --cxxflags --ldflags --system-libs --libs core`
```