# yapi 安装配置
***
## 安装依赖
- nodejs
- git
- MongoDB

```sh
curl -sL https://rpm.nodesource.com/setup_10.x | sudo bash -
yum install nodejs -y
npm install pm2@latest -g
```

## 运行
- /usr/local/node-v8.9.3-linux-x64/bin/pm2 start server/app.js

## 访问
- http://nssas.eelantech.com:40008/

## 信息记录
- 初始化管理员账号成功,账号名："admin@admin.com"，密码："ymfe.org"

## 使用说明
*登录时使用注册邮箱进行登录，所有请记住自己的邮箱*
&ensp;&ensp;&ensp;&ensp;首先进行注册后联系管理员添加进相应的分组

## 参考链接
- [安装YApi](https://yapi.ymfe.org/documents/redev.html)