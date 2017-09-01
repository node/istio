# 概念

概念可帮助您了解Istio系统的不同部分及其它使用的抽象。

- [Istio是什么?](what-is-istio.md)

	[概述](what-is-istio/overview.md): 提供Istio的概念介绍，包括其解决的问题和高层架构。

	[设计目标](what-is-istio/goals.md): 描述了Istio设计坚持的核心原则。

- 流量管理

	[概述](traffic-management/overview.md):概述Istio中的流量管理及其功能。

	[Pilot](traffic-management/pilot.md)：引入Pilot，负责在服务网格中管理Envoy代理的分布式部署的组件。

	[请求路由](traffic-management/request-routing.md)：描述在Istio服务网格中服务之间如何路由请求。

	[发现和负载均衡](traffic-management/load-balancing.md):描述在网格中的服务实例之间的流量如何负载均衡。

	[处理故障](traffic-management/handling-failures.md): Envoy中的故障恢复功能概述，可以被未经修改的应用程序来利用，以提高鲁棒性并防止级联故障。

	[故障注入](traffic-management/fault-injection.md): 介绍系统故障注入的概念，可用于发现跨服务的冲突故障恢复策略。

	[规则配置](traffic-management/rules-configuration.md): 提供Istio在服务网格中配置流量管理规则所使用的领域特定语言的高级概述。


