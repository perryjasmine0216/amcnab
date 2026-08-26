最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计线上问题复现思路简单讲解
简介：golang go http 静态文件禁止目录遍历，http.FileServer 防止../ 路径穿越，了解底层安全实现。
 | 原文链接：http://wiki.06zzlj.asia/arts/744990.Doc

原标题：项目实践：定时任务防重复执行落地实践
简介：golang bufio.Scanner 按行读取大文件，Scanner 逐行读取文本文件，处理超大日志 csv。
 | 原文链接：http://wiki.06zzlj.asia/arts/263221.Doc

原标题：golang 系统设计缓存预热缓存降级实现
简介：golang 灰度发布流量权重路由实现，根据权重切分流量，部分流量访问新版本服务，实现灰度发布。
 | 原文链接：http://wiki.06zzlj.asia/arts/825824.Doc

原标题：优化实践：批量操作性能优化，减少数据库IO
简介：golang go 比较运算符可比较类型，哪些类型可以直接 == 比较，map slice 函数不可直接比较。
 | 原文链接：http://wiki.06zzlj.asia/arts/081516.Doc

原标题：优化实践：异步改造同步接口提升吞吐能力
简介：golang time.Ticker 泄漏常见场景，忘记 Stop Ticker，导致协程泄漏，定时器资源无法释放。
 | 原文链接：http://wiki.06zzlj.asia/arts/604866.Doc

原标题：布隆过滤器数据高效去重实现
简介：golang 雪花 id 重复问题排查，排查雪花算法 ID 重复问题，时钟回拨、机器 ID 冲突，给出修复方案。
 | 原文链接：http://wiki.06zzlj.asia/arts/692570.Doc

原标题：golang 系统设计时间字段选型 datetime timestamp
简介：跨库查询性能优化处理，减少跨库关联查询，做数据冗余或者中间表，规避跨库查询性能低下。
 | 原文链接：http://wiki.06zzlj.asia/arts/698222.Doc

原标题：安全复盘：环境变量密钥泄露风险与防护
简介：API 大版本不兼容平滑迁移，API 版本迭代不兼容旧接口，设计平滑迁移方案，逐步完成版本切换。
 | 原文链接：http://wiki.06zzlj.asia/arts/155097.Doc

原标题：golang 系统设计网关缓存静态资源实现思路
简介：Fork 开源项目同步上游代码，Fork 开源仓库之后，配置上游源，同步官方最新代码，保持代码版本对齐。
 | 原文链接：http://wiki.06zzlj.asia/arts/567411.Doc

原标题：golang 系统设计布隆过滤器拦截不存在 key
简介：golang 自定义 pprof 扩展业务指标，扩展 pprof，输出业务自定义指标，结合性能数据分析业务状态。
 | 原文链接：http://wiki.06zzlj.asia/arts/174257.Doc

原标题：Practice：实现异步任务结果查询回调实践
简介：服务器 Swap 关闭提升响应速度，关闭服务器 Swap 交换分区，避免内存交换磁盘拖慢程序响应性能。
 | 原文链接：http://wiki.06zzlj.asia/arts/907288.Doc

原标题：ServiceWorker 缓存页面更新清理
简介：golang 项目目录分层规范设计，Go 后端项目目录分层规范，按领域分层，提高项目可读性可维护性。
 | 原文链接：http://wiki.06zzlj.asia/arts/538039.Doc

原标题：golang 系统设计 http 接口基准测试实操示例
简介：系统时间同步定时任务偏移，同步服务器系统时间，防止时间偏移，避免定时任务执行时间错乱。
 | 原文链接：http://wiki.06zzlj.asia/arts/530972.Doc

原标题：golang 系统设计延迟队列业务实现
简介：golang http client 全局变量复用，http Client 不要每次请求新建，复用 Transport 提升性能。
 | 原文链接：http://wiki.06zzlj.asia/arts/347174.Doc

原标题：入门实践：本地简单代理服务搭建
简介：golang go 领域驱动 DDD 项目分层，go 项目 DDD 分层架构，领域层应用层基础设施层划分业务代码。
 | 原文链接：http://wiki.06zzlj.asia/arts/264445.Doc

原标题：快速入门日志打印与日志分级基础用法
简介：git cherry‑pick 规范操作防 bug，规范 cherry‑pick 使用流程，处理冲突，避免错误引入不兼容代码。
 | 原文链接：http://wiki.06zzlj.asia/arts/102677.Doc

原标题：特殊输入字符过滤解析防护
简介：golang snowflake 时钟回拨解决方案，雪花算法处理时钟回拨，防止生成重复 ID，保证 ID 全局唯一。
 | 原文链接：http://wiki.06zzlj.asia/arts/870483.Doc

