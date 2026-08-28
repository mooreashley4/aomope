最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计 protobuf 默认值坑点梳理
简介：程序预加载加快服务启动速度，把高频使用资源提前预加载，减少请求阶段初始化，加快服务启动。
 | 原文链接：http://blog.xhldejj.cn/Article/details/753265.sHtML

原标题：安全笔记：CORS跨域配置错误安全风险
简介：golang hertz 反向代理与负载均衡，hertz 实现反向代理，内置负载均衡，快速搭建网关类服务。
 | 原文链接：http://blog.xhldejj.cn/Article/details/376478.sHtML

原标题：nodejs 读取大文件 csv 处理方案
简介：nodejs 日志轮转生产环境配置，配置 Node 日志轮转切割，防止日志文件无限变大，适配生产环境。
 | 原文链接：http://blog.xhldejj.cn/Article/details/315499.sHtML

原标题：线程调度优化减少上下文切换
简介：golang channel 关闭规则与坑点，关闭已经关闭 channel 会 panic，判断 channel 是否关闭正确写法。
 | 原文链接：http://blog.xhldejj.cn/Article/details/371872.sHtML

原标题：golang 系统设计 jmeter 简单压测脚本编写
简介：golang go 程序运行时动态修改配置，运行时热加载配置结构体，原子更新保证并发读取安全。
 | 原文链接：http://blog.xhldejj.cn/Article/details/001220.sHtML

原标题：Issue复现：内存泄漏定位完整复盘记录
简介：golang systemd 信号与优雅退出配合，systemd 停止服务发送 SIGTERM，go 程序捕获信号优雅关闭。
 | 原文链接：http://blog.xhldejj.cn/Article/details/477580.sHtML

原标题：依赖安装失败全方位排错
简介：nodejs 数据库连接池配置调优，调优 Node 数据库连接池参数，平衡性能与资源占用，避免连接耗尽。
 | 原文链接：http://blog.xhldejj.cn/Article/details/905997.sHtML

原标题：golang 系统设计故障预案编写模板参考示例
简介：站内邮件消息通知功能开发，实现站内消息、邮件通知推送，业务事件触发通知，提醒用户业务状态变更。
 | 原文链接：http://blog.xhldejj.cn/Article/details/456302.sHtML

原标题：设计思考：系统降级开关架构设计快速切流量
简介：ServiceWorker 缓存页面更新清理，处理 ServiceWorker 缓存，实现页面新版本更新，用户可以加载最新页面。
 | 原文链接：http://blog.xhldejj.cn/Article/details/185551.sHtML

原标题：golang 配置文件多环境加载
简介：golang 大内存分配 GC 抖动规避，避免瞬时大量对象创建，分批处理，防止 GC 抖动业务抖动。
 | 原文链接：http://blog.xhldejj.cn/Article/details/318927.sHtML

原标题：golang 系统设计缓存预热缓存降级实现
简介：golang cron 任务漂移问题处理，cron 任务执行超时导致任务漂移，通过分布式锁防止任务重叠执行。
 | 原文链接：http://blog.xhldejj.cn/Article/details/346710.sHtML

原标题：开发记录：分布式锁超时业务安全处理实践
简介：消息消费重试次数限制防爆炸，限制消息最大重试次数，防止失败消息无限重试造成消息爆炸堆积。
 | 原文链接：http://blog.xhldejj.cn/Article/details/935250.sHtML

原标题：golang alertmanager 钉钉告警推送
简介：golang go 第三方库选型评估要点，评估库活跃度维护情况、性能、依赖数量，选择合适开源库。
 | 原文链接：http://blog.xhldejj.cn/Article/details/556682.sHtML

原标题：Spring 事务传播机制配置生效
简介：golang go 随机数安全与非安全，math/rand 伪随机与 crypto/rand 密码学安全随机，区分业务场景。
 | 原文链接：http://blog.xhldejj.cn/Article/details/941479.sHtML

原标题：WebSocket 双向通信 demo 开发
简介：golang go 变量逃逸场景汇总，切片、指针、返回局部变量引发逃逸，变量分配到堆影响 GC。
 | 原文链接：http://blog.xhldejj.cn/Article/details/800394.sHtML

原标题：golang grafana 监控面板简单配置
简介：golang redis geo 地理位置存储查询，Redis GEO 存储经纬度，查询附近点位，实现附近人业务功能。
 | 原文链接：http://blog.xhldejj.cn/Article/details/282830.sHtML

原标题：排错：对象存储跨域配置不生效前端上传失败
简介：golang GC 频繁 STW 停顿优化，减少小对象分配，调整 GOGC，降低 GC 停顿对接口延迟影响。
 | 原文链接：http://blog.xhldejj.cn/Article/details/853610.sHtML

