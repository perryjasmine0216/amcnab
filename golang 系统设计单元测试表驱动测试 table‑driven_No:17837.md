最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计单元测试表驱动测试 table‑driven
简介：golang go 变量逃逸场景汇总，切片、指针、返回局部变量引发逃逸，变量分配到堆影响 GC。
 | 原文链接：http://book.yihduf.asia/blog/127079.Doc

原标题：nodejs 内存溢出问题排查修复
简介：golang nats jetstream 持久消息队列，nats jetstream 持久化消息，保证消息不丢失，实现可靠消费。
 | 原文链接：http://book.yihduf.asia/blog/106577.Doc

原标题：golang mongodb 索引优化查询速度
简介：golang grpc keepalive 保活配置，grpc keepalive 参数调优，检测断开僵死连接，释放无效连接资源。
 | 原文链接：http://book.yihduf.asia/blog/990919.Doc

原标题：Practice：实现数据库事务消息最终一致性demo
简介：TCP 心跳检测清理僵死连接，开启 TCP 心跳机制，自动清理僵死无效连接，释放连接资源。
 | 原文链接：http://book.yihduf.asia/blog/871035.Doc

原标题：Debug：分页偏移量过大数据库查询性能暴跌
简介：golang http 服务并发连接数限制，自定义 listener 统计连接数量，限制最大并发连接数保护服务。
 | 原文链接：http://book.yihduf.asia/blog/603294.Doc

原标题：性能复盘：数据库回滚日志过大性能影响优化
简介：数值 key 浮点匹配异常规避，避免浮点数作为 Redis 等存储的 key，防止精度问题引发 key 匹配失败。
 | 原文链接：http://book.yihduf.asia/blog/552603.Doc

原标题：入门实战：搭建简易静态网页项目
简介：环境变量不生效问题修复，排查环境变量加载顺序、作用域问题，修复环境变量读取不到的异常。
 | 原文链接：http://book.yihduf.asia/blog/882506.Doc

原标题：golang kafka 消息丢失重复消费
简介：golang context 超时取消实战案例，使用 context 控制协程、http 请求超时，自动终止超时任务，避免协程无限阻塞。
 | 原文链接：http://book.yihduf.asia/blog/844273.Doc

原标题：Debug：长连接未设置心跳，连接僵死不回收
简介：Nginx 透传真实客户端 IP 配置，配置 Nginx 把真实客户端 IP 传递后端服务，后端拿到访问者真实 IP。
 | 原文链接：http://book.yihduf.asia/blog/725725.Doc

原标题：复盘总结：分布式系统常见坑点汇总清单
简介：golang 字符串处理常用技巧汇总，字符串拼接、分割、替换、类型转换实操，规避字符串高频错误。
 | 原文链接：http://book.yihduf.asia/blog/054593.Doc

原标题：Hands‑on：简易速率限制中间件完整实现
简介：golang 读写分离 gorm 实现主从切换，gorm 配置主库写入从库查询，读写分离分担数据库查询压力。
 | 原文链接：http://book.yihduf.asia/blog/757247.Doc

原标题：部署实践：服务器防火墙安全组配置实践
简介：数据库排序规则统一结果一致，统一数据库表排序规则，解决不同环境查询排序结果不一致问题。
 | 原文链接：http://book.yihduf.asia/blog/331098.Doc

原标题：golang 系统设计缓存 key 淘汰雪崩防护思路
简介：golang 参数校验业务接口处理，Go 接口入参参数校验，拦截非法入参，减少业务层参数判断代码。
 | 原文链接：http://book.yihduf.asia/blog/640914.Doc

原标题：golang github actions 缓存依赖提速
简介：golang go embed 嵌入静态资源文件，使用 go embed 把静态文件编译进二进制，单文件部署携带静态资源。
 | 原文链接：http://book.yihduf.asia/blog/527942.Doc

原标题：死信队列处理消息阻塞业务
简介：日志切割配置防止日志丢失，配置日志切割轮转策略，日志按大小时间切割，防止日志文件丢失。
 | 原文链接：http://book.yihduf.asia/blog/296748.Doc

原标题：golang es 查询语句 DSL 实操
简介：服务健康检查告警监控体系，搭建健康检查加告警体系，服务异常及时推送告警通知运维人员。
 | 原文链接：http://book.yihduf.asia/blog/597254.Doc

原标题：架构复盘：多实例部署业务状态无状态改造
简介：golang strings.Builder 字符串高效拼接，strings.Builder 做字符串拼接，比 += 性能更高，减少内存拷贝。
 | 原文链接：http://book.yihduf.asia/blog/419829.Doc

