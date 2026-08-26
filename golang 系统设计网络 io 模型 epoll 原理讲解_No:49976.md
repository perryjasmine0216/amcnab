最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计网络 io 模型 epoll 原理讲解
简介：golang http 客户端连接泄漏排查，http client 未读取响应体导致连接无法复用，解决连接泄漏耗尽连接池。
 | 原文链接：http://wiki.kuulyb.asia/arts/114075.Doc

原标题：调优方案：服务实例扩容，水平扩展性能
简介：golang 任务失败重试与死信队列，异步任务失败自动重试，超过重试次数进入死信队列人工处理。
 | 原文链接：http://wiki.kuulyb.asia/arts/397243.Doc

原标题：前端打包产物体积压缩优化
简介：golang go‑zero api 接口开发与路由，go‑zero 编写 api 定义文件，生成代码开发 http 接口。
 | 原文链接：http://wiki.kuulyb.asia/arts/662147.Doc

原标题：golang 系统设计分布式事务几种方案优缺点
简介：golang 消息死信处理业务逻辑，Go 实现死信队列逻辑，消费失败消息转入死信，不阻塞正常消息队列。
 | 原文链接：http://wiki.kuulyb.asia/arts/627299.Doc

原标题：运维笔记：服务器磁盘内存监控告警配置
简介：用户敏感数据脱敏代码实现，编写数据脱敏工具，对手机号、身份证做脱敏处理，防止敏感信息直接泄露。
 | 原文链接：http://wiki.kuulyb.asia/arts/010292.Doc

原标题：多实例部署 Session 共享方案
简介：golang jwt 鉴权中间件完整示例，Gin JWT 鉴权中间件，令牌校验，解析用户信息，接口鉴权拦截。
 | 原文链接：http://wiki.kuulyb.asia/arts/767876.Doc

原标题：Debug：预加载逻辑错误服务启动时间成倍拉长
简介：golang hertz 反向代理与负载均衡，hertz 实现反向代理，内置负载均衡，快速搭建网关类服务。
 | 原文链接：http://wiki.kuulyb.asia/arts/447296.Doc

原标题：实战：多版本SDK兼容业务改造实践
简介：golang os 进程 pid 获取父进程 pid，os.Getpid 获取进程 id，获取父进程 pid，进程间识别。
 | 原文链接：http://wiki.kuulyb.asia/arts/316701.Doc

原标题：golang 结构体 json 序列化坑点
简介：golang 分布式锁 redis 实现，基于 Redis 实现 Go 分布式锁，解决多实例并发竞争资源问题。
 | 原文链接：http://wiki.kuulyb.asia/arts/715295.Doc

原标题：golang 系统设计 cpu 高占用排查步骤
简介：定时任务重复执行分布式锁，使用分布式锁控制定时任务，保证集群环境定时任务只会执行一次。
 | 原文链接：http://wiki.kuulyb.asia/arts/521032.Doc

原标题：golang redis 热点 key 业务规避
简介：Redis 内存淘汰策略数据防丢失，合理配置 Redis 内存淘汰策略，防止内存满后误删除业务重要数据。
 | 原文链接：http://wiki.kuulyb.asia/arts/271464.Doc

原标题：优化实践：预加载与懒加载业务场景取舍
简介：GitHub Markdown 文档语法汇总，整理 Markdown 常用语法，编写仓库 README、文档，提升开源项目文档排版质量。
 | 原文链接：http://wiki.kuulyb.asia/arts/845706.Doc

原标题：Hands‑on：手写简易ORM框架理解底层原理
简介：golang time.Ticker 泄漏常见场景，忘记 Stop Ticker，导致协程泄漏，定时器资源无法释放。
 | 原文链接：http://wiki.kuulyb.asia/arts/998288.Doc

原标题：入门实践：项目配置文件多环境管理方案
简介：开发测试生产多环境配置区分，讲解三套环境配置分离思路，配置文件隔离，防止开发配置泄露到生产环境。
 | 原文链接：http://wiki.kuulyb.asia/arts/601362.Doc

原标题：部署实践：多实例服务部署无状态改造
简介：Docker 容器时区错误修复方案，修复 Docker 容器内部时区偏差，解决容器内时间不对引发业务逻辑异常。
 | 原文链接：http://wiki.kuulyb.asia/arts/465633.Doc

原标题：golang 系统设计 jwt 安全使用避坑要点
简介：跨平台换行符统一异常修复，统一代码文件换行符，解决不同操作系统换行符不一致带来脚本执行异常。
 | 原文链接：http://wiki.kuulyb.asia/arts/976840.Doc

原标题：Practice：模拟第三方接口超时服务降级验证
简介：数据库排序规则统一结果一致，统一数据库表排序规则，解决不同环境查询排序结果不一致问题。
 | 原文链接：http://wiki.kuulyb.asia/arts/691921.Doc

