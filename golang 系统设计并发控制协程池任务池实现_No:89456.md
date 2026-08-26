最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计并发控制协程池任务池实现
简介：限流组件计数器令牌桶模式实现，实现计数器、令牌桶两种限流算法，封装可复用限流组件。
 | 原文链接：http://wiki.b2hisu.asia/arts/042946.Doc

原标题：golang 系统设计分布式锁看门狗续期原理理解
简介：golang http MaxHeaderBytes 限制请求头，设置 http 最大请求头大小，防止超大 header 攻击。
 | 原文链接：http://wiki.b2hisu.asia/arts/801474.Doc

原标题：golang 系统设计日志采样降低存储开销方案
简介：分布式锁失效问题排查修复，分析分布式锁失效场景，修复锁超时、续期问题，保证锁逻辑可靠。
 | 原文链接：http://wiki.b2hisu.asia/arts/671813.Doc

原标题：OpenSource：开源项目贡献者协作流程规范
简介：golang lru 缓存淘汰算法编写，手写 LRU 缓存淘汰算法，实现本地缓存，淘汰最久未使用数据。
 | 原文链接：http://wiki.b2hisu.asia/arts/483859.Doc

原标题：golang 系统设计代码评审高效沟通原则思路
简介：限流规则误拦截正常请求修复，修正限流规则阈值，避免合法用户被限流拦截，兼顾防护与可用性。
 | 原文链接：http://wiki.b2hisu.asia/arts/151344.Doc

原标题：golang 重试退避机制代码实现
简介：golang delve 远程调试 go 线上程序，delve 远程调试，线上环境附加进程调试排查线上 bug。
 | 原文链接：http://wiki.b2hisu.asia/arts/212722.Doc

原标题：设计思考：系统降级开关架构设计快速切流量
简介：golang 内存 dump 线上堆快照采集，线上生成内存 dump 文件，线下分析，定位内存泄漏问题。
 | 原文链接：http://wiki.b2hisu.asia/arts/405524.Doc

原标题：golang 系统设计大事务拆分实战思路
简介：golang 消息队列 kafka 消费开发，Go 开发 Kafka 消费程序，消费消息执行业务，理解 Kafka 消费逻辑。
 | 原文链接：http://wiki.b2hisu.asia/arts/448384.Doc

原标题：开发记录：网关实现接口鉴权、限流、日志打印
简介：golang go 程序守护进程实现思路，go 程序不做 daemon 化，依靠 systemd pm2 k8s 实现进程守护。
 | 原文链接：http://wiki.b2hisu.asia/arts/973552.Doc

原标题：方案对比：RPC、HTTP、gRPC场景选型分析
简介：图片上传预览格式大小处理，实现图片上传接口，校验文件格式、大小，完成上传后预览处理。
 | 原文链接：http://wiki.b2hisu.asia/arts/497350.Doc

原标题：golang 系统设计定时任务分布式锁防重复执行
简介：golang jaeger 链路追踪部署对接，jaeger 接收 opentelemetry 链路数据，可视化完整调用链路。
 | 原文链接：http://wiki.b2hisu.asia/arts/834104.Doc

原标题：golang 系统设计 ide 配置 go 开发效率提升技巧
简介：golang go 爬虫异步并发抓取，协程池控制并发抓取网页，多协程采集，提升爬虫采集速度。
 | 原文链接：http://wiki.b2hisu.asia/arts/160419.Doc

原标题：Nginx 静态代理负载均衡全套配置
简介：数据库连接及时关闭连接泄漏，确保数据库连接使用完毕释放归还连接池，杜绝连接泄漏耗尽连接。
 | 原文链接：http://wiki.b2hisu.asia/arts/876266.Doc

原标题：安全实践：接口错误信息不要暴露内部细节
简介：容器软链接文件权限修复，修复容器内软链接文件权限，让程序能够正常读取软链接指向的文件。
 | 原文链接：http://wiki.b2hisu.asia/arts/755339.Doc

原标题：代码格式化工具团队统一风格
简介：golang kitex 超时重试熔断配置，kitex 配置调用超时、重试、熔断策略，保障微服务调用稳定性。
 | 原文链接：http://wiki.b2hisu.asia/arts/645071.Doc

原标题：golang mongodb 事务多文档使用
简介：golang go math 大数高精度计算，math/big 处理超大整数、高精度浮点数，金额大数运算。
 | 原文链接：http://wiki.b2hisu.asia/arts/971399.Doc

原标题：golang 布隆过滤器实现去重
简介：前后端交互跨域问题完整处理，讲解跨域产生原理，列举多种解决方案，适配开发、生产不同环境的跨域处理。
 | 原文链接：http://wiki.b2hisu.asia/arts/617878.Doc