原标题：golang mysql 索引失效常见场景
简介：golang recover 捕获 panic 使用边界，recover 只在 defer 内部生效，协程内部必须捕获本协程 panic。
 | 原文链接：http://book.yihduf.asia/blog/494315.Doc

原标题：记一次第三方回调IP变动未更新防火墙拦截
简介：golang go 依赖漏洞检测 govulncheck，govulncheck 扫描依赖安全漏洞，发现项目供应链风险。
 | 原文链接：http://book.yihduf.asia/blog/931120.Doc

原标题：golang 系统设计开源项目贡献指南 contributing
简介：接口限流逻辑简单模拟实现，编写简易限流逻辑，限制接口访问频次，保护服务，避免短时间大量请求压垮系统。
 | 原文链接：http://book.yihduf.asia/blog/828172.Doc

原标题：坑点：gitrebase操作失误，代码提交丢失
简介：golang 分库分表 id 路由规则设计，分库分表 id 路由算法，id 映射库表，数据均匀打散避免热点分片。
 | 原文链接：http://book.yihduf.asia/blog/334722.Doc

原标题：性能复盘：磁盘Swap大量使用系统卡顿优化
简介：Nginx 反向代理路由配置实战，配置 Nginx 反向代理，实现请求转发、路由分发，掌握 Nginx 基础配置能力。
 | 原文链接：http://book.yihduf.asia/blog/352760.Doc

原标题：部署复盘：容器资源限制CPU内存配置实践
简介：GC 垃圾回收优化降低 CPU 占用，调整 GC 参数，优化对象创建销毁，降低垃圾回收带来 CPU 开销。
 | 原文链接：http://book.yihduf.asia/blog/567285.Doc

原标题：运维笔记：备份策略数据库定时备份脚本
简介：golang go 自定义错误类型实现，自定义 error 结构体，携带错误码、堆栈信息，统一业务错误。
 | 原文链接：http://book.yihduf.asia/blog/608066.Doc

原标题：性能笔记：操作系统文件句柄、虚拟内存调优
简介：Mock 接口服务快速搭建实操，搭建模拟后端接口，自定义返回数据、延迟响应，前端开发阶段无需依赖真实后端服务。
 | 原文链接：http://book.yihduf.asia/blog/226008.Doc

原标题：Practice：实现多级缓存本地缓存+Redis实践
简介：golang jwt 鉴权中间件完整示例，Gin JWT 鉴权中间件，令牌校验，解析用户信息，接口鉴权拦截。
 | 原文链接：http://book.yihduf.asia/blog/298131.Doc

原标题：nodejs 脚手架工具开发完整教程
简介：缓存穿透击穿雪崩全套防护，完整梳理缓存三大问题，落地全套防护策略，保障缓存层稳定运行。
 | 原文链接：http://book.yihduf.asia/blog/569273.Doc

原标题：安全笔记：CORS跨域配置错误安全风险
简介：依赖版本冲突兼容修复方案，定位依赖版本冲突根源，通过版本约束、替换包，解决版本不兼容运行报错。
 | 原文链接：http://book.yihduf.asia/blog/907132.Doc

原标题：golang 系统设计 protobuf 枚举类型规范写法
简介：对象存储上传下载权限实操，演示对象存储文件上传、下载、访问权限设置，适配业务文件存储场景。
 | 原文链接：http://book.yihduf.asia/blog/014680.Doc

原标题：golang 系统设计配置回滚版本历史记录实现
简介：golang 跨平台系统差异处理方案，处理 windows linux mac 路径、信号、文件权限差异，代码跨平台兼容。
 | 原文链接：http://book.yihduf.asia/blog/644798.Doc

原标题：golang zap 日志按日期切割方案
简介：golang http 服务并发连接数限制，自定义 listener 统计连接数量，限制最大并发连接数保护服务。
 | 原文链接：http://book.yihduf.asia/blog/008766.Doc

原标题：多线程线程安全脏数据规避
简介：golang 跨平台系统差异处理方案，处理 windows linux mac 路径、信号、文件权限差异，代码跨平台兼容。
 | 原文链接：http://book.yihduf.asia/blog/818925.Doc

原标题：安全实践：SQL注入产生场景与完整防御手段
简介：空指针异常判空容错处理，讲解空指针产生场景，规范判空逻辑，增加容错，避免空指针直接造成程序崩溃。
 | 原文链接：http://book.yihduf.asia/blog/937207.Doc

原标题：Practice：实现批量任务失败断点续跑实践
简介：系统文件描述符上限调大，调高操作系统文件描述符上限，解决高并发场景打开文件报错。
 | 原文链接：http://book.yihduf.asia/blog/292492.Doc

