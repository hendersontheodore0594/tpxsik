最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计代码评审高效沟通原则思路
简介：golang runtime.Gosched 主动让出调度，长计算循环主动 Gosched，让出调度权，防止其他协程饥饿。
 | 原文链接：http://book.jcaolwz.asia/blog/4365580.sHtMl

原标题：坑点：环境配置被打包进镜像引发安全泄露
简介：golang go‑zero 分布式锁组件使用，go‑zero 内置 redis 分布式锁，业务直接调用实现并发控制。
 | 原文链接：http://book.jcaolwz.asia/blog/0683162.sHtMl

原标题：Issue：容器日志驱动配置错误日志全部丢失
简介：golang 互斥锁读写锁并发安全，互斥锁读写锁实操，保护共享变量，解决多协程并发读写数据竞争。
 | 原文链接：http://book.jcaolwz.asia/blog/3424006.sHtMl

原标题：Architecture：静态资源分发CDN整体架构思路
简介：golang redis pipeline 与 txpipeline 区别，区分普通管道与事务管道，根据业务场景选择合适批量执行方案。
 | 原文链接：http://book.jcaolwz.asia/blog/4739011.sHtMl

原标题：记一次限流组件误配置把正常用户拦截
简介：golang os 打开文件 O_APPEND O_CREATE 标志，OpenFile 标志位，控制文件创建追加截断行为。
 | 原文链接：http://book.jcaolwz.asia/blog/6453754.sHtMl

原标题：设计思考：系统容量评估架构前期估算思路
简介：浮点计算精度错误处理方案，讲解浮点数计算精度丢失问题，使用合适数据类型，规避金额计算出错。
 | 原文链接：http://book.jcaolwz.asia/blog/6325173.sHtMl

原标题：golang mongodb 事务多文档使用
简介：golang go time 时区数据库内置，go 内置时区数据库，不用系统时区文件，容器时区不依赖系统。
 | 原文链接：http://book.jcaolwz.asia/blog/9631077.sHtMl

原标题：架构复盘：消息队列在业务系统中边界与最佳实践
简介：WebSocket 断线重连稳定优化，增加 WebSocket 断线自动重连逻辑，处理网络抖动，维持长连接稳定。
 | 原文链接：http://book.jcaolwz.asia/blog/6420234.sHtMl

原标题：Practice：实现定时任务动态启停管理接口
简介：nestjs 拦截器过滤器管道实战，实操 Nest 拦截器、异常过滤器、管道校验，处理请求与响应统一逻辑。
 | 原文链接：http://book.jcaolwz.asia/blog/0672487.sHtMl

原标题：Issue：文件句柄耗尽，服务缓慢卡死复盘
简介：缓存基础原理与简单代码实现，讲解缓存设计思路，编写简易缓存逻辑，减少重复计算与重复请求，提升程序响应速度。
 | 原文链接：http://book.jcaolwz.asia/blog/1270387.sHtMl

原标题：golang 系统设计消息 key 选择保证顺序性方案
简介：golang 读写分离 gorm 实现主从切换，gorm 配置主库写入从库查询，读写分离分担数据库查询压力。
 | 原文链接：http://book.jcaolwz.asia/blog/4731108.sHtMl

原标题：部署复盘：GitHubActions完整自动化配置
简介：前端打包产物体积压缩优化，多手段压缩前端打包产物，移除无用代码，压缩资源，提升页面加载速度。
 | 原文链接：http://book.jcaolwz.asia/blog/8631155.sHtMl

原标题：架构笔记：批量任务系统架构防重复、断点续跑
简介：golang gorm 原生 SQL 执行处理，复杂场景执行原生 SQL，处理返回结果集，兼顾性能与灵活性。
 | 原文链接：http://book.jcaolwz.asia/blog/0890264.sHtMl

原标题：golang channel 通道并发处理
简介：golang sync.Pool 对象池复用对象，sync.Pool 复用临时对象，减少内存分配，降低 GC 频率提升性能。
 | 原文链接：http://book.jcaolwz.asia/blog/2610828.sHtMl

原标题：优化实践：LRU本地缓存优化热点访问性能
简介：开发测试生产多环境配置区分，讲解三套环境配置分离思路，配置文件隔离，防止开发配置泄露到生产环境。
 | 原文链接：http://book.jcaolwz.asia/blog/3028607.sHtMl

原标题：golang 系统设计技术方案文档模板参考
简介：Git 误提交撤销回退实操教程，演示多种撤销提交方式，区分已经推送远程和本地未提交场景，处理误提交代码。
 | 原文链接：http://book.jcaolwz.asia/blog/6416484.sHtMl

原标题：golang 系统设计分表跨表 join 业务处理方案
简介：TCP 心跳检测清理僵死连接，开启 TCP 心跳机制，自动清理僵死无效连接，释放连接资源。
 | 原文链接：http://book.jcaolwz.asia/blog/7085346.sHtMl

