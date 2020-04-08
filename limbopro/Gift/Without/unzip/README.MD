![Quantumult x for limbopro][1]

## 毒奶预配置文件（unzip版）说明

0. 利用 Quantumult X 自带的 [配置文件] - [下载] 功能对 Quantumult X 各个模块即参数进行预配置；
1. 利用 NobyDa 贡献的脚本解锁🔓各项事务，VSCO，Termius，等；
2. 另外默认配置的是 🔓 美区App Store下载的 Tiktok；届时自己进 [QuantumultX] - [配置文件] - [编辑] - 找到 Tiktok 修改参数即可 
3. Surge/Clash 用户可以使用由毒奶提供的 订阅转换 API，亦能获得相同的效果；https://limbopro.xyz/archives/subconverter.html

## 本预配置文件所引用到的仓库
0. 在此毒奶对大家的付出表示感谢
1. [NobyDa](https://github.com/NobyDa/Script/tree/master) 脚本仓库
2. [ConnersHua](https://github.com/ConnersHua/Profiles/tree/master) 神机规则
3. [limbopro](https://github.com/limbopro/Profiles/tree/master/limbopro) 机场专线
4. [Qure](https://github.com/Koolson/Qure/tree/master/IconSet) 开源图标

## 关于策略及分流的说明
- **故障切换**：该策略组自动检测组内节点可用情况（surge 会切换选中最低延迟节点）；
- **机场专线**：主流机场域名分流规则，例如 N3RO ，你可使其请求走代理，直连等；
- **社交媒体**：国外社交媒体，如Twitter/Facebook/Instagram等，**流量消耗小，但需要稳定**；
- **苹果服务**：苹果服务相关分流规则；
- **Netflix**：鉴于大家喜欢看 Netflix；
- **其他国外流媒体**：如油管，P站等一切你可以想得到国外流媒体，**流量消耗大**；
- **广告拦截**：你可以选择让其 Reject 或者 代理 或者别的；
- **Final**： 排除以上已知的分流规则的其他未知；

* GEOIP,CN,DIRECT，默认中国大陆网站均走直连；

## 具体操作
### 第一步 ⏬ 下载 脚本仓库压缩包
1. https://github.com/NobyDa/Script/archive/master.zip
2. 复制上述并在 Safari 打开下载，打开下载的文件
3. 下载成功后，进入 [文件]App - [我的iPhone] - [下载项] 找到  Script-master.zip 并解压
4. 进入解压后的 文件夹 [Script-master]
5. 右上角 点击 [选择] - [全选]
6. 点击底部 中间类似 文件夹的按钮 📂 （移动）
7. 选择 [我的iPhone] - [Quantumult X] - [Scripts]
8. 点击 右上角 的 [移动] 按钮
9. 完成

### 第二步 ⏬ 下载 毒奶自用预配置文件（unzip版）

1. 复制 https://raw.githubusercontent.com/limbopro/Profiles/master/limbopro/Gift/Without/unzip/QuantumultX4limbopro.conf 预配置文件链接；
2. 进入 QuantumultX ，点击右下角 [三菱按钮]
3. 找到 [配置文件] 模块下的 [下载] 点击
4. 粘贴 刚刚复制的配置 [链接]，点击 右上角 [确定] 按钮
5. 确认，届时 QuantumultX 已添加 8个策略

### 第三步 生成并配置证书
1. 进入 QuantumultX ，点击右下角 [三菱按钮]
2. 找到 [MitM] 模块 - 生成并配置证书📄
3. 找到 [重写] 模块 - 开启按钮 🔘
4. 找到 [MitM] 模块 - 开启按钮 🔘

## Faq 
### 备份你的机场订阅链接🔗
1. 进入 QuantumultX ，点击右下角 [三菱按钮]
2. 找到 [配置文件] 模块 - 点击 [编辑] - 找到 [server_remote] 
3. 复制 [server_remote] 下方的机场订阅链接🔗 存到某处备用
4. 届时 恢复时 重新再 [server_remote] 下方 粘贴即可

### 使用毒奶预配置文件后的一些检查
1. 如果出现错误提示，不要慌
2. 进入 QuantumultX 主界面 - 各个图标点一下 看一下
3. 熟悉一下

## 最后 BTW
如果以后有更新的话，你也会驾轻就熟；另外，希望大家会看 Quantumult X 的日志；

### 进阶玩法
https://limbopro.xyz/archives/3846.html

[1]: https://raw.githubusercontent.com/limbopro/Profiles/master/limbopro/Gift/Without/unzip/Quantumult%20X%20for%20limbopro.jpg
