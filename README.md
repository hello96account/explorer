# EthExplorer (In Progress)

![EthExplorer Screenshot](http://i.imgur.com/NHFYq0x.png)

**执照**

GPL (see LICENSE)

**安装**

如果你还没有安装Git

如果你是 windows 

[Git地址]: https://git-scm.com/book/en/v2/Getting-Started-Installing-Git

你是 Centos 或Ubuntu

Centos

```
yum -y install git
```

Ubuntu

```
sudo apt-get install git
```



克隆本仓库

`https://gitee.com/aixuexichengxuyuan/eth-explore.git`

如果没有安装 nodejs ，请下载  

[nodejs官网]: https://nodejs.org/en/
[nodejs中文网]: http://nodejs.cn/



启动程序，自动下载依赖项

`npm start`

Then visit http://localhost:8000 in your browser of choice. You might get an error message:

`geth --rpc --rpccorsdomain "http://localhost:8000"`

Install [geth](https://github.com/ethereum/go-ethereum/wiki/Building-Ethereum "Geth install") if you don't already have it, then run the above command.

