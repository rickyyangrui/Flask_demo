## To_do_list 使用说明

- 修改app文件中的数据库参数：
```
app.config['SQLALCHEMY_DATABASE_URI'] = "mysql://user:password@localhost/test"
user：你自己的数据库的账号
password:你自己的数据库的密码 
test：就是你创建的database的名称，可以自行修改
```      
- 进入到虚拟环境中，并启动虚拟环境。

- 在虚拟环境中，切换目录到项目的文件
```
(flask-env) C:\Users**\PycharmProjects\Todo-list>python manage.py db init
(flask-env) C:\Users**\PycharmProjects\Todo-list>python manage.py db migrate
(flask-env) C:\Users**\PycharmProjects\Todo-list>python manage.py db upgrade
```

由于本项目没有去做注册功能，只是一个简单的flask-web练手项目，所以，我们可以自己手动在你创建好的数据库中添加username, password. 然后去登录界面进行登录