原标题：nestjs 框架模块化项目搭建
简介：golang 系统调用跟踪 strace 排查 go 程序，strace 跟踪系统调用，定位文件网络 IO 慢的底层原因。
 | 原文链接：http://book.yihduf.asia/blog/792369.Doc

原标题：Issue：本地可以访问，容器内部网络不通
简介：golang 分布式事务 seata go 客户端，seata‑go 实现分布式事务，保证跨库业务数据最终一致性。
 | 原文链接：http://book.yihduf.asia/blog/046849.Doc

原标题：golang 系统设计回调异步处理防止超时阻塞
简介：数据库事务 ACID 原理讲解，拆解事务四大特性，理解事务隔离、原子性，明白事务如何保障数据安全。
 | 原文链接：http://book.yihduf.asia/blog/377167.Doc

原标题：项目实践：Docker镜像安全扫描本地实操
简介：golang go 泛型约束与类型集合，泛型 type set 约束，限制泛型支持类型，写出安全泛型代码。
 | 原文链接：http://book.yihduf.asia/blog/697913.Doc

原标题：数据库分表存储大表优化方案
简介：golang go 逃逸分析实操查看，go build‑gcflags=-m 查看逃逸分析，减少堆分配优化程序性能。
 | 原文链接：http://book.yihduf.asia/blog/286525.Doc

原标题：批量异步处理系统业务落地
简介：项目目录结构规范化最佳实践，梳理源码、配置、静态资源目录划分，规范项目布局，提升代码可读性和可维护性。
 | 原文链接：http://book.yihduf.asia/blog/966396.Doc


二、踩坑排错｜Troubleshooting
原标题：golang github actions 多平台构建
简介：Redis 分布式锁高并发安全实现，基于 Redis 实现分布式锁，处理锁过期、续期，保障集群并发安全。
 | 原文链接：http://book.yihduf.asia/blog/070215.Doc

原标题：设计思考：系统降级开关架构设计快速切流量
简介：golang go 程序版本号内置编译注入，编译时注入 git commit 版本号，程序运行输出版本便于排查。
 | 原文链接：http://book.yihduf.asia/blog/561456.Doc

原标题：入门实践：简单的请求封装与异常捕获
简介：golang go mod replace 本地模块替换，replace 替换模块为本地目录，修改第三方库本地调试。
 | 原文链接：http://book.yihduf.asia/blog/963865.Doc

原标题：单元测试用例编写入门实操
简介：golang tidb 数据库 go 项目适配，go 程序适配 tidb，兼容 mysql 协议，分布式数据库业务开发。
 | 原文链接：http://book.yihduf.asia/blog/478747.Doc

原标题：golang 系统设计分表分页排序业务实现难点
简介：golang time.Ticker 泄漏常见场景，忘记 Stop Ticker，导致协程泄漏，定时器资源无法释放。
 | 原文链接：http://book.yihduf.asia/blog/856576.Doc

原标题：golang 系统设计告警规则阈值设置方法论
简介：缓存穿透防护保护数据库，实现缓存穿透防护手段，拦截不存在的数据查询，避免请求直接打穿数据库。
 | 原文链接：http://book.yihduf.asia/blog/591696.Doc

原标题：Git 仓库瘦身加快克隆下载速度
简介：golang redis 客户端业务使用，Go Redis 客户端对接，实现缓存、计数器，适配各类 Redis 业务场景。
 | 原文链接：http://book.yihduf.asia/blog/182946.Doc

原标题：实战项目：搭建私有Docker镜像仓库本地实践
简介：golang 简单爬虫请求防封禁，简易 Go 爬虫实现，增加请求间隔、UA 伪装，规避被目标站点封禁 IP。
 | 原文链接：http://book.yihduf.asia/blog/130381.Doc

原标题：Performance：避免全表扫描索引失效场景汇总
简介：MySQL 慢查询索引优化实战，抓取慢查询 SQL，分析执行计划，新增或者调整索引，提升 SQL 执行速度。
 | 原文链接：http://book.yihduf.asia/blog/178916.Doc

原标题：golang gitlab runner 部署与注册实操
简介：golang html 模板渲染简单示例，Go HTML 模板渲染，服务端渲染页面，填充数据输出 HTML 页面。
 | 原文链接：http://book.yihduf.asia/blog/067995.Doc

原标题：Practice：简易限流器分布式版本Redis实现
简介：Redis 大 key 拆分集群卡顿解决，拆分 Redis 超大 Key，避免大 key 操作造成 Redis 集群卡顿阻塞。
 | 原文链接：http://book.yihduf.asia/blog/722124.Doc

