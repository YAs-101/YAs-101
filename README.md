杨松 · Java 后端开发
长春理工大学 · 计算机科学技术学院 · 软件工程 · 2027 届
以 Java 后端为主，做过 Spring Cloud 微服务拆分、AI 搜索引用采集、操作系统层面的内存管理模拟。
习惯把项目从「能跑」推进到「能测、能说出数据」。
技术栈
分类
内容
语言
Java（主力，JDK 8 / 11 / 17）、SQL、JavaScript
框架
Spring Boot 3、Spring Cloud Alibaba、Spring Cloud Gateway、OpenFeign、MyBatis-Plus
中间件
Nacos（注册 / 配置）、Redis（缓存、分布式锁）
存储
MySQL 8（索引、事务、执行计划）
前端
Vue 3、ECharts
工程
Maven、Git、Linux 常用命令、Python 脚本
项目
StockPulse · 股票检测统计平台
Spring Boot 3.2.5 Spring Cloud 2023 Nacos Gateway MyBatis-Plus Vue 3
A 股数据检测统计平台，6 个 Maven 模块：common 公共模块 + 网关统一路由 + 用户 / 数据 / 检测 / 统计 4 个业务服务，
经 Nacos 注册发现、OpenFeign 互调。内置 5 条异常检测规则（涨停 / 跌停 / 放量 / 连涨 / 连跌），
前端为 ECharts 四视图仪表盘。数据覆盖 5807 只股票、291,814 条日线行情。
Virtual-Memory-Management · 虚拟存储器管理模拟器
Java 17 零第三方依赖
请求分页式存储管理：地址转换、缺页中断处理、改进型 Clock 置换算法。
页大小 1 KB、物理内存 10 KB 共 10 个页框、逻辑地址空间 64 页；缺页置换按 (R, M) 位四轮扫描淘汰，
R / M 位由模拟的 MMU 在每次访存时自动维护。终端交互，支持手工输入与随机生成两种地址序列。
geo-monitor · AI 搜索引用监测
Node.js Playwright Electron
自动向多个 AI 搜索引擎发起查询，采集回答正文与引用来源，输出引擎间的引用对比报告。
定位是 GEO（生成式引擎优化）场景下的效果度量工具。当前部分引擎因页面改版待适配，
状态与已知限制写在仓库 README 里。
进行中
文件存储服务 — Spring Boot 3 MySQL Redis MinIO
分片上传 / 断点续传 / 秒传。重心在两处：分片合并的并发幂等（分布式锁 + 唯一索引双层保护），
以及大文件全量 MD5 哈希的性能取舍。
其他
仓库
说明
Hotel-Room-Booking-Management-System
酒店客房预订管理系统，前后端分离
Simple-Pixel-Art-Board
浏览器端像素画板，原生 Canvas 实现
联系方式
- 邮箱：1356675991@qq.com
- 求职方向：Java 后端开发（实习 / 2027 届校招）
