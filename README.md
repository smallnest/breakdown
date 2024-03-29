# 2024 年互联网重大故障

![](breakdown.jpg)

## 知名企业服务监控页
截至目前：

- [阿里云](https://status.aliyun.com/)
- [腾讯云](https://status.cloud.tencent.com/)
- [华为云](https://status.service.huaweicloud.com/#/home)
- 百度云：无
- 天翼云：无
- [AWS](https://status.aws.amazon.com/)
- [微软 Azure](https://status.azure.com/zh-cn/status)
- [谷歌云](https://status.cloud.google.com/)
- [IBM Cloud](https://cloud.ibm.com/status?selected=status)
- [DigitalOcean](https://status.digitalocean.com/)
- [GitHub](https://www.githubstatus.com/)
- [GitLab](https://status.gitlab.com/)


作为一个云服务器厂商，服务健康页展示了他们的监控、管理能力和透明度，每一个厂商都应该有一个服务健康页，最好是`https://status.xxx.com`的域名形式。。

## 故障列表
- **2024年1月21日 由于配置更改，微软Azure崩了**


据微软称，2024年1月21日01:57 UTC到08:58 UTC之间，使用Azure资源管理器（ARM）的客户在执行资源管理操作时可能遇到了问题。
这影响了Azure CLI、Azure PowerShell、Azure 门户，以及依赖 ARM 进行内部资源管理操作的 Azure 服务的用户。
不出所料，用户迅速在社交媒体上表达他们对这些问题的不满。
微软表示，“后端服务进行了配置更改，导致ARM Web角色崩溃。”
解决方法是什么？通过绕过配置更改，让一切恢复正常。这就是传说中的微软质量控制工作。

遗憾的是，从用户反馈来看，所有Azure服务都需要更长的时间才能恢复。不过，无论如何，7个小时的中断也是不容忽视的。
微软承诺，将在周三发布一份初步的事后分析报告（ PIR ），介绍初步的根本原因和修复措施。我们将在14天后发布最终的PIR，到时会深入剖析这起事件。
就微软而言，在允许后台服务因配置更改而造成严重破坏之前，多进行一些测试是有益的。

这并不是Azure遭受的第一次宕机

影响较小，互联网并没有太多的此次事故的新闻。

参考: [由于配置更改，微软Azure崩了](https://zhuanlan.zhihu.com/p/679989357)、[Tesco techies and Azure jockeys hit the floor during weekend of outages](https://www.theregister.com/2024/01/22/a_weekend_of_outages_tesco_azure/)


- **2024年1月12日凌晨，腾讯旗下多款热门游戏集体掉线**


驱动中国2024年1月12日消息，在12日凌晨，许多网友纷纷反映，腾讯旗下的多款热门游戏，包括《英雄联盟》、《穿越火线》、《英雄联盟手游》、《地下城与勇士》、《金铲铲之战》以及《和平精英》等游戏的服务器出现了崩溃的情况。这些游戏的在线玩家都遭遇了集体掉线的问题。
到了12日上午，腾讯游戏的官方微博发布了一则回应。他们表示：“在昨晚的0时许，由于运营商的线路出现了故障，导致了网络的波动。因此，部分区域的服务器用户出现了掉线和暂时无法登录的情况。目前，相关的异常情况已经得到了恢复。”同时，他们也对由此问题给玩家们带来的不便表示了深深的歉意。

参考: [腾讯游戏网络波动，玩家集体掉线！官方回应：运营商线路故障导致！](https://game.qudong.com/article/844549.shtml)、[热门游戏服务器凌晨集体崩溃，腾讯官方回应](https://finance.sina.cn/2024-01-12/detail-inacftcc5124582.d.html?from=wap)、[腾讯游戏回应凌晨“所有游戏断开”起因是“运营商线路故障”](https://new.qq.com/rain/a/20240112A03FC200)


- **2024年1月8日，WIND万得P0级故障复盘**


万得旗下WIND金融终端今晨无法正常登录，出现全面故障。万得方面在今日开市前发公告称，登录故障系因“公司的主干网络线路故障，施工人员正在抢修”。这或是万得成立28年来第一次大面积宕机。
据财联社记者获悉，下午13时左右，WIND手机端的行情板块可以查看个股数据。下午16时左右，电脑终端已能成功登录进主界面，但相关功能查询仍存在较为明显的数据延迟现象。整体来看，WIND金融终端此次登录故障约为8小时。

参考：[2024.1.8 WIND万得P0级故障复盘](http://viplao.com/index.php/2024/01/08/2024-1-8-wind%E4%B8%87%E5%BE%97p0%E7%BA%A7%E6%95%85%E9%9A%9C%E5%A4%8D%E7%9B%98/)、[Wind突发停摆 金融终端宕机影响几何](https://www.chinanews.com.cn/cj/2024/01-09/10142643.shtml)、[Wind崩了一上午！回应称主干网络线路故障，同花顺一度涨超8%](http://www.cnenergynews.cn/kejizhuangbei/2024/01/08/detail_20240108143361.html)、[Wind“崩了” 这次与云无关！](https://finance.sina.cn/usstock/mggd/2024-01-08/detail-inaauwze6479912.d.html?oid=%E5%A4%A9%E6%B4%A5%E6%89%80%E6%9C%89%E6%A3%8B%E7%89%8C%E6%B8%B8%E6%88%8F%E5%A4%96%E6%8C%82%E9%83%BD%E6%9C%89%EF%BC%88%E5%AE%98%E6%96%B9%E5%BE%AE%E4%BF%A1959993704%EF%BC%89%E3%80%8E%E9%87%8D%E5%A4%A7%E6%99%AE%E5%8F%8A%E3%80%8F%E8%B4%B5%E5%B7%9E%E7%88%B1%E6%B8%B8%E9%80%8F%E8%A7%86%E8%BE%85%E5%8A%A9-%E5%A4%AA%E5%9D%91%E4%BA%86%E6%9E%9C%E7%84%B6%E6%9C%89%E6%8C%82&vt=4&cid=76729&node_id=76729)

- **2024年1月5日，WPS办公软件遭遇了一次服务故障，这导致了用户无法正常登录和使用该应用程序。**


2024年1月5日，WPS办公软件遭遇了一次服务故障，这导致了用户无法正常登录和使用该应用程序。这次服务故障使“WPS崩了”迅速登上微博热搜，引起了广泛的关注和讨论。用户们反馈的主要问题包括无法正常登录应用程序，以及文件保存不稳定等问题。

参考：[wps崩了](https://www.zhujib.com/wps-beng-le.html)