原标题：golang 系统设计限流算法原理代码实现
简介：golang mysql 长连接检测保活设置，配置 mysql 连接保活检测，剔除失效连接，避免拿到断开无效数据库连接。
 | 原文链接：http://blog.xhldejj.cn/Article/details/512713.sHtML

原标题：Issue：操作系统最大打开文件数限制导致报错
简介：golang 分布式 ID 雪花算法实现，Go 实现雪花算法，生成分布式全局唯一 ID，适配分库分表主键。
 | 原文链接：http://blog.xhldejj.cn/Article/details/267112.sHtML

原标题：golang 系统设计缓存 key 淘汰雪崩防护思路
简介：golang hertz 性能优化参数调优，hertz 连接池、缓冲区参数调优，最大化接口吞吐性能。
 | 原文链接：http://blog.xhldejj.cn/Article/details/743814.sHtML

原标题：golang k8s 命名空间资源隔离方案
简介：前端打包分包加载提速方案，前端打包做代码分包，拆分大 bundle，页面按需加载，提升首屏加载速度。
 | 原文链接：http://blog.xhldejj.cn/Article/details/116264.sHtML

原标题：golang 系统设计接口超时设计原则梳理
简介：文件描述符优化进程卡死修复，及时关闭文件句柄，控制打开文件数量，解决文件句柄耗尽进程卡死。
 | 原文链接：http://blog.xhldejj.cn/Article/details/677585.sHtML

原标题：开源项目本地运行排错完整清单
简介：代理 HTTPS 证书访问异常处理，配置代理根证书，解决代理环境 HTTPS 证书校验失败无法访问外网。
 | 原文链接：http://blog.xhldejj.cn/Article/details/756517.sHtML

原标题：布隆过滤器误判问题修正
简介：内存广播本地进程消息通知，实现进程内内存消息广播，进程内部模块之间事件通知解耦。
 | 原文链接：http://blog.xhldejj.cn/Article/details/427272.sHtML

原标题：golang 系统设计技术方案评审关注点清单参考
简介：序列化版本不一致解析失败，保证序列化对象版本对齐，修复版本不匹配导致对象反序列化失败。
 | 原文链接：http://blog.xhldejj.cn/Article/details/636718.sHtML

原标题：golang 系统设计指标聚合计算存储选型对比
简介：Nginx 反向代理路由配置实战，配置 Nginx 反向代理，实现请求转发、路由分发，掌握 Nginx 基础配置能力。
 | 原文链接：http://blog.xhldejj.cn/Article/details/431331.sHtML

原标题：架构笔记：分库分表中间件选型业务约束
简介：从零编写简易 CLI 命令行工具，通过实战案例实现基础命令交互，理解命令行程序执行逻辑，产出可运行小工具。
 | 原文链接：http://blog.xhldejj.cn/Article/details/855877.sHtML

原标题：实战：搭建日志收集分析简易完整演示环境
简介：GET POST 接口请求参数处理，讲解两种请求方式参数传递区别，演示参数接收、解析、校验，适配不同接口调用场景。
 | 原文链接：http://blog.xhldejj.cn/Article/details/766419.sHtML

原标题：服务器时钟同步任务错乱修复
简介：前端下载导出文件功能实现，前端实现文件流下载导出，处理异常，适配浏览器不同下载行为。
 | 原文链接：http://blog.xhldejj.cn/Article/details/960528.sHtML

原标题：nodejs 集群模式多核利用实现
简介：Spring 事务传播机制配置生效，理解事务传播行为，正确配置，修复事务不生效、事务失效的业务 bug。
 | 原文链接：http://blog.xhldejj.cn/Article/details/086777.sHtML

原标题：golang 系统设计降级策略开关配置方案
简介：跨域偶现失败配置修复，解决跨域问题时而复现时而正常，定位配置漏配、请求头异常等隐性问题。
 | 原文链接：http://blog.xhldejj.cn/Article/details/590937.sHtML

原标题：golang 系统设计开源项目依赖版本升级维护
简介：线程调度优化减少上下文切换，优化线程数量，减少线程频繁切换，降低 CPU 上下文切换开销。
 | 原文链接：http://blog.xhldejj.cn/Article/details/930621.sHtML

原标题：Security：限流防爬虫防恶意攻击防护体系
简介：golang go 容器 heap 堆实现优先队列，实现 heap 接口，构建优先队列，任务优先级调度。
 | 原文链接：http://blog.xhldejj.cn/Article/details/263000.sHtML

原标题：入门实践：使用模板快速生成项目脚手架
简介：golang e2e 端到端测试 go 接口，编写 e2e 测试，完整模拟用户请求，校验整套业务链路正确性。
 | 原文链接：http://blog.xhldejj.cn/Article/details/414131.sHtML

