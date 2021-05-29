# icpc-domjudge

原文请见：https://github.com/cn-xcpc-tools/cn-xcpc-docs

netboot: 网络安装与配置选手机

domserver: Domjudge 服务端的安装与配置

judgehost: Domjudge 评测端的安装与配置

cds: ICPC Tools 中的 Contest Data Server 工具，是使用其他工具的核心 API

resolver: 滚榜工具

presentation: 大屏幕工具链

coachview: 远程显示选手机桌面与摄像头的工具

icpc-live: 直播 layout 工具

board: 外榜

2021年4月份测试：<br>
judgehost使用domjudge7.3.2+ubuntu18.04<br>
domsever使用domjudge7.3.2+ubuntu server<br>
使用以上环境同样适用此教程

2021年5月：<br>
如果使用ubuntu16.04则domserver无法安装domjudge7.1.1及以上版本，因为ubuntu16.04的数据库版本以及php版本和domjudge所用到的版本不匹配，会出现语法报错，如果想挑战修改一下可以尝试。如果不想修改可以使用6.0.3版本（别的6.版本没有测试），亲测该版本可以。
