django注册登录
===
## 步骤
1. 新建项目 django-admin startproject my_login
2. 新建login模块 python manage.py startapp login
3. 迁移数据库 python manage.py makemigrations , python manage.py migrate
4. 运行 python manage.py runserver 127.0.0.1:8000

## 基本需求
1. 简单登录
2. 简单注册
3. session cookie
4. ajax表单验证
5. 邮箱验证

## 追加需求
0. 前端美化
1. 邮件认证链接
2. 密码加密
3. （选做）OAuth
4. （选做）继承django auth模块
5. 图形验证码
6. （选做）手机接口登录（短信接口）
7. （选做）sso单点登录
8. (选做) 根据用户上次ip判断风险（github上找判断ip位置的包，通过代理进行测试）
9. 用户名限制（长度、中英文、是否重复)
10. 弱密码扫描 （github上找弱密码字典)
11. 密码强度评估（插件）
12. 滑块验证码（极验）
13. 前端数据验证