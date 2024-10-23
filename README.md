# 全目录

3000套系统，根据编号搜索演示视频，复制至流浪器：www.yuque.com/wisebit/blog


<p>抠: 206157502(sql文件)</p>
<p>V: bishebao888888(sql文件)</p>


# springboot025基于SpringBoot网上超市的设计与实现# 5 系统实现
## 5.1 管理员功能实现
### 5.1.1 商品信息管理
管理员权限中的商品信息管理，其运行效果见下图。管理员查询商品需要提交商品名称才行，管理员点击查看评论，可以查看该商品对应的用户评论信息。

![](/md/blog.013.png)

图5.1 商品信息管理页面
### 5.1.2 用户管理
管理员权限中的用户管理，其运行效果见下图。管理员提交用户名获取用户资料，修改有异常情况的用户信息。点击详情可以对用户资料进行更为详细的查看。

![](/md/blog.014.png)

图5.2 用户管理页面
### 5.1.3 商品评价管理
管理员权限中的商品评价管理功能，其运行效果见下图。用户评价商品，需要得到管理员审核才可以显示。同时管理员点击统计报表可以统计商品评价信息。

![](/md/blog.015.png)

图5.3 商品评价管理页面
### 5.1.4 已支付订单
管理员权限中的已支付订单，其运行效果见下图。管理员查看已支付订单，然后逐个进行订单发货。

![](/md/blog.016.png)

图5.4 已支付订单页面
## 5.2 用户功能实现
### 5.2.1 商品信息
用户权限中的商品信息，其运行效果见下图。用户收藏喜欢的商品，可以立即购买商品，或评价商品，也能把商品添加到购物车。

![](/md/blog.017.png)

图5.5 商品信息页面
### 5.2.2 购物车
用户权限中的购物车，其运行效果见下图。购物车的商品允许直接下单，也允许删除购物车商品。

![](/md/blog.018.png)

图5.6 购物车页面
### 5.2.3 确认下单
用户权限中的确认下单，其运行效果见下图。确认下单之前，需要选择地址，也需要查看支付金额信息。

![](/md/blog.019.png)

图5.7 确认下单页面
### 5.2.4 已支付订单
用户权限中的已支付订单，其运行效果见下图。用户已经支付了订单，如果后悔购买商品的话，还可以申请退款。

![](/md/blog.020.png)

图5.8 已支付订单页面








