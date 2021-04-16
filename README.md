# upload-labs

## 拉取环境

```shell
git clone 环境地址
```



## 建立主环境

```shell
cd 项目文件夹中
docker build -t upload-labs .
```

## 建立单个环境

```shell
cd 关卡文件夹
docker build -t upload/pass:1(your subject) .
```

## shell.sh用法

```shell
建立了一个快捷启动脚本
目的是为了快速启动每个独立的关卡
用法：
1、授权
chmod 755 shell.sh
2、启动
./shell.sh(题目数例：01) (端口映射号)
```

