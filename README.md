<p align="center">
  <a href="https://ibb.co/XShYMy2"><img src="https://i.ibb.co/ChkPDJ1/1.jpg" alt="1" border="0"></a>
</p>
<h1 align="center">HI~这里是Gulugulu</h1>
<h1 align="center">好用的Web挖矿代理软件~ OwO</h1>
## 更新日志

```bigquery
2022-01-02 14:19   更新版本303（支持WEB）
2021-12-18 18:19   更新版本257（小白请无脑使用windows版本，QQ群下载，程序猿自行取用linux版）
2021-12-12 12:19   更新桌面版本
2021-12-08 17:44    2.3.1版本更新内容              
2021-12-07 11:11    2.2.2>>>优化了内存占用,去掉了一些无效打印,可以自定义抽水机名字 -devWorkerName
2021-12-07 09:10    2.2.1>>>修复无法指定端口的问题（测试的时候代码里面写死了）
2021-12-07 08:56    2.2>>>稳如老狗版本,代码重构完成
2021-12-06 14:30    2.1>>>修复一个bug
2021-12-06 13:53    2.0>>>代码全部重构。并且改为随机抽水
2021-12-06 01:35    1.0.2>>>增加了稳定性
2021-12-05 11:12    1.0.1>>>修复了大量矿机下map修改导致异常程序崩溃的bug
2021-12-05 05:07    1.0>>>修复了鱼池火币等子账户矿池子账户名过短导致程序崩溃的bug
2021-12-05 04:27    内测>>>增加了版本号,删除一些打印
```
## Liunx
```bash
git clone https://github.com/heishiqing/gulugulu.git
cd gulugulu 
然后运行gulugulu_web（注意要后台运行，不然会断开）
打开防火墙的18888端口，在网页上输入你的IP:18888，输入token，即可配置
```
### 后台运行时关闭

```bash
killall gulugulu
```
### 后台运行时查看
```bash
tail -f nohup.out
```
## 提示bash: git: command not found的先安装git
### ubuntu下
```bash
apt update
apt install git
```
### centos下
```bash
yum update
yum install git
```
## 提示bash: Permission denied的是没有权限
```bash
sudo chmod -R 777 gulugulu
```bash
```
## Windows下
```bash
运行gulugulu_web.exe
打开防火墙的18888端口，在网页上输入你的IP:18888，输入token，即可配置
```
# 参数说明
## 可以自定义矿池和本地端口 例如
```bash
抽水比例
抽水矿池（抽水去的矿池）
自定义矿机名（抽水工名字）
钱包地址
代理矿池（挖矿的矿池地址，官方的）
本地端口
```
## 重要说明

```bigquery
目前仅测试了ethermine，flexpool,鱼池，2miner，Hiveon别的矿池请自行测试,有什么问题可以提交git
推荐使用香港节点,flexpool和ethermine，2miner都可以到50ms以内,延迟率在0.5%-0.9%之间
```
## 推荐VPS
```bigquery
企鹅下发自查文书，赶快更换VPS，一直企鹅，亚马逊，谷歌，微软都会查中转行为

推荐一：衡天云，刚购买，考察中，个人资料有实名一栏，但是实际不需要实名就可以使用
https://sourl.cn/A9SLmG 

===============================

推荐二：   （小算力性价比型，大算力不要买）
香港 VPS，不需要实名，支持windows和Linux
HK-香港VPS-1C1G-优化带宽-年付特价
￥199.00 CNY
地址 https://sourl.cn/zJezb7
注册以后，查询特价商品
```
QQ群872223284
<p align="center">
  <a href="https://ibb.co/rxc6RzR"><img src="https://i.ibb.co/VgQSczc/QQ-20220102172857.jpg" alt="QQ-20220102172857" border="0"></a>
</p>


