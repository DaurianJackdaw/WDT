# 作业

截止日期：**2015-4-24**。

在上课讲述的系统的基础上，加上以下功能

1. （6分）分页功能
    1. 要求必须使用 Kaminari 库，每页显示10条帖子。
    2. 显示页面间导航的链接，推荐使用 bootstrap3 样式。
    3. （bonus 3分）将评论也加上分页功能。
2. （8分）将帖子、回复与用户进行关联
    1. 可以在 posts#index, posts#show 两张页面上看到作者的 email。
    2. 可以在 posts#show 评论部分看到评论者的 email。

# 大作业

满分 40 分，完成你的选题，也可以完成以下作业。

在上课讲述的系统上，丰富以下功能。

1. 更完善的用户系统
    1. 支持多种身份（发布者、审核者、管理员）。
    2. 完善用户管理，可以让管理员直接修改密码。
    3. 支持匿名评论，但显示用户的 IP 地址（和 Peer 类似）。
    4. （bonus） 加上 IP 地址的地理位置
2. 头像上传功能
    1. 用户可以上传头像。
    2. 推荐使用 Carrierwave。
    3. （bonus）使用 minimagick 对头像进行缩放。
3. （bonus）更完善的编辑界面
    1. 富文本编辑器功能
    2. 图片与文件上传功能
4. 界面的美观
    1. 建议多套用 Bootstrap 样式。