原标题：Security：文件路径穿越漏洞完整防护
简介：golang go 爬虫请求速率控制，爬虫限频、代理轮换，设置 UA，防止爬虫被目标站点封禁 IP。
 | 原文链接：http://book.yihduf.asia/blog/754499.Doc

原标题：WebSocket 双向通信 demo 开发
简介：golang 消息死信处理业务逻辑，Go 实现死信队列逻辑，消费失败消息转入死信，不阻塞正常消息队列。
 | 原文链接：http://book.yihduf.asia/blog/755280.Doc

原标题：踩坑记录：浮点精度错误造成业务计算错误
简介：K8s 镜像拉取网络故障修复，排查 K8s 集群镜像拉取网络问题，配置镜像源，恢复镜像正常拉取。
 | 原文链接：http://book.yihduf.asia/blog/110359.Doc

原标题：实战项目：GitHubAction自动测试构建实践
简介：eslint prettier 代码规范落地，配置 eslint 与 prettier，做代码检查格式化，统一前端团队代码风格。
 | 原文链接：http://book.yihduf.asia/blog/334419.Doc

原标题：golang 系统设计内部服务调用超时设置要点
简介：golang jwt 鉴权中间件完整示例，Gin JWT 鉴权中间件，令牌校验，解析用户信息，接口鉴权拦截。
 | 原文链接：http://book.yihduf.asia/blog/338627.Doc

原标题：golang 系统设计线上故障排查完整流程
简介：golang dns 自定义解析器实现，自定义 dns 解析，指定 dns 服务器，控制域名解析逻辑，适配内网环境。
 | 原文链接：http://book.yihduf.asia/blog/843156.Doc

原标题：golang 系统设计防爬虫简单策略
简介：Redis 分布式锁高并发安全实现，基于 Redis 实现分布式锁，处理锁过期、续期，保障集群并发安全。
 | 原文链接：http://book.yihduf.asia/blog/663199.Doc

原标题：golang redis 客户端业务使用
简介：线程调度优化减少上下文切换，优化线程数量，减少线程频繁切换，降低 CPU 上下文切换开销。
 | 原文链接：http://book.yihduf.asia/blog/785996.Doc

原标题：nestjs 框架模块化项目搭建
简介：vite 插件开发自定义构建逻辑，开发自定义 vite 插件，介入构建生命周期，实现项目个性化构建逻辑。
 | 原文链接：http://book.yihduf.asia/blog/673388.Doc

原标题：数值 key 浮点匹配异常规避
简介：golang context.Background 与 TODO 区别，Background 主流程根上下文，TODO 不确定用哪个上下文时使用。
 | 原文链接：http://book.yihduf.asia/blog/442253.Doc

原标题：TLS 版本兼容 HTTPS 握手失败
简介：vite 插件开发自定义构建逻辑，开发自定义 vite 插件，介入构建生命周期，实现项目个性化构建逻辑。
 | 原文链接：http://book.yihduf.asia/blog/265871.Doc

原标题：新手指南：读懂项目构建脚本作用
简介：golang go panic 合理使用边界，panic 只用于不可恢复程序错误，业务逻辑禁止直接 panic。
 | 原文链接：http://book.yihduf.asia/blog/444220.Doc

原标题：Practice：实现接口防重提交组件实践
简介：gitignore 文件编写过滤规则，讲解 gitignore 语法，编写过滤配置，忽略缓存、编译产物、密钥文件，保持仓库整洁。
 | 原文链接：http://book.yihduf.asia/blog/805345.Doc

原标题：golang 系统设计降级策略开关配置方案
简介：API 接口调试与异常处理实战，覆盖接口请求、参数组装、错误捕获，提供调试思路，高效定位接口返回异常问题。
 | 原文链接：http://book.yihduf.asia/blog/008265.Doc

原标题：golang redis hyperloglog 基数统计
简介：项目构建脚本编译打包解析，解读项目构建脚本，理清编译、压缩、资源复制流程，理解打包后产物如何生成。
 | 原文链接：http://book.yihduf.asia/blog/856731.Doc

原标题：macOS 脚本执行权限开启
简介：消息队列消费堆积扩容处理，消息大量堆积时，扩容消费实例，优化消费逻辑，加快消息处理速度。
 | 原文链接：http://book.yihduf.asia/blog/416830.Doc

原标题：全局本地依赖隔离冲突规避
简介：项目脚手架模板生成工具，搭建项目模板脚手架，一键生成标准化项目骨架，减少重复初始化工作。
 | 原文链接：http://book.yihduf.asia/blog/565806.Doc