原标题：golang github actions 发布 release 包
简介：限流规则误拦截正常请求修复，修正限流规则阈值，避免合法用户被限流拦截，兼顾防护与可用性。
 | 原文链接：http://wiki.kuulyb.asia/arts/233290.Doc

原标题：DevOps：多环境镜像标签版本管理规范
简介：golang context 超时取消实战案例，使用 context 控制协程、http 请求超时，自动终止超时任务，避免协程无限阻塞。
 | 原文链接：http://wiki.kuulyb.asia/arts/146044.Doc

原标题：golang docker 部署 mysql 注意事项
简介：Shell 运维脚本服务器效率提升，编写常用运维 Shell 脚本，自动化服务器运维操作，减少手工重复工作。
 | 原文链接：http://wiki.kuulyb.asia/arts/849074.Doc

原标题：文件锁正确使用避免死锁
简介：golang 限制 multipart 内存大小，设置 MaxMemory，大文件写入磁盘临时文件防止内存暴涨。
 | 原文链接：http://wiki.kuulyb.asia/arts/483128.Doc

原标题：性能复盘：慢查询日积月累拖垮数据库优化
简介：nodejs 多进程任务分发处理，多进程拆分处理 CPU 密集任务，主进程分发任务，利用多核提升处理速度。
 | 原文链接：http://wiki.kuulyb.asia/arts/146724.Doc

原标题：golang 系统设计采样策略降低链路存储开销
简介：golang go mod 私有 git 仓库配置，配置 go mod 拉取私有仓库代码，处理私有模块依赖拉取问题。
 | 原文链接：http://wiki.kuulyb.asia/arts/298639.Doc

原标题：Hands‑on：简易事件驱动架构原型开发
简介：golang 配置中心 apollo go 客户端，apollo go sdk 读取配置，配置变更自动热更新无需重启服务。
 | 原文链接：http://wiki.kuulyb.asia/arts/602143.Doc

原标题：调优方案：服务实例扩容，水平扩展性能
简介：golang rabbitmq 死信队列延迟消息，rabbitmq 实现死信、延迟消息，处理延时业务场景。
 | 原文链接：http://wiki.kuulyb.asia/arts/013465.Doc

原标题：golang 系统设计分表扩容数据平滑迁移思路
简介：golang nilnil interface 陷阱复现，interface 包含类型不为 nil 值为 nil，判 ==nil 返回 false 经典坑。
 | 原文链接：http://wiki.kuulyb.asia/arts/635747.Doc

原标题：golang 系统设计 gob msgpack 序列化对比
简介：本地运行正常线上报错排查，对比本地与线上环境差异，从配置、系统版本、文件权限定位线上独有的 bug。
 | 原文链接：http://wiki.kuulyb.asia/arts/079499.Doc

原标题：Practice：实现数据库连接池简易模拟实现
简介：golang http client 连接池调优，调优 Go HTTP Client 连接池参数，复用 TCP 连接，减少连接创建开销。
 | 原文链接：http://wiki.kuulyb.asia/arts/037168.Doc

原标题：Hands‑on：简易反向代理中间件实现
简介：配置外部化线上部署防错误，把配置从代码剥离，外部传入配置，修改配置不需要重新打包构建。
 | 原文链接：http://wiki.kuulyb.asia/arts/383610.Doc

原标题：golang 系统设计技术文档维护更新最佳实践
简介：文件读写与异常捕获代码示例，演示文件读取写入操作，增加异常捕获逻辑，规避文件不存在、权限不足导致崩溃。
 | 原文链接：http://wiki.kuulyb.asia/arts/971026.Doc

原标题：golang docker 容器资源限制设置
简介：golang base64 编码解码实操，Go Base64 编码解码示例，处理业务场景 Base64 格式数据转换。
 | 原文链接：http://wiki.kuulyb.asia/arts/562152.Doc

原标题：Architecture：鉴权授权系统架构设计思路
简介：前端 pdf 预览渲染方案对比，对比前端 PDF 预览库，分析性能、兼容性，给出业务选型参考。
 | 原文链接：http://wiki.kuulyb.asia/arts/487418.Doc

原标题：Issue：日志输出包含敏感信息造成泄露风险
简介：golang go 领域驱动 DDD 项目分层，go 项目 DDD 分层架构，领域层应用层基础设施层划分业务代码。
 | 原文链接：http://wiki.kuulyb.asia/arts/575105.Doc

原标题：golang minio 预签名 url 临时访问
简介：日志切割配置防止日志丢失，配置日志切割轮转策略，日志按大小时间切割，防止日志文件丢失。
 | 原文链接：http://wiki.kuulyb.asia/arts/594398.Doc

