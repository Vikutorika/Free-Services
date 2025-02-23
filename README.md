# Free Services

- 机场白嫖推荐走这里 https://airports.share4nothing.cf/

## PaaS服务

- ~~Railway https://railway.app 一个月21天（比heroku好用但是又类似，改了以后就是好死好吧，不推荐）~~
- ~~Heroku https://heroku.com 改了Pricing去掉了免费服务，之前还有一系列改动如去掉免费psql之类的，反正越来越恶心，好死（不推荐）~~
- Divio https://divio.com 配置为 `512MB + 5G存储 + 5G备份 + 1G数据库 + 10G流量`，地区只有北美，**无自定义域名，需要信用卡**，感觉不太好用
- Patr https://patr.cloud 免费额度5$，可开 `1vCPU + 512MB` 存储未知（青龙可以放上面跑），不支持自定义域名（可以用Vercel反代解决[文档见此](https://bili33.top/posts/vercel-reverse-proxy/)），**30分钟无访问自动重启容器**
- Koyeb https://www.koyeb.com 月免费5.5$，可开 `1vCPU + 512MB + 5GB` （或者折半开两个实例），支持自定义域名（1个），就体验来说不好，**要求每14天内登陆一次该平台否则暂停容器**
- zeabur [https://zeabur.com](https://zeabur.com?referralCode=GamerNoTitle) 超级推荐，服务器是台北的GCP，需要每7天去平台打卡（貌似可以脚本解决但我还没写），可以支付宝，**国人做的，别滥用人家的**
- Render https://render.com 每月750小时免费（一个实例够一个月的），月流量1T

## 托管服务？（不知道该叫啥了）

- Vercel https://vercel.com 这个应该都知道吧……
- Netify https://www.netlify.com 类似于Vercel
- Cloudflare Pages https://cloudflare.com 自带的域名被墙，要用自定义域名
- ~~Replit https://repl.it 一个在线IDE，但是可以通过高频率访问达到保活的目的，个人账户配置为 `0.5vCPU + 512MB RAM + 1GB 存储`（可以试试去白嫖它家的EDU服务 `2vCPU + 2GB RAM + 1GB 存储`，一开始不会让你验证东西的，只不过可能用一段时间就跟你说要验证，不验证的话额度跟个人账户一样）~~ 

## 服务器

> **大的（Azure、GCP之类的）就不说了，说些小众的**

- Linuxone https://linuxone.cloud.marist.edu IBM家的服务器，架构是`s390x`，对服务器占用的限制看得很严，我之前编译个东西都给我封了，注册信息随便填，强制公私钥链接（就是不能账号密码），3个月有效，据说邮件续期，配置见图
  - ![image](https://user-images.githubusercontent.com/28426291/230571639-7a050d26-ce45-425d-b19d-457b138b4073.png)
  - 续费邮件 ![image](https://user-images.githubusercontent.com/28426291/235694279-6e61d8b2-e95c-40f5-b797-66747c06cea5.png)
  - 续费链接（仅供参考） https://linuxone.cloud.marist.edu/#/extendaccount?token=zSm3a6k3sqwXM0xkD5UknWpRjgZxch%2BgBNXp12mzKV7UnJRCO8F9kbSvufmrcrSt

## 数据库

### Mongodb

- https://www.mongodb.com/cloud/atlas/register 官方的，512MB存储，RAM共享，可开地区很多（自己去看）

### Redis

- Upstash https://upstash.com/ 一个账号可开5个数据库（5个组织，每个组织一个），日2k条命令，也提供Kafka和qstash服务（这两个不会用）
- RedisLabs https://app.redislabs.com/ 可开一个Redis数据库（从AWS、GCP、Azure选），限制30MB存储和30个同时连接数量

## CDN

- Cloudflare https://cloudflare.com 大牌厂商懂得都懂
- Gcore https://gcore.com 好像被墙完了都……

## Office套件

- https://developer.microsoft.com/en-us/microsoft-365/dev-program 微软官方E5开发者版（应该都听说过吧，不过2023.4.5微软遣散了一堆白嫖党，反正我是没有幸免）

## Uptime服务

- https://uptimerobot.com 算元老级别了吧，支持Status Page但不支持自定义域名，协议多样（http,tcp,udp等）
- https://betterstack.com/better-uptime 这个也挺不错，但是没有那么多协议，支持Status Page且有自定义域名

## Pages服务

- https://github.com 大名鼎鼎的Github Pages，非pro可以在公共仓库建立pages，pro用户公私均可（富哥V50），域名为`github.io`，某些地区会被阻断
- https://cloudflare.com Cloudflare Pahes服务，有点像vercel那种但不完全是，自带的`pages.dev`被墙，需自配域名
- https://gitee.com **国内的垃圾服务** 不支持自定义域名，自带域名`.gitee.io`，**有内容审查，需实名！！！**

## 有推荐？

发送邮件到[GamerNoTitle@outlook.com](mailto:GamerNoTitle@outlook.com)，或者直接提交PR
