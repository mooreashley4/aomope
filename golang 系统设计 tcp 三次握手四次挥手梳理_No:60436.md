最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计 tcp 三次握手四次挥手梳理
简介：时间同步修复令牌提前过期，服务器时间不同步导致 JWT 令牌提前过期，同步系统时间解决异常。
 | 原文链接：http://book.gygll6.asia/blog/3131244.sHtML

原标题：golang 系统设计定时任务调度时间校准要点
简介：TCP 心跳检测清理僵死连接，开启 TCP 心跳机制，自动清理僵死无效连接，释放连接资源。
 | 原文链接：http://book.gygll6.asia/blog/3818833.sHtML

原标题：安全实践：防止重放攻击接口签名方案
简介：golang 信号触发配置重载实践，收到 SIGUSR1 信号重新加载配置，线上无需重启刷新配置。
 | 原文链接：http://book.gygll6.asia/blog/3056014.sHtML

原标题：Troubleshoot：CPU调度频繁上下文切换性能下降
简介：golang redis 过期时间处理技巧，设置 key 过期，监控过期事件，基于过期特性实现业务缓存逻辑。
 | 原文链接：http://book.gygll6.asia/blog/0456386.sHtML

原标题：golang 系统设计 pre‑commit 钩子本地代码校验
简介：时间精度统一业务判断修复，统一业务使用时间戳精度，毫秒秒区分清楚，修复时间判断逻辑错误。
 | 原文链接：http://book.gygll6.asia/blog/9607991.sHtML

原标题：golang 日志脱敏敏感字段过滤
简介：golang 程序崩溃 core dump 生成调试，开启 core dump，程序崩溃生成转储文件，事后分析崩溃原因。
 | 原文链接：http://book.gygll6.asia/blog/3951333.sHtML

原标题：golang 单元测试 table‑driven
简介：golang 内存持续上涨定位思路，区分内存泄漏、缓存占用、GC 参数不合理，分步定位内存持续走高。
 | 原文链接：http://book.gygll6.asia/blog/9636422.sHtML

原标题：golang 系统设计数据库版本迁移回滚方案
简介：golang go 无锁并发编程技巧，原子操作 sync/atomic，简单场景替换锁，提升并发性能。
 | 原文链接：http://book.gygll6.asia/blog/6589876.sHtML

原标题：golang 分库分表简单路由实现
简介：批量操作分批处理防止 OOM，大批量数据处理不一次性加载全部数据，分批循环处理，避免内存溢出。
 | 原文链接：http://book.gygll6.asia/blog/5441165.sHtML

原标题：golang 系统设计本地消息表可靠消息最终一致性
简介：golang go 程序权限最小化运行，容器内使用普通用户运行程序，拒绝 root 运行提升安全等级。
 | 原文链接：http://book.gygll6.asia/blog/0111448.sHtML

原标题：实战：Docker资源监控查看容器状态实操
简介：依赖版本冲突兼容修复方案，定位依赖版本冲突根源，通过版本约束、替换包，解决版本不兼容运行报错。
 | 原文链接：http://book.gygll6.asia/blog/4908020.sHtML

原标题：golang 系统设计定时任务分片执行分布式思路
简介：golang init 函数合理使用边界，少用 init，优先显式调用初始化，便于控制初始化时机。
 | 原文链接：http://book.gygll6.asia/blog/4848975.sHtML

原标题：golang etcd 配置中心简单使用
简介：golang md5 sha 加密工具实现，实现 MD5、SHA 哈希工具，做数据摘要，用于签名校验场景。
 | 原文链接：http://book.gygll6.asia/blog/4846088.sHtML

原标题：限流规则误拦截正常请求修复
简介：golang race 检测器性能开销，race 检测器有性能损耗，只用于测试环境，禁止生产开启 race。
 | 原文链接：http://book.gygll6.asia/blog/3651516.sHtML

原标题：OpenSource：开源项目版本发布CHANGELOG编写
简介：全局异常处理器接口返回统一，接入全局异常捕获，拦截业务全部异常，对外输出统一格式返回值。
 | 原文链接：http://book.gygll6.asia/blog/8172327.sHtML

原标题：golang mysql 主从同步延迟兼容
简介：静态资源 404 路径打包修复，修复打包后静态资源访问 404，调整资源输出路径，保证资源正常加载。
 | 原文链接：http://book.gygll6.asia/blog/5643014.sHtML

原标题：开发生产环境资源路径统一
简介：golang redis scan 遍历 key 避免阻塞，使用 scan 迭代遍历 redis 键，不用 keys 命令，防止阻塞 redis 服务。
 | 原文链接：http://book.gygll6.asia/blog/8809800.sHtML

