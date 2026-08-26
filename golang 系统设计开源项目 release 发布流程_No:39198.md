最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计开源项目 release 发布流程
简介：golang go 比较运算符可比较类型，哪些类型可以直接 == 比较，map slice 函数不可直接比较。
 | 原文链接：http://book.bus2wl.asia/blog/149525.Doc

原标题：调优方案：Docker容器内核参数性能调优
简介：golang snowflake 时钟回拨解决方案，雪花算法处理时钟回拨，防止生成重复 ID，保证 ID 全局唯一。
 | 原文链接：http://book.bus2wl.asia/blog/838436.Doc

原标题：记一次第三方回调IP变动未更新防火墙拦截
简介：golang systemd 信号与优雅退出配合，systemd 停止服务发送 SIGTERM，go 程序捕获信号优雅关闭。
 | 原文链接：http://book.bus2wl.asia/blog/545966.Doc

原标题：调优方案：gzip压缩开启降低网络传输体积
简介：git cherry‑pick 规范操作防 bug，规范 cherry‑pick 使用流程，处理冲突，避免错误引入不兼容代码。
 | 原文链接：http://book.bus2wl.asia/blog/386071.Doc

原标题：批量操作分批处理防止 OOM
简介：golang go mod graph 可视化依赖图，可视化 go 依赖关系，直观看到包之间依赖，定位冲突。
 | 原文链接：http://book.bus2wl.asia/blog/700817.Doc

原标题：线程池拒绝策略任务丢失防护
简介：golang io.Copy 流式拷贝数据，io.Copy 拷贝 reader 到 writer，不用加载全部数据到内存。
 | 原文链接：http://book.bus2wl.asia/blog/122461.Doc

原标题：服务健康检查监控接口开发
简介：golang 滑动窗口限流算法 go 实现，滑动窗口限流，解决固定窗口临界流量突增漏洞，限流更精准。
 | 原文链接：http://book.bus2wl.asia/blog/030718.Doc

原标题：限流规则误拦截正常请求修复
简介：本地数据库开发环境搭建指南，讲解数据库安装配置、账号权限设置、连接测试，快速搭建用于开发调试的数据库实例。
 | 原文链接：http://book.bus2wl.asia/blog/524689.Doc

原标题：golang 系统设计开源项目安全漏洞处理流程
简介：全局时间标准统一逻辑错乱修复，全服务统一使用同一时间标准，不要混用本地时间 UTC，修复时间逻辑 bug。
 | 原文链接：http://book.bus2wl.asia/blog/191487.Doc

原标题：排错：静态资源CDN缓存未刷新旧资源持续返回
简介：WebSocket 断线重连稳定优化，增加 WebSocket 断线自动重连逻辑，处理网络抖动，维持长连接稳定。
 | 原文链接：http://book.bus2wl.asia/blog/626205.Doc

原标题：接口限流逻辑简单模拟实现
简介：golang loki 日志收集 go 服务集成，日志输出适配 loki，标签携带 traceId，日志集中检索排查问题。
 | 原文链接：http://book.bus2wl.asia/blog/929628.Doc

原标题：方案对比：几种任务队列架构选型优缺点
简介：简易日志收集集中管理方案，搭建轻量日志收集方案，把多服务日志汇总，集中检索查看日志信息。
 | 原文链接：http://book.bus2wl.asia/blog/587905.Doc

原标题：设计思考：缓存分层架构设计与失效处理策略
简介：接口签名验签完整安全方案，一套完整接口签名方案，包含签名生成、请求携带、服务端验签校验。
 | 原文链接：http://book.bus2wl.asia/blog/196472.Doc

原标题：golang 系统设计缓存一致性方案对比
简介：golang sync.RWMutex 读写锁使用场景，读多写少场景读写锁，读共享写互斥，提升并发性能。
 | 原文链接：http://book.bus2wl.asia/blog/820911.Doc

原标题：golang 静态文件服务搭建教程
简介：golang go 服务日志输出 journald，systemd journald 接收程序 stdout 日志，统一管理服务日志。
 | 原文链接：http://book.bus2wl.asia/blog/052371.Doc

原标题：golang 系统设计本地缓存 redis 缓存多级组合
简介：golang kitex 字节微服务框架入门，kitex 开发 rpc 微服务，代码生成，服务注册发现完整流程。
 | 原文链接：http://book.bus2wl.asia/blog/912959.Doc

原标题：调优方案：Nginx性能参数调优高并发配置
简介：CDN 缓存刷新获取最新静态资源，调用 CDN 刷新接口，清除节点旧缓存，用户访问到更新后的静态文件。
 | 原文链接：http://book.bus2wl.asia/blog/589065.Doc