原标题：快速入门gRPC基础概念与简单示例
简介：golang defer 执行顺序与坑点，defer 后进先出，循环内部 defer 陷阱，资源释放正确写法。
 | 原文链接：http://wiki.b2hisu.asia/arts/331173.Doc

原标题：业务接口幂等完整落地案例
简介：手写简易 RPC 服务通信原型，手写极简 RPC 原型，理解服务注册、网络传输、方法调用底层逻辑。
 | 原文链接：http://wiki.b2hisu.asia/arts/945301.Doc

原标题：golang 系统设计 websocket 协议原理梳理
简介：容器软链接文件权限修复，修复容器内软链接文件权限，让程序能够正常读取软链接指向的文件。
 | 原文链接：http://wiki.b2hisu.asia/arts/146271.Doc

原标题：从零编写简易 CLI 命令行工具
简介：golang http 服务优雅关闭完整示例，接收终止信号，停止接收新请求，等待现有请求处理完毕后退出服务。
 | 原文链接：http://wiki.b2hisu.asia/arts/000595.Doc

原标题：golang 大文件 http 下载服务
简介：golang 消息队列实现事务消息方案，基于 kafka 实现事务消息，业务执行成功才对外投递消息。
 | 原文链接：http://wiki.b2hisu.asia/arts/236937.Doc

原标题：golang prometheus metrics 埋点开发
简介：网关集成鉴权限流日志一体化，在网关层整合鉴权、限流、请求日志，统一对入口请求做管控处理。
 | 原文链接：http://wiki.b2hisu.asia/arts/596128.Doc

原标题：golang 系统设计缓存预热脚本编写实操
简介：golang go mod tidy 依赖清理，go mod tidy 自动增删依赖，整理 go.mod go.sum 文件。
 | 原文链接：http://wiki.b2hisu.asia/arts/429395.Doc

原标题：golang 系统设计蓝绿发布滚动发布对比
简介：golang grpc 重试机制客户端配置，grpc 客户端配置重试策略，临时故障自动重试，提升调用稳定性。
 | 原文链接：http://wiki.b2hisu.asia/arts/619827.Doc

原标题：golang k8s service 服务暴露几种类型
简介：golang cgo 调用 C 语言代码示例，cgo 调用 C 函数，go 与 C 互相调用，对接 C 语言库能力。
 | 原文链接：http://wiki.b2hisu.asia/arts/170781.Doc

原标题：架构复盘：RPC框架架构超时重试设计要点
简介：golang go 泛型使用避坑注意点，泛型与 interface 区别，泛型性能，什么时候适合使用泛型。
 | 原文链接：http://wiki.b2hisu.asia/arts/903569.Doc

原标题：golang 系统设计字段命名类型选择最佳实践
简介：开发生产环境资源路径统一，对齐开发环境与生产环境资源路径，防止本地正常上线后资源找不到。
 | 原文链接：http://wiki.b2hisu.asia/arts/642396.Doc

原标题：前端防抖节流高频事件处理
简介：golang uuid 生成多种版本实现，生成 uuid v1 v4，生成唯一标识，业务用于单据编号场景。
 | 原文链接：http://wiki.b2hisu.asia/arts/858305.Doc

原标题：golang grafana 面板变量模板制作
简介：golang go mod tidy 依赖清理，go mod tidy 自动增删依赖，整理 go.mod go.sum 文件。
 | 原文链接：http://wiki.b2hisu.asia/arts/237736.Doc

原标题：安全复盘：Redis命令注入风险防护手段
简介：golang atomic 原子操作整数，atomic 加减比较交换，无锁更新整型变量，简单计数器场景。
 | 原文链接：http://wiki.b2hisu.asia/arts/152119.Doc

原标题：golang redis pipeline 原子性说明
简介：golang go 程序容器资源 requests limits，设置容器 cpu 内存配额，防止实例抢占集群资源，稳定调度。
 | 原文链接：http://wiki.b2hisu.asia/arts/787467.Doc

原标题：OOMKilled 容器被杀完整排查
简介：Nginx 静态代理负载均衡全套配置，一套 Nginx 配置示例，覆盖静态资源、反向代理、负载均衡场景。
 | 原文链接：http://wiki.b2hisu.asia/arts/953513.Doc

原标题：golang md5 sha 加密工具实现
简介：golang go 终端 pty 伪终端操作，pty 启动子进程，模拟终端交互，实现交互式命令调用。
 | 原文链接：http://wiki.b2hisu.asia/arts/422129.Doc

原标题：﻿【GettingStarted】从零搭建本地开发环境完整指南
简介：golang nilnil interface 陷阱复现，interface 包含类型不为 nil 值为 nil，判 ==nil 返回 false 经典坑。
 | 原文链接：http://wiki.b2hisu.asia/arts/683150.Doc

