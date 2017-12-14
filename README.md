# ops_skill_summary
#### Bootstrapping
* [云霁装机工具](http://github.com/idcos/osinstall)
* kickstart
* cobbler
* rpmbuild/xen
* kvm
* lxc
* openstack
* cloudstack
* opennebula
* eucalyplus
* rhev

***

#### 自动配置管理工具
* capistrano
* chef
* puppet
* func
* salstack
* ansible
* rundeck
* cfengine
* rudder

***

#### 自动化构建和测试
* ant
* maven
* selenium
* pyunit
* qunit
* jmeter
* gradle
* phpunit

***

#### 应用以及性能监控
* 通用监控
    * 基于事件
        * cacti
        * nagios
        * zabbix
            * 模板: [点击进入模版大全](https://monitoringartist.github.io/zabbix-searcher/)   
    * 基于时间
        * grafana
        * mtop
        * mrtg
        * [monit](https://mmonit.com/)
        * graphite
* 性能监控
    * 流量分析
        * iptraf
            * 简介: 网络性能工具
        * nload
        * ifstat
        * iftop
            * 简介: 类似top的网络连接工具
        * ntop
        * mtr
        * vnstat
        * tcpdump
            * 简介: 网络抓包
    * 内存分析
        * smem
            * 简介: 高级内存报表工具
    * 性能分析
        * [tcpdive](https://github.com/fastos/tcpdive)
            * 简介: TCP优化监控工具
        * [tcprstat](https://github.com/Lowercases/tcprstat)
            * 简介: 响应时间统计工具
    * 综合分析
        * dstat
            * 简介: 多类型资源统计
        * atop(htop/top)
        * nmon
            * 简介: 类Unix系统性能监控
        * slabtop
            * 简介: 内核slab缓存信息
        * sar
            * 简介: 性能监控和瓶颈检查
        * sysdig
            * 简介: 系统进程高级视图
        * collectl
            * 简介: 性能监控工具
        * systemtap
        * Perf
* 应用监控
    * apm
        * [mmtrix](http://www.mmtrix.com/)
            * 简介: 见过的最全面的分析工具
        * [pinpoint](https://github.com/naver/pinpoint)
            * 简介: Java应用监控
        * [alibench](http://alibench.com/)
        * [cat](https://github.com/dianping/cat)
    * mysql
        * mytop
        * orzdba
        * percona-toolkit
        * maatkit
        * [percona-omm](https://www.percona.com/software/database-tools/percona-monitoring-and-management)
        * [innotop](http://www.percona.com/blog/2013/10/14/innotop-real-time-advanced-investigation-tool-mysql/)
        * [myawr](https://github.com/noodba/myawr)
        * [mysqlpcap](https://github.com/hoterran/tcpcollect)
            * 简介: SQL级别的监控
        * [orchestrator](https://github.com/outbrain/orchestrator)
            * 简介: TOP级别可视化
***

#### 微服务相关平台
* openshift
* cloud foundry
* kubernetes
* mesosphere

***

#### 常用进程管理工具
* [mmonit](http://mmonit.com/monit/documentation/monit.html)
* [supervisor](http://supervisord.org)
    * 简介: 线上已大面积使用
* [frigga](https://github.com/xiaomi-sa/frigga)
* [strongloop process manager](http://strong-pm.io/compare/)

***

#### 常用日志收集工具
* elk stack
    * 组件: elasticsearch, filebeat/logstash, kibana
* scribe
* graylog

***

#### 常用绘图相关工具
* rrdtool
* gnuplot

***

#### 数据可视化的工具
* zeppelin
* metabase
* heka
* redash
* superset

***

#### 常用的流量控制系统
* panabit
* [pcap analyzer](http://le4f.net/post/post/pcap-online-analyzer)
    * 说明: 在线数据包分析工具

***

#### 常用的安全检查工具
* chrootkit
* rkhunter

***

#### 常用开源平台即服务
* cloudify
* cloudfoundry
* openshift
* [Deis](http://www.deis.io/) 
* Docker
* CoreOS
* [Atomic](https://access.redhat.com/articles/rhel-atomic-getting-started)
* [snappy](http://www.ubuntu.com/cloud/tools/snappy)
* [rancheros](http://rancher.com)

***


#### 服务自动发现与注册
* etcd
* [smartstack](http://nerds.airbnb.com)

***

#### 持续集成审计与测试
* 通用应用
    * [go](http://www.go.cd)
    * jenkins
    * gitlab
    * [phabricator](http://phabricator.org/)
        * 简介: facebook代码审查工具
    * [spinnaker](http://spinnaker.io/)
    * [phpci](https://www.phptesting.org)
        * 简介: php代码持续集成工具
* APP应用
    * [fastlane](https://fastlane.tools/#tools)
    * [xcode_shell](https://github.com/webfrogs/xcode_shell.git)
    * [xctool](https://github.com/facebook/xctool.git)

***

#### 常用数据库运维与管理
* 磁盘压测
    * fio
    * iozone
    * iometer
        * 注意: 目前只适用于win
* 非关系数据库
    * redis
        * 扩展工具
            * [dynomite](https://github.com/Netflix/dynomite)
            * twemproxy
            * codis
                * 扩展工具
                    * codis+SSDB+Aerospike
            * redis cluster
        * 管理平台
            * [cacheCloud](https://github.com/sohutv/cachecloud
                * 简介: 搜狐开发, 云管理平台
    * memcache
        * 扩展工具
            * [mcrouter](https://github.com/facebook/mcrouter)
    * mongodb
        * 压力测试
            * [iibench&sysbench](https://github.com/tmcallaghan)
* 关系型数据库
    * mysql
        * 基准测试
            * mysqlsla
            * sql-bench
            * super smack
            * percona's tpcc-mysql tool
            * sysbench
        * 代理中间件
            * [dbproxy](https://github.com/SOHUDBA/SOHU-DBProxy)
                * 简介: 搜狐开发
            * [mycat](http://www.mycat.org.cn/)
            * [altas](https://github.com/Qihoo360/Atlas)
            * [cobar](https://github.com/alibaba/cobar)
            * [qceanus](https://github.com/58code/Oceanus)
                * 简介: 58同城开发
            * [kingshard](https://github.com/flike/kingshard)
        * 逻辑备份
            * mysqldump
            * mysqlhotcopy
            * mydumper
            * mysqldumper 
            * mk-parallel-dump/mk-parallel-restore
        * 物理备份
            * xtrabackup
            * lvm snapshot
        * 迁移管理
            * [flyway](https://flywaydb.org/)
                简介: 数据库迁移工具
            * sqllog
                简介: 表结构对比工具
***

#### 各位大佬运维管理平台
* https://github.com/hequan2017/autoops
* https://github.com/pengzihe/cmdb
* https://github.com/welliamcao/OpsManage
* https://github.com/hgz6536/opman-django
* https://github.com/voilet/cmdb
* https://github.com/roncoo/roncoo-cmdb
* https://github.com/xmdevops/fms

#### Copyright:
2017.12.14  (c) Limanman <xmdevops@vip.qq.com>
