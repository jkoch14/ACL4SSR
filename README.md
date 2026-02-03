# ACL4SSR for Quantumult-X  

[![Quantumult-X](https://img.shields.io/badge/Quantumult--X-Support-brightgreen)](https://quantumult.app/) [![Surge](https://img.shields.io/badge/Surge-Support-blue)](https://nssurge.com/) [![Loon](https://img.shields.io/badge/Loon-Support-orange)](https://loonapp.com/) [web:3]

Quantumult-X / Surge / Loon 订阅转换规则，支持回国分流、去广告、NetEaseMusic 优化。[web:4]



特性
•	规则文件：BanAD.list (去广告)、ChinaDomain.list (国内直连)、NetMusic.list (网易云音乐绕过)、ChinaDNS.list 等。[github]
•	分流策略：中国流量 DIRECT，国际 PROXY，应用特定路由（如 Douyin）。
•	支持节点重命名、延迟测试 (url-test)。[github]
订阅链接
直接复制到 Quantumult-X 配置 > 远程资源：
•	完整规则：`https://raw.githubusercontent.com/[你的用户名]/ACL4SSR/main/ACL4SSR_Online_Full.ini`[github]
•	简版 (无广告)：`https://raw.githubusercontent.com/[你的用户名]/ACL4SSR/main/ACL4SSR_Online.ini`  
替换订阅参数：`[节点订阅]?target=quanx&config=https://raw.githubusercontent.com/[用户名]/ACL4SSR/main/ACL4SSR_Online_Full.ini`[github]
使用步骤
1.	Quantumult-X > 设置 > 配置 > 右上角 + > 添加远程资源 > 粘贴订阅链接。
2.	参数示例：`https://你的机场订阅?target=quanx,policy=🚀节点,url=https://raw.githubusercontent.com/[用户名]/ACL4SSR/main/ACL4SSR_Online_Full.ini`。
3.	更新配置，测试 NetEaseMusic/Douyin 是否直连国内服务器。[github +1]