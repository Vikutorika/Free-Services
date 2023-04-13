# Free Services

- 机场白嫖推荐走这里 https://airports.share4nothing.cf/

## PaaS服务

- Railway https://railway.app 一个月21天（比heroku好用但是又类似，改了以后就是好死好吧，不推荐）
- Heroku https://heroku.com 改了Pricing去掉了免费服务，之前还有一系列改动如去掉免费psql之类的，反正越来越恶心，好死（不推荐）
- Divio https://divio.com 配置为 `512MB + 5G存储 + 5G备份 + 1G数据库 + 10G流量`，地区只有北美，**无自定义域名，需要信用卡**，感觉不太好用
- Patr https://patr.cloud 免费额度5$，可开 `1vCPU + 512MB` 存储未知（青龙可以放上面跑），不支持自定义域名（可以用Vercel反代解决[文档见此](https://bili33.top/posts/vercel-reverse-proxy/)），**30分钟无访问自动重启容器**
- Koyeb https://www.koyeb.com 月免费5.5$，可开 `1vCPU + 512MB + 5GB` （或者折半开两个实例），支持自定义域名（1个），就体验来说不好，**要求每14天内登陆一次该平台否则暂停容器**
- zeabur http://zeabur.com 超级推荐，服务器是台北的GCP，之前在Twikoo群里见到过老板，目前在给人家平台排bug，**国人做的，别滥用人家的**

## 托管服务？（不知道该叫啥了）

- Vercel https://vercel.com 这个应该都知道吧……
- Netify https://www.netlify.com 类似于Vercel
- Cloudflare Pages https://cloudflare.com 自带的域名被墙，要用自定义域名
- Replit https://repl.it 一个在线IDE，但是可以通过高频率访问达到保活的目的，个人账户配置为 `0.5vCPU + 512MB RAM + 1GB 存储`（可以试试去白嫖它家的EDU服务 `2vCPU + 2GB RAM + 1GB 存储`，一开始不会让你验证东西的，只不过可能用一段时间就跟你说要验证，不验证的话额度跟个人账户一样）

## 服务器

> **大的（Azure、GCP之类的）就不说了，说些小众的**

- Linuxone https://linuxone.cloud.marist.edu IBM家的服务器，架构是`s390x`，对服务器占用的限制看得很严，我之前编译个东西都给我封了，注册信息随便填，强制公私钥链接（就是不能账号密码），3个月有效，据说邮件续期，配置见图
  - ![image](https://user-images.githubusercontent.com/28426291/230571639-7a050d26-ce45-425d-b19d-457b138b4073.png)

## 数据库

### Mongodb

- https://www.mongodb.com/cloud/atlas/register 官方的，512MB存储，RAM共享，可开地区很多（自己去看）

### Redis

- Upstash https://upstash.com/ 一个账号可开5个数据库（5个组织，每个组织一个），日2k条命令，也提供Kafka和qstash服务（这两个不会用）

## CDN

- Cloudflare https://cloudflare.com 大牌厂商懂得都懂
- Gcore https://gcore.com 好像被墙完了都……

## Office套件

- https://developer.microsoft.com/en-us/microsoft-365/dev-program 微软官方E5开发者版（应该都听说过吧，不过2023.4.5微软遣散了一堆白嫖党，反正我是没有幸免）

## Uptime服务

- 半夜临时想到的，睡醒了补

## Pages服务

- 也是半夜想的，睡醒了补

## 免费域名（虽然应该不差这个钱但我还是写上吧）

- 睡醒了补

## 有推荐

发送邮件到[GamerNoTitle@outlook.com](mailto:GamerNoTitle@outlook.com)，或者直接提交PR