原标题：golang 系统设计回调签名校验防伪造实现
简介：Spring 事务传播机制配置生效，理解事务传播行为，正确配置，修复事务不生效、事务失效的业务 bug。
 | 原文链接：http://blog.xhldejj.cn/Article/details/489261.sHtML

原标题：golang redis 缓存雪崩完整处理
简介：golang cgo 调用 C 语言代码示例，cgo 调用 C 函数，go 与 C 互相调用，对接 C 语言库能力。
 | 原文链接：http://blog.xhldejj.cn/Article/details/826523.sHtML

原标题：异步任务堆积消费能力优化
简介：golang 系统 IO 阻塞 goroutine 场景，理解系统调用阻塞 M，P 会调度其他 M，掌握 go 调度行为。
 | 原文链接：http://blog.xhldejj.cn/Article/details/774070.sHtML

原标题：快速入门WebSocket，实现简易双向通信demo
简介：golang url 参数编码处理方案，Go URL 参数编码解码，处理特殊字符，避免 URL 参数错乱。
 | 原文链接：http://blog.xhldejj.cn/Article/details/930836.sHtML

原标题：优化实践：接口批量合并减少网络请求次数
简介：日志敏感信息脱敏泄露防护，日志打印时自动脱敏手机号身份证，避免日志输出泄露用户隐私数据。
 | 原文链接：http://blog.xhldejj.cn/Article/details/016907.sHtML

原标题：golang 系统设计分布式锁不同场景选型对比
简介：数据库排序规则统一结果一致，统一数据库表排序规则，解决不同环境查询排序结果不一致问题。
 | 原文链接：http://blog.xhldejj.cn/Article/details/401445.sHtML


二、踩坑排错｜Troubleshooting
原标题：golang 链路追踪简易实现方案
简介：nodejs 进程间通信 IPC 实操，演示 Node.js 主进程子进程 IPC 通信，进程之间传递消息数据。
 | 原文链接：http://blog.xhldejj.cn/Article/details/169213.sHtML

原标题：实战项目：百万日志文件解析处理脚本实践
简介：golang gorm 批量插入性能调优，GORM 批量插入优化，调整批次大小，提升大量数据插入数据库速度。
 | 原文链接：http://blog.xhldejj.cn/Article/details/269918.sHtML

原标题：WSL 内存上限限制防止资源耗尽
简介：JWT 工具封装令牌刷新过期，封装 JWT 工具类，实现令牌生成、校验、过期刷新整套令牌管理逻辑。
 | 原文链接：http://blog.xhldejj.cn/Article/details/862883.sHtML

原标题：golang 系统设计读写分离架构示例
简介：golang 命令行参数解析开发，解析命令行入参，开发自定义 CLI 程序，读取启动参数配置服务。
 | 原文链接：http://blog.xhldejj.cn/Article/details/719287.sHtML

原标题：Hands‑on：简易代理服务器开发实践
简介：nodejs 数据库连接池配置调优，调优 Node 数据库连接池参数，平衡性能与资源占用，避免连接耗尽。
 | 原文链接：http://blog.xhldejj.cn/Article/details/307021.sHtML

原标题：效率笔记：调试网络请求curl命令高级用法
简介：golang 微服务网关简易实现，http 反向代理、路由匹配、鉴权限流，理解网关核心原理。
 | 原文链接：http://blog.xhldejj.cn/Article/details/193031.sHtML

原标题：模拟登录鉴权权限判断示例
简介：golang minio 私有对象存储开发，minio s3 对象存储，bucket 管理，文件上传下载权限设置。
 | 原文链接：http://blog.xhldejj.cn/Article/details/716847.sHtML

原标题：分布式 ID 生成器高并发实现
简介：golang grpc 重试机制客户端配置，grpc 客户端配置重试策略，临时故障自动重试，提升调用稳定性。
 | 原文链接：http://blog.xhldejj.cn/Article/details/904306.sHtML

原标题：golang 系统设计灰度发布实现思路
简介：vite 项目配置与构建提速技巧，讲解 vite 配置优化手段，提升开发热更新速度与生产构建打包效率。
 | 原文链接：http://blog.xhldejj.cn/Article/details/678988.sHtML

原标题：实战：数据库索引设计，复合索引最佳实践
简介：golang go 变量逃逸场景汇总，切片、指针、返回局部变量引发逃逸，变量分配到堆影响 GC。
 | 原文链接：http://blog.xhldejj.cn/Article/details/200108.sHtML

原标题：golang lru 缓存淘汰算法编写
简介：前端打包分包加载提速方案，前端打包做代码分包，拆分大 bundle，页面按需加载，提升首屏加载速度。
 | 原文链接：http://blog.xhldejj.cn/Article/details/082177.sHtML

原标题：文件句柄耗尽资源泄露处理
简介：golang go 无锁并发编程技巧，原子操作 sync/atomic，简单场景替换锁，提升并发性能。
 | 原文链接：http://blog.xhldejj.cn/Article/details/270118.sHtML

