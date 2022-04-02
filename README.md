## crontab-ui 

可视化的 crontab 管理系统

fork from：https://github.com/alseambusher/crontab-ui

## 1. 如何使用

安装依赖: `npm install`

安装 pm2: `npm install pm2 -g`

启动项目并自动保存定时任务:

`pm2 start app.js -- <账号> <密码> --autosave`

或:

`node app.js <账号> <密码> --autosave`


如:

`node app.js user1 pass1 --autosave`