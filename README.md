# public-tech-blogs-slides
原创内容，收集eBay在网络云原生，Istio/Service Mesh方面的探索和实践，同时整理最近几年的工作经验，同时也包括一些公开的演讲和meetup的PPT。
<br><br>
Collect the public tech blogs to summarize the work that we've been working on for years related with cloud-native network and Istio service mesh. Also include the slices for public presentation.

# 文档列表

- [001：eBay Feature测试环境上k8s的实践，2021.02.25]
   - 摘要：主要介绍eBay Feature测试环境如何通过软件如在均衡全量迁移到k8s，高峰的时候维护近6000个测试集群，即6000个Pod和VIP，同时做到高可靠性以及快速创建，创建一个feature测试集群95分位数39秒。
- [002：eBay的4层软件负载均衡实现，2021.03.12]
   - 摘要：主要介绍eBay基于IPVS的4层软件负载均衡的实践，结合iptables和BGP并且部署到生产环境。
- [003：eBay网络云原生实践-2021中国网络开源技术生态峰会，2021.05.15]
   - 摘要：分享eBay在云原生网络方面的探索和实践，包括数据边缘和数据中心。
- [004：eBay边缘节点的云原生网络实践，2021.08.27]
   - 摘要：分享eBay边缘节点（POP)基于IPVS、Envoy以及Contour的云原生网络实践，替换边缘节点的硬件负载均衡设备。
- [005：eBay基于Istio的应用网关的探索和实践，2021.07.17]
   - 摘要：分享eBay基于Istio的应用网关在多集群，多数据中心下的应用实践，以及如何构建高可用的架构
