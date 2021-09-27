# Git-command-example
Git command example，快速找到你需要命令

## 一，基础命令

### 1，设置用户签名

```shell
git config --global user.name mowang
git config --global user.email mowangblog@qq.com
```

### 2，查看用户签名信息

```shell
git config user.name
git config user.email
```

### 3，初始化本地库

```shell
git init
```

### 4，查看本地库状态

```shell
git status
```

### 5，添加暂存区

```shell
git add 文件名.后缀
git add . //全部提交
```

### 6，提交本地库

```shell
git commit -m"first commit" mowang.txt
```

### 7，查看历史版本

```shell
git reflog //精简显示版本日志
git log //详细显示版本日志
```

### 8，版本切换

```shell
git reset 94aa244 
git reset --hard 94aa244 
//94aa244为版本号的前7位
```

## 二，分支命令

### 1，创建分支

```shell
git branch 分支名
```

### 2，查看分支

```shell
git branch -v
```

### 3，切换分支

```shell
git checkout 分支名
```

### 4，合并分支

```shell
git merge 分支名
```

## 三，远程库命令

### 1，查看远程仓库别名

```shell
git remote -v
```

### 2，添加远程仓库地址和别名

```shell
git remote add 别名 远程地址
```

### 3，推送代码到远程库指定分支

```shell
git push 别名 分支
```

### 4，拉取远程仓库代码

```shell
git pull 别名 分支
```

### 5，克隆远程仓库代码

```shell
git clone git@github.com:mowangblog/Git-command-example.git 
//git@github.com:mowangblog/Git-command-example.git 是远程仓库地址ssh方式
//克隆代码不需要权限，提交代码需要权限
```

### 6，配置ssh免密登录

参考我写的这篇文章

[https://mowangblog.top/mowang/git-ssh](https://mowangblog.top/mowang/git-ssh)
