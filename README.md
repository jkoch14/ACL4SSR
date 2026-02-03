# ACL4SSR for Quantumult-X  

[![Quantumult-X](https://img.shields.io/badge/Quantumult--X-Support-brightgreen)](https://quantumult.app/) [![Surge](https://img.shields.io/badge/Surge-Support-blue)](https://nssurge.com/) [![Loon](https://img.shields.io/badge/Loon-Support-orange)](https://loonapp.com/) [web:3]

Quantumult-X / Surge / Loon 订阅转换规则，支持回国分流、去广告、NetEaseMusic 优化


## Quantumult-X 示例配置
直接导入此 inbound.conf 测试你的规则：


**导入步骤**：
1. Quantumult-X > 配置 > 新建 > 从剪贴板导入。
2. 添加节点到 [server_remote]：`https://你的机场订阅`。
3. 更新资源，切换 Proxy 策略测试。[web:32]

**订阅转换**：用 ACL4SSR 在线工具生成：`节点订阅?target=quanx&config=https://raw.githubusercontent.com/[用户名]/ACL4SSR/main/ACL4SSR_Online_Full.ini` [web:30]
