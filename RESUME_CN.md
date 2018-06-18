### 基本信息

* 宋晨川
* 出生年月：1988-12
* 毕业院校：东南大学 软件学院 全日制本科
* 邮箱：robscc269@gmail.com
* 电话：18602188765
* Github [robscc](https://github.com/robscc)

### 技能

- Golang 熟练
- PHP 熟悉
- Python 熟悉
- SQL 熟练
- Javascript 熟悉
- Lua 熟悉
- Docker 熟悉

### 工作经历

- 1. 上海渡维科技有限公司 软件工程师 2009.07 ~ 2013.12 开发体感游戏(C++)，电视机游戏平台（后端PHP-自研MVC框架，前端jQuery-做了动画帧率优化)
- 2. 交通银行福建省分行 IT运维 2013.12 ~ 2015.06 主要参与省行内部系统开发，数据提取，以及借调总行开发。
- 3. 同步网络有限公司 高级软件工程师，AirDroid服务端Leader 2015.06~2016.12
- 4. Ubiquiti Networks 高级软件工程师，FrontRow/UUM服务端Leader 2017.01 ~ 今

### 项目经历

#### UUM （2018.01 ~ 今)

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

#### 一元进宝 （2015.10~2016.04）

参照网易一元夺宝服务端Golang实现

1. 设计数据库，设计服务器架构。
2. 实现随机数池服务，支持横向扩展，使用队列来处理并发抢票的模式。
3. 实现中心化开奖计时服务。
4. 实现API服务。
5. 实现灵活的可以定制规则，支持事件监听的运营中心服务，使用js脚本定制活动逻辑。

### 个人评价

学习能力强，在技术选型上经验丰富，有带人经验。3年Golang线上实践，会多种工具语言。英文读写流畅。