原标题：代码格式化工具团队统一风格
简介：golang 大内存分配 GC 抖动规避，避免瞬时大量对象创建，分批处理，防止 GC 抖动业务抖动。
 | 原文链接：http://wiki.06zzlj.asia/arts/235914.Doc

原标题：快速入门容器基础概念，理解镜像与容器
简介：golang grpc 客户端拦截器封装，grpc 客户端拦截器实现请求统一签名、重试、链路信息透传。
 | 原文链接：http://wiki.06zzlj.asia/arts/782585.Doc

原标题：Git 代码冲突正确处理方式
简介：系统字符集统一乱码修复，统一数据库、程序、操作系统字符集，解决中文乱码显示异常问题。
 | 原文链接：http://wiki.06zzlj.asia/arts/831767.Doc

原标题：Debug：表单提交特殊字符造成接口解析失败
简介：golang 空接口 interface {} 类型处理，interface {} 存储任意类型，类型转换，处理泛型之前通用数据。
 | 原文链接：http://wiki.06zzlj.asia/arts/559937.Doc

原标题：零基础理解幂等性基础概念与场景
简介：golang go 信号处理优雅重启实现，USR2 触发程序重启，不关闭监听 socket 实现零停机升级。
 | 原文链接：http://wiki.06zzlj.asia/arts/798463.Doc

原标题：缓存穿透防护保护数据库
简介：golang os.Signal 信号监听完整示例，signal.Notify 监听信号，缓冲 channel 防止信号丢失。
 | 原文链接：http://wiki.06zzlj.asia/arts/440567.Doc

原标题：golang 系统设计请求签名校验完整方案
简介：OOMKilled 容器被杀完整排查，排查容器被 OOM 终止完整流程，区分程序内存泄露和容器内存限制过小。
 | 原文链接：http://wiki.06zzlj.asia/arts/296555.Doc

原标题：golang 系统设计压测工具 vegeta 使用示例
简介：新手快速上手 Git 版本控制实操指南，讲解 Git 基础概念与常用命令，结合实操案例，帮助零基础用户掌握版本控制核心能力。
 | 原文链接：http://wiki.06zzlj.asia/arts/824708.Doc

原标题：golang jaeger 链路追踪 go 接入
简介：golang 单元测试 mock http 请求，mock HTTP 外部接口，单元测试不依赖外部网络，保证用例稳定运行。
 | 原文链接：http://wiki.06zzlj.asia/arts/248393.Doc

原标题：TCP 心跳检测清理僵死连接
简介：golang 内存碎片问题识别与规避，大量小对象频繁分配产生内存碎片，通过对象池减少碎片。
 | 原文链接：http://wiki.06zzlj.asia/arts/231766.Doc

原标题：Issue：日志疯狂打日志快速占满磁盘空间
简介：golang cgo 性能开销避坑指南，cgo 调用开销，减少频繁 cgo 调用，规避 cgo 带来内存泄漏风险。
 | 原文链接：http://wiki.06zzlj.asia/arts/349750.Doc

原标题：部署实践：Nginx高可用配置方案实践
简介：golang go‑zero rpc 微服务开发，go‑zero 定义 proto，生成 rpc 服务代码，实现微服务调用。
 | 原文链接：http://wiki.06zzlj.asia/arts/861368.Doc

原标题：golang 系统设计敏感数据加密存储方案
简介：代码格式化工具团队统一风格，接入格式化工具，统一全团队代码书写风格，减少格式类 git 冲突。
 | 原文链接：http://wiki.06zzlj.asia/arts/503964.Doc

原标题：慢查询分析索引调优数据库实战
简介：golang go 逃逸分析实操查看，go build‑gcflags=-m 查看逃逸分析，减少堆分配优化程序性能。
 | 原文链接：http://wiki.06zzlj.asia/arts/580291.Doc

原标题：架构复盘：消息队列在业务系统中边界与最佳实践
简介：golang kitex 字节微服务框架入门，kitex 开发 rpc 微服务，代码生成，服务注册发现完整流程。
 | 原文链接：http://wiki.06zzlj.asia/arts/863296.Doc

原标题：golang 系统设计分布式配置中心思路
简介：golang 服务注册 etcd 简单示例，etcd 实现服务注册发现，微服务实例注册元数据，客户端发现节点。
 | 原文链接：http://wiki.06zzlj.asia/arts/080018.Doc

原标题：排错：CI缓存策略错误，每次全量重新构建
简介：内网 DNS 不稳定随机报错排查，定位内网 DNS 抖动问题，配置备选 DNS，解决偶现域名解析失败。
 | 原文链接：http://wiki.06zzlj.asia/arts/090876.Doc

