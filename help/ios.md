# [Maicloud 帮助中心](/README.md)

## iOS 使用帮助
[返回首页](/README.md)

## 下载和安装

1. 购买套餐后向管理员获取Apple ID，登录App Store，下载Shadowrocket （**不要登陆iCloud！！，下载完退出ID**）

## 配置服务器订阅

1. 登陆 [Maicloud Network 官网](http://www.maicloud.cc/)，在用户中心点击 iOS → 小火箭一键订阅 （**使用Safari浏览器**）

2. 如果点击小火箭一键订阅后没有反应，你可以手动配置订阅：  
登陆 [Maicloud Network 官网](http://www.maicloud.cc/)，复制订阅地址  
进入Shadowrocket，点击右上角加号
类型选择Subscribe，URL粘贴复制的订阅，然后点击完成

2. 在Shadowrocket软件中打开 **设置** - **服务器订阅** - **启动时更新**

## 启动代理
1. 多次点击延迟测试，然后在软件内选择一个节点（选择没有超时的），打开上方开关连接

2. 首次启动需要允许建立VPN连接

## 更新订阅
1. 如果你设置了启动时更新，软件会在每次启动时自动更新订阅

2. 手动更新订阅的方法：
点击服务器订阅地址（含有类似sub.maicloud.vip的东西）右侧按钮，然后点完成
3. 如果你的订阅无法更新，请删除所有的订阅和节点，然后重新配置订阅（重置订阅或者使用备用订阅地址）

## 注意事项
1. 你可以配合 <https://github.com/h2y/Shadowrocket-ADBlock-Rules> 来实现去广告，自动分流等功能

2. 如果连不上，请尝试切换线路，如果全部无法连接，请检查你的套餐，并尝试重启手机，检查是否允许Shadowrocket连接网络

3. “切换线路”，“切换节点”，“切换服务器”，在本文中含义相同

4. 出现问题你可以通过 **数据** - **删除全部节点**，然后重新配置

5. 如果遇到某些网站无法访问的情况，你可以把 **全局路由** 改成 **代理**  
但是这样会造成访问国内网站速度变慢，浪费流量，耗电变多，建议在用完后改成 **配置**，或者断开连接（不要乱选择其他模式）

5. 如有其他问题请[联系客服](https://ticket.maicloud.cc)

如果不想用软件自带的配置文件，你可以选择：  
国内用户访问海外：https://raw.githubusercontent.com/lhie1/Rules/master/Shadowrocket.conf  
海外用户访问国内：https://raw.githubusercontent.com/lhie1/Rules/master/Shadowrocket/Shadowrocket-cn.conf  