原标题：Issue：操作系统最大打开文件数限制导致报错
简介：业务错误码完整落地实践，落地完整业务错误码，枚举全部业务异常，统一返回，配套文档说明。
 | 原文链接：http://book.bus2wl.asia/blog/666112.Doc

原标题：架构笔记：WebSocket大规模连接服务架构
简介：业务错误码体系设计方案，设计项目统一错误码，区分不同业务异常，标准化错误返回，便于前端识别处理。
 | 原文链接：http://book.bus2wl.asia/blog/247207.Doc

原标题：golang 系统设计 rest http 方法使用原则
简介：golang make new 关键字使用区别，分清 new 与 make 适用类型，正确初始化切片 map 通道，杜绝 nil 引发 panic。
 | 原文链接：http://book.bus2wl.asia/blog/722976.Doc

原标题：架构笔记：任务调度系统架构设计与可靠性
简介：K8s 镜像拉取网络故障修复，排查 K8s 集群镜像拉取网络问题，配置镜像源，恢复镜像正常拉取。
 | 原文链接：http://book.bus2wl.asia/blog/602450.Doc

原标题：Security：Docker镜像安全扫描漏洞修复
简介：特殊输入字符过滤解析防护，过滤用户输入特殊字符，防止解析报错，规避恶意字符带来业务异常。
 | 原文链接：http://book.bus2wl.asia/blog/378290.Doc

原标题：动态定时任务业务调度实现
简介：WebSocket 聊天室实时通讯开发，基于 WebSocket 搭建简易聊天室，实现多人消息广播实时聊天效果。
 | 原文链接：http://book.bus2wl.asia/blog/042002.Doc

原标题：消息队列生产消费模型入门
简介：golang os 打开文件 O_APPEND O_CREATE 标志，OpenFile 标志位，控制文件创建追加截断行为。
 | 原文链接：http://book.bus2wl.asia/blog/260396.Doc

原标题：golang 系统设计配置本地缓存降级策略方案
简介：golang sql 注入风险规避要点，参数化查询杜绝 sql 注入，禁止字符串拼接 SQL 语句执行。
 | 原文链接：http://book.bus2wl.asia/blog/185667.Doc

原标题：Hands‑on：简易ID生成雪花算法完整实现
简介：golang 字符编码转换 go 处理，iconv‑go 做编码转换 gbk utf8 互转，处理老旧系统 gbk 编码数据。
 | 原文链接：http://book.bus2wl.asia/blog/962871.Doc

原标题：新手快速上手 Git 版本控制实操指南
简介：慢查询分析索引调优数据库实战，抓取慢查询，分析执行计划，优化索引，解决数据库慢查询拖慢业务。
 | 原文链接：http://book.bus2wl.asia/blog/507835.Doc

原标题：看懂报错日志快速定位问题
简介：golang 后端节点健康检查机制实现，定时探测后端节点状态，自动剔除故障节点，保障转发可用。
 | 原文链接：http://book.bus2wl.asia/blog/787407.Doc

原标题：ORM 框架数据库增删改查实操
简介：golang go 模板执行错误捕获，捕获模板执行错误，防止模板错误直接返回空白页面。
 | 原文链接：http://book.bus2wl.asia/blog/154615.Doc

原标题：golang 系统设计故障应急响应完整流程梳理
简介：nodejs 多进程任务分发处理，多进程拆分处理 CPU 密集任务，主进程分发任务，利用多核提升处理速度。
 | 原文链接：http://book.bus2wl.asia/blog/719529.Doc

原标题：golang 系统设计缓存与数据库一致性权衡
简介：golang errors.Is errors.As 错误判断，判断是否为指定错误类型，提取自定义错误信息，错误处理进阶。
 | 原文链接：http://book.bus2wl.asia/blog/675990.Doc

原标题：nodejs 信号处理优雅关闭服务
简介：浏览器缓存强制刷新方案，设置 HTTP 缓存头，处理浏览器缓存旧静态资源，让用户加载更新后的页面。
 | 原文链接：http://book.bus2wl.asia/blog/184801.Doc

原标题：踩坑记录：端口被占用导致服务启动失败
简介：文件监控服务自动重启开发，监控项目文件变更，代码修改自动重启服务，提升本地开发调试效率。
 | 原文链接：http://book.bus2wl.asia/blog/198046.Doc

原标题：项目实践：消息队列消息堆积模拟处理实践
简介：vue pinia 状态管理实战教程，Pinia 完整实战示例，实现状态定义修改，模块拆分替代 Vuex。
 | 原文链接：http://book.bus2wl.asia/blog/178050.Doc