原标题：golang 系统设计并发控制协程池任务池实现
简介：Docker 容器网络不通排查，排查容器网络模式、端口映射、防火墙，解决容器之间、容器外部网络不通。
 | 原文链接：http://book.yihduf.asia/blog/672748.Doc

原标题：MySQL 慢查询索引优化实战
简介：线上接口超时故障排查思路，从网络、数据库、代码逻辑逐层排查接口超时，定位慢请求根因。
 | 原文链接：http://book.yihduf.asia/blog/171582.Doc

原标题：vite 项目配置与构建提速技巧
简介：golang 进程信号捕获 SIGUSR 自定义信号，捕获用户自定义信号，实现线上不重启触发调试、日志切换。
 | 原文链接：http://book.yihduf.asia/blog/695008.Doc

原标题：golang 分布式上下文传递方案
简介：vite 项目配置与构建提速技巧，讲解 vite 配置优化手段，提升开发热更新速度与生产构建打包效率。
 | 原文链接：http://book.yihduf.asia/blog/355842.Doc

原标题：线上故障：热点Key打满RedisCPU节点过载
简介：golang go decimal 定点小数金额计算，decimal 库处理金额，规避 float64 精度丢失，财务计算。
 | 原文链接：http://book.yihduf.asia/blog/441593.Doc

原标题：架构笔记：业务系统反模式架构踩坑总结
简介：golang tidb 数据库 go 项目适配，go 程序适配 tidb，兼容 mysql 协议，分布式数据库业务开发。
 | 原文链接：http://book.yihduf.asia/blog/144228.Doc

原标题：架构复盘：供应链安全架构依赖包风险治理
简介：分布式任务调度集群原型开发，开发简易分布式调度原型，集群多节点运行，保证任务只执行一次。
 | 原文链接：http://book.yihduf.asia/blog/711702.Doc

原标题：golang 系统设计技术债务识别登记治理思路
简介：Docker Compose 一键搭建本地栈，使用 Compose 编排多个容器，一键拉起全套开发依赖服务。
 | 原文链接：http://book.yihduf.asia/blog/951362.Doc

原标题：golang 错误包装 errors.wrap 用法
简介：golang http 代理客户端配置，Go HTTP Client 配置代理，通过代理服务器发起网络请求。
 | 原文链接：http://book.yihduf.asia/blog/004153.Doc

原标题：golang etcd 配置中心简单使用
简介：golang go 程序 CPU 占用高定位步骤，pprof 定位热点函数，分析 CPU 高占用，优化耗时代码逻辑。
 | 原文链接：http://book.yihduf.asia/blog/733368.Doc

原标题：golang 系统设计文件存储选型对比
简介：golang testify testify 断言库使用，testify assert require 断言，简化单元测试断言代码。
 | 原文链接：http://book.yihduf.asia/blog/175299.Doc

原标题：实战：单元测试+集成测试完整项目落地实践
简介：数值 key 浮点匹配异常规避，避免浮点数作为 Redis 等存储的 key，防止精度问题引发 key 匹配失败。
 | 原文链接：http://book.yihduf.asia/blog/193312.Doc

三、实战开发｜Practice
原标题：golang 系统设计分表字段选择路由规则设计
简介：golang redis 过期键监听回调，监听 key 过期事件，过期触发业务逻辑，实现过期自动处理业务场景。
 | 原文链接：http://book.yihduf.asia/blog/146196.Doc

原标题：项目实践：数据库慢日志采集分析落地实践
简介：无用对象回收抑制内存上涨，优化对象生命周期，及时释放不再使用对象，抑制内存持续不断增长。
 | 原文链接：http://book.yihduf.asia/blog/710547.Doc

原标题：缓存过期打散防止缓存雪崩
简介：nodejs 单元测试 jest 实操教程，Jest 单元测试实操，编写测试用例，mock 依赖，验证业务逻辑正确性。
 | 原文链接：http://book.yihduf.asia/blog/465653.Doc

原标题：部署实践：HTTPS证书自动续期配置实践
简介：golang go 测试文件命名规范，_test.go 测试文件，TestXxx 单元测试函数命名规范。
 | 原文链接：http://book.yihduf.asia/blog/528141.Doc

原标题：golang 系统设计文件存储选型对比
简介：golang 云存储 s3 协议对象存储，go s3 客户端，兼容 minio 阿里云 oss，实现文件上传下载签名访问。
 | 原文链接：http://book.yihduf.asia/blog/895746.Doc

原标题：实战项目：实现分布式任务调度最小原型
简介：golang go json 序列化自定义字段，json 标签控制字段名称、忽略字段、omitempty 空值忽略。
 | 原文链接：http://book.yihduf.asia/blog/703719.Doc