原标题：Practice：实现业务id生成不连续有序ID方案
简介：接口请求重试容错机制实现，封装请求重试逻辑，遇到临时网络故障自动重试，提升第三方调用稳定性。
 | 原文链接：http://wiki.06zzlj.asia/arts/545138.Doc

原标题：golang 系统设计日志检索排查线上问题实操技巧
简介：跨平台 uniapp 多端开发实操，uniapp 开发一套代码，编译多端，梳理多端差异处理与适配技巧。
 | 原文链接：http://wiki.06zzlj.asia/arts/902247.Doc

原标题：Hands‑on：简易网关路由转发组件开发
简介：golang redis bloom 布隆过滤器 go‑redis，go‑redis 布隆过滤器，海量数据判断是否存在，减少数据库查询。
 | 原文链接：http://wiki.06zzlj.asia/arts/013280.Doc

原标题：golang docker compose 环境变量
简介：数据库排序规则统一结果一致，统一数据库表排序规则，解决不同环境查询排序结果不一致问题。
 | 原文链接：http://wiki.06zzlj.asia/arts/686257.Doc

原标题：golang 系统设计业务指标系统指标定义思路
简介：golang cobra 命令行参数配置绑定，cobra 绑定配置文件环境变量命令行参数，多源配置合并。
 | 原文链接：http://wiki.06zzlj.asia/arts/073754.Doc

原标题：golang 系统设计网关错误重试超时处理策略
简介：nodejs 消息队列消费服务开发，Node 开发消息队列消费端，监听队列消息执行业务逻辑，异步解耦业务。
 | 原文链接：http://wiki.06zzlj.asia/arts/660708.Doc


二、踩坑排错｜Troubleshooting
原标题：新手向：开源项目本地构建失败通用排查步骤
简介：日志敏感信息脱敏泄露防护，日志打印时自动脱敏手机号身份证，避免日志输出泄露用户隐私数据。
 | 原文链接：http://wiki.06zzlj.asia/arts/064222.Doc

原标题：方案设计：高可用Redis集群架构选型对比
简介：nestjs 拦截器过滤器管道实战，实操 Nest 拦截器、异常过滤器、管道校验，处理请求与响应统一逻辑。
 | 原文链接：http://wiki.06zzlj.asia/arts/636550.Doc

原标题：golang 系统设计延迟消息实现几种方案对比
简介：golang 模板函数自定义拓展，自定义 template 模板函数，在 html 模板调用自定义逻辑处理数据。
 | 原文链接：http://wiki.06zzlj.asia/arts/913576.Doc

原标题：golang 系统设计压测环境隔离避免影响生产
简介：golang gif 图片帧处理操作，解析 gif 图片帧，压缩、拆分 gif 动图，处理动图业务。
 | 原文链接：http://wiki.06zzlj.asia/arts/217626.Doc

原标题：程序信号中断退出处理逻辑
简介：golang 字符串处理常用技巧汇总，字符串拼接、分割、替换、类型转换实操，规避字符串高频错误。
 | 原文链接：http://wiki.06zzlj.asia/arts/182987.Doc

原标题：实战：Redis过期回调实现业务事件通知实践
简介：nodejs redis 缓存业务实战，Node 对接 Redis 实现业务缓存，缓存热点查询结果，减轻数据库压力。
 | 原文链接：http://wiki.06zzlj.asia/arts/086065.Doc

原标题：Performance：批量导入数据性能优化实践
简介：golang mock 单元测试编写技巧，单元测试 mock 外部依赖，隔离数据库网络，只测试业务逻辑本身。
 | 原文链接：http://wiki.06zzlj.asia/arts/059549.Doc

原标题：项目实践：本地模拟多节点分布式系统实践
简介：golang gorm 事务手动回滚提交，手动控制事务流程，业务异常主动回滚，保障数据操作原子性。
 | 原文链接：http://wiki.06zzlj.asia/arts/936979.Doc

原标题：快速入门日志打印与日志分级基础用法
简介：程序信号中断退出处理逻辑，捕获系统中断信号，执行资源释放、关闭连接，实现程序优雅退出。
 | 原文链接：http://wiki.06zzlj.asia/arts/053125.Doc

原标题：golang 系统设计内存复用 sync.pool 使用
简介：全平台系统环境变量配置，汇总多操作系统环境变量配置方法，统一项目读取逻辑，适配不同运行平台。
 | 原文链接：http://wiki.06zzlj.asia/arts/306291.Doc

原标题：macOS 脚本执行权限开启
简介：读懂开源项目 README 实用技巧，教你快速解析开源项目说明文档，提取安装、运行、配置关键信息，快速上手项目。
 | 原文链接：http://wiki.06zzlj.asia/arts/450932.Doc

