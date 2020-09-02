### 基本信息

* 宋晨川
* 出生年月：1988-12
* 毕业院校：东南大学 软件学院 全日制本科
* 邮箱：robscc269@gmail.com
* 电话：18602188765
* Github [robscc](https://github.com/robscc)

### 技能

- Golang 熟练
- Python 熟悉
- SQL 熟练
- Docker 熟悉

### 工作经历

- 1. 上海渡维科技有限公司 软件工程师 2009.07 ~ 2013.12 开发体感游戏(C++)，电视机游戏平台（后端PHP-自研MVC框架，前端jQuery-做了动画帧率优化)
- 2. 交通银行福建省分行 IT运维 2013.12 ~ 2015.06 主要参与省行内部系统开发，数据提取，以及借调总行开发。
- 3. 同步网络有限公司 高级软件工程师，AirDroid服务端Leader 2015.06~2016.12
- 4. Ubiquiti Networks 高级软件工程师，FrontRow/UUM服务端Leader 2017.01 ~ 2018.07
- 5. 顺丰科技有限公司 高级后端工程师 2018.07 ~ 今

### 项目经历

#### AI 自动化

>打通公司大数据平台以及AI的协作处理
>基于k8s 探索AI 训练以及预测的自动化
>编写K8S组件实现模型自动化Serving
>固化AI上线流程，提升算法工程师效率

#### 订单理赔预警

>项目管理
>下单的时候做订单理赔概率预测，形成预警下发小哥巴枪端
>使用Spark + XGBoost/GBT

1. 优化系统，降低资源使用率40%，提高batch处理效率100%
2. 优化模块结构，保证重要规则模块
3. 实现模型自动化训练以及部署
4. 实现模型线上切换
5. 实现Spark模型应用的关键指标监控

#### 智能包裹监控平台

>项目管理
>项目基于AIoT设备，收集物流过程中的温度，湿度，光照，震动等参数,实现实时监控。
>实现物流货物跟踪
>架构设计，代码框架搭建，通过MQTT协议接入设备数据

1. 设计服务器架构
2. 使用k8s Job 管理数据处理的异步任务
3. 实现边缘计算，OTT升级，以及配置下发
4. 提供算法模块实现监控能力提升

#### UUM （2018.01 ~ 2018.07）

>Uniquiti硬件设备统一管理系统；
>将Ubiquiti设备在云端统一管理以及调配；
>实现公司或者组织的人员以及权限管理；
>离线状态下，边缘计算Agent可以充当智能设备的中心节点。

1. 设计数据库，设计服务器架构.
2. 设计基础API服务
3. 为UUM设计边缘计算架构，并实现边缘计算Agent。

#### FrontRow (2017.01 ~ 今)

> 便携摄像机，服务端主要的实现的为API以及远程控制通道,
> 远程设备http服务访问通道, 异步转码服务。

[中区网站](https://www.frontrow.com.cn)

https://www.frontrow.com.cn

[外区网站（需使用国外ip访问，否则自动CDN至中区)](https://www.frontrow.com)

https://www.frontrow.com
https://cloud.frontrow.com

[VLOGNOW App](https://www.vlognow.me)

https://www.vlognow.me

1. 设计数据库，设计服务器架构，抽象公共库。
2. 设计灰度发布服务（app分发），实现成服务让客户端发布测试使用，并且可以作为客户端的配置分发系统k，使用lua控制分发的逻辑。
3. 设计并实现服务端API服务（Gin框架）。
4. 设计并实现可扩展的WebRTC信令服务器,实现多实例通信，适配AWS ALB。
5. 修改[FRP](https://github.com/fatedier/frp)适应项目需求，并提供Android客户端可用的JNI包。
6. 将所有服务容器化。
7. 利用WebRTC DataChannel，实现FrontRow设备自动化测试，并将测试结果入库分析。
8. 实现Gin框架的文档生成器，加速项目开发进度。
9. 实现Slack Bot,将用户Feedback信息以及客户端发布信息及时反馈在团队聊天Channel中。

#### AirDroid (2015.06 ~ 2016.12)

> AirDroid是在电脑可以接收设备的通知、回复短信,电脑与设备高效互传文件,
> AirMirror更能实现电脑完全控制安卓设备。

[AirDroid](https://www.airdroid.com)

https://www.airdroid.com

1. 主导重构主要API服务(Golang使用Revel框架，PHP使用ThinKPHP框架），流量计费服务。
2. 优化主要服务，修复旧项目的性能问题，SQL优化，流程优化，代码Review,将主服务的性能提高2倍，降低主机配置参数降低为原配置的1/4。
3. 提高后台服务的的扩展性，引入consul+etcd做中心化配置。
4. 抽取旧有代码公共部分，提取公共库，提高代码复用性。
5. 将各个模块api的权限校验部分逻辑回收至单独的模块，使用openresty实现。
6. 解决AirDroid 3.0 版本的安全问题，提出强制更新客户端方案，以及旧版本API的替换方案。
