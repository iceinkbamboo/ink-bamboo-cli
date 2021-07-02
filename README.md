# ink-bamboo-cli
- install
```
npm install --save ink-bamboo-cli
```
- use
```
import { dateConversion } from "ink-bamboo-cli"
// time-时间戳ms
// 返回时间差
dateConversion(time)
```

# 发布npm的流程
1. 注册npm账号
2. 创建项目
3. git init初始化
4. 写逻辑
5. 登录npm
```
npm login
根据提示依次输入账号、密码、邮箱
```
6. 修改发布版本号
```
npm version 版本号（1.1.0）
```
7. 发布
```
npm publish
```