原标题：排错：静态资源404，打包路径配置错误
简介：编译打包产物依赖分析解读，分析打包之后产物组成，理清运行依赖文件，排查打包后缺失文件问题。
 | 原文链接：http://wiki.b2hisu.asia/arts/315032.Doc

原标题：Debug：异步任务堆积，服务响应越来越慢
简介：golang go 时间 time.Timer time.Ticker，定时器与周期定时器，Stop Reset 正确使用，防止资源泄漏。
 | 原文链接：http://wiki.b2hisu.asia/arts/470814.Doc

原标题：安全实践：接口速率限制防止暴力破解
简介：golang k8s 客户端 client‑go 简单示例，client‑go 操作 k8s 资源，增删改查 pod deployment 等资源对象。
 | 原文链接：http://wiki.b2hisu.asia/arts/887095.Doc

原标题：golang k8s secret 加密敏感信息
简介：依赖版本冲突兼容修复方案，定位依赖版本冲突根源，通过版本约束、替换包，解决版本不兼容运行报错。
 | 原文链接：http://wiki.b2hisu.asia/arts/721952.Doc

原标题：golang 系统设计混沌测试故障注入简单示例
简介：全局异常处理器接口返回统一，接入全局异常捕获，拦截业务全部异常，对外输出统一格式返回值。
 | 原文链接：http://wiki.b2hisu.asia/arts/155341.Doc


二、踩坑排错｜Troubleshooting
原标题：简易网关请求路由过滤模拟
简介：无用对象回收抑制内存上涨，优化对象生命周期，及时释放不再使用对象，抑制内存持续不断增长。
 | 原文链接：http://wiki.b2hisu.asia/arts/176610.Doc

原标题：golang 系统设计分库分表 id 全局生成策略
简介：golang http client Transport 参数调优，Transport 最大连接空闲连接，TLS 配置，http 客户端调优。
 | 原文链接：http://wiki.b2hisu.asia/arts/755506.Doc

原标题：golang 系统设计性能优化通用思路方法论
简介：golang redis 锁超时业务处理，Redis 分布式锁超时问题处理，锁续期逻辑，防止业务未完成锁提前释放。
 | 原文链接：http://wiki.b2hisu.asia/arts/293540.Doc

原标题：实践：接口参数自动校验业务落地实践
简介：golang 数据库 ORM 框架选型对比，gorm xorm sqlx 对比各 ORM 优缺点，根据业务场景选型。
 | 原文链接：http://wiki.b2hisu.asia/arts/974501.Doc

原标题：踩坑记录：文件描述符不足，上传功能随机失败
简介：配置外部化线上部署防错误，把配置从代码剥离，外部传入配置，修改配置不需要重新打包构建。
 | 原文链接：http://wiki.b2hisu.asia/arts/895633.Doc

原标题：快速入门ORM，实现简单数据库增删改查
简介：golang html 模板防 xss 自动转义，理解 go html/template 自动转义，防止 XSS 攻击，处理不需要转义场景。
 | 原文链接：http://wiki.b2hisu.asia/arts/443097.Doc

原标题：安全复盘：业务登录暴力破解防护完整方案
简介：golang net.Listener 包装自定义监听器，包装 Listener 做连接计数、连接拦截，扩展网络能力。
 | 原文链接：http://wiki.b2hisu.asia/arts/284117.Doc

原标题：方案设计：异步解耦业务架构边界识别
简介：golang go 无锁并发编程技巧，原子操作 sync/atomic，简单场景替换锁，提升并发性能。
 | 原文链接：http://wiki.b2hisu.asia/arts/175808.Doc

原标题：实践：API接口文档自动导出离线文档实践
简介：golang 服务注册 etcd 简单示例，etcd 实现服务注册发现，微服务实例注册元数据，客户端发现节点。
 | 原文链接：http://wiki.b2hisu.asia/arts/371275.Doc

原标题：golang 系统设计容器 OOM 故障完整排查
简介：golang go 服务蓝绿发布实践思路，蓝绿两套实例，流量一键切换，回滚快速降低发布风险。
 | 原文链接：http://wiki.b2hisu.asia/arts/758140.Doc

原标题：排错：前端sourcemap错误线上无法定位报错
简介：golang 系统 IO 阻塞 goroutine 场景，理解系统调用阻塞 M，P 会调度其他 M，掌握 go 调度行为。
 | 原文链接：http://wiki.b2hisu.asia/arts/352221.Doc

原标题：golang docker 部署 redis 配置要点
简介：容器资源限制防止宿主机过载，设置容器 CPU 内存资源上限，避免单个容器耗尽宿主机全部硬件资源。
 | 原文链接：http://wiki.b2hisu.asia/arts/009233.Doc