原标题：性能笔记：避免频繁创建销毁对象GC优化
简介：golang cpu pprof 性能分析实操，使用 pprof 采集 CPU 性能数据，定位 CPU 高占用函数，做性能优化。
 | 原文链接：http://book.jcaolwz.asia/blog/4842761.sHtMl

原标题：架构笔记：冷热数据分离架构设计与迁移
简介：极简方式搭建个人技术文档站点，使用轻量化工具快速部署文档站点，支持 markdown 编写，实现知识沉淀与对外分享。
 | 原文链接：http://book.jcaolwz.asia/blog/7851906.sHtMl

原标题：Debug：DNS缓存TTL设置不当服务切换无法生效
简介：服务器 Swap 关闭提升响应速度，关闭服务器 Swap 交换分区，避免内存交换磁盘拖慢程序响应性能。
 | 原文链接：http://book.jcaolwz.asia/blog/9612107.sHtMl

原标题：实践：OpenAPI自动生成接口文档完整实践
简介：golang rabbitmq 死信队列延迟消息，rabbitmq 实现死信、延迟消息，处理延时业务场景。
 | 原文链接：http://book.jcaolwz.asia/blog/2615022.sHtMl

原标题：golang viper 配置热更新实操
简介：golang grpc 拦截器开发鉴权日志，开发 grpc 服务端拦截器，统一做鉴权、日志打印、异常捕获处理。
 | 原文链接：http://book.jcaolwz.asia/blog/3606385.sHtMl

原标题：pnpm 包管理工具实战避坑指南
简介：golang 环境变量读取与类型转换，读取系统环境变量，做类型转换默认值处理，适配多环境部署。
 | 原文链接：http://book.jcaolwz.asia/blog/9716370.sHtMl

原标题：Performance：避免循环查询N+1问题完整优化
简介：golang go 符号表与调试信息取舍，区分生产环境调试符号取舍，平衡镜像体积与故障排查能力。
 | 原文链接：http://book.jcaolwz.asia/blog/9277053.sHtMl

原标题：开发复盘：长轮询接口实现服务端消息推送
简介：golang mysql 长连接检测保活设置，配置 mysql 连接保活检测，剔除失效连接，避免拿到断开无效数据库连接。
 | 原文链接：http://book.jcaolwz.asia/blog/8189268.sHtMl

原标题：Docker 容器网络不通排查
简介：golang go 模板缓存预编译模板，预编译 html 模板，程序启动加载，避免每次请求解析模板损耗性能。
 | 原文链接：http://book.jcaolwz.asia/blog/4140035.sHtMl

原标题：golang 系统设计混沌测试简单场景模拟实现
简介：golang gin 参数绑定 query form json，掌握 Gin 多种参数绑定方式，适配不同请求格式参数读取。
 | 原文链接：http://book.jcaolwz.asia/blog/9377643.sHtMl

原标题：入门实践：简易导出导入文件功能实现
简介：golang net.Conn 包装自定义连接，包装 net.Conn，统计读写字节，日志打印，超时控制。
 | 原文链接：http://book.jcaolwz.asia/blog/8543838.sHtMl

原标题：golang http 请求重试封装工具
简介：端口占用释放资源重启服务，查找占用端口进程，结束占用进程，释放端口，让服务能够正常启动监听。
 | 原文链接：http://book.jcaolwz.asia/blog/6042314.sHtMl

原标题：跨库查询性能优化处理
简介：golang context.WithTimeout 超时上下文，WithTimeout 设置超时时间，超时自动 cancel 释放协程。
 | 原文链接：http://book.jcaolwz.asia/blog/1154011.sHtMl

原标题：新手教程：gitrebase基础使用与风险提示
简介：golang go 锁竞争导致 CPU 飙升，识别锁竞争场景，减少锁粒度，优化并发逻辑降低 CPU 开销。
 | 原文链接：http://book.jcaolwz.asia/blog/0397111.sHtMl

原标题：Issue：开源项目升级大版本后API不兼容踩坑
简介：golang rsa 公钥加密私钥解密，rsa 非对称加密，大文件分块加密，处理非对称加密长度限制。
 | 原文链接：http://book.jcaolwz.asia/blog/4199350.sHtMl

原标题：pnpm 包管理工具实战避坑指南
简介：OOMKilled 容器被杀完整排查，排查容器被 OOM 终止完整流程，区分程序内存泄露和容器内存限制过小。
 | 原文链接：http://book.jcaolwz.asia/blog/4261082.sHtMl

原标题：零基础理解幂等性基础概念与场景
简介：golang make new 关键字使用区别，分清 new 与 make 适用类型，正确初始化切片 map 通道，杜绝 nil 引发 panic。
 | 原文链接：http://book.jcaolwz.asia/blog/9465611.sHtMl