原标题：效率笔记：Makefile项目构建脚本编写实践
简介：nodejs 脚手架工具开发完整教程，从零开发 Node 命令行脚手架，实现项目模板生成，理解 CLI 开发。
 | 原文链接：http://wiki.kuulyb.asia/arts/871999.Doc

原标题：实战：对象存储断点续传下载实践
简介：golang httptest 模拟外部 http 服务，httptest.NewServer 模拟第三方 http 服务，单元测试 mock 外部接口。
 | 原文链接：http://wiki.kuulyb.asia/arts/965349.Doc

原标题：前端图片懒加载性能优化
简介：golang go 测试文件命名规范，_test.go 测试文件，TestXxx 单元测试函数命名规范。
 | 原文链接：http://wiki.kuulyb.asia/arts/805009.Doc

原标题：golang 系统设计 gob msgpack 序列化对比
简介：golang 互斥锁读写锁并发安全，互斥锁读写锁实操，保护共享变量，解决多协程并发读写数据竞争。
 | 原文链接：http://wiki.kuulyb.asia/arts/374897.Doc

原标题：快速上手调试工具定位简单代码错误
简介：golang gorm 索引设置与优化技巧，定义数据库索引，理解索引生效条件，避免索引失效慢查询。
 | 原文链接：http://wiki.kuulyb.asia/arts/852302.Doc

原标题：文件读写与异常捕获代码示例
简介：golang jwt 鉴权中间件完整示例，Gin JWT 鉴权中间件，令牌校验，解析用户信息，接口鉴权拦截。
 | 原文链接：http://wiki.kuulyb.asia/arts/272663.Doc


二、踩坑排错｜Troubleshooting
原标题：架构复盘：服务灰度发布架构设计与流量切分
简介：golang mime 类型检测文件，mime 识别文件 mime 类型，设置 http 响应 Content‑Type。
 | 原文链接：http://wiki.kuulyb.asia/arts/689591.Doc

原标题：坑点：npm/pip全局版本与项目本地版本冲突
简介：golang proto 默认值坑点梳理，梳理 Protobuf 默认值坑，零值字段区分未赋值，避免业务逻辑错误。
 | 原文链接：http://wiki.kuulyb.asia/arts/599480.Doc

原标题：踩坑：大事务引发数据库连接池耗尽
简介：golang 项目 go mod 依赖管理，Go Mod 管理项目依赖，下载、升级、清理依赖，解决依赖版本管理。
 | 原文链接：http://wiki.kuulyb.asia/arts/923691.Doc

原标题：实战：对象存储断点续传下载实践
简介：正则表达式文本处理实战案例，结合业务场景演示正则匹配、提取、替换，处理手机号、邮箱等各类文本校验需求。
 | 原文链接：http://wiki.kuulyb.asia/arts/486639.Doc

原标题：golang 结构体深拷贝几种实现
简介：golang 消息队列实现事务消息方案，基于 kafka 实现事务消息，业务执行成功才对外投递消息。
 | 原文链接：http://wiki.kuulyb.asia/arts/608123.Doc

原标题：前端错误监控上报系统搭建
简介：全平台系统环境变量配置，汇总多操作系统环境变量配置方法，统一项目读取逻辑，适配不同运行平台。
 | 原文链接：http://wiki.kuulyb.asia/arts/415899.Doc

原标题：踩坑记录：浮点数作为Rediskey匹配异常
简介：Redis 分布式锁高并发安全实现，基于 Redis 实现分布式锁，处理锁过期、续期，保障集群并发安全。
 | 原文链接：http://wiki.kuulyb.asia/arts/489066.Doc

原标题：坑点：依赖缓存未更新，旧代码持续运行
简介：数值类型溢出错乱问题修复，选择合适数值存储类型，处理数值溢出，避免数据存储错乱结果异常。
 | 原文链接：http://wiki.kuulyb.asia/arts/821432.Doc

原标题：Security：密码存储哈希加盐最佳实践
简介：多版本开发环境共存配置，实现同一工具多版本并存，快速切换不同版本，适配不同项目对版本的差异化需求。
 | 原文链接：http://wiki.kuulyb.asia/arts/128490.Doc

原标题：golang mysql 长连接短连接对比
简介：多实例部署 Session 共享方案，多服务实例部署场景，实现 Session 共享，保证用户登录状态跨实例生效。
 | 原文链接：http://wiki.kuulyb.asia/arts/964443.Doc

原标题：golang 系统设计开源项目 issue pr 模板编写
简介：Git commit 钩子提交规范校验，配置 Git 提交钩子，提交代码自动校验提交信息格式，规范提交记录。
 | 原文链接：http://wiki.kuulyb.asia/arts/458924.Doc

