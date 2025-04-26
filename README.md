# my_restapi

## REST API 介绍
REST这套开发现代化互联网应用程序的解决方案最早由罗伊.托马斯.菲尔丁在2000年发表的博士论文中提出，设计目标是在应用程序的业务逻辑上实现前后端分离，并在它们之间建立相互传递信息的行为规范，从而为应用程序的分布式部署创造基础。在编程方法论中，我们常将遵守或兼容了这套软件设计规范的架构成为RESTFUL架构。Representational State Transfer（表现层状态转移）

资源的表现层指的就是它在某个具体环境中的表现形式。具体到HTTP中，资源的表现层应该就是我们用来定位资源的统一资源标志符（URI）
提出的方案本质上是一套程序员在编写软件是需要遵守的设计规范，它本身并没有任何新的网络协议和数据格式，建立在HTTP、 URI、 XML、 JSON等一系列现有的网络协议数据格式之上。

## json server服务器搭建
利用 node.js提供的json-server模块可以帮助我们快速的建立一个网站数据原型，从而帮助我们在此基础上构建后端数据的SQL、graphql查询，及视图bootstrap、Tailwind、的选用。当前在线的[json-server](https://jsonplaceholder.typicode.com/)可以帮助我们快速的获得第一手反馈数据。
### 方法
1. 在github建立仓库
2. 建立一个db.json文件。
3. 访问[https://my-json-server.typicode.com/teddyand/myrestapi](https://my-json-server.typicode.com/teddyand/myrestapi)

### 示例
本api访问[https://my-json-server.typicode.com/teddyand/myrestapi/clients](https://my-json-server.typicode.com/teddyand/myrestapi/clients)