原标题：golang 系统设计开发环境本地调试最佳实践
简介：百万数据 Excel 导出内存优化，优化大 Excel 导出逻辑，流式输出，避免一次性加载全部数据造成 OOM。
 | 原文链接：http://wiki.b2hisu.asia/arts/746422.Doc

原标题：项目实践：搭建个人API网关最小实现版本
简介：golang kafka 消费者组重平衡避坑，规避消费者组频繁 rebalance，减少消费抖动，保障消息消费稳定性。
 | 原文链接：http://wiki.b2hisu.asia/arts/290384.Doc

原标题：Issue：Nginxkeepalive参数不合理大量TIME_WAIT
简介：业务接口幂等完整落地案例，完整业务场景幂等落地示例，覆盖表单提交、回调、重试各类场景。
 | 原文链接：http://wiki.b2hisu.asia/arts/965031.Doc

原标题：运维笔记：系统监控指标大盘搭建实操
简介：golang 单元测试 table‑driven，表格驱动单元测试写法，批量输入多组测试用例，简化单元测试代码。
 | 原文链接：http://wiki.b2hisu.asia/arts/335839.Doc

原标题：避坑：Spring事务传播行为理解错误事务失效
简介：golang base64 编码解码实操，Go Base64 编码解码示例，处理业务场景 Base64 格式数据转换。
 | 原文链接：http://wiki.b2hisu.asia/arts/495360.Doc

原标题：设计思考：大促系统架构压测改造整体思路
简介：golang 系统调用跟踪 strace 排查 go 程序，strace 跟踪系统调用，定位文件网络 IO 慢的底层原因。
 | 原文链接：http://wiki.b2hisu.asia/arts/455419.Doc

原标题：Hands‑on：简易跨进程通信demo开发实践
简介：golang rate‑limiter 限流组件，封装通用 Go 限流组件，支持多算法，业务接口直接复用调用。
 | 原文链接：http://wiki.b2hisu.asia/arts/968586.Doc

原标题：Performance：避免循环查询N+1问题完整优化
简介：golang panic 崩溃日志完整收集，捕获所有 panic，打印堆栈，记录日志，方便定位崩溃根源。
 | 原文链接：http://wiki.b2hisu.asia/arts/884226.Doc

原标题：手写简易 MQ 理解消息存储消费
简介：golang hmac 签名生成校验示例，hmac 生成消息签名，做接口请求签名，校验数据不被篡改。
 | 原文链接：http://wiki.b2hisu.asia/arts/963386.Doc

原标题：golang 系统设计数据库慢查询治理方案
简介：Nginx 丢失请求头配置修正，修复 Nginx 代理转发丢失请求头配置，保证上游服务拿到完整请求头信息。
 | 原文链接：http://wiki.b2hisu.asia/arts/414514.Doc

原标题：全局时间标准统一逻辑错乱修复
简介：golang grpc metadata 元数据透传，metadata 传递 traceId、鉴权信息，全链路透传上下文信息。
 | 原文链接：http://wiki.b2hisu.asia/arts/488768.Doc

原标题：golang 系统设计大事务拆分实战思路
简介：Redis 分布式锁高并发安全实现，基于 Redis 实现分布式锁，处理锁过期、续期，保障集群并发安全。
 | 原文链接：http://wiki.b2hisu.asia/arts/800045.Doc

原标题：入门实践：使用Git完成第一次代码提交与推送
简介：golang 子进程超时杀死防止挂住，context 控制子进程超时，超时强制杀掉子进程，避免子进程僵尸。
 | 原文链接：http://wiki.b2hisu.asia/arts/713089.Doc

原标题：安全复盘：CSRF跨站请求伪造防护配置
简介：webpack chunk 分包策略详解，讲解 webpack chunk 分包策略，拆分第三方包与业务代码，优化缓存复用。
 | 原文链接：http://wiki.b2hisu.asia/arts/257800.Doc

原标题：Issue：浏览器缓存ServiceWorker导致旧页面常驻
简介：golang consul 服务发现简单示例，对接 Consul 实现服务注册发现，微服务实例自动感知。
 | 原文链接：http://wiki.b2hisu.asia/arts/483977.Doc

原标题：快速入门环境区分：开发、测试、生产环境
简介：nodejs 跨域中间件配置细节，Express 跨域中间件配置细节，处理预检请求，修复偶现跨域失效。
 | 原文链接：http://wiki.b2hisu.asia/arts/332528.Doc

原标题：大事务拆分回滚日志暴涨解决
简介：golang 配置中心 apollo go 客户端，apollo go sdk 读取配置，配置变更自动热更新无需重启服务。
 | 原文链接：http://wiki.b2hisu.asia/arts/505244.Doc

