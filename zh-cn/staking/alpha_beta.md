# Wanchain星系共识Beta版的产品新增和参数改进

### 产品方面
* 新增[Wan Wallet桌面端轻钱包](https://github.com/wanchain/wan-wallet-desktop/releases)，委托人的WAN代币委托可在钱包中进行可视化操作，**目前只支持测试网络，请勿将主网WAN代币转入此钱包**；
* 新增[Wanchain Network Status](https://wanstats.net/)，为专业用户提供星系共识运行下Wanchain网络状态的可视化追踪平台；
* 改进[Wanchain PoS浏览器](http://testnet.wanscan.org/)，增加大量实用的跟踪信息和统计数据。

### 参数方面
* Slot时间由10秒缩短为5秒；
* Epoch时间由2天缩短为1天；
* 委托比率由1：5调升至1：10；
* 委托费率取值精度从百分之一提高到万分之一；
* docker镜像名称更新为：wanchain/client-go:2.0.0-beta.5；
* 启动参数和指令中的pluto, 更换为testnet。
