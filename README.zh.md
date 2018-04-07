
# 真棒去

[![Build Status](https://travis-ci.org/avelino/awesome-go.svg?branch=master)](https://travis-ci.org/avelino/awesome-go) [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) [![Slack Widget](https://camo.githubusercontent.com/984828c0b020357921853f59eaaa65aaee755542/68747470733a2f2f73332e65752d63656e7472616c2d312e616d617a6f6e6177732e636f6d2f6e6774756e612f6a6f696e2d75732d6f6e2d736c61636b2e706e67)](http://gophers.slack.com/messages/awesome)

精心制作的框架列表,图书馆和软件. 启发[真棒,蟒蛇](https://github.com/vinta/awesome-python). 

### 贡献

请尽快在这里[贡献指南](https://github.com/avelino/awesome-go/blob/master/CONTRIBUTING.md)第一. 谢谢大家[贡献者](https://github.com/avelino/awesome-go/graphs/contributors);你摇滚!

#### _如果您在此处看到不再保留或不适合的包或项目,请提交拉取请求以改进此文件. 谢谢!_

### 内容

-   [真棒去](#awesome-go)

    -   [音频和音乐](#audio-and-music)
    -   [认证和oauth](#authentication-and-oauth)
    -   [命令行](#command-line)
    -   [组态](#configuration)
    -   [持续集成](#continuous-integration)
    -   [css预处理器](#css-preprocessors)
    -   [数据结构](#data-structures)
    -   [数据库](#database)
    -   [数据库驱动](#database-drivers)
    -   [日期和时间](#date-and-time)
    -   [分布式系统](#distributed-systems)
    -   [电子邮件](#email)
    -   [可嵌入脚本语言](#embeddable-scripting-languages)
    -   [档](#files)
    -   [金融](#financial)
    -   [形式](#forms)
    -   [游戏开发](#game-development)
    -   [代和泛型](#generation-and-generics)
    -   [地理](#geographic)
    -   [去编译器](#go-compilers)
    -   [够程](#goroutines)
    -   [GUI](#gui)
    -   [硬件](#hardware)
    -   [图片](#images)
    -   [物联网](#iot-internet-of-things)
    -   [记录](#logging)
    -   [机器学习](#machine-learning)
    -   [消息](#messaging)
    -   [杂](#miscellaneous)
    -   [自然语言处理](#natural-language-processing)
    -   [联网](#networking)
    -   [OpenGL的](#opengl)
    -   [ORM](#orm)
    -   [包管理](#package-management)
    -   [查询语言](#query-language)
    -   [资源嵌入](#resource-embedding)
    -   [科学和数据分析](#science-and-data-analysis)
    -   [安全](#security)
    -   [系列化](#serialization)
    -   [模板引擎](#template-engines)
    -   [测试](#testing)
    -   [文字处理](#text-processing)
    -   [第三方apis](#third-party-apis)
    -   [公用事业](#utilities)
    -   [验证](#validation)
    -   [版本控制](#version-control)
    -   [视频](#video)
    -   [web框架](#web-frameworks)
        -   [中间件](#middlewares)
            -   [实际的中间件](#actual-middlewares)
            -   [用于创建http中间件的库](#libraries-for-creating-http-middlewares)
        -   [路由器](#routers)
    -   [视窗](#windows)
    -   [XML](#xml)

-   [工具](#tools)

    -   [代码分析](#code-analysis)
    -   [编辑插件](#editor-plugins)-[去生成工具](#go-generate-tools)
    -   [去工具](#go-tools)
    -   [软件包](#software-packages)
        -   [devops工具](#devops-tools)
        -   [其他软件](#other-software)

-   [服务器应用](#server-applications)

-   [资源](#resources)
    -   [基准](#benchmarks)
    -   [会议](#conferences)
    -   [电子书](#e-books)
    -   [地鼠](#gophers)
    -   [聚会](#meetups)
    -   [推特](#twitter)
    -   [网站](#websites)
        -   [教程](#tutorials)

## 音频和音乐

_用于处理音频的库. _

-   [easymidi](https://github.com/algoGuy/EasyMIDI)-  easymidi是一个简单而可靠的库,用于处理标准MIDI文件(smf). 
-   [后手](https://github.com/eaburns/flac)- 原生go flac解码器. 
-   [后手](https://github.com/mewkiz/flac)- 原生go flac解码器. 
-   [gaad](https://github.com/Comcast/gaad)- 本地去aac比特流解析器. 
-   [去-SOX](https://github.com/krig/go-sox)-  libsox绑定去. 
-   [go_mediainfo](https://github.com/zhulik/go_mediainfo)-  libmediainfo绑定去. 
-   [gosamplerate](https://github.com/dh1tw/gosamplerate)-  libsamplerate绑定去. 
-   [ID3V2](https://github.com/bogem/id3v2)- 快速,稳定的id3解析和写作库. 
-   [malgo](https://github.com/gen2brain/malgo)- 迷你音频库. 
-   [minimp3](https://github.com/tosone/minimp3)- 轻量级MP3解码库. 
-   [混合](https://github.com/go-mix/mix)- 音乐应用程序的基于序列的本地音频混音器. 
-   [MP3](https://github.com/tcolgate/mp3)- 原生mp3解码器. 
-   [音乐理论](https://github.com/go-music-theory/music-theory)- 音乐理论模型在走向. 
-   [portaudio](https://github.com/gordonklaus/portaudio)- 去绑定portaudio音频I / O库. 
-   [portmidi](https://github.com/rakyll/portmidi)- 为portmidi绑定. 
-   [标签库](https://github.com/wtolson/go-taglib)- 去绑定taglib. 
-   [Vorbis格式](https://github.com/mccoyst/vorbis)- "本地"去vorbis解码器(使用cgo,但没有依赖关系). 
-   [波形](https://github.com/mdlayher/waveform)- 去包能够从音频流生成波形图像. 

## 认证和oauth

_用于实现验证方案的库. _

-   [authboss](https://github.com/volatiletech/authboss)- 网络模块化认证系统. 它试图尽可能多地删除样板文件和"硬件",以便每次启动新的Web项目时,都可以插入,配置并开始构建应用程序,而无需每次都构建身份验证系统. 
-   [casbin](https://github.com/hsluoyz/casbin)- 支持访问控制模型(如acl,rbac,abac)的授权库. 
-   [cookiestxt](https://github.com/mengzhuo/cookiestxt)- 提供cookies.txt文件格式的解析器. 
-   [去-AWS-AUTH](https://github.com/smartystreets/go-aws-auth)-  aws(亚马逊网络服务)请求签名库. 
-   [去何塞](https://github.com/square/go-jose)-  jose工作组的json Web令牌,json web签名和json web加密规范的相当完整的实现. 
-   [去-的oauth2服务器](https://github.com/RichardKnop/go-oauth2-server)- 使用golang编写的独立的,符合规范的oauth2服务器. 
-   [gologin](https://github.com/dghubble/gologin)- 可连接的处理程序,用于使用oauth1和oauth2身份验证提供程序进行登录. 
-   [gorbac](https://github.com/mikespook/gorbac)- 在golang中提供轻量级的基于角色的访问控制(rbac)实现. 
-   [戈特](https://github.com/markbates/goth)- 提供了一个简单,干净,惯用的方法来使用oauth和oauth2. 处理多个开箱即用的供应商. 
-   [httpauth](https://github.com/goji/httpauth)-  http身份验证中间件. 
-   [智威汤逊](https://github.com/robbert229/jwt)- 干净和易于使用的JSON网络令牌(jwt)的实现. 
-   [智威汤逊,AUTH](https://github.com/adam-hanna/jwt-auth)- 具有许多配置选项的golang http服务器的jwt中间件. 
-   [智威汤逊,去](https://github.com/dgrijalva/jwt-go)-  golang实现json web令牌(jwt). 
-   [loginsrv](https://github.com/tarent/loginsrv)- 带有可插入后端的jwt登录微服务,如oauth2(github),htpasswd,osiam. 
-   [的oauth2](https://github.com/golang/oauth2)-  goauth2的继任者. 通用oauth 2.0软件包附带jwt,谷歌apis,计算引擎和应用程序引擎支持. 
-   [osin](https://github.com/RangelReale/osin)-  golang oauth2服务器库. 
-   [paseto](https://github.com/o1egl/paseto)-  golang实现平台不可知的安全令牌(paseto)
-   [permissions2](https://github.com/xyproto/permissions2)- 用于跟踪用户,登录状态和权限的库. 使用安全的cookies和bcrypt. 
-   [securecookie](https://github.com/chmike/securecookie)- 高效安全的Cookie编码/解码. 
-   [会议](https://github.com/icza/session)- 去Web服务器的会话管理(包括支持谷歌应用程序引擎 -  GAE). 
-   [sessiongate,去](https://github.com/f0rmiga/sessiongate-go)- 使用sessiongate redis模块进行会话管理. 
-   [会议](https://github.com/adam-hanna/sessions)- 简单,高性能,高度可定制的会话服务,用于访问http服务器. 
-   [yubigo](https://github.com/GeertJohan/yubigo)-  yubikey客户端软件包,提供了一个简单的api来将yubico yubikey集成到go应用程序中. 

## 命令行

### 标准cli

_用于构建标准或基本命令行应用程序的库. _

-   [argparse](https://github.com/akamensky/argparse)- 由python的argparse模块启发的命令行参数分析器. 
-   [ARGV](https://github.com/cosiner/argv)- 使用bash语法将库命令行字符串拆分为参数数组. 
-   [CLI](https://github.com/mkideal/cli)- 基于golang结构标签的功能丰富且易于使用的命令行包. 
-   [CLI](https://github.com/teris-io/cli)- 在go中构建命令行界面的简单且完整的api. 
-   [CLI-INIT](https://github.com/tcnksm/gcli)- 开始构建golang命令行应用程序的简单方法. 
-   [高潮](http://github.com/tucnak/climax)- 以"人脸"替代cli,本着去命令的精神. 
-   [眼镜蛇](https://github.com/spf13/cobra)- 现代气候相互作用的指挥官. 
-   [征用](https://github.com/jaffee/commandeer)- 开发友好的cli应用程序: 根据结构域和标签设置标志,默认值和用法. 
-   [完成](https://github.com/posener/complete)- 在go + go命令bash完成中写入bash完成. 
-   [docopt.go](https://github.com/docopt/docopt.go)- 让你微笑的命令行参数解析器. 
-   [驾驶](https://github.com/odeke-em/drive)- 谷歌驱动器客户端的命令行. 
-   [ENV](https://github.com/codingconcepts/env)- 针对结构的基于标记的环境配置. 
-   [旗](https://github.com/cosiner/flag)- 简单但功能强大的命令行选项解析库以支持子命令. 
-   [去精氨酸](https://github.com/alexflint/go-arg)- 基于结构的参数解析. 
-   [去-标志](https://github.com/jessevdk/go-flags)- 去命令行选项解析器. 
-   [gocmd](https://github.com/devfacet/gocmd)- 去建立命令行应用程序库. 
-   [主销](https://github.com/alecthomas/kingpin)- 支持子命令的命令行和标志分析器. 
-   [衬垫](https://github.com/peterh/liner)- 进入命令行界面的类似readline的库. 
-   [mitchellh / CLI](https://github.com/mitchellh/cli)- 去实现命令行界面的库. 
-   [mow.cli](https://github.com/jawher/mow.cli)- 通过复杂的标志和参数解析和验证来构建cli应用程序库. 
-   [同性恋亲友](https://github.com/spf13/pflag)-  go-flag标签包的替代品,实现posix / gnu-style  - 标志. 
-   [的ReadLine](https://github.com/chzyer/readline)- 纯粹的golang实现,它在许可下提供gnu-readline中的大部分功能. 
-   [sflags](https://github.com/octago/sflags)- 标志,urfave / cli,pflag,眼镜蛇,主引擎和其他库的基于结构的标志生成器. 
-   [strumt](https://github.com/antham/strumt)- 图书馆创建提示链. 
-   [ukautz / CLIF](https://github.com/ukautz/clif)- 小命令行界面框架. 
-   [urfave / CLI](https://github.com/urfave/cli)- 简单,快速和有趣的软件包,用于构建go中的命令行应用程序(以前称为codegangsta / cli). 
-   [wlog](https://github.com/dixonwille/wlog)- 支持跨平台颜色和并发性的简单日志记录界面. 
-   [wmenu](https://github.com/dixonwille/wmenu)- 易于使用的cli应用程序菜单结构,提示用户进行选择. 

### 先进的控制台uis

_构建控制台应用程序和控制台用户界面的库. _

-   [极光](https://github.com/logrusorgru/aurora)- 支持fmt.printf / sprintf的ansi终端颜色. 
-   [CFMT](https://github.com/mingrammer/cfmt)- 由引导色彩类型启发的上下文fmt. 
-   [粉笔](https://github.com/ttacon/chalk)- 美化终端/控制台输出的直观软件包. 
-   [颜色](https://github.com/fatih/color)- 彩色终端输出的多功能包装. 
-   [colourize](https://github.com/TreyBastian/colourize)- 在终端机上进入ansi彩色文本库. 
-   [去 - 阿塔曼](https://github.com/workanator/go-ataman)- 去库中渲染终端中的ansi彩色文本模板. 
-   [走,着色](https://github.com/mattn/go-colorable)- 可爱的windows作家. 
-   [去-colortext](https://github.com/daviddengcn/go-colortext)- 去终端的颜色输出库. 
-   [去-isatty](https://github.com/mattn/go-isatty)-  golang的isatty. 
-   [去提示符](https://github.com/c-bata/go-prompt)- 用于构建强大的交互式提示的库,受到启发[蟒提示符的工具包](https://github.com/jonathanslenders/python-prompt-toolkit). 
-   [gocui](https://github.com/jroimartin/gocui)- 极简主义的游戏库旨在创建控制台用户界面. 
-   [gommon /颜色](https://github.com/labstack/gommon/tree/master/color)- 风格的终端文字. 
-   [MPB](https://github.com/vbauerster/mpb)- 终端应用的多进度条. 
-   [进度条](https://github.com/schollz/progressbar)- 基本的线程安全进度条,适用于所有操作系统. 
-   [termbox,去](https://github.com/nsf/termbox-go)-  termbox是创建跨平台文本界面的库. 
-   [termtables](https://github.com/apcera/termtables)- 去红宝石库的端口[终端表](https://github.com/tj/terminal-table)用于简单的ascii表格生成以及提供降价和html输出. 
-   [termui](https://github.com/gizak/termui)- 去基于终端仪表板**termbox,去**并受到启发[祝福-的contrib](https://github.com/yaronn/blessed-contrib). 
-   [TUI-去](https://github.com/marcusolsson/tui-go)- 去ui图书馆建设丰富的终端应用程序. 
-   [uilive](https://github.com/gosuri/uilive)- 实时更新终端输出的库. 
-   [uiprogress](https://github.com/gosuri/uiprogress)- 灵活的库在终端应用程序中呈现进度条. 
-   [uitable](https://github.com/gosuri/uitable)- 使用表格数据提高终端应用程序可读性的库. 

## 组态

_用于配置解析的库. _

-   [配置](https://github.com/olebedev/config)- 包含环境变量和标志解析的json或yaml配置包装. 
-   [配置](https://github.com/paked/configure)- 通过多种来源提供配置,包括json,标志和环境变量. 
-   [ENV](https://github.com/caarlos0/env)- 解析环境变量去结构(使用默认值). 
-   [envcfg](https://github.com/tomazk/envcfg)- 取消编组环境变量以实现结构. 
-   [envconf](https://github.com/ian-kent/envconf)- 来自环境的配置. 
-   [envconfig](https://github.com/vrischmann/envconfig)- 从环境变量中读取你的配置. 
-   [envh](https://github.com/antham/envh)- 帮助者管理环境变量. 
-   [gcfg](https://github.com/go-gcfg/gcfg)- 将ini风格的配置文件读取到结构中;支持用户定义的类型和子部分. 
-   [去向上](https://github.com/ufoscout/go-up)- 一个简单的配置库,具有递归占位符解析和无魔法. 
-   [goconfig](https://github.com/crgimenes/goConfig)- 解析结构作为输入,并用来自命令行,环境变量和配置文件的参数填充此结构的字段. 
-   [godotenv](https://github.com/joho/godotenv)- 去ruby的dotenv库的端口(从中加载环境变量)`.ENV`). 
-   [去搞清楚](https://github.com/ian-kent/gofigure)- 简化应用程序配置. 
-   [走了/ jconf](https://github.com/One-com/gone/tree/master/jconf)- 模块化json配置. 让你配置结构以及它们配置的代码,并将解析委托给子模块而不牺牲完整的配置序列化. 
-   [hjson](https://github.com/hjson/hjson-go)- 人类json,一种人类的配置文件格式. 轻松的语法,更少的错误,更多的评论. 
-   [INGO](https://github.com/schachmat/ingo)- 标志保持在ini样的配置文件中. 
-   [INI](https://github.com/go-ini/ini)- 去包读取和写入ini文件. 
-   [joshbetz /配置](https://github.com/joshbetz/config)- 用于go的小型配置库,用于解析环境变量,json文件以及在叹息时自动重新加载. 
-   [微型](https://github.com/sasbury/mini)- 用于解析ini样式配置文件的golang包. 
-   [商店](https://github.com/tucnak/store)- 轻量级配置管理器. 
-   [毒蛇](https://github.com/spf13/viper)- 用f牙去配置. 
-   [XDG](https://github.com/OpenPeeDeeP/xdg)- 跨平台包裹,遵循[xdg标准](https://standards.freedesktop.org/basedir-spec/basedir-spec-latest.html). 

## 持续集成

_帮助持续集成的工具. _

-   [无人驾驶飞机](https://github.com/drone/drone)- 无人驾驶飞机是一个建立在码头上的持续集成平台,写成go. 
-   [gomason](https://github.com/nikogura/gomason)- 从干净的工作区测试,构建,签署和发布你的二进制文件. 
-   [goveralls](https://github.com/mattn/goveralls)- 整合coveralls.io连续代码覆盖率跟踪系统. 
-   [工作服](https://github.com/go-playground/overalls)- 多包装去goveralls工具项目coverprofile. 
-   [roveralls](https://github.com/LawrenceWoodman/roveralls)- 递归覆盖测试工具. 

## css预处理器

_用于预处理css文件的库. _

-   [C6](https://github.com/c9s/c6)- 用go编写的高性能sass兼容实现编译器. 
-   [GCSS](https://github.com/yosssi/gcss)- 纯粹的CSS预处理器. 
-   [去-libsass](https://github.com/wellington/go-libsass)- 将包装发送到兼容100%sass的libsass项目. 

## 数据结构

_通用数据结构和算法. _

-   [binpacker](https://github.com/zhuangsirui/binpacker)- 二进制打包器和解包器可帮助用户构建自定义二进制流. 
-   [位](https://github.com/yourbasic/bit)-  golang设置数据结构并带有额外的位扭曲功能. 
-   [位集合](https://github.com/willf/bitset)- 去包实现位集. 
-   [盛开](https://github.com/zhenjl/bloom)- 在过滤器中执行bloom过滤器. 
-   [盛开](https://github.com/yourbasic/bloom)-  golang bloom过滤器实现. 
-   [boomfilters](https://github.com/tylertreat/BoomFilters)- 处理连续,无界流的概率数据结构. 
-   [同时,作家](https://github.com/free/concurrent-writer)- 高度并发的直接替换`bufio.writer`. 
-   [conjungo](https://github.com/InVisionApp/conjungo)- 一个小而强大且灵活的合并库. 
-   [算上民日志](https://github.com/seiflotfy/count-min-log)- 执行count-min-log sketch: 大致用近似计数器计数(如count-min sketch,但使用较少的内存). 
-   [cuckoofilter](https://github.com/seiflotfy/cuckoofilter)- 布谷鸟过滤器: 在go中实现的计数布隆过滤器的一个很好的选择. 
-   [编码](https://github.com/zhenjl/encoding)- 去整数压缩库. 
-   [去自适应-基树](https://github.com/plar/go-adaptive-radix-tree)- 去实现自适应基数树. 
-   [去-数据结构](https://github.com/Workiva/go-datastructures)- 收集有用,高性能和线程安全的数据结构. 
-   [去-EF](https://github.com/amallia/go-ef)-  elias-fano编码的执行. 
-   [去-geoindex](https://github.com/hailocab/go-geoindex)- 内存地理索引. 
-   [去-rquad](https://github.com/aurelien-rainone/go-rquad)- 具有有效的点位置和邻居发现的区域四叉树. 
-   [神](https://github.com/emirpasic/gods)- 去数据结构. 容器,集合,列表,堆栈,地图,bidimaps,树,哈希集等. 
-   [golang集](https://github.com/deckarep/golang-set)- 线程安全和非线程安全的高性能套装. 
-   [goset](https://github.com/zoumo/goset)- 一个有用的设置集合实现去. 
-   [goskiplist](https://github.com/ryszard/goskiplist)- 在go中跳过列表实现. 
-   [有一个](https://github.com/kniren/gota)- 实施数据框架,系列和数据争夺方法. 
-   [希尔伯特](https://github.com/google/hilbert)- 去封装映射值和空间填充曲线,如希尔伯特和peano曲线. 
-   [hyperloglog](https://github.com/axiomhq/hyperloglog)- 使用稀疏loglog-beta偏差校正和减少尾部切割空间的hyperloglog实​​现. 
-   [莱文斯坦](https://github.com/agext/levenshtein)- 具有自定义编辑成本的levenshtein距离和相似性度量标准,以及用于常见前缀的winkler奖励. 
-   [莱文斯坦](https://github.com/agnivade/levenshtein)- 执行计算走路距离. 
-   [mafsa](https://github.com/smartystreets/mafsa)- 使用最小完美哈希的ma-fsa实现. 
-   [merkletree](https://github.com/cbergoon/merkletree)- 实施merkle树,提供数据结构内容的高效安全验证. 
-   [咆哮](https://github.com/RoaringBitmap/roaring)- 去实现压缩比特组的软件包. 
-   [skiplist](https://github.com/gansidui/skiplist)-  go中的skiplist实现. 
-   [特里](https://github.com/derekparker/trie)- 在执行中执行. 
-   [ttlcache](https://github.com/diegobernardes/ttlcache)- 内存中的lru string-interface {}映射,golang过期. 
-   [willf /大](https://github.com/willf/bloom)- 去包实施布隆过滤器. 

## 数据库

_数据库在go中实现. _

-   [獾](https://github.com/dgraph-io/badger)- 快速的键值存储. 
-   [bigcache](https://github.com/allegro/bigcache)- 用于千兆字节数据的高效密钥/值缓存. 
-   [螺栓](https://github.com/boltdb/bolt)- 低级别的键/值数据库. 
-   [buntdb](https://github.com/tidwall/buntdb)- 快速,可嵌入,内存中的键/值数据库,以便进行自定义索引和空间支持. 
-   [cache2go](https://github.com/muesli/cache2go)- 内存中的键: 值缓存,支持基于超时的自动失效. 
-   [clusteredbigcache](https://github.com/oaStuff/clusteredBigCache)- 具有集群支持和单个项目到期的bigcache. 
-   [蟑螂](https://github.com/cockroachdb/cockroach)- 可扩展的,地理复制的交易数据存储. 
-   [couchcache](https://github.com/codingsince1985/couchcache)- 由couchbase服务器支持的宁静缓存微服务. 
-   [DGraph组件](https://github.com/dgraph-io/dgraph)- 可扩展,分布式,低延迟,高吞吐量图形数据库. 
-   [diskv](https://github.com/peterbourgon/diskv)- 自行开发的磁盘备份键值存储. 
-   [eliasdb](https://github.com/krotik/eliasdb)- 无依赖的事务图形数据库,具有rest api,短语搜索和类似于sql的查询语言. 
-   [forestdb](https://github.com/couchbase/goforestdb)- 去forestdb的绑定. 
-   [gcache](https://github.com/bluele/gcache)- 缓存库,支持可用缓存,lfu,lru和arc. 
-   [走高速缓存](https://github.com/pmylund/go-cache)- 内存中的密钥: 值存储/缓存(类似于memcached)库,适用于单机应用程序. 
-   [goleveldb](https://github.com/syndtr/goleveldb)- 执行[性LevelDB](https://github.com/google/leveldb)键/值数据库中去. 
-   [gorocksdb](https://github.com/kapitan-k/gorocksdb)-  gorocksdb是一个包装[rocksdb](https://rocksdb.org)写在去. 
-   [groupcache](https://github.com/golang/groupcache)-  groupcache是​​一个缓存和缓存填充库,在很多情况下用作memcached的替代品. 
-   [influxdb](https://github.com/influxdb/influxdb)- 用于度量,事件和实时分析的可伸缩数据存储. 
-   [耶格](https://github.com/jaegertracing/jaeger)- 分布式追踪系统. 
-   [ledisdb](https://github.com/siddontang/ledisdb)-  ledisdb是基于leveldb的高性能nosql,如redis. 
-   [levigo](https://github.com/jmhodges/levigo)-  levigo是leveldb的包装. 
-   [苔藓](https://github.com/couchbase/moss)-  moss是一个简单的lsm键值存储引擎,写入速度为100%. 
-   [piladb](https://github.com/fern4lvarez/piladb)- 基于堆栈数据结构的轻量级宁静数据库引擎. 
-   [普罗米修斯](https://github.com/prometheus/prometheus)- 监测系统和时间序列数据库. 
-   [rqlite](https://github.com/rqlite/rqlite)- 基于sqlite的轻量级分布式关系数据库. 
-   [涂](https://github.com/nanobox-io/golang-scribble)- 小平面文件json商店. 
-   [tempdb中](https://github.com/rafaeljesus/tempdb)- 临时物品的键值存储. 
-   [tidb](https://github.com/pingcap/tidb)-  tidb是一个分布式的sql数据库. 灵感来自谷歌f1的设计. 
-   [细节一般](https://github.com/HouzuoGuo/tiedot)- 你的nosql数据库由golang提供支持. 
-   [华斯度](https://github.com/chrislusf/vasto)- 分布式高性能键值存储. 在磁盘上. 最终一致. 哈. 无需中断服务即可增长或缩小. 

_数据库模式迁移. _

-   [达尔文](https://github.com/GuiaBolso/darwin)- 数据库模式进化库. 
-   [去-灯具](https://github.com/RichardKnop/go-fixtures)- 用于golang优秀的内置数据库/ sql库的django风格的装置. 
-   [船夫](https://github.com/emvicom/gondolier)-  gondolier是一个使用结构自动迁移数据库模式的库. 
-   [鹅](https://github.com/steinbacher/goose)- 数据库迁移工具. 您可以通过创建增量sql或转到脚本来管理数据库的演变. 
-   [gormigrate](https://github.com/go-gormigrate/gormigrate)- 用于gorm orm的数据库模式迁移助手. 
-   [迁移](https://github.com/mattes/migrate)- 数据库迁移. cli和golang图书馆. 
-   [pravasan](https://github.com/pravasan/pravasan)- 简单的迁移工具 - 目前用于mysql,但计划很快支持postgres,sqlite,mongodb等. 
-   [苏打](https://github.com/markbates/pop/tree/master/soda)- 数据库迁移,创建,orm等...用于mysql,postgresql和sqlite. 
-   [SQL-迁移](https://github.com/rubenv/sql-migrate)- 数据库迁移工具. 允许使用go-bindata将迁移嵌入到应用程序中. 

_数据库工具. _

-   [chproxy](https://github.com/Vertamedia/chproxy)-  clickhouse数据库的http代理. 
-   [clickhouse散装](https://github.com/nikepan/clickhouse-bulk)- 收集小型零售商并向Clickhouse服务器发送大量请求. 
-   [去MySQL的](https://github.com/siddontang/go-mysql)- 去工具集来处理mysql协议和复制. 
-   [去MySQL的-elasticsearch](https://github.com/siddontang/go-mysql-elasticsearch)- 将你的mysql数据自动同步到elasticsearch. 
-   [kingshard](https://github.com/flike/kingshard)-  kingshard是由golang提供动力的高性能mysql代理. 
-   [myreplication](https://github.com/2tvenom/myreplication)-  mysql二进制日志复制监听器. 支持基于语句和行的复制. 
-   [配器](https://github.com/github/orchestrator)-  mysql复制拓扑管理器和可视化器. 
-   [pgweb](https://github.com/sosedoff/pgweb)- 基于web的postgresql数据库浏览器. 
-   [预备](https://github.com/hexdigest/prep)- 使用准备的SQL语句而不更改您的代码. 
-   [PERST](https://github.com/nuveo/prest)- 从任何postgresql数据库提供一个宁静的api. 
-   [rwdb](https://github.com/andizzle/rwdb)-  rwdb为多个数据库服务器设置提供了只读副本功能. 
-   [vitess](https://github.com/youtube/vitess)-  vitess提供的服务器和工具可以方便地扩展大型web服务的mysql数据库. 

_SQL查询生成器,用于构建和使用sql的库. _

-   [DAT](https://github.com/mgutz/dat)- 去postgres数据访问工具包. 
-   [dotsql](https://github.com/gchaincl/dotsql)- 去图书馆,帮助您将sql文件保存在一个地方并轻松使用它们. 
-   [gendry](https://github.com/didi/gendry)- 非侵入式SQL构建器和强大的数据绑定器. 
-   [goqu](https://github.com/doug-martin/goqu)- 惯用的SQL生成器和查询库. 
-   [伊戈尔](https://github.com/galeone/igor)-  postgresql的抽象层,支持高级功能并使用类似gorm的语法. 
-   [OZZO  -  DBX](https://github.com/go-ozzo/ozzo-dbx)- 强大的数据检索方法以及与数据库无关的查询构建功能. 
-   [scaneo](https://github.com/variadico/scaneo)- 生成go代码将数据库行转换为任意结构. 
-   [sqrl](https://github.com/elgris/sqrl)-  SQL查询生成器,改进性能的松鼠叉. 
-   [松鼠](https://github.com/Masterminds/squirrel)- 去图书馆,帮助你建立SQL查询. 
-   [XO](https://github.com/knq/xo)- 根据现有模式定义或支持postgresql,mysql,sqlite,oracle和microsoft sql server的自定义查询为数据库生成惯用代码. 

## 数据库驱动

_用于连接和操作数据库的库. _

-   关系数据库

    -   [avatica](https://github.com/Boostport/avatica)- 数据库/ sql的apache phoenix / avatica sql驱动程序. 
    -   [BGC](https://github.com/viant/bgc)- 数据存储连接for bigquery. 
    -   [firebirdsql](https://github.com/nakagami/firebirdsql)- 火鸟rdbms的SQL驱动程序去. 
    -   [去-ADODB](https://github.com/mattn/go-adodb)- 使用数据库/ sql的go的microsoft activex对象数据库驱动程序. 
    -   [去-mssqldb](https://github.com/denisenkom/go-mssqldb)- 微软的MSSQL驱动程序去. 
    -   [去-OCI8](https://github.com/mattn/go-oci8)- 使用数据库/ sql的oracle驱动程序. 
    -   [去-SQL驱动程序/ MySQL的](https://github.com/go-sql-driver/mysql)-  mysql的驱动程序去. 
    -   [去-sqlite3的](https://github.com/mattn/go-sqlite3)- 使用数据库/ sql的sqlite3驱动程序. 
    -   [gofreetds](https://github.com/minus5/gofreetds)- 微软的MSSQL驱动程序. 去包装[freetds的](http://www.freetds.org). 
    -   [PGX](https://github.com/jackc/pgx)-  postgresql驱动程序支持超出数据库/ sql公开的功能. 
    -   [PQ](https://github.com/lib/pq)-  pure go postgres driver for database / sql. 

-   nosql数据库

    -   [塞客户端,去](https://github.com/aerospike/aerospike-client-go)- 使用语言的aerospike客户端. 
    -   [arangolite](https://github.com/solher/arangolite)-  arangodb轻量级golang驱动程序. 
    -   [ASC](https://github.com/viant/asc)- 用于Aerospike的数据存储连接. 
    -   [凯莱](https://github.com/google/cayley)- 支持多个后端的图形数据库. 
    -   [DSC](https://github.com/viant/dsc)-  sql,nosql,结构化文件的数据存储连接. 
    -   [dynago](https://github.com/underarmour/dynago)-  dynago是dynamodb最不惊讶的客户的原则. 
    -   [去-couchbase](https://github.com/couchbase/go-couchbase)-  couchbase客户端. 
    -   [去-的CouchDB](https://github.com/fjl/go-couchdb)- 另一个couchdb http api包装去. 
    -   [gocb](https://github.com/couchbase/gocb)- 官方couchbase去sdk. 
    -   [gocql](http://gocql.github.io)- 去apache cassandra的语言驱动程序. 
    -   [gomemcache](https://github.com/bradfitz/gomemcache/)-  go编程语言的memcache客户端库. 
    -   [gorethink](https://github.com/dancannon/gorethink)- 去rethinkdb的语言驱动程序. 
    -   [goriak](https://github.com/zegl/goriak)- 去riak kv的语言驱动程序. 
    -   [氧化镁](https://github.com/globalsign/mgo)- 用于go语言的mongodb驱动程序,它遵循标准成语,在非常简单的api下实现丰富且经过测试的功能选择
    -   [蒙戈-GO-司机](https://github.com/mongodb/mongo-go-driver)-  go语言的官方mongodb驱动程序. 
    -   [Neo4j的](https://github.com/cihangir/neo4j)-  goo的neo4j rest API绑定. 
    -   [Neo4j的,去](https://github.com/davemeehan/Neo4j-GO)-  goo的neo4j休息客户端. 
    -   [neoism](https://github.com/jmcvetta/neoism)-  golang的neo4j客户端. 
    -   [redigo](https://github.com/garyburd/redigo)-  redigo是redis数据库的一个go客户端. 
    -   [Redis的](https://github.com/go-redis/redis)-  golang的redis客户端. 
    -   [Redis的](https://github.com/hoisie/redis)- 简单,功能强大的redis客户端. 
    -   [Redis的](https://github.com/bsm/redeo)-  redis协议兼容的tcp服务器/服务. 
    -   [xredis](https://github.com/shomali11/xredis)- 类型安全,可定制,干净和易于使用的redis客户端. 

-   搜索和分析数据库. 
    -   [BLEVE](https://github.com/blevesearch/bleve)- 现代文本索引库去. 
    -   [弹](https://github.com/olivere/elastic)-  elasticsearch客户端. 
    -   [elasticsql](https://github.com/cch123/elasticsql)- 在SQL中将sql转换为elasticsearch dsl. 
    -   [elastigo](https://github.com/mattbaird/elastigo)-  elasticsearch客户端库. 
    -   [去](https://github.com/OwnLocal/goes)- 与elasticsearch交互的库. 
    -   [暴动](https://github.com/go-ego/riot)- 走开源,分布式,简单高效的搜索引擎
    -   [skizze](https://github.com/seiflotfy/skizze)- 概率数据结构服务和存储. 

## 日期和时间

_用于处理日期和时间的库. _

-   [碳](https://github.com/uniplaces/carbon)- 使用很多util方法进行简单的时间延伸,从php碳库移植过来. 
-   [日期](https://github.com/rickb777/date)- 增加处理日期,日期范围,时间跨度,时间段和时间的时间. 
-   [dateparse](https://github.com/araddon/dateparse)- 事先不知道格式的解析日期. 
-   [durafmt](https://github.com/hako/durafmt)- 持续时间格式化库. 
-   [FEIERTAGE](https://github.com/wlbr/feiertage)- 用于计算德国公众假期的功能集,包括专攻德国(Bundesländer). 像复活节,五旬节,感恩节......
-   [去波斯日历](https://github.com/yaa110/go-persian-calendar)-  go(golang)中实施波斯(太阳能hijri)日历. 
-   [去,日出](https://github.com/nathan-osman/go-sunrise)- 计算给定位置的日出和日落时间. 
-   [goweek](https://github.com/grsmv/goweek)- 与golang的周实体一起工作的图书馆. 
-   [现在](https://github.com/jinzhu/now)- 现在是golang的时间工具包. 
-   [nulltime](https://github.com/kirillDanshin/nulltime)- 可以为空`了time.time`. 
-   [的strftime](https://github.com/awoodbeck/strftime)- 兼容c99的strftime格式器. 
-   [时间跨度](https://github.com/SaidinWoT/timespan)- 与时间间隔交互,定义为开始时间和持续时间. 
-   [timeutil](https://github.com/leekchan/timeutil)- 有用的扩展(timedelta,strftime,...)到golang的时间包. 
-   [星期二](https://github.com/osteele/tuesday)-  ruby​​兼容的strftime函数. 

## 分布式系统

_有助于构建分布式系统的软件包. _

-   [块根芹](https://github.com/svcavallar/celeriac.v1)- 增加对交互和监测芹菜工作者,任务和事件的支持. 
-   [一贯](https://github.com/buraksezer/consistent)- 与有界负载一致的哈希. 
-   [digota](https://github.com/digota/digota)-  grpc电子商务微服务. 
-   [DRMAA](https://github.com/dgruber/drmaa)- 基于drmaa标准的集群调度程序的作业提交库. 
-   [发射-IO](https://github.com/emitter-io/emitter)- 高性能,分布式,安全和低延迟的发布 - 订阅平台,内置mqtt,websockets和love. 
-   [流图](https://github.com/vectaport/flowgraph)-  mpi样式的预发送协调层. 
-   [闪光](https://github.com/chrislusf/gleam)- 以pure go和luajit编写的快速和可扩展的分布式映射/缩减系统,将go的高并发性与luajit的高性能相结合,可独立运行或分布式运行. 
-   [辉光](https://github.com/chrislusf/glow)- 易于使用的可扩展分布式大数据处理,map-reduce,dag执行,全部采用纯粹的方式. 
-   [走健康](https://github.com/InVisionApp/go-health)- 用于在服务中启用异步依赖性运行状况检查的库. 
-   [去跳](https://github.com/dgryski/go-jump)- 谷歌的"跳转"一致哈希函数的端口. 
-   [去-KIT](https://github.com/go-kit/kit)- 支持服务发现,负载均衡,可插拔传输,请求跟踪等的微服务工具包. 
-   [gorpc](https://github.com/valyala/gorpc)- 高负载的简单,快速和可扩展的rpc库. 
-   [GRPC,去](https://github.com/grpc/grpc-go)-  grpc的语言实现. 基于http / 2的rpc. 
-   [海姆达尔](https://github.com/gojektech/heimdall)- 具有重试和hystrix功能的强化的http客户端. 
-   [hprose](https://github.com/hprose/hprose-golang)- 非常新的rpc库,现在支持25种以上的语言. 
-   [jsonrpc](https://github.com/osamingo/jsonrpc)-  jsonrpc包帮助实现了json-rpc 2.0. 
-   [jsonrpc](https://github.com/ybbus/jsonrpc)-  json-rpc 2.0 http客户端实现. 
-   [krakend](https://github.com/devopsfaith/krakend)- 带有中间件的超高性能api网关框架. 
-   [微](https://github.com/micro/micro)- 可插拔的微服务工具包和分布式系统平台. 
-   [NATS](https://github.com/nats-io/gnatsd)- 针对微服务,iot和云原生系统的轻量级高性能消息传递系统. 
-   [筏](https://github.com/hashicorp/raft)- 由hashicorp编写的golang实现的木筏共识协议. 
-   [筏](https://github.com/coreos/etcd/tree/master/raft)- 由coreos实施木筏共识协议. 
-   [ringpop,去](https://github.com/uber/ringpop-go)- 可扩展的,容错的应用程序层分片用于前往应用程序. 
-   [rpcx](https://github.com/smallnest/rpcx)- 像alibaba dubbo这样的分布式可插入rpc服务框架. 
-   [侦探](https://github.com/ursiform/sleuth)- 用于无主p2p自动发现和http服务之间的rpc的库(使用[zeromq](https://github.com/zeromq/libzmq)). 
-   [tendermint](https://github.com/tendermint/tendermint)- 高性能中间件,用于将使用任何编程语言编写的状态机转换为使用tendermint共识和区块链协议的拜占庭容错复制状态机. 
-   [激流](https://github.com/anacrolix/torrent)-  bittorrent客户端软件包. 
    -   [DHT](https://godoc.org/github.com/anacrolix/dht)-  bittorrent kademlia实施. 
    -   [去-peerflix](https://github.com/Sioro-Neoku/go-peerflix)- 视频流媒体客户端. 

## 电子邮件

_实现电子邮件创建和发送的库和工具. _

-   [chasquid](https://blitiri.com.ar/p/chasquid)-  smtp服务器写入去. 
-   [洁肤水](https://github.com/aymerick/douceur)- 您的HTML电子邮件的CSS内联. 
-   [电子邮件](https://github.com/jordan-wright/email)- 一个强大而灵活的电子邮件库. 
-   [去-DKIM](https://github.com/toorop/go-dkim)-  dkim库,签署和验证电子邮件. 
-   [去-IMAP](https://github.com/emersion/go-imap)- 客户端和服务器的imap库. 
-   [去消息](https://github.com/emersion/go-message)- 用于互联网消息格式和邮件消息的流媒体库. 
-   [gomail](https://github.com/go-gomail/gomail/)-  gomail是一个非常简单而强大的发送邮件的软件包. 
-   [hectane](https://github.com/hectane/hectane)- 提供http api的轻量级smtp客户端. 
-   [爱马仕](https://github.com/matcornic/hermes)- 生成干净,响应式html电子邮件的golang包. 
-   [mailhog](https://github.com/mailhog/MailHog)- 使用web和api界面进行电子邮件和smtp测试. 
-   [sendgrid](https://github.com/sendgrid/sendgrid-go)-  sendgrid的去库发送电子邮件. 
-   [SMTP](https://github.com/mailhog/smtp)-  smtp服务器协议状态机. 

## 可嵌入脚本语言

_在你的代码中嵌入其他语言. _

-   [集会](https://github.com/PuerkitoBio/agora)- 动态类型,嵌入式编程语言. 
-   [ANKO](https://github.com/mattn/anko)- 用go编写的可编写脚本的解释器. 
-   [粘合剂](https://github.com/alexeyco/binder)- 去lua绑定库,基于[地鼠,LUA](https://github.com/yuin/gopher-lua). 
-   [GISP](https://github.com/jcla1/gisp)- 简单的lisp进去. 
-   [去-duktape](https://github.com/olebedev/go-duktape)-  duktape JavaScript引擎绑定去. 
-   [去-LUA](https://github.com/Shopify/go-lua)-  lua 5.2 vm的端口去纯粹去. 
-   [去的PHP](https://github.com/deuill/go-php)-  php绑定去. 
-   [去的Python](https://github.com/sbinet/go-python)- 天真去绑定到cpython c-api. 
-   [golua](https://github.com/aarzilli/golua)- 为lua c api绑定. 
-   [地鼠,LUA](https://github.com/yuin/gopher-lua)-  lua 5.1 vm和编译器写入go. 
-   [恩加罗](https://github.com/db47h/ngaro)- 可嵌入ngaro虚拟机实现使复古脚本. 
-   [玫瑰油](https://github.com/robertkrimen/otto)- 写在go的JavaScript解释器. 
-   [金银丝](https://github.com/ian-kent/purl)-  perl 5.18.2嵌入进去. 

## 档

_用于处理文件和文件系统的库. _

-   [afero](https://github.com/spf13/afero)- 文件系统抽象系统. 
-   [去-CSV标签](https://github.com/artonge/go-csv-tag)- 使用标签加载csv文件. 
-   [去-GTFS](https://github.com/artonge/go-gtfs)- 加载gtfs文件. 
-   [通知](https://github.com/rjeczalik/notify)- 使用简单API的文件系统事件通知库,类似于操作系统/信号. 
-   [天空步行者](https://github.com/dixonwille/skywalker)- 允许用户轻松地同时浏览文件系统. 
-   [tarfs](https://github.com/posener/tarfs)- 执行[`文件系统`接口](https://godoc.org/github.com/kr/fs#FileSystem)为tar文件. 

## 金融

_会计和财务软件包. _

-   [会计](https://github.com/leekchan/accounting)-  golang的货币和货币格式. 
-   [十进制](https://github.com/shopspring/decimal)- 任意精度的定点十进制数字. 
-   [去融资](https://github.com/FlashBoys/go-finance)- 全面的金融市场数据进入. 
-   [去融资](https://github.com/alpeb/go-finance)- 资金时间价值(年金),现金流量,利率转换,债券和折旧计算的财务函数库. 
-   [走钱](https://github.com/rhymond/go-money)- 实施捕鸟者的钱模式. 
-   [ofxgo](https://github.com/aclindsa/ofxgo)- 查询x服务器和/或解析响应(使用示例命令行客户端). 
-   [交易](https://github.com/claygod/transaction)- 以多线程模式运行的嵌入式账户事务数据库. 
-   [增值税](https://github.com/dannyvankooten/vat)- 增值税号码验证和欧盟增值税率. 

## 形式

_用于处理表单的库. _

-   [捆绑](https://github.com/robfig/bind)- 将表单数据绑定到任何值. 
-   [捆绑](https://github.com/mholt/binding)- 将net / http请求的表单和json数据绑定到结构体. 
-   [符合](https://github.com/leebenson/conform)- 保持用户输入检查. 基于结构标签对数据进行修整,清理和擦洗. 
-   [形成](https://github.com/go-playground/form)- 将url.values解码为go值(s),并将go值(s)编码为url.values. 双阵列和全地图支持. 
-   [formam](https://github.com/monoculum/formam)- 将表单的值解码为结构体. 
-   [形式](https://github.com/albrow/forms)- 框架不可知的库,用于解析和验证支持多部分表单和文件的form / json数据. 
-   [大猩猩/ CSRF](https://github.com/gorilla/csrf)- 为web应用程序和服务提供csrf保护. 
-   [nosurf](https://github.com/justinas/nosurf)-  csrf保护中间件的去. 

## 游戏开发

_真棒游戏开发库. _

-   [azul3d](https://github.com/azul3d/engine)-  3d写的游戏引擎. 
-   [ebiten](https://github.com/hajimehoshi/ebiten)- 死掉简单的2D游戏库. 
-   [恩戈](https://github.com/EngoEngine/engo)-  engo是一款开源的2D游戏引擎. 它遵循实体 - 组件系统范例. 
-   [garageengine](https://github.com/vova616/GarageEngine)- 写在opengl上的2D游戏引擎. 
-   [GLOP](https://github.com/runningwild/glop)-  glop(电力游戏库)是一个相当简单的跨平台游戏库. 
-   [去,爱仕达](https://github.com/beefsack/go-astar)- 执行a\*寻路算法. 
-   [去,啥东东](https://github.com/GlenKelley/go-collada)- 开始使用collada文件格式的软件包. 
-   [去-SDL2](https://github.com/veandco/go-sdl2)- 去绑定的[简单的直接媒体层](https://www.libsdl.org/). 
-   [go3d](https://github.com/ungerik/go3d)- 面向性能的2d / 3d数学包. 
-   [戈内特](https://github.com/xtaci/gonet)- 使用golang实现的游戏服务器框架. 
-   [汕头超声电子](https://github.com/xiaonanln/goworld)- 可扩展的游戏服务器引擎,具有空间实体框架和热插拔功能
-   [叶](https://github.com/name5566/leaf)- 轻量级游戏服务器框架. 
-   [纳米](https://github.com/lonnng/nano)- 轻量,设施,高性能golang游戏服务器框架
-   [橡木](https://github.com/oakmound/oak)- 纯粹的游戏引擎. 
-   [像素](https://github.com/faiface/pixel)- 手工制作的2D游戏库. 
-   [raylib,去](https://github.com/gen2brain/raylib-go)- 去绑定[raylib](http://www.raylib.com/),一个简单易用的图书馆来学习电子游戏编程. 
-   [termloop](https://github.com/JoelOtter/termloop)- 基于终端的游戏引擎,构建于termbox之上. 

## 代和泛型

_通过代码生成来增强语言功能的工具,比如泛型. _

-   [efaceconv](https://github.com/t0pep0/efaceconv)- 代码生成工具,用于从接口{}高性能转换为不分配的不可变类型. 
-   [根](https://github.com/clipperhouse/gen)- 用于"泛型"功能的代码生成工具. 
-   [去-枚举](https://github.com/abice/go-enum)- 代码注释的枚举代码生成. 
-   [去-LINQ](https://github.com/ahmetalpbalkan/go-linq)-  .net类似linq的查询方法. 
-   [goderive](https://github.com/awalterschulze/goderive)- 从输入类型派生函数. 
-   [接口](https://github.com/rjeczalik/interfaces)- 用于生成接口定义的命令行工具. 
-   [詹妮弗](https://github.com/dave/jennifer)- 生成没有模板的任意转码. 
-   [pkgreflect](https://github.com/ungerik/pkgreflect)- 进行软件包作用域反射的预处理器. 

## 地理

_地理工具和服务器_

-   [地理藏宝](https://github.com/melihmucuk/geocache)- 适用于基于地理位置的应用程序的内存缓存. 
-   [OSM](https://github.com/paulmach/osm)- 用于阅读,编写和使用openstreetmap数据和apis的库. 
-   [PBF](https://github.com/maguro/pbf)-  openstreetmap pbf golang编码器/解码器. 
-   [s2几何](https://github.com/golang/geo)-  s2几何库中去. 
-   [tile38](https://github.com/tidwall/tile38)- 具有空间索引和实时geofencing的地理位置db. 

## 去编译器

_编译工具转到其他语言. _

-   [gopherjs](https://github.com/gopherjs/gopherjs)- 从编译器转到JavaScript. 
-   [llgo](https://github.com/go-llvm/llgo)- 基于llvm的编译器. 
-   [tardisgo](https://github.com/tardisgo/tardisgo)-  golang to haxe到cpp / csharp / java / javascript transpiler. 

## 够程

_用于管理和配合goroutines的工具. _

-   [的CyclicBarrier](https://github.com/marusama/cyclicbarrier)-  golang的cyclicbarrier. 
-   [去絮凝物](https://github.com/workanator/go-floc)- 轻松编排门厅. 
-   [去流](https://github.com/kamildrazkiewicz/go-flow)- 控制goroutines执行顺序. 
-   [goslaves](https://github.com/themester/GoSlaves)- 简单和异步的goroutine池库. 
-   [goworker](https://github.com/benmanns/goworker)-  goworker是一个基于工作的后台工作者. 
-   [grpool](https://github.com/ivpusic/grpool)- 轻量级goroutine池. 
-   [平行-FN](https://github.com/rafaeljesus/parallel-fn)- 并行运行功能. 
-   [池](https://github.com/go-playground/pool)- 有限的goroutine或无限的goroutine池,以便更方便地处理和取消goroutine. 
-   [信号](https://github.com/kamilsk/semaphore)- 基于频道和上下文的超时锁定/解锁操作的信号模式实现. 
-   [信号](https://github.com/marusama/semaphore)- 基于cas的快速调整信号量实现(比基于通道的信号量实现更快). 
-   [金枪鱼](https://github.com/Jeffail/tunny)-  golang的goroutine池. 
-   [工人池](https://github.com/vardius/worker-pool)-  goworker是一个简单的异步工作者池. 
-   [工作者池](https://github.com/gammazero/workerpool)-  goroutine池限制任务执行的并发性,而不是排队的任务数. 

## GUI

_用于构建gui应用程序的库. _

_工具包_

-   [应用](https://github.com/murlokswarm/app)- 使用go,html和css创建应用程序包. 支持: macos,窗口正在进行中. 
-   [去-astilectron](https://github.com/asticode/go-astilectron)- 使用go和html / js / css(由电子驱动)构建跨平台gui应用程序. 
-   [去-GTK](http://mattn.github.io/go-gtk/)- 去绑定gtk. 
-   [去-QML](https://github.com/go-qml/qml)-  qml支持go语言. 
-   [去-sciter](https://github.com/sciter-sdk/go-sciter)- 为sciter绑定: 用于现代桌面UI开发的可嵌入html / css /脚本引擎. 跨平台. 
-   [goqt](https://github.com/visualfc/goqt)-  golang绑定到qt跨平台应用程序框架. 
-   [gotk3](https://github.com/gotk3/gotk3)- 去绑定gtk3. 
-   [gowd](https://github.com/dtylman/gowd)- 使用go,html,css和nw.js进行快速简单的桌面用户界面开发. 跨平台. 
-   [QT](https://github.com/therecipe/qt)- 支持qt绑定(支持windows / macos / linux / android / ios / sailfish os / raspberry pi). 
-   [UI](https://github.com/andlabs/ui)- 平台本地GUI库去. 跨平台. 
-   [步行](https://github.com/lxn/walk)-  windows应用程序库工具包
-   [网页流量](https://github.com/zserge/webview)- 使用简单的双向javascript绑定(windows / macos / linux)的跨平台webview窗口. 

_相互作用_

-   [gosx-通知](https://github.com/deckarep/gosx-notifier)-  osx桌面通知库去. 
-   [robotgo](https://github.com/go-vgo/robotgo)- 去本地的跨平台gui系统自动化. 控制鼠标,键盘和其他. 
-   [系统托盘](https://github.com/getlantern/systray)- 跨平台去图书馆在通知区域放置一个图标和菜单. 
-   [trayhost](https://github.com/shurcooL/trayhost)- 跨平台去图书馆在主机操作系统的任务栏中放置一个图标. 

## 硬件

_用于与硬件交互的库,工具和教程. _

看到[去硬件](https://github.com/rakyll/go-hardware)为一个全面的名单. 

## 图片

_用于处理图像的库. _

-   [图片报](https://github.com/anthonynsimon/bild)- 收集纯粹的图像处理算法. 
-   [BIMG](https://github.com/h2non/bimg)- 使用libvips进行快速高效的图像处理的小型软件包. 
-   [geopattern](https://github.com/pravj/geopattern)- 从一个字符串创建美丽的生成图像模式. 
-   [GG](https://github.com/fogleman/gg)- 纯粹的2D渲染. 
-   [礼品](https://github.com/disintegration/gift)- 图像处理过滤器包. 
-   [去开罗](https://github.com/ungerik/go-cairo)- 为开罗图形库绑定. 
-   [去-GD](https://github.com/bolknote/go-gd)- 绑定gd库. 
-   [去裸照](https://github.com/koyachi/go-nude)- 去裸露检测. 
-   [去-的OpenCV](https://github.com/lazywei/go-opencv)- 去绑定opencv. 
-   [走,网页颜色](https://github.com/jyotiska/go-webcolors)- 从python webcolors库的端口去. 
-   [gocv](https://github.com/hybridgroup/gocv)- 使用opencv 3.3+进行计算机视觉软件包. 
-   [goimagehash](https://github.com/corona10/goimagehash)- 去感性的图像哈希包. 
-   [govatar](https://github.com/o1egl/govatar)- 用于生成有趣头像的库和cmd工具. 
-   [imagick](https://github.com/gographics/imagick)- 绑定到imagemagick的magickwand c api. 
-   [假想](https://github.com/h2non/imaginary)- 快速简单的http microservice进行图像大小调整. 
-   [成像](https://github.com/disintegration/imaging)- 简单的去图像处理包. 
-   [IMG](https://github.com/hawx/img)- 选择图像处理工具. 
-   [LN](https://github.com/fogleman/ln)- 三维线条艺术渲染去. 
-   [MPO](https://github.com/donatj/mpo)- 用于mpo 3d照片的解码器和转换工具. 
-   [picfit](https://github.com/thoas/picfit)- 一个用go编写的图像调整大小服务器. 
-   [PT](https://github.com/fogleman/pt)- 路径跟踪引擎写入. 
-   [调整](https://github.com/nfnt/resize)- 使用通用插值方法进行图像大小调整. 
-   [苏亚雷斯](https://github.com/bamiaux/rez)- 图像调整大小在纯去和simd. 
-   [smartcrop](https://github.com/muesli/smartcrop)- 为任意图像和裁剪大小找到很好的作物. 
-   [svgo](https://github.com/ajstarks/svgo)- 去svg世代的语言库. 
-   [TGA](https://github.com/ftrvxmtrx/tga)- 包tga是targa图像格式解码器/编码器. 

## 物联网(物联网)

_用于编程设备的库. _

-   [connectordb](https://github.com/connectordb/connectordb)- 量化自我和物联网的开源平台. 
-   [设备](https://github.com/goiot/devices)- 用于iot设备的库套件,用于x / exp / io的实验. 
-   [爱娃](https://github.com/xcodersun/eywa)- 项目eywa本质上是一个连接管理器,用于跟踪连接的设备. 
-   [flogo](https://github.com/tibcosoftware/flogo)- 项目flogo是一个开源的IOT边缘应用程序和集成框架. 
-   [关贸总协定](https://github.com/paypal/gatt)-  gatt是构建蓝牙低功耗外设的一揽子计划. 
-   [gobot](https://github.com/hybridgroup/gobot/)-  gobot是机器人,物理计算和物联网的框架. 
-   [物联网](https://github.com/vaelen/iot/)-  iot是实施谷歌iot核心设备的简单框架. 
-   [mainflux](https://github.com/Mainflux/mainflux)- 工业Iot消息传递和设备管理服务器. 
-   [PERIPH](https://periph.io/)- 外设I / O接口与低级别的董事会设施. 
-   [sensorbee](https://github.com/sensorbee/sensorbee)- 用于iot的轻量级流处理引擎. 

## 记录

_用于生成和使用日志文件的库. _

-   [distillog](https://github.com/amoghe/distillog)- 蒸馏水平日志(将其视为stdlib +日志水平). 
-   [GLG](https://github.com/kpango/glg)-  glg是简单快速的平稳日志库. 
-   [考勤记录](https://github.com/golang/glog)- 走平的执行日志. 
-   [去-cronowriter](https://github.com/utahta/go-cronowriter)- 简单的作家,根据当前日期和时间自动旋转日志文件,如cronolog. 
-   [去日志](https://github.com/siddontang/go-log)- 日志库支持级别和多处理程序. 
-   [去日志](https://github.com/ian-kent/go-log)-  go中的log4j实现. 
-   [去记录器](https://github.com/apsdehal/go-logger)- 简单的去程序记录程序,以及级别处理程序. 
-   [gologger](https://github.com/sadlil/gologger)- 简单易用的日志库去,登录彩色控制台,简单的控制台,文件或elasticsearch. 
-   [gomol](https://github.com/aphistic/gomol)- 多输出结构化日志记录,带有可扩展的日志记录输出. 
-   [走了/日志](https://github.com/One-com/gone/tree/master/log)- 快速,可扩展,功能齐全的std-lib源兼容日志库. 
-   [journald](https://github.com/ssgreg/journald)- 执行systemd日志的本机api进行日志记录. 
-   [日志](https://github.com/apex/log)- 去结构化的日志包. 
-   [日志](https://github.com/go-playground/log)- 简单,可配置和可扩展的结构化日志记录. 
-   [日志](https://github.com/teris-io/log)- 结构化的日志界面可以将日志外观与其实现完全分开. 
-   [登录航程](https://github.com/firstrow/logvoyage)- 用golang编写的全功能日志saas. 
-   [log15](https://github.com/inconshreveable/log15)- 简单,强大的日志记录. 
-   [logdump](https://github.com/ewwwwwqm/logdump)- 用于多级日志记录的软件包. 
-   [logex](https://github.com/chzyer/logex)-  golang日志库,支持跟踪和级别,由标准日志库包装. 
-   [记录仪](https://github.com/azer/logger)- 简约的日志库去. 
-   [商标](https://github.com/mbndr/logo)-  golang记录器到不同的可配置编写器. 
-   [logrus](https://github.com/Sirupsen/logrus)- 结构化的记录器去. 
-   [logrusly](https://github.com/sebest/logrusly)-[logrus](https://github.com/sirupsen/logrus)插件将错误发​​送到[loggly](https://www.loggly.com/). 
-   [logutils](https://github.com/hashicorp/logutils)- 稍微好一点的登录(golang)扩展标准记录器的实用程序. 
-   [logxi](https://github.com/mgutz/logxi)-  12个因子的应用程序记录器,速度快,让你开心. 
-   [樵夫](https://github.com/natefinch/lumberjack)- 简单的滚动记录器,实现io.writecloser. 
-   [管理记录](https://github.com/jbrodriguez/mlog)- 简单的日志记录模块,有5个级别,一个可选的旋转日志文件功能和stdout / stderr输出. 
-   [OZZO日志](https://github.com/go-ozzo/ozzo-log)- 支持日志严重性,分类和过滤的高性能日志记录. 可以将过滤的日志消息发送到各种目标(例如控制台,网络,邮件). 
-   [seelog](https://github.com/cihub/seelog)- 通过灵活的调度,过滤和格式化记录功能. 
-   [喷](https://github.com/davecgh/go-spew)- 为数据结构实现深度漂亮的打印机以帮助调试. 
-   [stdlog](https://github.com/alexcesaro/log)-  stdlog是一个面向对象的库,提供了稳定的日志记录. 它对cron作业非常有用. 
-   [尾巴](https://github.com/hpcloud/tail)- 开始努力模拟bsd tail程序的功能. 
-   [Xlog软件](https://github.com/xfxdev/xlog)- 插件体系结构和灵活的日志系统,带有级别ctrl,多个日志目标和自定义日志格式. 
-   [Xlog软件](https://github.com/rs/xlog)- 结构化的记录器`净/上下文`了解具有灵活调度功能的http处理程序. 
-   [ZAP](https://github.com/uber-go/zap)- 快速,结构化,平稳登录. 
-   [zerolog](https://github.com/rs/zerolog)- 零分配json记录器. 

## 机器学习

_机器学习库. _

-   [贝叶斯](https://github.com/jbrukh/bayesian)-  golang的朴素贝叶斯分类. 
-   [云雾森林](https://github.com/ryanbressler/CloudForest)- 用于纯机器学习的快速,灵活,多线程的决策树组合. 
-   [fonet](https://github.com/Fontinalis/fonet)- 一个用go编写的深度神经网络库. 
-   [加戈](https://github.com/MaxHalford/gago)- 多种群,灵活,并行的遗传算法. 
-   [走集群](https://github.com/e-XpertSolutions/go-cluster)- 实施k模式和k-prototypes聚类算法. 
-   [深入](https://github.com/patrikeh/go-deep)- 一个功能丰富的神经网络库. 
-   [去,文芳](https://github.com/white-pony/go-fann)- 绑定快速人工神经网络(fann)库. 
-   [去-的Galib](https://github.com/thoj/go-galib)- 用go / golang编写的遗传算法库. 
-   [去-PR](https://github.com/daviddengcn/go-pr)- 模式识别软件包go lang. 
-   [gobrain](https://github.com/goml/gobrain)- 用go编写的神经网络. 
-   [godist](https://github.com/e-dard/godist)- 各种概率分布和相关方法. 
-   [GOGA](https://github.com/tomcraven/goga)- 遗传算法库. 
-   [golearn](https://github.com/sjwhitworth/golearn)- 一般机器学习库去. 
-   [golinear](https://github.com/danieldk/golinear)-  liblinear绑定去. 
-   [goml](https://github.com/cdipaolo/goml)- 在线机器学习. 
-   [gorecommend](https://github.com/timkaye11/goRecommend)- 用go编写的推荐算法库. 
-   [gorgonia](https://github.com/chewxy/gorgonia)- 基于图形的计算库,如theano for go,为构建各种机器学习和神经网络算法提供原语. 
-   [goscore](https://github.com/asafschers/goscore)- 为pmml得分api. 
-   [gosseract](https://github.com/otiai10/gosseract)- 通过使用tesseract c ++库去包ocr(光学字符识别). 
-   [LIBSVM](https://github.com/datastream/libsvm)- 基于libsvm 3.14的libsvm golang版本派生工作. 
-   [mlgo](https://github.com/NullHypothesis/mlgo)- 这个项目旨在提供简约的机器学习算法. 
-   [整齐](https://github.com/jinyeom/neat)- 即插即用,增强拓扑结构的神经元进化并行机制(整齐). 
-   [神经走](https://github.com/schuyler/neural-go)- 通过反向传播训练实施的多层感知器网络. 
-   [probab](https://github.com/ThePaw/probab)- 概率分布函数. 贝叶斯推断. 写在纯去. 
-   [regommend](https://github.com/muesli/regommend)- 推荐和协作过滤引擎. 
-   [屏蔽](https://github.com/eaigner/shield)- 贝叶斯文本分类器,具有灵活的分词器和存储后端. 
-   [tfgo](https://github.com/galeone/tfgo)- 易于使用的tensorflow绑定: 简化官方tensorflow去绑定的使用. 在go中定义计算图,加载并执行在python中训练过的模型. 
-   [瓦里斯](https://github.com/Xamber/Varis)-  golang神经网络. 

## 消息

_实现消息传递系统的库. _

-   [底栖生物](https://github.com/Jeffail/benthos)- 一系列协议之间的消息流媒体桥. 
-   [centrifugo](https://github.com/centrifugal/centrifugo)- 实时消息(websockets或sockjs)服务器. 
-   [DBUS](https://github.com/godbus/dbus)- 本地去d-bus绑定. 
-   [无人机线](https://github.com/appleboy/drone-line)- 发送[线](https://business.line.me/en/services/bot)使用二进制码,码头工或无人机ci的通知. 
-   [发射器](https://github.com/olebedev/emitter)- 使用go方式发出事件,使用通配符,谓词,取消可能性以及许多其他好成绩. 
-   [事件](https://github.com/agoalofalife/event)- 模式观察者的实现. 
-   [eventbus](https://github.com/asaskevich/EventBus)- 具有异步兼容性的轻量级事件总线. 
-   [gaurun客户端](https://github.com/osamingo/gaurun-client)-  gaurun客户端写入. 
-   [胶](https://github.com/desertbit/glue)- 强大的去和JavaScript套接字库(替代socket.io). 
-   [去-通知](https://github.com/TheCreeper/go-notify)- 本地实施freedesktop通知规范. 
-   [去-NSQ](https://github.com/nsqio/go-nsq)-  nsq官方包装. 
-   [go-socket.io](https://github.com/googollee/go-socket.io)-  golang的socket.io库,一个实时应用程序框架. 
-   [去-vitotrol](https://github.com/maxatome/go-vitotrol)- 客户端库到viessmann vitotrol网络服务. 
-   [咕噜](https://github.com/trivago/gollum)- 一个n: m多路复用器,用于收集来自不同来源的消息并将它们广播到一组目的地. 
-   [golongpoll](https://github.com/jcuga/golongpoll)- 使得web pub-sub变得简单的http longpoll服务器库. 
-   [鹅](https://github.com/ian-kent/goose)- 服务器发送事件. 
-   [gopush集群](https://github.com/Terry-Mao/gopush-cluster)-  gopush-cluster是一个go push服务器集群. 
-   [gorush](https://github.com/appleboy/gorush)- 使用推送通知服务器[apns2](https://github.com/sideshow/apns2)和谷歌[GCM](https://github.com/google/go-gcm). 
-   [guble](https://github.com/smancke/guble)- 使用推送通知的消息传递服务器(谷歌Firebase云消息传递,苹果推送通知服务,短信)以及WebSockets,一个休息API,具有分布式操作和消息持久性. 
-   [机械](https://github.com/RichardKnop/machinery)- 基于分布式消息传递的异步任务队列/作业队列. 
-   [芒果](https://github.com/go-mangos/mangos)- 纯运行nanomsg("可扩展协议")与运输互操作性. 
-   [旋律](https://github.com/olahol/melody)- 处理websocket会话的极简框架,包括广播和自动ping / pong处理. 
-   [messagebus](https://github.com/vardius/message-bus)-  messagebus是一个简单的异步消息总线,非常适合作为事件总线进行事件采购,cqrs,ddd. 
-   [nats去客户端](https://github.com/nats-io/nats)- 轻量级和高性能发布 - 订阅和分布式排队消息传递系统 - 这是go库. 
-   [NSQ事件总线](https://github.com/rafaeljesus/nsq-event-bus)- 围绕nsq主题和频道的一个小包装. 
-   [OPLOG](https://github.com/dailymotion/oplog)- 用于休息apis的通用oplog /复制系统. 
-   [发布订阅](https://github.com/tuxychandru/pubsub)- 简单的pubsub软件包. 
-   [rabbus](https://github.com/rafaeljesus/rabbus)- 通过amqp交换和队列的小包装. 
-   [rabtap](https://github.com/jandelgado/rabtap)-  rabbitmq瑞士军刀cli应用程序. 
-   [rapidmq](https://github.com/sybrexsys/RapidMQ)-  rapidmq是用于管理本地消息队列的轻量级可靠库. 
-   [萨拉马](https://github.com/Shopify/sarama)- 去apache kafka去图书馆. 
-   [uniqush推](https://github.com/uniqush/uniqush-push)-  redis支持将统一推送服务用于服务器端通知到移动设备. 
-   [zmq4](https://github.com/pebbe/zmq4)- 进入zeromq版本4的界面,也可用于[版本3](https://github.com/pebbe/zmq3)和[版本2](https://github.com/pebbe/zmq2). 

## 杂

_这些图书馆被放置在这里,因为其他类别似乎都不适合. _

-   [爱丽丝](https://github.com/magic003/alice)-  golang的添加剂依赖注入容器. 
-   [anagent](https://github.com/mudler/anagent)- 具有依赖注入的简约,可插拔的golang evloop / timer处理程序. 
-   [antch](https://github.com/antchfx/antch)- 一个快速,强大且可扩展的网页抓取和抓取框架. 
-   [归档](https://github.com/mholt/archiver)- 用于制作和提取.zip和.tar.gz档案的库和命令. 
-   [autoflags](https://github.com/artyom/autoflags)- 去包自动定义结构字段的命令行标志. 
-   [avgrating](https://github.com/kirillDanshin/avgRating)- 根据威尔逊评分公式计算平均得分和评分. 
-   [旗帜](https://github.com/dimiro1/banner)- 在你的应用程序中添加漂亮的横幅. 
-   [base64captcha](https://github.com/mojocn/base64Captcha)-  base64captch支持数字,数字,字母,算术,音频和数字字母验证码. 
-   [电池](https://github.com/distatus/battery)- 跨平台,标准化的电池信息库. 
-   [bitio](https://github.com/icza/bitio)- 高度优化的位级读写器. 
-   [browscap_go](https://github.com/digitalcrab/browscap_go)-  golang图书馆[浏览器功能项目](http://browscap.org/). 
-   [验证码](https://github.com/steambap/captcha)-  captcha包提供了一个易于使用,未经验证的api验证码生成. 
-   [CONV](https://github.com/cstockton/go-conv)- 套餐转换功能提供跨类型的快速直观转换. 
-   [datacounter](https://github.com/miolini/datacounter)- 去读者/作家/ http.responsewriter计数器. 
-   [错误](https://github.com/pkg/errors)- 提供简单的错误处理原语的包. 
-   [去 - 聊天机器人](https://github.com/go-chat-bot/bot)-  irc,slack&telegram bot写入. 
-   [去-commons-pool的](https://github.com/jolestar/go-commons-pool)-  golang的通用对象池. 
-   [去-multierror](https://github.com/hashicorp/go-multierror)-  go(golang)包将错误列表表示为单个错误. 
-   [去-的OpenAPI](https://github.com/go-openapi)- 收集包来解析和利用open-api模式. 
-   [去复原能力](https://github.com/eapache/go-resiliency)-  golang的弹性模式. 
-   [走,萨拉](https://github.com/oklahomer/go-sarah)- 构建所需聊天服务的机器人框架,包括线,松弛,gitter等. 
-   [去-unarr](https://github.com/gen2brain/go-unarr)-  rar,tar,zip和7z档案的解压缩库. 
-   [go.uuid](https://github.com/satori/go.uuid)- 实现通用唯一标识符(uuid). 支持创建和解析uuids. 
-   [gofakeit](https://github.com/brianvoe/gofakeit)- 随机数据生成器写入. 
-   [GOID](https://github.com/jakehl/goid)- 生成并解析符合rfc4122的v4 uuids. 
-   [gopsutil](https://github.com/shirou/gopsutil)- 用于检索进程和系统利用率(CPU,内存,磁盘等)的跨平台库. 
-   [gosms](https://github.com/haxpax/gosms)- 你自己的本地短信网关,可以用来发送短信. 
-   [gountries](https://github.com/pariz/gountries)- 公开国家和细分数据的软件包. 
-   [hanu](https://github.com/sbstjn/hanu)- 编写冗余机器人的框架. 
-   [健康](https://github.com/dimiro1/health)- 易于使用,可扩展的健康检查库. 
-   [健康检查](https://github.com/etherlabsio/healthcheck)- 为安宁的服务提供专注和并发的健康检查http处理程序. 
-   [hostutils](https://github.com/Wing924/hostutils)- 用于打包和解包fqdns列表的golang库. 
-   [靛青](https://github.com/osamingo/indigo)- 使用sonyflake并由base58编码的分布式唯一ID生成器. 
-   [工作](https://github.com/albrow/jobs)- 持久灵活的后台作业库. 
-   [LK](https://github.com/hyperboloide/lk)- 一个简单的golang授权库. 
-   [margelet](https://github.com/zhulik/margelet)- 构建电报机器人的框架. 
-   [pdfgen](https://github.com/hyperboloide/pdfgen)-  http服务从json请求生成pdf. 
-   [波斯语](https://github.com/mavihq/persian)- 一些用于波斯语的工具. 
-   [secdl](https://github.com/xor-gate/secdl)-  lighttpd modsecdownload算法移植到安全的下载URL. 
-   [shellwords](https://github.com/Wing924/shellwords)- 根据unix bourne shell的单词解析规则操作字符串的golang库. 
-   [短ID](https://github.com/teris-io/shortid)- 分布式一代超短,独特,非序列,网址友好的ID. 
-   [懒鬼](https://github.com/shomali11/slacker)- 易于使用的框架来创建闲置的机器人. 
-   [统计](https://github.com/go-playground/stats)- 监视器去memstats +系统统计信息,如内存,交换和CPU,并通过udp发送到任何你想要的日志等等...
-   [龟](https://github.com/hackebrot/turtle)-  emojis去. 
-   [UUID](https://github.com/agext/uuid)- 使用快速或密码质量的随机节点标识符生成,编码和解码uuids v1. 
-   [varhandler](https://github.com/azr/generators/tree/master/varhandler)- 生成样板http输入和输出处理. 
-   [WERR](https://github.com/txgruppi/werr)- 错误包装器为go中的错误类型创建一个包装器,它捕获文件,行和堆栈的位置. 
-   [wuid](https://github.com/edwingeng/wuid)- 一个极其快速的独特数字发生器,比uuid快10-135倍. 
-   [XKG](https://github.com/go-xkg/xkg)-  x键盘抓取器. 
-   [xstrings](https://github.com/huandu/xstrings)- 从其他语言移植的有用字符串函数的集合. 

## 自然语言处理

_用于使用人类语言的图书馆. _

-   [DPAR](https://github.com/danieldk/dpar/)- 基于转换的统计依赖分析器. 
-   [getlang](https://github.com/rylans/getlang)- 快速自然语言检测包. 
-   [去-ECO](https://github.com/ThePaw/go-eco)- 相似度,相异度和距离矩阵;多样性,公平和不平等措施;物种丰富度估计量;coenocline模型. 
-   [去,国际化](https://github.com/nicksnyder/go-i18n/)- 包和一个附带的工具来处理本地化的文本. 
-   [去-mystem](https://github.com/dveselov/mystem)-  cgo绑定到yandex.mystem  - 俄罗斯形态分析器. 
-   [去-NLP](https://github.com/nuance/go-nlp)- 用于处理离散概率分布和其他用于执行nlp工作的工具的实用程序. 
-   [去茎](https://github.com/agonopol/go-stem)- 执行porter干扰算法. 
-   [去-unidecode](https://github.com/mozillazg/go-unidecode)-  unicode文本的ascii音译. 
-   [go2vec](https://github.com/danieldk/go2vec)- 用于word2vec嵌入的阅读器和实用程序功能. 
-   [gojieba](https://github.com/yanyiwu/gojieba)- 这是一个执行[解霸](https://github.com/fxsjy/jieba)这是一个中文分词算法. 
-   [golibstemmer](https://github.com/rjohnsondev/golibstemmer)- 绑定雪球libstemmer库,包括porter 2. 
-   [gounidecode](https://github.com/fiam/gounidecode)-  unicode音译器(也称为unidecode). 
-   [GSE](https://github.com/go-ego/gse)- 进行高效的文本分割;支持英文,中文,日文等. 
-   [加护病房](https://github.com/goodsign/icu)-  cgo绑定icu4c c库检测和转换功能. 保证与版本50.1兼容. 
-   [libtextcat](https://github.com/goodsign/libtextcat)-  cgo绑定libtextcat c库. 保证与2.2版本的兼容性. 
-   [mmsego](https://github.com/awsong/MMSEGO)- 这是一个执行[mmseg](http://technology.chtsai.org/mmseg/)这是一个中文分词算法. 
-   [NLP](https://github.com/Shixzie/nlp)- 从字符串中提取值并用nlp填充结构. 
-   [NLP](https://github.com/james-bowman/nlp)- 去自然语言处理库支持lsa(潜在语义分析). 
-   [paicehusk](https://github.com/rookii/paicehusk)-  golang实现的骰子/果壳干扰算法. 
-   [彼得罗维奇](https://github.com/striker2000/petrovich)- 彼得罗维奇是一个使俄罗斯名字在特定语法情况下发挥作用的图书馆. 
-   [搬运工](https://github.com/a2800276/porter)- 这是一个非常简单的港口马丁波特的实施波特干扰算法. 
-   [porter2](https://github.com/zhenjl/porter2)- 非常快速的porter 2 stemmer. 
-   [散文](https://github.com/jdkato/prose)- 支持标记化,词性标注,命名实体提取等的文本处理库. 
-   [rake.go](https://github.com/Obaied/RAKE.go)- 进入快速自动关键字提取算法(rake)的端口. 
-   [分割](https://github.com/blevesearch/segment)- 去图书馆进行unicode文本分割,如中所述[unicode标准附件#29](http://www.unicode.org/reports/tr29/)
-   [句子](https://github.com/neurosnap/sentences)- 句子标记器: 将文本转换为句子列表. 
-   [shamoji](https://github.com/osamingo/shamoji)-  shamoji是用go编写的文字过滤软件包. 
-   [雪球](https://github.com/goodsign/snowball)- 雪球stemmer端口(cgo包装)去. 提供词干提取功能[雪球原生](http://snowball.tartarus.org/). 
-   [词干](https://github.com/dchest/stemmer)- 用于go编程语言的stemmer包. 包括英文和德文词干. 
-   [textcat](https://github.com/pebbe/textcat)- 开发基于n-gram的文本分类包,支持utf-8和原始文本. 
-   [whatlanggo](https://github.com/abadojack/whatlanggo)- 去自然语言检测包. 支持84种语言和24种脚本(写作系统,例如拉丁文,西里尔文等). 
-   [什么时候](https://github.com/olebedev/when)- 自然en和ru语言日期/时间分析器与可插拔规则. 

## 联网

_用于与网络的各个层一起工作的库. _

-   [地址解析协议](https://github.com/mdlayher/arp)- 软件包arp实现arp协议,如rfc 826中所述. 
-   [buffstreams](https://github.com/stabbycutyou/buffstreams)- 通过TCP流式传输协议缓冲数据变得简单. 
-   [老人星](https://github.com/zubairhamed/canopus)- 客户端/服务器实现(rfc 7252). 
-   [cidranger](https://github.com/yl2chen/cidranger)- 快速ip到cidr查找去. 
-   [DHCP6](https://github.com/mdlayher/dhcp6)- 软件包dhcp6实现了dhcpv6服务器,如rfc 3315中所述. 
-   [DNS](https://github.com/miekg/dns)- 去图书馆工作与DNS. 
-   [醚](https://github.com/songgao/ether)- 跨平台去发送和接收以太网帧. 
-   [以太网络](https://github.com/mdlayher/ethernet)- 封装以太网实现ieee 802.3 ethernet ii帧和ieee 802.1q vlan标签的封送和解组. 
-   [fasthttp](https://github.com/valyala/fasthttp)- 封装fasthttp是一个快速的http实现,比net / http快10倍. 
-   [fortio](https://github.com/istio/fortio)- 加载测试库和命令行工具以及web ui. 允许指定每秒设置的查询负载并记录延迟直方图和其他有用的统计信息并绘制它们. 
-   [FTP](https://github.com/jlaffaye/ftp)- 软件包的ftp实现了一个ftp客户端的描述[rfc 959](http://tools.ietf.org/html/rfc959). 
-   [拼命三郎](https://github.com/hashicorp/go-getter)- 去图书馆使用网址从各种来源下载文件或目录. 
-   [去,眩晕](https://github.com/ccding/go-stun)- 执行stun客户端(rfc 3489和rfc 5389). 
-   [gobgp](https://github.com/osrg/gobgp)- 在go编程语言中实现的bgp. 
-   [golibwireshark](https://github.com/sunwxg/golibwireshark)- 包golibwireshark使用libwireshark库来解码pcap文件并分析解剖数据. 
-   [gopacket](https://github.com/google/gopacket)- 使用libpcap绑定进入数据包处理库. 
-   [gopcap](https://github.com/akrennmair/gopcap)- 去libpcap包装. 
-   [goshark](https://github.com/sunwxg/goshark)- 包goshark使用tshark解码ip包并创建数据结构来分析包. 
-   [gosnmp](https://github.com/soniah/gosnmp)- 用于执行snmp操作的本机去库. 
-   [gotcp](https://github.com/gansidui/gotcp)- 去编写快速编写tcp应用程序的软件包. 
-   [抓](https://github.com/cavaliercoder/grab)- 去包管理文件下载. 
-   [graval](https://github.com/koofr/graval)- 实验性的ftp服务器框架. 
-   [jazigo](https://github.com/udhos/jazigo)-  jazigo是一款用于检索多个网络设备配置的工具. 
-   [KCP-去](https://github.com/xtaci/kcp-go)-  kcp  - 快速可靠的arq协议. 
-   [kcptun](https://github.com/xtaci/kcptun)- 基于kcp协议的非常简单和快速的udp隧道. 
-   [lhttp](https://github.com/fanux/lhttp)- 强大的websocket框架,更轻松地构建您的im服务器. 
-   [linkio](https://github.com/ian-kent/linkio)- 读写器接口的网络链路速度模拟. 
-   [LLB](https://github.com/kirillDanshin/llb)- 这是一个非常简单但快速的代理服务器后端. 可以用于快速重定向到预定义域,具有零内存分配和快速响应. 
-   [MDNS](https://github.com/hashicorp/mdns)-  golang中的简单mdns(多播DNS)客户端/服务器库. 
-   [mqttpaho](https://eclipse.org/paho/clients/golang/)-  paho go客户端提供一个mqtt客户端库,通过tcp,tls或websockets连接到mqtt brokers. 
-   [端口代理](https://github.com/aybabtme/portproxy)- 简单的tcp代理,将cors支持添加到不支持它的api. 
-   [publicip](https://github.com/polera/publicip)- 封装发布返回你的公共面临的IPV4地址(互联网出口). 
-   [生的](https://github.com/mdlayher/raw)-  package raw可以在设备驱动程序级别为网络接口读取和写入数据. 
-   [SFTP](https://github.com/pkg/sftp)- 软件包sftp执行ssh文件传输协议,如上所述<https://filezilla-project.org/specs/draft-ietf-secsh-filexfer-02.txt>. 
-   [SSH](https://github.com/gliderlabs/ssh)- 构建ssh服务器的更高级api(包装加密/ ssh). 
-   [sslb](https://github.com/eduardonunesp/sslb)- 这是一个超级简单的负载均衡器,只是一个实现某种性能的小项目. 
-   [击晕](https://github.com/go-rtc/stun)- 执行rfc 5389 stun协议. 
-   [tcp_server](https://github.com/firstrow/tcp_server)- 更快建立tcp服务器库. 
-   [UTP](https://github.com/anacrolix/utp)- 走utp微传输协议实现. 
-   [水](https://github.com/songgao/water)- 简单的tun / tap库. 
-   [WinRM的](https://github.com/masterzen/winrm)- 去winrm客户端远程执行Windows机器上的命令. 
-   [xtcp](https://github.com/xfxdev/xtcp)- 同步全双工通信的tcp服务器框架,正常关机,自定义协议. 
-   [yannff](https://github.com/intel-go/yanff)- 快速开发云和裸机高性能网络功能的框架. 

## OpenGL的

_用于使用opengl的库. _

-   [GL](https://github.com/go-gl/gl)- 去绑定opengl(通过发光生成). 
-   [GLFW](https://github.com/go-gl/glfw)- 去glfw 3绑定. 
-   [goxjs / GL](https://github.com/goxjs/gl)- 跨平台的opengl绑定(os x,linux,windows,browsers,ios,android). 
-   [goxjs / GLFW](https://github.com/goxjs/glfw)- 去跨平台的glfw库创建一个opengl上下文并接收事件. 
-   [mathgl](https://github.com/go-gl/mathgl)- 来自glm的灵感,专门用于3d数学的纯数学包. 

## ORM

_实现对象关系映射或数据映射技术的库. _

-   [beego orm](https://github.com/astaxie/beego/tree/master/orm)- 强大的orm框架. 支持: pq / mysql / sqlite3. 
-   [去-PG](https://github.com/go-pg/pg)-  postgresql orm,重点介绍postgresql特有的功能和性能. 
-   [去-查询集](https://github.com/jirfag/go-queryset)-  100%类型安全的ORM代码生成和mysql,postgresql,sqlite3,基于gorm的sql server支持. 
-   [去-sqlbuilder](https://github.com/huandu/go-sqlbuilder)- 一个灵活而强大的SQL字符串生成器库和一个零配置ORM. 
-   [去商店](https://github.com/gosuri/go-store)- 简单快速的redis支持的键值存储库. 
-   [gomodel](https://github.com/cosiner/gomodel)- 轻量级,快速的orm类库帮助与数据库交互. 
-   [GORM](https://github.com/jinzhu/gorm)-  golang的梦幻般的orm库旨在成为开发者友好的. 
-   [GORP](https://github.com/go-gorp/gorp)- 去关系持久化,orm-ish库去. 
-   [知识](https://github.com/abrahambotros/lore)- 简单轻量级的伪Orm /伪结构映射环境. 
-   [马洛](https://github.com/dadleyy/marlow)- 从项目结构生成的orm用于编译时安全保证. 
-   [流行/汽水](https://github.com/markbates/pop)- 数据库迁移,创建,orm等...用于mysql,postgresql和sqlite. 
-   [QBS](https://github.com/coocood/qbs)- 代表由struct查询. 去吧. 
-   [改革](https://github.com/go-reform/reform)- 基于非空接口和代码生成,更好的运行. 
-   [sqlboiler](https://github.com/volatiletech/sqlboiler)-  orm生成器. 根据您的数据库模式生成一个有特色的,超快速的orm. 
-   [upper.io/db](https://github.com/upper/db)- 通过使用包装成熟的数据库驱动程序的适配器,与不同的数据源进行交互的单一界面. 
-   [XORM](https://github.com/go-xorm/xorm)- 简单而强大的orm for go. 
-   [放大](https://github.com/albrow/zoom)- 基于redis构建的超快数据存储和查询引擎. 

## 包管理

_包和依赖管理库. _

-   [DEP](https://github.com/golang/dep)- 去依赖工具. 
-   [GIGO](https://github.com/LyricalSecurity/gigo)-  golang的像pip一样的依赖工具,支持私有存储库和哈希. 
-   [滑行](https://github.com/Masterminds/glide)- 轻松管理你的golang供应商和商品包. 受到诸如maven,bundler和pip等工具的启发. 
-   [godep](https://github.com/tools/godep)- 去依赖工具,godep通过修复它们的依赖关系帮助可重复地构建包. 
-   [GOM](https://github.com/mattn/gom)- 去经理 - 去捆绑. 
-   [GOOP](https://github.com/nitrous-io/goop)-  go的简单依赖管理器(golang),受bundler启发. 
-   [GOP](https://github.com/lunny/gop)- 用gopath构建和管理你的应用程序
-   [gopm](https://github.com/gpmgo/gopm)- 去包管理器. 
-   [govendor](https://github.com/kardianos/govendor)- 去包管理器. 转到与标准供应商文件配合使用的供应商工具. 
-   [GPM](https://github.com/pote/gpm)- 准系统依赖管理器. 
-   [GVT](https://github.com/FiloSottile/gvt)-`GVT`是一种简单的销售工具,用于基于全球供应商的本地交易(又名go15vendorexperiment). 
-   [约翰尼DEPS](https://github.com/VividCortex/johnny-deps)- 使用git的最小依赖版本. 
-   [坚果](https://github.com/jingweno/nut)- 供应商依赖关系. 
-   [vengo](https://github.com/DamnWidget/VenGO)- 创建和管理可导出的隔离虚拟环境. 

## 查询语言

-   [graphql](https://github.com/tmc/graphql)-  graphql解析器+实用程序. 
-   [graphql](https://github.com/sevki/graphql)-  go中的graphql实现. 
-   [graphql](https://github.com/neelance/graphql-go)- 关注易用性的graphql服务器. 
-   [graphql,去](https://github.com/graphql-go/graphql)- 执行graphql for go. 
-   [jsonql](https://github.com/elgs/jsonql)-  golang中的json查询表达式库. 

## 资源嵌入

-   [退出](https://github.com/mjibson/esc)- 将文件嵌入到go程序中并为它们提供http.filesystem接口. 
-   [fileb0x](https://github.com/UnnoTed/fileb0x)- 嵌入文件的简单工具,重点放在"自定义"和易用性上. 
-   [去嵌](https://github.com/pyros2097/go-embed)- 生成代码将资源文件嵌入到您的库或可执行文件中. 
-   [走资源](https://github.com/omeid/go-resources)- 与go一起嵌入的不良资源. 
-   [go.rice](https://github.com/GeertJohan/go.rice)-  go.rice是一个可以轻松处理资源(如html,js,css,图像和模板)的软件包. 
-   [packr](https://github.com/gobuffalo/packr)- 将静态文件嵌入到二进制文件中的简单而简单的方法. 
-   [静力学](https://github.com/go-playground/statics)- 将静态资源嵌入到单个二进制编译的go文件中+使用http.filesystem +符号链接. 
-   [statik](https://github.com/rakyll/statik)- 将静态文件嵌入到可执行文件中. 
-   [templify](https://github.com/wlbr/templify)- 将外部模板文件嵌入到代码中以创建单个文件二进制文件. 
-   [vfsgen](https://github.com/shurcooL/vfsgen)- 生成一个静态实现给定虚拟文件系统的vfsdata.go文件. 

## 科学和数据分析

_用于科学计算和数据分析的库. _

-   [布拉斯](https://github.com/ziutek/blas)- 实现blas(基本线性代数子程序). 
-   [图表](https://github.com/vdobler/chart)- 简单的图表绘图库. 支持多种图形类型. 
-   [evaler](https://github.com/soniah/evaler)- 简单的浮点算术表达式计算器. 
-   [EWMA](https://github.com/VividCortex/ewma)- 指数加权移动平均值. 
-   [GEOM](https://github.com/skelterjohn/geom)-  golang的2D几何图形. 
-   [去-DSP](https://github.com/mjibson/go-dsp)- 数字信号处理. 
-   [去-FN](https://github.com/ematvey/go-fn)- 用go语言编写的数学函数,不包含在数学pkg中. 
-   [去-GT](https://github.com/ThePaw/go-gt)- 用"go"语言编写的图论算法. 
-   [go.matrix](https://github.com/skelterjohn/go.matrix)-  go的线性代数(已停滞). 
-   [gocomplex](https://github.com/varver/gocomplex)-  go编程语言的复杂数字库. 
-   [goent](https://github.com/kzahedi/goent)- 执行熵度量
-   [gofrac](https://github.com/anschelsc/gofrac)- (可安装)分数库,支持基本算术. 
-   [gohistogram](https://github.com/VividCortex/gohistogram)- 数据流的近似直方图. 
-   [gonum / mat64](https://github.com/gonum/matrix)- 矩阵计算的通用包. mat64包为float64矩阵提供了基本的线性代数运算. 
-   [gonum /剧情](https://github.com/gonum/plot)-  gonum / plot提供了一个用于构建和绘制阴谋的API. 
-   [goraph](https://github.com/gyuho/goraph)- 纯走图理论库(数据结构,算法可视化). 
-   [斯里兰卡政府](https://github.com/cpmech/gosl)- 去线性代数,fft,几何,nurbs,数值方法,概率,优化,微分方程等科学图书馆. 
-   [gostat](https://github.com/ematvey/gostat)-  go语言的统计库. 
-   [图形](https://github.com/yourbasic/graph)- 基本图算法库. 
-   [颂](https://github.com/ChristopherRabotin/ode)- 支持扩展状态和基于通道的迭代停止条件的常微分方程(ode)求解器. 
-   [ORB](https://github.com/paulmach/orb)-  2D裁剪,geojson和mapbox矢量图片支持. 
-   [网页排名](https://github.com/alixaxel/pagerank)- 在go中实现加权的pagerank算法. 
-   [pihex](https://github.com/claygod/PiHex)- 对十六进制数pi执行"bailey-borwein-plouffe"算法. 
-   [疏](https://github.com/james-bowman/sparse)- 用于支持科学和机器学习应用的线性代数的稀疏矩阵格式,与gonum矩阵库兼容. 
-   [统计](https://github.com/montanaflynn/stats)-  golang标准库中缺少常用函数的统计信息包. 
-   [streamtools](https://github.com/nytlabs/streamtools)- 用于处理数据流的通用图形工具. 
-   [textrank](https://github.com/DavidBelicza/TextRank)- 具有可扩展特性(汇总,加权,短语提取)和多线程(goroutine)支持的golang中的textrank实现. 
-   [vectormath](https://github.com/spate/vectormath)-  vectormath for go,适用于sony的矢量数学库中的标量c函数,如bullet-2.79源代码(当前无效)所示. 

## 安全

_用于帮助您的应用程序更安全的库. _

-   [acmetool](https://github.com/hlandau/acme)- 用自动更新的acme(让我们加密)客户端工具. 
-   [argon2pw](https://github.com/raja/argon2pw)- 使用恒定时间密码比较生成argon2密码哈希值. 
-   [autocert](https://godoc.org/golang.org/x/crypto/acme/autocert)- 自动提供让我们加密证书并启动一个tls服务器. 
-   [badactor](https://github.com/jaredfolkins/badactor)- 以fail2ban的精神构建的内存中,应用驱动的jailer. 
-   [cameradar](https://github.com/Ullaakut/cameradar)- 工具和库,用于远程监控监控摄像机的rtsp流. 
-   [去-亚拉](https://github.com/hillu/go-yara)- 去绑定[亚拉](https://github.com/plusvic/yara),"针对恶意软件研究人员(和其他人)的模式匹配瑞士刀". 
-   [gosecretboxpassword](https://github.com/dwin/goSecretBoxPassword)- 一个可能安全散列和加密密码的偏执包. 
-   [乐高](https://github.com/xenolf/lego)- 纯粹的acme客户端库和cli工具(用于让我们加密). 
-   [memguard](https://github.com/awnumar/memguard)- 用于处理内存中敏感值的纯粹库. 
-   [氯化钠](https://github.com/kevinburke/nacl)- 执行nacl的api集. 
-   [passlib](https://github.com/hlandau/passlib)-  futureproof密码哈希库. 
-   [安全](https://github.com/unrolled/secure)-  http中间件,便于快速获得安全性. 
-   [简单scrypt](https://github.com/elithrar/simple-scrypt)-  scrypt软件包内置简单明了的api和自动成本校准. 
-   [SSH-拱顶](https://github.com/ssh-vault/ssh-vault)- 使用ssh密钥进行加密/解密. 

## 系列化

_用于二进制序列化的库和工具. _

-   [ASN1](https://github.com/PromonLogicalis/asn1)-  golang的asn.1 ber和der编码库. 
-   [巴姆巴姆](https://github.com/glycerine/bambam)- 来自go的cap'n proto模式的生成器. 
-   [高富华](https://github.com/pascaldekloe/colfer)-  colfer二进制格式的代码生成. 
-   [csvutil](https://github.com/jszwec/csvutil)- 高性能,惯用的csv记录编码和解码到原生去结构. 
-   [fwencoder](https://github.com/o1egl/fwencoder)- 固定宽度的文件解析器(编码和解码库). 
-   [去-capnproto](https://github.com/glycerine/go-capnproto)-  cap'n proto库和解析器. 
-   [去编解码器](https://github.com/ugorji/go)- 针对msgpack,cbor和json的高性能,功能丰富,惯用的编码,解码和rpc库,支持基于运行时或代码生成. 
-   [gogoprotobuf](https://github.com/gogo/protobuf)- 与小工具一起使用的协议缓冲区. 
-   [goprotobuf](https://github.com/golang/protobuf)- 以Google协议缓冲区的形式使用库和协议编译器插件的形式. 
-   [jsoniter](https://github.com/json-iterator/go)- 高性能100%兼容的"编码/ json"替代品. 
-   [mapstructure](https://github.com/mitchellh/mapstructure)- 去图书馆解码通用地图值到本地去结构. 
-   [php_session_decoder](https://github.com/yvasiyarov/php_session_decoder)-  golang库,用于处理php会话格式和php序列化/反序列化功能. 
-   [structomap](https://github.com/tuvistavie/structomap)- 通过静态结构轻松动态地生成地图. 
-   [结构](https://github.com/fatih/structs)- 支持将结构转换为地图,将键/值结构化为片的库等等. 

## 服务器应用

-   [阿尔杰农](https://github.com/xyproto/algernon)- 内置支持lua,markdown,gcss和琥珀色的http / 2 web服务器. 
-   [球童](https://github.com/mholt/caddy)-  caddy是一个易于配置和使用的替代方案,http / 2网络服务器. 
-   [领事](https://www.consul.io/)-  consul是服务发现,监控和配置的工具. 
-   [DEVD](https://github.com/cortesi/devd)- 开发人员的本地网络服务器. 
-   [ETCD](https://github.com/coreos/etcd)- 用于共享配置和服务发现的高可用密钥值存储. 
-   [FIDER](https://github.com/getfider/fider)-  fider是一个收集和组织客户反馈的开放平台. 
-   [狐狼](https://github.com/ortuman/jackal)- 一个用go编写的xmpp服务器. 
-   [minio](https://github.com/minio/minio)-  minio是一个分布式对象存储服务器. 
-   [NSQ](http://nsq.io/)- 一个实时分布式消息传递平台. 
-   [yakvs](https://github.com/sci4me/yakvs)- 小型联网内存键值存储. 

## 模板引擎

_图书馆和工具模板和lexing. _

-   [高手](https://github.com/yosssi/ace)-  ace是一个html模板引擎,受到苗条和玉石的启发. 王牌是黄金的一种改良. 
-   [琥珀色](https://github.com/eknkc/amber)- 琥珀是一款优雅的模板编辑引擎,适合编程语言,灵感来自haml和jade. 
-   [闺女](https://github.com/dskinner/damsel)- 标记语言,通过CSS选择器提供html大纲,通过pkg html / template和其他扩展. 
-   [自我](https://github.com/benbjohnson/ego)- 轻量级模板语言,可以让你编写模板. 模板被翻译成去和编译. 
-   [fasttemplate](https://github.com/valyala/fasttemplate)- 简单快速的模板引擎. 将模板占位符替换为速度的10倍[文/模板](http://golang.org/pkg/text/template/). 
-   [gofpdf](https://github.com/jung-kurt/gofpdf)-  pdf文档生成器,对文本,绘图和图像提供高级支持. 
-   [grender](https://github.com/dannyvankooten/grender)- 用于支持扩展其他模板文件的基于文件模板的html / template的小包装. 
-   [英雄](https://github.com/shiyanhui/hero)- 英雄是一个方便,快速和强大的去模板引擎. 
-   [喷射](https://github.com/CloudyKit/jet)- 喷气模板引擎. 
-   [kasia.go](https://github.com/ziutek/kasia.go)-  HTML和其他文本文档的模板系统 - 执行. 
-   [液体](https://github.com/osteele/liquid)- 去实施shopify液体模板. 
-   [胡子](https://github.com/hoisie/mustache)- 执行小胡子模板语言. 
-   [pongo2](https://github.com/flosch/pongo2)- 类似Django的模板引擎. 
-   [quicktemplate](https://github.com/valyala/quicktemplate)- 快速,功能强大且易于使用的模板引擎. 将模板转换为去代码然后编译它. 
-   [雷蒙德](https://github.com/aymerick/raymond)- 完整的车把实施. 
-   [剃刀](https://github.com/sipin/gorazor)-  golang的剃须刀视图引擎. 
-   [黄豆](https://github.com/robfig/soy)- 关闭模板(又名大豆模板),继续[官方规格](https://developers.google.com/closure/templates/). 
-   [丝绒](https://github.com/gobuffalo/velvet)- 完整的车把实施. 

## 测试

_用于测试代码库并生成测试数据的库. _

-   测试框架

    -   [断言](https://github.com/go-playground/assert)- 基本断言库与本地进行测试一起使用,用于定制断言的构建块. 
    -   [badio](https://github.com/cavaliercoder/badio)- 扩展去`测试/ iotest`包. 
    -   [baloo](https://github.com/h2non/baloo)- 易于表达的多功能端到端http api测试变得简单. 
    -   [BRO](https://github.com/marioidival/bro)- 观察目录中的文件并为其运行测试. 
    -   [cupaloy](https://github.com/bradleyjkemp/cupaloy)- 为您的测试框架提供简单的快照测试插件. 
    -   [dbcleaner](https://github.com/khaiql/dbcleaner)- 用于测试目的的清洁数据库,受到启发`database_cleaner`在红宝石. 
    -   [dsunit](https://github.com/viant/dsunit)- 数据存储测试sql,nosql,结构化文件. 
    -   [endly](https://github.com/viant/endly)- 声明式的端到端功能测试. 
    -   [弗里斯比](https://github.com/verdverm/frisby)- 休息api测试框架. 
    -   [银杏](http://onsi.github.io/ginkgo/)-  bdd测试框架. 
    -   [走红毯](https://github.com/msoap/go-carpet)- 在终端上查看测试覆盖的工具. 
    -   [去-mutesting](https://github.com/zimmski/go-mutesting)- 对源代码进行变异测试. 
    -   [去-VCR](https://github.com/dnaeon/go-vcr)- 记录并重播您的http互动,以进行快速,确定性和准确的测试. 
    -   [小妖精](https://github.com/franela/goblin)- 像摩卡一样的测试框架去. 
    -   [gocheck](http://labix.org/gocheck)- 更高级的测试框架替代gotest. 
    -   [goconvey](https://github.com/smartystreets/goconvey/)- 带有web ui和live reload的bdd风格框架. 
    -   [gocrest](https://github.com/corbym/gocrest)- 可组合的类似hamcrest的匹配器用于进行断言. 
    -   [godog](https://github.com/DATA-DOG/godog)- 黄瓜或behat像bdd框架去. 
    -   [gofight](https://github.com/appleboy/gofight)-  golang路由器框架的api处理程序测试. 
    -   [gogiven](https://github.com/corbym/gogiven)-  yatspec样的bdd测试框架. 
    -   [gomega](http://onsi.github.io/gomega/)-  rspec像匹配器/断言库. 
    -   [gospec](https://github.com/orfjackal/gospec)-  go编程语言的bdd式测试框架. 
    -   [gospecify](https://github.com/stesla/gospecify)- 这提供了一个bdd语法来测试你的代码. 任何使用rspec等库的人都应该很熟悉. 
    -   [gosuite](https://github.com/pavlo/gosuite)- 带有设置/拆卸设施的轻量级测试套件`测试`通过利用go1.7的分测试. 
    -   [hamcrest](https://github.com/rdrdr/hamcrest)- 声明性匹配对象的流畅框架,当应用于输入值时,产生自描述结果. 
    -   [httpexpect](https://github.com/gavv/httpexpect)- 简洁,声明性和易于使用的端到端http和其他api测试. 
    -   [restit](https://github.com/yookoala/restit)- 去微观框架,以帮助编写宁静的API集成测试. 
    -   [testfixtures](https://github.com/go-testfixtures/testfixtures)- 用于测试数据库应用程序的测试夹具的助手. 
    -   [作证](https://github.com/stretchr/testify)- 标准测试包的神圣延伸. 
    -   [wstest](https://github.com/posener/wstest)-  websocket客户端用于单元测试websocket http.handler. 

-   嘲笑

    -   [伪造](https://github.com/maxbrunsfeld/counterfeiter)- 用于生成独立模拟对象的工具. 
    -   [去-sqlmock](https://github.com/DATA-DOG/go-sqlmock)- 用于测试数据库交互的模拟sql驱动程序. 
    -   [去-TXDB](https://github.com/DATA-DOG/go-txdb)- 主要用于测试目的的基于单个事务的数据库驱动
    -   [gock](https://github.com/h2non/gock)- 多功能http嘲笑变得容易. 
    -   [gomock](https://github.com/golang/mock)- 为编程语言嘲笑框架. 
    -   [govcr](https://github.com/seborama/govcr)-  golang的http模拟: 记录和重放http交互以进行离线测试. 
    -   [minimock](https://github.com/gojuno/minimock)- 模拟发生器去接口. 
    -   [mockhttp](https://github.com/tv42/mockhttp)- 模拟对象去http.responsewriter. 

-   模糊和增量调试/缩小/缩小. 

    -   [去,模糊](https://github.com/dvyukov/go-fuzz)- 随机测试系统. 
    -   [gofuzz](https://github.com/google/gofuzz)- 用于填充随机值的库. 
    -   [塔沃尔](https://github.com/zimmski/tavor)- 通用的模糊和增量调试框架. 

-   硒和浏览器控制工具. 
    -   [CDP](https://github.com/mafredri/cdp)- 用于Chrome调试协议的类型安全绑定,可用于浏览器或实现它的其他调试目标. 
    -   [chromedp](https://github.com/knq/chromedp)- 驱动/测试Chrome,safari,edge,android webviews和其他支持chrome调试协议的浏览器的一种方法. 
    -   [GGR](https://github.com/aerokube/ggr)- 一个轻量级的服务器,可以将多个selenium集线器的selenium wedriver请求路由并代理. 
    -   [selenoid](https://github.com/aandryashin/selenoid)- 在容器内启动浏览器的替代硒中枢服务器. 

## 文字处理

_用于解析和处理文本的库. _

-   具体格式
    -   [对齐](https://github.com/Guitarbum722/align)- 一个对齐文本的通用应用程序. 
    -   [分配](https://github.com/sbstjn/allot)-  cli工具和机器人的占位符和通配符文本解析. 
    -   [bbconvert](https://github.com/CalebQ42/bbConvert)- 将bbcode转换为html,使您可以添加对自定义bbcode标记的支持. 
    -   [黑色星期五](https://github.com/russross/blackfriday)- 降价处理器. 
    -   [忧愁星期一](https://github.com/microcosm-cc/bluemonday)- 卫生洗手液. 
    -   [colly](https://github.com/asciimoo/colly)- 快速和优雅的地鼠抓取框架
    -   [commonregex](https://github.com/mingrammer/commonregex)-  go的常用正则表达式的集合
    -   [DOI](https://github.com/hscells/doi)-  go中的文档对象标识符(doi)解析器. 
    -   [editorconfig核心,走](https://github.com/editorconfig/editorconfig-core-go)-  editorconfig文件解析器和操纵器. 
    -   [ENCA](https://github.com/endeveit/enca)- 最小的cgo绑定[libenca](http://cihar.com/software/enca/). 
    -   [GENEX](https://github.com/alixaxel/genex)- 计数并将正则表达式扩展为所有匹配的字符串. 
    -   [github_flavored_markdown](https://godoc.org/github.com/shurcooL/github_flavored_markdown)-  Github风格降价渲染器(使用blackfriday),带围栏代码块突出显示,可点击的标题锚点链接. 
    -   [去,固定宽度](https://github.com/ianlopshire/go-fixedwidth)- 固定宽度的文本格式(带反射的编码器/解码器). 
    -   [走,人性化](https://github.com/dustin/go-humanize)- 将时间,数字和内存大小的格式化程序转换为可读格式. 
    -   [去-NMEA](https://github.com/adrianmo/go-nmea)- 去语言的nmea解析器库. 
    -   [去-runewidth](https://github.com/mattn/go-runewidth)- 用于获取字符或字符串的固定宽度. 
    -   [去-slugify](https://github.com/mozillazg/go-slugify)- 用多种语言支持制作漂亮的slu slu. 
    -   [去-电子名片](https://github.com/emersion/go-vcard)- 解析和格式化vcard. 
    -   [gofeed](https://github.com/mmcdole/gofeed)- 解析RSS和原子饲料. 
    -   [gographviz](https://github.com/awalterschulze/gographviz)- 解析graphviz点语言. 
    -   [gommon /字节](https://github.com/labstack/gommon/tree/master/bytes)- 将字节格式化为字符串. 
    -   [gonameparts](https://github.com/polera/gonameparts)- 将人名解析为单个名称部分. 
    -   [GOQ](https://github.com/andrewstuart/goq)- 使用带有jQuery语法的结构标记的html声明性解组(使用goquery). 
    -   [goquery](https://github.com/PuerkitoBio/goquery)-  goquery带来了一种类似于jquery的语法和一组功能. 
    -   [goregen](https://github.com/zach-klippenstein/goregen)- 用于从正则表达式生成随机字符串的库. 
    -   [gotext](https://github.com/leonelquinteros/gotext)-  gnu gettext实用程序. 
    -   [guesslanguage](https://github.com/endeveit/guesslanguage)- 用于确定unicode文本的自然语言. 
    -   [注入](https://github.com/facebookgo/inject)- 包装注射提供了基于反射的注射器. 
    -   [MXJ](https://github.com/clbanning/mxj)- 将xml编码/解码为json或map[串]接口{};用点符号路径和通配符提取值. 取代x2j和j2x软件包. 
    -   [SH](https://github.com/mvdan/sh)-  shell解析器和格式化程序. 
    -   [金属块](https://github.com/gosimple/slug)- 网址友好slugify与多语言支持. 
    -   [slugify](https://github.com/avelino/slugify)- 去slugify处理字符串的应用程序. 
    -   [syndfeed](https://github.com/zhengchun/syndfeed)- 原子1.0和rss 2.0的联合提要. 
    -   [toml](https://github.com/BurntSushi/toml)-  toml配置格式(带反射的编码器/解码器). 
-   效用
    -   [gotabulate](https://github.com/bndr/gotabulate)- 轻松漂亮 - 打印您的表格数据. 
    -   [KACE](https://github.com/codemodus/kace)- 常见案例转换,涵盖常见的初始化. 
    -   [parseargs,去](https://github.com/nproc/parseargs-go)- 理解引号和反斜杠的字符串参数解析器. 
    -   [PARTH](https://github.com/codemodus/parth)-  url路径分段解析. 
    -   [基数](https://github.com/yourbasic/radix)- 快速的字符串排序算法. 
    -   [xj2go](https://github.com/stackerzzq/xj2go)- 转换XML或JSON去结构. 
    -   [xurls](https://github.com/mvdan/xurls)- 从文本中提取网址. 

## 第三方apis

_用于访问第三方apis的库. _

-   [亚马逊产品广告的API](https://github.com/ngs/go-amazon-product-advertising-api)- 去客户端库[亚马逊产品广告api](https://affiliate-program.amazon.com/gp/advertising/api/detail/main.html). 
-   [森蚺](https://github.com/ChimeraCoder/anaconda)- 去twitter 1.1 api的客户端库. 
-   [AWS-SDK-去](https://github.com/aws/aws-sdk-go)-  go编程语言的官方aws sdk. 
-   [brewerydb](https://github.com/naegelejd/brewerydb)- 去图书馆进入brewerydb api. 
-   [纯情](https://github.com/andygrunwald/cachet)- 去客户端库[cachet(开源状态页面系统)](https://cachethq.io/). 
-   [circleci](https://github.com/jszwedko/go-circleci)- 去客户端库与circleci的api进行交互. 
-   [clarifai](https://github.com/samuelcouch/clarifai)- 去客户端库与Clarifai API进行交互. 
-   [codeship,去](https://github.com/codeship/codeship-go)- 去客户端库与codeship的API v2进行交互. 
-   [discordgo](https://github.com/bwmarrin/discordgo)- 为不一致的聊天API绑定. 
-   [ethrpc](https://github.com/onrik/ethrpc)- 去绑定ethereum json rpc api. 
-   [Facebook的](https://github.com/huandu/facebook)- 去支持facebook图表api的库. 
-   [FCM](https://github.com/maddevsio/fcm)- 去图书馆进行Firebase云消息传递. 
-   [GADS](https://github.com/emiddleton/gads)- 谷歌adwords非官方api. 
-   [加米](https://github.com/bit4bit/gami)- 去库的星号管理界面. 
-   [GCM](https://github.com/Aorioli/gcm)- 去谷歌云消息库. 
-   [地理golang](https://github.com/codingsince1985/geo-golang)- 去图书馆进入[谷歌地图](https://developers.google.com/maps/documentation/geocoding/intro),[Mapquest服务](http://open.mapquestapi.com/geocoding/),[nominatim](http://open.mapquestapi.com/nominatim/),[opencage](http://geocoder.opencagedata.com/api.html),[这里](https://developer.here.com/rest-apis/documentation/geocoder),[兵](https://msdn.microsoft.com/en-us/library/ff701715.aspx),[mapbox](https://www.mapbox.com/developers/api/geocoding/),和[OpenStreetMap的](https://wiki.openstreetmap.org/wiki/Nominatim)地理编码/反向地理编码apis. 
-   [github上](https://github.com/google/go-github)- 去库访问github rest api v3. 
-   [githubql](https://github.com/shurcooL/githubql)- 去图书馆访问github graphql api v4. 
-   [去,克罗诺斯](https://github.com/axelspringer/go-chronos)- 去图书馆进行互动[克罗诺斯](https://mesos.github.io/chronos/)作业调度程序
-   [去-hacknews](https://github.com/PaulRosset/go-hacknews)- 为hackernews api提供小客户端. 
-   [去-imgur](https://github.com/koffeinsource/go-imgur)- 去客户端库[imgur](https://imgur.com)
-   [去-JIRA](https://github.com/andygrunwald/go-jira)- 去客户端库[阿拉西亚杰拉](https://www.atlassian.com/software/jira)
-   [走马拉松](https://github.com/gambol99/go-marathon)- 去图书馆与中间层的马拉松比赛互动. 
-   [去-myanimelist](https://github.com/nstratos/go-myanimelist)- 去客户端库访问[myanimelist api](http://myanimelist.net/modules.php?go=api). 
-   [去-sptrans](https://github.com/sergioaugrod/go-sptrans)- 去sptrans olho vivo api的客户端库. 
-   [去-电报](https://github.com/toby3d/go-telegraph)- 电报发布平台api客户端. 
-   [去-tgbot](https://github.com/olebedev/go-tgbot)- 由swagger文件,基于会话的路由器和中间件生成的纯golang电报bot api包装器. 
-   [去-趋势](https://github.com/andygrunwald/go-trending)- 去图书馆进行访问[趋势库](https://github.com/trending)和[开发商](https://github.com/trending/developers)在github. 
-   [去颤搐](https://github.com/knspriggs/go-twitch)- 去客户端与twitch v3 api进行交互. 
-   [去,叽叽喳喳](https://github.com/dghubble/go-twitter)- 去Twitter客户端库v1.1 apis. 
-   [去-unsplash](https://github.com/hbagdi/go-unsplash)- 去客户端库[unsplash.com](https://unsplash.com)API. 
-   [去-XKCD](https://github.com/nishanths/go-xkcd)- 去xkcd api的客户端. 
-   [goamz](https://github.com/mitchellh/goamz)- 流行的叉子[goamz](https://launchpad.net/goamz)这增加了一些缺少的api调用某些包. 
-   [golyrics](https://github.com/mamal72/golyrics)-  golyrics是一个去库里从维基网站获取音乐歌词数据的库. 
-   [gomusicbrainz](https://github.com/michiwend/gomusicbrainz)- 去musicbrainz ws2客户端库. 
-   [谷歌](https://github.com/google/google-api-go-client)- 自动生成的谷歌apis去. 
-   [谷歌分析](https://github.com/chonthu/go-google-analytics)- 简单的封装,方便谷歌分析报告. 
-   [谷歌云](https://github.com/GoogleCloudPlatform/gcloud-golang)- 谷歌云端apis去客户端库. 
-   [谷歌的电子邮件审计-API](https://github.com/ngs/go-google-email-audit-api)- 去客户端库[谷歌G套房电子邮件审计API](https://developers.google.com/admin-sdk/email-audit/). 
-   [gostorm](https://github.com/jsgilmore/gostorm)-  gostorm是一个去库,它实现了编写风暴喷口和螺栓所需的通信协议,以便与风暴壳进行通信. 
-   [govkbot](https://github.com/nikepan/govkbot)- 简单去吧[VK](https://vk.com)bot库. 
-   [hipchat](https://github.com/andybons/hipchat)- 这个项目为hipchat api实现了一个golang客户端库. 
-   [hipchat(xmpp)](https://github.com/daneharrigan/hipchat)- 通过xmpp与hipchat进行通信的golang包. 
-   [IGDB](https://github.com/Henry-Sarabia/igdb)- 去客户的[互联网游戏数据库API](https://api.igdb.com/). 
-   [中](https://github.com/Medium/medium-sdk-go)-  golang sdk for medium的oauth2 api. 
-   [megos](https://github.com/andygrunwald/megos)- 用于访问的客户端库[apache mesos](http://mesos.apache.org/)簇. 
-   [米莎](https://github.com/onrik/micha)- 去电报机器人库去图书馆. 
-   [minio,去](https://github.com/minio/minio-go)-  minio去亚马逊s3兼容云存储库. 
-   [mixpanel](https://github.com/dukex/mixpanel)-  mixpanel是一个库,用于跟踪事件并将mixpanel配置文件更新从您的应用程序发送到mixpanel. 
-   [patreon,去](https://github.com/mxpv/patreon-go)- 去patreon api的图书馆. 
-   [贝宝](https://github.com/logpacker/paypalsdk)- 贝宝付款API的包装. 
-   [playlyfe](https://github.com/playlyfe/playlyfe-go-sdk)-  playlyfe rest api去sdk. 
-   [侧推](https://github.com/gregdel/pushover)- 为pushover API做封装. 
-   [rrdaclient](https://github.com/Omie/rrdaclient)- 去库访问statdns.com api,这反过来是rrda api. DNS查询HTTP. 
-   [shopify](https://github.com/rapito/go-shopify)- 去图书馆向shopify api提出请求. 
-   [松弛](https://github.com/nlopes/slack)- 松懈的API. 
-   [挝](https://github.com/sergiotapia/smitego)- 去包裹打包访问的smite游戏api. 
-   [Spotify的](https://github.com/rapito/go-spotify)- 去图书馆访问Spotify网络API. 
-   [蒸汽](https://github.com/sostronk/go-steam)- 去图书馆与蒸汽游戏服务器进行交互. 
-   [条纹](https://github.com/stripe/stripe-go)- 为客户提供条纹api. 
-   [TBOT](https://github.com/yanzay/tbot)- 类似于net / http的api报文机器人服务器. 
-   [telebot](https://github.com/tucnak/telebot)- 写在go的电报bot框架. 
-   [电报僵尸API](https://github.com/Syfaro/telegram-bot-api)- 简单而干净的电报机器人客户端. 
-   [textbelt](https://github.com/dietsche/textbelt)- 去textbelt.com txt消息API的客户端. 
-   [themoviedb](https://github.com/jbrodriguez/go-tmdb)- 简单的golang包来沟通[themoviedb.org](https://themoviedb.org). 
-   [翻译](https://github.com/poorny/translate)- 去网上翻译套餐. 
-   [trello](https://github.com/adlio/trello)- 去trello api的包装. 
-   [tumblr](https://github.com/mattcunningham/gumblr)- 去tumblr v2 api包装. 
-   [网络挂接](https://github.com/go-playground/webhooks)- 用于github和bitbucket的webhook接收器. 
-   [zooz](https://github.com/gojuno/go-zooz)- 去客户端zooz api. 

## 公用事业

_一般实用程序和工具,让您的生活更轻松. _

-   [abutil](https://github.com/bahlo/abutil)- 经常使用的golang助手的集合. 
-   [APM](https://github.com/topfreegames/apm)- 具有http api的golang应用程序的进程管理器. 
-   [backscanner](https://github.com/icza/backscanner)- 类似于bufio.scanner的扫描仪,但它以相反的顺序读取和返回行,从给定位置开始并向后移动. 
-   [boilr](https://github.com/tmrts/boilr)- 极快的cli工具,用于从样板模板创建项目. 
-   [乳糜](https://github.com/antham/chyle)- 使用具有多种配置可能性的git存储库的更新日志生成器. 
-   [电路](https://github.com/cep21/circuit)- 像执行断路器模式一样高效且功能完备的hystrix. 
-   [断路器](https://github.com/rubyist/circuitbreaker)- 断路器在走. 
-   [发条](http://github.com/onatm/clockwerk)- 使用简单,流畅的语法去安装程序包来安排定期作业. 
-   [命令](https://github.com/txgruppi/command)- 线程安全串行和并行调度程序的命令模式. 
-   [鸡舍](https://github.com/rakyll/coop)- 一些常用并发流程的备忘单. 
-   [复制面食](https://github.com/jutkko/copy-pasta)- 通用多工作站剪贴板,使用s3后端存储. 
-   [CTOP](https://github.com/bcicen/ctop)-[顶状](http://ctop.sh)接口(例如htop)用于容器度量. 
-   [死亡](https://github.com/vrecan/death)- 用信号管理应用程序的关闭. 
-   [deepcopier](https://github.com/ulule/deepcopier)- 简单的结构复制去. 
-   [钻研](https://github.com/derekparker/delve)- 去调试器. 
-   [DLOG](https://github.com/kirillDanshin/dlog)- 编译时控制的记录器,在不删除调试调用的情况下使您的版本更小. 
-   [ERGO](https://github.com/cristianoliveira/ergo)- 通过不同的端口管理多个本地服务变得容易. 
-   [评估](https://github.com/nullne/evaluator)- 基于s表达式动态地评估表达式. 它很容易扩展. 
-   [excelize](https://github.com/360EntSecGroup-Skylar/excelize)- 用于阅读和编写微软excel™(xlsx)文件的golang库. 
-   [fastlz](https://github.com/digitalcrab/fastlz)- 换行[fastlz](http://fastlz.org/)(免费的,开源的,可移植的实时压缩库). 
-   [文件类型](https://github.com/h2non/filetype)- 小包装来推断检查魔力数字签名的文件类型. 
-   [填料](https://github.com/yaronsumel/filler)- 使用"填充"标签填充结构的小工具. 
-   [FZF](https://github.com/junegunn/fzf)- 命令行模糊查找器写入. 
-   [生成](https://github.com/go-playground/generate)- 运行会在指定的路径或环境变量上递归生成,并且可以通过正则表达式进行过滤. 
-   [绅士](https://github.com/h2non/gentleman)- 全功能的插件驱动的http客户端库. 
-   [git的时间度量](https://github.com/git-time-metric/gtm)- 简单,无缝,轻量的git时间跟踪. 
-   [gjson](https://github.com/tidwall/gjson)- 用一行代码获取json值. 
-   [去-astitodo](https://github.com/asticode/go-astitodo)- 在你的代码中解析todos. 
-   [去绑定 - 插件](https://github.com/wendigo/go-bind-plugin)-  go: 生成用于包装由golang插件导出的符号的工具(仅限1.8). 
-   [去-的cron](https://github.com/rk/go-cron)- 简单的cron程序库,可以在特定的日期和时间以不同的时间间隔执行关闭或功能,从一秒一次到一年一次. 主要用于Web应用程序和长时间运行的守护进程. 
-   [去调试](https://github.com/tj/go-debug)-  golang库和应用程序的条件调试日志记录. 
-   [走干](https://github.com/ungerik/go-dry)- 干(不要重复自己)包去. 
-   [去放克](https://github.com/thoas/go-funk)- 提供助手(地图,查找,包含,过滤,大块,反向,...)的现代化实用程序库. 
-   [去-的HTTPHeader](https://github.com/mozillazg/go-httpheader)- 去库中编码结构到头字段. 
-   [去速率](https://github.com/beefsack/go-rate)- 定时限速器. 
-   [去后回应](https://github.com/nicklaw5/go-respond)- 去包处理常见的http json响应. 
-   [去-站点地图生成器](https://github.com/ikeikeikeike/go-sitemap-generator)- 写在go的xml站点地图生成器. 
-   [去火炬](https://github.com/uber/go-torch)-  go程序的随机火焰图分析器. 
-   [去触发](https://github.com/sadlil/go-trigger)-  go-lang全局事件触发器,用一个id注册事件并从你的项目的任何地方触发事件. 
-   [去下划线](https://github.com/tobyhede/go-underscore)- 有用的收集有用的去收集实用程序. 
-   [回去](https://github.com/carlescere/goback)- 走简单的指数退避包. 
-   [godaemon](https://github.com/VividCortex/godaemon)- 编写守护进程的实用程序. 
-   [godropbox](https://github.com/dropbox/godropbox)- 用于从Dropbox写入服务/应用程序的通用库. 
-   [gohper](https://github.com/cosiner/gohper)- 各种工具/模块有助于开发. 
-   [gojq](https://github.com/elgs/gojq)-  golang中的json查询. 
-   [gojson](https://github.com/ChimeraCoder/gojson)- 自动生成示例json的go(golang)结构体定义. 
-   [golarm](https://github.com/msempere/golarm)- 带系统事件的火警. 
-   [果洛](https://github.com/mlimaloureiro/golog)- 简单轻便的cli工具来跟踪您的任务. 
-   [gopencils](https://github.com/bndr/gopencils)- 小而简单的包装容易消费休息apis. 
-   [goplaceholder](https://github.com/michiwend/goplaceholder)- 用于生成占位符图像的小型golang库. 
-   [goreleaser](https://github.com/goreleaser/goreleaser)- 尽可能快速和轻松地交付二进制文件. 
-   [goreporter](https://github.com/wgliang/goreporter)- 执行静态分析,单元测试,代码审查和生成代码质量报告的golang工具. 
-   [goreq](https://github.com/franela/goreq)- 语言的最小和简单的请求库. 
-   [goreq](https://github.com/smallnest/goreq)- 基于gorequest的增强型简化http客户端. 
-   [gorequest](https://github.com/parnurzeal/gorequest)- 简化的http客户端,具有丰富的功能. 
-   [goseaweedfs](https://github.com/linxGnu/goseaweedfs)- 具有几乎完整功能的seaweedfs客户端库. 
-   [gotenv](https://github.com/subosito/gotenv)- 从中​​加载环境变量`.ENV`或任何`io.reader`进去. 
-   [goxlsxwriter](https://github.com/fterrag/goxlsxwriter)- 用于编写xlsx(microsoft excel)文件的libxlsxwriter的golang绑定. 
-   [GPATH](https://github.com/tenntenn/gpath)- 用反射表达式来简化访问结构域的库. 
-   [grequests](https://github.com/levigross/grequests)- 优雅和简单`净/ HTTP`包装遵循python的请求库. 
-   [GRON](https://github.com/roylee0704/gron)- 使用简单的go api定义基于时间的任务,gron的调度程序将相应地运行它们. 
-   [htcat](https://github.com/htcat/htcat)- 并行和流水线http获取实用程序. 
-   [httpcontrol](https://github.com/facebookgo/httpcontrol)-  httpcontrol包允许在超时和重试时进行http传输级别控制. 
-   [枢纽](https://github.com/github/hub)- 使用额外的功能包装git命令,从终端与github进行交互. 
-   [红椎,去](https://github.com/afex/hystrix-go)- 实现程序员定义的回退(又名断路器)的hystrix模式. 
-   [不朽](https://github.com/immortal/immortal)-  \* nix跨平台(操作系统不可知)主管. 
-   [固有](https://github.com/mengzhuo/intrinsic)- 在不写汇编代码的情况下使用x86 simd. 
-   [jobrunner](https://github.com/bamzi/jobrunner)- 智能且功能强大的cron作业调度程序,内置作业排队和实时监控. 
-   [jsonapi-错误](https://github.com/AmuzaTkts/jsonapi-errors)- 根据json API错误引用进行绑定. 
-   [jsonf](https://github.com/miolini/jsonf)- 控制台工具突出显示格式和结构查询获取JSON. 
-   [jsongo](https://github.com/ricardolonga/jsongo)- 流利的API,使创建JSON对象更容易. 
-   [jsonhal](https://github.com/RichardKnop/jsonhal)- 简单的去包,使定制结构元帅哈尔兼容JSON响应. 
-   [kazaam](https://github.com/Qntfy/kazaam)- 任意转换json文档的api. 
-   [lrserver](https://github.com/jaschaephraim/lrserver)-  livereload服务器去. 
-   [MC](https://github.com/minio/mc)-  minio客户端提供与亚马逊s3兼容云存储和文件系统一起工作的最小工具. 
-   [mergo](https://github.com/imdario/mergo)- 帮助合并golang中的结构和地图. 有用的配置默认值,避免混乱的if语句. 
-   [缩小](https://github.com/tdewolff/minify)-  html,css,js,xml,json和svg文件格式的快速缩小. 
-   [minquery](https://github.com/icza/minquery)- 支持高效分页的mongodb / mgo.v2查询(光标继续列出我们离开的文档). 
-   [mmake](https://github.com/tj/mmake)- 现代化的制作. 
-   [摩尔多瓦](https://github.com/StabbyCutyou/moldova)- 基于输入模板生成随机数据的实用程序. 
-   [熔点](https://github.com/sanbornm/mp)- 简单的cli电子邮件解析器. 它目前需要stdin并输出json. 
-   [mssqlx](https://github.com/linxGnu/mssqlx)- 数据库客户端库,任何主从的代理,主控主结构. 轻量级和自动平衡. 
-   [multitick](https://github.com/VividCortex/multitick)- 多路复用器用于对齐的代号. 
-   [myhttp](https://github.com/inancgumus/myhttp)- 简单的api使http获取请求支持超时. 
-   [netbug](https://github.com/e-dard/netbug)- 轻松远程分析您的服务. 
-   [okrun](https://github.com/xta/okrun)- 去运行错误压路机. 
-   [onecache](https://github.com/adelowo/onecache)- 支持多个后端存储的缓存库(redis,memcached,文件系统等). 
-   [panicparse](https://github.com/maruel/panicparse)- 分组类似的goroutines并着色堆栈转储. 
-   [PECO](https://github.com/peco/peco)- 简单的交互式过滤工具. 
-   [纠缠](https://github.com/sethgrid/pester)- 通过重试,退避和并发来进行http客户端调用. 
-   [下午](https://github.com/VividCortex/pm)- 具有http api的进程(即goroutine)管理器. 
-   [轮廓](https://github.com/pkg/profile)- 简单的分析支持包. 
-   [rclient](https://github.com/zpatrick/rclient)- 可读,灵活,简单易用的休息API客户端. 
-   [实现](https://github.com/tockins/realize)- 与文件观察者一起构建系统并实时重新加载. 使用自定义路径运行,构建和监视文件更改. 
-   [重复](https://github.com/ssgreg/repeat)- 执行对重试操作和心跳有用的不同退避策略. 
-   [请求](https://github.com/mozillazg/request)- 去人类的http请求. 
-   [rerate](https://github.com/abo/rerate)- 基于redis的速率计数器和限速器. 
-   [重新运行](https://github.com/ivpusic/rerun)- 在源更改时重新编译并重新运行应用程序. 
-   [resty](https://github.com/go-resty/resty)- 简单的http和休息客户端,由ruby休息客户端启发. 
-   [重试](https://github.com/kamilsk/retry)- 基于上下文重复执行操作直到成功为止的功能机制. 
-   [重试](https://github.com/thedevsaddam/retry)- 简单易用的重试机制包. 
-   [重试,去](https://github.com/rafaeljesus/retry-go)- 重试使golang变得简单和容易. 
-   [稳健](https://github.com/VividCortex/robustly)- 弹性运行功能,捕捉并重新启动恐慌. 
-   [RQ](https://github.com/ddo/rq)- 一个更好的golang stdlib http客户端界面. 
-   [调度](https://github.com/carlescere/scheduler)-  cronjobs日程安排变得简单. 
-   [吊绳](https://github.com/dghubble/sling)- 去api客户端的http请求生成器. 
-   [微调](https://github.com/briandowns/spinner)- 去包裹轻松提供一个终端微调器的选项. 
-   [SQLX](https://github.com/jmoiron/sqlx)- 在优秀的内置数据库/ sql包中提供了一套扩展. 
-   [风暴](https://github.com/asdine/storm)-  boltdb简单而强大的工具包. 
-   [结构](https://github.com/PumpkinSeed/structs)- 实现简单的函数来操作结构. 
-   [任务](https://github.com/go-task/task)- 简单的"制造"替代. 
-   [工具箱](https://github.com/viant/toolbox)-  slice,map,multimap,struct,函数,数据转换工具. 服务路由器,宏评估器,标记器. 
-   [乌戈](https://github.com/alxrm/ugo)-  ugo是带有简洁语法的切片工具箱. 
-   [清华紫光](https://github.com/esemplastic/unis)-  go中的字符串实用程序的common architecture™. 
-   [usql](https://github.com/knq/usql)-  usql是sql数据库的通用命令行界面. 
-   [UTIL](https://github.com/shomali11/util)- 收集有用的实用功能. (字符串,并发性,操作......). 
-   [wuzz](https://github.com/asciimoo/wuzz)- 用于HTTP检查的交互式cli工具. 
-   [xferspdy](https://github.com/monmohan/xferspdy)-  xferspdy在golang中提供二进制diff和补丁库. 
-   [XLSX](https://github.com/tealeg/xlsx)- 用于简化阅读go程序中最新版本的microsoft excel所使用的xml格式的库. 

## 验证

_用于验证的库. _

-   [govalidator](https://github.com/asaskevich/govalidator)- 用于字符串,数字,切片和结构的验证器和消毒剂. 
-   [govalidator](https://github.com/thedevsaddam/govalidator)- 使用简单的规则验证golang请求数据. 受到laravel要求验证的高度启发. 
-   [OZZO验证](https://github.com/go-ozzo/ozzo-validation)- 通过在通常的代码结构中指定的可配置和可扩展的验证规则来支持各种数据类型(结构,字符串,映射,切片等)的验证,而不是结构标签. 
-   [验证](https://github.com/markbates/validate)- 这个包提供了一个框架来编写去应用程序的验证. 
-   [验证器](https://github.com/go-playground/validator)- 进行结构和字段验证,包括交叉字段,交叉结构,地图,切片和数组潜水. 

## 版本控制

_用于版本控制的库. _

-   [GH](https://github.com/rjeczalik/gh)- 用于github webhooks的脚本化服务器和net / http中间件. 
-   [git2go](https://github.com/libgit2/git2go)- 去绑定libgit2. 
-   [去-VCS](https://github.com/sourcegraph/go-vcs)- 操作并检查vcs存储库. 
-   [HGO](https://github.com/beyang/hgo)-  hgo是go包的集合,提供对本地mercurial存储库的读取访问. 

## 视频

_用于处理视频的库. _

-   [转基因食品](https://github.com/3d0c/gmf)- 去绑定ffmpeg av\*库. 
-   [去-astisub](https://github.com/asticode/go-astisub)- 操作go中的字幕(.srt,.stl,.ttml,.webvtt,.ssa / .ass,teletext,.smi等). 
-   [去-astits](https://github.com/asticode/go-astits)- 在本地中解析和解复用mpeg传输流(.ts). 
-   [goav](https://github.com/giorgisio/goav)- 用于ffmpeg的comphrensive go绑定. 
-   [GST](https://github.com/ziutek/gst)- 去gstreamer绑定. 
-   [libgosubs](https://github.com/wargarblgarbl/libgosubs)- 字幕格式支持. 支持.srt,.ttml和.ass. 
-   [为v41](https://github.com/korandiz/v4l)- 用于linux的视频捕获库,用go编写. 

## web框架

_全堆栈web框架. _

-   [AAH](https://aahframework.org)- 可扩展,高性能,快速开发的Web框架. 
-   [空气](https://github.com/sheng/air)- 去理想的宁静网页框架. 
-   [班卓琴](https://github.com/nsheremet/banjo)- 非常简单快速的网页框架. 
-   [beego](https://github.com/astaxie/beego)-  beego是一款开源的高性能Web编程语言框架. 
-   [水牛](http://gobuffalo.io)- 带来铁轨的生产力!
-   [回声](https://github.com/labstack/echo)- 高性能,极简主义的网页框架. 
-   [火球](https://github.com/zpatrick/fireball)- 更"自然"的web框架感觉. 
-   [florest](https://github.com/jabong/florest-core)- 基于高性能工作流的rest API框架. 
-   [宝石](https://github.com/go-gem/gem)- 简单快速的网页框架,友好的休息API. 
-   [杜松子酒](https://github.com/gin-gonic/gin)- 杜松子酒是一个用go编写的web框架!它具有性能更好的马提尼式API,速度提高40倍. 如果你需要性能和生产力. 
-   [小发明](https://github.com/NYTimes/gizmo)- 纽约时代使用的微服务工具包. 
-   [去-JSON的REST](https://github.com/ant0ine/go-json-rest)- 快速简单的方法来设置一个宁静的JSON API. 
-   [走,放松](https://github.com/codehack/go-relax)- 构建可靠的API的框架. 
-   [去休息](https://github.com/ungerik/go-rest)- 小小和邪恶的休息框架. 
-   [果阿](https://github.com/raphael/goa)- 基于ruby的实践设计开发微服务的框架. 
-   [高尔夫球](https://github.com/dinever/golf)- 高尔夫是一个快速,简单和轻量级的微网框架. 它具有强大的功能,除去标准库以外没有任何依赖关系. 
-   [贡多拉](https://github.com/rainycape/gondola)- 用于编写更快速网站的Web框架,速度更快. 
-   [gongular](https://github.com/mustafaakin/gongular)- 通过输入映射/验证和(di)依赖注入快速运行web框架. 
-   [马卡龙](https://github.com/go-macaron/macaron)- 马卡龙是一个高效率的模块化设计网络框架. 
-   [芒果](https://github.com/paulbellamy/mango)- 芒果是一个模块化的网络应用框架,受机架和pep333的启发. 
-   [微服务](https://github.com/claygod/microservice)- 用golang编写的用于创建微服务的框架. 
-   [新](https://github.com/ivpusic/neo)-  neo是非常简单的api,它是最小的,快速的web框架. 
-   [resoursea](https://github.com/resoursea/api)- 快速编写基于资源的服务的休息框架. 
-   [休息层](http://rest-layer.io)- 在数据库之上构建rest / graphql api的框架,主要是配置代码. 
-   [陶醉](https://github.com/revel/revel)- 适用于go语言的高生产率web框架. 
-   [雷克斯](https://github.com/goanywhere/rex)-  rex是一个基于大猩猩/多路复用器的模块化开发库,完全兼容`净/ HTTP`. 
-   [sawsij](https://github.com/jaybill/sawsij)- 用于构建高性能,数据驱动的Web应用程序的轻量级开源Web框架. 
-   [探戈舞](https://github.com/lunny/tango)- 微型可插拔网页框架. 
-   [tigertonic](https://github.com/rcrowley/go-tigertonic)- 去构建由dropwizard启发的json web服务的框架. 
-   [交通](https://github.com/pilu/traffic)-  sinatra启发了正则表达式/模式复用器和web框架. 
-   [utron](https://github.com/gernest/utron)-  Go的轻量级mvc框架(golang). 
-   [紫耳蜂鸟属](https://github.com/nbari/violetear)- 去http路由器. 
-   [yarf](https://github.com/yarf-framework/yarf)- 快速微型框架,旨在快速简单地构建休息API和Web服务. 
-   [zerver](https://github.com/cosiner/zerver)-  zerver是一个富有表现力,模块化,功能完备的宁静框架. 

### 中间件

#### 实际的中间件

-   [客户端 - 定时](https://github.com/posener/client-timing)- 服务器时间标头的http客户端. 
-   [CORS](https://github.com/rs/cors)- 轻松地将cors功能添加到您的api. 
-   [formjson](https://github.com/rs/formjson)- 透明地将json输入作为标准表单发布. 
-   [去服务器定时](https://github.com/mitchellh/go-server-timing)- 添加/解析服务器时间标题. 
-   [限制器](https://github.com/ulule/limiter)- 去死简单的速率限制中间件. 
-   [收费站](https://github.com/didip/tollbooth)- 限制HTTP请求处理程序. 
-   [XFF](https://github.com/sebest/xff)- 处理`的x转发换`标题和朋友. 

#### 用于创建http中间件的库

-   [爱丽丝](https://github.com/justinas/alice)- 无痛的中间件链接去. 
-   [系列](https://github.com/codemodus/catena)-  http.handler包装连接(与"chain"相同的api). 
-   [链](https://github.com/codemodus/chain)- 与范围数据链接的处理程序包装(基于网络/上下文的"中间件"). 
-   [去缠绕](https://github.com/go-on/wrap)-  net / http的小型中间件软件包. 
-   [戈尔](https://github.com/alioygur/gores)- 去处理html,json,xml等响应的包. 对宁静的apis有用. 
-   [干预](https://github.com/carbocation/interpose)- 用于golang的简约网络/ http中间件. 
-   [muxchain](https://github.com/stephens2424/muxchain)- 净/ HTTP的轻量级中间件. 
-   [内格罗尼](https://github.com/urfave/negroni)-  golang的惯用http中间件. 
-   [给予](https://github.com/unrolled/render)- 去打包,以轻松呈现json,xml和html模板响应. 
-   [渲染](https://github.com/thedevsaddam/renderer)- 简单,轻量和更快的响应(json,jsonp,xml,yaml,html,文件)渲染包. 
-   [黑麦](https://github.com/InVisionApp/rye)- 支持jwt,cors,statsd和1.7上下文的小型中间件库(带有罐装中间件). 
-   [统计](https://github.com/thoas/stats)- 去中间件,存储有关您的Web应用程序的各种信息. 
-   [挥发物](https://github.com/volatile/core)- 极简主义的中间件堆栈提高了灵活性,良好的实践和干净的代码. 

### 路由器

-   [外侨](https://github.com/gernest/alien)- 来自外太空的轻量级和快速http路由器. 
-   [骨](https://github.com/go-zoo/bone)- 闪电般的http复用器. 
-   [bxog](https://github.com/claygod/Bxog)- 简单快速的http路由器. 它适用于不同难度,长度和嵌套的路线. 他知道如何从收到的参数中创建一个url. 
-   [志](https://github.com/go-chi/chi)- 基于网络/上下文构建的小型,快速和富有表现力的http路由器. 
-   [fasthttprouter](https://github.com/buaazp/fasthttprouter)- 高性能路由器`httprouter`. 第一个路由器适合`fasthttp`. 
-   [fastrouter](https://github.com/razonyang/fastrouter)- 一个快速,灵活的http路由器. 
-   [gocraft /网络](https://github.com/gocraft/web)- 多路复用器和中间件软件包. 
-   [枸杞](https://github.com/goji/goji)-  goji是一个简约而灵活的http请求多路复用器,支持`净/上下文`. 
-   [gorouter](https://github.com/vardius/gorouter)-  gorouter是一个服务器/ api微型架构,http请求路由器,多路复用器,多路复用器,为请求路由器提供中间件支持`净/上下文`. 
-   [gowww /路由器](https://github.com/gowww/router)- 快如闪电的http路由器完全兼容net / http.handler接口. 
-   [httprouter](https://github.com/julienschmidt/httprouter)- 高性能路由器. 使用这个和标准的http处理程序来组成一个非常高性能的web框架. 
-   [httptreemux](https://github.com/dimfeld/httptreemux)- 高速,灵活的基于树的http路由器. 灵感来自httprouter. 
-   [拉尔斯](https://github.com/go-playground/lars)- 是一个轻量级,快速和可扩展的零分配http路由器,用于创建可定制的框架. 
-   [medeina](https://github.com/imdario/medeina)-  medeina是一个基于httprouter的http路由树,灵感来自于roda和cuba. 
-   [MUX](https://github.com/gorilla/mux)-  golang强大的url路由器和调度器. 
-   [OZZO路由](https://github.com/go-ozzo/ozzo-routing)- 支持正则表达式路由匹配的极速(golang)http路由器. 完全支持建立宁静的apis. 
-   [拍](https://github.com/bmizerany/pat)-  sinatra的作者sinatra风格模式muxer为go的net / http库. 
-   [纯](https://github.com/go-playground/pure)- 是一个轻量级的http路由器,坚持std"net / http"实现. 
-   [午休](https://github.com/VividCortex/siesta)- 编写中间件和处理程序的可组合框架. 
-   [vestigo](https://github.com/husobee/vestigo)- 高性能,独立的,符合http的url路由器,用于访问web应用程序. 
-   [XMUX](https://github.com/rs/xmux)- 基于. 的高性能复用器`httprouter`同`净/上下文`支持. 
-   [xujiajun / gorouter](https://github.com/xujiajun/gorouter)- 一个简单快速的http路由器. 
-   [宙斯](https://github.com/daryl/zeus)- 非常简单快速的http路由器. 

## 视窗

-   [D3D9](https://github.com/gonutz/d3d9)- 去direct3d9绑定. 
-   [去-OLE](https://github.com/go-ole/go-ole)-  golang的win32 ole实现. 

## XML

_用于处理xml的库和工具. _

-   [XML-COMP](https://github.com/xml-comp/xml-comp)- 简单的命令行xml比较器,可生成文件夹,文件和标签的差异. 
-   [的XmlWriter](https://github.com/shabbyrobe/xmlwriter)- 基于libxml2的xmlwriter模块的程序化XML生成API. 
-   [XPath的](https://github.com/antchfx/xpath)- 去xpath包. 
-   [XQuery的](https://github.com/antchfx/xquery)-  xquery允许您使用xpath表达式从html / xml文档提取数据. 

# 工具

_去软件和插件. _

## 代码分析

-   [apicompat](https://github.com/bradleyfalzon/apicompat)- 检查针对向后不兼容的更改的最近更改项目. 
-   [DUPL](https://github.com/mibk/dupl)- 代码克隆检测工具. 
-   [errcheck](https://github.com/kisielk/errcheck)-  errcheck是用于检查go程序中未检查错误的程序. 
-   [gcvis](https://github.com/davecheney/gcvis)- 实时显示go程序gc跟踪数据. 
-   [去金属间](https://github.com/alecthomas/gometalinter)-  metalinter是一种自动应用所有静态分析工具并以标准化形式报告其输出的工具. 
-   [去-的CheckStyle](https://github.com/qiniu/checkstyle)-  checkstyle是一种类似java checkstyle的样式检查工具. 这个工具受java checkstyle,golint的启发. 该风格指的是去代码审查评论中的一些点. 
-   [去-cleanarch](https://github.com/roblaszczak/go-cleanarch)-  go-cleanarch是为了验证干净的体系结构规则而创建的,比如你项目中的依赖规则和包之间的交互. 
-   [去-过时](https://github.com/firstrow/go-outdated)- 显示过时包的控制台应用程序. 
-   [goast查看器](https://github.com/yuroyoro/goast-viewer)- 基于网络的golang ast可视化器. 
-   [gocover.io](http://gocover.io/)-  gocover.io提供任何golang包作为服务的代码覆盖范围. 
-   [goimports](https://godoc.org/golang.org/x/tools/cmd/goimports)- 自动修复(添加,删除)您的导入导入工具. 
-   [golangci](https://golangci.com/)-  golangci是一个针对github pull请求的自动golang代码审查服务. 服务是开源的,它对开源项目是免费的. 
-   [golint](https://github.com/golang/lint)-  golint是去源代码的linter. 
-   [golint在线](http://go-lint.appspot.com/)-  lints online使用golint包在github,bitbucket和google项目托管上使用源文件. 
-   [goreturns](https://sourcegraph.com/github.com/sqs/goreturns)- 添加零值返回语句以匹配func返回类型. 
-   [gosimple](https://github.com/dominikh/go-tools/tree/master/cmd/gosimple)-  gosimple是专门用于简化代码的源代码的linter. 
-   [gostatus](https://github.com/shurcooL/gostatus)- 命令行工具,显示包含go软件包的存储库的状态. 
-   [接口部分](https://github.com/mvdan/interfacer)- 建议接口类型的linter. 
-   [皮棉](https://github.com/surullabs/lint)- 运行棉绒作为测试的一部分. 
-   [PHP解析器](https://github.com/z7zmey/php-parser)- 一个用于写入php的解析器. 
-   [staticcheck](https://github.com/dominikh/go-tools/tree/master/cmd/staticcheck)-  staticcheck是`去兽医`在类固醇,应用大量的静态分析检查,你可能会习惯从像resharper for c#工具. 
-   [篷布](https://github.com/verygoodsoftwarenotvirus/tarp)-  tarp可以找到函数和方法,而不需要直接在源代码中进行单元测试. 
-   [unconvert](https://github.com/mdempsky/unconvert)- 从源代码中移除不必要的类型转换. 
-   [没用过](https://github.com/dominikh/go-tools/tree/master/cmd/unused)- 未使用的检查代码为未使用的常量,变量,函数和类型. 
-   [验证](https://github.com/mccoyst/validate)- 自动验证带有标签的结构字段. 

## 编辑插件

-   [去jetbrains IDE插件](https://plugins.jetbrains.com/plugin/9568-go)- 去jetbrains IDE插件. 
-   [去语言服务器](https://github.com/theia-ide/go-language-server)- 将vscode go扩展转换为支持语言服务器协议的语言服务器的包装器. 
-   [去模式](https://github.com/dominikh/go-mode.el)-  go模式为gnu / emacs. 
-   [去加](https://github.com/joefitzgerald/go-plus)go(golang)包中添加了自动完成,格式化,语法检查,linting和审查的原子. 
-   [goclipse](https://github.com/GoClipse/goclipse)- 去eclipse插件. 
-   [gocode](https://github.com/nsf/gocode)-  go编程语言的自动完成守护进程. 
-   [gosublime](https://github.com/DisposaBoy/GoSublime)- 用于文本编辑器的golang插件集sublimetext 3提供代码完成和其他类似IDE的功能. 
-   [忒伊亚-GO-扩展](https://github.com/theia-ide/theia-go-extension)- 为theia ide提供语言支持. 
-   [丝绒](https://github.com/velour/velour)-  acme编辑器的irc客户端. 
-   [VIM-编译器去](https://github.com/rjohnsondev/vim-compiler-go)-  vim插件在保存时突出显示语法错误. 
-   [VIM-去](https://github.com/fatih/vim-go)- 去vim开发插件. 
-   [vscode,去](https://github.com/Microsoft/vscode-go)- 为视觉工作室代码(vs代码)的扩展,它为go语言提供支持. 
-   [看](https://github.com/eaburns/Watch)- 在文件更改中以最快的速度运行命令. 

## 去生成工具

-   [通用](https://github.com/usk81/generic)- 灵活的数据类型. 
-   [GENNY](https://github.com/cheekybits/genny)- 去优雅的泛型. 
-   [gonerics](http://github.com/bouk/gonerics)- 去的惯用的泛型. 
-   [gotests](https://github.com/cweill/gotests)- 从您的源代码生成测试. 
-   [re2dfa](https://github.com/opennota/re2dfa)- 将正则表达式转换为有限状态机,并输出源代码. 

## 去工具

-   [colorgo](https://github.com/songgao/colorgo)- 包装`走`命令为彩色`去建立`输出. 
-   [深度](https://github.com/KyleBanks/depth)- 通过分析导入可视化任何包的依赖树. 
-   [GB](https://getgb.io/)- 一种易于使用的基于项目的编程语言编译工具. 
-   [发电机去琅](https://github.com/axelspringer/generator-go-lang)- 一个[自耕农](https://yeoman.io)发电机开始新的项目. 
-   [去-callvis](https://github.com/TrueFurby/go-callvis)- 使用点格式显示您的Go程序的通话图. 
-   [去-PKG完成](https://github.com/skelterjohn/go-pkg-complete)-  bash完成go和wgo. 
-   [走,昂首阔步](https://github.com/go-swagger/go-swagger)-  swagger 2.0实现去. swagger是一个简单而强大的代表你的宁静api. 
-   [octolinker](https://github.com/OctoLinker/browser-extension)- 通过github的octolinker浏览器扩展高效浏览go文件. 
-   [richgo](https://github.com/kyoh86/richgo)- 丰富`去测试`带有文字装饰的输出. 
-   [RTS](https://github.com/galeone/rts)-  rts: 对结构的响应. 从服务器响应生成结构. 

## 软件包

_软件写在去. _

### devops工具

-   [恰当地](https://github.com/smira/aptly)- 恰当的是一个debian存储库管理工具. 
-   [极光](https://github.com/xuri/aurora)- 跨平台的基于Web的beanstalkd队列服务器控制台. 
-   [awsenv](https://github.com/soniah/awsenv)- 为配置文件加载amazon(aws)环境变量的小型二进制文件. 
-   [女妖](https://github.com/eleme/banshee)- 周期性度量的异常检测系统. 
-   [爆破](https://github.com/dave/blast)-  api负载测试和批量作业的简单工具. 
-   [投弹手](https://github.com/codesenberg/bombardier)- 快速的跨平台http基准测试工具. 
-   [商船甲板长](https://github.com/bosun-monitor/bosun)- 时间序列警报框架. 
-   [走吧](https://github.com/liudng/dogo)- 监视源文件中的更改并自动编译和运行(重新启动). 
-   [无人机詹金斯](https://github.com/appleboy/drone-jenkins)- 使用二进制,码头或无人机ci触发下游jenkins工作. 
-   [无人机SCP](https://github.com/appleboy/drone-scp)- 通过ssh使用二进制,码头或无人机ci复制文件和工件. 
-   [运输机](https://github.com/chrismckenzie/dropship)- 通过cdn部署代码的工具. 
-   [easyssh代理](https://github.com/appleboy/easyssh-proxy)-  golang包,通过ssh和scp轻松远程执行`proxycommand`. 
-   [gitea](https://github.com/go-gitea/gitea)- 叉子,完全由社区驱动. 
-   [去衡量指标](https://github.com/rcrowley/go-metrics)- 进入Coda hale的指标库端口: <https://github.com/codahale/metrics>. 
-   [去,自更新](https://github.com/sanbornm/go-selfupdate)- 使您的应用程序自行更新. 
-   [gobrew](https://github.com/cryptojuice/gobrew)-  gobrew可让您轻松切换go的多个版本. 
-   [godbg](https://github.com/sirnewton01/godbg)- 基于web的gdb前端应用程序. 
-   [视护目镜](https://gogs.io/)-  Go编程语言中的自我托管git服务. 
-   [gonative](https://github.com/inconshreveable/gonative)- 创建go的构建工具,可以交叉编译到所有平台,同时仍然使用启用cgo的stdlib软件包版本. 
-   [govvv](https://github.com/ahmetalpbalkan/govvv)- "去构建"包装来轻松地将版本信息添加到二进制文件中. 
-   [GOX](https://github.com/mitchellh/gox)- 死简单,没有装饰去交叉编译工具. 
-   [goxc](https://github.com/laher/goxc)- 构建工具,专注于交叉编译和打包. 
-   [葡萄](https://github.com/yaronsumel/grapes)- 轻量级工具,旨在轻松地通过SSH分发命令. 
-   [GVM](https://github.com/moovweb/gvm)-  gvm提供了一个管理go版本的界面. 
-   [嘿](https://github.com/rakyll/hey)- 嘿是一个小程序,它负责将一些负载发送到Web应用程序. 
-   [黑热病](https://github.com/ajvb/kala)- 简单,现代和高性能的作业调度程序. 
-   [kcli](https://github.com/cswank/kcli)- 用于检查卡夫卡主题/分区/消息的命令行工具. 
-   [kubernetes](https://github.com/kubernetes/kubernetes)- 谷歌的集装箱集群管理器. 
-   [manssh](https://github.com/xwjdsh/manssh)-  manssh是一个用于管理你的ssh别名配置的命令行工具. 
-   [MOBY](https://github.com/moby/moby)- 为集装箱生态系统组装容器系统的合作项目. 
-   [猜拳](https://github.com/emicklei/mora)- 用于访问mongodb文档和元数据的其余服务器. 
-   [预兆](https://github.com/ostrost/ostent)- 收集并显示系统指标,并可选择中继至石墨和/或influxdb. 
-   [打包机](https://github.com/mitchellh/packer)- 打包器是一种用于从单一源配置为多个平台创建相同机器映像的工具. 
-   [pewpew](https://github.com/bengadbois/pewpew)- 灵活的http命令行应力测试器. 
-   [啮齿动物](https://github.com/alouche/rodent)- 啮齿动物帮助您管理版本,项目和跟踪依赖项. 
-   [s3gof3r](https://github.com/rlmcpherson/s3gof3r)- 针对大型物体进出亚马逊s3的高速传输优化的小型实用程序/库. 
-   [scaleway-CLI](https://github.com/scaleway/scaleway-cli)- 从命令行管理裸机服务器(就像使用docker一样). 
-   [SG](https://github.com/ChristopherRabotin/sg)- 对一组http端点(比如ab)进行基准测试,根据之前的响应,可以在每次调用之间使用响应代码和数据来针对特定的服务器压力. 
-   [SKM](https://github.com/TimothyYe/skm)-  skm是一个简单而强大的ssh密钥管理器,它可以帮助您轻松管理多个ssh密钥!
-   [statusok](https://github.com/sanathp/statusok)- 监控您的网站并在服务器停机或响应时间超出预期时通过闲置,电子邮件通知apis.get. 
-   [traefik](https://github.com/containous/traefik)- 反向代理和负载均衡器,支持多个后端. 
-   [素食](https://github.com/tsenart/vegeta)-  http负载测试工具和库. 超过9000!
-   [网络挂接](https://github.com/adnanh/webhook)- 允许用户创建在服务器上执行命令的http端点(挂钩)的工具. 
-   [宽](https://wide.b3log.org/login)- 使用golang的团队的基于网络的ide. 
-   [WinRM的-CLI](https://github.com/masterzen/winrm-cli)-  cli工具在Windows机器上远程执行命令. 

### 其他软件

-   [博格](https://github.com/crufter/borg)- 基于终端的搜索引擎,用于bash片段. 
-   [盒装](https://github.com/tejo/boxed)- 基于Dropbox的博客引擎. 
-   [樱桃](https://github.com/rafael-santiago/cherry)- 小型网聊服务器
-   [电路](https://github.com/gocircuit/circuit)- 电路是一种可编程的平台即服务(paas)和/或基础架构即服务(iaas),用于管理,发现,同步和协调包含云应用程序的服务和主机. 
-   [康卡斯特](https://github.com/tylertreat/Comcast)- 模拟糟糕的网络连接. 
-   [confd](https://github.com/kelseyhightower/confd)- 使用来自etcd或consul的模板和数据管理本地应用程序配置文件. 
-   [DDNS](https://github.com/skibish/ddns)- 数字海洋网络dns作为后端的个人ddns客户端. 
-   [搬运工人](http://www.docker.com/)- 面向开发人员和系统管理员的分布式应用程序开放平台. 
-   [documize](https://github.com/documize/community)- 集成saas工具数据的现代wiki软件. 
-   [舰队](https://github.com/coreos/fleet)- 分布式init系统. 
-   [去包店](https://github.com/shurcooL/Go-Package-Store)- 在你的gopath中显示go软件包更新的应用程序. 
-   [GOCC](https://github.com/goccmack/gocc)-  gocc是一个用于编写go的编译器工具包. 
-   [godns](https://github.com/timothyye/godns)- 一个动态的dns客户端工具,支持dnspod&he.net,写成go. 
-   [godoctooltip](https://github.com/diankong/GoDocTooltip)-  go doc站点的chrome扩展,其功能描述显示为功能列表中的工具提示. 
-   [的Goland](https://jetbrains.com/go)- 功能齐全的跨平台go ide. 
-   [GOR](https://github.com/buger/gor)-  http流量复制工具,用于实时重放从生产到舞台/开发环境的流量. 
-   [雨果](http://gohugo.io/)- 快速和现代的静态网站引擎. 
-   [IDE](https://github.com/thestrukture/ide)- 浏览器可访问的ide. 专为一起去吧. 
-   [IPE](https://github.com/dimiro1/ipe)- 开放源代码推送服务器实现与go中写入的推入客户端库兼容. 
-   [jaydiff](https://github.com/yazgazan/jaydiff)-  json diff实用程序写成go. 
-   [朱朱](https://jujucharms.com/)- 与云无关的服务部署和编排 - 支持ec2,azure,openstack,maas等. 
-   [飞跃](https://github.com/jeffail/leaps)- 使用操作变换的编程服务. 
-   [limetext](http://limetext.org/)-  lime文本是一款功能强大而优雅的文本编辑器,主要用于开发旨在成为免费和开放源代码的文本崇高软件继承者. 
-   [liteide](https://github.com/visualfc/liteide)-  liteide是一个简单的,开源的,跨平台的go ide. 
-   [幻梦](https://github.com/quii/mockingjay-server)- 来自一个配置文件的虚假http服务器和消费者驱动合同. 您还可以使服务器随机行为不便,以帮助进行更真实的性能测试. 
-   [mylg](https://github.com/mehrdadrad/mylg)- 用go编写的命令行网络诊断工具. 
-   [naclpipe](https://github.com/unix4fun/naclpipe)- 简单的基于nacl ec25519的加密管道工具. 
-   [内斯](https://github.com/fogleman/nes)- 任天堂娱乐系统(奈斯)模拟器写在去. 
-   [橙猫](https://github.com/noraesae/orange-cat)- 降价预览器写在去. 
-   [轨道](https://github.com/gulien/orbit)- 用于运行命令并从模板生成文件的简单工具. 
-   [衣夹](https://github.com/pointlander/peg)-  peg,解析表达式语法,是packrat解析器生成器的实现. 
-   [管](https://github.com/b3log/pipe)- 一个小而美的博客平台. 
-   [邮差](https://github.com/zachlatta/postman)- 用于批量发送电子邮件的命令行工具. 
-   [restic](https://github.com/restic/restic)- 重复备份程序. 
-   [RKT](https://github.com/coreos/rkt)- 与init系统集成的应用程序容器运行时,与docker等其他容器格式兼容,并支持像kvm这样的替代执行引擎. 
-   [海藻文件系统](https://github.com/chrislusf/seaweedfs)- 快速,简单和可扩展的分布式文件系统,具有o(1)磁盘寻道功能. 
-   [shell2http](https://github.com/msoap/shell2http)- 通过http服务器执行shell命令(用于原型设计或远程控制). 
-   [卡](https://github.com/intelsdi-x/snap)- 强大的遥测框架. 
-   [告密者](https://github.com/lucasgomide/snitch)- 当有人通过tsuru部署任何应用程序时,通知您的团队和许多工具的简单方法. 
-   [叠起](https://github.com/pressly/sup)- 堆叠起来,一个超级简单的部署工具 - 只需unix  - 把它想象成一个服务器网络的"make". 
-   [syncthing](https://syncthing.net/)- 开放,分散的文件同步工具和协议. 
-   [tenyks](https://github.com/kyleterry/tenyks)- 面向服务的irc bot使用redis和json进行消息传递. 
-   [术语知多少](https://github.com/crazcalm/term-quiz)- 为您的终端进行测验. 
-   [TOTO](https://github.com/blogcin/ToTo)- 使用Go语言编写的简单代理服务器,可与浏览器一起使用. 
-   [toxiproxy](https://github.com/shopify/toxiproxy)- 代理模拟自动化测试的网络和系统条件. 
-   [鹤](https://tsuru.io/)- 可扩展的开源平台作为服务软件. 
-   [VFLOW](https://github.com/VerizonDigital/vflow)- 高性能,可扩展和可靠的ipfix,sflow和netflow收集器. 
-   [websysd](https://github.com/ian-kent/websysd)- 基于网络的流程管理器(如马拉松或新贵). 
-   [惠灵顿](https://github.com/wellington/wellington)-  sass项目管理工具,用sprite函数(如指南针)扩展语言. 

# 资源

_在哪里发现新的图书馆. _

## 基准

-   [autobench](https://github.com/davecheney/autobench)- 比较不同版本之间性能的框架. 
-   [去基准测试应用程序内](https://github.com/mrLSD/go-benchmark-app)- 强大的http基准测试工具,可以混合使用wrk和围攻工具. 收集基准和比较结果的统计数据和各种参数. 
-   [去的基准](https://github.com/tylertreat/go-benchmarks)- 很少有其他的微基准. 比较一些语言功能和其他方法. 
-   [去-HTTP-路由标杆](https://github.com/julienschmidt/go-http-routing-benchmark)- 去http请求路由器基准和比较. 
-   [走型断言基准](https://github.com/hgfischer/go-type-assertion-benchmark)- 进行类型断言的两种方式的天真性能测试. 
-   [去的web框架,基准](https://github.com/smallnest/go-web-framework-benchmark)- 去web框架基准. 
-   [go_serialization_benchmarks](https://github.com/alecthomas/go_serialization_benchmarks)- 去序列化方法的基准. 
-   [gocostmodel](https://github.com/PuerkitoBio/gocostmodel)- 走向语言的基本操作基准. 
-   [golang-微基准测试](https://github.com/amscanne/golang-micro-benchmarks)- 微型基准的小集合. 目的是比较一些语言功能与其他人. 
-   [golang-SQL标杆](https://github.com/tyler-smith/golang-sql-benchmark)- 流行的go数据库/ sql实用程序的基准集合. 
-   [gospeed](https://github.com/feyeleanor/GoSpeed)- 去计算语言结构速度的微型基准. 
-   [kvbench](https://github.com/jimrobinson/kvbench)- 关键/价值数据库基准. 
-   [天网](https://github.com/atemerev/skynet)-  skynet 1m线程microbenchmark. 
-   [SPEEDTEST调整大小](https://github.com/fawick/speedtest-resize)- 比较go语言的各种图像调整大小算法. 

## 会议

-   [资本去](http://www.capitalgolang.com)- 华盛顿特区,美国
-   [dotgo](http://www.dotgo.eu)- 法国巴黎
-   [gocon](http://gocon.connpass.com/)- 日本东京
-   [golab](http://golab.io/)- 佛罗伦萨,意大利
-   [golanguk](http://golanguk.com/)- 伦敦,英国
-   [gopherchina](http://gopherchina.org)- 上海,中国
-   [gophercon](http://www.gophercon.com/)- 丹佛,美国
-   [gophercon巴西](https://gopherconbr.org)- 弗洛里亚诺波利斯,br
-   [gophercon迪拜](http://www.gophercon.ae/)- 迪拜,阿联酋
-   [gophercon欧洲](https://gophercon.is/)- 雷克雅未克,冰岛
-   [gophercon印度](http://www.gophercon.in/)- 浦那,印度
-   [gophercon俄罗斯](https://www.gophercon-russia.ru)- 莫斯科,俄罗斯
-   [gophercon新加坡](https://gophercon.sg)- 新加坡枫树商务城
-   [gothamgo](http://gothamgo.com/)- 美国纽约市

## 电子书

-   [去开发者的笔记本](https://leanpub.com/GoNotebook/read)
-   [在go中编程的介绍](http://www.golang-book.com/)
-   [用golang构建web应用程序](https://www.gitbook.com/book/astaxie/build-web-application-with-golang/details)
-   [与去建设web应用程序](https://www.gitbook.com/book/codegangsta/building-web-apps-with-go/details)
-   [去训练营](http://golangbootcamp.com)
-   [gobooks](https://github.com/dariubs/GoBooks)- 一本精选清单. 
-   [学习去](https://www.miek.nl/downloads/Go/Learning-Go-latest.pdf)
-   [网络编程与去](https://jan.newmarch.name/go/)
-   [去编程语言](http://www.gopl.io/)
-   [Web应用程序去反教科书](https://github.com/thewhitetulip/web-dev-golang-anti-textbook/)

## 地鼠

-   [去,鼠矢量](https://github.com/keygx/Go-gopher-Vector)- 去gopher矢量数据[.ai,svg.]
-   [地鼠,徽标](https://github.com/GolangUA/gopher-logos)- 可爱的Gopher标志
-   [鼠贴纸](https://github.com/tenntenn/gopher-stickers)
-   [鼠矢量](https://github.com/golang-samples/gopher-vector)
-   [gophericons](https://github.com/shalakhin/gophericons)
-   [gopherize.me](https://github.com/matryer/gopherize.me)- 自我炫耀
-   [地鼠](https://github.com/ashleymcnamara/gophers)-  ashley mcnamara的地鼠作品
-   [地鼠](https://github.com/egonelbre/gophers)- 免费的地鼠
-   [地鼠](https://github.com/rogeralsing/gophers)- 随机地鼠图形
-   [地鼠](https://github.com/sillecelik/go-gopher)- 地鼠amigurumi玩具模式

## 聚会

-   [去语言nyc](https://www.meetup.com/golanguagenewyork/)
-   [去伦敦用户组](https://www.meetup.com/Go-London-User-Group/)
-   [去多伦多](https://www.meetup.com/go-toronto/)
-   [去亚特兰大的用户组](https://www.meetup.com/Go-Users-Group-Atlanta/)
-   [gobridge,旧金山,ca](https://www.meetup.com/gobridge/)
-   [gojakarta](https://www.meetup.com/GoJakarta/)
-   [golang阿姆斯特丹](https://www.meetup.com/golang-amsterdam/)
-   [golang阿根廷](https://www.meetup.com/Golang-Argentina/)
-   [golang班加罗尔](https://www.meetup.com/Golang-Bangalore/)
-   [golang belo horizo​​nte  - 巴西](https://www.meetup.com/go-belo-horizonte/)
-   [golang波士顿](https://www.meetup.com/bostongo/)
-   [golang dc,arlington,va](https://www.meetup.com/Golang-DC/)
-   [golang dorset,英国](https://www.meetup.com/golang-dorset/)
-   [golang以色列](https://www.meetup.com/Go-Israel/)
-   [golang joinville  - 巴西](https://www.meetup.com/Joinville-Go-Meetup/)
-   [golang lima  - 秘鲁](https://www.meetup.com/Golang-Peru/)
-   [golang lyon](https://www.meetup.com/Golang-Lyon/)
-   [golang墨尔本](https://www.meetup.com/golang-mel/)
-   [golang山景](https://www.meetup.com/Golang-Mountain-View/)
-   [golang纽约](https://www.meetup.com/nycgolang/)
-   [golang巴黎](https://www.meetup.com/Golang-Paris/)
-   [golang浦那](https://www.meetup.com/Golang-Pune/)
-   [golang新加坡](https://www.meetup.com/golangsg/)
-   [golang斯德哥尔摩](https://www.meetup.com/Go-Stockholm/)
-   [golangsãopaulo  - 巴西](https://www.meetup.com/golangbr/)
-   [Golang温哥华,BC](https://www.meetup.com/golangvan/)
-   [golangмосква](https://www.meetup.com/Golang-Moscow/)
-   [golangпитер](https://www.meetup.com/Golang-Peter/)
-   [伊斯坦布尔golang](https://www.meetup.com/Istanbul-Golang/)
-   [西雅图去程序员](https://www.meetup.com/golang/)
-   [乌克兰golang用户组织](https://www.meetup.com/uagolang/)
-   [犹他州去用户组](https://www.meetup.com/utahgophers/)
-   [女性谁 - 去旧金山,约](https://www.meetup.com/Women-Who-Go/)

_在这里添加你的城市/国家的组(发送**PR**)_

## 推特

-   [@golang](https://twitter.com/golang)
-   [@golang_news](https://twitter.com/golang_news)
-   [@golangflow](https://twitter.com/golangflow)
-   [@golangweekly](https://twitter.com/golangweekly)

## 网站

-   [真棒去@libhunt](https://go.libhunt.com)- 你的去工具箱. 
-   [真棒远程工作](https://github.com/lukasz-madon/awesome-remote-job)- 精心制作的远程工作清单. 他们中的很多人都在寻找黑客. 
-   [真棒,迷死](https://github.com/bayandin/awesome-awesomeness)- 其他令人惊叹的名单清单. 
-   [flipboard  - 去杂志](https://flipboard.com/section/the-golang-magazine-bVP7nS)- 收集文章和教程. 
-   [去博客](http://blog.golang.org)- 官方去博客. 
-   [去挑战](http://golang-challenge.org/)- 通过解决问题并获得专家的反馈来学习. 
-   [去论坛](https://forum.golangbridge.org)- 论坛去讨论. 
-   [在5分钟内](https://www.goin5minutes.com/)-  5分钟的屏幕录像专注于完成一件事. 
-   [去项目](https://github.com/golang/go/wiki/Projects)- 在社区维基上的项目列表. 
-   [去报告卡](https://goreportcard.com)- 你的包裹的报告卡. 
-   [gocryforhelp](https://github.com/ninedraft/gocryforhelp)- 收集需要帮助的项目. 开始你的开源方式的好地方. 
-   [godoc.org](https://godoc.org/)- 开源go软件包的文档. 
-   [golang流](https://golangflow.io)- 发布更新,新闻,软件包等等. 
-   [golang新闻](https://golangnews.com)- 关于编程的链接和新闻. 
-   [golang显卡](https://github.com/mholt/golang-graphics)- 收集图像,图形和艺术. 
-   [golang螺母](https://groups.google.com/forum/#!forum/golang-nuts)- 去邮件列表. 
-   [谷歌加社区](https://plus.google.com/communities/114112804251407510571)-  #golang爱好者的Google +社区. 
-   [地鼠社区聊天](https://invite.slack.golangbridge.org)- 加入我们新的松鼠社区,寻找地鼠[了解它是如何来的](https://blog.gopheracademy.com/gophers-slack-community/)). 
-   [gowalker.org](https://gowalker.org)- 去项目API文档. 
-   [justforfunc](https://www.youtube.com/c/justforfunc)-  youtube频道致力于编程语言提示和技巧,由francesc campoy主持[@francesc](https://twitter.com/francesc). 
-   [R / golang](https://www.reddit.com/r/golang)- 关于去的消息. 
-   [趋势今天在github上去仓库](https://github.com/trending?l=go)- 找到新的图书馆的好地方. 

### 教程

-   [去一趟](http://tour.golang.org/)- 互动之旅. 
-   [用golang构建web应用程序](https://github.com/astaxie/build-web-application-with-golang)-  golang电子书介绍如何用golang构建一个web应用程序. 
-   [建设去使用杜松子酒的Web应用程序和微服务](https://semaphoreci.com/community/tutorials/building-go-web-applications-and-microservices-using-gin)- 熟悉杜松子酒并了解它如何帮助您减少样板代码并构建请求处理管道. 
-   [游戏与去](http://gameswithgo.org/)- 一个视频系列教学编程和游戏开发. 
-   [以身作则](https://gobyexample.com/)- 动手介绍去使用带注释的示例程序. 
-   [去作弊表](https://github.com/a8m/go-lang-cheat-sheet)- 去参考卡. 
-   [去数据库/ SQL教程](http://go-database-sql.org/)- 对数据库/ sql的介绍. 
-   [golangbot](https://golangbot.com/learn-golang-series/)- 开始编程的教程. 
-   [hackr.io](https://hackr.io/tutorials/learn-golang)- 学习Golang编程社区提交和投票的最佳在线golang教程. 
-   [如何使用godog进行行为驱动的开发](https://semaphoreci.com/community/tutorials/how-to-use-godog-for-behavior-driven-development-in-go)- 开始使用godog  - 构建和测试go应用程序的行为驱动开发框架. 
-   [与去工作](https://github.com/mkaz/working-with-go)- 介绍去找有经验的程序员. 
-   [你的基本去吧](http://yourbasic.org/golang)- 大量的教程和如何