原标题：golang 系统设计并发控制协程池任务池实现
简介：golang go mod graph 可视化依赖图，可视化 go 依赖关系，直观看到包之间依赖，定位冲突。
 | 原文链接：http://book.yihduf.asia/blog/447293.Doc

原标题：golang 系统设计监控告警体系搭建思路
简介：golang 命令行参数解析开发，解析命令行入参，开发自定义 CLI 程序，读取启动参数配置服务。
 | 原文链接：http://book.yihduf.asia/blog/463029.Doc

原标题：golang 系统设计 docker compose 本地开发环境搭建
简介：golang go 单二进制文件静态编译交叉编译，交叉编译不同操作系统架构二进制文件，实现一次编译多平台运行。
 | 原文链接：http://book.yihduf.asia/blog/302303.Doc

原标题：实践：API版本控制多种策略落地对比实践
简介：nodejs 进程间通信 IPC 实操，演示 Node.js 主进程子进程 IPC 通信，进程之间传递消息数据。
 | 原文链接：http://book.yihduf.asia/blog/334948.Doc

原标题：请求重试组件退避策略实现
简介：golang base64 编码解码实操，Go Base64 编码解码示例，处理业务场景 Base64 格式数据转换。
 | 原文链接：http://book.yihduf.asia/blog/304462.Doc

原标题：手写简易 MQ 理解消息存储消费
简介：布隆过滤器数据高效去重实现，实现布隆过滤器组件，用于海量数据去重，节省大量内存空间。
 | 原文链接：http://book.yihduf.asia/blog/078023.Doc

原标题：入门实践：项目配置文件多环境管理方案
简介：CI 流水线超时时间延长配置，调大 CI 任务超时阈值，解决构建任务耗时较长被流水线强制终止。
 | 原文链接：http://book.yihduf.asia/blog/970031.Doc

原标题：实战：Redis过期回调实现业务事件通知实践
简介：开发测试生产多环境配置区分，讲解三套环境配置分离思路，配置文件隔离，防止开发配置泄露到生产环境。
 | 原文链接：http://book.yihduf.asia/blog/154102.Doc

原标题：极简 API 网关路由转发实现
简介：golang go 项目工程目录布局标准，不同规模 go 项目目录结构，小型项目中型项目大型微服务项目布局。
 | 原文链接：http://book.yihduf.asia/blog/747502.Doc

原标题：入门实践：简单的请求封装与异常捕获
简介：golang trace 可视化分析协程阻塞，使用 trace 网页 UI，定位协程阻塞、系统调用阻塞、锁等待。
 | 原文链接：http://book.yihduf.asia/blog/538438.Doc

原标题：Troubleshooting：数据库索引失效，查询性能暴跌
简介：golang sync.Map 高并发 map 使用场景，sync.Map 适用场景，读写实操，对比普通 map 加锁性能差异。
 | 原文链接：http://book.yihduf.asia/blog/233669.Doc

原标题：部署复盘：数据库主从备份恢复演练实践
简介：DNS 解析异常第三方调用故障，排查 DNS 解析故障，修复域名解析，恢复第三方接口网络调用。
 | 原文链接：http://book.yihduf.asia/blog/556668.Doc

原标题：部署复盘：容器资源限制CPU内存配置实践
简介：golang atomic.Value 存储任意类型数据，atomic.Value 安全存储读取任意类型，配置热更新常用。
 | 原文链接：http://book.yihduf.asia/blog/031340.Doc

原标题：golang 系统设计指标聚合计算存储选型对比
简介：golang interface {} 类型断言类型转换，类型断言 ok 模式，避免断言失败触发 panic。
 | 原文链接：http://book.yihduf.asia/blog/410730.Doc

原标题：Hands‑on：手写简单消息队列理解存储模型
简介：golang viper 多源配置管理实操，viper 读取配置文件环境变量命令行参数，多源配置优先级管理。
 | 原文链接：http://book.yihduf.asia/blog/601399.Doc

原标题：golang 系统设计压测指标 qps rt 错误率讲解
简介：golang 优雅处理 http 重定向逻辑，自定义控制 http 重定向跳转次数，防止无限重定向死循环。
 | 原文链接：http://book.yihduf.asia/blog/417409.Doc

原标题：Troubleshooting：k8s镜像拉取失败镜像仓库网络问题
简介：golang 分页查询封装通用工具，封装 Go 通用分页工具，统一处理分页参数，简化业务分页接口开发。
 | 原文链接：http://book.yihduf.asia/blog/596326.Doc