原标题：Security：开源项目安全审计简易检查清单
简介：golang 数据库 ORM 框架选型对比，gorm xorm sqlx 对比各 ORM 优缺点，根据业务场景选型。
 | 原文链接：http://book.jcaolwz.asia/blog/3298279.sHtMl

原标题：golang 日志 zap 结构化日志实践
简介：GitHub Markdown 文档语法汇总，整理 Markdown 常用语法，编写仓库 README、文档，提升开源项目文档排版质量。
 | 原文链接：http://book.jcaolwz.asia/blog/7193575.sHtMl

原标题：golang 系统设计单元测试编写原则最佳实践
简介：golang 雪花算法 workId 自动获取，自动获取机器 workId，不用手动配置，简化分布式 id 部署。
 | 原文链接：http://book.jcaolwz.asia/blog/2567516.sHtMl

原标题：避坑：文件锁处理不当多进程竞争死锁
简介：服务器 Swap 关闭提升响应速度，关闭服务器 Swap 交换分区，避免内存交换磁盘拖慢程序响应性能。
 | 原文链接：http://book.jcaolwz.asia/blog/4504365.sHtMl

原标题：golang 系统设计 sql 注入 xss 防护实践
简介：文件描述符优化进程卡死修复，及时关闭文件句柄，控制打开文件数量，解决文件句柄耗尽进程卡死。
 | 原文链接：http://book.jcaolwz.asia/blog/1559374.sHtMl

原标题：部署复盘：配置不要硬编码进镜像最佳实践
简介：golang go 测试 t.Run 子测试分组，t.Run 实现子测试，分组执行用例，输出分组测试结果。
 | 原文链接：http://book.jcaolwz.asia/blog/9286297.sHtMl


二、踩坑排错｜Troubleshooting
原标题：架构复盘：供应链安全架构依赖包风险治理
简介：golang go 程序守护进程实现思路，go 程序不做 daemon 化，依靠 systemd pm2 k8s 实现进程守护。
 | 原文链接：http://book.jcaolwz.asia/blog/0824964.sHtMl

原标题：开发测试生产多环境配置区分
简介：express 中间件开发业务实践，开发 Express 自定义中间件，拦截请求，实现鉴权、日志记录等通用逻辑。
 | 原文链接：http://book.jcaolwz.asia/blog/5083423.sHtMl

原标题：golang 系统设计 issue 模板 bug 反馈模板
简介：golang redis 事务 multi exec 使用，Redis 事务 multi exec 实现批量命令原子执行，理解 redis 事务隔离特性。
 | 原文链接：http://book.jcaolwz.asia/blog/6715127.sHtMl

原标题：限流窗口绕过漏洞修复方案
简介：前端虚拟列表大数据渲染优化，实现虚拟滚动列表，只渲染可视区域 DOM，上万条数据页面流畅渲染。
 | 原文链接：http://book.jcaolwz.asia/blog/0590473.sHtMl

原标题：golang 系统设计分库分表扩容平滑迁移
简介：golang 定时任务任务持久化存储，定时任务持久化到数据库，服务重启任务不丢失，动态管理任务。
 | 原文链接：http://book.jcaolwz.asia/blog/1152895.sHtMl

原标题：AI实践：大模型生成测试用例实践与校验
简介：时间同步修复令牌提前过期，服务器时间不同步导致 JWT 令牌提前过期，同步系统时间解决异常。
 | 原文链接：http://book.jcaolwz.asia/blog/4207838.sHtMl

原标题：实践：前后端时间格式统一规范落地实践
简介：golang md5 sha 加密工具实现，实现 MD5、SHA 哈希工具，做数据摘要，用于签名校验场景。
 | 原文链接：http://book.jcaolwz.asia/blog/9422015.sHtMl

原标题：golang 系统设计消息重试次数间隔策略设置
简介：磁盘占满服务不可用清理方案，定位磁盘占用大文件，清理日志、缓存文件，恢复磁盘可用空间。
 | 原文链接：http://book.jcaolwz.asia/blog/3080680.sHtMl

原标题：Hands‑on：简易配置热更新组件开发实践
简介：golang go1.18 + 泛型基础实操，go 泛型基础语法，泛型函数泛型类型，实现通用工具函数。
 | 原文链接：http://book.jcaolwz.asia/blog/4839772.sHtMl

原标题：坑点：npm/pip全局版本与项目本地版本冲突
简介：golang http 服务性能优化调参，调优 Go HTTP 服务参数，调整连接池，提升服务并发吞吐能力。
 | 原文链接：http://book.jcaolwz.asia/blog/2073165.sHtMl

原标题：全平台系统环境变量配置
简介：golang base64 大文件流式编解码，大文件流式 base64 转换，不用一次性加载全部文件进入内存。
 | 原文链接：http://book.jcaolwz.asia/blog/0550859.sHtMl

