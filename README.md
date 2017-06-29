# 联系方式

- 手机：13811820579 
- Email：suliquanhm@hotmail.com 

---

# 个人信息

 - 苏立权/男/1988 
 - 专科/北京联合大学 
 - 工作年限：6年 
 - 期望职位：C/C++高级工程师 
 - 期望薪资：税前月薪23k~25k 
 - 期望城市：北京 

---

# 工作经历

## 北京思锐信息技术有限公司 （ 2016年5月 ~ 2017年3月 ）

### 海外资产美股项目

**责任描述：**
在项目中主要负责美股行情网关模块的开发工作，以及项目上线后的代码重构与Bug修复。

**项目介绍：**
该项目为凤凰金融App中投资理财模块部分的美股项目，可以让用户在应用内进行美股投资。前端分为Android和iOS两个版本，后端使用Node实现Web后台，使用C++实现美股行情数据的抓取，解析与处理部分，后端模块间使用TCP长链接进行通讯。
本人在项目中负责美股行情数据的解析处理部分，该部分分为两个模块，数据抓取模块和数据解析模块，数据抓取模块只负责行情数据的抓取与备份并将行情数据传输给数据解析模块，数据解析模块会根据规定报文格式解析行情数据，然后根据股票代码到Hash Table中查找上一笔交易的数据，并使用新数据更新覆盖上一次的交易数据，最后存入Redis缓存供前端接口查找调用，并发送给前端web服务供实时数据更新。

### 交易管理平台

** 责任描述： **
在项目中主要负责底层基础模块的开发，并参与项目架构的讨论与搭建。

** 项目介绍： **


## 北京英进质方科技有限公司 （ 2013年4月 ~ 2016年5月 ）

### 马来西亚Time PCC项目

** 责任描述： **
负责项目架构设计与部分模块的开发调试工作，功能需求的后期升级与维护。

** 项目介绍： **
该项目以3GPP规范中PCC架构为基础，实现了其中PCRF(Policy and Charging Rules Function)部分，以完成固网用户上线时的策略下发，策略变更与用户下线功能。各个模块采用多进程设计，模块内部业务处理采用多线程设计。模块间使用socket建立连接，并用内部定义报文进行消息通信。其中DUI模块与SNIFF模块在同一台服务器上且消息单一，使用有名管道进行通信。
该项目核心为在DUI模块内部维护一个用户Hash Table用于维护用户的基本信息与上线信息，共其他模块进行数据的查询下发与维护。

### 马来西亚P1 GTP报文解析项目

** 责任描述： **
负责GTP报文解析模块的设计、开发与调试工作。

** 项目介绍： **
该项目为马来西亚电信运营商P1为接入LTE网络进行用户认证需求开发的，用C语言实现在AAA报文服务器中监听GTP-C报文数据包，根据其中的Create Session Request消息和Create Session Response消息来判断用户的上线对接状态。
本人在项目中负责报文解析模块的架构设计与代码实现。该项目实现了一个简单的GTP-C报文协议栈，能够对TCP协议进行部分字段解析并对建立在之上的GTP-C协议进行全字段解析，获取其中关键字段用来匹配用户在线认证。期间使用tcpdump对网卡进行抓包并使用Wireshark对抓到的数据包进行过滤与分析。

### 北京移动Wlan上网日志留存项目

** 责任描述： **
负责项目的架构设计、开发与调试工作，以及后期功能增加与项目维护。

** 项目介绍： **
该项目是北京移动为了保存Wlan用户上网痕迹而发起的，整体结构分为数据采集和数据展示两部分，后端数据采集部分使用C语言实现并部署在多个数据采集机上，前端数据展示部分使用java实现，前后端间的数据传输使用文件传输。
本人在项目中负责后端数据采集部分的开发与测试，数据源由北京移动机房分光而来，因数据量巨大为防止丢包并提高抓包速度，使用了pf_ring抓包工具在网卡上直接抓包并传到进程内进行匹配处理，匹配原则为用户上行数据包中的四元组数据与下行数据包中的四元组数据能够对应上就算一条上网行为，此时需记下该条上网行为的四元组数据和会话开始结束时间还有该私网IP对应的公网IP和端口，之后将该条记录写入到文件中，待稍后传给前端数据展示模块。

## 北京联银通科技有限公司 （ 2010年10月 ~ 2013年3月 ）

### 民生银行储蓄国债项目

** 责任描述： **
项目负责国债相关交易的实现与平台代码的优化，和文档的编写。

** 项目介绍： **
该项目为储蓄国债在民生银行实施项目，根据银行实际情况对储蓄国债平台进行本地部署与交易开发。并根据银行个性化需求进行新增服务的设计与开发。还会对系统进行调优，使系统更够承受一定的压力而稳定运行。

---

# 技能清单

以下均为我熟练使用的技能

- 开发语言：C/C++/Python/shell
- 开发工具：gcc/gdb/emacs/vim/Wireshark
- 开发库：Poco/Boost/ACE/libev/libevent/libuv
- 网络编程：socket/epoll/select/tcp/udp/http
- 数据库相关：MySQL/Oracle/Redis/TimesTen
- 版本管理、文档和自动化部署工具：Svn/Git
- 操作系统：CentOS/Debian/FreeBSD

---

# 致谢
感谢您花时间阅读我的简历，期待能有机会和您共事。