原标题：内网 DNS 不稳定随机报错排查
简介：golang alertmanager 告警配置实践，alertmanager 配置告警路由，告警发送邮件钉钉，异常及时通知运维。
 | 原文链接：http://wiki.kuulyb.asia/arts/560661.Doc

原标题：入门实践：Git分支创建切换合并完整演示
简介：golang go mod graph 查看依赖关系，go mod graph 打印依赖树，定位间接依赖来源，解决版本冲突。
 | 原文链接：http://wiki.kuulyb.asia/arts/257255.Doc

原标题：golang 系统设计单元测试编写原则最佳实践
简介：golang http client Transport 参数调优，Transport 最大连接空闲连接，TLS 配置，http 客户端调优。
 | 原文链接：http://wiki.kuulyb.asia/arts/468129.Doc

原标题：排错：前端缓存304异常更新不及时
简介：golang defer 闭包变量捕获坑，defer 捕获循环变量引用，变量被复写，理解闭包变量捕获规则。
 | 原文链接：http://wiki.kuulyb.asia/arts/687501.Doc

原标题：踩坑：批量MQ消费失败直接无限重试消息爆炸
简介：nodejs 流处理大文件不占内存，使用 Node.js 流处理超大文件，边读边写，不需要全部加载进内存。
 | 原文链接：http://wiki.kuulyb.asia/arts/014062.Doc

原标题：Practice：实现异步任务结果查询回调实践
简介：golang 负载均衡轮询加权轮询实现，手写负载均衡算法，轮询、加权轮询分发请求到后端节点。
 | 原文链接：http://wiki.kuulyb.asia/arts/251662.Doc

原标题：golang 系统信号信号量处理
简介：golang redis hash 结构业务实战，使用 Redis Hash 存储对象数据，适合对象字段频繁更新业务场景。
 | 原文链接：http://wiki.kuulyb.asia/arts/409607.Doc

原标题：CLI 工具进度条交互效果开发
简介：多线程线程安全脏数据规避，梳理多线程共享变量，做好同步控制，避免并发修改产生脏数据。
 | 原文链接：http://wiki.kuulyb.asia/arts/025929.Doc

原标题：项目实践：Docker镜像安全扫描本地实操
简介：golang 分库分表 id 路由规则设计，分库分表 id 路由算法，id 映射库表，数据均匀打散避免热点分片。
 | 原文链接：http://wiki.kuulyb.asia/arts/518235.Doc

原标题：程序信号中断退出处理逻辑
简介：内存广播本地进程消息通知，实现进程内内存消息广播，进程内部模块之间事件通知解耦。
 | 原文链接：http://wiki.kuulyb.asia/arts/473212.Doc

原标题：golang 系统设计自动化测试 ci 流水线集成实操
简介：CORS 跨域问题多种解决方案，对比 CORS、代理等不同跨域方案优缺点，根据业务场景选择合适的跨域处理方式。
 | 原文链接：http://wiki.kuulyb.asia/arts/085479.Doc

原标题：golang 系统设计单元测试 mock 外部依赖技巧
简介：golang go url url.Values 参数编码，url.Values 构建 url 查询参数，自动处理参数 url 编码。
 | 原文链接：http://wiki.kuulyb.asia/arts/822274.Doc

原标题：golang cron 定时任务防并发执行
简介：golang go 测试文件命名规范，_test.go 测试文件，TestXxx 单元测试函数命名规范。
 | 原文链接：http://wiki.kuulyb.asia/arts/680843.Doc

原标题：效率笔记：Git高级命令日常开发高频使用汇总
简介：数据库主从延迟业务兼容处理，业务适配主从复制延迟，避免读取从库拿到还未同步完成旧数据。
 | 原文链接：http://wiki.kuulyb.asia/arts/358230.Doc

原标题：Security：业务操作审计日志安全留存
简介：golang 终端交互式输入选择，命令行交互式问答选择输入，实现交互式脚本工具。
 | 原文链接：http://wiki.kuulyb.asia/arts/789503.Doc

原标题：Issue：文件句柄耗尽，服务缓慢卡死复盘
简介：golang redis 客户端业务使用，Go Redis 客户端对接，实现缓存、计数器，适配各类 Redis 业务场景。
 | 原文链接：http://wiki.kuulyb.asia/arts/967948.Doc

原标题：golang k8s secret 加密敏感信息
简介：文件监控服务自动重启开发，监控项目文件变更，代码修改自动重启服务，提升本地开发调试效率。
 | 原文链接：http://wiki.kuulyb.asia/arts/570398.Doc

原标题：golang 系统设计缓存过期时间设置原则梳理
简介：golang mongodb go 驱动实操教程，mongo‑go‑driver 操作 mongodb，文档增删改查聚合查询。
 | 原文链接：http://wiki.kuulyb.asia/arts/672622.Doc

