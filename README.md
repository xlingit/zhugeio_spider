# zhugeio-uerdata
get zhugeio user data.

主要运用技术：
python 生成器和迭代器 在web的运用

主要需求 user-info：
获取所有用户数据，目前是通过获取所以的用户id 来获取用户数据
用户大概数据按页存储（页数未知）
单个用户具体数据（单页或多页）
主要实现目标：
1.登录 部分暂时使用cookie 获取当前会话jssessionid （已完成）
2.获取所以用户id（已完成） 这块使用了 生成器和迭代器
3.获取所以用户具体数据（post 请求根据id 获取数据）
4.存储所以用户数据
  