原标题：golang 系统设计数据库连接池调优实践
简介：缓存穿透防护保护数据库，实现缓存穿透防护手段，拦截不存在的数据查询，避免请求直接打穿数据库。
 | 原文链接：http://wiki.b2hisu.asia/arts/889940.Doc

原标题：golang 错误处理最佳实践汇总
简介：golang go select 多路等待 channel，select 等待多个 channel，default 非阻塞，超时等待 channel。
 | 原文链接：http://wiki.b2hisu.asia/arts/010431.Doc

原标题：正则表达式优化 CPU 占满问题
简介：前后端交互跨域问题完整处理，讲解跨域产生原理，列举多种解决方案，适配开发、生产不同环境的跨域处理。
 | 原文链接：http://wiki.b2hisu.asia/arts/454709.Doc

原标题：性能笔记：磁盘IO过高业务优化手段
简介：RPC 报文大小上限调优大请求，调大 RPC 框架报文最大限制，支持传输大体积请求报文不被截断。
 | 原文链接：http://wiki.b2hisu.asia/arts/869707.Doc

原标题：golang 系统设计配置中心核心能力梳理讲解
简介：golang 灰度发布流量权重路由实现，根据权重切分流量，部分流量访问新版本服务，实现灰度发布。
 | 原文链接：http://wiki.b2hisu.asia/arts/717436.Doc

原标题：用户敏感数据脱敏代码实现
简介：接口签名校验防篡改实现，实现请求签名验签逻辑，校验请求参数未被篡改，提升接口调用安全性。
 | 原文链接：http://wiki.b2hisu.asia/arts/209329.Doc

原标题：性能笔记：避免频繁创建销毁对象GC优化
简介：DNS 解析异常第三方调用故障，排查 DNS 解析故障，修复域名解析，恢复第三方接口网络调用。
 | 原文链接：http://wiki.b2hisu.asia/arts/820035.Doc

原标题：golang mysql 连接泄漏检测方法
简介：golang 进程信号捕获 SIGUSR 自定义信号，捕获用户自定义信号，实现线上不重启触发调试、日志切换。
 | 原文链接：http://wiki.b2hisu.asia/arts/006629.Doc

原标题：调优方案：消息队列消费速度优化处理堆积
简介：golang 大文件读取内存优化，Go 流式读取大文件，分块处理，避免大文件一次性加载全部到内存。
 | 原文链接：http://wiki.b2hisu.asia/arts/638864.Doc

原标题：golang 系统设计事务消息 rocketmq 简单原理
简介：不必要字符转义关闭业务异常，关闭多余自动转义逻辑，防止业务数据被错误转义，破坏原始数据。
 | 原文链接：http://wiki.b2hisu.asia/arts/330262.Doc

原标题：调试工具断点调试变量查看技巧
简介：项目构建脚本编译打包解析，解读项目构建脚本，理清编译、压缩、资源复制流程，理解打包后产物如何生成。
 | 原文链接：http://wiki.b2hisu.asia/arts/047391.Doc

三、实战开发｜Practice
原标题：golang 系统设计链路追踪架构简单讲解
简介：golang redis hash 结构业务实战，使用 Redis Hash 存储对象数据，适合对象字段频繁更新业务场景。
 | 原文链接：http://wiki.b2hisu.asia/arts/457739.Doc

原标题：后端分页查询逻辑代码实现
简介：读懂开源项目 README 实用技巧，教你快速解析开源项目说明文档，提取安装、运行、配置关键信息，快速上手项目。
 | 原文链接：http://wiki.b2hisu.asia/arts/465298.Doc

原标题：项目实践：实现数据脱敏组件支持多种脱敏规则
简介：golang 分库分表 id 路由规则设计，分库分表 id 路由算法，id 映射库表，数据均匀打散避免热点分片。
 | 原文链接：http://wiki.b2hisu.asia/arts/866184.Doc

原标题：前后端会话登录状态持久化
简介：golang grpc metadata 元数据透传，metadata 传递 traceId、鉴权信息，全链路透传上下文信息。
 | 原文链接：http://wiki.b2hisu.asia/arts/755238.Doc

原标题：排错：多实例部署session共享失效登录失效
简介：golang make new 关键字使用区别，分清 new 与 make 适用类型，正确初始化切片 map 通道，杜绝 nil 引发 panic。
 | 原文链接：http://wiki.b2hisu.asia/arts/891743.Doc

原标题：开发记录：服务优雅关闭释放资源完整实现
简介：golang bcrypt 密码哈希加密存储，bcrypt 做用户密码哈希，加盐存储密码，保障用户密码安全。
 | 原文链接：http://wiki.b2hisu.asia/arts/177670.Doc

