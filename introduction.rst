.. _introduction:

简介
====

**ThreatKey** 是一套基于Docker的高交互(high-interaction)、轻量级的蜜罐系统，
能够在一台VPS或物理机上同时运行多种不同类型的蜜罐，降低部署成本。系统的主要功能有:

- 蜜罐快速搭建
- 多样化日志的收集、查询、统计、分析
- 恶意样本下载
- 蜜罐云端管理(新增、停止、启动、重置)
- 等

与一般的低交互蜜罐模拟服务不同，**ThreatKey** 所提供的蜜罐内运行的是真实的漏洞环境，通过多种类型的监控来记录攻击者的行为，收集的信息包括：

- 访问/登陆日志
- 网络请求，如http(s)、dns、irc等
- 文件变化日志、文件快照
- bash命令
- 等

因此，**ThreatKey** 不仅能够捕获到"外层"的攻击行为，还能记录下入侵后的操作，能有效帮助企业和安全研究人员更加全面的分析整个攻击过程，"感知"潜在的威胁。