原标题：日志驱动异常日志不输出修复
简介：golang gin 静态资源访问配置，Gin 配置静态资源目录，直接对外提供静态文件访问服务。
 | 原文链接：http://book.jcaolwz.asia/blog/5546040.sHtMl

原标题：入门实践：简易导出导入文件功能实现
简介：golang go work 多模块本地开发，go work 多模块本地同时开发，本地模块互相引用，无需推送仓库。
 | 原文链接：http://book.jcaolwz.asia/blog/2169340.sHtMl

原标题：Performance：数据库索引优化常见错误案例
简介：golang delve 远程调试 go 线上程序，delve 远程调试，线上环境附加进程调试排查线上 bug。
 | 原文链接：http://book.jcaolwz.asia/blog/1493469.sHtMl

原标题：golang gin 中间件执行顺序讲解
简介：golang 分表跨表 join 查询处理方案，分表后跨分片关联查询解决方案，业务层聚合代替数据库 join。
 | 原文链接：http://book.jcaolwz.asia/blog/0132758.sHtMl

原标题：限流规则误拦截正常请求修复
简介：热更新开发环境配置教程，配置代码热重载，修改代码无需重启服务立即生效，大幅提升本地开发调试效率。
 | 原文链接：http://book.jcaolwz.asia/blog/0320966.sHtMl

原标题：API 大版本不兼容平滑迁移
简介：golang go‑zero 框架项目快速搭建，go‑zero 脚手架生成微服务项目，api rpc 服务快速开发。
 | 原文链接：http://book.jcaolwz.asia/blog/8035273.sHtMl

原标题：golang grafana 监控面板简单配置
简介：空指针异常判空容错处理，讲解空指针产生场景，规范判空逻辑，增加容错，避免空指针直接造成程序崩溃。
 | 原文链接：http://book.jcaolwz.asia/blog/1205161.sHtMl

原标题：golang 系统设计网关路由规则动态配置实现
简介：golang http 客户端连接泄漏排查，http client 未读取响应体导致连接无法复用，解决连接泄漏耗尽连接池。
 | 原文链接：http://book.jcaolwz.asia/blog/6610713.sHtMl

原标题：golang 系统设计网关缓存静态资源实现思路
简介：golang http 客户端连接泄漏排查，http client 未读取响应体导致连接无法复用，解决连接泄漏耗尽连接池。
 | 原文链接：http://book.jcaolwz.asia/blog/8977568.sHtMl

原标题：架构复盘：多级缓存架构，本地缓存+分布式缓存
简介：Redis 分布式锁高并发安全实现，基于 Redis 实现分布式锁，处理锁过期、续期，保障集群并发安全。
 | 原文链接：http://book.jcaolwz.asia/blog/4426219.sHtMl

原标题：前端组件库按需加载性能优化
简介：golang defer 执行顺序与坑点，defer 后进先出，循环内部 defer 陷阱，资源释放正确写法。
 | 原文链接：http://book.jcaolwz.asia/blog/2983709.sHtMl

原标题：golang 系统设计 io 瓶颈磁盘网络优化实践
简介：编译打包产物依赖分析解读，分析打包之后产物组成，理清运行依赖文件，排查打包后缺失文件问题。
 | 原文链接：http://book.jcaolwz.asia/blog/1567896.sHtMl

原标题：golang redis 发布订阅简单示例
简介：vue pinia 状态管理实战教程，Pinia 完整实战示例，实现状态定义修改，模块拆分替代 Vuex。
 | 原文链接：http://book.jcaolwz.asia/blog/2027520.sHtMl

原标题：golang 系统设计分布式配置中心思路
简介：接口签名验签完整安全方案，一套完整接口签名方案，包含签名生成、请求携带、服务端验签校验。
 | 原文链接：http://book.jcaolwz.asia/blog/2300511.sHtMl

原标题：快速入门Nginx基础配置，反向代理示例
简介：golang 后端节点健康检查机制实现，定时探测后端节点状态，自动剔除故障节点，保障转发可用。
 | 原文链接：http://book.jcaolwz.asia/blog/4159553.sHtMl

原标题：坑点：版本号语义化理解错误依赖版本错乱
简介：golang pprof 线上采集性能数据，线上环境采集 pprof 性能样本，不用停机，分析线上性能问题。
 | 原文链接：http://book.jcaolwz.asia/blog/6636972.sHtMl

原标题：golang 系统设计 cpu 瓶颈定位优化方案
简介：golang 结构体深浅拷贝区别实操，区分结构体浅拷贝深拷贝，规避指针引用带来数据意外篡改问题。
 | 原文链接：http://book.jcaolwz.asia/blog/4901736.sHtMl

原标题：实战项目：HTTPS本地自签名证书配置实践
简介：golang 探测文件真实内容类型，读取文件头部字节判断真实文件格式，规避后缀伪造。
 | 原文链接：http://book.jcaolwz.asia/blog/2253998.sHtMl