原标题：快速入门Nginx基础配置，反向代理示例
简介：代理 HTTPS 证书访问异常处理，配置代理根证书，解决代理环境 HTTPS 证书校验失败无法访问外网。
 | 原文链接：http://book.gygll6.asia/blog/7271374.sHtML

原标题：golang mysql 分表自增 id 方案
简介：golang proto 可选字段处理方案，protobuf 可选字段正确判断，区分未赋值与零值，业务逻辑不出现偏差。
 | 原文链接：http://book.gygll6.asia/blog/9285752.sHtML

原标题：实战：gRPC服务编写客户端服务端完整demo
简介：golang go url url.Values 参数编码，url.Values 构建 url 查询参数，自动处理参数 url 编码。
 | 原文链接：http://book.gygll6.asia/blog/9526773.sHtML

原标题：排错：DockerCompose依赖顺序启动顺序坑
简介：接口签名校验防篡改实现，实现请求签名验签逻辑，校验请求参数未被篡改，提升接口调用安全性。
 | 原文链接：http://book.gygll6.asia/blog/6305913.sHtML

原标题：系统时间同步定时任务偏移
简介：布隆过滤器数据高效去重实现，实现布隆过滤器组件，用于海量数据去重，节省大量内存空间。
 | 原文链接：http://book.gygll6.asia/blog/5751688.sHtML

原标题：Debug：网关超时时间小于后端接口超时设置
简介：golang kafka 批量消费性能优化，开启批量拉取消息，调整批量大小，提升 kafka 消息消费吞吐量。
 | 原文链接：http://book.gygll6.asia/blog/5334322.sHtML

原标题：golang 系统设计多级缓存架构落地
简介：golang tcp 四次挥手 go 程序行为，理解 tcp 四次挥手，处理连接关闭、重置、RST 包异常场景。
 | 原文链接：http://book.gygll6.asia/blog/3219306.sHtML

原标题：踩坑：批量MQ消费失败直接无限重试消息爆炸
简介：golang http 中间件洋葱模型原理，理解 go http 中间件洋葱模型，请求响应流转顺序，编写自定义中间件。
 | 原文链接：http://book.gygll6.asia/blog/7459598.sHtML

原标题：实战项目：数据导出Excel百万级大数据导出方案
简介：golang 参数校验业务接口处理，Go 接口入参参数校验，拦截非法入参，减少业务层参数判断代码。
 | 原文链接：http://book.gygll6.asia/blog/1242878.sHtML

原标题：golang docker 多阶段构建 go 镜像
简介：golang gorm 批量插入性能调优，GORM 批量插入优化，调整批次大小，提升大量数据插入数据库速度。
 | 原文链接：http://book.gygll6.asia/blog/9347963.sHtML

原标题：Architecture：静态配置与动态配置架构分离
简介：golang json number 数字不转 float64，使用 json.Number 保留原始数字字符串，防止大数字精度丢失。
 | 原文链接：http://book.gygll6.asia/blog/8217528.sHtML

原标题：数据库主从延迟业务兼容处理
简介：golang 分表跨表 join 查询处理方案，分表后跨分片关联查询解决方案，业务层聚合代替数据库 join。
 | 原文链接：http://book.gygll6.asia/blog/3115483.sHtML

原标题：Issue：浏览器缓存ServiceWorker导致旧页面常驻
简介：SSH 密钥配置 GitHub 免密登录，分步生成配置 SSH 密钥，实现 GitHub 免密推送拉取，免去重复输入账号密码的麻烦。
 | 原文链接：http://book.gygll6.asia/blog/0625745.sHtML

原标题：MySQL 慢查询索引优化实战
简介：golang 网卡 ip 读取网络信息获取，程序读取本机网卡 IP，多网卡环境筛选业务使用 IP 地址。
 | 原文链接：http://book.gygll6.asia/blog/5299088.sHtML

原标题：golang 系统设计网关缓存静态资源实现思路
简介：golang 内存 pprof 定位内存泄漏，pprof 分析内存快照，定位内存泄露对象，解决 Go 程序内存持续上涨。
 | 原文链接：http://book.gygll6.asia/blog/1797427.sHtML

原标题：golang 系统设计分库分表本地测试调试技巧
简介：golang hystrix 模式简易熔断实现，简易熔断组件，错误率达到阈值触发熔断，快速失败保护下游。
 | 原文链接：http://book.gygll6.asia/blog/8275759.sHtML

原标题：OpenSource：开源项目风险评估依赖安全检查
简介：golang 时间时区处理避坑指南，Go 时间时区常见坑，时区转换，时间比较，规避时间逻辑错误。
 | 原文链接：http://book.gygll6.asia/blog/1275058.sHtML

