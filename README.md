# Sec-Interview-4-2023
一个2023届毕业生在毕业前持续更新、收集的安全岗面试题及面试经验分享~

## 写在更前面

和铺天盖地的研发、产品等校招宣讲和内推通知不同，安全岗位虽然在大多数公司中都属于“研发”下的一个分类，但是宣讲时很少会提到。。这就不得不我们自己去挖掘了，同时我也希望能有更多的招聘人员（或者有了解的直接发issue）能介绍一下自己公司的安全部门、部门平时的业务，对于学生来说也更容易找到适合自己技术特点或者自己感兴趣的部门。

## 写在前面

1. 个人强烈感觉面试因人而异，对于简历上有具体项目经历的同学，个人感觉面试官会着重让你介绍自己的项目，包括但不限于介绍一次真实攻防/渗透/挖洞/CTF/代码审计的经历 => 因此对于自己的项目，面试前建议做一次复盘，最好能用文字描述出细节，在面试时才不会磕磕绊绊、或者忘了一些自己很得意的细节
2. 面试题会一直更新（大概，直到我毕业或者躺平为止吧...）包括一些身边同学（若他们同意的话）和牛客上扒拉下来的（若有，会贴出链接）还有自己的一些经历
3. 还有一点很想说的，就是面试题/面经，本质上只是一种“见识”，他并不能实质上提升自己的水平，还是希望大家（包括我自己）不要太局限于面经，可以查缺补漏但没必要面经问什么自己就一定要学什么，按自己的节奏学就行了，毕竟每人的技术特点不一样，面试的过程和问题也会不一样

**最后欢迎大家fork项目！xdm自己有面试经验的话也欢迎发pr！有分享就有收获！**

**若有不方便公开的内容请联系本人第一时间删除！**

# 安全岗目录

有最新的公司校招信息可以随时issue，我会第一时间更新

以安全为主业的公司我就不放了（360、深信服、奇安信等），主要放不以安全为主业但有安全业务的公司

