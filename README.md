# 在线视频学习平台

开发日志请看doc目录下的[UpdateLogs.md](doc/UpdateLogs.md)文件

## 计划开发三大模块
    在线视频学习
    在线题库, 在线debug（暂定）
    直播  （暂定）

### video技术方案
    1. 功能模块
        1.用户模块登录注册
        1.1用户系统（debug，题库，视屏）
        1.2第三方（QQ，微博，github）
        1.3IP记录（登录信息）
        1.4操作信息（更改密码，访问日志）
        1.5用户的播放记录

    2.视频信息相关模块 (存储使用阿里OSS）
      2.1视屏上传（视屏是我们自己传，开放第三方，附件和源代码）
      2.1.1第三方审核（校内，学号，手机号，校外（身份证，手机号码校验））
      2.2视屏审核（人工）
      2.3视频存储目录（章节划分）
      2.4视屏播放相关
      2.4.1评论
      2.4.2like/share
      2-5视屏分类（tags）

    3.会员系统
      3.1付费和非付费
      3.2等级积分
      3.3充值系统
      3.4账单系统

    4.商城系统
      4.1积分（充值）兑换
      4.2直接购物（周边产品）


### 在线题库方案
    1.登录注册模块

    2.题目录入

    3.做题
      3.1题目分类
      3.2做答的结果
      3.2.1点击提交  可以看到正确的答案（后台要统计成绩）------选择

    3.2.2简答和代码  （模糊匹配）