原标题：golang 链路追踪简易实现方案
简介：golang runtime.Gosched 主动让出调度，长计算循环主动 Gosched，让出调度权，防止其他协程饥饿。
 | 原文链接：http://book.gygll6.asia/blog/0745630.sHtML

原标题：安全复盘：定时任务权限过大风险管控
简介：nodejs jwt 登录鉴权完整示例，Node 实现 JWT 登录鉴权，登录签发令牌，接口校验令牌身份。
 | 原文链接：http://book.gygll6.asia/blog/4612964.sHtML

原标题：踩坑记录：数值溢出造成业务ID错乱异常
简介：golang delve 远程调试 go 线上程序，delve 远程调试，线上环境附加进程调试排查线上 bug。
 | 原文链接：http://book.gygll6.asia/blog/2913234.sHtML

原标题：坑点：gitcherry‑pick引入不兼容代码
简介：golang go 爬虫请求速率控制，爬虫限频、代理轮换，设置 UA，防止爬虫被目标站点封禁 IP。
 | 原文链接：http://book.gygll6.asia/blog/9261307.sHtML

原标题：实战项目：前端资源打包体积优化完整实操
简介：golang http 服务优雅关闭完整示例，接收终止信号，停止接收新请求，等待现有请求处理完毕后退出服务。
 | 原文链接：http://book.gygll6.asia/blog/7772433.sHtML

原标题：golang github actions 发布 release 包
简介：golang grpc 客户端流上传数据，客户端流式请求，客户端分批上传数据到服务端，适合大文件传输。
 | 原文链接：http://book.gygll6.asia/blog/1764046.sHtML


二、踩坑排错｜Troubleshooting
原标题：golang 系统设计内网外网服务隔离方案
简介：全局本地依赖隔离冲突规避，区分全局依赖与项目本地依赖，隔离环境，防止全局包干扰项目运行。
 | 原文链接：http://book.gygll6.asia/blog/6831972.sHtML

原标题：新手教程：本地项目初始化gitignore配置
简介：golang go 零停机升级实践要点，socket 继承，流量无损，旧连接处理完毕后旧进程退出。
 | 原文链接：http://book.gygll6.asia/blog/0105647.sHtML

原标题：Practice：实现请求body重复读取中间件实践
简介：浮点计算精度错误处理方案，讲解浮点数计算精度丢失问题，使用合适数据类型，规避金额计算出错。
 | 原文链接：http://book.gygll6.asia/blog/8708020.sHtML

原标题：golang 系统设计多级缓存更新策略
简介：golang 容器信号转发处理问题修复，docker/k8s 正确转发 SIGTERM 信号，保证 go 程序收到信号优雅退出。
 | 原文链接：http://book.gygll6.asia/blog/7522235.sHtML

原标题：快速入门：API接口调试完整实操步骤
简介：golang 钉钉企业微信告警消息推送，go 调用企业微信钉钉接口，推送告警通知、业务消息。
 | 原文链接：http://book.gygll6.asia/blog/7554589.sHtML

原标题：golang 系统设计 http1.1 http2 核心差异讲解
简介：开源项目本地运行排错完整清单，汇总开源项目拉取后运行失败各类问题，给出排查思路，快速解决本地启动异常。
 | 原文链接：http://book.gygll6.asia/blog/2077241.sHtML

原标题：service‑worker 离线缓存实践
简介：golang go 服务蓝绿发布实践思路，蓝绿两套实例，流量一键切换，回滚快速降低发布风险。
 | 原文链接：http://book.gygll6.asia/blog/8758937.sHtML

原标题：OpenSource：开源项目版本发布CHANGELOG编写
简介：golang http 代理客户端配置，Go HTTP Client 配置代理，通过代理服务器发起网络请求。
 | 原文链接：http://book.gygll6.asia/blog/2349569.sHtML

原标题：golang 系统设计链路查询定位慢请求实操技巧
简介：golang go‑fuzz 模糊测试开发，go fuzz 模糊测试，自动构造异常输入，发现代码隐藏 bug。
 | 原文链接：http://book.gygll6.asia/blog/0501640.sHtML

原标题：性能笔记：压测如何定位真实系统瓶颈
简介：golang rate‑limiter 限流组件，封装通用 Go 限流组件，支持多算法，业务接口直接复用调用。
 | 原文链接：http://book.gygll6.asia/blog/9011931.sHtML

原标题：monorepo 项目多包管理最佳实践
简介：数值 key 浮点匹配异常规避，避免浮点数作为 Redis 等存储的 key，防止精度问题引发 key 匹配失败。
 | 原文链接：http://book.gygll6.asia/blog/1951047.sHtML