原标题：golang mysql 存储过程简单使用
简介：golang defer panic 异常处理，理解 defer 延迟执行，panic 恐慌捕获，实现函数资源释放异常保护。
 | 原文链接：http://blog.xhldejj.cn/Article/details/746762.sHtML

原标题：golang 速率限制令牌桶实现
简介：golang go mod graph 查看依赖关系，go mod graph 打印依赖树，定位间接依赖来源，解决版本冲突。
 | 原文链接：http://blog.xhldejj.cn/Article/details/723144.sHtML

原标题：golang 系统设计 k8s 集群安全配置梳理
简介：golang go 项目安全检查漏洞扫描，扫描 go 项目依赖漏洞，代码安全审计，规避安全风险。
 | 原文链接：http://blog.xhldejj.cn/Article/details/768174.sHtML

原标题：Docker 容器网络不通排查
简介：静态博客部署 GitHub Pages 教程，将静态博客项目部署至 GitHub Pages，完成线上访问，快速搭建个人技术博客站点。
 | 原文链接：http://blog.xhldejj.cn/Article/details/642818.sHtML

原标题：OpenSource：开源项目版本发布CHANGELOG编写
简介：服务健康检查监控接口开发，开发健康检查接口，反馈服务运行状态，供编排工具监控服务存活状态。
 | 原文链接：http://blog.xhldejj.cn/Article/details/693714.sHtML

原标题：实战项目：数据导出Excel百万级大数据导出方案
简介：golang proto 默认值坑点梳理，梳理 Protobuf 默认值坑，零值字段区分未赋值，避免业务逻辑错误。
 | 原文链接：http://blog.xhldejj.cn/Article/details/599428.sHtML

原标题：nestjs 框架模块化项目搭建
简介：数据库 utf8mb4 支持 emoji 存储，数据库字段设置 utf8mb4 字符集，完整支持 emoji 表情存储入库。
 | 原文链接：http://blog.xhldejj.cn/Article/details/997043.sHtML

原标题：避坑：版本升级之后项目直接无法启动
简介：Cookie 跨环境登录配置调整，调整 Cookie 域、Secure 属性，适配开发测试生产环境，修复登录失效。
 | 原文链接：http://blog.xhldejj.cn/Article/details/048370.sHtML

原标题：部署复盘：数据库主从备份恢复演练实践
简介：静态博客部署 GitHub Pages 教程，将静态博客项目部署至 GitHub Pages，完成线上访问，快速搭建个人技术博客站点。
 | 原文链接：http://blog.xhldejj.cn/Article/details/384306.sHtML

原标题：Redis 大 key 拆分集群卡顿解决
简介：主干开发团队代码合并策略，讲解主干开发模式，团队代码合并流程，适合高频迭代的团队协作模式。
 | 原文链接：http://blog.xhldejj.cn/Article/details/592270.sHtML

原标题：Troubleshoot：MySQL字符集utf8非utf8mb4emoji报错
简介：golang redis geo 地理位置存储查询，Redis GEO 存储经纬度，查询附近点位，实现附近人业务功能。
 | 原文链接：http://blog.xhldejj.cn/Article/details/780223.sHtML

原标题：缓存穿透击穿雪崩全套防护
简介：golang alertmanager 告警配置实践，alertmanager 配置告警路由，告警发送邮件钉钉，异常及时通知运维。
 | 原文链接：http://blog.xhldejj.cn/Article/details/208776.sHtML

原标题：nodejs 集群模式多核利用实现
简介：空指针异常判空容错处理，讲解空指针产生场景，规范判空逻辑，增加容错，避免空指针直接造成程序崩溃。
 | 原文链接：http://blog.xhldejj.cn/Article/details/614624.sHtML

原标题：零基础理解模块化与组件化基础思想
简介：golang slice 切片底层原理与坑点，切片扩容、截取、底层数组共享，规避切片修改互相影响数据。
 | 原文链接：http://blog.xhldejj.cn/Article/details/288115.sHtML

原标题：golang 系统设计缓存基准测试对比方案
简介：golang 高并发下锁优化减少竞争，减小锁粒度，读写锁替换互斥锁，无锁编程降低锁竞争开销。
 | 原文链接：http://blog.xhldejj.cn/Article/details/978006.sHtML

原标题：分布式 ID 生成器高并发实现
简介：golang redis zset 实现延时任务队列，zset 存储任务到期时间，轮询到期任务执行，简易延迟队列。
 | 原文链接：http://blog.xhldejj.cn/Article/details/053206.sHtML

原标题：golang kafka 消息丢失重复消费
简介：数值 key 浮点匹配异常规避，避免浮点数作为 Redis 等存储的 key，防止精度问题引发 key 匹配失败。
 | 原文链接：http://blog.xhldejj.cn/Article/details/783625.sHtML

