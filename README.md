<div align="center">

<h1>杨松</h1>

<p><b>Java 后端开发</b> · 长春理工大学 计算机科学技术学院 · 软件工程 · 2027 届</p>

<p>
Java 后端为主，做过 Spring Cloud 微服务拆分、AI 搜索引用采集、操作系统层面的内存管理模拟。<br>
习惯把项目从「能跑」推进到「能测、能说出数据」。
</p>

<p>
<a href="mailto:1356675991@qq.com"><img src="https://img.shields.io/badge/Email-1356675991%40qq.com-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="Email"></a>
<a href="https://github.com/YAs-101"><img src="https://img.shields.io/badge/GitHub-YAs--101-181717?style=flat-square&logo=github&logoColor=white" alt="GitHub"></a>
<img src="https://img.shields.io/badge/%E6%B1%82%E8%81%8C-Java%20%E5%90%8E%E7%AB%AF%E5%BC%80%E5%8F%91-2F81F7?style=flat-square" alt="求职方向">
</p>

</div>

---

## 技术栈

| 分类 | 内容 |
| :--- | :--- |
| **语言** | ![Java](https://img.shields.io/badge/Java_17-ED8B00?style=flat-square&logo=openjdk&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) ![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logoColor=white) |
| **后端** | ![Spring Boot](https://img.shields.io/badge/Spring_Boot_3-6DB33F?style=flat-square&logo=springboot&logoColor=white) ![Spring Cloud](https://img.shields.io/badge/Spring_Cloud_2023-6DB33F?style=flat-square) ![Nacos](https://img.shields.io/badge/Nacos-2E9BD6?style=flat-square) ![MyBatis Plus](https://img.shields.io/badge/MyBatis--Plus-B72F2F?style=flat-square) ![OpenFeign](https://img.shields.io/badge/OpenFeign-4B9BE0?style=flat-square) |
| **存储与中间件** | ![MySQL](https://img.shields.io/badge/MySQL_8-4479A1?style=flat-square&logo=mysql&logoColor=white) ![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white) |
| **前端** | ![Vue](https://img.shields.io/badge/Vue_3-4FC08D?style=flat-square&logo=vuedotjs&logoColor=white) ![ECharts](https://img.shields.io/badge/ECharts-AA344D?style=flat-square) |
| **工程与工具** | ![Maven](https://img.shields.io/badge/Maven_3.9-C71A36?style=flat-square&logo=apachemaven&logoColor=white) ![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white) ![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black) |

## 项目

### [StockPulse · 股票检测统计平台](https://github.com/YAs-101/stock-platform-v0.1)

A 股数据检测统计平台：Spring Cloud 微服务拆分，5 条异常检测规则，ECharts 可视化仪表盘。

- **架构**：6 个 Maven 模块，`common` 公共模块 + 网关（:9999）+ 用户 / 数据 / 检测 / 统计 4 个业务服务
- **治理**：Nacos 2.4.1 做注册与配置中心，Gateway 统一路由与 CORS，OpenFeign 服务间调用
- **业务**：涨停 / 跌停 / 放量 / 连涨 / 连跌 5 条检测规则，四视图（大盘 / 搜索 / 排行 / 预警）仪表盘
- **数据**：5807 只股票、291,814 条日线行情，Python + baostock 采集

### [Virtual-Memory-Management · 虚拟存储器管理模拟器](https://github.com/YAs-101/Virtual-Memory-Management)

请求分页式存储管理 + 改进型 Clock 置换算法，Java 17 实现，零第三方依赖。

- **地址变换**：逻辑地址 → 页号 / 页内偏移 → 物理帧号，缺页时触发中断并装入
- **置换算法**：按 (R, M) 位四轮扫描淘汰，优先选干净且未被引用的页
- **参数**：页大小 1 KB，物理内存 10 KB 共 10 个页框，逻辑地址空间 64 页
- **交互**：终端运行，支持手工输入与随机生成两种地址序列

### [geo-monitor · AI 搜索引用监测](https://github.com/YAs-101/geo-monitor)

GEO（生成式引擎优化）场景下的引用度量工具：多引擎采集 AI 搜索回答与引用来源，输出对比报告。

- **采集**：Playwright 驱动多个 AI 搜索引擎，抓取回答正文与引用链接
- **产出**：跨引擎引用对比报告（HTML），支持从历史数据重新渲染而不重采
- **现状**：部分引擎因页面改版待适配，状态与限制写在仓库 README 里

## 进行中

> **文件存储服务** · `Spring Boot 3` `MySQL` `Redis` `MinIO`
>
> 分片上传 / 断点续传 / 秒传。重心在两处：分片合并的并发幂等（Redis 分布式锁 + 数据库唯一索引双层保护），
> 以及大文件全量 MD5 哈希的性能取舍。

## 其他仓库

| 仓库 | 说明 |
| :--- | :--- |
| [Hotel-Room-Booking-Management-System](https://github.com/YAs-101/Design-and-Implementation-of-Hotel-Room-Booking-Management-System) | 酒店客房预订管理系统，前后端分离 |
| [Simple-Pixel-Art-Board](https://github.com/YAs-101/Simple-Pixel-Art-Board) | 浏览器端像素画板，原生 Canvas 实现 |

---

<p align="center">
  <sub>Java 后端开发 · 2027 届 · <a href="mailto:1356675991@qq.com">1356675991@qq.com</a></sub>
</p>