原标题：golang 系统设计 rest api 接口设计最佳实践
简介：内网测试服务搭建团队调试，配置本地服务内网可访问，团队成员能够访问调试，方便前后端联调与内部演示。
 | 原文链接：http://book.gygll6.asia/blog/3471317.sHtML

原标题：新手参与开源社区贡献指南
简介：golang kafka 同步异步消费对比，对比 Kafka 同步消费异步消费，分析优缺点，业务选型参考。
 | 原文链接：http://book.gygll6.asia/blog/2055851.sHtML

原标题：Performance：大事务拆分，减少锁持有时间
简介：golang url 解析路径参数提取，url.Parse 解析 url，获取协议主机路径查询参数。
 | 原文链接：http://book.gygll6.asia/blog/1885456.sHtML

原标题：踩坑：环境变量未生效导致线上配置错乱
简介：时间同步修复令牌提前过期，服务器时间不同步导致 JWT 令牌提前过期，同步系统时间解决异常。
 | 原文链接：http://book.gygll6.asia/blog/7459160.sHtML

原标题：golang 系统设计内网外网服务隔离方案
简介：golang 配置文件多格式兼容加载，同时支持 yaml toml json 多种格式配置文件，灵活适配不同部署环境。
 | 原文链接：http://book.gygll6.asia/blog/4497153.sHtML

原标题：golang 系统设计多级缓存架构落地
简介：golang go 多版本管理 gvm 使用，gvm 管理多个 go sdk 版本，快速切换不同 go 版本做项目开发。
 | 原文链接：http://book.gygll6.asia/blog/7150695.sHtML

原标题：golang 系统设计回调重试幂等完整处理
简介：golang yaml 解析配置加载实操，Go 解析 YAML 配置文件，读取配置参数，驱动业务运行。
 | 原文链接：http://book.gygll6.asia/blog/9905664.sHtML

原标题：Issue：本地数据库与线上数据库排序规则差异
简介：golang 协程泄露问题排查方法，识别 Go 协程泄露现象，分析泄露场景，给出排查定位协程泄露手段。
 | 原文链接：http://book.gygll6.asia/blog/7727912.sHtML

原标题：golang redis 客户端业务使用
简介：golang gorm select 指定查询字段，指定查询字段，避免查询全部字段，减少数据传输，提升查询性能。
 | 原文链接：http://book.gygll6.asia/blog/3015754.sHtML

原标题：性能复盘：消息队列大量小消息性能问题优化
简介：DNS TTL 配置域名切换生效，调整 DNS 解析 TTL，缩短缓存时间，域名变更后可以快速全网生效。
 | 原文链接：http://book.gygll6.asia/blog/4109058.sHtML

原标题：零基础理解版本控制核心概念与工作流
简介：nestjs 全局返回格式统一处理，Nest 全局拦截器统一包装接口返回数据，对外输出标准化响应格式。
 | 原文链接：http://book.gygll6.asia/blog/3460127.sHtML

原标题：安全复盘：OAuth2授权流程安全坑点汇总
简介：本地数据库开发环境搭建指南，讲解数据库安装配置、账号权限设置、连接测试，快速搭建用于开发调试的数据库实例。
 | 原文链接：http://book.gygll6.asia/blog/0807497.sHtML

原标题：依赖安装失败全方位排错
简介：golang gitlab ci go 项目流水线编写，gitlab ci 流水线执行单元测试、静态检查、构建推送镜像。
 | 原文链接：http://book.gygll6.asia/blog/9669130.sHtML

原标题：golang 重试退避机制代码实现
简介：golang 分库分表简单路由实现，简易分表路由逻辑实现，根据分片 key 计算分片位置，数据路由写入。
 | 原文链接：http://book.gygll6.asia/blog/5388070.sHtML

原标题：全量回归测试提升代码质量
简介：golang 子进程超时杀死防止挂住，context 控制子进程超时，超时强制杀掉子进程，避免子进程僵尸。
 | 原文链接：http://book.gygll6.asia/blog/8327494.sHtML

原标题：Hands‑on：shell脚本批量自动化运维小工具
简介：echarts 大数据渲染性能调优，大数据量 ECharts 图表调优，数据采样、分片渲染，解决图表卡顿。
 | 原文链接：http://book.gygll6.asia/blog/2983810.sHtML

原标题：运维笔记：系统监控指标大盘搭建实操
简介：golang 分布式事务 seata go 客户端，seata‑go 实现分布式事务，保证跨库业务数据最终一致性。
 | 原文链接：http://book.gygll6.asia/blog/2615546.sHtML

原标题：设计思考：系统幂等性整体架构层面保障
简介：HTTP 状态码请求头完整梳理，汇总常用 HTTP 状态码与请求头含义，帮助快速看懂网络请求，排查接口通信问题。
 | 原文链接：http://book.gygll6.asia/blog/3949867.sHtML

