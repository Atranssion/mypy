Git作为一个软件，是不需要Github就可以运行的，但它也是一个依赖网络的软件，使用Git与别人协作，你一定要有个Email地址。

在某个文件夹下用命令行进行初始化：
git init
完了之后用ll命令查看，会发现多了3个隐藏文件：
./	../	.git/	index.html/	style.css
出现.git之后，表示该目录已经成功初始化了。

纳入Git管辖的文件有四种状态：untracked；modified; staged; committed;



git list用来查看当前配置情况。



你自己创建的副本叫branch，别人抄你的，叫fork；

Git用三个个指针搞定版本定位，head，master和分支指针。


指定完毕本地仓库地址与远程仓库地址后，要让它们关联起来。方法是