原标题：golang 系统设计混沌测试故障注入简单示例
简介：golang docker 镜像构建最佳实践，Go 项目 Docker 镜像构建最佳实践，减小镜像体积，安全构建。
 | 原文链接：http://book.bus2wl.asia/blog/464720.Doc

原标题：性能笔记：避免频繁创建销毁对象GC优化
简介：golang hmac 签名生成校验示例，hmac 生成消息签名，做接口请求签名，校验数据不被篡改。
 | 原文链接：http://book.bus2wl.asia/blog/649413.Doc

原标题：Architecture：大文件上传下载系统架构设计
简介：golang jwt 鉴权中间件完整示例，Gin JWT 鉴权中间件，令牌校验，解析用户信息，接口鉴权拦截。
 | 原文链接：http://book.bus2wl.asia/blog/854483.Doc

原标题：golang 系统设计指标聚合计算存储选型对比
简介：golang go xml 解析生成 xml 文档，encoding/xml 解析 xml，结构体标签映射 xml 节点属性。
 | 原文链接：http://book.bus2wl.asia/blog/047259.Doc

原标题：golang 系统设计日志脱敏防止信息泄露
简介：版本升级服务启动失败处理，版本更新之后服务无法启动，对比新旧版本配置、依赖差异，完成故障修复。
 | 原文链接：http://book.bus2wl.asia/blog/748354.Doc

原标题：golang 系统设计无锁编程思路简单示例
简介：数据库连接池参数调优，调整连接池最大最小连接数，空闲超时，避免连接耗尽或者资源浪费。
 | 原文链接：http://book.bus2wl.asia/blog/130948.Doc


二、踩坑排错｜Troubleshooting
原标题：golang redis 过期策略内存淘汰
简介：WSL 搭建 Windows Linux 开发环境，配置 WSL 环境，在 Windows 系统使用 Linux 工具链，适配 Linux 开发项目。
 | 原文链接：http://book.bus2wl.asia/blog/524587.Doc

原标题：golang mysql innodb 事务隔离级别
简介：golang io.Copy 流式拷贝数据，io.Copy 拷贝 reader 到 writer，不用加载全部数据到内存。
 | 原文链接：http://book.bus2wl.asia/blog/016299.Doc

原标题：golang 系统设计 go netpoll 多路复用简单理解
简介：系统文件描述符上限调大，调高操作系统文件描述符上限，解决高并发场景打开文件报错。
 | 原文链接：http://book.bus2wl.asia/blog/129955.Doc

原标题：golang 系统设计监控告警体系搭建思路
简介：API 接口调试与异常处理实战，覆盖接口请求、参数组装、错误捕获，提供调试思路，高效定位接口返回异常问题。
 | 原文链接：http://book.bus2wl.asia/blog/537923.Doc

原标题：开发记录：实现完整用户登录鉴权业务模块
简介：nestjs 拦截器过滤器管道实战，实操 Nest 拦截器、异常过滤器、管道校验，处理请求与响应统一逻辑。
 | 原文链接：http://book.bus2wl.asia/blog/635549.Doc

原标题：golang 系统设计分布式锁不同场景选型对比
简介：golang 表单文件大小限制配置，限制表单上传文件最大体积，拦截超大文件上传请求，保护服务。
 | 原文链接：http://book.bus2wl.asia/blog/291135.Doc

原标题：开发记录：长连接连接管理自动清理僵死连接
简介：用户敏感数据脱敏代码实现，编写数据脱敏工具，对手机号、身份证做脱敏处理，防止敏感信息直接泄露。
 | 原文链接：http://book.bus2wl.asia/blog/614760.Doc

原标题：MySQL 慢查询索引优化实战
简介：nodejs 单元测试 jest 实操教程，Jest 单元测试实操，编写测试用例，mock 依赖，验证业务逻辑正确性。
 | 原文链接：http://book.bus2wl.asia/blog/785565.Doc

原标题：golang 系统设计回调重试幂等完整处理
简介：golang go 依赖漏洞检测 govulncheck，govulncheck 扫描依赖安全漏洞，发现项目供应链风险。
 | 原文链接：http://book.bus2wl.asia/blog/485814.Doc

原标题：本地数据库开发环境搭建指南
简介：golang nil channel 阻塞特性，nil channel 读写永久阻塞，理解 nil channel 行为做逻辑控制。
 | 原文链接：http://book.bus2wl.asia/blog/617137.Doc

原标题：nodejs 多进程任务分发处理
简介：golang icmp ping 程序实现，go 实现 ping 工具发送 icmp 报文，检测网络连通性。
 | 原文链接：http://book.bus2wl.asia/blog/486387.Doc