原标题：Troubleshooting：WSL文件权限问题大量踩坑
简介：golang bytes.Buffer 字节缓冲区使用，bytes.Buffer 字节内存缓冲区，拼接字节，避免频繁内存分配。
 | 原文链接：http://book.jcaolwz.asia/blog/3451573.sHtMl

原标题：项目语义化版本号规范管理
简介：golang regexp 正则捕获分组提取数据，正则捕获分组提取子匹配内容，拿到需要业务字段。
 | 原文链接：http://book.jcaolwz.asia/blog/3098900.sHtMl

原标题：golang k8s hpa 水平 pod 自动扩缩容
简介：golang 速率限制令牌桶实现，Go 实现令牌桶限流算法，可复用限流器，控制业务调用速率。
 | 原文链接：http://book.jcaolwz.asia/blog/4584305.sHtMl

原标题：方案对比：几种任务队列架构选型优缺点
简介：Docker 容器时区错误修复方案，修复 Docker 容器内部时区偏差，解决容器内时间不对引发业务逻辑异常。
 | 原文链接：http://book.jcaolwz.asia/blog/3069087.sHtMl

原标题：线程调度优化减少上下文切换
简介：Git 标签版本标记发布管理，使用 Git 标签标记项目版本，打标签推送远程，用于版本发布、版本回溯。
 | 原文链接：http://book.jcaolwz.asia/blog/6830243.sHtMl

原标题：golang docker 镜像构建最佳实践
简介：golang sort 搜索查找切片元素，sort.Search 二分查找有序切片，快速定位元素索引位置。
 | 原文链接：http://book.jcaolwz.asia/blog/1877539.sHtMl

原标题：零基础学习简单正则表达式实战案例
简介：本地运行正常线上报错排查，对比本地与线上环境差异，从配置、系统版本、文件权限定位线上独有的 bug。
 | 原文链接：http://book.jcaolwz.asia/blog/1877560.sHtMl

原标题：动态定时任务业务调度实现
简介：golang go 自定义错误类型实现，自定义 error 结构体，携带错误码、堆栈信息，统一业务错误。
 | 原文链接：http://book.jcaolwz.asia/blog/6269452.sHtMl

原标题：开发复盘：内存缓存LRU淘汰策略实现实践
简介：golang go 泛型实现通用数据结构，泛型实现通用栈队列，复用逻辑支持多种数据类型。
 | 原文链接：http://book.jcaolwz.asia/blog/9371643.sHtMl

原标题：golang 系统设计网关路由规则动态配置实现
简介：接口签名校验防篡改实现，实现请求签名验签逻辑，校验请求参数未被篡改，提升接口调用安全性。
 | 原文链接：http://book.jcaolwz.asia/blog/0285189.sHtMl

原标题：方案设计：高可用Redis集群架构选型对比
简介：golang 命令行交互 cobra 开发 cli，cobra 库开发功能完善命令行工具，子命令参数标志解析。
 | 原文链接：http://book.jcaolwz.asia/blog/2248794.sHtMl

三、实战开发｜Practice
原标题：golang mysql limit 大分页优化
简介：golang redis hyperloglog 基数统计，hyperloglog 统计 UV 基数，海量数据去重统计，极低内存开销。
 | 原文链接：http://book.jcaolwz.asia/blog/0754616.sHtMl

原标题：设计思考：容器化业务应用架构改造要点
简介：golang go 项目安全检查漏洞扫描，扫描 go 项目依赖漏洞，代码安全审计，规避安全风险。
 | 原文链接：http://book.jcaolwz.asia/blog/5304206.sHtMl

原标题：golang 多协程任务池并发控制
简介：golang grpc metadata 元数据透传，metadata 传递 traceId、鉴权信息，全链路透传上下文信息。
 | 原文链接：http://book.jcaolwz.asia/blog/2640852.sHtMl

原标题：踩坑：环境变量未生效导致线上配置错乱
简介：golang 系统资源限制读取 cpu 内存，读取系统容器 cpu 内存限制，程序适配容器资源配额做业务调优。
 | 原文链接：http://book.jcaolwz.asia/blog/2920897.sHtMl

原标题：项目实践：幂等表实现接口幂等业务实践
简介：DNS TTL 配置域名切换生效，调整 DNS 解析 TTL，缩短缓存时间，域名变更后可以快速全网生效。
 | 原文链接：http://book.jcaolwz.asia/blog/1872944.sHtMl

原标题：Cookie 跨环境登录配置调整
简介：golang 系统信号信号量处理，Go 处理系统各类信号，SIGINT、SIGTERM，实现程序可控退出。
 | 原文链接：http://book.jcaolwz.asia/blog/8562482.sHtMl

原标题：OAuth2 第三方登录服务搭建
简介：golang 信号量控制并发数量，使用信号量控制并发，限制同时执行任务数量，保护下游资源。
 | 原文链接：http://book.jcaolwz.asia/blog/8829800.sHtMl

