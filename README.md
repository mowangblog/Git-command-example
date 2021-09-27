# Git-command-example
Git command example，快速找到你需要命令

## 一，基础命令

### 1，配置用戶信息

#### 1.1，设置用户签名

```shell
git config --global user.name mowang
git config --global user.email mowangblog@qq.com
```

#### 1.2，查看用户签名信息

```shell
git config user.name
git config user.email
```

### 2，操作本地库

#### 2.1，初始化本地库

```shell
git init
```

#### 2.2，查看本地库状态

```shell
git status
```

#### 2.3，添加暂存区

```shell
git add 文件名.后缀
git add . //全部提交
```

#### 2.4，提交本地库

```shell
git commit -m"first commit" mowang.txt
```

### 3，历史版本

#### 3.1，查看历史版本

```shell
git reflog //精简显示版本日志
git log //详细显示版本日志
```

#### 3.2，版本切换

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

### 1，远程库操作

#### 1.1，查看远程仓库别名

```shell
git remote -v
```

#### 1.2，添加远程仓库地址和别名

```shell
git remote add 别名 远程地址
```

#### 1.3，推送本地库分支到远程库指定分支
