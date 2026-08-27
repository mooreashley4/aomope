最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计消息发送确认机制配置实操
简介：golang go 程序守护进程实现思路，go 程序不做 daemon 化，依靠 systemd pm2 k8s 实现进程守护。
 | 原文链接：http://book.eeszkl.asia/blog/7742260.sHtMl

原标题：设计思考：分布式锁选型、风险、业务约束
简介：golang cron 任务漂移问题处理，cron 任务执行超时导致任务漂移，通过分布式锁防止任务重叠执行。
 | 原文链接：http://book.eeszkl.asia/blog/0507754.sHtMl

原标题：golang 系统设计第三方 sdk 二次封装技巧
简介：golang mime 类型检测文件，mime 识别文件 mime 类型，设置 http 响应 Content‑Type。
 | 原文链接：http://book.eeszkl.asia/blog/3265754.sHtMl

原标题：Hands‑on：手写简单RPC框架基础通信版本
简介：golang cgo 内存管理 C 与 Go 内存，区分 Go 内存 C 堆内存，防止 cgo 内存泄漏，正确释放 C 内存。
 | 原文链接：http://book.eeszkl.asia/blog/4533677.sHtMl

原标题：golang 系统设计 pr 评审合并完整流程
简介：golang go 服务压测前后性能对比，压测记录 QPS 延迟，优化前后对比，验证优化效果。
 | 原文链接：http://book.eeszkl.asia/blog/6024219.sHtMl

原标题：Issue：定时任务并发执行未加锁重复执行业务
简介：golang http 服务性能优化调参，调优 Go HTTP 服务参数，调整连接池，提升服务并发吞吐能力。
 | 原文链接：http://book.eeszkl.asia/blog/2397694.sHtMl

原标题：开发复盘：统一错误码体系设计落地实践
简介：golang atomic.Value 存储任意类型数据，atomic.Value 安全存储读取任意类型，配置热更新常用。
 | 原文链接：http://book.eeszkl.asia/blog/3365063.sHtMl

原标题：golang 限流熔断降级完整示例
简介：前端错误监控上报系统搭建，搭建前端错误监控，捕获页面 JS 错误，上报后端，快速发现线上页面 bug。
 | 原文链接：http://book.eeszkl.asia/blog/2325387.sHtMl

原标题：开发复盘：统一错误码体系设计落地实践
简介：项目构建脚本编译打包解析，解读项目构建脚本，理清编译、压缩、资源复制流程，理解打包后产物如何生成。
 | 原文链接：http://book.eeszkl.asia/blog/6172390.sHtMl

原标题：正则表达式优化 CPU 占满问题
简介：golang cgroup 读取容器资源限制，go 程序读取 cgroup，获取容器 cpu 内存限额，适配容器环境。
 | 原文链接：http://book.eeszkl.asia/blog/6383013.sHtMl

原标题：从零搭建简单的健康检查接口示例
简介：CI 流水线构建失败日志排查，阅读 CI 流水线输出日志，定位构建脚本、依赖、环境导致流水线失败问题。
 | 原文链接：http://book.eeszkl.asia/blog/2389425.sHtMl

原标题：DNS TTL 配置域名切换生效
简介：golang go panic 合理使用边界，panic 只用于不可恢复程序错误，业务逻辑禁止直接 panic。
 | 原文链接：http://book.eeszkl.asia/blog/4362794.sHtMl

原标题：golang 系统设计 lru 缓存算法实现思路
简介：无用对象回收抑制内存上涨，优化对象生命周期，及时释放不再使用对象，抑制内存持续不断增长。
 | 原文链接：http://book.eeszkl.asia/blog/7371469.sHtMl

原标题：OpenSource：开源项目README高质量编写指南
简介：分布式事务最终一致性实现，基于可靠消息实现最终一致性，解决跨数据库跨服务业务数据一致性。
 | 原文链接：http://book.eeszkl.asia/blog/9694409.sHtMl

原标题：开发记录：短信发送服务封装，失败重试策略
简介：Git 误删提交代码恢复找回，使用 Git reflog 工具找回被误删除提交记录，恢复误删除代码。
 | 原文链接：http://book.eeszkl.asia/blog/1839350.sHtMl

原标题：Practice：数据库分表简单实现方案与代码示例
简介：网关集成鉴权限流日志一体化，在网关层整合鉴权、限流、请求日志，统一对入口请求做管控处理。
 | 原文链接：http://book.eeszkl.asia/blog/5209645.sHtMl

原标题：YAML 配置文件语法快速上手
简介：hosts 配置本地回环访问修复，修改 hosts 配置，修复 127.0.0.1 解析异常，本地服务访问失败问题。
 | 原文链接：http://book.eeszkl.asia/blog/9667026.sHtMl