原标题：golang 系统设计海量数据分页查询
简介：golang go mod graph 查看依赖关系，go mod graph 打印依赖树，定位间接依赖来源，解决版本冲突。
 | 原文链接：http://book.gygll6.asia/blog/3177381.sHtML

原标题：数据库 utf8mb4 支持 emoji 存储
简介：golang os/exec 安全执行外部命令，规避命令注入漏洞，参数分离，禁止拼接命令字符串执行。
 | 原文链接：http://book.gygll6.asia/blog/6021806.sHtML

原标题：Practice：批量异步任务处理系统设计实现
简介：golang json 解析未知动态 json 结构，解析到 map [string] any 处理未知 json，动态读取字段。
 | 原文链接：http://book.gygll6.asia/blog/3360314.sHtML

原标题：golang 系统设计密钥轮换安全实践思路
简介：golang gorm 批量插入性能调优，GORM 批量插入优化，调整批次大小，提升大量数据插入数据库速度。
 | 原文链接：http://book.gygll6.asia/blog/7759864.sHtML

原标题：golang http grpc 全链路埋点示例
简介：ORM 框架数据库增删改查实操，使用 ORM 框架完成数据库基础操作，减少手写 SQL，简化业务层数据库交互代码。
 | 原文链接：http://book.gygll6.asia/blog/5588340.sHtML

原标题：实战：gRPC服务编写客户端服务端完整demo
简介：golang os 打开文件 O_APPEND O_CREATE 标志，OpenFile 标志位，控制文件创建追加截断行为。
 | 原文链接：http://book.gygll6.asia/blog/4505758.sHtML

原标题：golang 系统设计消息大小限制业务处理方案
简介：nestjs 权限守卫鉴权实现方案，使用 Nest 守卫实现接口鉴权，角色权限控制，拦截未授权接口访问。
 | 原文链接：http://book.gygll6.asia/blog/3342087.sHtML

原标题：快速入门简单签名校验实现思路
简介：golang ioutil 已废弃替换方案，ioutil 废弃之后替换为 os io 包函数，更新旧项目代码。
 | 原文链接：http://book.gygll6.asia/blog/1377363.sHtML

原标题：golang docker 部署 mysql 注意事项
简介：golang websocket 服务端开发，Go 实现 WebSocket 服务端，处理连接、消息收发，实现长连接服务。
 | 原文链接：http://book.gygll6.asia/blog/8377168.sHtML

原标题：Issue：开源项目升级大版本后API不兼容踩坑
简介：express 中间件开发业务实践，开发 Express 自定义中间件，拦截请求，实现鉴权、日志记录等通用逻辑。
 | 原文链接：http://book.gygll6.asia/blog/2319897.sHtML

原标题：golang gin 路由分组权限管控
简介：golang golangci‑lint 静态代码检查配置，golangci‑lint 静态检查，代码规范检测，提前发现代码隐患。
 | 原文链接：http://book.gygll6.asia/blog/1838167.sHtML

三、实战开发｜Practice
原标题：Troubleshooting：代理环境下证书校验失败HTTPS报错
简介：接口签名验签完整安全方案，一套完整接口签名方案，包含签名生成、请求携带、服务端验签校验。
 | 原文链接：http://book.gygll6.asia/blog/2857684.sHtML

原标题：golang grafana 面板变量模板制作
简介：golang rate 令牌桶限流器源码理解，拆解令牌桶限流核心逻辑，理解令牌生成消耗，掌握限流底层原理。
 | 原文链接：http://book.gygll6.asia/blog/9231138.sHtML

原标题：方案对比：定时任务框架选型与架构对比
简介：golang sync.Map 适用场景与性能对比，读多写少，离散 key，对比普通 map 加锁性能差异。
 | 原文链接：http://book.gygll6.asia/blog/1942520.sHtML

原标题：开发记录：搭建CI/CD流水线自动构建部署项目
简介：git cherry‑pick 规范操作防 bug，规范 cherry‑pick 使用流程，处理冲突，避免错误引入不兼容代码。
 | 原文链接：http://book.gygll6.asia/blog/7424805.sHtML

原标题：踩坑记录：浮点精度错误造成业务计算错误
简介：golang 集成测试测试数据库回滚，集成测试结束自动回滚数据库，不污染测试环境数据。
 | 原文链接：http://book.gygll6.asia/blog/5962183.sHtML

原标题：Practice：实现异步任务结果查询回调实践
简介：CORS 跨域问题多种解决方案，对比 CORS、代理等不同跨域方案优缺点，根据业务场景选择合适的跨域处理方式。
 | 原文链接：http://book.gygll6.asia/blog/6640551.sHtML

