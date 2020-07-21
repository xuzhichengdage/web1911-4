# 打开vscode命令行工具

```
ctrl + `（ESC下面的符号）
```

## 本地源代码管理

1、生成一个git仓库

```shell
git init
```
命令执行后，会在当前的工作目录里生成一个.git文件夹，这个目录是当前项目的仓库文件夹，
以后不能删除这个目录，删除后，代码的记录就没了！

2、添加代码的变更文件到暂存更改里
```shell
git add <文件路径|文件夹路径>
```

3、提交暂存（确认存储）
```shell
git commit -m "描述"
```

4、查看分支
```shell
git branch
```
5、创建分支
```shell
git branch 分支名称
```