原标题：开发记录：容器日志标准输出采集实践方案
简介：OOMKilled 容器被杀完整排查，排查容器被 OOM 终止完整流程，区分程序内存泄露和容器内存限制过小。
 | 原文链接：http://book.eeszkl.asia/blog/7979117.sHtMl

原标题：golang 熔断降级简易组件开发
简介：golang nats 轻量消息队列 go 开发，nats 高性能轻量消息系统，发布订阅模式异步解耦业务。
 | 原文链接：http://book.eeszkl.asia/blog/4713194.sHtMl

原标题：Practice：模拟热点key，验证缓存防护策略
简介：golang 配置文件多格式兼容加载，同时支持 yaml toml json 多种格式配置文件，灵活适配不同部署环境。
 | 原文链接：http://book.eeszkl.asia/blog/8526903.sHtMl

原标题：Practice：实现文件监控自动重启开发服务工具
简介：golang http client 连接池调优，调优 Go HTTP Client 连接池参数，复用 TCP 连接，减少连接创建开销。
 | 原文链接：http://book.eeszkl.asia/blog/7082947.sHtMl

原标题：golang goroutine 协程基础实操
简介：golang go 死锁检测工具，静态检查、运行检测，发现 channel 锁导致死锁问题。
 | 原文链接：http://book.eeszkl.asia/blog/2689163.sHtMl

原标题：golang 系统设计创建更新时间自动维护方案
简介：golang go 优雅处理信号丢失场景，处理信号丢失、信号被忽略，保障程序可以正常接收终止信号。
 | 原文链接：http://book.eeszkl.asia/blog/1308716.sHtMl

原标题：方案设计：分布式锁失效风险架构层面规避
简介：特殊输入字符过滤解析防护，过滤用户输入特殊字符，防止解析报错，规避恶意字符带来业务异常。
 | 原文链接：http://book.eeszkl.asia/blog/4622805.sHtMl

原标题：数据库分表存储大表优化方案
简介：golang 异步任务队列 worker 池开发，任务入数据库或 redis，worker 池消费执行，异步处理耗时业务。
 | 原文链接：http://book.eeszkl.asia/blog/0087617.sHtMl

原标题：调优方案：服务实例扩容，水平扩展性能
简介：﻿从零搭建本地开发环境完整教程，手把手完成环境配置，梳理踩坑点，帮助开发者快速搭建可用的本地开发环境，降低上手成本。
 | 原文链接：http://book.eeszkl.asia/blog/2732996.sHtMl

原标题：golang base64 编码解码实操
简介：golang 系统资源限制读取 cpu 内存，读取系统容器 cpu 内存限制，程序适配容器资源配额做业务调优。
 | 原文链接：http://book.eeszkl.asia/blog/0876427.sHtMl

原标题：golang 系统设计网关错误重试超时处理策略
简介：golang 协程 panic 捕获防止崩溃，协程内部捕获 panic，防止单个协程恐慌造成整个 Go 进程崩溃。
 | 原文链接：http://book.eeszkl.asia/blog/4248494.sHtMl

原标题：开发复盘：消息队列消息顺序性业务落地实践
简介：大事务拆分回滚日志暴涨解决，拆分大型数据库事务，减少回滚日志生成量，避免磁盘被回滚日志占满。
 | 原文链接：http://book.eeszkl.asia/blog/1508584.sHtMl

原标题：MySQL 慢查询索引优化实战
简介：golang 容器时区设置镜像构建处理，镜像内部设置正确时区，解决容器时间与宿主机不一致。
 | 原文链接：http://book.eeszkl.asia/blog/3201884.sHtMl

原标题：golang gin 路由分组权限管控
简介：golang time.Ticker 泄漏常见场景，忘记 Stop Ticker，导致协程泄漏，定时器资源无法释放。
 | 原文链接：http://book.eeszkl.asia/blog/3431076.sHtMl

原标题：golang 分布式上下文传递方案
简介：慢查询分析索引调优数据库实战，抓取慢查询，分析执行计划，优化索引，解决数据库慢查询拖慢业务。
 | 原文链接：http://book.eeszkl.asia/blog/6055425.sHtMl

原标题：项目实践：灰度发布简易方案落地实践
简介：golang testify mock 模拟接口，mock 接口生成 mock 对象，单元测试模拟外部依赖行为。
 | 原文链接：http://book.eeszkl.asia/blog/7795533.sHtMl

原标题：Hands‑on：简易连接池原型实现理解原理
简介：nodejs 流处理大文件不占内存，使用 Node.js 流处理超大文件，边读边写，不需要全部加载进内存。
 | 原文链接：http://book.eeszkl.asia/blog/8232783.sHtMl