原标题：golang kafka 监控指标简单梳理
简介：nodejs 数据库连接池配置调优，调优 Node 数据库连接池参数，平衡性能与资源占用，避免连接耗尽。
 | 原文链接：http://book.jcaolwz.asia/blog/1634084.sHtMl

原标题：golang 系统设计分布式锁可重入实现思路
简介：golang 服务限流熔断降级监控完整实践，微服务防护体系，限流熔断降级指标监控告警整套落地。
 | 原文链接：http://book.jcaolwz.asia/blog/6606226.sHtMl

原标题：nodejs 进程间通信 IPC 实操
简介：程序性能指标 CPU 内存监控，讲解基础性能指标含义，简单实现监控采集，初步定位程序运行性能瓶颈。
 | 原文链接：http://book.jcaolwz.asia/blog/5334467.sHtMl

原标题：GC 垃圾回收优化降低 CPU 占用
简介：golang jaeger 链路追踪部署对接，jaeger 接收 opentelemetry 链路数据，可视化完整调用链路。
 | 原文链接：http://book.jcaolwz.asia/blog/8545456.sHtMl

原标题：golang 系统设计分表跨表 join 业务处理方案
简介：golang tcp keepalive 参数程序配置，go 程序设置 tcp keepalive，操作系统 tcp 保活参数，清理僵死连接。
 | 原文链接：http://book.jcaolwz.asia/blog/3408675.sHtMl

原标题：开发复盘：消息队列消息顺序性业务落地实践
简介：golang json 自定义 MarshalJSON UnmarshalJSON，自定义 json 序列化反序列化逻辑，处理特殊格式字段。
 | 原文链接：http://book.jcaolwz.asia/blog/9608851.sHtMl

原标题：跨平台换行符统一异常修复
简介：预编译 SQL 防注入实现，使用预编译 SQL 方式，杜绝 SQL 注入风险，提升数据库访问层安全能力。
 | 原文链接：http://book.jcaolwz.asia/blog/0638797.sHtMl

原标题：Debug：预加载逻辑错误服务启动时间成倍拉长
简介：极简方式搭建个人技术文档站点，使用轻量化工具快速部署文档站点，支持 markdown 编写，实现知识沉淀与对外分享。
 | 原文链接：http://book.jcaolwz.asia/blog/8234891.sHtMl

原标题：golang 系统设计最小权限原则落地实践
简介：golang yaml 解析配置加载实操，Go 解析 YAML 配置文件，读取配置参数，驱动业务运行。
 | 原文链接：http://book.jcaolwz.asia/blog/2982297.sHtMl

原标题：批量异步处理系统业务落地
简介：nodejs 接口限流防刷代码实现，Node 层实现接口限流，限制 IP 访问频次，防护接口被恶意高频调用。
 | 原文链接：http://book.jcaolwz.asia/blog/2261206.sHtMl

原标题：浏览器缓存强制刷新方案
简介：前端虚拟列表大数据渲染优化，实现虚拟滚动列表，只渲染可视区域 DOM，上万条数据页面流畅渲染。
 | 原文链接：http://book.jcaolwz.asia/blog/2103721.sHtMl

原标题：全局异常处理器接口返回统一
简介：nodejs 信号处理优雅关闭服务，监听系统信号，执行资源清理，实现 Node 服务优雅停机，拒绝粗暴杀死进程。
 | 原文链接：http://book.jcaolwz.asia/blog/7782450.sHtMl

原标题：布隆过滤器数据高效去重实现
简介：nodejs 数据库连接池配置调优，调优 Node 数据库连接池参数，平衡性能与资源占用，避免连接耗尽。
 | 原文链接：http://book.jcaolwz.asia/blog/4151981.sHtMl

原标题：项目语义化版本号规范管理
简介：前端水印防信息泄露实现，实现网页水印功能，页面叠加用户信息水印，防止页面截图信息外泄。
 | 原文链接：http://book.jcaolwz.asia/blog/5896847.sHtMl

原标题：golang 系统设计压测工具 vegeta 使用示例
简介：golang time 定时器重置 Reset 正确用法，Timer Reset 调用前提，避免 Reset 带来逻辑错误。
 | 原文链接：http://book.jcaolwz.asia/blog/1234509.sHtMl

原标题：前后端交互跨域问题完整处理
简介：数据库主从延迟业务兼容处理，业务适配主从复制延迟，避免读取从库拿到还未同步完成旧数据。
 | 原文链接：http://book.jcaolwz.asia/blog/7187115.sHtMl

原标题：golang 系统设计 jmeter 简单压测脚本编写
简介：golang 微服务网关简易实现，http 反向代理、路由匹配、鉴权限流，理解网关核心原理。
 | 原文链接：http://book.jcaolwz.asia/blog/8800756.sHtMl