原标题：CI 持续集成自动构建流程
简介：golang gin 获取客户端真实 IP，多层代理场景正确拿到用户真实访问 IP，避免拿到网关代理内网地址。
 | 原文链接：http://blog.xhldejj.cn/Article/details/608625.sHtML

原标题：gRPC 服务端客户端入门示例
简介：golang hertz http 框架快速上手，hertz 高性能 http 框架，路由中间件参数校验快速开发接口服务。
 | 原文链接：http://blog.xhldejj.cn/Article/details/084062.sHtML

原标题：坑点：环境配置写死代码，上线忘记修改
简介：golang sort 切片排序自定义 less，sort.Slice 切片快速排序，自定义 less 函数实现业务排序。
 | 原文链接：http://blog.xhldejj.cn/Article/details/005729.sHtML

原标题：golang 文件上传下载接口开发
简介：react hooks 常见陷阱避坑指南，梳理 React Hooks 高频踩坑点，依赖数组、闭包陷阱，写出稳定组件。
 | 原文链接：http://blog.xhldejj.cn/Article/details/771809.sHtML

原标题：前端大文件分片上传完整方案
简介：网络读取超时设置连接挂起防护，设置网络读取超时时间，防止请求无限挂起不返回，占用连接资源。
 | 原文链接：http://blog.xhldejj.cn/Article/details/341374.sHtML

原标题：golang prometheus metrics 埋点开发
简介：从零编写简易 CLI 命令行工具，通过实战案例实现基础命令交互，理解命令行程序执行逻辑，产出可运行小工具。
 | 原文链接：http://blog.xhldejj.cn/Article/details/649647.sHtML

原标题：Hands‑on：实现WebSocket聊天室完整前后端demo
简介：golang os.Exit 退出程序注意 defer 不执行，os.Exit 会直接退出，不会执行 defer，优雅退出不要直接 os.Exit。
 | 原文链接：http://blog.xhldejj.cn/Article/details/085539.sHtML

原标题：实践：大文件分片上传后端完整实现思路
简介：golang raw socket 底层网络报文收发，raw socket 收发原始网络报文，做网络抓包数据包处理。
 | 原文链接：http://blog.xhldejj.cn/Article/details/231977.sHtML

原标题：Security：文件路径穿越漏洞完整防护
简介：热更新开发环境配置教程，配置代码热重载，修改代码无需重启服务立即生效，大幅提升本地开发调试效率。
 | 原文链接：http://blog.xhldejj.cn/Article/details/690921.sHtML

原标题：Performance：避免全表扫描索引失效场景汇总
简介：golang nacos go 客户端配置服务发现，nacos‑go 对接 nacos，配置管理、微服务注册发现。
 | 原文链接：http://blog.xhldejj.cn/Article/details/896259.sHtML

原标题：开发复盘：实现定时任务调度服务支持动态任务
简介：缓存穿透防护保护数据库，实现缓存穿透防护手段，拦截不存在的数据查询，避免请求直接打穿数据库。
 | 原文链接：http://blog.xhldejj.cn/Article/details/997614.sHtML

三、实战开发｜Practice
原标题：golang 系统设计压测环境隔离避免影响生产
简介：golang atomic 原子操作整数，atomic 加减比较交换，无锁更新整型变量，简单计数器场景。
 | 原文链接：http://blog.xhldejj.cn/Article/details/329247.sHtML

原标题：Troubleshooting：Redis大key引发集群卡顿
简介：并发数据覆盖加锁安全处理，多线程并发修改同一数据，增加锁机制，防止并发覆盖丢失更新数据。
 | 原文链接：http://blog.xhldejj.cn/Article/details/899613.sHtML

原标题：golang 错误处理最佳实践汇总
简介：golang recover 捕获 panic 使用边界，recover 只在 defer 内部生效，协程内部必须捕获本协程 panic。
 | 原文链接：http://blog.xhldejj.cn/Article/details/159787.sHtML

原标题：调优方案：JVM内存参数优化，降低GC频率
简介：手写简易 RPC 服务通信原型，手写极简 RPC 原型，理解服务注册、网络传输、方法调用底层逻辑。
 | 原文链接：http://blog.xhldejj.cn/Article/details/120959.sHtML

原标题：实战：接口压力测试实操，定位系统瓶颈
简介：golang go 单二进制文件静态编译交叉编译，交叉编译不同操作系统架构二进制文件，实现一次编译多平台运行。
 | 原文链接：http://blog.xhldejj.cn/Article/details/216862.sHtML

原标题：部署实践：多实例服务部署无状态改造
简介：Docker Compose 一键搭建本地栈，使用 Compose 编排多个容器，一键拉起全套开发依赖服务。
 | 原文链接：http://blog.xhldejj.cn/Article/details/152447.sHtML