原标题：简易网关请求路由过滤模拟
简介：golang 单元测试 table‑driven，表格驱动单元测试写法，批量输入多组测试用例，简化单元测试代码。
 | 原文链接：http://book.eeszkl.asia/blog/1482014.sHtMl

原标题：项目依赖安全扫描漏洞防范
简介：golang 接口限流中间件开发，Gin 开发限流中间件，接口层实现访问频率限制，防护接口流量。
 | 原文链接：http://book.eeszkl.asia/blog/0422231.sHtMl

原标题：分布式 ID 全局唯一生成方案
简介：nodejs 消息队列消费服务开发，Node 开发消息队列消费端，监听队列消息执行业务逻辑，异步解耦业务。
 | 原文链接：http://book.eeszkl.asia/blog/6601611.sHtMl

原标题：安全实践：敏感信息加密存储传输完整方案
简介：Mock 接口服务快速搭建实操，搭建模拟后端接口，自定义返回数据、延迟响应，前端开发阶段无需依赖真实后端服务。
 | 原文链接：http://book.eeszkl.asia/blog/6093238.sHtMl

原标题：golang mysql 慢查询日志开启分析
简介：nodejs 项目 pm2 部署运维指南，使用 PM2 管理 Node 服务，进程守护、日志、重启，线上部署运维实操。
 | 原文链接：http://book.eeszkl.asia/blog/4791739.sHtMl

原标题：服务熔断防止故障级联传播
简介：golang redis list 队列简易消息队列，利用 Redis List 实现简易队列，完成任务入队消费基础能力。
 | 原文链接：http://book.eeszkl.asia/blog/9351856.sHtMl


二、踩坑排错｜Troubleshooting
原标题：设计思考：消息顺序性架构保证与业务妥协
简介：golang go‑zero 监控指标埋点，go‑zero 内置 metrics 监控，上报业务指标对接监控平台。
 | 原文链接：http://book.eeszkl.asia/blog/7546624.sHtMl

原标题：golang 系统设计 git 工作流本地开发提交流程
简介：golang rabbitmq go 客户端生产消费，streadway/amqp 实现 rabbitmq 生产者消费者，队列交换机绑定。
 | 原文链接：http://book.eeszkl.asia/blog/1513539.sHtMl

原标题：线上异常：缓存雪崩带来数据库压力瞬间飙升
简介：API 大版本不兼容平滑迁移，API 版本迭代不兼容旧接口，设计平滑迁移方案，逐步完成版本切换。
 | 原文链接：http://book.eeszkl.asia/blog/1274560.sHtMl

原标题：架构复盘：消息队列在业务系统中边界与最佳实践
简介：序列化版本不一致解析失败，保证序列化对象版本对齐，修复版本不匹配导致对象反序列化失败。
 | 原文链接：http://book.eeszkl.asia/blog/7151202.sHtMl

原标题：golang 系统设计日志脱敏防止信息泄露
简介：golang 自定义 pprof 扩展业务指标，扩展 pprof，输出业务自定义指标，结合性能数据分析业务状态。
 | 原文链接：http://book.eeszkl.asia/blog/3302165.sHtMl

原标题：实战：Nginx负载均衡多种策略配置实践
简介：golang 分布式唯一 id 多种方案对比，雪花、redis、uuid 对比各方案优缺点，指导业务选型使用。
 | 原文链接：http://book.eeszkl.asia/blog/8951864.sHtMl

原标题：开源实践：开源项目本地调试构建排坑经验
简介：golang 任务失败重试与死信队列，异步任务失败自动重试，超过重试次数进入死信队列人工处理。
 | 原文链接：http://book.eeszkl.asia/blog/5274908.sHtMl

原标题：日志敏感信息脱敏泄露防护
简介：WSL 内存上限限制防止资源耗尽，修改 WSL 内存上限配置，避免 WSL 占用主机大量内存资源。
 | 原文链接：http://book.eeszkl.asia/blog/3095941.sHtMl

原标题：性能笔记：服务CPU高负载定位分析完整步骤
简介：golang go 随机数安全与非安全，math/rand 伪随机与 crypto/rand 密码学安全随机，区分业务场景。
 | 原文链接：http://book.eeszkl.asia/blog/4704249.sHtMl

原标题：开源实践：Fork上游项目，持续同步更新代码
简介：golang sync.Map 适用场景与性能对比，读多写少，离散 key，对比普通 map 加锁性能差异。
 | 原文链接：http://book.eeszkl.asia/blog/0763093.sHtMl

原标题：从零学习基础的接口请求与参数处理
简介：golang 分布式 ID 雪花算法实现，Go 实现雪花算法，生成分布式全局唯一 ID，适配分库分表主键。
 | 原文链接：http://book.eeszkl.asia/blog/6096090.sHtMl

