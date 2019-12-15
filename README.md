# Qt 拼音输入法，采用Google拼音内核

## 文件夹说明

* googlepinyin<br>
Google拼音核心源码

* plugin<br>
输入法插件源码

* window<br>
对输入法的简单测试窗口

* Windows_test<br>
Windows上运行测试结果

## 编译说明
1. 先编译测试程序，再编译googlepinyin源码；
2. 把编译好的库文件libgooglepinyin.a放到plugin/googlepinyin目录下；
3. 再编译plugin源码，把编译后的库文件放到测试程序执行文件所在目录下的platforminputcontexts文件夹下；
4. 复制plugin目录下的dict目录到测试程序执行文件所在目录下；
5. 运行window测试代码即可测试输入法。

## 测试结果
![测试结果](https://github.com/tgtsml/QtInputMethod_GooglePinyin/blob/master/test_exe/test.png)