原标题：nodejs 内存溢出问题排查修复
简介：golang go 随机数安全与非安全，math/rand 伪随机与 crypto/rand 密码学安全随机，区分业务场景。
 | 原文链接：http://blog.xhldejj.cn/Article/details/555774.sHtML

原标题：OAuth2 第三方登录服务搭建
简介：包管理器依赖缓存清理，清理本地依赖缓存，解决缓存旧包引发问题，拉取最新版本依赖包。
 | 原文链接：http://blog.xhldejj.cn/Article/details/712152.sHtML

原标题：记一次第三方回调IP变动未更新防火墙拦截
简介：golang go 基准测试 benchmark 编写，Benchmark 性能基准测试，测量函数执行耗时内存分配情况。
 | 原文链接：http://blog.xhldejj.cn/Article/details/158096.sHtML

原标题：实战：Docker资源监控查看容器状态实操
简介：golang net/http/httptest 服务端模拟，httptest.NewRecorder 记录 handler 响应，校验返回状态码 body。
 | 原文链接：http://blog.xhldejj.cn/Article/details/602100.sHtML

原标题：golang k8s service 服务暴露几种类型
简介：golang go 程序守护进程实现思路，go 程序不做 daemon 化，依靠 systemd pm2 k8s 实现进程守护。
 | 原文链接：http://blog.xhldejj.cn/Article/details/410293.sHtML

原标题：服务健康检查监控接口开发
简介：golang io.Copy 流式拷贝数据，io.Copy 拷贝 reader 到 writer，不用加载全部数据到内存。
 | 原文链接：http://blog.xhldejj.cn/Article/details/665701.sHtML

原标题：golang grpc protobuf 开发实操
简介：golang gin 获取客户端真实 IP，多层代理场景正确拿到用户真实访问 IP，避免拿到网关代理内网地址。
 | 原文链接：http://blog.xhldejj.cn/Article/details/260687.sHtML

原标题：golang 优雅关闭 grpc 服务示例
简介：golang excel 大文件读取流式解析，流式读取大 excel 文件，逐行解析数据，不加载全部内容进内存。
 | 原文链接：http://blog.xhldejj.cn/Article/details/349214.sHtML

原标题：复盘总结：系统压测报告模板与分析思路
简介：golang math 包常用数学函数，绝对值取整平方根三角函数，业务数学计算工具。
 | 原文链接：http://blog.xhldejj.cn/Article/details/452109.sHtML

原标题：golang 系统设计内部服务熔断降级配置思路
简介：golang docker 镜像构建最佳实践，Go 项目 Docker 镜像构建最佳实践，减小镜像体积，安全构建。
 | 原文链接：http://blog.xhldejj.cn/Article/details/096615.sHtML

原标题：Architecture：链路追踪架构核心组件与埋点
简介：golang go sum 校验失败处理方案，go sum 校验不匹配，排查网络代理，清理缓存解决校验报错。
 | 原文链接：http://blog.xhldejj.cn/Article/details/012154.sHtML

原标题：WebSocket 断线重连稳定优化
简介：前端大文件分片上传完整方案，前端分片切割大文件，配合后端分片接口，实现稳定大文件上传。
 | 原文链接：http://blog.xhldejj.cn/Article/details/670629.sHtML

原标题：golang mysql 分表 id 路由逻辑
简介：golang go 爬虫 robots 协议遵守，解析 robots.txt 规则，控制爬虫抓取范围，合规采集网页数据。
 | 原文链接：http://blog.xhldejj.cn/Article/details/821025.sHtML

原标题：golang 链路追踪简易实现方案
简介：golang go 应用内存使用优化手段，减少对象分配，复用对象，降低 GC 压力，减少 GC 停顿时间。
 | 原文链接：http://blog.xhldejj.cn/Article/details/637620.sHtML

原标题：实战：GraphQL服务搭建与CRUD实操
简介：日志切割配置防止日志丢失，配置日志切割轮转策略，日志按大小时间切割，防止日志文件丢失。
 | 原文链接：http://blog.xhldejj.cn/Article/details/237340.sHtML

原标题：多规则数据脱敏组件开发
简介：golang regexp 正则捕获分组提取数据，正则捕获分组提取子匹配内容，拿到需要业务字段。
 | 原文链接：http://blog.xhldejj.cn/Article/details/029743.sHtML

原标题：接口限流逻辑简单模拟实现
简介：Docker 容器网络不通排查，排查容器网络模式、端口映射、防火墙，解决容器之间、容器外部网络不通。
 | 原文链接：http://blog.xhldejj.cn/Article/details/968114.sHtML

原标题：实战：Redis管道批量操作性能优化实践
简介：数据库主从延迟业务兼容处理，业务适配主从复制延迟，避免读取从库拿到还未同步完成旧数据。
 | 原文链接：http://blog.xhldejj.cn/Article/details/494333.sHtML

