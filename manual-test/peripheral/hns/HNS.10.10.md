---
HNS，海思网络子系统（Hisilicon Network Subsystem），主要是验证设备上网口的性能。
本用例验证的是XGE收发包后详细统计数据查询。

Hardware platform: D03 D05  
Software Platform: CentOS Ubuntu Debian 
Author: Vasily Fang <fangyuanzheng3@huawei.com>  
Date: 2017-11-15
Categories: Estuary Documents  
Remark:
---

# Dependency
```
  1.单板启动正常
  2.所有网口各模块加载正常
```

# Test Procedure
```bash
  1.网口up
  2.对端向单板发100个包
  3.多次输入命令: ethtool -l eth0
```

# Expected Result
```bash
  正确打印统计数据
```
