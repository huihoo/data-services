# 数据模型

### 简介
数据模型是应用和服务的核心，数据模型的设计、数据存储方式将决定最后的应用和商业模式。

数据模型（建模）的通用模式，可以被应用到成百上千的行业、数以万计的项目，和无数可高度复用的模块和应用中。

### 数据模型
基于一套功能强大的通用数据模型资源库，这将会把基于数据库的开发项目带到一个高起点。这些针对通用业务功能的模型都是经过项目实践验证的，会使用数据库开发人员节省非常非常多的时间和成本。它们覆盖制造业、电信业、保险业、医疗保健业、金融服务业、专业服务业、旅游业和电子商务等领域。

### 模型参考
#### Apache OFBiz
* 人与组织
* 产品模型 
* 产品订购模型
* 装运模型
* 工作计划模型
* 发票模型
* 会计和预算模型
* 人力资源模型
* 数据仓库数据模型
* 制造业模型
* 电信业模型
* 医疗保健模型
* 保险业模型
* 金融服务业模型
* 专业服务业模型
* 旅行业模型
* 电子商务模型

[Apache OFBiz 数据模型](http://docs.huihoo.com/apache/ofbiz/data-model/)

#### Apache Usergird
Usergrid提供了一组核心应用程序对象，主要实现了对用户的管理以及对交互性的增强、通过自由的数据存储系统存储数据、检索以及返回任何类型的内容和对象集合等。Usergrid也提供了对日志数据的支持，这使得实时事件分析和关键指标的跟踪成为可能。

应用对象(Data Entity Types)包括：

* 用户(user)
* 用户组(group)
* 角色(role)
* 应用(application)
* 行为(activity)
* 设备(device)
* 资源(asset)
* 目录(folder)
* 事件(event)
* 通知(notifier)
* 通告(notification)
* 收到(receipt)

每个对象都被保存在其各自的集合中(/users，/groups……)。Usergrid也允许创建用户想要的任何类型的动态(自定义的)实体。动态实体会被自动保存在以实体类型复数为名称的集合中。

所提及的消息(message)概念是以notifier、notification、receipt数据实体类型体现。

[Usergrid 默认实体数据模型](https://usergrid.apache.org/docs/rest-endpoints/api-docs.html#models)

#### odoo
Odoo模型描述业务对象，比如一次机会，一个销售订单，或者业务伙伴（消费者，供应商等等），模型拥有一个属性列表（可理解为表字段），模型是使用派生自Odoo模板类的Python类来实现的。这些模型被直接地翻译为数据库对象，当安装或者升级模块时Odoo也会自动地处理它们。将模型文件放到一个models子目录内可以看作是最佳实践。
* [odoo ORM API](http://www.odoo.com/documentation/11.0/reference/orm.html)
* [odoo Data Files](http://www.odoo.com/documentation/11.0/reference/data.html)
* [odoo v8 Data Model](http://useopenerp.com/)

### 书籍
* 《数据模型资源手册（卷1）》
* 《数据模型资源手册（卷2）》
* [《数据模型资源手册（卷3）——数据模型通用模式》](https://www.amazon.cn/%E6%95%B0%E6%8D%AE%E6%A8%A1%E5%9E%8B%E8%B5%84%E6%BA%90%E6%89%8B%E5%86%8C-%E6%95%B0%E6%8D%AE%E6%A8%A1%E5%9E%8B%E9%80%9A%E7%94%A8%E6%A8%A1%E5%BC%8F-Len-Silverston/dp/B01N5Y4H0F/)

### 图集
![odoo数据模型](https://wiki.huihoo.com/images/5/51/Odoo-data-model.png) odoo数据模型

![odoo视图](https://wiki.huihoo.com/images/0/09/Odoo-data-model-view.png) odoo视图

![odoo视图细节](https://wiki.huihoo.com/images/c/c8/Odoo-data-model-view-detail.png) odoo视图细节

![usergrid数据模式](https://wiki.huihoo.com/images/0/00/Apache-usergrid-cassandra.png) usergrid数据模式

![比特币交易数据](https://wiki.huihoo.com/images/c/ca/Gekko-mongodb.png) 比特币交易数据