原标题：DevOps：Docker镜像安全扫描集成CI流程
简介：GC 垃圾回收优化降低 CPU 占用，调整 GC 参数，优化对象创建销毁，降低垃圾回收带来 CPU 开销。
 | 原文链接：http://wiki.b2hisu.asia/arts/663840.Doc

原标题：golang 系统设计 id 生成器选型对比
简介：golang io.MultiReader MultiWriter 拼接流，多个 reader 拼接，多 writer 同时写入一份数据。
 | 原文链接：http://wiki.b2hisu.asia/arts/389656.Doc

原标题：golang k8s cronjob 定时任务配置
简介：项目语义化版本号规范管理，遵循语义化版本规范管理项目版本，明确主次版本变更含义。
 | 原文链接：http://wiki.b2hisu.asia/arts/996253.Doc

原标题：golang gorm 预加载关联查询优化
简介：golang tidb 数据库 go 项目适配，go 程序适配 tidb，兼容 mysql 协议，分布式数据库业务开发。
 | 原文链接：http://wiki.b2hisu.asia/arts/580165.Doc

原标题：golang kafka 批量发送消费优化
简介：前端虚拟列表大数据渲染优化，实现虚拟滚动列表，只渲染可视区域 DOM，上万条数据页面流畅渲染。
 | 原文链接：http://wiki.b2hisu.asia/arts/264113.Doc

原标题：跨平台 uniapp 多端开发实操
简介：golang go list 双向链表使用，container/list 双向链表，频繁增删节点业务场景使用。
 | 原文链接：http://wiki.b2hisu.asia/arts/410078.Doc

原标题：浏览器本地存储安全使用技巧
简介：WSL 内存上限限制防止资源耗尽，修改 WSL 内存上限配置，避免 WSL 占用主机大量内存资源。
 | 原文链接：http://wiki.b2hisu.asia/arts/114831.Doc

原标题：实战：搭建本地对象存储兼容S3协议demo
简介：golang redis hash 结构业务实战，使用 Redis Hash 存储对象数据，适合对象字段频繁更新业务场景。
 | 原文链接：http://wiki.b2hisu.asia/arts/973875.Doc

原标题：golang k8s 资源请求限制配置
简介：golang 容器内读取 k8s 配置 configmap，程序读取 k8s configmap 配置，配置与镜像分离便于运维。
 | 原文链接：http://wiki.b2hisu.asia/arts/603019.Doc

原标题：golang 系统设计消息重试次数间隔策略设置
简介：golang aes cbc gcm 模式加密对比，AES‑CBC AES‑GCM 模式加密解密，理解两种模式差异选型。
 | 原文链接：http://wiki.b2hisu.asia/arts/721985.Doc

原标题：Git 代码冲突正确处理方式
简介：golang go 整洁架构代码组织实践，整洁架构依赖向内，解耦业务逻辑与外部基础设施。
 | 原文链接：http://wiki.b2hisu.asia/arts/077898.Doc

原标题：nodejs 定时任务生产环境避坑
简介：跨平台 uniapp 多端开发实操，uniapp 开发一套代码，编译多端，梳理多端差异处理与适配技巧。
 | 原文链接：http://wiki.b2hisu.asia/arts/852557.Doc

原标题：golang http 代理客户端配置
简介：golang 模糊测试 go fuzz 基础编写，Fuzz 测试函数，自动生成随机输入，发现代码崩溃 panic。
 | 原文链接：http://wiki.b2hisu.asia/arts/006364.Doc

原标题：golang 消息死信处理业务逻辑
简介：开发环境变量配置全平台教程，区分 Windows、macOS、Linux 系统，讲解环境变量配置、加载优先级与常见失效原因。
 | 原文链接：http://wiki.b2hisu.asia/arts/407335.Doc

原标题：Issue：操作系统最大打开文件数限制导致报错
简介：golang k8s go 服务 yaml 资源编写，k8s 部署 go 应用 deployment service，健康检查资源限制配置。
 | 原文链接：http://wiki.b2hisu.asia/arts/157755.Doc

原标题：项目实践：实现数据脱敏组件支持多种脱敏规则
简介：消息队列生产消费模型入门，讲解消息队列生产、存储、消费流程，理解异步解耦、削峰，掌握消息队列基础概念。
 | 原文链接：http://wiki.b2hisu.asia/arts/625134.Doc

原标题：架构复盘：业务系统中如何合理使用分库分表
简介：golang 信号触发配置重载实践，收到 SIGUSR1 信号重新加载配置，线上无需重启刷新配置。
 | 原文链接：http://wiki.b2hisu.asia/arts/828473.Doc

原标题：方案设计：统一ID生成服务架构对比雪花算法
简介：golang 错误栈捕获打印方案，捕获错误完整调用堆栈，线上日志输出堆栈，快速定位错误发生代码位置。
 | 原文链接：http://wiki.b2hisu.asia/arts/276295.Doc