原标题：Git 标签版本标记发布管理
简介：线上接口超时故障排查思路，从网络、数据库、代码逻辑逐层排查接口超时，定位慢请求根因。
 | 原文链接：http://book.yihduf.asia/blog/090179.Doc

原标题：golang redis zset 排行榜业务实现
简介：golang benchmark 减少测试干扰，benchmark 执行循环 b.N，避免循环内部做非被测逻辑干扰结果。
 | 原文链接：http://book.yihduf.asia/blog/031057.Doc

原标题：git rebase 整理提交历史实操
简介：配置外部化线上部署防错误，把配置从代码剥离，外部传入配置，修改配置不需要重新打包构建。
 | 原文链接：http://book.yihduf.asia/blog/454400.Doc

原标题：开发复盘：实现定时任务调度服务支持动态任务
简介：golang io.MultiReader MultiWriter 拼接流，多个 reader 拼接，多 writer 同时写入一份数据。
 | 原文链接：http://book.yihduf.asia/blog/012505.Doc

原标题：golang redis 缓存穿透解决方案
简介：Docker 容器时区错误修复方案，修复 Docker 容器内部时区偏差，解决容器内时间不对引发业务逻辑异常。
 | 原文链接：http://book.yihduf.asia/blog/422883.Doc

原标题：排错：GitLFS大文件推送失败完整排障
简介：golang sync/atomic 原子操作使用注意，理解原子操作内存顺序，规避原子操作错误使用带来 bug。
 | 原文链接：http://book.yihduf.asia/blog/952381.Doc

原标题：运维笔记：备份策略数据库定时备份脚本
简介：文件监控服务自动重启开发，监控项目文件变更，代码修改自动重启服务，提升本地开发调试效率。
 | 原文链接：http://book.yihduf.asia/blog/498669.Doc

原标题：golang 系统设计开源项目贡献指南 contributing
简介：golang gorm 预加载关联查询优化，GORM 预加载关联数据，避免 N+1 查询问题，提升数据库查询性能。
 | 原文链接：http://book.yihduf.asia/blog/833066.Doc

原标题：优化实践：接口返回字段裁剪减少报文大小
简介：本地数据库开发环境搭建指南，讲解数据库安装配置、账号权限设置、连接测试，快速搭建用于开发调试的数据库实例。
 | 原文链接：http://book.yihduf.asia/blog/466709.Doc

原标题：实战：容器内执行调试排错完整实操流程
简介：缓存穿透击穿雪崩全套防护，完整梳理缓存三大问题，落地全套防护策略，保障缓存层稳定运行。
 | 原文链接：http://book.yihduf.asia/blog/566149.Doc

原标题：前端水印防信息泄露实现
简介：nodejs 多进程任务分发处理，多进程拆分处理 CPU 密集任务，主进程分发任务，利用多核提升处理速度。
 | 原文链接：http://book.yihduf.asia/blog/078798.Doc

原标题：Practice：JWT工具封装，刷新令牌完整逻辑
简介：nodejs 全局异常捕获进程防护，捕获未捕获异常与 Promise 拒绝，尽量保护进程不因为异常直接退出。
 | 原文链接：http://book.yihduf.asia/blog/552478.Doc

原标题：Debug：请求头过大Nginx拒绝连接报错
简介：数据库分表存储大表优化方案，对超大数据表做分表，拆分数据，降低单表数据量提升查询性能。
 | 原文链接：http://book.yihduf.asia/blog/003595.Doc

原标题：安全实践：输入输出双向过滤安全最佳实践
简介：golang go 爬虫异步并发抓取，协程池控制并发抓取网页，多协程采集，提升爬虫采集速度。
 | 原文链接：http://book.yihduf.asia/blog/654246.Doc

原标题：golang 系统设计密钥轮换安全实践思路
简介：golang go 服务蓝绿发布实践思路，蓝绿两套实例，流量一键切换，回滚快速降低发布风险。
 | 原文链接：http://book.yihduf.asia/blog/918874.Doc

原标题：方案对比：几种任务队列架构选型优缺点
简介：golang go 项目工程目录布局标准，不同规模 go 项目目录结构，小型项目中型项目大型微服务项目布局。
 | 原文链接：http://book.yihduf.asia/blog/376887.Doc

原标题：Practice：批量异步任务处理系统设计实现
简介：前端 pdf 预览渲染方案对比，对比前端 PDF 预览库，分析性能、兼容性，给出业务选型参考。
 | 原文链接：http://book.yihduf.asia/blog/882303.Doc

四、架构设计｜Architecture
原标题：HelloGitHubPages：部署你的第一个静态博客
简介：golang 滑动窗口限流算法 go 实现，滑动窗口限流，解决固定窗口临界流量突增漏洞，限流更精准。
 | 原文链接：http://book.yihduf.asia/blog/887985.Doc