原标题：golang redis 缓存击穿防护实现
简介：golang gin 获取客户端真实 IP，多层代理场景正确拿到用户真实访问 IP，避免拿到网关代理内网地址。
 | 原文链接：http://book.jcaolwz.asia/blog/9231481.sHtMl

原标题：golang 系统设计 rest api 接口设计最佳实践
简介：内存泄漏定位分析完整流程，分享内存泄漏排查步骤，定位没有释放的对象，解决内存持续上涨问题。
 | 原文链接：http://book.jcaolwz.asia/blog/1718610.sHtMl

原标题：手写简易 ORM 理解对象映射
简介：golang lru 缓存淘汰算法编写，手写 LRU 缓存淘汰算法，实现本地缓存，淘汰最久未使用数据。
 | 原文链接：http://book.jcaolwz.asia/blog/2888933.sHtMl

原标题：Architecture：安全防护架构XSSCSRFSQL注入防御
简介：程序性能指标 CPU 内存监控，讲解基础性能指标含义，简单实现监控采集，初步定位程序运行性能瓶颈。
 | 原文链接：http://book.jcaolwz.asia/blog/6907636.sHtMl

原标题：设计思考：大促系统架构压测改造整体思路
简介：Cookie 跨环境登录配置调整，调整 Cookie 域、Secure 属性，适配开发测试生产环境，修复登录失效。
 | 原文链接：http://book.jcaolwz.asia/blog/0359238.sHtMl

原标题：golang 项目环境变量加载方案
简介：磁盘 inode 耗尽文件创建失败，排查磁盘 inode 占用，清理大量小文件，恢复文件创建能力。
 | 原文链接：http://book.jcaolwz.asia/blog/5780338.sHtMl

原标题：golang 系统设计主干开发 trunk‑based 讲解
简介：分布式 ID 生成器高并发实现，实现高性能分布式 ID 生成器，适配高并发业务，生成全局唯一 ID。
 | 原文链接：http://book.jcaolwz.asia/blog/7191647.sHtMl

原标题：后端登录鉴权模块完整开发
简介：service‑worker 离线缓存实践，使用 ServiceWorker 实现静态资源离线缓存，弱网环境页面依然可访问。
 | 原文链接：http://book.jcaolwz.asia/blog/9204813.sHtMl

原标题：Hands‑on：简易熔断逻辑状态机原型实现
简介：golang bufio 缓冲读写性能优化，bufio 带缓冲读写，减少系统调用，提升文件网络 IO 性能。
 | 原文链接：http://book.jcaolwz.asia/blog/3659057.sHtMl

原标题：从零学习简单分页逻辑实现思路
简介：golang 容器信号转发处理问题修复，docker/k8s 正确转发 SIGTERM 信号，保证 go 程序收到信号优雅退出。
 | 原文链接：http://book.jcaolwz.asia/blog/6493138.sHtMl

原标题：项目实践：搭建个人API网关最小实现版本
简介：Shell 运维脚本服务器效率提升，编写常用运维 Shell 脚本，自动化服务器运维操作，减少手工重复工作。
 | 原文链接：http://book.jcaolwz.asia/blog/9348647.sHtMl

原标题：golang redis 客户端业务使用
简介：golang embed 目录读取文件列表，embed 嵌入整个目录，读取目录下全部文件，做静态资源服务。
 | 原文链接：http://book.jcaolwz.asia/blog/6485674.sHtMl

原标题：踩坑记录：时间戳精度不一致引发判断错误
简介：golang jwt jwk 公钥验证令牌，使用 jwk 公钥校验 jwt，非对称方式签发校验令牌，提升安全性。
 | 原文链接：http://book.jcaolwz.asia/blog/5566563.sHtMl

原标题：OpenSource：如何高效阅读大型开源项目源码
简介：Git 子模块更新代码不全修复，正确更新 Git 子模块，拉取子模块完整代码，解决子模块目录为空问题。
 | 原文链接：http://book.jcaolwz.asia/blog/6776839.sHtMl

原标题：golang 系统设计架构图绘图工具选型对比
简介：golang excel 生成导出高性能方案，excelize 流式生成 excel，百万行数据导出，规避内存溢出。
 | 原文链接：http://book.jcaolwz.asia/blog/8103897.sHtMl

原标题：开发复盘：导出大文件避免内存溢出实现方案
简介：golang 简单爬虫请求防封禁，简易 Go 爬虫实现，增加请求间隔、UA 伪装，规避被目标站点封禁 IP。
 | 原文链接：http://book.jcaolwz.asia/blog/5289895.sHtMl

四、架构设计｜Architecture
原标题：缓存过期策略优化防业务故障
简介：golang race 检测器性能开销，race 检测器有性能损耗，只用于测试环境，禁止生产开启 race。
 | 原文链接：http://book.jcaolwz.asia/blog/6312304.sHtMl