原标题：golang 系统设计大流量削峰处理方案
简介：并发数据覆盖加锁安全处理，多线程并发修改同一数据，增加锁机制，防止并发覆盖丢失更新数据。
 | 原文链接：http://book.bus2wl.asia/blog/211804.Doc

原标题：开发复盘：大事务拆分优化业务性能实践
简介：Git 误提交撤销回退实操教程，演示多种撤销提交方式，区分已经推送远程和本地未提交场景，处理误提交代码。
 | 原文链接：http://book.bus2wl.asia/blog/221950.Doc

原标题：性能复盘：数据库回滚日志过大性能影响优化
简介：golang 错误静默忽略风险规避，禁止空忽略错误，必须处理或者明确注释为什么忽略错误。
 | 原文链接：http://book.bus2wl.asia/blog/376541.Doc

原标题：安全实践：容器最小化镜像减少攻击面
简介：golang go 服务蓝绿发布实践思路，蓝绿两套实例，流量一键切换，回滚快速降低发布风险。
 | 原文链接：http://book.bus2wl.asia/blog/363305.Doc

原标题：golang 系统设计网关错误重试超时处理策略
简介：golang go 项目工程目录布局标准，不同规模 go 项目目录结构，小型项目中型项目大型微服务项目布局。
 | 原文链接：http://book.bus2wl.asia/blog/655958.Doc

原标题：golang etcd watch 监听配置变更
简介：端口占用释放资源重启服务，查找占用端口进程，结束占用进程，释放端口，让服务能够正常启动监听。
 | 原文链接：http://book.bus2wl.asia/blog/745304.Doc

原标题：实战：数据库索引设计，复合索引最佳实践
简介：golang grpc 重试机制客户端配置，grpc 客户端配置重试策略，临时故障自动重试，提升调用稳定性。
 | 原文链接：http://book.bus2wl.asia/blog/946585.Doc

原标题：golang 系统设计第三方调用超时重试熔断
简介：golang elasticsearch 客户端 golang 实操，es 客户端文档增删改查，条件搜索聚合统计对接搜索引擎。
 | 原文链接：http://book.bus2wl.asia/blog/183224.Doc

原标题：golang 系统设计链路数据存储选型对比讲解
简介：golang goroutine 泄露常见场景汇总，channel 阻塞、context 忘记取消，导致协程无法退出发生泄露。
 | 原文链接：http://book.bus2wl.asia/blog/200147.Doc

原标题：golang gorm 预加载关联查询优化
简介：golang ioutil 已废弃替换方案，ioutil 废弃之后替换为 os io 包函数，更新旧项目代码。
 | 原文链接：http://book.bus2wl.asia/blog/534340.Doc

原标题：本地运行正常线上报错排查
简介：配置与镜像分离防止信息泄露，业务配置不打包进镜像，外部挂载配置，避免密钥配置随镜像泄露。
 | 原文链接：http://book.bus2wl.asia/blog/443004.Doc

原标题：golang 系统设计第三方接口 mock 单元测试
简介：接口签名验签完整安全方案，一套完整接口签名方案，包含签名生成、请求携带、服务端验签校验。
 | 原文链接：http://book.bus2wl.asia/blog/941924.Doc

原标题：架构笔记：WebSocket大规模连接服务架构
简介：跨平台换行符统一异常修复，统一代码文件换行符，解决不同操作系统换行符不一致带来脚本执行异常。
 | 原文链接：http://book.bus2wl.asia/blog/541060.Doc

原标题：图片上传预览格式大小处理
简介：golang 日志 zap 结构化日志实践，接入 Zap 结构化日志库，打印结构化日志，方便日志检索解析。
 | 原文链接：http://book.bus2wl.asia/blog/307319.Doc

原标题：项目实践：MySQL读写分离本地模拟实践
简介：golang context.WithValue 传递元数据，WithValue 只传 traceId 鉴权元数据，不要传业务大对象。
 | 原文链接：http://book.bus2wl.asia/blog/670273.Doc

原标题：golang 系统设计内部服务调用超时设置要点
简介：内存广播本地进程消息通知，实现进程内内存消息广播，进程内部模块之间事件通知解耦。
 | 原文链接：http://book.bus2wl.asia/blog/201846.Doc

原标题：golang k8s devops 流水线简单思路
简介：golang redis stream 消息队列实战，redis stream 实现可靠消息队列，消费组、ack 确认，消息不丢失。
 | 原文链接：http://book.bus2wl.asia/blog/016543.Doc

原标题：golang csv 读写批量数据处理
简介：golang ctx 传递规则不要存结构体，context 作为函数参数传递，禁止放入结构体字段存储。
 | 原文链接：http://book.bus2wl.asia/blog/487798.Doc