原标题：内存泄漏定位分析完整流程
简介：golang go 泛型实现通用数据结构，泛型实现通用栈队列，复用逻辑支持多种数据类型。
 | 原文链接：http://wiki.kuulyb.asia/arts/129570.Doc

原标题：golang 系统设计线程协程泄露定位方法
简介：用户敏感数据脱敏代码实现，编写数据脱敏工具，对手机号、身份证做脱敏处理，防止敏感信息直接泄露。
 | 原文链接：http://wiki.kuulyb.asia/arts/352505.Doc

原标题：设计思考：大促系统架构压测改造整体思路
简介：golang jaeger 链路追踪部署对接，jaeger 接收 opentelemetry 链路数据，可视化完整调用链路。
 | 原文链接：http://wiki.kuulyb.asia/arts/090426.Doc

原标题：golang 系统设计消息队列解耦削峰
简介：Cookie Session 会话状态管理，讲解 Cookie 与 Session 原理，理解登录状态保存，实现服务端会话管理逻辑。
 | 原文链接：http://wiki.kuulyb.asia/arts/626907.Doc

原标题：开源源码阅读拆解学习思路
简介：golang 空接口 interface {} 类型处理，interface {} 存储任意类型，类型转换，处理泛型之前通用数据。
 | 原文链接：http://wiki.kuulyb.asia/arts/107467.Doc

原标题：定时任务重复执行分布式锁
简介：日志切割配置防止日志丢失，配置日志切割轮转策略，日志按大小时间切割，防止日志文件丢失。
 | 原文链接：http://wiki.kuulyb.asia/arts/348543.Doc

原标题：golang k8s 网络策略网络隔离设置
简介：golang url 参数编码处理方案，Go URL 参数编码解码，处理特殊字符，避免 URL 参数错乱。
 | 原文链接：http://wiki.kuulyb.asia/arts/394467.Doc

原标题：项目实践：数据库慢日志采集分析落地实践
简介：golang go 领域驱动 DDD 项目分层，go 项目 DDD 分层架构，领域层应用层基础设施层划分业务代码。
 | 原文链接：http://wiki.kuulyb.asia/arts/148759.Doc

原标题：golang 工具函数库封装思路
简介：缓存穿透击穿雪崩全套防护，完整梳理缓存三大问题，落地全套防护策略，保障缓存层稳定运行。
 | 原文链接：http://wiki.kuulyb.asia/arts/872983.Doc

原标题：避坑：CookieSecure属性造成测试环境登录失败
简介：前后端交互跨域问题完整处理，讲解跨域产生原理，列举多种解决方案，适配开发、生产不同环境的跨域处理。
 | 原文链接：http://wiki.kuulyb.asia/arts/640316.Doc

原标题：性能笔记：连接池参数调优数据库RPC连接池
简介：golang go‑pg postgres 客户端实操，go‑pg 操作 PostgreSQL 数据库，CRUD 关联查询业务开发。
 | 原文链接：http://wiki.kuulyb.asia/arts/962341.Doc

三、实战开发｜Practice
原标题：踩坑记录：文件描述符不足，上传功能随机失败
简介：golang oss 签名 URL 临时访问，生成 oss 临时签名 url，限时访问私有文件，保障文件访问安全可控。
 | 原文链接：http://wiki.kuulyb.asia/arts/557335.Doc

原标题：安全笔记：JWT安全风险，签名泄露过期控制
简介：新手参与开源社区贡献指南，介绍开源社区基础规则，讲解阅读 issue、提交 PR 流程，指导开发者参与开源贡献。
 | 原文链接：http://wiki.kuulyb.asia/arts/338743.Doc

原标题：Performance：数据库分表解决单表过大性能衰减
简介：CI 流水线超时时间延长配置，调大 CI 任务超时阈值，解决构建任务耗时较长被流水线强制终止。
 | 原文链接：http://wiki.kuulyb.asia/arts/964064.Doc

原标题：入门实战：搭建简易静态网页项目
简介：golang math 包常用数学函数，绝对值取整平方根三角函数，业务数学计算工具。
 | 原文链接：http://wiki.kuulyb.asia/arts/215418.Doc

原标题：线上接口超时故障排查思路
简介：服务健康检查监控接口开发，开发健康检查接口，反馈服务运行状态，供编排工具监控服务存活状态。
 | 原文链接：http://wiki.kuulyb.asia/arts/306254.Doc

原标题：安全复盘：日志打印敏感信息泄露治理
简介：golang nats jetstream 持久消息队列，nats jetstream 持久化消息，保证消息不丢失，实现可靠消费。
 | 原文链接：http://wiki.kuulyb.asia/arts/755286.Doc

