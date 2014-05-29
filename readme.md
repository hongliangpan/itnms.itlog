#it综合日志管理系统

#日志审计能力
##网络设备审计
支持：CISCO、华为
日志审计支持：NAT 1.0、FLOW 1.0、NetStream V5
####开机、重启、关机的时间记录
####宕机的时间记录
####CPU、内存的使用情况
####接口状态
####访问者登录时间记录
####配置发生修改的记录
####设备异常
####会话详细信息记录
####NAT1.0日志
包括经过NAT转换前的源IP地址、源端口，经过NAT转换后的源IP地址、源端口，所访问的目的IP、目的端口、协议号、开始时间、结束时间、操作字等关键信息。
####FLOW1.0日志
包括源IP、目的IP、源端口、目的端口、流起始时间、结束时间、操作字等关键信息。
####NetStream V5日志
包括日志的开始时间、结束时间、协议类型、源IP地址、目的IP地址、服务类型、入接口、出接口、报文数、字节数、流数、总激活时间等信息。
####DIG 1.0 日志
DIG 1.0 日志包括DIGFLOW1.0（支持网络层数据）和DIGEST1.0（支持应用层数据）
####DIGFLOW1.0日志
记录包含：开始时间、结束时间、源IP地址、目的IP地址、源端口号、目的端口号、协议类型（目前区分TCP、UDP和ICMP三种协议）、输入包个数、输出包个数、输入字节数、输出字节数。
####DIGEST1.0日志
记录包含：开始时间、结束时间、源IP地址、目的IP地址、目的端口号、摘要信息（目前支持HTTP协议、FTP协议、SMTP协议报文）。

##防火墙设备审计	
支持：CISCO PIX、Juniper NetScreen
####开机、重启、关机的时间纪录
####CPU、内存利用情况
####接口状态
####访问者登录时间记录
####配置发生修改的记录
####设备异常
####会话详细信息记录
####事件类型
####带宽使用情况
####本身的安全性
####规则/策略事件
####网页访问情况
####邮件收发情况
####FTP访问情况
####TELNET情况
####VPN活动情况
####异常情况进行实时的告警
####信息记录进行基于时间、空间的综合统计分析的能力
##操作系统审计
支持Windows、Linux/Unix
####用户登录退出报告 
####用户登录失败报告 
####特定文件、目录访问报告
####系统开机/关机报告
####系统时间修改报告
####系统日志修改报告
####系统远程登录报告
####系统帐号管理操作跟踪
####审计策略变更跟踪
####用户认证成功/失败报告
####应用访问报告
Windows Event Log
####开关机
####系统登陆、注销
####网络登陆
####帐号增加、删除
####用户属性更改（名称、权限、组等）
####口令猜测
####运行程序
####策略更改（系统策略、审计策略等）
####服务增加、删除、开启、关闭
####服务异常关闭
####服务器硬件异常
####日志清除
####审计访问对象 
####应用程序异常
####时间更改、驱动更改
Unix/Linux Syslog
####开关机
####系统认证信息
####口令猜测
####帐户、组管理信息
####关键配置文件错误
####硬件告警、错误
####内核错误信息
####守护进程开启、关闭、错误
数据库审计
支持：MSSQL、ORACLE、Informix
####访问源分析
####用户登录
####数据查询
####数据修改
####数据删除
####数据定义
####权限管理
####创建数据库内容
（包括数据表、视图、过程、索引、函数, 数据库链接），通过设定规则，对某些特定的数据库创建操作进行实施告警：
####新建数据表\视图\过程\函数\索引汇总报告
统计所有数据库的数据表、视图、过程、函数、索引名称，使管理清楚了解当前条件下所有新增对象名称及其他属性。
####修改数据库表内容
####修改数据表结构汇总报告
列出数据库中所有被修改数据表结构的数据表名；
####特定数据表修改字段详细报告
列出数据表修改字段信息。
####对数据库进行数据的插入
####插入数据汇总报告
####特定用户插入数据详细报告
####特定数据表插入数据详细报告
####拷贝表数据详细报告
####对数据库进行数据的删除
####删除数据记录汇总报告
####特定用户删除数据详细报告
####特定数据表删除数据详细报告
####数据库删除表汇总报告
####对数据库进行数据的修改
####修改数据记录汇总报告
####特定用户修改数据详细报告
####特定数据表修改数据详细报告
####对数据库进行数据的查询
####查询数据记录汇总报告
####特定用户查询数据详细报告
####特定数据表查询数据详细报告
####数据库环境参数设置
####特定存储过程修改参数报告
####特定表修改参数报告
####数据库权限修改
####用户权限修改报告
####数据库权限修改报告
####数据表权限修改报告
####用户行为状态审计
####用户行为
####用户登录汇总统计报告
显示所有条件范围内用户登录数据库名的详细信息
####用户特定数据库登录详细报告
####时间访问
####异常时间访问数据库汇总统计报告
对非工作或正常时间下访问数据的行为进行详细统计
