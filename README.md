# TeacherReview-back-end
这是导师点评系统1.0版本代码，项目基于SpringBoot+MyBatis框架快速搭建，目前只支持部分功能。
具体功能包含如下：

1、用户可以借助微信小程序授权，同时以微信小程序的openID作为用户的唯一标识以及其他useInfo添加至数据库作为一条用户信息；
![授权界面](src/main/resources/static/authorize.jpg)
2、获取点赞数前五的老师信息；
![主页界面](src/main/resources/static/recomment.jpg)
3、按照学校院系的方式模糊查询该系的老师，同时返回该系点赞数前五的老师名单；
![老师界面](src/main/resources/static/teachers.jpg)
4、按老师ID查询老师的具体信息；
![老师详细信息界面](src/main/resources/static/deatils.jpg)
5、用户可以对某个老师进行点评、也可以删除自己的评论（删除品论根据用户的ID+评论时间位移识别）；
![评论界面](src/main/resources/static/commment.jpg)
6、用户可以给老师点赞，每个人为每个老师点赞的次数仅为一次；
![点赞界面](src/main/resources/static/support.jpg)