原标题：golang 系统设计 graphql 接口优缺点梳理
简介：RPC 接口字段增减兼容处理，RPC 接口新增删除字段做好向前兼容，老版本服务不会解析报错崩溃。
 | 原文链接：http://wiki.kuulyb.asia/arts/544506.Doc

原标题：API 大版本不兼容平滑迁移
简介：浏览器缓存强制刷新方案，设置 HTTP 缓存头，处理浏览器缓存旧静态资源，让用户加载更新后的页面。
 | 原文链接：http://wiki.kuulyb.asia/arts/709913.Doc

原标题：前端下载导出文件功能实现
简介：golang redis lua 脚本原子操作，使用 Lua 脚本实现原子逻辑，减少网络往返，保障多命令原子执行。
 | 原文链接：http://wiki.kuulyb.asia/arts/197917.Doc

原标题：golang 系统设计数据库连接池调优实践
简介：golang redis pipeline 与 txpipeline 区别，区分普通管道与事务管道，根据业务场景选择合适批量执行方案。
 | 原文链接：http://wiki.kuulyb.asia/arts/394139.Doc

原标题：golang 系统设计线上日志快速检索技巧
简介：golang 灰度发布流量权重路由实现，根据权重切分流量，部分流量访问新版本服务，实现灰度发布。
 | 原文链接：http://wiki.kuulyb.asia/arts/542341.Doc

原标题：golang mysql 事务回滚异常处理
简介：golang gorm 预加载关联查询优化，GORM 预加载关联数据，避免 N+1 查询问题，提升数据库查询性能。
 | 原文链接：http://wiki.kuulyb.asia/arts/831806.Doc

原标题：golang 优雅停机服务关闭实现
简介：golang go 代码覆盖率线上统计，单元测试覆盖率统计，找出未测试代码分支，提升测试质量。
 | 原文链接：http://wiki.kuulyb.asia/arts/066004.Doc

原标题：优化实践：读写分离分担主库查询压力
简介：golang 接口限流中间件开发，Gin 开发限流中间件，接口层实现访问频率限制，防护接口流量。
 | 原文链接：http://wiki.kuulyb.asia/arts/793264.Doc

原标题：golang git 提交信息规范校验
简介：golang goroutine 泄露常见场景汇总，channel 阻塞、context 忘记取消，导致协程无法退出发生泄露。
 | 原文链接：http://wiki.kuulyb.asia/arts/686528.Doc

原标题：golang grafana 面板变量模板制作
简介：网关超时时间调优后端等待，调大网关向后端转发请求超时时间，给后端业务充足处理时间。
 | 原文链接：http://wiki.kuulyb.asia/arts/717899.Doc

原标题：新手教程：gitstash暂存工作区变更实操
简介：golang 故障演练服务模拟超时报错，程序模拟接口超时、报错，做混沌测试验证熔断降级有效性。
 | 原文链接：http://wiki.kuulyb.asia/arts/449130.Doc

原标题：golang 系统设计缓存热点 key 问题业务规避
简介：golang go 网络编程 net 包基础，net 包 tcp udp socket 编程，监听接收连接，读写数据。
 | 原文链接：http://wiki.kuulyb.asia/arts/369700.Doc

原标题：业务错误码完整落地实践
简介：golang 协程 panic 捕获防止崩溃，协程内部捕获 panic，防止单个协程恐慌造成整个 Go 进程崩溃。
 | 原文链接：http://wiki.kuulyb.asia/arts/691780.Doc

原标题：部署实践：HTTPS证书自动续期配置实践
简介：包管理器依赖冲突解决方案，分析依赖冲突产生根源，提供版本调整、锁定依赖等手段，解决项目依赖报错问题。
 | 原文链接：http://wiki.kuulyb.asia/arts/244540.Doc

原标题：实战：gRPC服务编写客户端服务端完整demo
简介：golang 漏桶算法实现接口限流，漏桶算法控制请求流出速率，平滑突发流量，削平流量峰值。
 | 原文链接：http://wiki.kuulyb.asia/arts/868362.Doc

原标题：ServiceWorker 缓存页面更新清理
简介：golang cobra 命令行参数配置绑定，cobra 绑定配置文件环境变量命令行参数，多源配置合并。
 | 原文链接：http://wiki.kuulyb.asia/arts/621675.Doc

原标题：Security：文件上传漏洞攻击面完整防护方案
简介：正则表达式文本处理实战案例，结合业务场景演示正则匹配、提取、替换，处理手机号、邮箱等各类文本校验需求。
 | 原文链接：http://wiki.kuulyb.asia/arts/990089.Doc