原标题：golang 系统设计链路追踪架构简单讲解
简介：golang go select 多路等待 channel，select 等待多个 channel，default 非阻塞，超时等待 channel。
 | 原文链接：http://wiki.06zzlj.asia/arts/723416.Doc

原标题：空指针异常判空容错处理
简介：前端水印防信息泄露实现，实现网页水印功能，页面叠加用户信息水印，防止页面截图信息外泄。
 | 原文链接：http://wiki.06zzlj.asia/arts/788299.Doc

原标题：调优方案：JVM内存参数优化，降低GC频率
简介：Dockerfile 编写容器打包实战，讲解 Dockerfile 指令含义，编写镜像构建脚本，将本地项目打包成可分发容器镜像。
 | 原文链接：http://wiki.06zzlj.asia/arts/207919.Doc

原标题：golang 系统设计缓存过期时间设置原则梳理
简介：WebSocket 聊天室实时通讯开发，基于 WebSocket 搭建简易聊天室，实现多人消息广播实时聊天效果。
 | 原文链接：http://wiki.06zzlj.asia/arts/020727.Doc

原标题：golang mysql 避免 select * 查询
简介：Cookie 跨环境登录配置调整，调整 Cookie 域、Secure 属性，适配开发测试生产环境，修复登录失效。
 | 原文链接：http://wiki.06zzlj.asia/arts/618560.Doc

原标题：golang 系统设计内网外网服务隔离方案
简介：golang sync.Cond 条件变量使用，Cond 条件变量协程等待唤醒，复杂并发同步场景。
 | 原文链接：http://wiki.06zzlj.asia/arts/593287.Doc

原标题：架构复盘：服务优雅停机架构设计资源释放
简介：golang redis bloom 布隆过滤器 go‑redis，go‑redis 布隆过滤器，海量数据判断是否存在，减少数据库查询。
 | 原文链接：http://wiki.06zzlj.asia/arts/044758.Doc

原标题：Architecture：鉴权授权系统架构设计思路
简介：golang nacos go 客户端配置服务发现，nacos‑go 对接 nacos，配置管理、微服务注册发现。
 | 原文链接：http://wiki.06zzlj.asia/arts/140421.Doc

原标题：Debug：分布式会话时钟不同步令牌提前失效
简介：手写简易 ORM 理解对象映射，手写极简 ORM 示例，理解对象与数据库表字段映射底层原理。
 | 原文链接：http://wiki.06zzlj.asia/arts/196283.Doc

原标题：Debug：时间回拨，定时任务调度逻辑错乱
简介：golang io.LimitReader 限制读取字节数，LimitReader 限制最大读取，防止读取超大数据。
 | 原文链接：http://wiki.06zzlj.asia/arts/086994.Doc

原标题：DevOps：环境配置管理区分开发测试生产
简介：网关集成鉴权限流日志一体化，在网关层整合鉴权、限流、请求日志，统一对入口请求做管控处理。
 | 原文链接：http://wiki.06zzlj.asia/arts/455668.Doc

原标题：golang 系统设计多级缓存架构落地
简介：golang docker compose 开发环境 go 服务，docker compose 编排 go 服务与中间件，本地一键拉起整套开发环境。
 | 原文链接：http://wiki.06zzlj.asia/arts/526627.Doc

原标题：业务幂等键设计防重复逻辑
简介：nestjs 全局返回格式统一处理，Nest 全局拦截器统一包装接口返回数据，对外输出标准化响应格式。
 | 原文链接：http://wiki.06zzlj.asia/arts/363935.Doc

原标题：项目实践：数据库慢日志采集分析落地实践
简介：golang netlink 系统信息获取，netlink 获取系统网络信息，网卡地址，内核网络状态读取。
 | 原文链接：http://wiki.06zzlj.asia/arts/400656.Doc

原标题：实战项目：搭建私有Docker镜像仓库本地实践
简介：css 变量主题切换方案实现，使用 CSS 变量实现网页主题切换，多套主题样式快速切换无需大量 CSS。
 | 原文链接：http://wiki.06zzlj.asia/arts/604848.Doc

原标题：用户敏感数据脱敏代码实现
简介：内存溢出问题现象识别排查，识别内存溢出现象，梳理排查方向，定位内存持续上涨引发服务崩溃问题。
 | 原文链接：http://wiki.06zzlj.asia/arts/528825.Doc

原标题：实战：容器内执行调试排错完整实操流程
简介：网络读取超时设置连接挂起防护，设置网络读取超时时间，防止请求无限挂起不返回，占用连接资源。
 | 原文链接：http://wiki.06zzlj.asia/arts/720053.Doc

原标题：eslint prettier 代码规范落地
简介：异步任务堆积消费能力优化，处理消息任务堆积问题，提升消费处理速度，恢复队列正常处理水位。
 | 原文链接：http://wiki.06zzlj.asia/arts/550324.Doc