原标题：nodejs 单元测试 jest 实操教程
简介：全局异常处理器接口返回统一，接入全局异常捕获，拦截业务全部异常，对外输出统一格式返回值。
 | 原文链接：http://wiki.b2hisu.asia/arts/629561.Doc

原标题：golang 系统设计告警风暴抑制方案实现
简介：nodejs 消息队列消费服务开发，Node 开发消息队列消费端，监听队列消息执行业务逻辑，异步解耦业务。
 | 原文链接：http://wiki.b2hisu.asia/arts/562981.Doc

原标题：性能笔记：操作系统文件句柄、虚拟内存调优
简介：golang sync.Mutex 互斥锁正确模式，互斥锁 defer Unlock，锁粒度控制，避免锁范围过大。
 | 原文链接：http://wiki.b2hisu.asia/arts/287362.Doc

原标题：Security：Web常见安全漏洞原理与修复清单
简介：golang go math 大数高精度计算，math/big 处理超大整数、高精度浮点数，金额大数运算。
 | 原文链接：http://wiki.b2hisu.asia/arts/890565.Doc

原标题：golang 系统设计分表扩容数据平滑迁移思路
简介：golang grpc 客户端流上传数据，客户端流式请求，客户端分批上传数据到服务端，适合大文件传输。
 | 原文链接：http://wiki.b2hisu.asia/arts/932339.Doc

原标题：golang 告警推送钉钉机器人实现
简介：golang lru 缓存淘汰算法编写，手写 LRU 缓存淘汰算法，实现本地缓存，淘汰最久未使用数据。
 | 原文链接：http://wiki.b2hisu.asia/arts/188062.Doc

原标题：golang redis 缓存预热实现思路
简介：接口限流逻辑简单模拟实现，编写简易限流逻辑，限制接口访问频次，保护服务，避免短时间大量请求压垮系统。
 | 原文链接：http://wiki.b2hisu.asia/arts/151395.Doc

原标题：Docker Compose 一键搭建本地栈
简介：golang cgroup 读取容器资源限制，go 程序读取 cgroup，获取容器 cpu 内存限额，适配容器环境。
 | 原文链接：http://wiki.b2hisu.asia/arts/121628.Doc

原标题：Troubleshoot：跨域偶现失败难以复现问题
简介：跨域偶现失败配置修复，解决跨域问题时而复现时而正常，定位配置漏配、请求头异常等隐性问题。
 | 原文链接：http://wiki.b2hisu.asia/arts/343328.Doc

原标题：项目目录结构规范化最佳实践
简介：golang http 服务优雅关闭完整示例，接收终止信号，停止接收新请求，等待现有请求处理完毕后退出服务。
 | 原文链接：http://wiki.b2hisu.asia/arts/933764.Doc

原标题：golang etcd watch 监听配置变更
简介：golang 雪花 id 重复问题排查，排查雪花算法 ID 重复问题，时钟回拨、机器 ID 冲突，给出修复方案。
 | 原文链接：http://wiki.b2hisu.asia/arts/467715.Doc

原标题：不必要字符转义关闭业务异常
简介：golang trace 可视化分析协程阻塞，使用 trace 网页 UI，定位协程阻塞、系统调用阻塞、锁等待。
 | 原文链接：http://wiki.b2hisu.asia/arts/638181.Doc

原标题：磁盘占满服务不可用清理方案
简介：轻量 API 后端接口服务快速开发，快速搭建简易 API 服务，实现基础接口能力，快速支撑小型业务需求。
 | 原文链接：http://wiki.b2hisu.asia/arts/862658.Doc

原标题：消息队列重复消费业务处理
简介：golang 内存持续上涨定位思路，区分内存泄漏、缓存占用、GC 参数不合理，分步定位内存持续走高。
 | 原文链接：http://wiki.b2hisu.asia/arts/793681.Doc

原标题：安全笔记：文件下载接口路径校验安全
简介：golang go 程序抢占调度理解，理解 go 抢占式调度原理，长循环阻塞调度，造成协程调度延迟。
 | 原文链接：http://wiki.b2hisu.asia/arts/935195.Doc

原标题：OpenSource：开源项目README高质量编写指南
简介：golang channel 作为函数参数方向，声明 channel 入参方向，只读 channel 只写 channel 提升代码约束。
 | 原文链接：http://wiki.b2hisu.asia/arts/484128.Doc

四、架构设计｜Architecture
原标题：快速上手简单的限流逻辑模拟实现
简介：golang nats jetstream 持久消息队列，nats jetstream 持久化消息，保证消息不丢失，实现可靠消费。
 | 原文链接：http://wiki.b2hisu.asia/arts/310484.Doc

