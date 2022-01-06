<p align="center">
  <a href="https://ibb.co/XShYMy2"><img src="https://i.ibb.co/ChkPDJ1/1.jpg" alt="1" border="0"></a>
</p>
<h1 align="center">HI~这里是Gulugulu</h1>
<h1 align="center">好用的Web挖矿代理软件~ OwO</h1>
<h1 align="center">纯转发无开发费，开发费：0.1-5%=0.3%，5-10%=0.6%，10-20%=1%~ OwO</h1>
<h1 align="center"> <a href="https://t.me/+3NCHntWEQ6BhODc1">点我加入飞机群</a>!</h1>

## 更新日志

```bigquery
2022-01-06 04:30   更新版本（修复bug）
2022-01-02 14:19   更新版本（支持WEB）
2021-12-18 18:19   更新版本（小白请无脑使用windows版本，QQ群下载，程序猿自行取用linux版）
2021-12-12 12:19   更新桌面版本

```
## Liunx
```bash
git clone https://github.com/heishiqing/gulugulu.git
sudo chmod -R 777 gulugulu（获取权限）
cd gulugulu 
然后运行nohup ./gulugulu_web &（注意要后台运行，不然会断开）
cat  config.yml（这个命令可以查看token）
打开防火墙的18888端口，在网页上输入你的IP:18888，输入token，即可配置
(注意事项，不要使用360等浏览器，使用Chrome或微软Edge浏览器。 
第一次配置后，请修改Token，再请求配置页面，防止别人知道你的IP地址，更换你的抽水钱包)

### 后台运行时关闭

```bash
killall gulugulu

### 后台运行时查看
```bash
tail -f nohup.out

### 防火墙相关命令
1.防火墙打开
sudo ufw enable
2.防火墙重启
sudo ufw reload
3.打开想要的端口（以9000为例）
ufw allow 9000
4.查看本机端口使用情况
ufw status
5.关闭防火墙
sudo ufw disable

## 提示bash: git: command not found需要先安装git
### ubuntu下
```bash
apt update
apt install git

### centos下
```bash
yum update
yum install git

## 提示bash: Permission denied是没有权限
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
```bash
抽水比例   这里是百分比，填入数字1就是1%
抽水矿池  （抽水去的矿池，比方说可以把鱼池的抽去E池，）
自定义矿机名  （抽水工名字）
钱包地址  顾名思义，抽水的钱包地址
代理矿池  （你转发的矿池挖矿地址，官方的）
本地端口  矿工连接你服务器的端口，比方说222.222.222.222:5678，这里就写5678
```
## 其他说明

```bigquery
目前仅测试了ethermine，flexpool,鱼池，2miner，Hiveon别的矿池请自行测试,有什么问题可以提交git
推荐使用香港节点,flexpool和ethermine，2miner都可以到50ms以内,延迟率在0.5%-0.9%之间
```
## 推荐VPS
```bash
## 推荐一：衡天云，刚购买，考察中，个人资料有实名一栏，但是实际不需要实名就可以使用
https://sourl.cn/A9SLmG


## 推荐二：   （小算力性价比型，大算力不要买）
https://sourl.cn/zJezb7
香港 VPS，不需要实名，支持windows和Linux
HK-香港VPS-1C1G-优化带宽-年付特价
￥199.00 CNY
注册以后，查询特价商品
```

<p align="center">
  <a href="https://ibb.co/rxc6RzR"><img src="https://i.ibb.co/fknpzyz/QQ-20220102172857.jpg" alt="QQ-20220102172857" border="0"></a>
</p>