原标题：实战：接口压力测试实操，定位系统瓶颈
简介：golang go 项目 CI github actions 配置，github actions 实现 go 项目 ci，自动测试、代码检查、编译打包镜像。
 | 原文链接：http://wiki.kuulyb.asia/arts/199128.Doc

原标题：接口压测定位系统性能瓶颈
简介：express 请求参数校验处理，接入参数校验库，校验入参，拦截非法参数，提前拦截错误请求。
 | 原文链接：http://wiki.kuulyb.asia/arts/524914.Doc

原标题：设计思考：防雪崩，系统过载保护架构设计
简介：golang 模糊测试 go fuzz 基础编写，Fuzz 测试函数，自动生成随机输入，发现代码崩溃 panic。
 | 原文链接：http://wiki.kuulyb.asia/arts/968338.Doc

原标题：golang mysql exists in 性能对比
简介：golang redis lua 脚本原子操作，使用 Lua 脚本实现原子逻辑，减少网络往返，保障多命令原子执行。
 | 原文链接：http://wiki.kuulyb.asia/arts/887465.Doc

原标题：golang docker 部署 prometheus 整套
简介：golang go work 多模块本地开发，go work 多模块本地同时开发，本地模块互相引用，无需推送仓库。
 | 原文链接：http://wiki.kuulyb.asia/arts/405318.Doc

原标题：golang ip 限流黑名单实现方案
简介：golang os 打开文件 O_APPEND O_CREATE 标志，OpenFile 标志位，控制文件创建追加截断行为。
 | 原文链接：http://wiki.kuulyb.asia/arts/809745.Doc

原标题：项目实践：搭建个人API网关最小实现版本
简介：golang goroutine 泄露常见场景汇总，channel 阻塞、context 忘记取消，导致协程无法退出发生泄露。
 | 原文链接：http://wiki.kuulyb.asia/arts/541679.Doc

原标题：golang 系统设计布隆过滤器拦截不存在 key
简介：nodejs 数据库连接池配置调优，调优 Node 数据库连接池参数，平衡性能与资源占用，避免连接耗尽。
 | 原文链接：http://wiki.kuulyb.asia/arts/347917.Doc

原标题：文件监控服务自动重启开发
简介：golang go 泛型约束与类型集合，泛型 type set 约束，限制泛型支持类型，写出安全泛型代码。
 | 原文链接：http://wiki.kuulyb.asia/arts/833318.Doc

原标题：golang docker compose 环境变量
简介：Nginx 缓冲区调优大文件上传，调大 Nginx 请求缓冲区，支持客户端上传大体积文件，避免上传被截断。
 | 原文链接：http://wiki.kuulyb.asia/arts/421509.Doc

原标题：运维笔记：服务器日志轮转logrotate配置
简介：golang strconv 字符串类型转换，字符串转数字布尔，处理转换失败 error，避免 panic。
 | 原文链接：http://wiki.kuulyb.asia/arts/548506.Doc

原标题：Hands‑on：编写shell健康检查自动重启脚本
简介：golang redis scan 遍历 key 避免阻塞，使用 scan 迭代遍历 redis 键，不用 keys 命令，防止阻塞 redis 服务。
 | 原文链接：http://wiki.kuulyb.asia/arts/326707.Doc

原标题：Hands‑on：模拟RPC超时重试业务异常场景
简介：golang bufio.Scanner 缓冲区调大，Scanner 默认缓冲区大小不够，读取超长行需要扩大缓冲区。
 | 原文链接：http://wiki.kuulyb.asia/arts/372334.Doc

原标题：简易网关请求路由过滤模拟
简介：golang select 随机分支执行特性，多个 channel 就绪 select 随机选择，理解 select 行为特性。
 | 原文链接：http://wiki.kuulyb.asia/arts/981840.Doc

原标题：开发记录：业务错误告警邮件通知组件实践
简介：golang time.After 内存泄漏场景，for 循环使用 time.After 会创建大量 timer，造成内存泄漏。
 | 原文链接：http://wiki.kuulyb.asia/arts/600916.Doc

原标题：实战项目：Nginx限速、限流、防爬虫配置实践
简介：nodejs 集成测试业务流程编写，编写 Node 集成测试，调用真实接口，验证完整业务链路执行结果。
 | 原文链接：http://wiki.kuulyb.asia/arts/668834.Doc

原标题：Hands‑on：代码生成器，一键生成CRUD模板
简介：nestjs 拦截器过滤器管道实战，实操 Nest 拦截器、异常过滤器、管道校验，处理请求与响应统一逻辑。
 | 原文链接：http://wiki.kuulyb.asia/arts/002471.Doc

四、架构设计｜Architecture
原标题：包管理器依赖冲突解决方案
简介：golang 跨域处理中间件编写，Gin 跨域中间件开发，处理预检 OPTIONS 请求，解决浏览器跨域报错。
 | 原文链接：http://wiki.kuulyb.asia/arts/922141.Doc