原标题：踩坑：大报文传输，RPC消息超过大小限制
简介：golang go 版本管理 go install 安装工具，go install 安装指定版本 go 工具，管理本地 go 工具版本。
 | 原文链接：http://wiki.b2hisu.asia/arts/160570.Doc

原标题：线上接口超时故障排查思路
简介：文件批量导入导出功能实现，开发批量导入导出接口，处理大量文件数据，完成业务数据批量迁移与导出。
 | 原文链接：http://wiki.b2hisu.asia/arts/655432.Doc

原标题：网关集成鉴权限流日志一体化
简介：express 请求参数校验处理，接入参数校验库，校验入参，拦截非法参数，提前拦截错误请求。
 | 原文链接：http://wiki.b2hisu.asia/arts/840969.Doc

原标题：Issue：CI脚本超时，构建任务无故终止
简介：静态资源 404 路径打包修复，修复打包后静态资源访问 404，调整资源输出路径，保证资源正常加载。
 | 原文链接：http://wiki.b2hisu.asia/arts/065532.Doc

原标题：golang kafka 消费者组原理讲解
简介：golang aes cbc gcm 模式加密对比，AES‑CBC AES‑GCM 模式加密解密，理解两种模式差异选型。
 | 原文链接：http://wiki.b2hisu.asia/arts/119896.Doc

原标题：实践：实现Redis分布式锁完整可运行代码
简介：golang 雪花算法 workId 自动获取，自动获取机器 workId，不用手动配置，简化分布式 id 部署。
 | 原文链接：http://wiki.b2hisu.asia/arts/826208.Doc

原标题：开源实践：给开源项目写单元测试贡献代码
简介：golang 容器健康检查接口开发，Go 开发 HTTP 健康接口，供容器编排工具探测实例存活状态。
 | 原文链接：http://wiki.b2hisu.asia/arts/874911.Doc

原标题：安全复盘：CSRF跨站请求伪造防护配置
简介：golang mongodb go 驱动实操教程，mongo‑go‑driver 操作 mongodb，文档增删改查聚合查询。
 | 原文链接：http://wiki.b2hisu.asia/arts/087293.Doc

原标题：复盘总结：微服务改造踩坑经验总结记录
简介：golang 容器内读取 k8s 配置 configmap，程序读取 k8s configmap 配置，配置与镜像分离便于运维。
 | 原文链接：http://wiki.b2hisu.asia/arts/048559.Doc

原标题：golang 系统设计 protobuf 枚举类型规范写法
简介：时间同步修复令牌提前过期，服务器时间不同步导致 JWT 令牌提前过期，同步系统时间解决异常。
 | 原文链接：http://wiki.b2hisu.asia/arts/464989.Doc

原标题：开发复盘：内存缓存LRU淘汰策略实现实践
简介：golang map 并发读写 panic 解决方案，map 非并发安全，讲解加锁、sync.map 方案解决并发读写崩溃。
 | 原文链接：http://wiki.b2hisu.asia/arts/515623.Doc

原标题：golang 系统设计读写分离延迟业务兼容
简介：golang 链路追踪简易实现方案，简易链路追踪实现，传递 traceId，记录调用链路，方便排查慢调用。
 | 原文链接：http://wiki.b2hisu.asia/arts/471027.Doc

原标题：golang 系统设计第三方 sdk 二次封装技巧
简介：golang 结构体 json 序列化坑点，梳理 Go 结构体 JSON 序列化高频坑点，字段大小写、零值处理问题。
 | 原文链接：http://wiki.b2hisu.asia/arts/174578.Doc

原标题：DevOps：Docker镜像安全扫描集成CI流程
简介：服务熔断防止故障级联传播，实现服务熔断逻辑，下游故障时快速失败，阻止故障向上游链式扩散。
 | 原文链接：http://wiki.b2hisu.asia/arts/102071.Doc

原标题：前端虚拟列表大数据渲染优化
简介：golang 布隆过滤器实现去重，Go 实现布隆过滤器，海量数据去重，节省内存开销，提升判断效率。
 | 原文链接：http://wiki.b2hisu.asia/arts/597368.Doc

原标题：实战项目：编写Dockerfile多阶段构建减小镜像体积
简介：Spring 事务传播机制配置生效，理解事务传播行为，正确配置，修复事务不生效、事务失效的业务 bug。
 | 原文链接：http://wiki.b2hisu.asia/arts/226300.Doc

原标题：复盘总结：接口重构兼容旧版本改造复盘
简介：golang dns 自定义解析器实现，自定义 dns 解析，指定 dns 服务器，控制域名解析逻辑，适配内网环境。
 | 原文链接：http://wiki.b2hisu.asia/arts/471856.Doc

?