原标题：golang prometheus histogram 指标
简介：Git 误删提交代码恢复找回，使用 Git reflog 工具找回被误删除提交记录，恢复误删除代码。
 | 原文链接：http://book.bus2wl.asia/blog/099981.Doc

原标题：golang mysql limit 大分页优化
简介：golang jaeger 链路追踪部署对接，jaeger 接收 opentelemetry 链路数据，可视化完整调用链路。
 | 原文链接：http://book.bus2wl.asia/blog/862030.Doc

原标题：Hands‑on：简易跨进程通信demo开发实践
简介：CI 构建缓存加速编译速度，开启 CI 流水线依赖缓存，复用上一次构建依赖包，缩短流水线构建耗时。
 | 原文链接：http://book.bus2wl.asia/blog/662265.Doc

原标题：Hands‑on：简易速率限制中间件完整实现
简介：内存泄漏定位分析完整流程，分享内存泄漏排查步骤，定位没有释放的对象，解决内存持续上涨问题。
 | 原文链接：http://book.bus2wl.asia/blog/259287.Doc

原标题：HelloMarkdown：GitHubMarkdown完整语法速查
简介：golang go 二进制安全 strip 减小体积，strip 剥离二进制调试符号，缩小程序二进制文件体积。
 | 原文链接：http://book.bus2wl.asia/blog/497695.Doc

原标题：HelloCI：理解持续集成基础工作流程
简介：golang systemd 配置 go 服务部署，编写 systemd unit 文件管理 go 服务，开机自启、崩溃自动重启。
 | 原文链接：http://book.bus2wl.asia/blog/670740.Doc

原标题：Architecture：静态资源分发CDN整体架构思路
简介：golang jwt jwk 公钥验证令牌，使用 jwk 公钥校验 jwt，非对称方式签发校验令牌，提升安全性。
 | 原文链接：http://book.bus2wl.asia/blog/787911.Doc

原标题：golang http 服务性能优化调参
简介：golang 容器 OOM 被杀死排查区分，区分业务内存泄漏、容器限制过小，定位容器 OOMKilled 原因。
 | 原文链接：http://book.bus2wl.asia/blog/616450.Doc

原标题：Troubleshoot：批量导入数据，事务过大回滚日志暴涨
简介：序列化版本不一致解析失败，保证序列化对象版本对齐，修复版本不匹配导致对象反序列化失败。
 | 原文链接：http://book.bus2wl.asia/blog/869748.Doc

原标题：死信队列处理消息阻塞业务
简介：golang go url url.Values 参数编码，url.Values 构建 url 查询参数，自动处理参数 url 编码。
 | 原文链接：http://book.bus2wl.asia/blog/424743.Doc

原标题：开发复盘：长轮询接口实现服务端消息推送
简介：大事务拆分防止连接池耗尽，将执行时间很长的大事务拆分为小事务，减少事务占用连接时长。
 | 原文链接：http://book.bus2wl.asia/blog/929213.Doc

三、实战开发｜Practice
原标题：Practice：模拟缓存雪崩缓存击穿验证防护策略
简介：Docker 多阶段构建镜像瘦身，使用 Docker 多阶段构建，剔除编译阶段依赖，产出体积更小运行镜像。
 | 原文链接：http://book.bus2wl.asia/blog/523340.Doc

原标题：网关超时时间调优后端等待
简介：静态站点自动部署发布方案，配置流水线，代码更新自动构建静态站点并且部署上线，简化发布。
 | 原文链接：http://book.bus2wl.asia/blog/477519.Doc

原标题：WSL 内存上限限制防止资源耗尽
简介：上传接口跨域配置特殊适配，针对文件上传接口，适配复杂请求，修复上传场景下跨域失效问题。
 | 原文链接：http://book.bus2wl.asia/blog/208462.Doc

原标题：TCP 长连接参数优化 TIME_WAIT
简介：CDN 缓存刷新获取最新静态资源，调用 CDN 刷新接口，清除节点旧缓存，用户访问到更新后的静态文件。
 | 原文链接：http://book.bus2wl.asia/blog/996990.Doc

原标题：新手向：Mac/Windows开发环境差异踩坑
简介：数据库排序规则统一结果一致，统一数据库表排序规则，解决不同环境查询排序结果不一致问题。
 | 原文链接：http://book.bus2wl.asia/blog/083804.Doc

原标题：记一次升级操作系统内核引发服务不稳定
简介：golang go http 静态文件禁止目录遍历，http.FileServer 防止../ 路径穿越，了解底层安全实现。
 | 原文链接：http://book.bus2wl.asia/blog/348167.Doc