原标题：golang 系统设计 webhook 回调接口设计要点
简介：golang 单元测试 mock http 请求，mock HTTP 外部接口，单元测试不依赖外部网络，保证用例稳定运行。
 | 原文链接：http://book.gygll6.asia/blog/1052990.sHtML

原标题：git cherry‑pick 规范操作防 bug
简介：golang go 多版本管理 gvm 使用，gvm 管理多个 go sdk 版本，快速切换不同 go 版本做项目开发。
 | 原文链接：http://book.gygll6.asia/blog/2266663.sHtML

原标题：golang 系统设计 protobuf 枚举类型规范写法
简介：golang 互斥锁读写锁并发安全，互斥锁读写锁实操，保护共享变量，解决多协程并发读写数据竞争。
 | 原文链接：http://book.gygll6.asia/blog/3317015.sHtML

原标题：性能复盘：系统上下文切换过高性能下降调优
简介：golang go‑zero 框架项目快速搭建，go‑zero 脚手架生成微服务项目，api rpc 服务快速开发。
 | 原文链接：http://book.gygll6.asia/blog/8268492.sHtML

原标题：入门实践：实现简单文件读写功能
简介：CORS 跨域问题多种解决方案，对比 CORS、代理等不同跨域方案优缺点，根据业务场景选择合适的跨域处理方式。
 | 原文链接：http://book.gygll6.asia/blog/4537997.sHtML

原标题：死信队列处理消息阻塞业务
简介：进程线程并发基础概念讲解，区分进程与线程，讲解调度逻辑，理解并发执行原理，为高并发业务开发打基础。
 | 原文链接：http://book.gygll6.asia/blog/8331055.sHtML

原标题：避坑：CookieSecure属性造成测试环境登录失败
简介：golang ip 限流黑名单实现方案，基于 IP 做限流与黑名单，拦截恶意 IP 访问，保护接口服务。
 | 原文链接：http://book.gygll6.asia/blog/3154769.sHtML

原标题：Architecture：静态资源分发CDN整体架构思路
简介：golang rabbitmq go 客户端生产消费，streadway/amqp 实现 rabbitmq 生产者消费者，队列交换机绑定。
 | 原文链接：http://book.gygll6.asia/blog/5906193.sHtML

原标题：golang 配置热更新不重启服务
简介：nodejs http 服务性能调优实战，调优 Node HTTP 服务内核参数，连接复用，提升接口并发处理能力。
 | 原文链接：http://book.gygll6.asia/blog/5803903.sHtML

原标题：数据库连接池参数调优
简介：golang go ring 环形容器循环队列，ring 环形链表实现循环队列，环形缓冲区业务场景。
 | 原文链接：http://book.gygll6.asia/blog/4244241.sHtML

原标题：golang 分布式 ID 雪花算法实现
简介：golang go 包循环导入报错解决，A 导入 B B 导入 A，循环导入报错，重构代码拆分包消除循环依赖。
 | 原文链接：http://book.gygll6.asia/blog/4170083.sHtML

原标题：线上接口超时故障排查思路
简介：golang 大文件 HTTP 流式上传接收，服务端流式接收上传文件，不全部加载内存，防止大文件 OOM 崩溃。
 | 原文链接：http://book.gygll6.asia/blog/2349251.sHtML

原标题：新手教程：Git撤销错误提交的几种常用方式
简介：请求工具封装统一异常处理，对网络请求做二次封装，统一捕获各类请求异常，标准化接口返回格式。
 | 原文链接：http://book.gygll6.asia/blog/6183240.sHtML

原标题：项目目录结构规范化最佳实践
简介：golang go 整洁架构代码组织实践，整洁架构依赖向内，解耦业务逻辑与外部基础设施。
 | 原文链接：http://book.gygll6.asia/blog/2673757.sHtML

原标题：GET POST 接口请求参数处理
简介：golang prometheus 指标埋点开发，业务埋点计数器、仪表盘、直方图，对接 prometheus 采集监控指标。
 | 原文链接：http://book.gygll6.asia/blog/5405704.sHtML

原标题：golang ci 流水线自动部署 k8s 示例
简介：golang gin 参数绑定 query form json，掌握 Gin 多种参数绑定方式，适配不同请求格式参数读取。
 | 原文链接：http://book.gygll6.asia/blog/1346310.sHtML

原标题：golang 系统设计版本号语义化规范讲解
简介：GC 垃圾回收优化降低 CPU 占用，调整 GC 参数，优化对象创建销毁，降低垃圾回收带来 CPU 开销。
 | 原文链接：http://book.gygll6.asia/blog/8271151.sHtML

原标题：服务启动依赖顺序配置正确
简介：golang k8s 客户端 client‑go 简单示例，client‑go 操作 k8s 资源，增删改查 pod deployment 等资源对象。
 | 原文链接：http://book.gygll6.asia/blog/2548081.sHtML

