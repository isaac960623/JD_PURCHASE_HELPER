# JD_PURCHASE_HELPER
JD_PURCHASE_ROBOT

environment: python 3.7

requirements:

1. bs4
2. requests
3. lxml
4. urllib3

stockinfo.json 用来填写商品id、地址id及购买数量，

"good" : 商品id为 https://item.jd.com/xxxxxxx.html xxxxxx就是商品id

"area" : 地址id获取方法：
1. ![image](https://user-images.githubusercontent.com/44981780/112804157-a4df4a80-90a6-11eb-9ecd-c289bb91e5b9.png)
2. 找到图中![image](https://user-images.githubusercontent.com/44981780/112804260-c809fa00-90a6-11eb-9cf6-f984705201c9.png) data_id后面的value，就是地址id
购买数量自己填写

"count" : count就是想购买的数量