原标题：golang gorm 批量插入性能调优
简介：golang go 网络编程 net 包基础，net 包 tcp udp socket 编程，监听接收连接，读写数据。
 | 原文链接：http://book.bus2wl.asia/blog/514403.Doc

原标题：golang github actions 多平台构建
简介：golang 数据库慢查询监控实现，Go 封装 SQL 执行监控，记录慢 SQL，上报日志，发现数据库性能问题。
 | 原文链接：http://book.bus2wl.asia/blog/381865.Doc

原标题：Architecture：监控告警架构避免告警风暴设计
简介：golang uuid 生成多种版本实现，生成 uuid v1 v4，生成唯一标识，业务用于单据编号场景。
 | 原文链接：http://book.bus2wl.asia/blog/930644.Doc

原标题：golang 系统设计分布式任务调度
简介：golang url 解析路径参数提取，url.Parse 解析 url，获取协议主机路径查询参数。
 | 原文链接：http://book.bus2wl.asia/blog/623302.Doc

原标题：操作系统内核版本适配服务
简介：前端大文件分片上传完整方案，前端分片切割大文件，配合后端分片接口，实现稳定大文件上传。
 | 原文链接：http://book.bus2wl.asia/blog/006704.Doc

原标题：golang 系统设计大表加索引线上执行方案
简介：golang 服务注册 etcd 简单示例，etcd 实现服务注册发现，微服务实例注册元数据，客户端发现节点。
 | 原文链接：http://book.bus2wl.asia/blog/735805.Doc

原标题：Performance：避免内存拷贝，大对象处理优化
简介：golang go 程序 CPU 占用高定位步骤，pprof 定位热点函数，分析 CPU 高占用，优化耗时代码逻辑。
 | 原文链接：http://book.bus2wl.asia/blog/639605.Doc

原标题：Hands‑on：简易的事件订阅发布组件开发实践
简介：HTTP 状态码请求头完整梳理，汇总常用 HTTP 状态码与请求头含义，帮助快速看懂网络请求，排查接口通信问题。
 | 原文链接：http://book.bus2wl.asia/blog/932145.Doc

原标题：前端国际化多语言方案落地
简介：接口签名验签完整安全方案，一套完整接口签名方案，包含签名生成、请求携带、服务端验签校验。
 | 原文链接：http://book.bus2wl.asia/blog/078093.Doc

原标题：优化实践：接口批量合并减少网络请求次数
简介：后端分页查询逻辑代码实现，编写后端分页接口，处理页码、每页条数参数，优化大数据量查询返回结果。
 | 原文链接：http://book.bus2wl.asia/blog/340692.Doc

原标题：DevOps：多阶段构建Dockerfile最佳实践
简介：nodejs 单元测试 jest 实操教程，Jest 单元测试实操，编写测试用例，mock 依赖，验证业务逻辑正确性。
 | 原文链接：http://book.bus2wl.asia/blog/042520.Doc

原标题：入门实践：搭建简单的热更新开发环境
简介：webpack chunk 分包策略详解，讲解 webpack chunk 分包策略，拆分第三方包与业务代码，优化缓存复用。
 | 原文链接：http://book.bus2wl.asia/blog/591300.Doc

原标题：系统文件描述符上限调大
简介：缓存穿透击穿雪崩全套防护，完整梳理缓存三大问题，落地全套防护策略，保障缓存层稳定运行。
 | 原文链接：http://book.bus2wl.asia/blog/569609.Doc

原标题：优化实践：接口返回字段裁剪减少报文大小
简介：golang go 排序 sort 包自定义排序，sort 包实现自定义排序逻辑，对切片按业务规则排序。
 | 原文链接：http://book.bus2wl.asia/blog/901672.Doc

原标题：golang 系统设计分库分表中间件思路
简介：golang go 值传递引用传递理解，go 全部为值传递，指针本质拷贝指针值，理清参数传递行为。
 | 原文链接：http://book.bus2wl.asia/blog/718624.Doc

原标题：架构复盘：系统扩容缩容架构无状态优先原则
简介：golang benchmark 参数‑bench‑mem 统计内存分配，benchmark 开启内存统计，观察内存分配次数大小。
 | 原文链接：http://book.bus2wl.asia/blog/072018.Doc

原标题：golang es 更新文档注意版本冲突
简介：golang slice 切片底层原理与坑点，切片扩容、截取、底层数组共享，规避切片修改互相影响数据。
 | 原文链接：http://book.bus2wl.asia/blog/525469.Doc

原标题：golang html 模板渲染简单示例
简介：golang go time 时区数据库内置，go 内置时区数据库，不用系统时区文件，容器时区不依赖系统。
 | 原文链接：http://book.bus2wl.asia/blog/885223.Doc