原标题：Git 误删提交代码恢复找回
简介：前端打包分包加载提速方案，前端打包做代码分包，拆分大 bundle，页面按需加载，提升首屏加载速度。
 | 原文链接：http://book.gygll6.asia/blog/9961023.sHtML

原标题：Troubleshooting：k8s镜像拉取失败镜像仓库网络问题
简介：golang redis bloom 布隆过滤器 go‑redis，go‑redis 布隆过滤器，海量数据判断是否存在，减少数据库查询。
 | 原文链接：http://book.gygll6.asia/blog/5294780.sHtML

原标题：踩坑记录：分页逻辑错误造成数据重复输出
简介：golang testing.TB Helper 标记辅助函数，t.Helper 标记辅助函数，报错打印真实调用位置。
 | 原文链接：http://book.gygll6.asia/blog/8442503.sHtML

原标题：golang 系统设计代码评审 checklist 清单
简介：批量数据处理脚本编写技巧，编写脚本批量处理大量业务数据，循环处理、分批执行，提升数据处理效率。
 | 原文链接：http://book.gygll6.asia/blog/0433161.sHtML

原标题：golang consul 健康检查服务注册
简介：golang rate‑limiter 限流组件，封装通用 Go 限流组件，支持多算法，业务接口直接复用调用。
 | 原文链接：http://book.gygll6.asia/blog/6499249.sHtML

原标题：Dockerfile 编写容器打包实战
简介：golang go 应用内存使用优化手段，减少对象分配，复用对象，降低 GC 压力，减少 GC 停顿时间。
 | 原文链接：http://book.gygll6.asia/blog/6574442.sHtML

原标题：golang toml 配置文件解析教程
简介：版本升级服务启动失败处理，版本更新之后服务无法启动，对比新旧版本配置、依赖差异，完成故障修复。
 | 原文链接：http://book.gygll6.asia/blog/1605724.sHtML

原标题：程序日志分级输出规范实践
简介：系统时间同步定时任务偏移，同步服务器系统时间，防止时间偏移，避免定时任务执行时间错乱。
 | 原文链接：http://book.gygll6.asia/blog/5766343.sHtML

原标题：golang 系统设计 README 开源文档模板
简介：golang redis 过期时间处理技巧，设置 key 过期，监控过期事件，基于过期特性实现业务缓存逻辑。
 | 原文链接：http://book.gygll6.asia/blog/5900601.sHtML

原标题：踩坑：消息队列消息堆积，消费者处理能力不足
简介：消息队列生产消费模型入门，讲解消息队列生产、存储、消费流程，理解异步解耦、削峰，掌握消息队列基础概念。
 | 原文链接：http://book.gygll6.asia/blog/5547078.sHtML

原标题：方案设计：统一ID生成服务架构对比雪花算法
简介：布隆过滤器误判问题修正，调整布隆过滤器参数，降低误判概率，保证业务去重逻辑准确。
 | 原文链接：http://book.gygll6.asia/blog/4836816.sHtML

原标题：设计思考：容器化业务应用架构改造要点
简介：golang mock 单元测试编写技巧，单元测试 mock 外部依赖，隔离数据库网络，只测试业务逻辑本身。
 | 原文链接：http://book.gygll6.asia/blog/3153694.sHtML

原标题：缓存过期打散防止缓存雪崩
简介：golang map 并发读写 panic 解决方案，map 非并发安全，讲解加锁、sync.map 方案解决并发读写崩溃。
 | 原文链接：http://book.gygll6.asia/blog/5635897.sHtML

原标题：架构复盘：网关层、应用层、数据库层层限流架构
简介：集成测试业务流程编写示例，编写业务流程集成测试，覆盖完整业务链路，验证模块之间协同工作是否正常。
 | 原文链接：http://book.gygll6.asia/blog/6035359.sHtML

原标题：架构笔记：WebSocket大规模连接服务架构
简介：JWT 令牌过期异常处理，捕获 JWT 过期、篡改异常，编写业务处理逻辑，引导用户重新获取令牌。
 | 原文链接：http://book.gygll6.asia/blog/9199217.sHtML

原标题：Practice：实现多级缓存本地缓存+Redis实践
简介：GitHub 项目提交推送完整流程讲解，从仓库初始化到提交推送远程仓库，梳理全流程细节，避开新手高频错误。
 | 原文链接：http://book.gygll6.asia/blog/5246561.sHtML

四、架构设计｜Architecture
原标题：进程线程并发基础概念讲解
简介：golang excel 生成导出高性能方案，excelize 流式生成 excel，百万行数据导出，规避内存溢出。
 | 原文链接：http://book.gygll6.asia/blog/4569353.sHtML

