@import "resume.less"
<head>
    <title>个人简历</title>
    <link href="https://fonts.googleapis.com/css?family=Noto+Sans+SC|Source+Code+Pro:500&display=swap&subset=chinese-simplified" rel="stylesheet">
    <link href="https://cdn.bootcss.com/font-awesome/5.8.2/css/all.min.css" rel="stylesheet" >
</head>

## 李文博 <span class="titleEng">/Wenbo Li</span>
## Java开发工程师 <span class="titleEng">/Java Software Engineer</span>

<i class="fas fa-envelope"></i> E-mail: liwenbo9501@outlook.com

<i class="fas fa-phone"></i> Phone: 17376595680

<i class="fab fa-weixin"></i> Wechat/QQ: 114437826
### <i class="fas fa-tag"></i> 关于我
李文博/男/1995

本科/忻州师范大学计算机系/网络工程 2013.9 - 2017.6

工作年限: 2年

个人博客: <https://wilbur.club>

### <i class="fas fa-list"></i> 工作经历
#### 杭州玄籍网络科技有限公司 2017.10 - 2019.3
* ##### AD NETWORK网盟平台（内部使用和SaaS平台，长期维护）
    * ###### SpringMVC + Spring + ibatis + Dubbo + Zookeeper + Redis + RabbitMQ等
    * ###### 项目描述:
        Mobgeek API是基于移动互联网的效果广告平台，为广告主吸引高效率的目标用户群，为媒体带来最大化的流量变现，对接全球最有竞争力的Offer和海量的媒体资源。实现广告与流量的最优质的匹配。
    * ###### 主要职责:
        1. 负责了offer的跳转测试及统计，渠道的注册与审核，点击的稀释，结算单，核减的优化与改进，offer榜单和推荐，运营KPI等管理后台和渠道端后台模块的前后端开发与维护；
        2. 原始数据量较大，日均百万级，配合技术主管完成分库分表，对数据的查询展示等使用Redis作为缓存技术进行改造，极大提升访问速度。
        3. 负责一些公共组件的设计、开发和迭代，如自定义注解实现全局日志统计，使用ForkJoinPool实现并发请求工具，一些Dubbo公共API的开发等。
* ##### MAXMOBI SSP平台
    * ###### SpringBoot + Mybatis + Redis + Docker + Spring Security等

    * ###### 项目描述:
        MAXMOBI是领先的以数据驱动的移动广告流量变现平台，有SDK，js等形式，以大数据为驱动，把最合适的广告投给最匹配的人群。
    * ###### 主要职责:
        1. 主要负责了管理后台以及媒体商平台的搭建与功能开发及维护，如媒体商，广告位，应用管理，SDK与文档管理，媒体商注册登录，Spring Security权限管理，展示、点击等的回调记录等。
        2. 负责了多家媒体伙伴的API对接，如创变，优客来，百度/小熊博望等。
        3. 配合技术经理开发公共组件如通过自定义注解实现多数据源的切换，zookeeper实现分布式锁等。

#### 浪潮通信信息系统有限公司 2016.10 - 2017.9
* ##### 运营商生活商城
    * ###### SpringMVC + Spring + MyBatis + Redis + Solr + Dubbo等
    * ###### 项目描述:
        本项目采用分布式架构按照功能拆分成多个子模块：包括前台模块、CMS模块、SSO模块、会员模块、订单模块、搜索模块、活动模块等。子模块之间通信通过发布服务，使用Dubbo远程调用方式实现。使用redis集群做缓存提高系统的性能，并使用redis实现session共享。搜索模块使用solrCloud做搜索引擎。
    * ###### 主要职责:
        1. 负责CMS模块的需求分析和项目构建，开发和维护图片FTP上传，内容管理等模块；
        2. redis集群的搭建，通过Jedis进行用户注册登录模块的开发与测试；
        3. 负责购物车模块的开发及测试，通过redis缓存和cookie读写提升性能；
        4. SolrCloud的搭建和配置，参与搜索系统模块的开发和测试；
* ##### 运营商家客业务管理平台
    * ###### ExtJS + Struts2 + Spring + Hibernate + Oracle + osworkflow等
    * ###### 项目描述:
        本项目是一个工单流程管理系统。如宽带、魔百和等业务的开通包含多个环节，本系统负责对各项流程如施工预约、现场开通，设备激活等进行把控，调用第三方短信接口通知装维人员和用户当前进度等。为手机App提供各种服务调用，如图片上传服务，Web Service服务等。
    * ###### 主要职责:
        1. 负责了分光器零星扩容模块前后台的开发与测试；部分需求的改造和优化等。
        2. 负责了资源查询、质检结果上传、图片上传接口的开发与测试；
        3. 通过WSDL生成Web Service客户端，解析xml报文等；
        4. 开发了资源数据上传的接口，通过JWS实现基于SOAP的Web Service服务端。
### <i class="fas fa-code"></i> 技术清单
<i class="fas fa-coffee"></i> **Java** 熟悉Java基础，有J.U.C多线程使用经验，了解JVM，JMM，GC基础
<i class="fas fa-leaf"></i> **框架** SpringMVC，Spring，MyBatis，SpringBoot等；
<i class="fas fa-database"></i> **数据库** MySQL，Redis，Oracle，MongoDB，Memcached等；
<i class="fas fa-server"></i> **服务器** Linux，Tomcat，Nginx，Zookeeper，Docker等；
<i class="fas fa-laptop-code"></i> **前端** HTML，CSS，JS，jQuery，EasyUI，Bootstrap，Ajax，Jsonp等；
<i class="fas fa-wrench"></i> **开发工具** Eclipse，IntelliJ IDEA，Maven，Git，SVN等；
<i class="fas fa-code-branch"></i> **其他** Solr，Quartz，RabbitMQ，SOAP等。