原标题：golang excel 简单读写操作示例
简介：rebase 操作防止代码丢失，讲解 rebase 风险点，操作前做好备份，规避错误操作造成代码提交丢失。
 | 原文链接：http://book.bus2wl.asia/blog/817171.Doc

原标题：golang 系统设计 rest http 方法使用原则
简介：数据库连接及时关闭连接泄漏，确保数据库连接使用完毕释放归还连接池，杜绝连接泄漏耗尽连接。
 | 原文链接：http://book.bus2wl.asia/blog/562779.Doc

原标题：golang toml 配置文件解析教程
简介：golang rabbitmq go 客户端生产消费，streadway/amqp 实现 rabbitmq 生产者消费者，队列交换机绑定。
 | 原文链接：http://book.bus2wl.asia/blog/695905.Doc

原标题：Troubleshooting：数据库主从延迟带来查询数据不一致
简介：golang kafka 消费者组重平衡避坑，规避消费者组频繁 rebalance，减少消费抖动，保障消息消费稳定性。
 | 原文链接：http://book.bus2wl.asia/blog/086086.Doc

原标题：避坑：预编译SQL失效，出现SQL注入风险
简介：缓存穿透击穿雪崩全套防护，完整梳理缓存三大问题，落地全套防护策略，保障缓存层稳定运行。
 | 原文链接：http://book.bus2wl.asia/blog/744989.Doc

原标题：复盘总结：技术方案文档模板架构设计文档
简介：golang 日志级别动态调整热更新，不用重启程序动态修改日志输出级别，线上调试排查问题十分方便。
 | 原文链接：http://book.bus2wl.asia/blog/853477.Doc

原标题：设计思考：消息队列重复消费架构层防御手段
简介：monorepo 项目多包管理最佳实践，monorepo 仓库管理多子包，统一版本管理，处理包之间互相依赖。
 | 原文链接：http://book.bus2wl.asia/blog/081409.Doc

原标题：gitignore 文件编写过滤规则
简介：golang go 泛型使用避坑注意点，泛型与 interface 区别，泛型性能，什么时候适合使用泛型。
 | 原文链接：http://book.bus2wl.asia/blog/379638.Doc

原标题：golang redis hyperloglog 基数统计
简介：请求工具封装统一异常处理，对网络请求做二次封装，统一捕获各类请求异常，标准化接口返回格式。
 | 原文链接：http://book.bus2wl.asia/blog/470598.Doc

原标题：安全实践：容器最小化镜像减少攻击面
简介：后端分页查询逻辑代码实现，编写后端分页接口，处理页码、每页条数参数，优化大数据量查询返回结果。
 | 原文链接：http://book.bus2wl.asia/blog/585398.Doc

原标题：Architecture：链路追踪架构核心组件与埋点
简介：golang gin 静态资源访问配置，Gin 配置静态资源目录，直接对外提供静态文件访问服务。
 | 原文链接：http://book.bus2wl.asia/blog/113306.Doc

原标题：Hands‑on：简易配置热更新组件开发实践
简介：golang http body 必须关闭的重要性，无论成功失败必须关闭 request.Body，否则连接无法复用泄漏。
 | 原文链接：http://book.bus2wl.asia/blog/576279.Doc

原标题：Troubleshoot：磁盘inode耗尽，无法新建文件
简介：golang go 项目 CI github actions 配置，github actions 实现 go 项目 ci，自动测试、代码检查、编译打包镜像。
 | 原文链接：http://book.bus2wl.asia/blog/995141.Doc

原标题：安全实践：接口速率限制防止暴力破解
简介：golang tcp keepalive 参数程序配置，go 程序设置 tcp keepalive，操作系统 tcp 保活参数，清理僵死连接。
 | 原文链接：http://book.bus2wl.asia/blog/041350.Doc

原标题：golang redis 集群 hash 槽讲解
简介：跨平台 uniapp 多端开发实操，uniapp 开发一套代码，编译多端，梳理多端差异处理与适配技巧。
 | 原文链接：http://book.bus2wl.asia/blog/898622.Doc

原标题：Issue：容器日志驱动配置错误日志全部丢失
简介：golang ip 限流黑名单实现方案，基于 IP 做限流与黑名单，拦截恶意 IP 访问，保护接口服务。
 | 原文链接：http://book.bus2wl.asia/blog/944954.Doc

四、架构设计｜Architecture
原标题：golang gin 中间件执行顺序讲解
简介：golang redis 客户端业务使用，Go Redis 客户端对接，实现缓存、计数器，适配各类 Redis 业务场景。
 | 原文链接：http://book.bus2wl.asia/blog/139583.Doc

