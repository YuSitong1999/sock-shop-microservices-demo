# 测试结果文件和描述

## 韧性测试代理日志（测试过程和结果）

[proxy_2024-02-06-16_tags.log](proxy_2024-02-06-16_tags.log)

## CoreDNS 日志

### 简短配置 log . "{remote} {name} {rcode}"

Pod IP [deploy_pod_wide.log](deploy_pod_wide.log)

部署完成及之前日志 [deploy_coredns.log](deploy_coredns.log)

/tags 请求完成及之前日志 [request_tags_coredns.log](request_tags_coredns.log)

### 全面配置 log . "{remote} {name} {rcode} {proto} {type}"

Pod IP [deploy_pod_wide.log](deploy_pod_wide.2.log)

部署完成及之前日志 [deploy_coredns.log](deploy_coredns.2.log)

/tags 请求完成及之前日志 [request_tags_coredns.log](request_tags_coredns.2.log)

### 全面配置首先安装 Chaos Mesh k8s_dns_chaos

Chaos Mesh Pod IP [chaos-mesh_pod_wide.log](chaos-mesh_pod_wide.log)

Sock Shop Pod IP [sock-shop_pod_wide.log](sock-shop_pod_wide.log)

Chaos Mesh 部署完成及之前日志 [chaos-mesh_coredns.log](chaos-mesh_coredns.log)

Chaos Mesh 和 Sock Shop 部署完成及之前日志 [chaos-mesh_sock-shop_coredns.log](chaos-mesh_sock-shop_coredns.log)

/tags 请求完成及之前日志 [chaos-mesh_sock-shop_request_coredns.log](chaos-mesh_sock-shop_request_coredns.log)