原标题：Git 代码冲突正确处理方式
简介：golang 分库分表 id 路由规则设计，分库分表 id 路由算法，id 映射库表，数据均匀打散避免热点分片。
 | 原文链接：http://wiki.kuulyb.asia/arts/931568.Doc

原标题：golang 系统设计配置多环境隔离方案落地
简介：golang grpc 负载均衡客户端实现，grpc 客户端负载均衡，轮询随机权重，分发请求到多个服务实例。
 | 原文链接：http://wiki.kuulyb.asia/arts/738921.Doc

原标题：入门实践：简易导出导入文件功能实现
简介：移动端适配 rem vw 方案对比，对比 rem 与 vw 移动端适配方案，分析优缺点，给出选型建议。
 | 原文链接：http://wiki.kuulyb.asia/arts/760920.Doc

原标题：Hands‑on：简易代理服务器开发实践
简介：golang go select 多路等待 channel，select 等待多个 channel，default 非阻塞，超时等待 channel。
 | 原文链接：http://wiki.kuulyb.asia/arts/479620.Doc

原标题：Issue：日志输出包含敏感信息造成泄露风险
简介：golang gorm 事务手动回滚提交，手动控制事务流程，业务异常主动回滚，保障数据操作原子性。
 | 原文链接：http://wiki.kuulyb.asia/arts/234415.Doc

原标题：Git 误提交撤销回退实操教程
简介：golang go 服务蓝绿发布实践思路，蓝绿两套实例，流量一键切换，回滚快速降低发布风险。
 | 原文链接：http://wiki.kuulyb.asia/arts/240491.Doc

原标题：CLI 批量处理工具文件操作开发
简介：布隆过滤器数据高效去重实现，实现布隆过滤器组件，用于海量数据去重，节省大量内存空间。
 | 原文链接：http://wiki.kuulyb.asia/arts/818830.Doc

原标题：golang 系统设计架构图绘图工具选型对比
简介：golang elasticsearch 客户端 golang 实操，es 客户端文档增删改查，条件搜索聚合统计对接搜索引擎。
 | 原文链接：http://wiki.kuulyb.asia/arts/520911.Doc

原标题：golang 系统设计网关限流熔断降级配置思路
简介：golang time.Ticker 泄漏常见场景，忘记 Stop Ticker，导致协程泄漏，定时器资源无法释放。
 | 原文链接：http://wiki.kuulyb.asia/arts/372139.Doc

原标题：golang prometheus histogram 指标
简介：golang redis scan 遍历 key 避免阻塞，使用 scan 迭代遍历 redis 键，不用 keys 命令，防止阻塞 redis 服务。
 | 原文链接：http://wiki.kuulyb.asia/arts/865699.Doc

原标题：OpenSource：开源项目风险评估依赖安全检查
简介：golang go 线上故障排查完整流程，CPU 高、内存上涨、接口超时、goroutine 泄露一套排查处理流程。
 | 原文链接：http://wiki.kuulyb.asia/arts/333986.Doc

原标题：golang 系统设计状态字段枚举约束设计思路
简介：开发代理服务网络限制解决，搭建本地代理服务，解决开发环境网络访问受限，实现外部接口正常调用。
 | 原文链接：http://wiki.kuulyb.asia/arts/163487.Doc

原标题：golang 系统设计令牌桶漏桶算法对比
简介：golang docker 多阶段构建 go 镜像，Go 项目 Docker 多阶段构建，编译与运行阶段分离，大幅度缩减最终镜像体积，提升镜像分发效率。
 | 原文链接：http://wiki.kuulyb.asia/arts/777837.Doc

原标题：方案设计：异步解耦业务架构边界识别
简介：golang go 输入数据校验防御，所有外部入参严格校验长度格式，防止恶意输入造成业务异常。
 | 原文链接：http://wiki.kuulyb.asia/arts/851571.Doc

原标题：坑点：gitrebase操作失误，代码提交丢失
简介：golang math 包常用数学函数，绝对值取整平方根三角函数，业务数学计算工具。
 | 原文链接：http://wiki.kuulyb.asia/arts/590869.Doc

原标题：golang 系统设计重试退避策略业务落地
简介：依赖版本冲突兼容修复方案，定位依赖版本冲突根源，通过版本约束、替换包，解决版本不兼容运行报错。
 | 原文链接：http://wiki.kuulyb.asia/arts/348482.Doc

原标题：golang 系统设计性能瓶颈定位完整方法论
简介：golang go 网络编程 net 包基础，net 包 tcp udp socket 编程，监听接收连接，读写数据。
 | 原文链接：http://wiki.kuulyb.asia/arts/181985.Doc

?