原标题：Troubleshoot：磁盘打满导致服务全部不可用
简介：golang 子进程执行命令标准流处理，exec.Command 执行外部命令，处理 stdout stderr，防止缓冲区阻塞卡死。
 | 原文链接：http://book.bus2wl.asia/blog/224268.Doc

原标题：golang 系统设计日志级别业务使用原则梳理
简介：golang 系统调用跟踪 strace 排查 go 程序，strace 跟踪系统调用，定位文件网络 IO 慢的底层原因。
 | 原文链接：http://book.bus2wl.asia/blog/349036.Doc

原标题：入门实践：简单数据脱敏处理示例
简介：多版本开发环境共存配置，实现同一工具多版本并存，快速切换不同版本，适配不同项目对版本的差异化需求。
 | 原文链接：http://book.bus2wl.asia/blog/471350.Doc

原标题：安全复盘：定时任务权限过大风险管控
简介：并发数据覆盖加锁安全处理，多线程并发修改同一数据，增加锁机制，防止并发覆盖丢失更新数据。
 | 原文链接：http://book.bus2wl.asia/blog/383738.Doc

原标题：golang redis set 集合去重业务
简介：GET POST 接口请求参数处理，讲解两种请求方式参数传递区别，演示参数接收、解析、校验，适配不同接口调用场景。
 | 原文链接：http://book.bus2wl.asia/blog/675854.Doc

原标题：实战项目：WebSocket消息广播房间分组实践
简介：Nginx 透传真实客户端 IP 配置，配置 Nginx 把真实客户端 IP 传递后端服务，后端拿到访问者真实 IP。
 | 原文链接：http://book.bus2wl.asia/blog/673377.Doc

原标题：预编译 SQL 防注入实现
简介：golang go 泛型约束与类型集合，泛型 type set 约束，限制泛型支持类型，写出安全泛型代码。
 | 原文链接：http://book.bus2wl.asia/blog/171822.Doc

原标题：Security：Docker镜像安全扫描漏洞修复
简介：golang cobra 命令行参数配置绑定，cobra 绑定配置文件环境变量命令行参数，多源配置合并。
 | 原文链接：http://book.bus2wl.asia/blog/068515.Doc

原标题：golang mongodb 聚合管道实操案例
简介：golang 链路追踪简易实现方案，简易链路追踪实现，传递 traceId，记录调用链路，方便排查慢调用。
 | 原文链接：http://book.bus2wl.asia/blog/744696.Doc

原标题：分布式 ID 全局唯一生成方案
简介：异步编程 Promise 执行流程解析，拆解异步执行顺序，理解回调与 Promise 差异，理清异步场景下代码执行逻辑。
 | 原文链接：http://book.bus2wl.asia/blog/764422.Doc

原标题：macOS 脚本执行权限开启
简介：golang go 泛型使用避坑注意点，泛型与 interface 区别，泛型性能，什么时候适合使用泛型。
 | 原文链接：http://book.bus2wl.asia/blog/527540.Doc

原标题：Hands‑on：搭建OAuth2简易授权服务Demo
简介：前后端交互跨域问题完整处理，讲解跨域产生原理，列举多种解决方案，适配开发、生产不同环境的跨域处理。
 | 原文链接：http://book.bus2wl.asia/blog/928501.Doc

原标题：golang 系统设计消息幂等消费去重实现方案
简介：golang redis 过期键监听回调，监听 key 过期事件，过期触发业务逻辑，实现过期自动处理业务场景。
 | 原文链接：http://book.bus2wl.asia/blog/079903.Doc

原标题：Issue：防火墙拦截ICMP，MTU问题网络丢包
简介：golang go regexp 正则预编译，regexp.MustCompile 预编译正则，不要循环内部编译正则，节省 CPU。
 | 原文链接：http://book.bus2wl.asia/blog/592439.Doc

原标题：golang 系统设计消息体序列化选型对比
简介：golang sync.Mutex 互斥锁正确模式，互斥锁 defer Unlock，锁粒度控制，避免锁范围过大。
 | 原文链接：http://book.bus2wl.asia/blog/940462.Doc

原标题：golang gorm 预加载关联查询优化
简介：请求工具封装统一异常处理，对网络请求做二次封装，统一捕获各类请求异常，标准化接口返回格式。
 | 原文链接：http://book.bus2wl.asia/blog/888155.Doc

原标题：golang mysql 索引失效常见场景
简介：golang go 无锁并发编程技巧，原子操作 sync/atomic，简单场景替换锁，提升并发性能。
 | 原文链接：http://book.bus2wl.asia/blog/045931.Doc

?
