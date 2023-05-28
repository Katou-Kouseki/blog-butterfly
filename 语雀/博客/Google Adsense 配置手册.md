---
title: Google Adsense 配置手册
urlname: "31"
author: CC康纳百川
date: 2021-10-24T20:25:00.000Z
updated: 2021-11-08T19:20:00.000Z
translate_title: google-adsense-configuration-manual
subtitle: Google Adsense Configuration Manual
tags: 博客
keywords: google adsense
categories: 博客
description: 本文根据 CC 个人使用经验来介绍 Google Adsense 的食用方法
cover: "https://pic1.afdiancdn.com/user/8a7f563c2e3811ecab5852540025c377/common/0a77436f677dd11422579e07ba6423b3_w1920_h1080_s188.jpg"
id: 31
---

本文首发在[**语雀**](https://www.yuque.com/ccknbc/blog/31/)，自动同步更新至[**CC 的部落格**](https://blog.ccknbc.cc/posts/google-adsense-configuration-manual/)

## 写在前面

当作是一个公告了，如果你“不幸”点开了这篇文章，那么麻烦您动动小手，关闭您的广告屏蔽插件，或者添加本站到白名单，然后刷新一下点击一次广告（虽然还是有几率看不到广告）后继续浏览本篇文章

## 缘起

Q：如果你的流量还可以，自认为文章写的还不错，有了一定的阅读基数，那么你会选择开启赞赏功能还是开启 Google Adsense 呢？

当然如果有人愿意赞赏支持你继续创作，或者是你真的帮助别人解决了一些问题，那么可能会收到一些打赏；但对于我这种产出有限的来说，开启广告或者是更好的选择（我已经厚脸皮求您暂时关掉广告插件了，如果还是不愿意点击广告，那真的是不喜欢广告了）；因此博客成立以来便一直未提供赞赏二维码，广告也只是申请的那段时间开过一段时间，直到最近，才加入了爱发电（但有手续费，所以不是很推荐）；即使很早就开通了 Adsense ，但因为身在大陆，还是要遵守相关法律法规，毕竟也公安备案了，如果不注意就可能引来麻烦，所以如何设置好 Adsense 一直困扰着我。

## 配置

### 阅读体验

关于如何配置其实很简单，只是因为我们是博客，所以还是要注意用户阅读体验，因此我们需要为移动设备优化广告尺寸，并且将广告数量调至最低（自动广告），关闭影响阅读体验的锚定广告和穿插广告等
![所有网站15-–-Google-AdSense.png](https://cdn.nlark.com/yuque/0/2021/png/8391407/1635428346469-f4520c37-4d94-45c7-b508-82c486ab7f63.png#averageHue=%23fefdfd&clientId=ud2d03121-7696-4&from=drop&id=u34996628&originHeight=536&originWidth=900&originalType=binary&ratio=1&rotation=0&showTitle=false&size=54095&status=done&style=none&taskId=ueafa19b2-49e6-472a-9db4-36ef7af8503&title=)
![所有网站11-–-Google-AdSense.png](https://cdn.nlark.com/yuque/0/2021/png/8391407/1635428396535-48847476-a0f6-48b9-a9d6-03ca4b239f7f.png#averageHue=%23fbfbfa&clientId=ud2d03121-7696-4&from=drop&id=uc3d9ad6f&originHeight=666&originWidth=451&originalType=binary&ratio=1&rotation=0&showTitle=false&size=53097&status=done&style=none&taskId=u21478629-a5bb-47c0-8e93-0368c7e5da4&title=)
![所有网站12-–-Google-AdSense.png](https://cdn.nlark.com/yuque/0/2021/png/8391407/1635428402109-0b01d130-db6a-4287-9108-d3f62c216bb3.png#averageHue=%23fdfcfc&clientId=ud2d03121-7696-4&from=drop&id=u617414fc&originHeight=1385&originWidth=449&originalType=binary&ratio=1&rotation=0&showTitle=false&size=58805&status=done&style=none&taskId=uf602eea2-118b-47f7-ac3a-55fc796c845&title=)
至于排除网页，因为开启了匹配内容，那么我们有必要屏蔽掉 404 页面
![image.png](https://cdn.nlark.com/yuque/0/2021/png/8391407/1636370271352-de513540-99e3-4c69-a1f3-0c6b9302303f.png#averageHue=%23fefefe&clientId=u0b8af91e-07e4-4&from=paste&height=220&id=u3a172f83&originHeight=440&originWidth=452&originalType=binary&ratio=1&rotation=0&showTitle=false&size=19473&status=done&style=none&taskId=uc63976a3-4686-4795-a9c1-393eefc36dc&title=&width=226)
此外，如果你使用的是自定义广告单元广告，按照使用体验，可在首页放置信息流广告，侧边栏放置展示广告，文章页放置内嵌广告（在对应位置插入对应代码）
![所有网站14-–-Google-AdSense.png](https://cdn.nlark.com/yuque/0/2021/png/8391407/1635428577592-1583d7c2-dda4-4528-af6e-b84be4133140.png#averageHue=%23fefefd&clientId=ud2d03121-7696-4&from=drop&id=uf58ebec4&originHeight=1126&originWidth=1920&originalType=binary&ratio=1&rotation=0&showTitle=false&size=186457&status=done&style=none&taskId=ue97a6c12-617c-4f0b-8c80-d37b7bf495d&title=)

### 屏蔽内容

> 1. 敏感类别，例如涉黄涉政内容，即使我本人还算比较开放，但网站广告的受众我无法保证，所以为了未成年的健康成长，我会屏蔽掉所有敏感类别

![所有网站6-–-Google-AdSense.png](https://cdn.nlark.com/yuque/0/2021/png/8391407/1635427678324-df66d562-828f-458c-95a1-da0418b89a55.png#averageHue=%23fefefe&clientId=ud2d03121-7696-4&from=drop&id=u28c67ee4&originHeight=1437&originWidth=1920&originalType=binary&ratio=1&rotation=0&showTitle=false&size=188540&status=done&style=none&taskId=u8a560340-a133-4274-b543-71059d864cf&title=)

> 2. 普通类别，最为典型的就是赌博和网络连接类应用，但即使这样屏蔽掉，还是偶尔会有漏网之鱼，因此我会定期手动屏蔽不合适的广告

![所有网站-–-Google-AdSense.png](https://cdn.nlark.com/yuque/0/2021/png/8391407/1635427863020-de9f1391-95d7-4794-9c6b-b4b716b92b63.png#averageHue=%23fefdfd&clientId=ud2d03121-7696-4&from=drop&id=ub032e38e&originHeight=2471&originWidth=1920&originalType=binary&ratio=1&rotation=0&showTitle=false&size=371923&status=done&style=none&taskId=u464ad97d-52dd-44c1-89b2-26620541000&title=)

> 其实类别还有其他，后续也会慢慢更新，只是这张图就不再更新了，因为长截图吗（懒），所以看下面的图片就好了

![所有网站1-–-Google-AdSense.png](https://cdn.nlark.com/yuque/0/2021/png/8391407/1635427884580-ac7e7e2e-a27a-4005-9169-9283b02e0aef.png#averageHue=%23fefdfc&clientId=ud2d03121-7696-4&from=drop&id=uacd846f0&originHeight=1026&originWidth=1920&originalType=binary&ratio=1&rotation=0&showTitle=false&size=167430&status=done&style=none&taskId=u40757193-cf4f-40e1-b830-77fa250ad52&title=)
![所有网站2-–-Google-AdSense.png](https://cdn.nlark.com/yuque/0/2021/png/8391407/1635427903527-4d4de4a0-8509-485c-b508-b2ec35a3f59e.png#averageHue=%23fefcfb&clientId=ud2d03121-7696-4&from=drop&id=u825a6f03&originHeight=200&originWidth=1390&originalType=binary&ratio=1&rotation=0&showTitle=false&size=41118&status=done&style=none&taskId=u6e59097f-d658-4c24-b97a-3a34b224a3a&title=)
![所有网站3-–-Google-AdSense.png](https://cdn.nlark.com/yuque/0/2021/png/8391407/1635427910515-bda36ebb-6767-44da-ae60-3ae4065a2a12.png#averageHue=%23fefdfd&clientId=ud2d03121-7696-4&from=drop&id=u1db67d41&originHeight=391&originWidth=1380&originalType=binary&ratio=1&rotation=0&showTitle=false&size=74911&status=done&style=none&taskId=u13b1ca38-4653-4bd1-accb-f937fc1eff8&title=)![所有网站4-–-Google-AdSense.png](https://cdn.nlark.com/yuque/0/2021/png/8391407/1635427917121-d47b5ed8-55b3-45ab-b12d-8c24d14c2784.png#averageHue=%23fdfdfc&clientId=ud2d03121-7696-4&from=drop&id=ubdca728c&originHeight=177&originWidth=1372&originalType=binary&ratio=1&rotation=0&showTitle=false&size=46106&status=done&style=none&taskId=u3719f3a6-5647-45e0-babf-ee77f651c28&title=)![所有网站16-–-Google-AdSense.png](https://cdn.nlark.com/yuque/0/2021/png/8391407/1635427952977-dcf2645b-5b32-41ea-87fd-26f0174e90e9.png#averageHue=%23f8f6f5&clientId=ud2d03121-7696-4&from=drop&id=u3669b3b1&originHeight=892&originWidth=1920&originalType=binary&ratio=1&rotation=0&showTitle=false&size=493330&status=done&style=none&taskId=u70491bc9-040e-4c13-bccd-11310a1e6bd&title=)![所有网站17-–-Google-AdSense.png](https://cdn.nlark.com/yuque/0/2021/png/8391407/1635427965638-fe4fec45-0413-444f-88fe-4a0e9a4aefcf.png#averageHue=%23f9f8f2&clientId=ud2d03121-7696-4&from=drop&id=u546bcac0&originHeight=892&originWidth=1920&originalType=binary&ratio=1&rotation=0&showTitle=false&size=357143&status=done&style=none&taskId=u300930e4-0dd9-48c0-b830-cbed994b160&title=)
说真的，关于这个社交网络在线社区类别我觉得有必要考量一下，有待后续观察中，因为展示百分比算少的，但是占收入很高，所以可能和色情相关联？
![image.png](https://cdn.nlark.com/yuque/0/2021/png/8391407/1635581743419-6fb8762e-ddbb-4580-8605-4b5ce5d578a8.png#averageHue=%23fdfaf9&clientId=u7aab50a4-01af-4&from=paste&id=ua452a6cd&originHeight=560&originWidth=841&originalType=binary&ratio=1&rotation=0&showTitle=false&size=40621&status=done&style=none&taskId=u66017954-922e-4518-a776-824897d27db&title=)

> 总之，屏蔽类别关键词：`软件`，`烟草`，`酒精`

还有存疑的类别就是`网络安全软件`，`浏览器`和`电视节目`，因为我们看到的不符合法律要求的广告，在我看来，他们应该属于这些范畴内
![image.png](https://cdn.nlark.com/yuque/0/2021/png/8391407/1635583311753-d05538e3-ecca-4018-a312-d15d225a49bc.png#averageHue=%23fefefd&clientId=u7aab50a4-01af-4&from=paste&id=u36d34177&originHeight=254&originWidth=1376&originalType=binary&ratio=1&rotation=0&showTitle=false&size=36573&status=done&style=none&taskId=ua9609a93-0a86-4140-bf73-34ed7b57951&title=)
![image.png](https://cdn.nlark.com/yuque/0/2021/png/8391407/1635582314358-9009611c-3999-490c-bca3-374058af2c9d.png#averageHue=%23fefdfd&clientId=u7aab50a4-01af-4&from=paste&height=257&id=u372c93c5&originHeight=513&originWidth=1385&originalType=binary&ratio=1&rotation=0&showTitle=false&size=57515&status=done&style=none&taskId=uf498f87a-8ca0-40fa-a6d9-7cc16fdaf27&title=&width=692.5)

### 隐私保护

> 除了屏蔽敏感内容以外，还得注意隐私保护，因此还可以针对性做一点设置，不提供个性化广告服务（即使知道这样会减少广告点击率，但本来也就没什么点击率）；此外为了网页加载速度和阅读体验，关闭动画展示、VPAID 广告

![所有网站9-–-Google-AdSense.png](https://cdn.nlark.com/yuque/0/2021/png/8391407/1635428112922-e64ca989-4c5e-4c23-beb5-48fb7100af82.png#averageHue=%23fefefd&clientId=ud2d03121-7696-4&from=drop&id=u1a63438b&originHeight=1346&originWidth=1920&originalType=binary&ratio=1&rotation=0&showTitle=false&size=247803&status=done&style=none&taskId=uc83adc33-68aa-4817-a8fe-6b76dfed387&title=)![所有网站10-–-Google-AdSense.png](https://cdn.nlark.com/yuque/0/2021/png/8391407/1635428120761-09d27159-76e4-4998-8587-aa9404d438cf.png#averageHue=%23fefefd&clientId=ud2d03121-7696-4&from=drop&id=u298d1df8&originHeight=892&originWidth=1920&originalType=binary&ratio=1&rotation=0&showTitle=false&size=154539&status=done&style=none&taskId=u4a34a550-78ff-4010-ac2b-934b73f1b7c&title=)
![所有网站5-–-Google-AdSense.png](https://cdn.nlark.com/yuque/0/2021/png/8391407/1635428210581-3a98a62e-76aa-4b1c-845b-ad4b4be80e51.png#averageHue=%23fefefd&clientId=ud2d03121-7696-4&from=drop&id=u1d91d2de&originHeight=787&originWidth=1432&originalType=binary&ratio=1&rotation=0&showTitle=false&size=142742&status=done&style=none&taskId=uc5daad4d-4a39-44d8-9c8b-daaa36b4c7c&title=)![所有网站7-–-Google-AdSense.png](https://cdn.nlark.com/yuque/0/2021/png/8391407/1635428224004-548d863d-d1dc-480e-8890-be1e3b991334.png#averageHue=%23fefdfd&clientId=ud2d03121-7696-4&from=drop&id=uf7edb613&originHeight=1153&originWidth=1920&originalType=binary&ratio=1&rotation=0&showTitle=false&size=233451&status=done&style=none&taskId=ub77f964b-318a-4278-a713-1048ff91c53&title=)![所有网站8-–-Google-AdSense.png](https://cdn.nlark.com/yuque/0/2021/png/8391407/1635428232516-413c44a4-7f1e-42f8-850e-b05f7cf51720.png#averageHue=%23fefdfd&clientId=ud2d03121-7696-4&from=drop&id=u58c0bf14&originHeight=1063&originWidth=1920&originalType=binary&ratio=1&rotation=0&showTitle=false&size=229192&status=done&style=none&taskId=u8aca170f-9028-45d0-9138-2cadca9aeb9&title=)

## 展望未来

开通广告当然还可以激励着自己，希望能坚持产出以便对得起我展示广告，虽然还不一定看得到，但确实展示量够了还是有一点收入的，哪怕每天 0.01 ＄，十年过去，应该够域名费用了吧（笑死，还是不够），但我还不配，或许那个时候我的博客访问量激增（当然掌握了更多知识，分享了更多内容）。

当然这个世上没有如果，既然买了十年的域名，就要好好做下去，但愿十年后博客还有人访问评论，交流心得！此外，如果你知道更好的广告屏蔽类别组合，欢迎留言，因为真的不想再突然蹦出色情和梯子广告了，不然别人还以为我是什么不正经博客，本来访问量就低，就怕三秒就走了，名声还坏了！！！
