# Web安全学习笔记

* 基于https://github.com/LyleMi/Learn-Web-Hacking 进行修改，感谢LyleMi大神的分享.
* LyleMi大神笔记的在线版本 https://websec.readthedocs.io .

### 本地编译

```bash
git clone https://github.com/LyleMi/Learn-Web-Hacking.git
cd Learn-Web-Hacking
pip install -r requirements.txt
make local
```

### TODO

* 增加论坛/其他资料信息
* 增加src平台信息
* 针对各类型，增加hackerone/wooyun实例

### Visual Studio code

* Table Formatter -> table:format current

### 笔记大纲

1. 基础知识
    - Web发展简史
    - 计算机网络
    - 域名系统
    - HTTP标准
    - 代码审计
    - WAF
2. 信息收集
    - 域名信息
    - 站点信息
    - 端口信息
3. 内网渗透
    - Windows信息收集
    - Windows持久化
    - Linux信息收集
    - 痕迹清理
4. 常见漏洞
    - SQL注入
    - XSS
    - CSRF
    - SSRF
    - 命令注入
    - 文件读取
    - 文件上传
    - 文件包含
    - XXE
    - 模版注入
    - Xpath注入
    - 逻辑漏洞 / 业务漏洞
    - 配置安全
    - 中间件
    - Web Cache欺骗攻击
5. 语言与框架
    - PHP
    - Python
    - Java
    - JavaScript
    - Ruby
6. 防御技术
    - 总体思路
    - 团队建设
    - 威胁情报
    - 风险控制
    - 加固检查
    - 蜜罐技术
    - 入侵检测
    - 应急响应
    - 溯源分析
7. 工具与资源
    - 工具列表
    - 推荐资源
    - 爆破工具
    - 下载工具
    - 流量相关
    - 嗅探工具
    - SQLMap
8. 其他
    - 认证方式
    - 拒绝服务攻击
    - Docker