原标题：消息队列生产消费模型入门
简介：golang aes cbc gcm 模式加密对比，AES‑CBC AES‑GCM 模式加密解密，理解两种模式差异选型。
 | 原文链接：http://wiki.06zzlj.asia/arts/436302.Doc

原标题：项目实践：消息队列消息确认机制业务实践
简介：浏览器缓存强制刷新方案，设置 HTTP 缓存头，处理浏览器缓存旧静态资源，让用户加载更新后的页面。
 | 原文链接：http://wiki.06zzlj.asia/arts/184020.Doc

原标题：golang ci 流水线自动部署 k8s 示例
简介：golang gorm group by 分组统计，GORM 分组聚合统计，实现 count sum 等统计查询，快速完成统计业务。
 | 原文链接：http://wiki.06zzlj.asia/arts/060001.Doc

原标题：热更新开发环境配置教程
简介：缓存过期策略优化防业务故障，合理设置缓存过期策略，规避集中过期，减少缓存失效带来业务抖动。
 | 原文链接：http://wiki.06zzlj.asia/arts/750861.Doc

原标题：任务执行锁防止并发重复调度
简介：golang redis 过期键监听回调，监听 key 过期事件，过期触发业务逻辑，实现过期自动处理业务场景。
 | 原文链接：http://wiki.06zzlj.asia/arts/596091.Doc

原标题：golang kafka 消息顺序性保证方案
简介：golang go‑zero 中间件鉴权限流，go‑zero 自定义中间件，实现鉴权、限流、日志打印通用能力。
 | 原文链接：http://wiki.06zzlj.asia/arts/607897.Doc

原标题：golang k8s 基础概念 pod deployment
简介：golang 模糊测试 go fuzz 基础编写，Fuzz 测试函数，自动生成随机输入，发现代码崩溃 panic。
 | 原文链接：http://wiki.06zzlj.asia/arts/748486.Doc

原标题：安全复盘：消息队列未授权访问安全加固
简介：日志切割配置防止日志丢失，配置日志切割轮转策略，日志按大小时间切割，防止日志文件丢失。
 | 原文链接：http://wiki.06zzlj.asia/arts/749617.Doc

原标题：Hands‑on：简易代理服务器开发实践
简介：golang race 检测器性能开销，race 检测器有性能损耗，只用于测试环境，禁止生产开启 race。
 | 原文链接：http://wiki.06zzlj.asia/arts/937327.Doc

原标题：前端下载导出文件功能实现
简介：golang go 运行时获取编译信息，程序内部读取编译时间 git 版本，接口输出程序版本信息。
 | 原文链接：http://wiki.06zzlj.asia/arts/374794.Doc

原标题：性能笔记：HTTP连接复用性能优化实践
简介：前端防抖节流高频事件处理，封装防抖节流工具，处理滚动、输入框输入等高频触发事件减少执行次数。
 | 原文链接：http://wiki.06zzlj.asia/arts/590610.Doc

三、实战开发｜Practice
原标题：golang 多协程任务池并发控制
简介：golang go 终端 pty 伪终端操作，pty 启动子进程，模拟终端交互，实现交互式命令调用。
 | 原文链接：http://wiki.06zzlj.asia/arts/534398.Doc

原标题：多实例部署 Session 共享方案
简介：golang go panic 合理使用边界，panic 只用于不可恢复程序错误，业务逻辑禁止直接 panic。
 | 原文链接：http://wiki.06zzlj.asia/arts/607378.Doc

原标题：踩坑记录：CPU亲和配置不合理多核心负载不均
简介：golang gorm 批量插入性能调优，GORM 批量插入优化，调整批次大小，提升大量数据插入数据库速度。
 | 原文链接：http://wiki.06zzlj.asia/arts/074382.Doc

原标题：排错：DockerCompose依赖顺序启动顺序坑
简介：异步编程 Promise 执行流程解析，拆解异步执行顺序，理解回调与 Promise 差异，理清异步场景下代码执行逻辑。
 | 原文链接：http://wiki.06zzlj.asia/arts/241172.Doc

原标题：golang 系统设计架构图绘制规范简单建议
简介：golang 接口返回统一封装工具，封装 Go 接口统一返回工具，标准化成功失败返回结构体。
 | 原文链接：http://wiki.06zzlj.asia/arts/352272.Doc

原标题：实践：Git工作流主干开发团队协作实践
简介：golang 命令行彩色输出终端，终端彩色文字输出，进度条交互，优化命令行工具用户体验。
 | 原文链接：http://wiki.06zzlj.asia/arts/272375.Doc