原标题：golang 系统设计网关错误重试超时处理策略
简介：golang 信号量控制并发数量，使用信号量控制并发，限制同时执行任务数量，保护下游资源。
 | 原文链接：http://book.yihduf.asia/blog/731288.Doc

原标题：hosts 配置本地回环访问修复
简介：golang 命令行参数解析开发，解析命令行入参，开发自定义 CLI 程序，读取启动参数配置服务。
 | 原文链接：http://book.yihduf.asia/blog/884973.Doc

原标题：golang 静态编译缩小镜像体积
简介：golang map 并发读写 panic 解决方案，map 非并发安全，讲解加锁、sync.map 方案解决并发读写崩溃。
 | 原文链接：http://book.yihduf.asia/blog/050997.Doc

原标题：实战：WebSocket断线重连完整业务处理实践
简介：golang go‑zero rpc 微服务开发，go‑zero 定义 proto，生成 rpc 服务代码，实现微服务调用。
 | 原文链接：http://book.yihduf.asia/blog/336740.Doc

原标题：Debug日志：生产环境偶发空指针异常排查
简介：golang oss 签名 URL 临时访问，生成 oss 临时签名 url，限时访问私有文件，保障文件访问安全可控。
 | 原文链接：http://book.yihduf.asia/blog/591032.Doc

原标题：安全笔记：第三方SDK安全风险评估要点
简介：golang errgroup 协程组错误处理，errgroup 捕获协程错误，context 取消剩余协程，简化并发任务。
 | 原文链接：http://book.yihduf.asia/blog/690258.Doc

原标题：Debug：预加载逻辑错误服务启动时间成倍拉长
简介：golang http 服务并发连接数限制，自定义 listener 统计连接数量，限制最大并发连接数保护服务。
 | 原文链接：http://book.yihduf.asia/blog/429802.Doc

原标题：golang redis 缓存雪崩完整处理
简介：数据库连接及时关闭连接泄漏，确保数据库连接使用完毕释放归还连接池，杜绝连接泄漏耗尽连接。
 | 原文链接：http://book.yihduf.asia/blog/398663.Doc

原标题：golang 系统设计 tcp 粘包拆包处理方案实现
简介：golang go 应用内存使用优化手段，减少对象分配，复用对象，降低 GC 压力，减少 GC 停顿时间。
 | 原文链接：http://book.yihduf.asia/blog/631754.Doc

原标题：golang 系统设计大表结构变更不停机方案
简介：Mock 接口服务快速搭建实操，搭建模拟后端接口，自定义返回数据、延迟响应，前端开发阶段无需依赖真实后端服务。
 | 原文链接：http://book.yihduf.asia/blog/239995.Doc

原标题：正则表达式文本处理实战案例
简介：golang 自定义 pprof 扩展业务指标，扩展 pprof，输出业务自定义指标，结合性能数据分析业务状态。
 | 原文链接：http://book.yihduf.asia/blog/043147.Doc

原标题：进程线程并发基础概念讲解
简介：golang proto 默认值坑点梳理，梳理 Protobuf 默认值坑，零值字段区分未赋值，避免业务逻辑错误。
 | 原文链接：http://book.yihduf.asia/blog/641517.Doc

原标题：Architecture：中小型后端服务整体架构设计复盘
简介：golang accept 错误循环崩溃处理，accept 返回系统错误，处理临时错误，避免死循环占满 CPU。
 | 原文链接：http://book.yihduf.asia/blog/045433.Doc

原标题：golang 系统设计 api 网关核心能力梳理
简介：golang 熔断降级简易组件开发，Go 简易熔断组件，下游故障触发熔断，保护上游服务不被拖垮。
 | 原文链接：http://book.yihduf.asia/blog/411995.Doc

原标题：golang redis set 集合去重业务
简介：golang 信号量控制并发数量，使用信号量控制并发，限制同时执行任务数量，保护下游资源。
 | 原文链接：http://book.yihduf.asia/blog/881849.Doc

原标题：golang 分布式锁防死锁处理
简介：vite 插件开发自定义构建逻辑，开发自定义 vite 插件，介入构建生命周期，实现项目个性化构建逻辑。
 | 原文链接：http://book.yihduf.asia/blog/660736.Doc

原标题：golang 系统设计 api 网关核心能力梳理
简介：Docker 多阶段构建镜像瘦身，使用 Docker 多阶段构建，剔除编译阶段依赖，产出体积更小运行镜像。
 | 原文链接：http://book.yihduf.asia/blog/414025.Doc

?