原标题：golang 系统设计线上 ddl 变更安全执行思路
简介：golang mongodb go 驱动实操教程，mongo‑go‑driver 操作 mongodb，文档增删改查聚合查询。
 | 原文链接：http://book.eeszkl.asia/blog/4864694.sHtMl

原标题：golang k8s devops 流水线简单思路
简介：golang slice 切片底层原理与坑点，切片扩容、截取、底层数组共享，规避切片修改互相影响数据。
 | 原文链接：http://book.eeszkl.asia/blog/4545862.sHtMl

原标题：Hands‑on：简易代理服务器开发实践
简介：golang pprof 线上采集性能数据，线上环境采集 pprof 性能样本，不用停机，分析线上性能问题。
 | 原文链接：http://book.eeszkl.asia/blog/5259275.sHtMl

原标题：开发复盘：超时参数统一治理线上服务实践
简介：golang 结构体零值可用性原则，go 结构体尽量做到零值可用，不用初始化直接使用提升易用性。
 | 原文链接：http://book.eeszkl.asia/blog/5516203.sHtMl

原标题：golang 静态编译缩小镜像体积
简介：前端工程化 webpack 打包优化，针对 webpack 项目做打包调优，分包、压缩、Tree‑Shaking，缩减包体积。
 | 原文链接：http://book.eeszkl.asia/blog/6789601.sHtMl

原标题：记一次第三方SDK版本兼容引发线上故障
简介：golang go get 升级降级依赖版本，go get 指定版本升级降级依赖包，管理第三方库版本。
 | 原文链接：http://book.eeszkl.asia/blog/1610569.sHtMl

原标题：golang 项目 makefile 脚本编写
简介：golang kafka 消费者组重平衡避坑，规避消费者组频繁 rebalance，减少消费抖动，保障消息消费稳定性。
 | 原文链接：http://book.eeszkl.asia/blog/1807177.sHtMl

原标题：golang kafka 消息丢失重复消费
简介：无用对象回收抑制内存上涨，优化对象生命周期，及时释放不再使用对象，抑制内存持续不断增长。
 | 原文链接：http://book.eeszkl.asia/blog/4101976.sHtMl

原标题：入门实践：本地简单代理服务搭建
简介：nodejs 流处理大文件不占内存，使用 Node.js 流处理超大文件，边读边写，不需要全部加载进内存。
 | 原文链接：http://book.eeszkl.asia/blog/6678844.sHtMl

原标题：开发测试生产多环境配置区分
简介：golang bufio.Scanner 缓冲区调大，Scanner 默认缓冲区大小不够，读取超长行需要扩大缓冲区。
 | 原文链接：http://book.eeszkl.asia/blog/4520083.sHtMl

原标题：golang 系统设计技术方案文档模板参考
简介：ICMP 放通网络丢包问题修复，放开 ICMP 协议，解决 MTU 问题导致网络丢包，修复网络不稳定现象。
 | 原文链接：http://book.eeszkl.asia/blog/6534637.sHtMl

原标题：Practice：实现数据库连接池简易模拟实现
简介：golang go 项目 CI github actions 配置，github actions 实现 go 项目 ci，自动测试、代码检查、编译打包镜像。
 | 原文链接：http://book.eeszkl.asia/blog/5383744.sHtMl

原标题：golang mysql exists in 性能对比
简介：数据库分表存储大表优化方案，对超大数据表做分表，拆分数据，降低单表数据量提升查询性能。
 | 原文链接：http://book.eeszkl.asia/blog/6876450.sHtMl

原标题：golang csv 读写批量数据处理
简介：golang go 变量逃逸场景汇总，切片、指针、返回局部变量引发逃逸，变量分配到堆影响 GC。
 | 原文链接：http://book.eeszkl.asia/blog/4431344.sHtMl

原标题：golang 系统设计布隆过滤器原理与落地
简介：nodejs 全局异常捕获进程防护，捕获未捕获异常与 Promise 拒绝，尽量保护进程不因为异常直接退出。
 | 原文链接：http://book.eeszkl.asia/blog/3150085.sHtMl

原标题：golang 优雅关闭 grpc 服务示例
简介：缓存穿透击穿雪崩全套防护，完整梳理缓存三大问题，落地全套防护策略，保障缓存层稳定运行。
 | 原文链接：http://book.eeszkl.asia/blog/9032257.sHtMl

原标题：golang docker 镜像体积优化技巧
简介：用户敏感数据脱敏代码实现，编写数据脱敏工具，对手机号、身份证做脱敏处理，防止敏感信息直接泄露。
 | 原文链接：http://book.eeszkl.asia/blog/8122933.sHtMl

原标题：排错：对象存储跨域配置不生效前端上传失败
简介：golang 终端交互式输入选择，命令行交互式问答选择输入，实现交互式脚本工具。
 | 原文链接：http://book.eeszkl.asia/blog/8637979.sHtMl