原标题：复盘总结：缓存改造业务落地踩坑复盘
简介：golang 参数校验业务接口处理，Go 接口入参参数校验，拦截非法入参，减少业务层参数判断代码。
 | 原文链接：http://book.gygll6.asia/blog/7910646.sHtML

原标题：Hands‑on：简易ID生成雪花算法完整实现
简介：Dockerfile 编写容器打包实战，讲解 Dockerfile 指令含义，编写镜像构建脚本，将本地项目打包成可分发容器镜像。
 | 原文链接：http://book.gygll6.asia/blog/6481212.sHtML

原标题：安全组端口开放网络访问
简介：golang go 服务蓝绿发布实践思路，蓝绿两套实例，流量一键切换，回滚快速降低发布风险。
 | 原文链接：http://book.gygll6.asia/blog/9619563.sHtML

原标题：golang alertmanager 钉钉告警推送
简介：前端 pdf 预览渲染方案对比，对比前端 PDF 预览库，分析性能、兼容性，给出业务选型参考。
 | 原文链接：http://book.gygll6.asia/blog/7486509.sHtML

原标题：实践：静态站点自动化部署到GitHubPages
简介：golang 文件上传下载接口开发，Go 开发文件上传下载接口，校验文件，处理文件读写存储逻辑。
 | 原文链接：http://book.gygll6.asia/blog/3640974.sHtML

原标题：复盘总结：分布式系统常见坑点汇总清单
简介：缓存基础原理与简单代码实现，讲解缓存设计思路，编写简易缓存逻辑，减少重复计算与重复请求，提升程序响应速度。
 | 原文链接：http://book.gygll6.asia/blog/5614396.sHtML

原标题：短信服务封装失败自动重试
简介：golang go 程序运行时动态修改配置，运行时热加载配置结构体，原子更新保证并发读取安全。
 | 原文链接：http://book.gygll6.asia/blog/7153769.sHtML

原标题：golang mock 单元测试编写技巧
简介：接口限流逻辑简单模拟实现，编写简易限流逻辑，限制接口访问频次，保护服务，避免短时间大量请求压垮系统。
 | 原文链接：http://book.gygll6.asia/blog/0127059.sHtML

原标题：安全实践：接口速率限制防止暴力破解
简介：golang http 中间件洋葱模型原理，理解 go http 中间件洋葱模型，请求响应流转顺序，编写自定义中间件。
 | 原文链接：http://book.gygll6.asia/blog/2394162.sHtML

原标题：golang 系统设计并发控制协程池任务池实现
简介：golang 性能压测 wr 工具实操指南，wr 压测工具对 Go 接口压测，观察 QPS 延迟，定位接口性能瓶颈。
 | 原文链接：http://book.gygll6.asia/blog/4830621.sHtML

原标题：golang 系统设计告警风暴抑制合并降噪方案
简介：内存泄漏定位分析完整流程，分享内存泄漏排查步骤，定位没有释放的对象，解决内存持续上涨问题。
 | 原文链接：http://book.gygll6.asia/blog/6374909.sHtML

原标题：golang mysql 长连接短连接对比
简介：golang pdf 生成 go 服务端生成 pdf，服务端动态生成 pdf 报表文件，直接输出下载给到前端。
 | 原文链接：http://book.gygll6.asia/blog/8326866.sHtML

原标题：快速上手简单的限流逻辑模拟实现
简介：golang go race 竞态检测工具，‑race 检测数据竞争，编译运行检测并发读写数据竞争 bug。
 | 原文链接：http://book.gygll6.asia/blog/2348066.sHtML

原标题：实战：基于内存实现简单消息广播组件
简介：golang race 检测器性能开销，race 检测器有性能损耗，只用于测试环境，禁止生产开启 race。
 | 原文链接：http://book.gygll6.asia/blog/0758453.sHtML

原标题：坑点：Git仓库过大，clone速度极慢解决方案
简介：golang ip2regionIP 地址解析实战，集成 ip2region 库，根据 IP 解析归属地城市，实现 IP 地域解析。
 | 原文链接：http://book.gygll6.asia/blog/1763913.sHtML

原标题：踩坑记录：CPU亲和配置不合理多核心负载不均
简介：golang sync/atomic 原子操作使用注意，理解原子操作内存顺序，规避原子操作错误使用带来 bug。
 | 原文链接：http://book.gygll6.asia/blog/2909435.sHtML

原标题：多规则数据脱敏组件开发
简介：golang go work 多模块本地开发，go work 多模块本地同时开发，本地模块互相引用，无需推送仓库。
 | 原文链接：http://book.gygll6.asia/blog/8963313.sHtML

?