原标题：golang 系统设计基准测试 benchmark 编写
简介：限流窗口绕过漏洞修复方案，修复限流时间窗口漏洞，避免攻击者绕过限流规则，保障接口防护有效。
 | 原文链接：http://wiki.06zzlj.asia/arts/079256.Doc

原标题：Hands‑on：简易邮件发送服务封装实践
简介：golang os 主机名内核版本读取，os 读取主机名，内核信息，操作系统版本，获取运行环境信息。
 | 原文链接：http://wiki.06zzlj.asia/arts/059927.Doc

原标题：设计思考：系统容量评估架构前期估算思路
简介：golang 日志 zap 结构化日志实践，接入 Zap 结构化日志库，打印结构化日志，方便日志检索解析。
 | 原文链接：http://wiki.06zzlj.asia/arts/771489.Doc

原标题：方案对比：轮询长轮询WebSocket推送架构选型
简介：golang 日志级别动态调整热更新，不用重启程序动态修改日志输出级别，线上调试排查问题十分方便。
 | 原文链接：http://wiki.06zzlj.asia/arts/640706.Doc

原标题：安全笔记：XSS跨站脚本攻击防御落地实践
简介：golang 链路追踪简易实现方案，简易链路追踪实现，传递 traceId，记录调用链路，方便排查慢调用。
 | 原文链接：http://wiki.06zzlj.asia/arts/925478.Doc

原标题：golang lru 缓存淘汰算法编写
简介：golang elasticsearch 客户端 golang 实操，es 客户端文档增删改查，条件搜索聚合统计对接搜索引擎。
 | 原文链接：http://wiki.06zzlj.asia/arts/495365.Doc

原标题：Troubleshoot：跨域偶现失败难以复现问题
简介：golang go 信号处理优雅重启实现，USR2 触发程序重启，不关闭监听 socket 实现零停机升级。
 | 原文链接：http://wiki.06zzlj.asia/arts/261320.Doc

原标题：Performance：数据库索引优化常见错误案例
简介：golang go time 时区数据库内置，go 内置时区数据库，不用系统时区文件，容器时区不依赖系统。
 | 原文链接：http://wiki.06zzlj.asia/arts/863935.Doc

原标题：golang mysql 批量导入数据实操
简介：golang 异步任务队列 worker 池开发，任务入数据库或 redis，worker 池消费执行，异步处理耗时业务。
 | 原文链接：http://wiki.06zzlj.asia/arts/904965.Doc

原标题：golang 系统设计事务消息 rocketmq 简单原理
简介：golang go 并发模式 fan‑out fan‑in，fanout 分发任务 fanin 汇总结果，多协程并发处理任务。
 | 原文链接：http://wiki.06zzlj.asia/arts/338668.Doc

原标题：优化实践：接口返回字段裁剪减少报文大小
简介：手写简易 MQ 理解消息存储消费，手写极简消息队列 Demo，理解消息存储、投递、消费完整流程。
 | 原文链接：http://wiki.06zzlj.asia/arts/356732.Doc

原标题：安全复盘：定时任务权限过大风险管控
简介：golang 空接口 interface {} 类型处理，interface {} 存储任意类型，类型转换，处理泛型之前通用数据。
 | 原文链接：http://wiki.06zzlj.asia/arts/748461.Doc

原标题：Git 误删提交代码恢复找回
简介：ServiceWorker 缓存页面更新清理，处理 ServiceWorker 缓存，实现页面新版本更新，用户可以加载最新页面。
 | 原文链接：http://wiki.06zzlj.asia/arts/789807.Doc

原标题：新手指南：看懂开源项目的Issue与PR
简介：golang go 模块迁移从 GOPATH 到 GoMod，老项目从 GOPATH 迁移 go mod，解决依赖管理混乱问题。
 | 原文链接：http://wiki.06zzlj.asia/arts/828849.Doc

原标题：golang 系统设计故障止损降级回滚执行原则
简介：业务错误码完整落地实践，落地完整业务错误码，枚举全部业务异常，统一返回，配套文档说明。
 | 原文链接：http://wiki.06zzlj.asia/arts/457471.Doc

原标题：Troubleshooting：Nginx缓冲区过小大文件上传失败
简介：golang yaml 解析配置加载实操，Go 解析 YAML 配置文件，读取配置参数，驱动业务运行。
 | 原文链接：http://wiki.06zzlj.asia/arts/863305.Doc

原标题：方案设计：短链接系统完整架构方案拆解
简介：CLI 批量处理工具文件操作开发，开发命令行批量工具，实现批量文件处理，提升重复文件处理效率。
 | 原文链接：http://wiki.06zzlj.asia/arts/087923.Doc

原标题：golang 时间时区处理避坑指南
简介：golang mongodb 索引优化慢查询处理，mongodb 创建索引，分析慢查询，优化聚合查询执行性能。
 | 原文链接：http://wiki.06zzlj.asia/arts/770997.Doc