原标题：排坑：Git提交历史混乱，如何清理错误提交
简介：golang go 依赖漏洞检测 govulncheck，govulncheck 扫描依赖安全漏洞，发现项目供应链风险。
 | 原文链接：http://book.eeszkl.asia/blog/2161719.sHtMl

原标题：新手向：项目目录结构规范与含义解析
简介：golang 项目 makefile 脚本编写，编写 Makefile 脚本，封装编译、测试、构建命令，简化项目操作。
 | 原文链接：http://book.eeszkl.asia/blog/7451973.sHtMl

原标题：项目实践：OpenTelemetry链路追踪本地部署实践
简介：Git 分支切换合并删除完整操作，实操分支全生命周期操作，包含切换、合并、删除，熟悉日常开发分支处理流程。
 | 原文链接：http://book.eeszkl.asia/blog/0425039.sHtMl

原标题：开源实践：开源项目本地调试构建排坑经验
简介：golang go ring 环形容器循环队列，ring 环形链表实现循环队列，环形缓冲区业务场景。
 | 原文链接：http://book.eeszkl.asia/blog/0733569.sHtMl

原标题：Troubleshooting：数据库索引失效，查询性能暴跌
简介：golang csv 百万级数据导入数据库，流式读取 csv 分批写入数据库，避免一次性加载全部数据。
 | 原文链接：http://book.eeszkl.asia/blog/4412897.sHtMl

原标题：golang 系统设计告警分级 p0‑p3 定义处理流程
简介：批量数据处理脚本编写技巧，编写脚本批量处理大量业务数据，循环处理、分批执行，提升数据处理效率。
 | 原文链接：http://book.eeszkl.asia/blog/8714385.sHtMl

原标题：golang es 分词器选型业务适配
简介：golang http 中间件洋葱模型原理，理解 go http 中间件洋葱模型，请求响应流转顺序，编写自定义中间件。
 | 原文链接：http://book.eeszkl.asia/blog/6124780.sHtMl

原标题：golang github actions 多平台构建
简介：golang go 测试 t.Run 子测试分组，t.Run 实现子测试，分组执行用例，输出分组测试结果。
 | 原文链接：http://book.eeszkl.asia/blog/7431321.sHtMl

原标题：golang 系统设计分布式事务业务选型决策思路
简介：golang crypto 密码学最佳实践，go crypto 包加密签名，规避不安全算法，使用安全密码套件。
 | 原文链接：http://book.eeszkl.asia/blog/9212194.sHtMl

原标题：服务启动依赖顺序配置正确
简介：golang 内存持续上涨定位思路，区分内存泄漏、缓存占用、GC 参数不合理，分步定位内存持续走高。
 | 原文链接：http://book.eeszkl.asia/blog/7869670.sHtMl

原标题：golang 速率限制令牌桶实现
简介：Git 子模块更新代码不全修复，正确更新 Git 子模块，拉取子模块完整代码，解决子模块目录为空问题。
 | 原文链接：http://book.eeszkl.asia/blog/3938395.sHtMl

三、实战开发｜Practice
原标题：golang docker compose 环境变量
简介：golang e2e 端到端测试 go 接口，编写 e2e 测试，完整模拟用户请求，校验整套业务链路正确性。
 | 原文链接：http://book.eeszkl.asia/blog/1420994.sHtMl

原标题：实践：大文件分片上传后端完整实现思路
简介：golang 大内存分配 GC 抖动规避，避免瞬时大量对象创建，分批处理，防止 GC 抖动业务抖动。
 | 原文链接：http://book.eeszkl.asia/blog/0735376.sHtMl

原标题：golang 系统设计网关 ssl 证书配置更新实操
简介：项目语义化版本号规范管理，遵循语义化版本规范管理项目版本，明确主次版本变更含义。
 | 原文链接：http://book.eeszkl.asia/blog/4104014.sHtMl

原标题：优化实践：接口批量合并减少网络请求次数
简介：golang runtime.Gosched 主动让出调度，长计算循环主动 Gosched，让出调度权，防止其他协程饥饿。
 | 原文链接：http://book.eeszkl.asia/blog/4237918.sHtMl

原标题：golang 系统设计定时任务失败重试告警实现
简介：golang bcrypt 密码哈希加密存储，bcrypt 做用户密码哈希，加盐存储密码，保障用户密码安全。
 | 原文链接：http://book.eeszkl.asia/blog/8867371.sHtMl

原标题：ServiceWorker 缓存页面更新清理
简介：golang 信号量控制并发数量，使用信号量控制并发，限制同时执行任务数量，保护下游资源。
 | 原文链接：http://book.eeszkl.asia/blog/0193201.sHtMl

