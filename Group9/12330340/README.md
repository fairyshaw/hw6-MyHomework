# SE-386 Lab 06. MyHomework    

based on http://code.tutsplus.com/tutorials/authenticating-nodejs-applications-with-passport--cms-21619

## install & start development
1. install MonogoDB
2. run mongod (on default port 27017)
3. npm install
4. grunt watch

实现功能：
1. 注册账号时选择老师还是学生
2. 老师可以添加新的作业要求，并登录后，可以查看自己发布的作业要求，且在截止日期前可修改作业要求和截止日期
3. 学生登录后可以查看作业要求，在截止日期前可以提交作业并修改
4. 老师在截止日期后可评分

使用注意：
注册时请务必勾选角色是老师还是学生