原标题：golang 告警推送钉钉机器人实现
简介：golang 文件上传下载接口开发，Go 开发文件上传下载接口，校验文件，处理文件读写存储逻辑。
 | 原文链接：http://book.jcaolwz.asia/blog/2727457.sHtMl

原标题：项目实践：OpenTelemetry链路追踪本地部署实践
简介：nodejs 多进程任务分发处理，多进程拆分处理 CPU 密集任务，主进程分发任务，利用多核提升处理速度。
 | 原文链接：http://book.jcaolwz.asia/blog/7290889.sHtMl

原标题：golang 系统设计 commit 提交规范约定
简介：nodejs 接口限流防刷代码实现，Node 层实现接口限流，限制 IP 访问频次，防护接口被恶意高频调用。
 | 原文链接：http://book.jcaolwz.asia/blog/2066463.sHtMl

原标题：架构复盘：多级缓存架构，本地缓存+分布式缓存
简介：缓存过期打散防止缓存雪崩，对缓存过期时间增加随机偏移，避免大量缓存同时失效引发缓存雪崩。
 | 原文链接：http://book.jcaolwz.asia/blog/6730203.sHtMl

原标题：缓存过期策略优化防业务故障
简介：golang sync.WaitGroup 协程等待控制，WaitGroup 控制一组协程等待全部执行完成，完成批量协程任务调度。
 | 原文链接：http://book.jcaolwz.asia/blog/6248083.sHtMl

原标题：golang k8s hpa 水平 pod 自动扩缩容
简介：前端打包产物体积压缩优化，多手段压缩前端打包产物，移除无用代码，压缩资源，提升页面加载速度。
 | 原文链接：http://book.jcaolwz.asia/blog/1824661.sHtMl

原标题：Issue：防火墙拦截ICMP，MTU问题网络丢包
简介：golang strconv 字符串类型转换，字符串转数字布尔，处理转换失败 error，避免 panic。
 | 原文链接：http://book.jcaolwz.asia/blog/8178894.sHtMl

原标题：golang 系统设计 tcp 三次握手四次挥手梳理
简介：单元测试用例编写入门实操，讲解测试用例设计思路，演示基础单元测试代码，提升代码健壮性，提前发现逻辑 bug。
 | 原文链接：http://book.jcaolwz.asia/blog/1186492.sHtMl

原标题：项目语义化版本号规范管理
简介：WSL 搭建 Windows Linux 开发环境，配置 WSL 环境，在 Windows 系统使用 Linux 工具链，适配 Linux 开发项目。
 | 原文链接：http://book.jcaolwz.asia/blog/1667955.sHtMl

原标题：内存广播本地进程消息通知
简介：Nginx 静态代理负载均衡全套配置，一套 Nginx 配置示例，覆盖静态资源、反向代理、负载均衡场景。
 | 原文链接：http://book.jcaolwz.asia/blog/2776866.sHtMl

原标题：开发记录：网关实现接口鉴权、限流、日志打印
简介：golang 项目目录分层规范设计，Go 后端项目目录分层规范，按领域分层，提高项目可读性可维护性。
 | 原文链接：http://book.jcaolwz.asia/blog/6449561.sHtMl

原标题：DevOps：容器网络模式选型与坑点总结
简介：golang jwt 令牌刷新逻辑实现，实现 JWT 双令牌机制，access 短期有效 refresh 刷新令牌，实现无感续期登录。
 | 原文链接：http://book.jcaolwz.asia/blog/6370235.sHtMl

原标题：项目脚手架模板生成工具
简介：golang 参数校验业务接口处理，Go 接口入参参数校验，拦截非法入参，减少业务层参数判断代码。
 | 原文链接：http://book.jcaolwz.asia/blog/1839800.sHtMl

原标题：架构复盘：数据库主从架构设计与延迟应对方案
简介：文件句柄上限调整上传随机失败，调高系统文件句柄上限，解决高并发上传场景随机打开文件失败。
 | 原文链接：http://book.jcaolwz.asia/blog/2294756.sHtMl

原标题：golang 项目 go mod 依赖管理
简介：golang aes cbc gcm 模式加密对比，AES‑CBC AES‑GCM 模式加密解密，理解两种模式差异选型。
 | 原文链接：http://book.jcaolwz.asia/blog/2753941.sHtMl

原标题：性能复盘：锁等待严重业务逻辑优化记录
简介：golang 信号量 semaphore 并发限制，基于 semaphore 实现并发数量控制，保护数据库、第三方接口不被打满。
 | 原文链接：http://book.jcaolwz.asia/blog/6071746.sHtMl

原标题：golang 内存缓存简单实现方案
简介：golang go‑zero 中间件鉴权限流，go‑zero 自定义中间件，实现鉴权、限流、日志打印通用能力。
 | 原文链接：http://book.jcaolwz.asia/blog/8108894.sHtMl

?