原标题：开发记录：短信发送服务封装，失败重试策略
简介：golang strconv 字符串类型转换，字符串转数字布尔，处理转换失败 error，避免 panic。
 | 原文链接：http://book.eeszkl.asia/blog/2830901.sHtMl

原标题：开发复盘：避免大报文导致服务OOM优化实践
简介：golang 响应 body 流式返回大数据，http 流式输出数据，边生成边返回，无需在内存组装完整返回结果。
 | 原文链接：http://book.eeszkl.asia/blog/4468165.sHtMl

原标题：golang 系统设计覆盖索引减少回表查询实现
简介：分布式 ID 生成器高并发实现，实现高性能分布式 ID 生成器，适配高并发业务，生成全局唯一 ID。
 | 原文链接：http://book.eeszkl.asia/blog/2237251.sHtMl

原标题：golang 系统设计本地缓存更新失效方案实现
简介：golang nats jetstream 持久消息队列，nats jetstream 持久化消息，保证消息不丢失，实现可靠消费。
 | 原文链接：http://book.eeszkl.asia/blog/1472179.sHtMl

原标题：开发复盘：大事务拆分优化业务性能实践
简介：golang io.LimitReader 限制读取字节数，LimitReader 限制最大读取，防止读取超大数据。
 | 原文链接：http://book.eeszkl.asia/blog/9224603.sHtMl

原标题：性能复盘：内存泄漏定位，内存持续上涨优化
简介：golang http 服务优雅关闭完整示例，接收终止信号，停止接收新请求，等待现有请求处理完毕后退出服务。
 | 原文链接：http://book.eeszkl.asia/blog/6782006.sHtMl

原标题：浏览器缓存强制刷新方案
简介：golang net.Listener 包装自定义监听器，包装 Listener 做连接计数、连接拦截，扩展网络能力。
 | 原文链接：http://book.eeszkl.asia/blog/4754863.sHtMl

原标题：前端静态缓存更新生效处理
简介：golang http 代理客户端配置，Go HTTP Client 配置代理，通过代理服务器发起网络请求。
 | 原文链接：http://book.eeszkl.asia/blog/9010946.sHtMl

原标题：设计思考：分布式系统时钟同步带来的架构问题
简介：golang 字符串处理常用技巧汇总，字符串拼接、分割、替换、类型转换实操，规避字符串高频错误。
 | 原文链接：http://book.eeszkl.asia/blog/7135707.sHtMl

原标题：复盘总结：数据库迁移升级风险评估清单
简介：golang init 函数合理使用边界，少用 init，优先显式调用初始化，便于控制初始化时机。
 | 原文链接：http://book.eeszkl.asia/blog/9221187.sHtMl

原标题：实战：GraphQL服务搭建与CRUD实操
简介：日志驱动异常日志不输出修复，排查日志驱动配置，修复日志写入配置，恢复程序正常日志输出。
 | 原文链接：http://book.eeszkl.asia/blog/1248113.sHtMl

原标题：Performance：数据库大表优化，冷热数据分离
简介：前后端交互跨域问题完整处理，讲解跨域产生原理，列举多种解决方案，适配开发、生产不同环境的跨域处理。
 | 原文链接：http://book.eeszkl.asia/blog/7130205.sHtMl

原标题：数据库连接池参数调优
简介：golang etcd key 监听变更 watch 机制，watch 监听 etcd 键变化，配置变更实时感知，实现配置热更新。
 | 原文链接：http://book.eeszkl.asia/blog/3413617.sHtMl

原标题：安全笔记：CSP内容安全策略配置实践
简介：前端国际化多语言方案落地，搭建前端多语言国际化方案，切换语言，页面文本自动切换对应语种。
 | 原文链接：http://book.eeszkl.asia/blog/3782233.sHtMl

原标题：新手指南：项目本地编译输出产物解析
简介：golang sort 稳定排序 Stable，稳定排序保留相等元素原有顺序，业务需要稳定排序场景。
 | 原文链接：http://book.eeszkl.asia/blog/8478616.sHtMl

原标题：方案对比：几种分布式限流算法架构适用性
简介：数据库索引重建提升查询速度，针对碎片化索引，重建数据库索引，恢复 SQL 查询执行性能。
 | 原文链接：http://book.eeszkl.asia/blog/3393873.sHtMl

原标题：排错：HTTPS证书过期导致接口调用失败
简介：golang 负载均衡轮询加权轮询实现，手写负载均衡算法，轮询、加权轮询分发请求到后端节点。
 | 原文链接：http://book.eeszkl.asia/blog/3427665.sHtMl