原标题：Security：业务操作审计日志安全留存
简介：Cookie Session 会话状态管理，讲解 Cookie 与 Session 原理，理解登录状态保存，实现服务端会话管理逻辑。
 | 原文链接：http://wiki.06zzlj.asia/arts/194356.Doc

原标题：HelloGitWorkflow：理解简单主干开发流程
简介：全量回归测试提升代码质量，搭建全量回归测试集，版本发布执行回归测试，避免迭代引入旧 bug。
 | 原文链接：http://wiki.06zzlj.asia/arts/348280.Doc

原标题：零基础理解会话、Cookie、Session基础
简介：Docker 容器入门镜像实操教程，介绍 Docker 基础概念，演示镜像拉取、容器启停，帮助新手建立容器化开发认知。
 | 原文链接：http://wiki.06zzlj.asia/arts/006928.Doc

原标题：代理 HTTPS 证书访问异常处理
简介：golang arp 缓存读取操作，读取系统 arp 缓存表，获取 ip 对应的 mac 地址信息。
 | 原文链接：http://wiki.06zzlj.asia/arts/611185.Doc

原标题：HelloGitWorkflow：理解简单主干开发流程
简介：golang go 模板执行错误捕获，捕获模板执行错误，防止模板错误直接返回空白页面。
 | 原文链接：http://wiki.06zzlj.asia/arts/893862.Doc

原标题：golang 系统信号信号量处理
简介：服务器时钟同步任务错乱修复，配置服务器 NTP 时间同步，保证集群所有机器时间保持一致。
 | 原文链接：http://wiki.06zzlj.asia/arts/143318.Doc

原标题：golang k8s secret 加密敏感信息
简介：golang context.Background 与 TODO 区别，Background 主流程根上下文，TODO 不确定用哪个上下文时使用。
 | 原文链接：http://wiki.06zzlj.asia/arts/557532.Doc

原标题：Performance：数据库join优化，大表join规避
简介：golang bufio.Scanner 缓冲区调大，Scanner 默认缓冲区大小不够，读取超长行需要扩大缓冲区。
 | 原文链接：http://wiki.06zzlj.asia/arts/001274.Doc

原标题：安全笔记：GitHubAction密钥安全管理
简介：Redis 热点 key 拆分降低集群压力，拆分访问量极高的热点 Key，分散请求压力，避免 Redis 节点压力过高。
 | 原文链接：http://wiki.06zzlj.asia/arts/694881.Doc

原标题：golang defer panic 异常处理
简介：代码模块化组件化拆分思路，讲解代码拆分原则，将大业务拆分为独立模块组件，提升代码复用与维护能力。
 | 原文链接：http://wiki.06zzlj.asia/arts/005680.Doc

原标题：Performance：后端接口性能优化完整分析流程
简介：golang cgo 调用 C 语言代码示例，cgo 调用 C 函数，go 与 C 互相调用，对接 C 语言库能力。
 | 原文链接：http://wiki.06zzlj.asia/arts/472387.Doc

原标题：Practice：实现跨机器文件同步脚本实践
简介：重复提交幂等防护再次讲解，梳理前端重复点击、网络重试场景，落地接口幂等，杜绝重复业务。
 | 原文链接：http://wiki.06zzlj.asia/arts/404546.Doc

原标题：业务错误码体系设计方案
简介：golang 系统信号信号量处理，Go 处理系统各类信号，SIGINT、SIGTERM，实现程序可控退出。
 | 原文链接：http://wiki.06zzlj.asia/arts/340202.Doc

原标题：DevOps：环境配置管理区分开发测试生产
简介：golang 项目目录分层规范设计，Go 后端项目目录分层规范，按领域分层，提高项目可读性可维护性。
 | 原文链接：http://wiki.06zzlj.asia/arts/565410.Doc

原标题：golang 系统设计分布式锁红锁优缺点梳理
简介：数据库排序规则统一结果一致，统一数据库表排序规则，解决不同环境查询排序结果不一致问题。
 | 原文链接：http://wiki.06zzlj.asia/arts/044787.Doc

原标题：运维笔记：系统内核参数调优生产服务器
简介：消息队列消费堆积扩容处理，消息大量堆积时，扩容消费实例，优化消费逻辑，加快消息处理速度。
 | 原文链接：http://wiki.06zzlj.asia/arts/332919.Doc

四、架构设计｜Architecture
原标题：坑点：npm/pip全局版本与项目本地版本冲突
简介：golang fasthttp 高性能 http 库使用，fasthttp 高性能 http 实现，适合超高 QPS 场景，对比 net/http 差异。
 | 原文链接：http://wiki.06zzlj.asia/arts/065126.Doc

