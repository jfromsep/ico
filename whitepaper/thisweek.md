## 本周目标

- event processor （红雨）- 基本完成，下周可以完成（充值成功事件），以太可以测试（比特币节点还没有部署）充值。
- 虚拟资产支付 （亚东）- 还不能签名。
- GPRC之间全部用TLS （符坤）
- 完成ios推送通知 （AppNotificationWriter) （韩陈裔）- 部分做完，但没有测试。
- 管理员不能确认自己的充值到账：http://gitlab.zhonganonline.com/exchange/nextex/issues/98 （符坤） - OK
- 内部风控流程要有一个基本的版本拿出来讨论。（昊旻，Jay）-下个星期
- 优化外部K线的获取方式-schedule（永丰）-完成
- 提供更丰富的外部数据 - 完成
- 提供内部任何虚拟货币对人民币的价格（通过外部交易所汇总平均）（永丰）
- 根据银行卡号，自动填充发卡行名字的接口（昊旻，建法）- 做完了

- 需要博客运营的清晰定位，以及运营策略，包括每周多少文章，多少转发等等（周杰）- 没完成

- 研发EventLog Viewer后台监控，查看，调试应用 - 符坤

- review彼此的代码 （红雨，亚东，建法）
- 研发后台管理程序-功能设计（王东，袁康）
- 模拟比特币分叉的各种情况，确认cryptrustapi 实现正确 （亚东） - 完成

- 分库分表（建法，永丰）
- ticker美元和人民币价格（符坤，永丰）
- 部署Prometheus进行服务器的监控 - https://github.com/grpc-ecosystem/java-grpc-prometheus/blob/80e32f7a73e216db913135474ec67bf4056ff49b/src/main/java/me/dinowernli/grpc/prometheus/MonitoringServerInterceptor.java（袁康）- 没完成

## 后续目标

- docker/jar中配置文件的替换 - [issues/3](http://gitlab.zhonganonline.com/exchange/commons/issues/3)（建法）

- 和团队成员进行one-on-one谈话或团建。（王东）
- 调试比特币，以太坊充值事件生成逻辑（建法，王东）
- 和大鸟明确部署的方案（单独部署服务器，或者通过运维团队来部署 - 默认可以通过配置完成）。（王东）
- 对NEXTEX进行性能测试（符坤）
- 使用IPFS对服务器snapshot进行备份
