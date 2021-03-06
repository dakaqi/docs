### 分区管理

拿京狮会举例：用于管理下属的专区\(region\)和分区\(zone\)。专区和分区的概念举例说明：

![](/assets/region2.png)



在业务模型上，region和zone是同一个概念。一个账号下，可开设下级分区，分区下又可设定下一级分区，也可直接开设分区。分区下是服务队。

#### 开设分区

输入内容：

| 分区名称 | 无备注 |
| :--- | :--- |
| 分区简称 | 无备注 |
| 分区logo | 无备注 |
| 登录手机 | 手机和会员号二选一 |
| 登录会员号 | 手机和会员号二选一 |
| 登录密码 | 登录后需重新设定。 |
| 行政级别 | 值：全国、省市、地市、区县、街道、社区、行业 |
| 类别 | 值：专区、分区等。根据系统设置中分区类别获取。 |
| 所属行业类别（京狮会设定默认值为：） | 值：党政机关、事业单位（不含公立学校）、公立学校、国有经济控制企业、集体经济控制企业、非公有经济控制企业、新社会组织（不含民办学校）、民办学校、军队武警、城市社区（居委会）、建制村（农村社区）、其他 |
| 代码类型 | 值：所属机构法人组织代码、社会信用代码 |
| 代码号 | 无备注 |
| 邮政地址 | 由于邮寄相关业务 |
| 管辖区域 | 选择：省、市、区，填写镇街、社区 |
| 邮政编码 | 无备注 |
| 权限设定 | 多选，根据权限列表设定 |

#### 权限列表

选择一级类目即表示勾选该类目下所有二级类目。勾选某一个二级类目，就自动勾选对应的一级类目。

| 一级类目 | 二级类目 |
| :--- | :--- |
| 组织机构管理 | 机构管理 |
|  | 会员管理 |
|  | 年度管理 |
|  | 职务管理 |
| 分区管理 | 开设分区 |
|  | 查询分区 |
|  | 修改分区 |
|  | 取消分区 |
| 服务队管理 | 创建服务队 |
|  | 查询服务队 |
|  | 管理服务队 |
| 目标管理 | 查询目标 |
| 统计报表 | 需要再细化 |
| 资讯管理 | 发布资讯 |
|  | 浏览资讯 |
|  | 管理资讯 |
| 系统设置 | 账号管理 |
|  | 名词定义 |

说明：组织结构中的年度管理、系统设置中的名词定义仅最顶层账号也就是D385能使用。

#### 查询分区\(不完整，需补充\)

查询下设的所有分区信息。某一专区下，可创建分区。

显示内容，还需添加：

| 分区名称 | 无备注 |
| :--- | :--- |
| 专区描述 | 无备注 |

#### 修改专区信息\(不完整，需补充\)

修改专区的名称以及描述信息。

可修改内容，与创建一样：

| 专区名称 | 无备注 |
| :--- | :--- |
| 专区描述 | 无备注 |

#### 取消专区

取消某一个特定专区。取消需进行手机授权，确保非误操作造成的专区取消。取消前提：该专区无下属服务队。