| 公司及投递链接                                               | base                         | 岗位                                                         | 部门                                                         | 投递时间                                    |
| ------------------------------------------------------------ | ---------------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------- |
| [字节跳动提前批](https://jobs.bytedance.com/campus/position?&category=6704216109274368264&type=2&current=1&limit=10) | 北京、深圳、杭州             | 渗透测试工程师<br />安全研究工程师<br />安全工程师           | 安全与风控<br />无恒实验室                                   | 7.7~7.31                                    |
| [华为提前批](https://career.huawei.com/reccampportal/portal5/campus-recruitment-detail.html?jobId=235728) | 基本全覆盖                   | 网络安全与隐私保护工程师                                     | 基本覆盖                                                     | 7.31之前                                    |
| [SHEIN提前批](https://app.mokahr.com/campus_apply/shein/2932#/job/ae220d63-46e9-4893-9423-12ba9f4f7472) | 南京                         | 安全工程师                                                   | 无                                                           |                                             |
| [大疆](https://we.dji.com/zh-CN/campus/position?from=home_page&top_cta=undefined&project=recruitment&page=1&category=109_110) | 上海、深圳                   | 嵌入式系统安全工程师<br />功能安全工程师<br />安全技术开发工程师 | 研发团队<br />车载团队<br />信息管理团队                     | 7.6~8.10                                    |
| [联想](https://talent.lenovo.com.cn/joblist?apply_to=campus) | 北京、天津、厦门             | 安全工程师                                                   | [IDG](https://talent.lenovo.com.cn/resume/jdlist/2225)<br />[Lenovo Research](https://talent.lenovo.com.cn/resume/jdlist/2227) | 7.15开始                                    |
| [oppo提前批](https://careers.oppo.com/campus/post/detail?id=421&privacyVal) | 深圳、成都                   | 终端安全工程师（二进制、安卓、逆向类）                       |                                                              |                                             |
| [网易雷火](https://campus.163.com/app/detail/index?id=1953&projectId=45) | 杭州                         | 游戏安全工程师（游戏、安全、二进制）                         | 雷火事业群                                                   | 7.5~9.28                                    |
| [蔚来](https://nio.jobs.feishu.cn/campus/?keywords=%E5%AE%89%E5%85%A8&category=6937213309162752293&location=&project=&type=&job_hot_flag=&current=1&limit=10&functionCategory=) | 上海、北京、合肥             | 岗位较多，覆盖面大                                           |                                                              |                                             |
| [科大讯飞](https://campus.iflytek.com/official-pc/jobDetail?id=330&projectId=4) | 合肥                         | 安全工程师                                                   |                                                              | 7.11                                        |
| [米哈游](https://campus.mihoyo.com/#/campus/position)        | 上海                         | [信息安全工程师（客户端）](https://campus.mihoyo.com/#/campus/position/47)<br />[安全运营](https://campus.mihoyo.com/#/campus/position/13) |                                                              | 7.4                                         |
| [Shopee](https://app.mokahr.com/campus_apply/shopee/2962#/job/6399612b-8821-42f9-955f-fb3b9be6012c) | 深圳（Sg暂未上线hc）         | 安全工程师                                                   | 研发中心                                                     | 7.18~10.14                                  |
| [百度](https://talent.baidu.com/jobs/list?search=%E5%AE%89%E5%85%A8) | 北京、成都                   | 安全工程师<br />数据安全研究员<br />人工智能安全算法研发工程师 |                                                              | 提前批：7.14\~8.26<br />常规批：8.27\~10.16 |
| [网易]()                                                     | 杭州                         | [IOS安全开发](https://campus.163.com/app/detail/index?id=2112&projectId=46)<br />[Android安全开发](https://campus.163.com/app/detail/index?id=2111&projectId=46)<br />[安全运营专员（产品岗）](https://campus.163.com/app/detail/index?id=2066&projectId=46) |                                                              | 8.2~9.2                                     |
| 网易游戏（互娱）                                             | 广州                         | [安全工程师](https://game.campus.163.com/position-detail/704) |                                                              | 7.26~9月中下旬                              |
| [海康威视](https://campushr.hikvision.com/school.html)       | 杭州                         | [网络安全工程师](https://campushr.hikvision.com/JobDetails.html?id=1fc64fd9523b49b8b062cb3402202aa3&type=0)<br />[安全开发工程师](https://campushr.hikvision.com/JobDetails.html?id=9f16bee4baf14cba94b8cc1033991b9d&type=0)<br /><br />[安全研究员（博士学历）](https://campushr.hikvision.com/JobDetails.html?id=cf4ff46e1b8b40639e188206af78a2fa&type=0)<br />安全方案工程师 |                                                              |                                             |
| [4399](http://web.4399.com/campus/yjsgw/jishulei/#1157023)   | 广州                         | 信息安全工程师                                               |                                                              |                                             |
| [美团](https://campus.meituan.com/jobs?jobFamily=1&jobId=4961&jobName=%E5%AE%89%E5%85%A8%E5%B7%A5%E7%A8%8B%E5%B8%88&jobType=1&pageNo=3) |                              | 安全工程师（简历稀缺）                                       |                                                              | 8.1~10.31（招满即止）                       |
| [Garena](https://app.mokahr.com/campus_apply/garena/38200#/jobs?keyword=%E5%AE%89%E5%85%A8) | 上海、杭州                   | 信息安全工程师<br />安全逆向工程师                           |                                                              |                                             |
| [AutoX](https://app.mokahr.com/campus_apply/autox/6313#/jobs?keyword=%E5%AE%89%E5%85%A8) | 北上广深                     | [信息安全合规工程师](https://app.mokahr.com/campus_apply/autox/6313#/job/2da57366-8bc2-41d3-9c83-8e5e0082fb80)<br />[安全开发运维工程师](https://app.mokahr.com/campus_apply/autox/6313#/job/276fa91d-e3f1-4409-937b-3af11be36ac2)<br />[嵌入式开发-安全工程师](https://app.mokahr.com/campus_apply/autox/6313#/job/ded0b8c3-1034-4a81-b85e-cfc49a44b7b6)<br />[后台开发工程师-安全服务](https://app.mokahr.com/campus_apply/autox/6313#/job/ba93e27f-9323-4410-b214-8b831971d1bb) | [网络安全团队](https://mp.weixin.qq.com/s/AM9aAq3okhWjaJwhnxwoWQ) |                                             |
| [快手](https://campus.kuaishou.cn/#/campus/job-info/2947)    | 北京                         | 安全工程师                                                   | 工程类-安全                                                  |                                             |
| [字节跳动正式批](https://jobs.bytedance.com/campus/position?keywords=%E5%AE%89%E5%85%A8&category=&location=&project=7111884057764448548&type=2&job_hot_flag=&current=1&limit=10&functionCategory=) | 北京、深圳、杭州             | 安全研究工程师<br />安全工程师<br />隐私计算研究员<br />渗透测试工程师<br /> | 安全与风控<br />无恒实验室                                   | 8.10~10.31                                  |
| [完美世界](https://recruit.games.wanmei.com/campus-recruitment/pwrd/45131/#/jobs?keyword=%E5%AE%89%E5%85%A8) | 北京-朝阳区                  | [安全分析工程师（提前批）](https://recruit.games.wanmei.com/campus-recruitment/pwrd/45131/#/job/c5c0e2e5-d457-4707-9b9a-1cec3d2ead0e)<br />[安全分析工程师](https://recruit.games.wanmei.com/campus-recruitment/pwrd/45131/#/job/1ae1e5e3-675d-4434-996e-78e4fecd2866) |                                                              |                                             |
| [京东](https://campus.jd.com/#/details?id=3770)              | 北京                         | 安全工程师                                                   |                                                              | 8.1~10.28                                   |
| [中国电信天翼云](https://wecruit.hotjob.cn/SU62b2ae672f9d24458d72f9cc/pb/school.html?postName=%E5%AE%89%E5%85%A8) | 北京、成都、厦门、广州       | 信息安全工程师（北京要求硕士及以上）                         |                                                              |                                             |
| [拼多多](https://careers.pinduoduo.com/campus/recent/detail?guid=ad8cb3ac-267b-4b35-ab45-ec46de791741&from=home&scrolltop=700) |                              | 安全工程师                                                   | 仅开放内推                                                   | 8.15~10.14                                  |
| [阿里巴巴](https://talent.alibaba.com/campus/position-list?campusType=freshman) | 杭州、北京、上海             | 安全工程师                                                   |                                                              |                                             |
| [Zoom](https://www.nowcoder.com/careers/zoom/102351?type=neitui&source=08D65A1F3FCEF22E11D216B0D92CCECC477A4E945DEDE621) | 苏州、杭州、合肥             | 应用安全工程师                                               |                                                              | 9.28之前                                    |
| [远景科技](https://app.mokahr.com/campus_apply/envisiongroup/43123?sourceToken=e4614e2db76faa2afde1f6698825d29b#/job/6600c287-372b-4f54-ab8a-86a2e809dd06) | 上海                         | 信息安全工程师                                               | 远景能源                                                     | 10.31之前                                   |
| [贝壳找房](http://campus.ke.com/adcrecru.aspx)               | 北京                         | 安全研发工程师<br />安全工程师                               |                                                              |                                             |
| [竞技世界](https://campus.jj.cn/#/chooseJob)                 | 北京                         | 安全工程师                                                   |                                                              | 8.22开始                                    |
| [地平线](https://wecruit.hotjob.cn/SU62d914f10dcad43c775ec125/pb/school.html?postName=%E5%AE%89%E5%85%A8) | 上海                         | [安全工程师（信息/功能方向)-Auto](https://wecruit.hotjob.cn/SU62d914f10dcad43c775ec125/pb/posDetail.html?postId=62f4dc5e2f9d241d028a008d&postType=campus&recruitType=1) |                                                              |                                             |
| [小红书REDstar](https://job.xiaohongshu.com/campus)          | 上海                         | [java开发工程师-安全](https://job.xiaohongshu.com/jobs/6708/campus)<br />[机器学习算法工程师-安全技术 |                                                              | 9.30之前                                    |
| [度小满](https://app.mokahr.com/campus_apply/duxiaoman/74050#/) | 北京                         | [信息安全工程师](https://app.mokahr.com/campus_apply/duxiaoman/74050?sourceToken=5c372cd2d6c9fd5e1f173ade6b28fe9a#/job/6e183800-6109-4fbd-b0f6-72951a862309) |                                                              |                                             |
| [兴业数金](https://www.nowcoder.com/careers/cibfintech/104324?ncsr=EYzuBA) | 上海、福州、成都             | 信息安全工程师                                               |                                                              |                                             |
| [oppo](https://careers.oppo.com/campus/post/home)            | 深圳、成都                   | 终端安全工程师<br />互联网安全工程师<br />信息安全工程师     |                                                              |                                             |
| [小米](https://hr.xiaomi.com/campus)                         | 北京、南京                   | [安全研发工程师](https://app.mokahr.com/campus_apply/xiaomi/47097#/job/86505662-20d2-4eb8-8943-d0d3e1cc21e7)<br />[安全工程师](https://app.mokahr.com/campus_apply/xiaomi/47097#/job/e0fa3f01-7380-4c40-9e0e-32a1dfecf082)<br />[安全操作系统工程师](https://app.mokahr.com/campus_apply/xiaomi/47097#/job/3c92b9ec-abea-467b-b083-00bf5128be2c) |                                                              | 9.7之前免笔试                               |
| [vivo](https://hr.vivo.com/wt/vivo/web/templet1000/index/corpwebPosition1000vivo!gotoPostInfoForAjax?postId=145934&recruitType=1&brandCode=1) | 深圳、东莞                   | 安全工程师                                                   |                                                              |                                             |
| [小鹏](https://app.mokahr.com/campus_apply/xiaopeng/22#/)    | 广州、上海                   | [信息安全培训生](https://app.mokahr.com/campus_apply/xiaopeng/22#/job/ea87d1bc-2d28-4385-9357-0b5fcf0f3aba)<br />[系统安全软件工程师](https://app.mokahr.com/campus_apply/xiaopeng/22#/job/00b172ec-9b85-48a9-b228-2c5b0331e932) |                                                              |                                             |
| [Momenta](https://momenta.jobs.feishu.cn/campus/position/7132723277702121742/detail?spread=YMAY754) | 深圳                         | 信息安全工程师                                               |                                                              |                                             |
| [TCL](http://campus.tcl.com/post/details.html?post_code=all) | 深圳                         | 软件开发工程师（安全方向）<br />信息安全工程师               | 鸿鹄实验室（提前批）<br />软件工程中心                       |                                             |
| [吉利](https://campus.geely.com/hcm-web/#/jobs/school)       | 杭州、宁波                   | 信息安全工程师<br />功能安全工程师<br />[氪学家-信息安全/攻防方向](https://campus.geely.com/hcm-web/#/job-detail/school/10979)<br />信息安全开发工程师<br />[氪学家-车联网安全研究员](https://campus.geely.com/hcm-web/#/job-detail/school/10978) | 多个下属组织分开收                                           |                                             |
| [中兴](https://app.mokahr.com/campus-recruitment/zte/46903#/job/7b9efee8-799e-4c69-b34b-7d5cc9fb5797) | 南京、长沙、西安、深圳       | 网络安全工程师                                               |                                                              |                                             |
| [滴滴](https://campus.didiglobal.com/campus_apply/didiglobal/6223#/jobs?keyword=%E5%AE%89%E5%85%A8) | 北京                         | 安全工程师（密码开发、容器开发、接口安全、反入侵、移动安全）<br />安全算法工程师 | CTO线<br />国际化事业部                                      |                                             |
| [顺丰科技](http://campus.sf-express.com/#/postDetail/1054)   | 深圳                         | 信息安全工程师（顺丰科技）                                   |                                                              |                                             |
| [微众银行](https://campus.webank.com/campus-recruitment/webankhr/18005/#/jobs?keyword=%E5%AE%89%E5%85%A8) | 深圳、武汉                   | 信息安全工程师（应用安全、信息安全管理、后端开发C++、反欺诈、安全攻防） |                                                              |                                             |
| [腾讯音乐](https://join.tencentmusic.com/campus/post-details/?id=11740) | 深圳                         | 安全策略                                                     |                                                              |                                             |
| [TP-Link](https://hr.tp-link.com.cn/jobList)                 | 深圳                         | [网络安全算法工程师](https://hr.tp-link.com.cn/jobDetail/5415)<br />[信息安全工程师（深圳）](https://hr.tp-link.com.cn/jobDetail/5467) |                                                              |                                             |
| [携程](https://campus.ctrip.com/campus-recruitment/trip/37757#/job/ff4bdaf8-3c0a-45f6-a46e-1e2d8c2910e7) | 上海                         | 基础安全工程师                                               |                                                              |                                             |
| [海尔](http://vta.maker.haier.net/client/campus/deliverfirst/id/19/fid/7/rid/105.html) | 青岛                         | 信息安全工程师                                               |                                                              |                                             |
| [荣耀](https://career.hihonor.com/SU60eea919bef57c1023f6fe78/pb/posDetail.html?postId=62b3b9f70dcad406d138ee41&postType=campus&recruitType=1) | 北京、南京、深圳             | 网络安全工程师                                               |                                                              |                                             |
| [中国人寿](https://chinalife.hotjob.cn/wt/chinalife/web/templet1000/index/corpwebPosition1000chinalife!gotoPostListForAjax?brandCode=1&recruitType=1) | 很多                         | 很多                                                         |                                                              |                                             |
| [格力](https://gree.zhiye.com/zpdetail/620670720?r=-1&p=&c=&d=&k=%E5%AE%89%E5%85%A8) | 珠海                         | 信息安全                                                     |                                                              |                                             |
| [传音控股](https://transsion.zhiye.com/campus?r=-1&p=&c=&d=&k=%E5%AE%89%E5%85%A8#jlt) | 上海、重庆                   | 系统安全工程师（web、安卓、安全开发）<br />安全合规<br />安卓隐私安全开发 |                                                              |                                             |
| [美的]()                                                     | 深圳、佛山、武汉             | [信息安全技术研发工程师](https://careers.midea.com/schoolOut/post/details?projectRuleId=cf176940-20cc-4651-a0d7-b64b8c452399&positionId=8a928eae826e11800182a9f8fe970610&recruitCategoryId=85ed0569354a46578240983830fe0c5b)<br />[信息安全工程师](https://careers.midea.com/schoolOut/post/details?projectRuleId=cf176940-20cc-4651-a0d7-b64b8c452399&positionId=8a928eae826e11800182ab773dbe0b64&recruitCategoryId=85ed0569354a46578240983830fe0c5b) |                                                              |                                             |
| [西云数据](https://app.mokahr.com/campus_apply/nwcdcloud/4047?sourceToken=199bbc29da2b6aaa73f3c074f362b75f#/job/3920a99a-364e-4a38-8dec-8272d108125a) | 北京                         | 信息安全工程师                                               |                                                              |                                             |
| [工商银行](https://job.icbc.com.cn/pc/index.html#/main/school/home/post?pti=D00001) | 北京、广州、杭州、珠海       | 科技菁英-安全技术                                            |                                                              | 8.29~9.30                                   |
| [欧科云链](https://www.nowcoder.com/jobs/school/detail?jobId=118712&activityId=17&activitySuffix=2023szhzc&channel=sq_sqdoc) | 北京                         | 安全开发工程师                                               |                                                              |                                             |
| [建信金科](https://www.nowcoder.com/jobs/school/detail?jobId=146456&activityId=16&activitySuffix=2023jrzc&channel=sq_sqdoc) | 北京                         | 信息安全工程师（实施管理中心）                               |                                                              | 8.27~9.30                                   |
| [阳光保险](https://www.nowcoder.com/jobs/school/detail?jobId=140521&activityId=16&activitySuffix=2023jrzc&channel=sq_sqdoc) | 北京                         | 信息安全工程师（安全运维/安全开发）                          |                                                              | 8.27~9.30                                   |
| [奕斯伟](https://campus.eswincomputing.com/campusxq?jobId=310620216&c=&c2=&p=1^-1,3^-1&ky=&d=&PageIndex=3#zw) | 北京                         | 信息安全工程师                                               |                                                              |                                             |
| [58同城](https://campus.58.com/xzxq?jobId=150515131)         | 北京                         | 安全工程师                                                   |                                                              |                                             |
| [金发科技](https://kingfa.zhiye.com/zpdetail/560681834)      | 广州                         | 信息安全工程师                                               |                                                              |                                             |
| [东方财富](https://zhaopin.eastmoney.com/campus-recruitment/eastmoney/57971#/jobs?keyword=%E5%AE%89%E5%85%A8) | 上海                         | 信息安全岗位<br />信息安全开发工程师<br />信息安全咨询师     |                                                              |                                             |
| [中金所](https://cffexit.zhiye.com/zpdetail/390501584)       | 上海                         | 运维工程师-网络安全技术方向                                  | 硕士+                                                        |                                             |
| [中国电信天翼云](https://wecruit.hotjob.cn/SU62b2ae672f9d24458d72f9cc/pb/school.html?postName=%E5%AE%89%E5%85%A8) | 北京、成都、厦门、广州       | 信息安全工程师                                               | 北京需要硕士+                                                |                                             |
| [浩鲸科技](http://iwhalecloud.zhiye.com/form?fromPage=job&jobAdId=fec6b63f-abc8-4f1d-9057-b0d867c9bc4e) | 南京                         | 安全工程师                                                   |                                                              |                                             |
| [商汤科技](https://hr.sensetime.com/SU604c56f9bef57c3d1a752c60/pb/school.html?postName=%E5%AE%89%E5%85%A8) | 北京、深圳                   |                                                              |                                                              |                                             |
| [三一重工](https://sanycampus.zhiye.com/campus?k=%E5%AE%89%E5%85%A8) | 长沙                         | 信息安全工程师                                               | 硕士+                                                        |                                             |
| [经纬恒润](https://wecruit.hotjob.cn/SU62a93e760dcad45229a827cc/pb/school.html?postName=%E5%AE%89%E5%85%A8) | 较多                         | 较多                                                         |                                                              |                                             |
| [理想](https://li.jobs.feishu.cn/referral/campus/position/?keywords=%E5%AE%89%E5%85%A8&category=&location=&project=7095664339228051720&type=&job_hot_flag=&current=1&limit=10&functionCategory=&token=NTsxNjYwNTQwMjE4NDgzOzcxMTQ4MzEzNTczMDIwMTM5ODA7NzExOTQyNjMxOTE0NjIwNzUwMQ) | 北京、杭州                   | 安全研发工程师<br />安全运营工程师<br />安全测试工程师<br />信息安全合规专员 |                                                              |                                             |
| [中国一汽](https://faw-zhaopin.hotjob.cn/positionList?recruitType=1&projectId=202301) | 长春                         | [车联网安全工程师](https://faw-zhaopin.hotjob.cn/SU603374380dcad4635b836531/pb/posDetail.html?postId=63049c732f9d2453a5e2e2ce&postType=campus)<br />[信息安全工程师](https://faw-zhaopin.hotjob.cn/SU603374380dcad4635b836531/pb/posDetail.html?postId=62f0e07ebef57c29eacf940f&postType=campus)<br />[电子电气网络及安全软件工程师](https://faw-zhaopin.hotjob.cn/SU603374380dcad4635b836531/pb/posDetail.html?postId=62e2870f2f9d24381014f7a2&postType=campus) |                                                              |                                             |
| [中国系统](https://app.mokahr.com/campus_apply/cestc/7509#/jobs?keyword=%E5%AE%89%E5%85%A8) | 北京、武汉                   | [安全工程师](https://app.mokahr.com/campus_apply/cestc/7509#/job/85f40df5-1170-423c-be4c-96c21bff5582)<br />[数据安全工程师](https://app.mokahr.com/campus_apply/cestc/7509#/job/bb142f8a-c334-4d41-978e-caa20b134099) |                                                              |                                             |
| [蚂蚁集团](https://talent.antgroup.com/campus-list?type=freshman) | 北京、上海、杭州、重庆、成都 | [安全工程师](https://talent.antgroup.com/campus-position?positionId=1102001303) |                                                              |                                             |
| [联易融](https://hr.linklogis.com/#/jobDetail/08e50ef2-ec61-4b98-93f3-4c8501aa60d6/390509430?WorkingPlace=%E6%B7%B1%E5%9C%B3%E5%B8%82) | 深圳                         | 信息安全工程师                                               |                                                              |                                             |
| [海信集团](https://hisense.zhiye.com/jihui?k=%E7%BD%91%E7%BB%9C%E5%AE%89%E5%85%A8) | 佛山、青岛                   | 网络安全工程师                                               |                                                              |                                             |
| [人保寿险](https://picc.zhiye.com/xzlist3?k=%E5%AE%89%E5%85%A8&d=-1&c=&p=1^-1,3^-1&PageIndex=1) | 福州、上海、佛山、南京       | 信息安全、基础安全、应用安全、数据安全                       |                                                              |                                             |
| [途虎养车](https://app.mokahr.com/campus_apply/tuhu/28398?sourceToken=c403a200011f884f58ed33626baef087#/job/46ecffba-8698-4735-ab4d-6fe54261c277) | 上海                         | 信息安全工程师                                               |                                                              |                                             |
| [零跑科技](https://leapmotor.zhiye.com/search?r=2&p=&c=&d=&k=%e5%ae%89%e5%85%a8#jlt) | 杭州                         | 信息安全工程师<br />信息安全开发工程师                       |                                                              |                                             |
| [腾讯](https://join.qq.com/post_detail.html?pid=1&id=112&tid=2) | 深圳、北京                   | 安全技术                                                     |                                                              |                                             |

# 好文分享

[我的秋招安全之路](https://www.nowcoder.com/discuss/1071449)

[作为安全工程师，都有哪些可选择的公司？](https://www.nowcoder.com/discuss/972050)

[安全岗笔试题](https://www.nowcoder.com/search?type=paper&query=%E5%AE%89%E5%85%A8+%E7%AC%94%E8%AF%95)

[部分安全岗汇总（牛客）](https://www.nowcoder.com/discuss/250116?type=all&order=recall&pos=&page=2&ncTraceId=&channel=-1&source_id=search_all_nctrack&gio_id=C644A4A66482D41AB59A3DF3F860459E-1662134259514)

[部分牛客安全岗面经](https://www.nowcoder.com/discuss/751095?type=post&order=recall&pos=&page=1&ncTraceId=&channel=-1&source_id=search_post_nctrack&gio_id=C644A4A66482D41AB59A3DF3F860459E-1662134563061)

下午听说字节和快手校招官网hc泄露，看了下应该是去年的数据，毕竟去年总计8k+hc对的上，今年剩3khc了（指字节，快手我不清楚）

不过还是有点参考性的，看看也行（下图是字节的）

| 岗位             | 部门       | hc   | base |
| ---------------- | ---------- | ---- | ---- |
| 渗透测试工程师   | 无恒实验室 | 1    | 杭州 |
| 渗透测试工程师   | 无恒实验室 | 1    | 深圳 |
| 渗透测试工程师   | 无恒实验室 | 4    | 北京 |
| 安全工程师       | 无恒实验室 | 1    | 杭州 |
| 安全工程师       | 无恒实验室 | 1    | 深圳 |
| 安全工程师       | 无恒实验室 | 4    | 北京 |
| 渗透测试工程师   | 安全与风控 | 10   | 深圳 |
| 渗透测试工程师   | 安全与风控 | 10   | 杭州 |
| 渗透测试工程师   | 安全与风控 | 10   | 北京 |
| 安全工程师       | 安全与风控 | 15   | 深圳 |
| 安全工程师       | 安全与风控 | 15   | 北京 |
| 安全工程师       | 安全与风控 | 15   | 杭州 |
| 隐私计算研究员   | 安全与风控 | 2    | 深圳 |
| 安全研究工程师   | 安全与风控 | 1    | 北京 |
| 安全产品运营     | 飞书       | 2    | 北京 |
| 安全策略产品经理 | 番茄小说   | 1    | 北京 |

**<big>目录</big>**

- [0x00 字节跳动-渗透测试实习生](#0x00-字节跳动-渗透测试实习生)
- [0x01 阿里云安全实习](#0x01-阿里云安全实习)
- [0x02 深信服-漏洞研究员实习](#0x02-深信服-漏洞研究员实习)
- [0x04 字节跳动-安全研究实习生](#0x04-字节跳动-安全研究实习生)
- [0x05 长亭科技-安全服务工程师](#0x05-长亭科技-安全服务工程师)
- [0x06 天融信面试复盘](#0x06-天融信面试复盘)
- [0x07 腾讯-安全技术实习生](#0x07-腾讯-安全技术实习生)
- [0x08 小鹏汽车-安全工程师](#0x08-小鹏汽车-安全工程师)
- [0x09 阿里巴巴-阿里云安全](#0x09-阿里巴巴-阿里云安全)
- [0x0B 字节跳动-无恒实验室](#0x0b-字节跳动-无恒实验室)
- [0x0C 58同城-安全工程师](#0x0c-58同城-安全工程师)
- [0x0D 腾讯-玄武实验室](#0x0d-腾讯-玄武实验室)
- [0x0E 360-安全工程师](#0x0e-360-安全工程师)
- [0x0F 快手-安全实习生](#0x0f-快手-安全实习生)
- [0x10 华顺信安-安全服务工程师](#0x10-华顺信安-安全服务工程师)
- [0x11 奇安信面试复盘](#0x11-奇安信面试复盘)
- [0x12 京东-安全研发](#0x12-京东-安全研发)
- [0x13 安恒面试复盘](#0x13-安恒面试复盘)
- [0x14 浙江东岸检测](#0x14-浙江东岸检测)
- [0x15 360-安全工程师实习](#0x15-360-安全工程师实习)
- [0x16 某一线实验室实习](#0x16-某一线实验室实习)
- [0x17 腾讯-科恩实验室实习](#0x17-腾讯-科恩实验室实习)
- [0x18 某四字大厂面试复盘](#0x18-某四字大厂面试复盘)
- [0x19 某四字大厂实习面试复盘](#0x19-某四字大厂实习面试复盘)
- [0x1A 某两字大厂面试复盘](#0x1a-某两字大厂面试复盘)
- [0x1B 某安全公司-安全研究员](#0x1b-某安全公司-安全研究员)
- [0x1C 腾讯-科恩实验室实习](#0x1c-腾讯-科恩实验室实习)
- [0x1D 长亭科技 安全服务工程师实习](#0x1d-长亭科技-安全服务工程师实习)
- [0x1E PingCAP 安全工程师](#0x1e-pingcap-安全工程师)
- [0x1F shopee](#0x1f-shopee)
- [0x20 深信服](#0x20-深信服)
- [0x21 华为](#0x21-华为)
- [0x22 360](#0x22-360)
- [0x23 深信服-深蓝攻防实验室](#0x23-深信服-深蓝攻防实验室)
- [0x24 B站](#0x24-b站)
- [0x25 shopee-红队-Singapore](#0x25-shopee-红队-singapore)
- [0x26 长亭](#0x26-长亭)
- [0x27 奇安信 安全研究员 实习](#0x27-奇安信-安全研究员-实习)
- [0x28 美团 安全岗实习](#0x28-美团-安全岗实习)
- [0x29 美团 安全工程师实习](#0x29-美团-安全工程师实习)
- [0x2A 京东 安全研究](#0x2a-京东-安全研究)
- [0x2B 百度](#0x2b-百度)
- [0x2C 腾讯](#0x2c-腾讯)
- [0x2D 奇安信 A-TEAM](#0x2d-奇安信-a-team)
- [0x2E 快手 安全工程师](#0x2E-快手-安全工程师)
- [0x2F 快手 安全实习生](#0x2F-快手-安全实习生)
- [0x30 快手 安全工程师](#0x30-快手-安全工程师)
- [0x31 快手 安全工程师](#0x31-快手-安全工程师)
- [0x32 蚂蚁 安全工程师 实习](#0x32-蚂蚁-安全工程师-实习)
- [0x33 蚂蚁 安全工程师 实习](#0x33-蚂蚁-安全工程师-实习)
- [0x34 商汤科技 安全开发工程师](#0x34-商汤科技-安全开发工程师)
- [0x35 海康威视 网络安全工程师](#0x35-海康威视-网络安全工程师)
- [0x36 度小满 信息安全工程师](#0x36-度小满-信息安全工程师)
- [0x37 长亭 安全开发工程师](#0x37-长亭-安全开发工程师)
- [0x38 小米 安全工程师](#0x38-小米-安全工程师)
- [0x39 携程旅游 基础安全工程师](#0x39-携程旅游-基础安全工程师)
- [0x40 欧科云链 安全开发](#0x40-欧科云链-安全开发)


# 致谢

感谢 `PolarPeak` 、 `lalalashenle` 、 `4ra1n` 、`底层群员` 、`TARDIS` 、[`Theoyu`](https://github.com/yuuuuu422)师傅的分享！



# 0x00 字节跳动-渗透测试实习生

> 字节直接找朋友内推的效率很高，当天上午投简历，下午就约了面试，裸面挺痛苦的建议复习一下再去

1. 自我介绍
2. 渗透的流程
3. 信息收集如何处理子域名爆破的泛解析问题
4. 如何绕过CDN查找真实ip
5. phpinfo你会关注哪些信息
6. 有没有了解过权限维持
7. 说一个你感觉不错的漏洞，展开讲讲
8. 输出到href的XSS如何防御
9. samesite防御CSRF的原理
10. CSRF防御
11. json格式的CSRF如何防御
12. 浏览器解析顺序和解码顺序
13. 过滤逗号的SQL注入如何绕过
14. 过滤limit后的逗号如何绕过
15. fastjson相关漏洞
16. 说一个你知道的python相关的漏洞（SSTI原理，利用过程,payload相关的东西）开放性问答

# 0x01 阿里云安全实习

时长：20分钟

1. 自我介绍
2. 看你简历上说擅长java、php代码审计，也没有类似的经历能够分享一下，比如说独自审的一套代码或者开源项目，从中发现的一些比较高危的问题
3. 在审项目的时候，比如一个web网站，简单说说思路
4. 简单描述一下什么是水平越权，什么是垂直越权，我要发现这两类漏洞，那我代码审计要注意什么地方
5. 解释一下ssrf
6. 怎么防御ssrf，场景：`http://ip/?url=image.jpg`
7. 常见的内网段有哪些，他们的掩码是什么
8. 教育系统攻防演练，分享一个渗透的例子
9. 除了学校，有没有试过渗透别的系统
10. 像这样的场景（给内网靶标），渗透内网系统的思路
11. 反问环节（问了工作内容）
    - 岗位做的是阿里云云平台安全，内部安全保障，保障阿里云自身的安全不出问题，整个系统的上线前中后过程，每个方向都有人

# 0x02 深信服-漏洞研究员实习

时长：15分钟

1. 自我介绍
2. 在xx实习的时候做什么东西
3. 渗透测试的思路简单说一下
4. 护网在里面担当一个什么样的角色
5. 红队的一些思路
6. 拿下系统后有没有做横向
7. 前段时间那个log4j有研究吗，可以简单说一下吗
8. （继上一个问题）有哪些混淆绕过的方法
9. 内存马有没有了解过
10. 冰蝎、哥斯拉这些工具有没有了解过
11. 做攻击队的时候有没有研究过什么攻击，比如研究一些工具还是魔改什么的
12. 那么多漏洞和攻击，比较擅长哪一个
13. 说一下shiro反序列化的形成原因、利用链
14. 对一些bypass的方法有没有了解过，有什么姿势可以简单介绍一下
15. 反问

# 0x03

# 0x04 字节跳动-安全研究实习生

## 一面

时长：50分钟

1. 你投的岗位是安全研究实习生，你了解我们这边主要是做什么的吗
2. 自我介绍
3. 现在有什么比较想做的方向吗，比如你写的代码审计、攻防演练、你在学校的研究方向（密码学）其实是三个大方向，现在有什么比较想做的吗
   - 说了代码审计、安全研究
4. 有没有审过开源框架、cms、中间件之类的
5. 面试官介绍了工作内容
6. 我看你简历上有几段实习经历和项目经历，先聊一下实习经历吧，在A主要做什么的
7. 详细聊聊入侵检测主要在做什么，遇到的问题
8. 关于入侵检测产生大量误报的原因，有没有分析过，有没有比较好的解决方法
9. 和A比起来，B的应该就比较偏攻击方对吧，有打仗（雾，面试官好像确实是这么说的）有代码审计，聊一下在B主要做了些什么
10. 审表达式引擎的步骤和思路
11. 刚刚你说的审计听起来好像和普通开发的审计差不多，都是通过程序流、文档去做，有没有从安全方面入手审计一些项目
12. xxe是怎么造成的，从代码层面来看
13. 我看你简历有很多攻防演练经历对吧，这几段攻防演练经历有没有哪一次印象比较深刻的，挑一个聊一聊
14. 你的这次攻击好像更多的是利用弱口令，有没有一些更有技巧的方法
15. 这个头像上传的webshell是怎么上传的
16. 还有什么其他的检验方式？要怎么绕过？
17. 这两天log4j漏洞很火，有没有去了解一下
18. 面试官最后介绍业务
19. 反问环节

## 一面plus-安全研发实习生

> 很奇葩的剧情，一面面试官面完告诉我有base北京base深圳问我是不是想要深圳的，我说是，结果过了一个多星期hr告诉我因为我一面面试官是北京的，然后我选了深圳，所以一面不作数，重新约了一面
>
> 接着一面这天中午又收到了感谢信，然后看官网状态是流程已终止，本以为没得面了没想到还是正常进行....

> 等到二面才发现原来已经变成安全研发了，本来我投的是安全研究的...

时长：45分钟

1. 自我介绍

2. A护网做了什么

3. 做哪一层的处置，waf？ids？

4. 遇到的问题是什么，有什么印象深刻的处置

5. 怎么解决误报过多的情况，有做过什么规则能解决这个情况的

6. 他的内网误报是在办公网还是生产网

7. 比如mysql也会执行powershell，怎么做防护（前面说了很多内网误报是因为有人写了ps脚本触发的）

8. 有没有挖过src

9. 在做攻防的时候，资产收集这块有没有什么经验介绍的

10. 一个单位的一级域名可能不止一个，怎么收集某个单位的所有域名，注意不是子域名

11. 还有没有其他的资产收集的经验

12. 除了信息收集，有没有什么漏洞方面的攻击案例

13. 聊一下sql注入

14. 怎么防御

15. 遇到order by时怎么防御

16. 用转义字符防御时，如果遇到数据库的列名或是表名本身就带着特殊字符，应该怎么做

17. 宽字节注入

18. ssrf了解吗

19. 怎么修复

20. 基于黑白名单的修复，现在的生产基本都是用的docker，ip是随时变的，而且docker重启后可能什么都不一样了，怎么做一个修复

21. fastjson反序列化

22. redis的漏洞

23. mysql的提权

24. shiro反序列化

25. 最近很火的log4j，聊一下原理

26. jndi的解析流程和原理

27. 有没有什么你做的比较好的地方我没有问到的，可以聊一聊

28. 惯例介绍部门的主要业务

29. 惯例反问

## 二面

> 紧接在一面plus后，就隔了10分钟，一面复盘写一半就开始二面了

时长：25分钟

1. 聊攻防演练中比较得意、印象深刻的一次经历
2. 安全领域比较擅长什么
3. 审的一般是什么，java？python？
4. csrf了解吗，怎么做一个修复
5. 在拿到java系统的代码时，审计的流程是怎样的
6. java系统中的sql注入怎么做一个防御和修复
7. 在浏览器中输入一个域名去访问时，浏览器做了什么
8. 一个系统的登录页，通常可能出现什么漏洞
9. 云安全了解吗
10. 有做过安全工具的开发吗，比如waf或者扫描器之类的
11. 惯例介绍业务
12. 惯例反问

# 0x05 长亭科技-安全服务工程师

## 一面

时长：30分钟

1. 自我介绍
2. web渗透测试有没有过实战
3. 讲一下sql注入原理
4. 有没有从代码层面了解过sql注入的成因（反问代码层面指的是不是sql语句，答是）
5. 了不了解xss，有没有从代码层面了解xss的原理
6. 对owasp top10漏洞哪个比较了解
7. 讲一讲怎么防御sql注入
8. sql注入怎么绕过过滤
9. 问了护网时xx有没有成为靶标，有没有对攻击队行为做过研判
10. 在xx护网时的工作内容，有没有做过流量包、数据包的研判
11. 学校攻防演练时担任的角色，主要工作内容，渗透测试的思路，有什么成果（这个问的还是挺细的，具体到分配的任务、有没有拿下主机或者域控、攻防演练的形式和持续时间等都聊了）
12. 平时ctf打的多不多，有什么成绩
13. 平时会不会关注一些新颖的漏洞，会不会做代码审计，比如shiro漏洞等有没有做过漏洞复现
14. 对钓鱼邮件这些有没有什么了解（因为上面聊xx护网时说了钓鱼邮件和微信钓鱼的事）
15. 目前学习的方向是什么
16. 最后介绍人才需求
17. 反问环节

## 二面

时长：34min

1. 自我介绍
1. 学代码审计偏哪个语言？擅长哪个语言
1. 拿到一份php代码做审计，审计的流程大概是怎样的
1. 对php开发框架熟吗？比如ThinkPHP这些
1. 给的源码是ThinkPHP框架的话，审计起来和没有使用框架的有什么不同，从流程上或者从关注的点上有什么不同
1. php原生的敏感函数有哪些，比如搜关键字的话会搜哪些
1. 反序列化漏洞了解吗
1. 反序列的时候，unserialize()反序列一个字符串的时候，对象会有一些魔术方法会被自动调用到，在找反序列化的链时，有哪些魔术方法是可以作为一个入手点去找的
1. 有没有审计过实际的项目，比如github上一些开源cms
1. java审计可以聊一下吗
1. 之前做渗透时有没有做过完整的项目，除了ctf
1. 能不能说一些找到的漏洞，怎么找到的
1. ssrf这类的漏洞熟悉吗，说一下原理和利用方式
1. 我们利用ssrf可以做什么，达到什么效果
1. 在php环境下，怎么最大程度的利用ssrf，拿到shell或者进内网
1. 怎么利用内网的机器请求内网中的服务
1. ssrf漏洞的修复建议，修复的时候需要注意哪些细节
1. 如果用白名单策略修复ssrf，从用户输入的变量里拿出要访问的目标，这个要注意哪些，因为一些url会通过特殊的字符做白名单绕过，对取变量这个操作有哪些要注意的细节？
1. php中三个等号和两个等号有什么区别
1. php代码常见入口函数怎么找
1. 有一些php的开发框架可以帮我们做一些url路由，对这些路由的方法熟悉吗
1. 介绍下PHP的变量覆盖
1. 有一个php的程序，本身就允许文件包含的操作，同时想要避免文件包含漏洞，写代码的时候要注意哪些
1. 远程文件包含和本地文件包含，这两种涉及的php设置有什么
1. 本地文件包含能不能通过php配置限制文件包含的路径（不通过代码直接通过配置项来解决）
1. php、java代码审计对哪个漏洞特别熟悉
1. php在做sql注入防御时有哪些方法
1. java做sql注入的防御
1. sql的二次注入了解吗，能介绍一下吗
1. 写代码的时候怎么防止二次注入

# 0x06 天融信面试复盘

时长：15~20分钟

1. 有没有做过现实环境的渗透测试？有没有提交过src？
2. 对免杀技术了解多少，制作的木马能不能过360
3. ctf的成绩？擅长什么方向的题？
4. 攻防演练有什么成果？
5. shiro漏洞了解吗，讲一下原理
6. 在linux下，现在有一个拥有大量ip地址的txt文本文档，但是里面有很多重复的，如何快速去重？
7. 在内网渗透中，通过钓鱼邮件获取到主机权限，但是发现内网拦截了tcp的出网流量，聊一下这个时候应该怎么进行通信？
8. 代码能力怎样，平时有没有做过代码审计？
9. 目前对什么方向感兴趣？

# 0x07 腾讯-安全技术实习生

时长：15分钟

1. 自我介绍

1. sql注入了解吗，讲一讲二次注入的原理

1. 二次注入要怎么修复

1. sql注入过waf了解吗，若一个sql注入过滤了information关键词，怎么绕过

1. Redis未授权访问

1. 渗透测试的一个完整流程

1. 打ctf的时候有没有遇到什么印象特别深的题目

1. 文件下载漏洞有没有什么比较好的利用方式

1. 利用文件下载漏洞找文件名具体是找什么文件名（读取文件一般会读取哪些文件）（ctf中？实战中？）

1. 命令执行漏洞，http不出网有什么比较好的处理方法（发散一点说）

1. 接上一题，通过隧道通信，详细讲讲通过什么类型的隧道，讲讲具体操作

1. 漏洞预警

1. 有没有复现过中间件类型的漏洞（有没有完整的复现过漏洞）

1. 在学校的攻防演练中扮演的角色的主要职责是什么

# 0x08 小鹏汽车-安全工程师

时长：37分钟

1. 自我介绍
1. 有没有挖过src？
1. 平时web渗透怎么学的，有实战吗？有过成功发现漏洞的经历吗？
1. 做web渗透时接触过哪些工具
1. xxe漏洞是什么？ssrf是什么？
1. 打ctf的时候负责什么方向的题
1. 为什么要搞信息安全，对安全这一块有多大的兴趣，以后会不会转行，还是打算一直从事安全方面工作
1. 自己平时怎么学安全的，如果让你做一个新的方向（app安全），会投入多少时间去学习，还是说有自己想做的方向
1. 聊一聊代码审计的流程
1. 平时是怎么做代码审计的
1. 有没有审计过开源框架、CMS？
1. 怎么判断一个数据库是mysql还是oracle的？
1. sql注入的种类，利用方式？
1. 聊一聊sql注入的原理及防御思路
1. 做开发的时候用的是什么语言
1. 做java开发的时候用过什么框架，能不能做java安全开发
1. 有没有做过安卓开发
1. 有没有用python写过工具？
1. msf利用的是哪个漏洞，有没有成功反弹？
1. 护网的时候主要做了些什么，聊一聊对安全产品的理解
1. 公司现在需要做app安全的人，现在要你做的话，你会去学吗，或者说感兴趣吗，还是说有别的想做的，不想做app安全，能投入多少时间去学
1. 内网渗透了解吗？聊一聊内网渗透的思路

---

> 接下来从0x09~0x0B都是同一位博主的面经，发在牛客上，看了下感觉很不错就转过来了，再附上这个博主的一些面试题/学习笔记的链接，个人觉得挺好的
>
> [CSDN 网络安全-常见面试题](https://blog.csdn.net/lady_killer9/article/details/120075430)
>
> [CSDN 网络安全-自学笔记](https://blog.csdn.net/lady_killer9/article/details/106791542)

# 0x09 阿里巴巴-阿里云安全

作者：宠你＆我的天性

链接：https://www.nowcoder.com/discuss/642461?source_id=profile_create_nctrack&channel=-1

来源：牛客网

## 一面

1.  自我介绍一下，讲一下课题和课外实践？ 

2.  WAF管理平台后端API有做过压力测试吗？ 

3.  你现在的论文已经发表了吗？ 

4.  你的毕业论文是什么？ 

5.  在字节跳动训练营最大的收获是什么？ 

6.  在研究生期间或日常生活中有什么可以分享的有意义的事情？ 

7. 快排的时间复杂度是多少？ 

   - 最快的情况下是多少？是什么样的情况？ 

   - 最慢的情况下是多少？是什么样的情况？ 

8.    哈希冲突有哪些解决办法？  

9.    编程题(easy) 

##  二面

1. 自我介绍一下？ 
2. 我们这里是密码管理服务，密码这块你了解多少呢？ 
3. 你未来计划更偏向于安全研究还是安全研发？ 
4. 你对云上PKI的安全，身份认证的能力感兴趣吗？ 
5. 介绍一下字节跳动训练营做了什么？

   - Sql注入的原理和防御方案有哪些？ 

   - WAF防护SQL注入的原理是什么？ 

   - 本次训练营中，怎么分工协作的？你的角色是什么？你的贡献是什么？有没有提升效率的可能？ 

   - 漏洞挖掘是纯工具还是有一些手工的？ 

   - WAF管理平台后端API有哪些功能？ 

   - WAF的增删改查数据量大吗？ 

   - Redis解决了什么问题？ 

   - 热点数据怎么保证redis和db中的一致？ 

   - 用户登录认证是怎么做的？ 

   - Token的安全怎么保护？ 

   - Token的内容该如何设计？ 

   - 怎么保证数据不被篡改呢？ 

6. SDN漏洞挖掘的思路？ 
   - 漏洞挖掘有挖掘出RCE漏洞吗？ 
   - 对栈溢出、堆溢出有研究吗？ 

7. 说一下https协议的过程？ 
   - 随机数一般有几个？ 
   - 如果有一个的话会如何？ 

8. 对C++或C熟悉吗？ 
9. 哈希表的原理和冲突解决办法？（和一面重复了） 
10. Mysql查询快的原因？ 
    - 事务的四大特性，mysql隔离级别？ 
    - 解释一下乐观锁和悲观锁？ 

11. 多并发编程有涉及过吗？ 
    - 读写锁和互斥锁/排他锁用过吗？有什么区别？为什么会用？  

12. 有一项软件著作权，做的什么软件？    
13. 编程题(medium)  

##  三面（交叉面）

1. 字节跳动训练营越权问题解决办法？ 
   - 防火墙都是自己写的规则去防御吗？ 
   - 任务都是一样，你们得了第一，你们团队做的好的地方在哪里？ 
2.  SDN漏洞挖掘项目，你能列举一个比较有技术含量的漏洞吗？漏洞原理和挖掘过程？ 
3.  Python2和Python3的区别？ 
   - Xrange和range返回的是什么？ 
4.  数据库索引的作用？mysql索引的变化？ 
5.  数据库弱口令，登进去后如何提权？ 
6.  你自己写项目的时候，怎么进行的   SQL注入防御？   
7.  怎么进行CSRF防御？
   - Token加密什么东西？ 
   -  校验什么？ 
   -  Token为什么需要加密？ 
   -  使用明文随机数可以吗？ 
8.  怎么防重放攻击 ？    
9.  Docker有哪些安全上的好处？    
10.  个人发展方向？    
11.  当前在哪里日常实习？   
12.  实习多久了？为什么想来阿里？



# 0x0A





# 0x0B 字节跳动-无恒实验室

部门：无恒实验室

岗位：安全工程师

作者：宠你＆我的天性

链接：https://www.nowcoder.com/discuss/749954?source_id=discuss_experience_nctrack&channel=-1

来源：牛客网

---

1. 自我介绍
2. 阿里巴巴实习介绍？
3. 启明星辰实习介绍？
4. 消息队列是自研的，还是开源的？叫什么名字？
5. 任务下发？状态监测
6. 子域名扫描插件怎么写的？
7. 指纹识别插件怎么写的？
8. wappalyzer怎么进行指纹识别的？
9. CSDN的XSS漏洞挖掘过程？
10. SQL注入的原理？
11. 目前防御SQL注入的方式有哪些？
12. 有哪些SQL语句无法使用预编译的方式？
13. SQL注入如何判断注入点？ 
14. 已知example.com/?id = 1，是mysql，如何获得mysql版本？
15. 无回显情况下怎么弄？ceye dnslog外带
16. 除了外带呢？
17. CSRF的原理？
18. CSRF使用POST请求时，如何攻击？隐藏表单
19. 不是表单呢？
20. AJAX发送POST请求？
21. Ajax发送POST请求会发几个数据包？ 
22. 让你来写一个CSRF攻击插件，你怎么写？包含哪些模块？
23. SSRF的原理？
24. 让你写一个SSRF插件，你怎么写？
25. 反问环节



# 0x0C 58同城-安全工程师

岗位：安全工程师

作者：Lamber-maybe

链接：https://www.nowcoder.com/discuss/766311?source_id=discuss_experience_nctrack&channel=-1

来源：牛客网

---

1. 你先做个自我介绍吧

2. 假如说有个SQL注入如下

   ```
   select * from user where userid = {};
   ```

   1. response里面没有返回内容 
   2. 1s就超时了，直接返回404页面 

   这种情况下如何注入?

3. 比如说我写一个安全SDK
   1. sql注入的修复, 怎么写(伪代码)

      答：我倾向于使用预编译的方式

   2. 但是预编译的话, 研发可能不会用怎么办呢, 就是说如果他觉得改起来太麻烦了能不能更方便一点. 因为预编译的话, 我每条SQL每条查询都得去改.

      答：那设计一个白名单怎么样呢

   3. 那你大概写一下怎样设计一个白名单. 你可以分场景, 比如说什么场景什么场景的SQL注入, 或者是参数里面应该做什么操作

   4. xss的修复, 怎么写(伪代码)
      答: 用实体化转义

   5. 但是我们有一个场景啊, 你看我们上传简历这里, 有时候会支持上传html的简历, 对吧. 他本身业务就需要用到html, 如果用html实体化转义的话, 他全都会被转义, 那这样的话业务就崩了嘛, 对不对. 那这种情况下我们要怎么样去写一个xss的过滤, 或者是说转义, 去解决这个类似于简历这个场景. 你可以想一想, 写不出来代码也没关系.

      答：白名单限制, 黑名单过滤.

   6. 其实我们自己是这样做的, 对于这种情况, 我们第一是会做一个html标签的白名单, 第二是事件的白名单. 黑名单我们就不搞了.

   7. rce的修复, 怎么写(伪代码)(java或者python的命令执行)
      答: 白名单限制, 只允许需要的函数. 但RCE的话我感觉在业务场景当中, 一般来说也不是很容易出现
      面试官: 欸, 我们就出现了很多. 尤其是运维部门.

      我: 我打CTF比较多, 我了解的RCE都是PHP方面的. 比如说system, popen之类的. 一般来说都是直接做过滤

   8. 那PHP中这些函数全部被黑名单了, 你还有什么方法

      答: 字符串拼接 `$a=p.h.p.i.n.f.o()`

   9. 你有没有用过php里面的反引号啊

      答: 还有用 `chr()` 函数来绕过

   10. 面试官: 编码是吧
   11. xxe的修复, 怎么写(伪代码)
       答: 对XXE来说, 我只了解他的攻击方式, 对他的防御不是很了解. 攻击方式就是做XML的外部实体化注入. 一个攻击模板, 可以读文件, 可以做命令执行
   12. XXE怎么做命令执行呢, 就拿php来说, XXE怎么做命令执行
   13. XXE这个命令执行是要他的服务端本身支持某些特殊的协议, 一般来说是不行的

4. 了解过自动化代码[审计]()的工具吗, 类似于fortify这种

   答: 我只用过那个一个比较老的那个, 我想不起来了(指seay)

5. 没关系, 那你有没有了解过他的一些原理, 大概怎么做的

   我: 他原理一般都是通过匹配一些特殊函数, 去定位可能出现漏洞的函数的位置

6. 但这种的话他误报很高欸, 就像我这种RCE的话, 你直接匹配的话他很多都是误报了, 很多他都不是web思路的

   我: 还有一种是, 给他加一些自定义规则

7. 那有没有更好的办法呢, 误报太多了我们没办法接受啊

   我: 我有一个想法就是, 他自己匹配了之后, 能不能从前端从一个黑盒的层面再去验证一遍

8. 那黑盒验证, 我就有需求是, 首先我得知道, 首先我php里面我这个函数到底是哪个入口传进来的, 对吧. 但这个有可能经过了层层调用, 甚至有可能是`include()`这种, 那这种的话, 对于我来说 , 我并不知道他影响到了哪一些入口, 这种情况怎么办呢
9. 你们学校有学编译原理吗
10. 其实我觉得安全专业还是要学一下编译原理

11. 有没有搞过linux的这种后渗透相关的

    1. 面试官: 比如这个linux被我攻陷了, 我想去拿到更多的信息, 比如说一些横向的信息, 那种有没有搞过
       我: 这种不是很了解, 但windows的会一点

    2. 面试官: 那你可以简单讲一下, 比如你先攻陷一台windows的机器, 然后我想在这个windows的域内去做一些横向移动, 我想把这个windows的域的权限给拿到, 这种你该怎么做
       我: 通过票据伪造, 白银票据和黄金票据
       面试官: 你这个票据伪造要怎么做呢
       我: 一般用mimikatz就可以了吧

    3. 面试官: 你mimikatz抓取的是内存里面的密码和一些他的票据, 那我如果本身是低权限的呢, 就我本身抓不了密码, 或者我抓到的用户密码并不是域账号的, 是一个低权限账号呢. 因为大部分渗透进来都是个应用, 应用他可能并没有域权限
       我: 从低权限往上提

    4. 面试官: 那你一般会怎么提权
       我: 一般windows的漏洞吧
       面试官: 那现在就用这个windows系统的提权, 我现在就一个webshell, 那我怎么样去提权

    5. 面试官: 你可以这样嘛, 你上传一个提权的脚本或者exe嘛, 你webshell去跑这个exe, 他就把这个web应用权限提权了

12. 那你最后有什么想问我的吗



# 0x0D 腾讯-玄武实验室

作者：立志区块链安全的菜鸡

链接：https://www.nowcoder.com/discuss/711602?source_id=discuss_experience_nctrack&channel=-1

来源：牛客网

部门：玄武实验室

1. 自我介绍
2. 讲解一下CSRF原理吧
3. 什么时候接触web安全的
4. 为什么学WEB安全
5. 参加过哪些比赛
6. 你发挥了那行作用
7. 讲讲反序列化吧
8. 说一说最近你关注的安全圈大事
9. 那你说说你遇到最优印象的吧
10. 我看你简历上有黑盒测试 说一说吧
    - 一个是钱包的测试 一个是交易所的测试，钱包主要是信息泄露，水平越权
11. 怎么发现的
    - 信息泄露是webpack可以直接查看api 等调用信息，水平越权是构造josn包返回了用户数据账户密码之类的
12. 怎么构造的
13. 那继续说说交易所
14. （区块链相关）讲一讲逆向函数涉及到的接收参数的指令集
15. 说说重入漏洞
16. 有对最近那个最大的区块链安全事件有了解吗
17. 好，那你对密码学有什么接触嘛
18. 我看你简历有许多对Defi的审计，那你有什么对漏洞的挖掘的经验吗
19. 嗯好 那现在我问你个问题 你思考下 在DEFI项目中建立了各种各样的经济模型 怎样才能找出可能存在的漏洞
20. 讲讲你对未来可能出现的新型漏洞的猜想吧
21. 有一种 游戏在猜对正确答案后可获得奖励
22. 反问

# 0x0E 360-安全工程师

作者：Djade

链接：https://www.nowcoder.com/discuss/628090?source_id=discuss_experience_nctrack&channel=-1

来源：牛客网

1. 自我介绍 

2. WAF及其绕过方式 

3. IPS/IDS/HIDS 

4. 云安全 

5. 怎么绕过安骑士/安全狗等 

6. Gopher扩展攻击面 

7. Struct2漏洞 

8. UDF提权 

9. DOM XSS 

10. 数据库提权 

11. 怎么打Redis 

12. 内网渗透 

13. 容器安全 

14. k8s docker逃逸 

15. linux、windows命令：过滤文件、查看进程环境变量 

16. 站库分离怎么拿webshell



# 0x0F 快手-安全实习生

作者：ArrowQin

链接：https://www.nowcoder.com/discuss/651317?source_id=discuss_experience_nctrack&channel=-1

来源：牛客网

部门：系统运营部

## 一面

1. 自我介绍
2. 问项目
3. 针对项目问了很多详细的问题，不便透露，通用问题如下：
4. 做项目的时候有没有遇到什么问题，怎么解决
5. 做项目学到了什么东西
6. 项目中有没有什么地方自己做过优化
7. 有没有对网站做过渗透测试
8. Linux操作熟悉吗，怎么看进程PID
9. 用过什么数据库，答：sqlite,mongodb,面试官好像不太了解没咋问
10. 为什么用mongodb
11. 了解ES吗(Elasticsearch)
12. HTTPS建立过程
13. python怎么管理内存
14. 深拷贝和浅拷贝区别
15. python多进程、多线程、协程有用到吗，都在什么地方用到
16. python可以实现真正的多线程吗
17. 代码题：ip排序

（转成元组排序就行了，记得把str转成int，不然192会比50大）

```
输入：iplist = ["1.1.1.1","192.168.1.110","10.192.2.4","10.50.2.3","10.50.2.10","111.120.12.1","172.18.5.112"]
输出：
1.1.1.1
10.50.2.3
10.50.2.10
10.192.2.4
111.120.12.1
172.18.5.112
192.168.1.110
```

18. 写Web API的时候怎么防止SQL注入
19. 怎么防XSS
20. 了解越权漏洞么，有没有挖过越权漏洞
21. 有没有什么比较擅长的我还没问到的

## 二面

1. 问项目

2. 项目哪一块时间花的比较多

3. 怎么溯源攻击

4. 举一个溯源攻击的例子

5. 怎么检测webshell

6. sql注入在mysql和sqlserver中有什么区别

7. 想找安全开发的岗位还是安全研究的岗位

8. 代码题：手机九宫格键盘，输入数字，输出所有的字母组合

   如输入23，输出['ad','ae','af','bd','be','bf','cd','ce','cf']

9. 讲一下DNS协议的作用、解析过程

10. DNS协议的安全问题

11. 实习时间



# 0x10 华顺信安-安全服务工程师

来源：知乎

链接：https://zhuanlan.zhihu.com/p/426763642

1. 自我介绍
2. 红蓝队经验
3. 关于shiro漏洞了解多少
4. 说说你APP测试的经验
5. xposed用的什么框架，有没有自己写过app解密
6. Xss、SSRF、SQL 产生的原因，修复方案？
7. 如果你Xss打了后台，发现是内网的怎么办
8. 假设给你一个目标站，你要怎么做？
9. linux和windows提权知多少。
10. 会不会进程注入？
11. 做过几次应急？
12. 讲讲windows和linux应急你咋做的
13. 用过没用过我们家的goby和fofa?
14. 会不会apk反编译？
15. 你python水平咋样？
16. 你php怎么审的

---

> 备注：从0x11~0x14都是同一位师傅的面经，来源于知乎，里面有这位师傅的回答及一些总结、知识点，我这只是选了几个个人认为比较有代表性的公司和面经的题目出来
>
> 来源：知乎
>
> 链接：https://zhuanlan.zhihu.com/p/164774894
>

# 0x11 奇安信面试复盘

1. MVC框架详细说一下
2. 详细介绍一下sql注入
3. xss与csrf的区别
4. csrf的原理以及如何防范
5. 还有什么你擅长的但是没有问到的吗
6. 讲一下xxe的原理
7. xxe会用到哪些函数
8. 文件上传，详细说说
9. 常见的web容器有哪些
10. apache 7.0 文件上传黑名单怎么绕过，详细说说
11. 密码学的对称密码与非对称密码有哪些
12. md5是不是对称加密
13. apache可以执行php文件吗
14. 了解哪些数据库
15. 说说反序列化的原理
16. 反序列化会用到哪些函数
17. xxe有没有实战过
18. java的多线程
19. python有过哪些项目，写过什么东西
20. 之前python学到什么地方



# 0x12 京东-安全研发

1. 首先根据简历提问
2. 问我的一个项目完成的怎么的样了，//简历中的
3. Java基础怎么样，
4. 有没有自己动手写过一些工具
5. 有没有想过自己以后要写一下扫描器
6. sql注入的简单原理及其如何防御
7. 有没有了解过反序列化 尤其是Java方向的
8. 数据结构还记得多少
9. src主要挖掘一些什么类型的漏洞
10. 了解的MSF框架怎么样
11. 数据库主要了解的哪些，主要学的什么数据库
12. ssrf的原理及其防御 ---> 这有深入



# 0x13 安恒面试复盘

1. sqlmap爆出当前库名的参数是什么？

2. namp探测系统的参数是什么 --->大写还是小写

3. namp的小写o与a是干嘛的

4.  布尔型盲注的具体语句是什么

5.  宽字节的原理

6.  python有没有反序列化

7.  get传参与post传参的区别

8.  Http有哪些请求方式

9.  如何判定cdn与cdn的作用

10.  如何确认服务器的真实IP

11.  详细说了说信息收集过程

12.  一串编码如何确认是base64

13.  栅栏密码的原理是什么

14.  base64与md5如何区别

15.  oracle的默认端口是多少

16.  mysql的管理员密码一般放到哪

17.  如果substr()函数被禁用，你脑子里有多少替换函数

18.  redis如何拿下，哪个端口，具体语句，具体操作

19.  如何通过邮箱知道对方的IP

20.  说一下同源策略

21.  如何收集网站管理员邮箱等等

22.  ssrf有哪些危害

23.  如何防御ssrf-->问的较深---->建议在详细了解一下

24.  Linux的某两个文件怎么分辨（忘了具体是哪两个文件了）

25.  MSF框架稍微问的深入了一些

26.  web容器（中间件）有哪些解析漏洞与原理

27.  如何防范sql注入 --->这问的很深




# 0x14 浙江东岸检测

1. xss的标签
2. 说说大学这几年，你最自豪的事情
3. 简单说说sql注入
4. 说说偏移注入
5. 说说ctf你都做哪些题型
6. 遇到的比较困难的web题型的ctf题目
7. xxe了解吗，有没有自己审计出
8. 说说反序列化
9. bypass说说
10. 假如，让你设计一个waf，你会怎么设计
11. 内网渗透与提权了解吗
12. 平常都挖掘哪些src
13. 有没有自己手写过一些脚本
14. 说说sql注入，手工怎么爆出所有库名字



# 0x15 360-安全工程师实习

时长：45min

来源：知乎

链接：https://zhuanlan.zhihu.com/p/362868972

1. 自我介绍

2. WAF及其绕过方式

3. IPS/IDS/HIDS

4. 云安全

5. 怎么绕过安骑士/安全狗等

6. Gopher扩展攻击面

7. Struct2漏洞

8. UDF提权

9. DOM XSS

10. 数据库提权

11. 怎么打Redis

12. 内网渗透

13. 容器安全

14. k8s docker逃逸

15. linux、windows命令：过滤文件、查看进程环境变量

16. 站库分离怎么拿webshell



# 0x16 某一线实验室实习

来源：知乎

链接：https://zhuanlan.zhihu.com/p/426747686

## 技术面

1. 面试官：你好，听说你对来我们公司的意愿非常强烈，是为什么呢

  我：因为我在项目中与贵公司的人员有过合作，感觉无论是技术还是硬件或者是待遇都算圈子里一流的

2. 面试官：那你了解我们实验室吗？

   我：我有了解过，巴拉巴拉说了一下

3. 面试官：那我先给你介绍一下实验室的方向，分为三个方向….

   我：好的明白了

4. 面试官：你在项目中是否使用过我们公司的设备，感觉使用体验如何（意思就是让说设备的优缺点）

   我：那我就实话实说了？

5. 面试官：没问题的，我就想听听你的意见

   我：我使用过…. ,优点就是性能好，能探测到更多的威胁情报之类的（大家脑补吧），感觉不足的就是探测和分析出的威胁，没法给出具体的流量片段，没法通过一个设备有效确定攻击，没有流量特征不好和其他全流量设备进行联动，可能是设备出场的保护机制，保护特征库不被外泄。

6. 面试官：你知道主流的设备原理和开发过程吗

   我：（我就说了一下原理，还不知道对不对）

7. 面试官：你在项目中是做过流量分析对吗？能不能说说你的具体案

   我：我在国家hvv中协助发现过0day，单独发现过frp反弹定时回确认包向外输送流量，shiro反序列化等漏洞（我主要讲了我frp反弹的发现思路和流程）

8. 面试官：除了这些常规的特征发现，你自己还有什么快速确定的方法吗？

   我：（给大家分享一下我自己的流量分析心得）

   1. 确定事件的类型（确定事件是什么样的攻击，比如sql注入和爆破和frp的流量分析步骤就不一样）
   2. 确定事件的时间，首先划定一个时间段
   3. 确定数据流，攻击的数据流我们是要看HTTP，TCP，还是ssh
   4. 分析是内网—>外网还是外网—>内网，内网和外网时两种查询方法，正确的查询能有效的通过分析更少的数据包获取结果
      比如 内网—>外网 我们确定后，第一步肯定先去先查看外网ip的流量，判断行为
      外网—>内网 这样一般都是拿下了一个外网的服务器当做跳板机，我们肯定要先去分析内网的受害者服务器，看看有没有被攻击成功
   5. 首先我们需要确定到攻击行为后，再深入的流量分析和应急响应，很多都是误报
   6. 数据包的大小也是分析的条件，分析SSL数据包需要解密
      - 爆破攻击
        1. SMB,SSH,MSSQL等协议比较多，看包的大小，成功登陆的包很大
        2. 看ACK，SYN包的次数，如果成功至少20起步，放到科莱上为40起步，但是注意不是失效包和重传的包（注意加密流的ack和syn包也很多，为客户端一次，服务端一次）
      - 重传攻击：
        1. 如果一个数据包非常大，几个G或者一个G，我们就考虑数据包是否进行了重传，然后查看数据包的重传数，打个比方就是刷新，如果短时间重传数非常多，就为机器操作，判定为攻击
   7. 我们发现一个攻击（如平台登录后的sql注入）我们可以通过流量回溯装置抓取那个被登录用户的用户名和密码，登录平台后自己利用发现的payload进行尝试，看是否能注入成功


9. 面试官：听说你还做过红队？是哪个项目，你在里面的职责是什么

   我：介绍了一下我的项目经验，然后说我在红队的是突击手负责打点（我们当时孤军奋战没后援，也没擅长内网的选手）

10. 面试官：说说你项目中的成果

    我：….

11. 面试官：说一下你在项目里遇到的问题

    我：我们通过exp拿下了一个锐捷路由器的webshell，但是卡在了反弹shell上面，无法进行反弹

12. 面试官：那说一下项目结束后你是否有思考过这个问题，是否咨询过他人，解决方式是什么？（我感觉真的非常重视思考和问题解决，非常重视项目的闭环）

    我：我有问过也拿过锐捷路由器的朋友，然后我认为是数据库和网站分离开了，然后只能拿下来webshell权限

13. 面试官：你如何快速准确的确定资产？

    我：通过fofa，谷歌语法，钟馗之眼，一些的注册信息

14. 面试官：fofa的语法是什么？

15. 面试官：你如何在这些资产中快速的确定漏洞？

    我：最快的就是扫描器先扫描一遍，然后进行信息搜集，针对性的攻击，或者我们通过fofa语法针对性的在资产表中搜集是否存在特殊的cms或者oa系统….

16. 面试官:一般扫描都会封禁你，你会怎么办

    我：我会第一就是使用ip池代理，要么就是使用5g

17. 面试官：你这些信息搜集和攻击都是效率不是很高的，项目结束后你有没有思考解决方法呢

    我：我有想过自己写一个程序，把代码池和一些信息搜集和特定的利用方法融合，但是没写出来（又一次感到代码不好的痛苦）

18. 面试官：那你是否有了解过国家hvv红队的隐藏流量过防火墙的技术呢？

    我：有了解过，但是这个我不太会，没有地方去学（有点尴尬）

19. 面试官：你们在打点的时候有没有什么特殊的方法呢？

    我：我们除了搜索特点的oa系统，还会搜集资产里的邮件系统，进行信息搜集登录邮件系统，搜集各种配置文件数据库文件登录网站后台，我们成功登录到两个网站后台，和一个邮件系统，也拿下了几个oa

20. 面试官：你们这么针对特定oa，是因为有0day吗（笑）

    我：我们队有这几个oa的0ady和半day

21. 面试官：开发这边怎么样？能直接上手开发吗？

    我：python还能自己开发几个小工具，java还是只能看懂（好尴尬我真不行，可能是学安全时间还不够长，本来想今年主攻代码的）

22. 面试官：意思就是只能开发几个简单的扫描脚本对么（大家一定啊要好好学代码）

    我：是（尴尬的笑），最近在学习使用pos3编写poc

23. 面试官：你如果来实习你想进行哪方面的学习呢？

    我：（我选择了一个偏向防御类的方向，因为我知道攻击类的我应该水平不够，我很有自知之明）
    然后就是一些询问能工作几个月，什么时候能到岗

> 综合下来我认为面试官认为我的不足就是，红队时的攻击和信息搜集效率不高需要改进，可能缺少一点项目的反思和解决思路

## hr面

1. 首先介绍一下你自己的经历？
2. 你才大二该大三，你在学校是怎么自学安全的？
3. 你是怎么接触安全的？
4. 你现在的学习内容是什么？
5. 近期的学习规划是什么？
6. 你在大学中平时课程和安全的学习是怎么分配的？是否会冲突？



# 0x17 腾讯-科恩实验室实习

## 一面

时长：一个半小时

1. tcp三次握手
2. 介绍一次渗透测试过程  
   - 讲了一次代码审计
3. SSRF漏洞
4. 内网渗透大致流程
5. 再介绍一次难度比较高的渗透测试
6. 防守方有哪些入侵检测手段，有哪些痕迹是可以抓到的‌
7. 介绍进程和线程
8. 进程和线程内存空间的关系
9. 父子进程的介绍
10. 孤儿进程和僵尸进程    
    - 这个我讲反掉了
11. kill一个进程的时候，都发生了那些事情，从父子进程角度讲
12. 反弹shell的几种方式    
    - 本质是用tcp协议传输bash程序
13. att&ck矩阵的类别，介绍其中的CC
14. 到域名下拿到命令执行的结果
    - 这部分没听清楚，面试的时候直接说了不知道，复盘听录音还是没怎么听清，但好像大概想问的是DNS域名解析获取命令执行回显
15. Linux命令通配符
16. 护网的溯源、威胁分析工作之类的问了十分钟左右
    - 完全不会，以后简历上再也不写护网了
17. xx攻防演练中防守方有哪些手段，问的比较杂，主要就是问入侵痕迹检测和溯源之类的东西
    - 这部分也不太会

18. SVM、KNN介绍

19. 卷积神经网络介绍

20. 莱文斯坦距离

21. 搜索引擎算法
    - 不太了解，大概讲了下字典树

22. 倒排索引
23. 恶意样本给出函数家族的md5，如何进行分类
    - 从统计规律讲了下
24. 反问



## 二面

时长：半小时

1. 第一个问题就直接问了护网，和一面问的差不多，直接裂开
2. Linux开机自启动方式
3. init.d脚本介绍
4. Linux怎么查看程序调用了哪些文件
5. 如何监控Linux文件操作
   - 问到这里就已经非常慌了，Linux比较进阶的操作都不是很会，而且面试官一直在叹气我日
6. Linux有哪些系统调用
   - 不会
7. GDB调试
   - 不会
8. 查看Linux开放的网络端口、多线程状态
9. 反弹shell的方式
10. Linux下怎么隐藏文件
11. 子域名收集
12. DNS重绑定
13. DNS解析的流程
14. CC流量
    - 听都没听过
15. ssh隧道
    - 面试没听清楚，听到隧道就以为是UDP穿越隧道开讲了
16. https证书机制介绍
17. burpsuite一些使用方法，插件开发方法
18. nmap的基本操作
19. syn开放链接原理
20. redis漏洞利用
21. runc容器逃逸原理
22. 常见WAF种类(不知道为什么还特别问了长亭的WAF)
23. MySQL的UAF
    - 没听过
24. 算法题(比较简单，leetcode easy级别)
25. Linux进程通信
26. 反问



---

> 备注：从0x18~0x1B均来自于许少牛客网的分享，不多说了，许少yyds
>
> 作者：4ra1n
>
> 链接：https://www.nowcoder.com/discuss/772753?source_id=profile_create_nctrack&channel=-1
>
> 来源：牛客网

# 0x18 某四字大厂面试复盘

这个面试有许少的两个问答式文章，建议参考

一面链接：https://zhuanlan.zhihu.com/p/412934756

二面链接：https://zhuanlan.zhihu.com/p/413684879

## 一面

1. 看你做java多一些，讲讲java内存马原理和利用
2. 那你讲下如何查杀java内存马，工具和原理角度
3. 冰蝎和哥斯拉了解吗，讲讲原理
4. 你之前在其他公司实习做了些什么事情
5. 有绕waf的实战经验吗，从各种漏洞的角度谈下
6. 熟悉webshell免杀吗，讲下原理
7. 做过其他免杀吗，比如结合cs和msfvenom的
8. 谈谈fastjson反序列化原理和常见利用链吧
9. 数据结构熟悉吗，谈谈红黑树原理
10. java的hashmap用到红黑树，讲下hashmap的原理
11. 有没有流量分析的经验
12. 谈谈代码审计经验
13. 看你有些cnvd和cve，讲讲挖洞的过程
14. 有打过知名的ctf吗，讲将经历
15. 熟悉内网渗透，域控这些，说一下实战经历
16. 谈谈java反序列化的cc链原理吧
17. 看你重写过sqlmap，读过sqlmap源码吗
18. 看你熟悉mysql，讲讲索引，存储结构等
19. 讲讲mysql为什么要用b+树
20. 看过mysql源码吗
21. 分析过二进制漏洞吗
22. 有没有用汇编写过东西
23. 谈谈linux内核的漏洞
24. 挖过缓冲区溢出漏洞吗
25. python的沙箱逃逸了解吗
26. python的flask模版注入讲讲
27. 看你做过抽象语法树相关的项目，谈一谈
28. 讲讲rasp的概念和原理
29. 谈谈rasp的对抗
30. 谈谈php和golang语言本身的安全问题
31. 机器学习和算法相关懂嘛
32. 看你尝试写过简单的操作系统，谈谈思路
33. 你有什么要问我的吗

## 二面

1. 讲讲你挖过印象最深的洞
2. 讲讲你写过的安全工具，从出发点和原理层面谈谈
3. 讲讲文件上传这里怎样绕WAF
4. SSRF的利用和绕WAF手段
5. 谈谈MSSQL如果XPCMDSHELL不能用怎么拿SHELL
6. 遇到没有回显的RCE怎么办
7. 不使用SQLMAP的OS-SHELL，各种数据库怎么写SHELL
8. 给你一个比较大的日志，应该如何分析
9. 谈谈redis未授权会导致哪些问题
10. 讲讲SYN FLOOD原理，防御，检测手段
11. 讲讲UDP反射放大的原理，防御，检测手段
12. 说一说自己的优势吧
13. 你有什么要问我的吗

## 三面

1. Padding Oracle Attack讲讲
2. Fastjson反序列化原理以及1.2.47绕过的原理
3. 除了readObject以外造成反序列化的函数有哪些
4. CC链中找你最熟悉的几条链讲一讲
5. Shiro550反序列化的原理及利用工具编写思路
6. Spring/Struts2的RCE中印象最深的讲一讲分析过程
7. sql注入绕WAF的方式尽可能多说
8. 分块传输绕WAF的原理
9. 文件上传绕WAF的方式都有哪些
10. 讲讲你挖过这些CVE中印象最深的
11. 你自己最大的优点和缺点是什么
12. 未来你想做安全的哪一个领域
13. 你学校成绩如何有挂科吗
14. 你有什么要问我的吗



# 0x19 某四字大厂实习面试复盘

## 一面

1. 自我介绍
2. 数组和链表各自的优势和原因
3. 操作系统层面解释进程和线程区别
4. 线程和进程通信方式以及数据安全问题
5. 多进程和多线程的选用场景以及原因
6. 了解过哪些WAF说说原理
7. 尽可能多地说下SQL注入绕WAF方式
8. FUZZ绕WAF的Payload长度通常是多少
9. 写过哪些正则说说具体的场景
10. 不查资料不能测试直接写ipv4的正则
11. Fastjson的反序列化原理
12. Java反射机制会导致怎样的安全问题
13. XSS和CSRF的相同点以及如何配合利用
14. CSRF_TOKEN的位置以及原理和绕过
15. 尽可能多地说你所知道的HTTP头
16. Nmap常见扫描方式的原理以及NSE脚本原理
17. 看到你有不少CNVD证书讲一讲挖洞过程
18. 讲一讲你考过的证书都学到了些什么
19. 看到你Github有不少项目讲讲
20. 你觉得自己还有什么亮点吗
21. 你有什么要问我的

## 二面

1. 自我介绍
2. 熟悉哪些Web漏洞讲讲
3. 跨域的解决办法原理以及安全问题
4. Python多进程和多线程如何选择
5. Python的GIL锁本质上做了什么事情
6. Java的JVM为什么要有GCROOT
7. Java的JVM有哪些垃圾收集器
8. 垃圾回收计数引用机制的缺点是什么
9. CSRF怎么拿到Cookie
10. 如何判断一个网站是钓鱼网站
11. 不同域名怎样通过CSRF拿Cookie
12. 说一些常见的HTTP头以及作用
13. HTTP-Only本质上做了什么事情
14. 平衡二叉树和二叉搜索树讲一下
15. SYN Flood攻击原理及解决方案
16. SYN 反向探测的原理是什么
17. TCP SYN Cookie的原理
18. ARP欺骗攻击原理及解决方案
19. UDP端口探测的有效方式是什么
20. Nmap的FIN扫描和空扫描是什么
21. 三次握手的序列号变化说一下
22. Python的值类型和引用类型是哪些
23. Python的list和dict线程安全吗
24. 讲一下你做过收获最大的一个项目
25. 你有什么要问我的

## 三面

1. 自我介绍
2. 解释下CSRF
3. 结合实际的例子说说SSRF
4. 结合实际的例子讲讲RCE
5. 为什么现在文件上传很少了
6. 基于语义分析的WAF了解吗
7. 讲一下你上一段实习做了什么
8. 讲几个印象深刻的挖洞经历
9. 讲一下你对未来的规划
10. 有没有转正的意愿
11. 你有什么要问我的

## 四面（HR）

1. 面试的体验怎么样
2. 谈人生理想
3. 最早实习时间



# 0x1A 某两字大厂面试复盘

## 一面

1. 自我介绍
2. 前两段实习做了些什么
3. 中等难度的算法题
4. java的class文件结构
5. kafka的原理了解吗
6. fastjson反序列化原理
7. 讲讲你研究最深入的领域

## 二面

1. 排序处不能用预编译应该怎么防
2. 从白盒黑盒两个角度讲下挖过的漏洞
3. ssrf的绕过和防御
4. 讲讲fortity等代码审计工具原理
5. 存储过程角度讲讲预编译的原理
6. csp是如何防御xss的
7. csrf为什么用token可以防御
8. 给你一个项目讲下审计思路
9. 内网相关的问题
10. 讲下你挖过的逻辑漏洞
11. 讲讲你用golang写过的东西
12. 什么是安全

## 三面

1. 讲下你自己写ysoserial的思路
2. 确定sql注入漏洞后如何进一步利用
3. 泛微OA的漏洞原理讲讲
4. 新爆出的Confluence RCE讲讲
5. 以前的实习中做了什么事
6. ***原理以及实战中的绕过
7. 红蓝对抗的流程讲讲

## 四面

1. java反序列化原理和工具
2. 讲讲关于指纹识别的方式
3. shiro反序列化工具的原理
4. 不用sqlmap情况下sql注入点如何找
5. 讲讲你挖到的这几个cve
6. 二进制方面有无了解



# 0x1B 某安全公司-安全研究员

## 一面

1. 讲讲你写的几个Burp插件原理
2. 做过什么JavaWeb项目吗
3. CC1-7找熟悉的讲一下原理
4. Fastjson和Jackson反序列化原理讲讲
5. BCEL可以用其他类加载器吗
6. XStream反序列化讲讲
7. 最基本的反序列化原理是什么
8. 了解JEP290的原理吗
9. 讲下RMI原理以及相关的漏洞
10. JdbcRowSetImpl如何触发的JNDI注入
11. CC链四个Transformer区别
12. 讲下你挖过的CVE和CNVD
13. 反序列化除了readObject还有什么触发点
14. 讲下Spring相关的RCE原理
15. 讲讲IIOP和T3反序列化原理
16. PHP等语言的反序列化讲讲

## 二面

1. 做了几年安全
2. 未来想做什么
3. 讲讲实习期间做的事
4. 工作地点要求



# 0x1C 腾讯-科恩实验室实习

## 一面

时长：一个钟

1. 自我介绍
2. 简单介绍做的项目->基于项目的衍生（搜索域、搜索方法等）
3. 逆向C++相比起逆向C有哪些困难点？有用IDA python吗？
4. Linux程序分为哪几个段？
5. .data段存放哪些数据？.bss段存放哪些数据？
6. 函数调用时的流程，参数如何传入，寄存器的变化，栈的变化？
7. 解释程序的编译和链接，编译的过程中会有哪些操作（编译原理），If/Else语法树？
8. 了解Linux /proc目录吗？如果要查看进程打开了哪些文件，有哪些方法？
9. 人脸识别有哪些方法？怎样去进行相似度比对？有没有听过三元组损失
10. 如何比较两篇英文文献的相似度？如何比较两个C函数的相似度？
11. 什么情况下源代码与IDA反编译程序的代码差别很大？讲讲函数展开造成的区别？如何消除这种区别实现代码相似度匹配？
12. 了解TF-IDF文档匹配算法，搜索引擎的算法吗？
13. python中集合，求交集与并集的时间复杂度是多少？有没有o(1)的方法，迅速判定元素是否在集合中？



## 二面

时长：一面的一半

1. 工控场景的入侵检测与普通场景入侵检测的区别（简历项目）
2. 有了解过真实场景的入侵检测项目吗？（如一个企业办公的出口网部署入侵检测）
3. 面对加密后流量，正常访问与木马的区别可能有哪些？如何用AI或传统方法进行检测？是有监督问题还是无监督问题？
4. 面对静态编译的大型木马（几百M...），如何通过IDA定位其网络传输部分的逻辑？
5. 如何动态地去找导入表->从攻击者的角度，如何不在编码时直接导入相关API的前提下进行攻击？
6. Windows下有哪些常用的反调试技术？
7. 单步执行的原理是什么？
8. 在内存中已Load的程序，如何快速找到其具有执行权限的段？
9. 恶意软件有哪些方案检测自己处于沙箱中？
10. 怎么知道进程和其开的端口的对应关系？
11. SGD和Adam的区别？
12. 神经网络架构搜索领域目前的进展
13. WAF的实现原理，与IDA的区别，WAF针对包会检测哪些字段
14. 简介Linux下的Syscall
15. 工作中符合个人兴趣的研究项目或思路
16. 如何缩减模型的检测时延？
17. 如何降低模型的误报率？
18. 如何找攻击样本？



# 0x1D 长亭科技 安全服务工程师实习

1. 讲一下最熟悉的三种web漏洞类型，原理，测试方式
2. SQL注入过滤单引号怎么绕过
3. mysql报错注入常用的函数
4. 报错注入绕waf
5. mysql写文件的函数有哪些
6. into outfile使用有哪些限制
7. mysql提权
8. sqlserver除了sql注入外还有什么渗透的方式
9. ssrf漏洞原理
10. ssrf可以使用的伪协议
11. 哪些功能点会有ssrf
12. 对内网ip进行过滤，有什么绕过的方式
13. 有了解过Redis RCE的过程吗
14. Redis未授权如何获得服务器权限
15. Redis主从复制漏洞
16. 任意文件读取，一般读取什么类型的文件
17. 如何通过文件读取获取到web的绝对路径
18. /etc/passwd文件包含哪些内容
19. java反序列化漏洞有了解吗
20. 之前shiro的反序列化漏洞有了解吗
21. 知道哪些组件或中间件包含反序列化漏洞
22. 针对一个站点，你首先会做什么事
23. 说几个你比较熟悉的CMS，它有哪些特征
24. 正向代理和反向代理的区别
25. 说一下常见的端口对应的服务有哪些
26. 有没有接触过护网这块的工作
27. 比较常见的内置用户有哪些
28. 说一下映像最深刻的一次渗透测试经历，说一下大概过程，发现了什么漏洞
29. 有没有挖过业务逻辑的漏洞
30. 挖过哪些SRC
31. 挖到最多的是哪些类型漏洞
32. 弱口令，有验证码怎么绕过
33. 说一下非对称加密算法的加密过程
34. 有哪些了解过的非对称加密算法

---

> 接下来篇都是来自`xiabee`师傅在牛客和博客上的同步分享
>
> 牛客链接：https://www.nowcoder.com/subject/index/8032f6748b124176bbe67fb37b19ecad
>
> 博客：
>
> 作者(Author)：xiabee
>
> 链接(URL)：https://xiabee.cn/coding/2022-spring-recruitment/
>
> 来源(Source)：xiabee-瞎哔哔

# 0x1E PingCAP 安全工程师

岗位：安全工程师

## 一面

时长：四十多分钟

CTF相关：

1. 你给同学的授课内容
   - 如实说 
2. SQL注入如何判断数据库类型
   - “sqlmap一把梭......” 
   - 手动注的话用version函数等 
   - 面试官在听完我的答案之后说了他的答案：一般采用撞函数的方法，xxx数据库的函数名是xxx，xxxx数据库的函数名是xxxxx，特定函数执行正确的话即可判断数据库类型，`version`广义上说说撞函数的一种 
3. 布尔盲注、时间盲注
   - 忘记怎么答的了，面试官应该没有补充我的答案 
4. 印象中比较有价值的题
   - 聊了一下去年的国赛SQL签到题，“网络原因，时间盲注不行......” 
   - 聊了一下职业杯的某题，特定的font导致报错看不到，最后用curl实现了报错注入 
   - 聊了一下职业杯的某题，利用注入直接执行了SQL命令修改了密码执行逻辑，而非传统的读写注入 
5. 接上一题的`font`，“平时用过Burp Suite吗，BP中会打印全部内容，为什么会看不见`font`呢” 
   - “用过，当时太懒了没开BP......curl了一下发现可以注就懒得开BP了” 
6. 一些BP的操作
   - 忘了答了啥，应该没啥大问题 
7. SSRF相关
   - 简单聊了一下 
8. 如何理解逻辑层面的漏洞
   - 聊着聊着跑题了，后面面试官提醒我，又重新编了一段（x）
   -  大概意思就是“不该加的功能别乱加”，顺便提了一下log4shell的漏洞成因，“乱加功能” 
9. XSS相关
   - “打比赛用的不多，细节可能忘记了”

 护网相关：

  10. 聊聊演习
  11. 如果让你给甲方企业做渗透测试，你的大概思路 
      - 主站扫描、CDN检测、口令探测、注入之类 
      - 在授权范围内攻击上游厂商，尝试获取甲方站点源代码，现场审计0day 
      - 在授权范围内攻击下游客户、旁站等，先进入内网再突破DMZ 
      - 面试官也给出了他的答案进行补充，具体是啥忘了...... 
  12. 介绍了很久的黄金票据和白银票据，准备提问...... 
      - “金银票据听说过，但是具体使用细节不熟悉......没有实操过” 
      - 面试官给我科普了一下 

项目相关：

13. 邮件系统 
    - 大概聊了一下多线程编程，C与python 
14. 作品赛
    - 背了一下摘要，讲了一下个人工作，区块链与libsnark 
    - 没有细问，但是也没有打断我，让我自己叨逼叨了半天
15. 区块链与智能合约
    - 聊了一下truffle、solidity，吐槽了一下solidity不好用 
16. 爬虫 
    - 聊了一下“乐学给爷爬”系统和知乎刷流量系统 
    - “初代项目，维护跑路，停止服务” 
17. 容器，介绍了很久的k8s，准备提问 
    - “暂时还不会，目前只用过docker-compose”，场面一度十分尴尬 
    - 虽然但是，面试官还是给我科普了一下k8s 
18. 可能还问到了一些二进制的问题，具体忘了 
19. 反问：工作时间，是否加班等 
    - “我们和国外公司比较像，周六周日、法定节假日一定不上班” 
    - “我们以结果为导向，上班时间没有强制要求，你愿意九点来也可以，愿意十点来也可以；愿意五点走也可以，愿意六点走也可以，公司没有强制要求；如果有需要，也可以远程办公”
    - “正常情况下不加班，但是如果遇到突发事件可能需要应急响应，像log4shell这种级别的漏洞就得做应急” 
    - 聊到这里突然有点哽咽，如此遵守中国劳动法的公司，对标的却是外企，国内996的公司真的需要那么多人996吗......

> 总体而言，PingCAP是截至目前，我面试过的面试体验最好的公司，问题的问题很深入，涉及的面很广，但是不管我答的有多烂面试官都会听我讲完；并且能明显看到面试官在记录面试内容，在我讲完之后再针对性提问，而不是在我讲到一半直接打断我...... PingCAP是今天最晚面试的公司，但是最早发出了二面邀请（大概一面过了三个小时就通知了）......可以感受到他们虽然不加班，但是效率还是挺高的。

## 二面

>  实打实面了一个小时，聊了很多很多方向，从项目经历到个人发展规划，还聊到了公司选择等，感觉收获挺大的。 

1. 自我介绍
   - 简单背了一下简历（然后是针对简历的提问） 

作品赛相关:

2. 介绍这个系统 
3. 数据安全相关
4. 聊了一下区块链的开发经历 

区块链相关

5. 智能合约的鉴权、公私密钥相关等 
6. 数字钱包的身份认证等 
7. 智能合约的开发遇到那些困难 

作品赛相关:

8. 这个系统和普通联邦学习系统有什么突出特点吗
   -  “挺鸡肋的......保证了安全性，但是牺牲了性能”（瞎说什么大实话）
9. 聊了一下大型开源项目二次开发的经历与感悟

渗透相关:

10. 介绍一下渗透经历
11. 方便聊聊渗透思路吗
12. 渗透过程中的感悟，防守方有哪些不足，作为进攻方主要利用了哪些方式进行渗透 
    - “利用防守方安全意识薄弱......正经的WAF打不穿，但是并不是所有的站点都有WAF” 

 Github相关

13. 面试官看到了我的Github，里面有一些docker-compose的脚本，聊了一下项目 
14. 介绍一下上述项目的开发历程、设计初衷等
15. 聊了很多云配置的内容 
16. 聊到了LNMP的系统搭建，dockerfile相关 

CTF相关

17. 介绍一下CTF相关学习、比赛、获奖等
18. 介绍一下擅长领域

工作意向相关

19. “像你有CTF经历，简历也不错，应该能去很多公司，像长亭、腾讯云、深信服等，包括我们公司，你对未来的公司选择会有怎样的考虑” 
    - 直接点名长亭了，有点慌；内心OS：长亭的面试邮件到现在都没发，PingCAP搞快点把我收了...... 
    - 说了一下自己的选择标准：优先选择“不加班”，然后选择可能可以落户的公司，最后比较薪资； 

20. 关于加班问题和面试官产生了一点分歧，“我可能要给你泼点冷水，我们也不是不加班，对于一个刚入职的新人，而且你还这么有目标，为了自己的理想肯定是要付出一定努力的......” 
    - 狡辩了一下，“我不是厌倦加班，我厌倦的是那种没有意义的加班......单纯的堆积工作时常其实没有太多意思” 
    - 然后提到了其他申请的公司，聊了一下对其他公司以及PingCAP的看法；没有踩一捧一的意思，就单纯的聊了一下对工作模式的看法 

21. 英语水平相关: 问了一下口语咋样，但是没有直接上英文，好像下一轮有英文 
22. 反问环节：问了一下面试流程，其他忘记了 

> 二面居然秒过了（半小时以内吧），我这面试复盘害妹写完就给我发三面邮件了......呜呜呜我宣布PingCAP也是我的Dream Company之一

## 三面

> 项目主管面，总面试时间约50分钟，聊的内容挺多，体验也很不错。

1. 自我介绍
2. 介绍一下项目
3. SSRF相关
4. 开发过的脚本、项目等
5. python相关：python是真正的多线程吗
6. 挖过的漏洞
7. 英语相关：用英文介绍一下XSS 
8. 英语相关：介绍不出来，介绍一下自己吧 
9. 平时安全相关的技术是怎样学习的呢 
10. 了解安全咨询的渠道等 
11. 实战相关 
12. 反问：主管介绍了工作内容、工作组等 
13. 反问：实习相关 
14. 主管点评：整体不错，渗透和开发这块需要加强，个人强项不够突出，可以多看看漏洞测试、漏洞公开等，尝试自己挖掘开源项目的漏洞

## 四面

> 大主管+HRBP面，一共面了约四十五分钟，大主管面了半小时，HRBP面了十五分钟左右。 大主管主要是业务方向，对攻击手段问的不深，主要是防护与架构相关的问题，给我一种我是架构师的错觉（不是） 

1. 介绍一下你了解到的C/C++相关漏洞 

   - 聊了一下缓冲区溢出 
   - 聊了一下和其他业务嵌套时的漏洞 

2. 详细聊聊缓冲区溢出 

   - 栈溢出 

   - 堆溢出（不会） 

   - BSS溢出（不会） 

3. 缓冲区溢出如何避免 

   - 编译时避免 
   - 运行时避免 

4. 了解GO语言吗

   - “暂时不了解” 

5. “没有关系，那根据你的认识，你认为GO语言有哪些安全漏洞呢” 

   - “缓冲区溢出是不可避免的，只是利用难度的区别” 
   - 然后提了一下嵌套业务相关的漏洞 

6. 刚刚提到的其他漏洞如何避免 

   - 提到了SQL注入等
   - “预编译，上WAF” 

7. WAF相关，对于某些实体，比如本身就是一段SQL代码，如何防止误报

   - 实体化，权限控制，纯代码直接实体化，使其没有执行权限 
   - 不能实体化的代码宁可误报也不放过......（瞎答的） 

8. 开放性问题，本公司的攻击面有哪些，应对策略有哪些 

   - 具体比较细节了，包括内部攻击外部攻击之类的 
   - 回答的比较泛，基于规则/行为/角色等，也对一些具体的服务说了些应对策略 

9. 数据安全相关，安全架构相关，如何保障数据安全等 

   - 零信任模型 
   - 最小权限原则 
   - 基于身份/角色的访问控制等 

10. “简历里面提到了容器，你对容器安全有了解吗” 

    - 瞎扯了点容器逃逸 
    - “平时接触容器主要是开发，容器安全接除不多” 

11. 剩下内容不记得了，大概问了半小时 

12. 反问：安全组的人员配置、团队规模等，以及这个凑够一桌麻将开office具体政策 

    - 安全团队其实都是remote work，基本上都不在北京...... 
    - 开office的政策由HRBP解答的，确实有，也可以在南昌开，凑够人就行。 

    

> HRPB基本上没有涉及技术问题，中途聊了一下作品赛，可能是提到了数据安全，HRPB对这个比较感兴趣（x） 

1. 在北京吗

2. 有无实习打算 

3. 是否为独生子女 

4. 有无考研打算 

5. 回应了一下刚刚开office的问题 

6. 还有没有其他公司的offer 

7. 对公司的选择是怎么样的 

8. 为什么觉得PingCAP是dream company 

9. 反问环节问了一下怎么不谈薪资......“下一轮会有专门的同学和你交流”

   

> 从0x1F到0x26都来自于https://github.com/biggerduck/RedTeamNotes/blob/main/2022%E5%A4%A7%E5%8E%82%E9%9D%A2%E7%BB%8F.pdf  觉得写的很好就把一些比较多的整过来了，建议去下个pdf看前言部分，问题部分仅供参考

# 0x1F shopee

1. 和信息安全相关的返回 response 头（https://www.cnblogs.com/yungyu16/p/13333909.html） 
2. linux 常见命令 
3. docker 常见命令 
4. jwt 是什么 
5. weblogic 反序列化原理（有一个 xml 反序列化漏洞 还有后台文件上传 还有二次 urldecode 权限绕过） 
6. java 代码审计 exec 命令执行的相关利用 前面拼了一段 然后调用 lang.runtime.exec("fuck" + a) 这里可以利用吗 （不行 因为根据 exec 的方法 这里不能识别执行） 
7. 内存马相关原理 
8. shiro 反序列化漏洞利用的时候 由于 waf 过长 被 ban 了 怎么解决这个问题（如果是 waf 拦截 可以尝试更换 http 头 如果是 tomcat 头过长 可以在 cookie 写一个 loader 然后 shellcode 写到 body 里） 
9. 内存马扫描原理 如何检测内存马 
10. java 代码审计反序列化原理(输入的恶意类被识别 解析了) 
11. ysoserial 原理 commoncollections 利用链的原理 (cc1 最后 invoke 反射加载输入的方法 cc2 cc3 等等大同小异) 
12. linux 全盘查找文件命令(find / -name fucku) 
13. docker run 的常用命令(docker run -it centos -p --name -d ) 
14. java 反序列化 php 反序列化 python 反序列化的区别和相同点(java 反序列化需要利用链 php反序列化也需要利用链 python反序列化不需要利用链 有一个\_\_reduce\_\_可以自己构造 命令执行) 
15. linux 全盘搜索含有某个字符的文件/linux 全盘搜索叫某个名字的文件(grep -rl 'abc' /)(find -name / fucku)



# 0x20 深信服

1. 宽字节注入原理，是只有 gbk 编码的才存在宽字节注入吗？ 
2. php 反序列化原理 
3. 内网一台机器，只有一个 mssql 的服务账户权限，如何进行后续的利用 
4. rsa 算法原理/aes 算法原理 
5. 一台机器不能出网，如何把一个 exe 文件放到对应的目标机器上去（dmz 区）



# 0x21 华为

1. log4j 如何绕过 trustcodebase 
2. Springboot+shiro 环境如何进行渗透 
3. 实战中如何判断 fastjson 的版本 
4. Fastjson 文件读写 gadget 是哪条，原理是什么 
5. 内存马类型，如何检测 
6. 给一个后台登录框有什么利用思路 
7. Spring4shell 原理&检测&利用 
8. 安卓系统如何进行 rce，有什么思路 
9. 给一个移动端的 app，已知服务端是 cloud 环境，有什么思路利用



# 0x22 360

>  红队&&企业蓝军方向
>
> 以下都是同一场面试提的问题，两个面试官，一个代审一个红队，时长接近两小时

1. shiro 如何绕 waf 
2. weblogic 如果在打站的时候，一旦遇到了 waf，第一个 payload 发过去，直接被拦截了， ip 也被 ban 了，如何进行下一步操作 
3. jboss 反序列化原理 
4. weblogic 反序列化原理，随便说一个漏洞，然后说触发原理 
5. fastjson 怎么判断是不是有漏洞，原理是什么 
6. fastjson 判断漏洞回显是怎么判断的，是用 dns 做回显还是其他的协议做，为什么 
7. fastjson 高版本，无回显的情况，如何进行绕过，为什么可以这样绕过 
8. 代码审计，做过哪些，主流的代码审计 java 框架请简述 
9. 泛微，致远，用友这三套系统代码框架简述 
10. 泛微的前台漏洞触发和后台漏洞触发，如何通用性的挖泛微的洞，泛微能反序列化吗， 怎么挖 
11. php 代码审计如果审计到了一个文件下载漏洞，如何深入的去利用？ 
12. php 里面的 disable_function 如何去进行绕过，为什么可以绕过，原理是什么 
13. 假如说，在攻防的时候，控下来一台机器，但是只是一台云主机，没有连接内网，然后 也没有云内网，请问怎么深入的对这台云主机进行利用？ 
14. redis 怎么去做攻击，主从复制利用条件，为什么主从复制可以做到拿 shell，原理是什 么，主从复制会影响业务吗，主从复制的原理是什么？ 
15. becl 利用链使用条件，原理，代码跟过底层没有，怎么调用的？ 
16. 假如我攻击了一台 17010 的机器，然后机器被打重启了，然后重启成功后，机器又打成 功了，但是无法抓到密码，为什么无法抓到，这种情况怎么解决这个问题？ 
17. 内网我现在在域外有一台工作组机器的权限，但是没有域用户，横向也不能通过漏洞打 到一台域用户的权限，但是我知道一定有域，请问这种情况怎么进入域中找到域控？ 
18. jboss 反序列化漏洞原理 
19. 内网拿到了一台 mssql 机器的权限，但是主机上有 360，一开 xpcmdshell 就被拦截了， 执行命令的权限都没有，这种情况怎么进行绕过。
20. 什么是 mssql 的存储过程，本质是什么？为什么存储过程可以执行命令？
21. 如果想通过 mssql 上传文件，需要开启哪个存储过程的权限？ 
22. 内网文件 exe 落地怎么去做，用什么命令去执行来落地，如果目标主机不出网怎么办？ 
23. 内网域渗透中，利用 ntlm relay 配合 adcs 这个漏洞的情况，需要什么利用条件，responder 这台主机开在哪台机器上，为什么，同时为什么 adcs 这个漏洞能获取域管理员权限，原理 是什么 
24. 内网域渗透中，最新出的 CVE-2022-26923 ADCS 权限提升漏洞需要什么利用条件，原理 是什么，相比原来的 ESC8 漏洞有什么利用优势？ 
25. 内网渗透中，如果拿到了一套 vcenter 的权限，如何去进一步深入利用？db 文件如何解 密？原理是什么？ 
26. vcenter 机器拿到管理员密码了，也登录进去了，但是存在一个问题，就是内部有些机 器锁屏了，需要输入密码，这个时候怎么去利用？ 
27. 内网权限维持的时候，360 开启了晶核模式，怎么去尝试权限维持？计划任务被拦截了 怎么办？ 
28. mssql 除了 xpcmdshell，还有什么执行系统命令的方式？需要什么权限才可以执行？ 
29. 如果 net group "Domain Admins" /domain 这条命令，查询域内管理员，没法查到，那么 可能出现了什么问题？怎么解决 
30. 查询域内管理员的这条命令的本质究竟是去哪里查，为什么输入了之后就可以查到？ 
31. 免杀中，如何去过国内的杀软，杀软究竟在杀什么？那么国外的杀软比如卡巴斯基为什 么同样的方法过不了呢？
32. 免杀中，分离免杀和单体免杀有啥区别，为什么要分离，本质是什么？
33. 打点常用什么漏洞，请简述
34. 内网横向中，是直接进去拿一台机器的权限直接开扫，还是有别的方法？ 
35. 钓鱼用什么来钓？文案思路？如何判断目标单位的机器是哪种协议出网？是只做一套来 钓鱼还是做几套来钓鱼？如何提高钓鱼成功率？ 
36. 钓鱼上线的主机，如何进行利用？背景是只发现了一个域用户，但是也抓不到密码，但 是有域



# 0x23 深信服-深蓝攻防实验室

1. 内网怎么打 思路 
2. 国护刷分策略 通用性的寻找通用靶标思路 怎么刷 
3. 数据库 主机 云 vcenter 刷满是多少分（看你打的多不多 对分的规则熟悉不） 
4. 内网的多级代理用什么东西代理 
5. 如果 tcp 和 udp 不出网 用什么策略来进行代理的搭建 
6. 多级代理如何做一个 cdn 进行中转 具体怎么实现 
7. 内网有 acl 策略 如果是白名单 如何绕过这个白名单进行出网上线 ip 和域名的都有可能



# 0x24 B站

1. k8s 和 docker 如何去做攻击 有哪些利用方式 是什么原因导致的 
2. cs 的域前置和云函数如何去配置 
3. 内网攻击的时候 内网有那些设备可以利用 （hadoop kibana 之类的设备） 
4. 攻击 redis 不同的 linux 系统有什么不同 
5. sql 注入的时候，如果遇到了返回的时候长度不够，怎么解决，如何截取，用什么函数截 取 
6. 域前置 
7. 免杀



# 0x25 shopee-红队-Singapore

1. linux 除了基本的内核提权还有什么别的方式可以进行提权 
2. 如何删除 linux 机器的入侵痕迹
3. 寻找真实 ip 的快速有效的办法 
4. print nightmare 漏洞利用&分析
5. java invoke 反射具体利用 
6. 域内常用命令 
7. 根据子网掩码探测指定资产 
8. 什么是无状态扫描 
9. kerberos 原理 
10. ntlm relay 原理 
11. 内网现在微软至今都没有修复一个漏洞，可以从普通的域用户提权到域管用户，用了 ntlm relay，你讲一下是什么漏洞 
12. 100 家单位，现在需要在一天时间内拿到所有单位的 ip，port，banner，怎么做，用什 么东西来做 
13. 黄金票据原理，黄金票据在 kerberos 的哪个阶段？如何制作？用哪个用户的 hash 来制 作？ 
14. cs 域前置的原理？流量是怎么通信的？从我直接执行一个命令，例如 whoami，然后到 机器上，中间的流量是怎么走的？ 
15. java 反序列化原理



# 0x26 长亭

1. spring spel 漏洞原理&利用方法 什么情况才能利用
2. java jdbc 反序列化高版本不出网的条件下如何利用 
3. tomcat becl 如何利用 
4. shiro 反序列化用的是哪种加密方法 如何利用
5. ueditor 哪种语言环境存在漏洞 怎么利用 如何绕 waf 
6. 内网 Windows Print Spooler 利用&原理 
7. 内网 PotitPetam 利用&原理 
8. 域内 pth 和工作组 pth 的差别 
9. 域内用户和工作组用户的差别 
10. 如何攻击域控 
11. spirng4shell&log4j 利用 
12. 外网常用打点漏洞有哪些
13. 一个任意文件读取/任意文件下载，如何进一步利用
14. 用友 nc beanshell 执行命令如何过 waf
15. shiro 反序列化漏洞如果 cookie 中的 payload 过长被 waf 拦截如何绕 waf



# 0x27 奇安信 安全研究员 实习

作者：想搞二进制

链接：https://www.nowcoder.com/discuss/970682

来源：牛客网

## 一面 5.17

1. 自我介绍，内容包括：第一部分，做过的安全相关的有难度的项目，难点在哪。第二部分，安全技能树，哪些是比较擅长的，能做什么。
2. 讲讲linux平台的漏洞缓解机制
3. 讲讲linux平台的ELF文件结构，或者windows平台的PE文件结
4. NX是怎么绕过的
5. 讲讲ASLR怎么绕过
6. 用过kali的msf吗？都用来干嘛了，哪些工具用的比较多？ 
7. 函数的调用约定有哪些?区别是什么?32与64位有什么不同
8. 用fuzzing主要是用来干嘛？主流的产品（chrome那些）有挖过漏洞吗？
9. 对windows平台的漏洞和保护机制了解多少？
10. 分析过linux的公开漏洞吗？写过exp吗？
11. 有没有逆向分析过linux平台下的病毒
12. 英文水平怎么样

## 二面 5.18

  聊了一下我现在做的fuzzing，之前做过的APT实习 

## 三面 5.24

聊对奇安信的了解，聊人生 

6月1号打电话说过了，6月10号收到offer： 珠海安全研究员 



# 0x28 美团 安全岗实习

备注：作者是二进制的

作者：hx19970923

链接：https://www.nowcoder.com/discuss/889681

来源：牛客网

Q: 介绍下项目和专业技能 
A: blah blah 

Q: 说说你的反汇编器如何开发的 
A: 当时学逆向所以想写一个，上网查 x86 指令格式后就开始写 

Q: 反汇编器支持的 opcode 全吗 
A: 一字节的比较全，两字节的不够全 

Q: 做一个反汇编器，指令集 opcode 的意义去哪查 
 A: 厂商的手册，比如英特尔开发者手册，如果是代码虚拟机那种就自己逆向 

Q: 怎么识别指令跳转条件和内存访问 
A: （？没懂这个问题）是说指令 opcode 内部是怎么设计的吗 

Q: （重新解释了一遍问题） 
A: （？？继续懵逼）不同的跳转条件对应不同的 opcode，也对应不同表项，反汇编器里内置了一个表，比如 0xaa 对应 jne，0xbb 对应 je（难道是想问 ModR/M, SIB 那些？ 

Q: （好像还是不满意于是跳过了上一个问题）那你觉得这个项目难点在哪 
A: 一开始完全不懂 x86 指令格式，然后自己学习查资料实现了它（好了我知道没有难点 

Q: 介绍下你开发的 Windows 沙箱 
A: blah blah 

Q: 这个重定向你做全了吗 
A: 文件重定向比较全，注册表的写了一点没继续写 

Q: 做一个沙箱，有什么需要重定向的 
A: 文件，注册表，还有一些 IPC 对象比如管道 

Q: 你做到什么程度 
A: 文件比较全，注册表不全，进程隔离完全依赖于系统安全机制，IPC 对象没做（逐渐小声 

Q: 说说你的研究生课题 
A: blah blah 

Q: 怎么增强模型健壮性的 
A: blah blah 

Q: 怎么看健壮性增强了 
A: 增强前后各自攻击一下记录成功率，降低了就是增强了 

Q: 训练学过的样本又拿去攻击，不会有问题吗 
 A: 训练集和测试集是分开的，对抗训练学的是训练集上的对抗样本 

Q: 比赛是团体赛吗 
A: 是 

Q: 你负责什么 
A: 逆向和少量 pwn 

Q: 这个比赛的脱壳是什么壳，怎么脱的 
A: nSPack，ESP 定律脱 

Q: 有没有手动修复，还是工具直接脱 
A: 没有，OEP 直接 dump（感觉事情不妙） 

Q: 那我可以理解你这个脱壳就是工具点一下呗 
A: ……是（呜呜 

Q: ESP 定律原理知道吗 
A: 一大堆废话，最后才转到堆栈平衡（反思一下应该先点出堆栈平衡再说废话emmm） 

Q: 这场比赛你贡献了啥 
A: 做了这道逆向队伍进了决赛，虽然是因为队里 Web 手没做出题而已 

Q: 看了你的博客，做这些逆向 CTF 题，可能投入了足够时间大家都能会，下一步你要怎么做 
A: （以为是问未来学习规划）一个是实战经验很缺乏，要加强，一个是明确方向，现在有点没方向 

Q: （解释了一下他说的是人工分析有局限，要向自动化分析发展）知道自动化分析吗 
A: 知道但没深入了解 

Q: 你知道哪些自动化分析的例子 
A: fuzzing，AEG，Unicorn 

Q: 自己调试过真实漏洞吗 
A: 无 

Q: 研究生方向为什么不是安全 
A: 导师选的 

Q: 毕业想做安全还是研究生的方向 
A: 安全 

反问阶段 
Q: 部门是基础研发吗 
A: 我们主要做安全的一些基础研究，包括刚刚跟你说的自动化分析，还不是研发 

Q: 能提些学习建议吗 
A: 多实战，往自动化方向靠，深入了解操作系统的细节，重视正向开发 

总结：找实习以来收到的第一次面试，没想到自己这么拉垮。本来就知道自己菜，一问三不知感觉更菜了，看得出面试官尽力找问题问我了，是我不争气凉得明明白白



# 0x29 美团 安全工程师实习

作者：h4m5t

链接：https://www.nowcoder.com/discuss/624742

来源：牛客网

面试官是一位会弹吉他的安全工程师，比较和蔼，没有问刁钻的问题。 面试时间总共15分钟，我也不知道为啥这么短，可能那边有业务要做吧。 

  1.自我介绍 

  2.平时怎么学安全的 

  3.每天有多长时间学安全 

  4.SQL注入有哪些 

  5.给你一个URL，怎么判断注入 

  6.SQL注入防范 

  7.平时有看安全方面的文章吗，讲一篇 

  讲了一下昨晚看的DNSlog注入 

  8.讲一下CTF 

  9.讲一下你做过的渗透 

  最后 你有什么要问的吗？ 

  1.怎么学习安全 

  2.甲方和乙方的安全有什么不同 

**面试建议** 

其实提前看了几篇[美团]()技术部的文章和面试官写的web蜜罐，但我没讲。 

可以提前查一下面试官的研究方向，如果正好是你擅长的，那就好了。如果是你不擅长的，就尽量把话题引导其他方向，让面试官跟着你的项目走。 



# 0x2A 京东 安全研究

作者：方糕姐姐

来源：[牛客网](https://www.nowcoder.com/discuss/1033501?type=all&order=recall&pos=&page=0&ncTraceId=&channel=-1&source_id=search_all_nctrack&gio_id=C644A4A66482D41AB59A3DF3F860459E-1662006302081)

1. 深挖项目。 

  	每个项目的主要难点，以及你做了什么，提到的有中间人攻击、数字证书之类的。 

2. Java八股 

   final关键字的用途？ 


  	static关键字的用途？两者的区别？ 


  	非对称密码[算法]()和对称密码[算法]()的区别和联系？ 


 	 RSA的数学证明？ 


​	  为什么web端的数字证书能够被抓包 解析之类的？ 

​	  序列化和反序列化中有什么漏洞？ 

​	  还有记不清了 哈哈哈 

3. 手撕代码以及优化

   斐波那契 递归 

   双指针 

   快速查询

# 0x2B 百度

作者：zhengtu

来源：[牛客网](https://www.nowcoder.com/discuss/494211)

## 一面

时长：48分钟

1. mysql注入，已知information.schema相关表在代码层中被过滤，不考虑绕过情况，还可以怎么查询表名或字段 
     考虑sys[数据]()库，一些被访问过的表会被存储信息，索引中存在的表等 

2. mysql注入中基于报错注入的多种方式 
    记得floor,updatexml，extractvalue三种，第一种主键重复，后面两种基于xpath语法解析错误 

3. 前端xss如果特殊字符输出被htmlscecial过滤了怎么办 
    该函数默认只编码双引号，对单引号无效 
    在js中可以利用\u003c等绕过符号过滤 
    采用反引号执行命令，(可以采用jquery加载第三方js，或者添加script子节点引入js，或者直接获取cookie利用js访问第三方脚本) 
     编码转换，富文本，[数据]()库输出输入场景都有可能失效，比如前端调用了html函数作为输出的情况 

4. 同源策略是啥，rerfer检测，前端空rerfer防御，怎么构造 
     同源的标准是协议，端口，域名三者的统一，实质是浏览器对不允许的服务端返回的[数据]()进行了拦截 
    实现跨域有两种方式，jsonp和cors 
    服务端验证rerferer头(为空则不用rerferer头判断)，校验csrf token，在http头中自定义属性并验证 

5. jsonp是什么，怎么绕过 
    劫持问题，防御取决于服务端如何配置，绕过取决于服务端的配置，关键词绕过 

6. sqlmap源码是否分析过。 
7. tp漏洞复现 
8. java反序列化rmi原理(简历上有写)，其他类型的反序列化是什么 
9. 如果让你编写一个DOM型xss扫描器，你该怎么写？假如事件需要点击，比如onclick去点击，该怎么检测这种类型的xss 
    返回结果，人工判断，或者利用windows事件触发 

10. 内网渗透流程和方式，比如域渗透 
11. windows10上面的pth怎么利用 

12. linux主机留后门的各种方式？ 
     计划任务，webshell，自启动后门，写注册表 

13. DNS隧道搭建方式

## 二面

时长：53分钟

1. 如何入门的经历 
2. 数据结构，算法，计网基础(非计科类专业自闭) 
3. 针对已有的项目深入提问(实现，拓展，创新)扫描器实现对比拓展(不晓得) 
4. 知识面深入，内网探测高危服务除了端口扫描还有啥？ 
5. 漏洞挖掘的挑战性的事件的优秀亮点 
6. 其他公司面试情况 
7. 渗透方向能力目标，学习的新方向。 
8. 反问，有点考核提问智慧的意思，让我各种方面问他问题 

## 三面

1. 问了项目的思路和思考方式
2. 挑战性的问题如何解决
3. 聊了未来城市选择和发展路线
4. 还有一些其他遇到某问题表现和思路是什么样的

和技术相关的问题占比很少



# 0x2C 腾讯

## 一面

作者：zhengtu

来源：[牛客网](https://www.nowcoder.com/discuss/494211)

1. 编写工具的具体思路，sql注入，xss  
2. csrf的防御，   referer验证，referer为空则防御(referer是浏览器特性，为空排除特性之外的问题则做防御验证)，  
3. xxe无回显探测   dns验证，内部实体探测  
4. xss硬编码如何利用   前端dom型被js代码转义出来，比如\u003c,前提是返回在了js中，在html中除非具备某种标签，其特性可导致特殊编码执行，则能转义出来  
5. java反序列化基础  
6. 白盒审计能力问题--这一点应该说可以自行拓展，对owasp10做过调试，对tp审计做过深入调试，对rmi反序列化做过调试，学习过一本书的样子 
7. 密码重置处的逻辑问题--第一二三步验证不统一，验证统一但后台返回的更改密码的token可被预测，枚举可猜解，返回敏感数据，后端与前端验证不一致，存在数据查询则可注入，xss编码问题

## 二面

问了各种问题，包括项目中如何解决问题，应急响应做过哪些处理，针对大量请求高并发的解决
有很多具体的场景，询问你的思路
聊了国家安全，各种安全视界的思考，见识



# 0x2D 奇安信 A-TEAM

作者：zhengtu

来源：[牛客网](https://www.nowcoder.com/discuss/494211)

​     我投的这个岗位是[奇安信]()A-TEAM的渗透[测试]()，这个团队方向是以红队为主。面试流程是我体验最快的一家，可能是由于已经快11月份了，所以采取了滚动批次面试的方式，一个下午就完成了面试流程。面试官问的东西技术难度比较广和深，而且都是基于实际的应用场景来问的。所以基本杜绝了做题和背题的方式，需要一定的实战经验和见识。    

​    

## 一面    

​     1、sql注入基于利用方式而言有哪些类型？    

​     2、sql注入写马有哪些方式？    

​     3、oracle注入除了注入[数据]()之外有哪些直接利用的方式？(这个真没见过，答不出来)，sqlserver获取shell的方法？    

​     4、xss的利用方式？    

​     5、同源策略的绕过方式？    

​     6、完整的渗透[测试]()流程思路？(从拿下webshell到后渗透的实战经历)    

​     7、如何绕过基于语义检测的waf，比如雷池，[阿里云]()waf等(不是太理解语义这东西，说了一些我知道的绕过场景)    

​     8、问了预编译场景下是否存在sql注入。(这一点老实说并不存在，但面试官提到第一次预编译的过程假如存在可控[数据]()，这确实是可能的，我说了自己的看法)    

​     9、编程问了个多线程和协程的区别。 
​    

## 二面    

​     1、问了项目的实现思路和方法。    

​     2、黄金票据和白银票据的区别？    

​     3、pth中LM hash和NTLM hash的区别(这个之前做过研究，不过只记得一点了)    

​     4、CDN的绕过方式？    

​     5、waf的绕过方式？    

​     6、其他忘了       

 

## 三面    

​     1、问了学校经历    

​     2、问我自己觉得是个内向还是外向的人？？？(事实上我觉得让自己来评判这个问题没有意义，我可以把自己塑造得很内向，也可以说得很外向，但性格是矛盾和多样化的，用这样非黑即白的问题去询问，反而不如直接问平时相关的经历和事项)    

​     我:我觉得性格这个东西是不应该一概而论的，我觉得我既不内向，也不外向。不如让我说说我的其他经历和思考。您这边来看看我是什么样的。是否适合这个岗位。剩下就balabala    

​     3、询问其他offer状况



# 0x2E 快手 安全工程师

作者：牛客271656551号

来源：[牛客网](https://www.nowcoder.com/discuss/1022507)

1. 自我介绍   
2.  介绍项目 
3.  Linux提权方式，脏牛提权原理 
4.  公司中了勒索病毒怎么办、分哪几步，勒索病毒原理，勒索病毒是怎么传播的 
5.  如何绕过waf 
6.  SQL注入的种类，怎么防御SQL注入，业务层面防止SQL注入的方法 
7.  哪些情况SQL预编译无效 
8.  怎么判断服务器是Windows还是Linux，能不能用ping命令判断 
9.  了解的安全论坛有哪些 
10.  平时有什么兴趣爱好 
11.  学习过程中遇到的最大的挑战或困难 
12. ​    反问



# 0x2F 快手 安全实习生

作者：ArrowQin

来源：[牛客网](https://www.nowcoder.com/discuss/651317)

面试岗位：【暑期实习】安全实习生-系统运营部

## 一面

1. 自我介绍
2. 问项目
3. 针对项目问了很多详细的问题，不便透露，通用问题如下：
4. 做项目的时候有没有遇到什么问题，怎么解决
5. 做项目学到了什么东西
6. 项目中有没有什么地方自己做过优化
7. 有没有对网站做过渗透测试
8. Linux操作熟悉吗，怎么看进程PID
9. 用过什么数据库，答：sqlite,mongodb,面试官好像不太了解没咋问
10. 为什么用mongodb
11. 了解ES吗(Elasticsearch)
12. HTTPS建立过程
13. python怎么管理内存
14. 深拷贝和浅拷贝区别
15. python多进程、多线程、协程有用到吗，都在什么地方用到
16. python可以实现真正的多线程吗
17. 代码题：ip排序（转成元组排序就行了，记得把str转成int，不然192会比50大）
18. 写Web API的时候怎么防止SQL注入
19. 怎么防XSS
20. 了解越权漏洞么，有没有挖过越权漏洞
21. 有没有什么比较擅长的我还没问到的

## 二面

1. 问项目
2. 项目哪一块时间花的比较多
3. 怎么溯源攻击
4. 举一个溯源攻击的例子
5. 怎么检测webshell
6. sql注入在mysql和sqlserver中有什么区别
7. 想找安全开发的岗位还是安全研究的岗位
8. 代码题：手机九宫格键盘，输入数字，输出所有的字母组合
9. 如输入23，输出['ad','ae','af','bd','be','bf','cd','ce','cf']
10. (我就模拟做)
11. 讲一下DNS协议的作用、解析过程
12. DNS协议的安全问题
13. 实习时间



# 0x30 快手 安全工程师

作者：Qber

来源：[牛客网](https://www.nowcoder.com/discuss/750247)

技术类： 

 1，自我介绍 

 2，根据简历逐步问技术，问工具的具体使用 

 3，SQL注入漏洞，类型，可以造成什么危害 

​		MSSQL与Oracle   

​		SQL注入写入Shell的具体命令 

 4，XSS，存储型怎么利用，有哪些危害，除了钓鱼 

​        带外COKIES的时候，遇到WAF怎们 

 5，AWVS登录扫描怎么操作，SQLMAP怎么用，有那几个级别，分别有什么区别，参数 

 SQLMAP如何扫[数据]()包，本地读文件，指定参数，这些的具体命令 

 6，如何绕过WAF 

 7，如何入侵[快手]() 

 视频上传点、社工，钓鱼邮件 

 供应链攻击 

 8，钓鱼邮件你会用那些恶意木马、shellcode 

 9、NMAP如何静PING扫描，如何看端口开放，如何看系统版本信息，具体的命令是什么 

 编程题：比较version号不同，写了大概思路，但是细节没处理好，直接给面试官说放弃了，面试官问了思想，然后又问特殊情况，想了一下，实在想不错 

 经历类： 

 1，你挖到的比较有意思的漏洞 

 2，你最近学习的东西，比较有意思的 

 反问： 

 1，甲方安全与乙方安全有啥不同， 

 2，感觉自己答得磕磕绊绊的，希望面试官能给一些后续的学习建议 

 总结： 

  面试体验非常好，中间说了好多不会，面试官也没有非常生气，还是完整的走完流程，最后给了很好的学习建议。 

  对于工具的使用问题问的很细致，但是最近都在手工渗透，复测，自然没有经常用工具，哎，反正感觉每场面试问的都很不一样。



# 0x31 快手 安全工程师

作者：HsiAo.

来源：[牛客网](https://www.nowcoder.com/discuss/1030186)

老早之前投的快手，26号通知面试，27号11点面试，面了40分钟。 

  面试官很好，是我自己菜，还有我代码能力真的不行，尤其是用python（不自量力，python还没怎么[刷题]()呢） 

  1、自我介绍 

  2、介绍下项目 

  3、介绍实习 

  4、信息收集 

  5、给你一个网站，你会怎么去挖掘漏洞 

  6、sql注入修复意见 

  7、XSS修复意见 

  8、弱口令修复意见 

  9、数据库操作 

  10、手撕代码，我代码真不行，题目：给你几个版本号如：1.3.2，2.1.4，1.0，让你判断版本号大小 

  11、操作系统查看最近登陆的用户 

  12、查看文件的最后300行 

  13、文件的权限777之类的 

  14、osi7层 

  15、tcp3次握手 

  16、反问

# 0x32 蚂蚁 安全工程师 实习

作者：求求了让我来个offer

来源：[牛客网](https://www.nowcoder.com/discuss/921755)

 面试时间线

 3.7初面也就是简历面，3.9一面，3.18二面，3.22hr面

## 简历面

 3.7初面 25min

1.  自我介绍一下
2.  hw的项目做了什么负责什么角色
3.  重保的项目做了什么负责什么角色
4.  应急响应做过吗
5.  内网渗透有了解吗然后问了关于内网渗透的东西
6.  ctf有打过吗
7.  逆向二进制有做过吗
8.  反序列化php和java
9.  你有什么想问我的吗

 因为初面是简历评估的问题也不是很难就问了些项目延展了一点点就过去了

## 一面

 3.9 一面 32min

1.  自我介绍
2.  hw项目
3.  重保项目
4.  src项目
5.  src中你印象最深刻的一个漏洞
6.  src中你碰到的困难以及如何克服的
7.  log4j2
8.  jndi注入
9.  逆向二进制有了解吗
10.  大学中学的最好的课
11.  我们地点是在xx地有问题吗
12.  有没有考研的想法
13.  你有什么想问我的吗
     

 一面属于在初面的基础上对项目更加深层次的挖了一下

## 二面

 二面 3.18 25min

1.  自我介绍一下
2.  自我介绍完面试官说前面两次面试已经基本差不多技术方面的东西都问完了，我来问你点别的
3.  然后问我对我这些src中挖到的漏洞的思考以及克服的困难和印象最深刻的漏洞
4.  如果是我蚂蚁的业务支付宝你会怎么样去测试
5.  有考研的打算吗
6.  base地没问题吗
7.  什么时候能来
8.  你有什么想问我的吗

 这二面的感觉就是更加注重你的发散思维以及对他业务的逻辑思考，因为我属于是src出身，所以这次面试正好对在我的口上了，所以对他业务的东西思考我就说了很多

## hr面

 3.22

 hr面

 hr面就是根据简历问你一些性格方面的东西

 你项目中克服的困难

 什么时候能来实习

 意愿的地点是哪

 为什么北方人不选择北京

# 0x33 蚂蚁 安全工程师 实习

作者：verf1sh

来源：[牛客网](https://www.nowcoder.com/discuss/944438)



## 一面

时间：2022/03/07

1. 对什么方向比较兴趣，漏洞挖掘还是利用
2. 有没有写过实际的利用exp（写过路由器的）
3. 路由器那个exp能达到什么效果，能rce吗
4. 这些知识是你课程上学习的还是自己打ctf学的
5. 有没有用fuzz挖到过漏洞
6. 读过英文的技术文献吗，有没有看一些英文的论文
7. 有没有写过论文
8. 愿意做偏研究的工作吗
9. 数据库fuzz你有哪些改进思路
10. 数据库的漏洞利用除了dos还能达到什么程度
11. 你用的fuzz是python写的还是c写的
12. c开发能力怎么样
13. 用的win本还是mac本
14. 做过安卓的利用吗
15. 有什么想问我的

## 二面

时间：2022/03/07

1. 做一下自我介绍，把实习和项目都介绍一下
2. 介绍一下rhg可以做到什么程度，能进行哪些漏洞利用，能绕过哪些保护措施
3. rhg参加的是什么比赛，是bctf吗
4. bctf参加过吗，有哪些有意思的题
5. 对比一下qemu模式fuzz和源码模式fuzz
6. 说说qemu模式的动态插桩怎么实现的，有什么优缺点
7. 把你的实习展开说一下
8. fuzz普通程序和数据库有哪些不同点
9. 论文里是怎么去解决数据库fuzz中的一些难点
10. 你觉得作者的思路哪些是好的，哪些存在问题
11. 你做的一些改动提升了什么，有比较好的效果吗，有没有挖出漏洞
12. 看你的博客有用过afl++去挖漏洞，说说afl++和afl有哪些不同
13. 你觉得afl++有哪些策略对你来说很有用
14. 说说afl有哪些模块，每个模块的流程
15. afl-fuzz为什么速度很快
16. C++程序怎么去逆向找虚表

## 三面

时间：2022/04/08

1. 自我介绍
2. 介绍在深信服的工作
3. 数据库fuzz和普通程序fuzz有什么不同
4. 怎么给AFL做适配去fuzz数据库
5. 介绍一下fuzz的流程，从选取目标开始
6. 讲一下AFL的插桩原理
7. 怎么选择fuzz测试点，感觉类似于fuzz单个API函数吧
8. Linux内核你了解哪部分，内存、网络、设备？
9. 如果让你做内核的安全研究，你想从哪一块入手，为什么
10. 有计划过怎么去夯实自己的基础吗
11. 有没有工作上的规划，毕业后做哪方面研究
12. 期望base哪里
13. 什么时候可以来实习，实验室老师会限制实习时间吗
14. 研三的时候可以实习吗

## HR面

时间：2022/04/20

1. 介绍一下本科和研究生的学习情况，为什么研究生选择换方向
2. 印象深刻的比赛，负责哪方面工作，遇到过什么难点，你认为在队友会用哪些形容词形容你
3. 了解部门工作内容吗，是你最想做的方向吗，希望base哪里

4.28 意向



> 从0x34至0x40均来自于 **[Theoyu](https://github.com/yuuuuu422)** 师傅的分享

# 0x34 商汤科技 安全开发工程师

## 一面

20分钟+做题

1. 问实习，问项目
2. 基础问题：
   如何查看自己服务器某个端口情况 ：netstat lsof
   如何查看远程服务器情况：telnet、nc、三次握手查看
3. 两道题 
   一个字符串全排列
   一个第一个不重复子串

说了一下安全开发是基本上全开发，推去了安全攻防



## 二面

安全攻防
时长：55分钟

1. 自我介绍
2. 面试官介绍部门下面三个工作分组：
   1. 入侵检测 
   2. 安全体系建设（SDL）
   3. 红蓝对抗
3. 反弹shell 如何检测？
4. 如果攻击者使用了AWK、如何检测?
5. 除了进程树的命令匹配，还有可以检测反弹shell的方法吗？
6. 你了解哪一些提权手段？
7. 细说一下什么是SUID提权
8. 分别说说这几类提权的检测方法
9. 如果让你设计一款入侵检测系统，你会往哪几方面考虑（发散思维）（文件、网络连接、进程）
10. 进程隐藏技术是什么，如何检测？
11. log4j的原理
12. 如果一个环境下存在有漏洞版本的log4j，如何在不升级的情况下做预防？
13. 聊聊IAST
14. 如果多进程下，A进程的Source 触发到了 B进程的sink点，如何溯源？
15. 职业规划
16. 反问



# 0x35 海康威视 网络安全工程师

## 一面

时长：45分钟

1. 自我介绍
2. 你认为海康威视哪些地方存在安全风险
3. iot漏洞挖掘有了解吗
4. 云上攻防了解多少
5. 数据上云有哪些风险
6. ssrf和csrf
7. openrasp看过源码吗
8. jndi如何做hook
9. 高版本jndi如何绕过

```
算法：给一棵树，输出树每一层第一个和最后一个不为空节点中间的个数（中间可以为空）
    10
   /   \
  8     18
 / \      \
5   9       20     -----第三层节点数为4

    10
   /   \
  8     18
 / \    /
5   9  16         -----第三层节点数为3

很离谱，只有题目，没有输入输入样例也没有模版，只给10分钟，我说如果树是以数组的形式输入，可以得到树每层第一个和最后一个的边界，双指针遍历再坐标相减即可，面试官好像没认真听，草草结束了。
```



# 0x36 度小满 信息安全工程师

## 一面

时长：40分钟

1. sql注入原理，waf如何检测
2. ssrf csrf区别
3. 邮件协议了解多少
4. smtp如何伪造？ （搭建匿名邮件服务器、如果目标域名没有设置SPF Sender Policy Framework,就可以伪造）
5. 入侵检测全流程
6. 提权怎么检测
7. 提权 什么情况会出现误报？
8. 容器内提权，怎么检测？ 
9. 内网被搭了隧道，怎么检测？
10. 流量加密了 怎么检测？

## 二面

时长：30分钟

1. 框架类漏洞挖掘思路、业务逻辑漏洞挖掘思路
2. 反序列化漏洞如何检测
3. AES分类，默认密钥长度
4. AES加密流程
5. shiro爆破key，构建的初始序列化数据是什么？



# 0x37 长亭 安全开发工程师

## 一面

时长：40分钟 

会问一些计算机基础的八股，但都是结合具体案例说的，体验不错

1. nmap支持哪几种扫描方式，分别对应tcp三次握手的哪个流程
2. 进程 线程 协程，分别用具体的场景说明一下
3. 浏览器开启多个窗口，属于多进程还是多线程？一个窗口内的多标签呢？为什么这样设计？
4. 知道go的协程内部是如何实现的吗？
5. shiro反序列化说一下
6. 如何探测是否存在某个类（jar包）(反序列化炸弹)
7. 如果让你开发，如何设计前后端的权限校验
8. 聊项目，聊了很久的XRAY
9. 看过cs源码吗？对武器研发有没有什么想法？
10. 会rust吗？
11. 聊规划
12. 反问，问了一个项目上的问题，面试官从技术上帮我讲解了（第一次反问技术问题..）



# 0x38 小米 安全工程师

## 一面 

时长：45分钟

1. sql注入怎么预防、预编译为什么能防？
2. php和java侧预编译有什么区别
3. SSRF php 和 java 分别有什么利用方式
4. 说一下php和java侧反序列化的异同、利用
5. SCA是什么，具体该怎么实现，灰盒怎么做、白盒怎么做（灰盒可以依赖agent分析，白盒结合maven插件会比单纯分析xml好一些）
6. log4j有哪些防御方法
7. 从agent到字节码hook的整个流程（伪代码）
8. 谈一下codeql，能不能用来做CI/CD
9. codeql哪些地方会断，该怎么处理
10. 白盒理论了解多少，相比于灰盒
11. 说一下SAST、DAST、IAST的优缺点
12. 了解 devsecops 吗
13. 未来想从事什么方向

## 二面 

时长：45分钟

1. 说项目
2. 说实习 x2
3. 终端命令的进程信息具体该如何采集
4. runtime.exec 后面的部分注入能不能执行
5. 漏洞挖掘和SDL 对哪部分感兴趣



# 0x39 携程旅游 基础安全工程师

## 一面

时长：80分钟

1. 自我介绍
2. 反序列化流程
3. 如何挖掘的0day
4. sql注入本质
5. sql注入怎么写马
6. outfile和dumpfile的区别（前者支持多行以及自定义编码）
7. 宽字符截断的原理，说一个具体例子
8. SSRF利用和防御
9. SSRF无回显怎么利用
10. 如果有一个接口可能有SSRF说你说你的流程
11. shiro说一下
12. shiro利用如果失败，可能是哪一环出了问题？（控制变量，逐一摸索）
13. 文件上传如何防御
14. 说项目，漏扫怎么做？
15. 了解sqlmap是怎么实现的吗？或者常规xss如何扫描？
16. 聊实习，反弹shell如何检测？
17. 反弹shell的本质是什么？
18. 作为一个agent，需要采集哪一些信息，如何构建进程树？
19. 提权如何检测？
20. 说一下其他主机侧的安全重点。
21. 云原生，容器安全了解多少
22. docker逃逸说一下
23. 云服务了解吗，打云上攻防吗？
24. 内网渗透了解多少、AD域了解多少
25. 隧道的本质是什么
26. 反问



## 二面&三面

（二面面完根据我想做的方向帮我转了一下岗，两面差别不大，放在一起）
时长：50分钟

1. 实习2做了什么
2. 如果在甲方做代码审计，你认为和在红队漏洞挖掘有什么不一样？
3. 如何权衡各种漏洞扫描或者入侵检测到漏报和误报
4. 实习具体做了什么，有什么收获
5. IAST 主动和被动的区别
6. IAST应该放在CI/CD的哪一环，了解过代理式吗？
7. 实习过程中有什么困难
8. 希望做自己擅长的领域，还是乐意探索新的方向？



# 0x40 欧科云链 安全开发

## 一面 

时长：一个多小时

面试官思路非常清晰，做完自我介绍后就和我说面试会涉及攻防以及开发三个角度，每个环节循序渐进。

攻：攻从前中后三个阶段展开

前：

1. sql注入如何判断数据库类型（根据利用的难易程度展开）
2. xss除了打cookie还有什么其他的思路
3. 代码审计的流程
4. filter的作用域
5. 哪些业务场景可能会出现反序列化漏洞
6. 除了readobject，还有哪些反序列化触发点
7. 如果一个反序列化打失败了，可能存在哪些原因？
8. 如何挖掘一条新的反序列化链
9. AST是什么
10. 代码如何生成AST？
11. 有没有不经过IR阶段（比如借助LLVM），直接生成AST的方法，和前者相比又有什么缺陷？

聊的有些偏了，回到攻击。

中：

1. 抛开exp，如何提权 （说了suid和mysql提权）
2. suid提权的生命周期（结合euid）
3. windows 烂土豆了解吗
4. 免杀知道多少，webshell免杀，静态、动态免杀

后：

1. 隧道相关
2. CS源码看过吗
3. 内网相关，我直接说不太了解

防：

1. HIDS的流程是什么
2. IAST和RASP的区别
3. 两者在埋点深浅上有什么处理（同样一类漏洞，会怎么做埋点处理）
4. 埋点埋的深和埋的浅对检出率有什么影响？（一下子没转过弯来，说让我想一想）
5. log4j做埋点，直接在log4j的Class里做hook，和直接hook jndi的initial和lookup 有什么区别（算是对上面那个问题的提示）
6. 了解百度的iast是怎么做的，主动式和被动式的的区别
7. 这两者会产生脏数据吗？

开发：

1. 聊项目
2. 符号执行了解吗
3. 符号执行是如何做约束求解的
4. 哪些漏洞可以用fuzz检测到
5. 纯白盒了解多少？说几个市面上开源或者闭源的白合工具，知道是基于什么实现的吗
6. 反问

## 二面 

时长：30分钟

1. 英语水平（ ok很看重英语，包括听说读写）
2. 聊项目
3. 介绍了很长一段的培养方案（很吸引人）
4. 聊理想、职业规划