原标题：坑点：gitrebase操作失误，代码提交丢失
简介：分布式锁失效问题排查修复，分析分布式锁失效场景，修复锁超时、续期问题，保证锁逻辑可靠。
 | 原文链接：http://blog.xhldejj.cn/Article/details/593745.sHtML

原标题：架构复盘：多级缓存架构，本地缓存+分布式缓存
简介：golang 子进程执行命令标准流处理，exec.Command 执行外部命令，处理 stdout stderr，防止缓冲区阻塞卡死。
 | 原文链接：http://blog.xhldejj.cn/Article/details/275252.sHtML

原标题：方案对比：同步调用vs异步消息业务选型
简介：异步异常捕获避免进程崩溃，捕获异步代码内部抛出异常，防止未捕获异常直接导致整个进程退出。
 | 原文链接：http://blog.xhldejj.cn/Article/details/731917.sHtML

原标题：golang k8s cronjob 定时任务配置
简介：golang http 服务并发连接数限制，自定义 listener 统计连接数量，限制最大并发连接数保护服务。
 | 原文链接：http://blog.xhldejj.cn/Article/details/152032.sHtML

原标题：开发记录：JWT过期刷新滑动过期实现实践
简介：数据库死锁成因规避方案，讲解数据库死锁产生条件，给出业务层面规避手段，减少死锁事件发生。
 | 原文链接：http://blog.xhldejj.cn/Article/details/016552.sHtML

原标题：实战：单元测试+集成测试完整项目落地实践
简介：golang aes cbc gcm 模式加密对比，AES‑CBC AES‑GCM 模式加密解密，理解两种模式差异选型。
 | 原文链接：http://blog.xhldejj.cn/Article/details/501415.sHtML

原标题：golang 系统设计消息重试次数间隔策略设置
简介：golang 文件上传下载接口开发，Go 开发文件上传下载接口，校验文件，处理文件读写存储逻辑。
 | 原文链接：http://blog.xhldejj.cn/Article/details/607456.sHtML

原标题：全局异常处理器接口返回统一
简介：golang 自定义 http round tripper，封装 http 客户端拦截，实现请求日志、签名、重试统一处理逻辑。
 | 原文链接：http://blog.xhldejj.cn/Article/details/026555.sHtML

原标题：MySQL 慢查询索引优化实战
简介：golang 数据库慢查询监控实现，Go 封装 SQL 执行监控，记录慢 SQL，上报日志，发现数据库性能问题。
 | 原文链接：http://blog.xhldejj.cn/Article/details/538393.sHtML

原标题：golang k8s 命名空间资源隔离方案
简介：golang 简单爬虫请求防封禁，简易 Go 爬虫实现，增加请求间隔、UA 伪装，规避被目标站点封禁 IP。
 | 原文链接：http://blog.xhldejj.cn/Article/details/285950.sHtML

原标题：golang 系统设计本地消息表可靠消息最终一致性
简介：golang slice 切片底层原理与坑点，切片扩容、截取、底层数组共享，规避切片修改互相影响数据。
 | 原文链接：http://blog.xhldejj.cn/Article/details/594687.sHtML

原标题：日志切割配置防止日志丢失
简介：golang makefile 多平台编译脚本，makefile 一键交叉编译多平台二进制，打包镜像，执行测试。
 | 原文链接：http://blog.xhldejj.cn/Article/details/781801.sHtML

原标题：golang 系统设计分布式锁看门狗续期原理理解
简介：golang context 超时取消实战案例，使用 context 控制协程、http 请求超时，自动终止超时任务，避免协程无限阻塞。
 | 原文链接：http://blog.xhldejj.cn/Article/details/964097.sHtML

原标题：golang 系统设计数据库慢查询治理方案
简介：文件编码统一随机乱码修复，统一项目全部文件读写编码，消除随机中文乱码，保证文本处理稳定。
 | 原文链接：http://blog.xhldejj.cn/Article/details/883020.sHtML

原标题：golang 系统设计接口不兼容平滑迁移方案
简介：数据库索引重建提升查询速度，针对碎片化索引，重建数据库索引，恢复 SQL 查询执行性能。
 | 原文链接：http://blog.xhldejj.cn/Article/details/388172.sHtML

原标题：日志输出规范防止磁盘爆满
简介：golang io.Reader io.Writer 接口理解，io 读写接口，各类数据源统一抽象，适配 io 复制函数。
 | 原文链接：http://blog.xhldejj.cn/Article/details/601086.sHtML

四、架构设计｜Architecture
原标题：实战项目：搭建本地Mock服务快速开发联调
简介：golang redis zset 实现延时任务队列，zset 存储任务到期时间，轮询到期任务执行，简易延迟队列。
 | 原文链接：http://blog.xhldejj.cn/Article/details/257068.sHtML

