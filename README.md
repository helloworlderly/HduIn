# HduIn
杭州电子科技大学官方App
## 功能
### 核心功能 —— 选课
- 范围：公选课与体育课。

- 优势：无需填写验证码，提高选课效率。 收藏夹，一键收藏，开放选课，直接提交。无需内网，任何网络下都可以进行选课。选课速度远远高于正方选课系统，最快用时10ms，平均用时4.39s；相比正方半小时选不上课速度大大提升

- 数据统计（2016年下半学期）：总计用HduIn选课人数：5032人。~<br>~ 选课成功：7662节。

![Alt text](./84AE8C0E2CADA7D0E5AC4B86F709C18D.jpg)

![Alt text](./7FCC5148DC74E5BC09AD84F2BE399044.jpg)

![Alt text](./1503651145834.png)


### 主要功能 —— 信息查询
在网络中心授权下，我们尽最大努力获取大量与学生学习生活相关的数据，方便同学快速查询

![Alt text](./1503651260784.png)

### 社交功能 —— 杭电圈子
web端的家园论坛作为移动端版本出现在HduIn里面，走到哪里聊到哪里。


##技术
### 登录
使用OAuth2认证，通过杭电网络中心授权API获取token，学号作为有用户名，token作为密码，登录LeanCloud用户系统。token过期，重新登录，LeanCloud端密码重置。

###  推送
集成LeanCloud，推送参数控制相关信息的状态。
![Alt text](./1504255351778.png)


### 