原标题：golang 静态文件服务搭建教程
简介：nodejs 项目 pm2 部署运维指南，使用 PM2 管理 Node 服务，进程守护、日志、重启，线上部署运维实操。
 | 原文链接：http://wiki.06zzlj.asia/arts/258002.Doc

原标题：golang 参数校验业务接口处理
简介：golang prometheus client 业务埋点实操，prometheus client‑go 业务埋点，计数器、仪表盘、直方图指标开发。
 | 原文链接：http://wiki.06zzlj.asia/arts/293660.Doc

原标题：从零学习基础的接口请求与参数处理
简介：golang http body 必须关闭的重要性，无论成功失败必须关闭 request.Body，否则连接无法复用泄漏。
 | 原文链接：http://wiki.06zzlj.asia/arts/930529.Doc

原标题：坑点：缓存过期策略不当引发业务异常
简介：项目依赖安全扫描漏洞防范，扫描项目第三方依赖包，修复存在安全漏洞依赖，防范供应链攻击。
 | 原文链接：http://wiki.06zzlj.asia/arts/488772.Doc

原标题：Issue：日志输出包含敏感信息造成泄露风险
简介：express 中间件开发业务实践，开发 Express 自定义中间件，拦截请求，实现鉴权、日志记录等通用逻辑。
 | 原文链接：http://wiki.06zzlj.asia/arts/382481.Doc

原标题：golang 系统设计分布式锁不同场景选型对比
简介：golang map 并发读写 panic 解决方案，map 非并发安全，讲解加锁、sync.map 方案解决并发读写崩溃。
 | 原文链接：http://wiki.06zzlj.asia/arts/244405.Doc

原标题：快速入门容器基础概念，理解镜像与容器
简介：golang 命令行交互 cobra 开发 cli，cobra 库开发功能完善命令行工具，子命令参数标志解析。
 | 原文链接：http://wiki.06zzlj.asia/arts/660338.Doc

原标题：Spring 事务传播机制配置生效
简介：golang sync.WaitGroup 协程等待控制，WaitGroup 控制一组协程等待全部执行完成，完成批量协程任务调度。
 | 原文链接：http://wiki.06zzlj.asia/arts/377146.Doc

原标题：golang 系统设计回调签名校验防伪造实现
简介：golang go 排序 sort 包自定义排序，sort 包实现自定义排序逻辑，对切片按业务规则排序。
 | 原文链接：http://wiki.06zzlj.asia/arts/990586.Doc

原标题：定时任务周期调度 demo 开发
简介：golang fasthttp 服务开发完整示例，fasthttp 搭建 http 服务，路由、参数读取、响应返回完整业务。
 | 原文链接：http://wiki.06zzlj.asia/arts/711308.Doc

原标题：实战：Redis集群本地搭建与功能验证
简介：nodejs 内存溢出问题排查修复，Node.js 程序 OOM 排查流程，定位内存泄露，调整内存限制修复崩溃。
 | 原文链接：http://wiki.06zzlj.asia/arts/798713.Doc

原标题：安全笔记：依赖包漏洞检测供应链安全
简介：golang excel 生成导出高性能方案，excelize 流式生成 excel，百万行数据导出，规避内存溢出。
 | 原文链接：http://wiki.06zzlj.asia/arts/233562.Doc

原标题：日志敏感信息脱敏泄露防护
简介：短信服务封装失败自动重试，封装短信发送组件，处理发送失败自动重试，兼容多短信服务商。
 | 原文链接：http://wiki.06zzlj.asia/arts/449442.Doc

原标题：零基础理解依赖管理与包管理器
简介：CI 构建缓存加速编译速度，开启 CI 流水线依赖缓存，复用上一次构建依赖包，缩短流水线构建耗时。
 | 原文链接：http://wiki.06zzlj.asia/arts/454105.Doc

原标题：golang 系统设计缓存与数据库一致性权衡
简介：git rebase 整理提交历史实操，使用 rebase 整理杂乱提交记录，将多条提交合并，保持 git 提交历史干净线性。
 | 原文链接：http://wiki.06zzlj.asia/arts/977316.Doc

原标题：Git LFS 大文件推送失败解决
简介：golang sql 注入风险规避要点，参数化查询杜绝 sql 注入，禁止字符串拼接 SQL 语句执行。
 | 原文链接：http://wiki.06zzlj.asia/arts/002002.Doc

原标题：golang 系统设计创建更新时间自动维护方案
简介：消息队列生产消费模型入门，讲解消息队列生产、存储、消费流程，理解异步解耦、削峰，掌握消息队列基础概念。
 | 原文链接：http://wiki.06zzlj.asia/arts/619802.Doc

?
