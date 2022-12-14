# QingWheel/轻轮
Lightweight React Scaffold  
轻量级React脚手架  
  
![](./docs/image/Qw.jpg)
## 定位
React初学者的入门示例  
个人开发者的提效模板   
小微团队的协同范本
## Qing系列
### React-JavaScript版
- [React18 + React-Router6 + Redux](https://github.com/ArtanisW/qw-react-router-redux) 
- [React18 + React-Router6](https://github.com/ArtanisW/qw-react-router) 
- [React18](https://github.com/ArtanisW/qw-react)
### React-TypeScript版
开发中，敬请期待
### Qing-Node
- [qw-koa2](https://github.com/ArtanisW/qw-koa2)开发中
## 背景
当你从零开始搭建React脚手架时，有木有觉得很繁琐  
create-react-app配置隐晦，xx企业级框架过于厚重  
一些前端的内卷，已经卷到了造很多重复的轮子，来凸显自身价值  
大量的业务封装，让你脱离了公司框架，忘记了纯净的React体系是啥样

轻轮，0糖0私货，不造假轮子，安心拧螺丝！  
## 起步
前端新手请参考[萌新指南](./docs/MENG_XIN.md)  
使用时，先fork或者自己新建一个空的git工程，然后迁移代码  
安装过程如有异常请提issue，会定期更新在[常见问题](./docs/Q%26A.md)
## 运行环境
截至目前的Node LTS版本运行稳定，低版本没测。  
测了有问题也不要提issue，不考虑向下兼容。  
问就是建议升级。
```
node -v // 16.16.0
npm -v // 8.11.0
```
## 运行项目
参考package.json中的script
```
启动开发环境：npm start(监控配置模式)
// 上述模式会监控webpack配置，自动重启服务，需要全局安装nodemon)
// npm i -g nodemon
启动开发环境：npm run dev(常规模式)
构建测试环境：npm run qa
构建正式环境：npm run prod
```
## 注意
仅供学习使用；未经授权不得用于商业用途