原标题：快速上手阅读开源项目源码的入门思路
简介：golang go‑zero api 接口开发与路由，go‑zero 编写 api 定义文件，生成代码开发 http 接口。
 | 原文链接：http://book.eeszkl.asia/blog/6394481.sHtMl

原标题：golang 系统设计分布式事务业务选型决策思路
简介：OAuth2 第三方登录服务搭建，搭建 OAuth2 服务，支持第三方账号登录，实现授权登录能力。
 | 原文链接：http://book.eeszkl.asia/blog/5503421.sHtMl

原标题：golang 系统设计测试环境预发环境生产环境隔离
简介：golang gin 路由分组权限管控，Gin 路由分组，不同分组绑定鉴权中间件，实现接口权限分组管控。
 | 原文链接：http://book.eeszkl.asia/blog/9347108.sHtMl

原标题：安全复盘：消息队列未授权访问安全加固
简介：golang tidb 数据库 go 项目适配，go 程序适配 tidb，兼容 mysql 协议，分布式数据库业务开发。
 | 原文链接：http://book.eeszkl.asia/blog/8057450.sHtMl

原标题：golang redis 锁超时业务处理
简介：golang 灰度发布流量权重路由实现，根据权重切分流量，部分流量访问新版本服务，实现灰度发布。
 | 原文链接：http://book.eeszkl.asia/blog/7465685.sHtMl

原标题：golang 系统设计内部服务调用超时设置要点
简介：golang interface {} 类型断言类型转换，类型断言 ok 模式，避免断言失败触发 panic。
 | 原文链接：http://book.eeszkl.asia/blog/3591649.sHtMl

原标题：golang 系统设计死信队列 dlq 业务落地完整流程
简介：容器软链接文件权限修复，修复容器内软链接文件权限，让程序能够正常读取软链接指向的文件。
 | 原文链接：http://book.eeszkl.asia/blog/2381362.sHtMl

原标题：golang 系统设计大文件上传架构
简介：golang staticcheck 静态代码分析，staticcheck 深度静态检查，发现代码错误、性能问题、风格问题。
 | 原文链接：http://book.eeszkl.asia/blog/9808994.sHtMl

原标题：golang 信号捕获程序退出处理
简介：golang 环境变量读取与类型转换，读取系统环境变量，做类型转换默认值处理，适配多环境部署。
 | 原文链接：http://book.eeszkl.asia/blog/1949712.sHtMl

原标题：快速上手简单信号处理脚本编写
简介：golang go 第三方库选型评估要点，评估库活跃度维护情况、性能、依赖数量，选择合适开源库。
 | 原文链接：http://book.eeszkl.asia/blog/6097580.sHtMl

原标题：golang 系统设计测试覆盖率目标合理设定思路
简介：golang tcp_NODELAY 关闭延迟发送，设置 tcp_NODELAY，关闭 Nagle 算法，降低小包请求延迟。
 | 原文链接：http://book.eeszkl.asia/blog/0161979.sHtMl

原标题：坑点：缓存过期策略不当引发业务异常
简介：环境变量不生效问题修复，排查环境变量加载顺序、作用域问题，修复环境变量读取不到的异常。
 | 原文链接：http://book.eeszkl.asia/blog/0853274.sHtMl

原标题：DevOps：容器网络模式选型与坑点总结
简介：react 状态管理方案选型对比，对比 Redux、Zustand 等 React 状态管理库，分析适用业务场景辅助选型。
 | 原文链接：http://book.eeszkl.asia/blog/8698572.sHtMl

原标题：AI‑Dev：利用AI快速阅读陌生开源项目源码
简介：golang gorm ORM 数据库操作，GORM 实操数据库 CRUD，模型定义，关联查询，简化 Go 数据库开发。
 | 原文链接：http://book.eeszkl.asia/blog/7732608.sHtMl

原标题：坑点：环境配置被打包进镜像引发安全泄露
简介：golang sort 搜索查找切片元素，sort.Search 二分查找有序切片，快速定位元素索引位置。
 | 原文链接：http://book.eeszkl.asia/blog/9906454.sHtMl

原标题：golang docker compose 部署 minio
简介：golang time 时间格式化参考时间牢记，2006‑01‑02T15:04:05Z07:00，掌握 go 时间格式化关键点。
 | 原文链接：http://book.eeszkl.asia/blog/8945156.sHtMl

原标题：前端权限路由动态生成实现
简介：集成测试业务流程编写示例，编写业务流程集成测试，覆盖完整业务链路，验证模块之间协同工作是否正常。
 | 原文链接：http://book.eeszkl.asia/blog/2240018.sHtMl

四、架构设计｜Architecture
原标题：Practice：实现多数据源动态切换组件实践
简介：多实例部署 Session 共享方案，多服务实例部署场景，实现 Session 共享，保证用户登录状态跨实例生效。
 | 原文链接：http://book.eeszkl.asia/blog/9569279.sHtMl

