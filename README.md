# 战矛圈

## 6月更新计划

- 增加点击量的显示
- 部分错误信息的友好提示
- 详情页美化
- 增加评论功能
- 长时间未激活用户的清理

## 更新记录

### 2019.6.16

- 修复金币价格不能输入小数的问题
- 修复注册和修改用户名时，不合格依旧显示合格的问题
- 增加价格另议的可选项
- 调整市场页面的 item-cell 下边距，露出灰色背景

### 2019.6.15

- 依赖的框架 js 文件采用cdn加速，提示访问速度
- 修复详情页中创建时间显示的问题
- 修复详情页刷新显示空白问题

### 2019.6.14 

- 增加一台服务器，解决内存不足导致服务下线的问题
- 修复阿里云封锁25端口导致注册邮件无法发送的问题
- 修复又拍云上传凭证签发失败的问题
- 优化又拍云签发信息获取逻辑，在springboot启动时就创建bean实例，从数据库中获取，避免重复查询数据库
- 修复"我的"页面中刷新后丢失状态导致重发激活邮箱按钮显示的问题

### 2019.6.13 

项目完成，发布最初版本