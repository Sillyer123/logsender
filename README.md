# logsender Instructions
运行环境：python2.x  
使用方法：需要哪种场景日志直接进入目录运行client.py
## 场景详情
- Wanacry  
  - 触发告警  
   - 外网主机发起特定端口扫描（自行添加情报）  
   - 外网主机发起MS17-010攻击（自行CEP规则）  
   - sysmon—检测到WannaCry病毒（自行CEP规则）  
   - 内网主机发起特定端口扫描（自行添加情报）  
   - 内网主机发起MS17-010攻击（自行CEP规则）  
   - sysmon—检测到WannaCry病毒（自行CEP规则）  
   - 内网主机发起特定端口扫描（自行添加情报）  
  - 需要事件  
   - 网络连接  
   - 漏洞利用（添加IDS解析规则）
   - windows进程创建  
- demo1
 - 触发告警  
  - 外网主机发起端口扫描  
  - 网站高频访问  
  - 网站高频404访问  
  - 通用web攻击  
  - Web攻击返回状态码200  
  - 发现webshell后门连接（自行CEP规则）  
  - 发现metapreter后门连接（自行CEP规则）  
  - 针对特定账号的FTP暴力破解  
  - 内网主机针对特定账号的FTP暴力破解  
  - 针对特定主机的FTP暴力破解  
  - 内网主机针对特定主机的FTP暴力破解
