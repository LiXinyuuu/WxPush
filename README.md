## 1.登录微信公众测试号平台
https://mp.weixin.qq.com/debug/cgi-bin/sandboxinfo?action=showinfo&t=sandbox/index
记录下面两个信息
![在这里插入图片描述](https://img-blog.csdnimg.cn/80d82dd85f884673968697a29fb52b69.png)
### 2.关注公众号可以获取到用户的openid
![在这里插入图片描述](https://img-blog.csdnimg.cn/4179e8f3f52441c5aa7a64432c47cb3d.png)
### 3. 消息模板![在这里插入图片描述](https://img-blog.csdnimg.cn/1e05c17d3f834674befbb7d92d02edb1.png)

天气模板
```java
{{txt1.DATA}}
你现在所在的地区：{{city.DATA}}
今天的日期：{{date.DATA}} {{week.DATA}}
{{txt2.DATA}}
今天的天气：{{wea.DATA}}
最高气温：{{tem1.DATA}}
最低气温：{{tem2.DATA}}
风向：{{win.DATA}}
风力：{{win_speed.DATA}}
风速：{{win_meter.DATA}}
湿度：{{humidity.DATA}}
能见度：{{visibility.DATA}}
气压：{{pressure.DATA}}
空气质量：{{air.DATA}}
pm2.5含量：{{air_pm25.DATA}}
空气等级：{{air_level.DATA}}
温馨小提示：{{air_tips.DATA}}
```
事件模板
```
{{txt1.DATA}}
{{txt2.DATA}}
{{txt3.DATA}}
```
时间模板
```
{{txt1.DATA}}
距离我们认识已经过去{{day1.DATA}}天了
而我们在一起到现在也有{{day2.DATA}}天了
目前离冬瓜的生日还有{{day3.DATA}}天
离苕皮的生日还有{{day4.DATA}}天
大冬瓜已经在世上活了{{day5.DATA}}天了
小苕皮也存活的{{day6.DATA}}天了
{{txt2.DATA}}
```
