## 安装脚手架

```
npm install -g yog2
```

## 快速创建基础运行框架

```
$ yog2 init project

[NOTIC] Downloading and unzipping...
prompt: Enter your project name:  (yog)
[NOTIC] Done

cd yog
npm install

yog2 run
```

## 快速创建多个应用

```
$ yog2 init app

[NOTIC] Downloading and unzipping...
prompt: Enter your app name:  (home) webapp
[NOTIC] Done
```

```
$ yog2 init app

[NOTIC] Downloading and unzipping...
prompt: Enter your app name:  (home) wxapp
[NOTIC] Done
```

## 部署app

```
cd webapp
yog2 release --dest debug

http://127.0.0.1:8085/webapp
```