原标题：接口请求重试容错机制实现
简介：golang http client 连接池调优，调优 Go HTTP Client 连接池参数，复用 TCP 连接，减少连接创建开销。
 | 原文链接：http://blog.xhldejj.cn/Article/details/155502.sHtML

原标题：golang 空接口 interface 使用技巧
简介：nestjs 框架模块化项目搭建，从零搭建 NestJS 项目，模块化拆分业务，搭建规范后端项目骨架。
 | 原文链接：http://blog.xhldejj.cn/Article/details/524918.sHtML

原标题：golang redis 分布式计数器开发
简介：golang go 线上故障排查完整流程，CPU 高、内存上涨、接口超时、goroutine 泄露一套排查处理流程。
 | 原文链接：http://blog.xhldejj.cn/Article/details/417917.sHtML

原标题：golang 系统设计压测工具 wrk 使用实操
简介：nodejs 多进程任务分发处理，多进程拆分处理 CPU 密集任务，主进程分发任务，利用多核提升处理速度。
 | 原文链接：http://blog.xhldejj.cn/Article/details/809599.sHtML

原标题：新手向：npm/pip/maven依赖版本冲突入门排查
简介：后端分页查询逻辑代码实现，编写后端分页接口，处理页码、每页条数参数，优化大数据量查询返回结果。
 | 原文链接：http://blog.xhldejj.cn/Article/details/338146.sHtML

原标题：golang 系统设计网关路由规则动态配置实现
简介：golang go 初始化顺序包变量 init 函数，包级变量初始化，init 执行顺序，理解包加载执行流程。
 | 原文链接：http://blog.xhldejj.cn/Article/details/401059.sHtML

原标题：文件锁正确使用避免死锁
简介：golang rate 令牌桶限流器源码理解，拆解令牌桶限流核心逻辑，理解令牌生成消耗，掌握限流底层原理。
 | 原文链接：http://blog.xhldejj.cn/Article/details/908434.sHtML

原标题：接口请求重试容错机制实现
简介：CPU 亲和性配置负载均衡调度，配置进程 CPU 亲和，均衡利用多核 CPU，优化程序调度性能。
 | 原文链接：http://blog.xhldejj.cn/Article/details/782408.sHtML

原标题：golang 系统设计配置敏感信息加密存储
简介：golang race 检测器性能开销，race 检测器有性能损耗，只用于测试环境，禁止生产开启 race。
 | 原文链接：http://blog.xhldejj.cn/Article/details/499827.sHtML

原标题：golang 系统设计压测工具 vegeta 使用示例
简介：golang kitex 超时重试熔断配置，kitex 配置调用超时、重试、熔断策略，保障微服务调用稳定性。
 | 原文链接：http://blog.xhldejj.cn/Article/details/060737.sHtML

原标题：golang gin 中间件执行顺序讲解
简介：YAML 配置文件语法快速上手，讲解 YAML 基础语法、缩进规则，编写项目配置文件，规避语法错误引发程序异常。
 | 原文链接：http://blog.xhldejj.cn/Article/details/760352.sHtML

原标题：Performance：避免全表扫描索引失效场景汇总
简介：golang go 二进制安全 strip 减小体积，strip 剥离二进制调试符号，缩小程序二进制文件体积。
 | 原文链接：http://blog.xhldejj.cn/Article/details/633655.sHtML

原标题：golang goroutine 协程基础实操
简介：golang go 整洁架构代码组织实践，整洁架构依赖向内，解耦业务逻辑与外部基础设施。
 | 原文链接：http://blog.xhldejj.cn/Article/details/990652.sHtML

原标题：golang traceId spanId 传递方案
简介：gRPC 服务端客户端入门示例，搭建 gRPC 服务端与调用客户端，学习 protobuf 定义，掌握 RPC 基础开发流程。
 | 原文链接：http://blog.xhldejj.cn/Article/details/785597.sHtML

原标题：golang docker 部署 mysql 注意事项
简介：golang 命令行彩色输出终端，终端彩色文字输出，进度条交互，优化命令行工具用户体验。
 | 原文链接：http://blog.xhldejj.cn/Article/details/150223.sHtML

原标题：设计思考：分布式ID系统架构选型对比
简介：golang regexp 正则捕获分组提取数据，正则捕获分组提取子匹配内容，拿到需要业务字段。
 | 原文链接：http://blog.xhldejj.cn/Article/details/567376.sHtML

原标题：golang 系统设计 hot‑reload 热重载 go 开发工具
简介：golang context.Background 与 TODO 区别，Background 主流程根上下文，TODO 不确定用哪个上下文时使用。
 | 原文链接：http://blog.xhldejj.cn/Article/details/774455.sHtML

?
