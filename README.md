# Git-command-example
Git command example，快速找到你需要命令

## 一，基础命令

### 1，配置用戶信息

#### 1.1，设置用户签名

```shell
git config --global user.name mowang
git config --global user.email mowangblog@qq.com,2
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

2.4，提交本地库

```shell
git commits -m'提交的注释信息' mowang.txt
```

