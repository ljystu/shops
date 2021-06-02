# Campus-shops

# 导语

### 项目数据库和部署视频，获取方式
### 关注公众号：理木客，后台回复：shop 
### 项目的数据文件请加QQ群：994793967  获取
### QQ群：994793967 内会不定期上传项目源码和学习资料，群内也有考研的研友欢迎进群交流 :smile: 
![](https://images.gitee.com/uploads/images/2021/0330/182006_9a40275f_3026905.jpeg "1.jpg")
![](https://images.gitee.com/uploads/images/2021/0330/182017_93054a81_3026905.jpeg "2.jpg")
![](https://images.gitee.com/uploads/images/2021/0330/182024_a36815c2_3026905.jpeg "3.jpg")

### 如需更多项目资源和学习资源，请加入此群：671408308
### 项目演示视频：[Springboot + Vue.js 的校园二手交易商城](https://www.bilibili.com/video/BV16X4y1V7ay/)
### 短信验证码及支付接口申请演示视频：[如何申请短信验证码接口和支付宝支付接口](https://www.bilibili.com/video/BV1Wh411Q76C/)
### 项目部署视频：请关注公众号 理木客 获取
#### 介绍
毕设：基于Springboot的校园二手交易商城的设计与实现

#### 软件架构
- Springboot+vue+MySQL

#### 部署系统必备
- JDK（1.8版本,并配置系统环境变量）
- MySQL（5.7版本）
- Navicat for MySQL（可视化）
- Maven（换阿里源，管理Jar包）
- Lombok插件（简化实体类）
- 本项目采用IDEA开发，以上工具类及安装教程可在QQ群中获取

#### 可选项
- 阿里SMS（个人目前几乎无法申请验证码签名了）
- 支付宝沙箱（可以申请）
- 若需要短信验证码接口，请私聊管理员：猫儿去哪儿了
- 修改注册后完善信息中的学校信息，请在/resources/templates/user/perfectinfo.html中修改

#### 其它
- 数据库里的账号密码默认都是 123456，进行过加盐加密
- 管理员默认入口  localhost/admin
- 默认两个管理员：猫儿、猫给这儿
- 超级管理员账号密码：admin  123456

### 已有功能
  #### 登陆、注册、重置密码模块
  1. 登录：登录可以使用手机号或用户名进行登录
  2. 注册的时候会判断账号是否以及存在，用户名是否已存在。
     
     会判断手机号及邮箱的格式，但不会判断邮箱是否已使用过。
     
     发送短信验证时也会对手机号进行查重，验证码五分钟内有效。
  3. 重置密码时会验证手机号格式，判断是否存在该用户，  短信验证码五分钟有效。 

  #### 商品模块
  1. 发布商品
  2. 修改商品
  3. 商品详情界面
  4. 首页界面
  5. 商品列表界面
  6. 商品搜索界面

  #### 评论模块
  1. 查看商品下所有评论及回复
  2. 评论回复以及对应删除操作

  #### 个人中心
  1. 修改个人信息
  2. 修改密码
  3. 分页展示个人各类商品信息 已审核:1，待审核:3，违规:0，已完成:4
  4. 个人对商品的操作 删除:2  已完成:4
  5. 更换手机号

  #### 收藏模块
  1. 商品详情界面：收藏商品or取消收藏
  2. 收藏列表界面取消收藏
  3. 分页查看用户所有收藏内容
  4. 查看商品收藏状态

  #### 售出记录模块
  1. 用户设置商品为售出状态时存入售出记录
  2. 用户分页查看所有的售出记录
  3. 用户删除售出记录

  #### 聊天模块
  1.可以进行在线聊天

  #### 公告模块
  1. 发布公告
  2. 默认展示最新发布的前三条公告
  3. 公告详情的展示
  4. 修改公告及删除公告
  5. 删除公告

  #### 后台操作功能
  1. 管理员登录
  2. 查看用户列表
  3. 给予用户封号
  4. 管理员审核商品
  5. 管理员分页展示各类商品信息 全部，已审核:1，待审核:3，违规:0 完成:4
  6. 管理员对商品的操作 违规:0 通过审核:1

  #### 网站公告
  1. 管理员发布网站公告
  2. 管理员本人修改或删除公告
  3. 查看网站公告

  #### 通知模块
  1. 评论回复、商品审核、私信发送通知
  2. 设置为管理员或用户发送通知

  #### 支付模块
  1. 提供支付宝沙箱支付，发货，确认收货等操作（此功能暂未开源，若需要请进群联系）


  #### 部分图片
  1.商品首页
![image](https://user-images.githubusercontent.com/46672076/110750258-2c425680-827d-11eb-866f-395e779aa527.png)

  2.商品详情
![image](https://user-images.githubusercontent.com/46672076/110750317-42e8ad80-827d-11eb-8999-32f8b9f4be70.png)

  3.个人中心
![image](https://user-images.githubusercontent.com/46672076/110750402-614ea900-827d-11eb-8ec0-230600cd73b3.png)

  4.在线聊天
![image](https://user-images.githubusercontent.com/46672076/110750750-e8038600-827d-11eb-91ed-2491d22251c0.png)



