# ceph 历史版本

具体可以通过如下搜索https://ceph.com/en/news/blog/search/?q=v0.30了解各个版本所作的修改

| 时间           |  版本名    |  版本       | 说明                |
| :--------      | :----      | :------     | :-----              |
| 2008年1月      |            | 0.1         | 在此版本中就有mds了 |
| 2010年5月      |            | 0.20        | mds: reduced memory utilization (still more to do!) |
| 2011年6月      |            | 0.30        | mds: misc clustered mds fixes <br>mds: misc rename journaling/replay fixes <br>mds: fixed flock deadlock when processes die during lock wait |
| 2012年6月3日   | Argonaut   | 0.48        |   |
| 2013年1月1日   | Bobtail    | 0.56        |   |
| 2013年5月7日   | Cuttlefish | 0.61        | mds: backpointers on all data and metadata objects <br> mds: faster fail-over <br>mds: many many bug fixes |
| 2013年8月14日  | Dumpling   | 0.67        | cephfs: open-by-ino support (for improved NFS reexport) |
| 2013年11月9日  | Emperor    | 0.72        | mds: many bug fixes and stability improvements |
| 2014年5月      | Firefly    | 0.80        | EC |
| 2014年10月     | Giant      | 0.87        | 单mds |
| 2015年4月      | Hammer     | 0.94        | Cephfs快照增强 |
| 2015年11月     | Infernalis | 9.x         |  |
| 2016年4月      | Jewel      | 10.x        | Cephfs稳定版，但快照和多活mds还不可用 <br> blueStore（实验性）<br> 多文件系统（实验性） |
| 2017年1月      | Kraken     | 11.x        |  |
| 2017年8月      | Luminous   | 12.x        | 多mds稳定 <br> 目录分片稳定 |
| 2018年6月      | Mimic      | 13.x        | 快照稳定 |
| 2019年3月      | Nautilus   | 14.x        | NFS-Ganesha |
| 2020年3月      | Octopus    | 15.x        |  |
| 2021年3月      | Pacific    | 16.x        | 多文件系统稳定 <br>多mds scrub稳定 <br>文件系统镜像可用 |
| 2022年4月      | Quincy     | 17.2.0      | 可以指定id创建fs，可以rename fs <br>FileStore在 Quincy 中已被弃用，BlueStore 成为 Ceph 的默认存储引擎 |
