# spiders

包含了本人完成的所有爬虫项目
项目中用到的get_proxy()函数,是本人的付费接口获取到的代理,所以没有展示出来,请多谅解.

## 目前完成的项目

1. **糗事百科爬虫** -- 平平无奇,不多介绍

2. **妹子图爬虫**  -- 懂的都懂

3. **bilibili爬虫**
    目前可以爬取指定用户的所有视频信息,指定视频的弹幕(1000条),搜索;功能都很基础,没有深入去做,后续可能会在机器人项目中进行完善
4. **网易云音乐爬虫**
    selenium + mimtproxy;在网易云音乐页面点击歌曲播放按钮,可以通过一个接口获取到播放歌曲信息的json数据,通过mimtproxy抓取这个数据,从中获取到歌曲id与歌曲url,然后进行下载,所以爬取vip歌曲是需要登录vip账号的...

5. **磁力链爬虫**
    还没搞明白,原文链接 <https://github.com/chenjiandongx/magnet-dht>

6. **英雄联盟爬虫**
    使用wegame中的查询接口,通过输入玩家的昵称+所在大区,查询玩家的等级,段位,最近战绩等信息

7. **王者荣耀壁纸爬虫**
    一个普通的多线程爬虫

8. **堆糖头像爬虫**
    使用多线程请求堆糖的搜索接口,每次请求获得24个头像图片的url,然后保存到指定路径中

9. **bilibili直播弹幕爬虫**
    多线程获取指定直播间的最新九条弹幕,进行去重处理,保存到redis数据库中

10. **有道翻译爬虫**
    有道翻译接口使用了js加密,爬虫对加密方式进行了破解

11. **58同城爬虫**
    58爬虫使用了字体反爬,爬虫会根据网页中的font-face来建立code->number的映射,以此来破译加密的内容

12. **古诗文网爬虫**
    初次使用scrapy框架来进行爬虫编写

13. **猎云网爬虫**
    使用scrapy中的CrawlSpider类来进行爬虫编写

14. **github模拟登录**
    github模拟表单提交,以此来进行模拟登录