原标题：项目实践：MySQL读写分离本地模拟实践
简介：golang tcp 连接泄露排查定位，netstat 查看连接状态，找出未正常关闭连接，定位连接泄漏代码。
 | 原文链接：http://book.eeszkl.asia/blog/5109353.sHtMl

原标题：golang 系统设计 protobuf 可选字段使用技巧
简介：golang go‑zero 分布式锁组件使用，go‑zero 内置 redis 分布式锁，业务直接调用实现并发控制。
 | 原文链接：http://book.eeszkl.asia/blog/8615234.sHtMl

原标题：开发代理服务网络限制解决
简介：Nginx 反向代理路由配置实战，配置 Nginx 反向代理，实现请求转发、路由分发，掌握 Nginx 基础配置能力。
 | 原文链接：http://book.eeszkl.asia/blog/6735838.sHtMl

原标题：架构笔记：冷热数据分离架构设计与迁移
简介：golang 自定义 http round tripper，封装 http 客户端拦截，实现请求日志、签名、重试统一处理逻辑。
 | 原文链接：http://book.eeszkl.asia/blog/7385793.sHtMl

原标题：golang 容器健康检查接口开发
简介：golang 数据库 ORM 框架选型对比，gorm xorm sqlx 对比各 ORM 优缺点，根据业务场景选型。
 | 原文链接：http://book.eeszkl.asia/blog/9729152.sHtMl

原标题：Security：文件路径穿越漏洞完整防护
简介：golang kafka 批量消费性能优化，开启批量拉取消息，调整批量大小，提升 kafka 消息消费吞吐量。
 | 原文链接：http://book.eeszkl.asia/blog/0401237.sHtMl

原标题：前端虚拟列表大数据渲染优化
简介：缓存过期打散防止缓存雪崩，对缓存过期时间增加随机偏移，避免大量缓存同时失效引发缓存雪崩。
 | 原文链接：http://book.eeszkl.asia/blog/1126204.sHtMl

原标题：golang 系统设计开源项目安全漏洞处理流程
简介：nodejs 集成测试业务流程编写，编写 Node 集成测试，调用真实接口，验证完整业务链路执行结果。
 | 原文链接：http://book.eeszkl.asia/blog/6985630.sHtMl

原标题：golang 系统设计开发环境本地调试最佳实践
简介：eslint prettier 代码规范落地，配置 eslint 与 prettier，做代码检查格式化，统一前端团队代码风格。
 | 原文链接：http://book.eeszkl.asia/blog/6495188.sHtMl

原标题：接口请求重试容错机制实现
简介：golang redis 过期时间处理技巧，设置 key 过期，监控过期事件，基于过期特性实现业务缓存逻辑。
 | 原文链接：http://book.eeszkl.asia/blog/8745910.sHtMl

原标题：nodejs 项目 pm2 部署运维指南
简介：golang 单元测试 mock http 请求，mock HTTP 外部接口，单元测试不依赖外部网络，保证用例稳定运行。
 | 原文链接：http://book.eeszkl.asia/blog/9938072.sHtMl

原标题：express 请求参数校验处理
简介：golang gorm 原生 SQL 执行处理，复杂场景执行原生 SQL，处理返回结果集，兼顾性能与灵活性。
 | 原文链接：http://book.eeszkl.asia/blog/8679949.sHtMl

原标题：golang 系统设计配置多环境隔离方案落地
简介：golang 单例模式实现几种方式，Go 单例模式多种实现对比，sync.Once 等方式，实现全局唯一实例。
 | 原文链接：http://book.eeszkl.asia/blog/4468517.sHtMl

原标题：golang 系统设计 mq 故障降级业务策略
简介：rebase 操作防止代码丢失，讲解 rebase 风险点，操作前做好备份，规避错误操作造成代码提交丢失。
 | 原文链接：http://book.eeszkl.asia/blog/5613275.sHtMl

原标题：API 大版本不兼容平滑迁移
简介：golang go 服务日志输出 journald，systemd journald 接收程序 stdout 日志，统一管理服务日志。
 | 原文链接：http://book.eeszkl.asia/blog/3642325.sHtMl

原标题：golang 系统设计密钥轮换安全实践思路
简介：golang hertz http 框架快速上手，hertz 高性能 http 框架，路由中间件参数校验快速开发接口服务。
 | 原文链接：http://book.eeszkl.asia/blog/2385994.sHtMl

原标题：线上故障：Redis内存淘汰策略错误数据丢失
简介：文件监控服务自动重启开发，监控项目文件变更，代码修改自动重启服务，提升本地开发调试效率。
 | 原文链接：http://book.eeszkl.asia/blog/3222601.sHtMl

?
