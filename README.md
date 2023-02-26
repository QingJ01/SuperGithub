# SuperGithub
快速跳转GitHub镜像网站的猴油脚本

# 安装方式
[【推荐】Greasy Fork直接安装](https://greasyfork.org/zh-CN/scripts/460744-github-%E9%95%9C%E5%83%8F%E5%8A%A0%E9%80%9F%E8%AE%BF%E9%97%AE-%E5%85%8B%E9%9A%86%E5%92%8C%E4%B8%8B%E8%BD%BD)

[GitHub下载js](https://raw.githubusercontent.com/SQ8888/SuperGithub/main/SuperGithub.js)



# 本脚本只为学习使用，若因此造成任何损失本人概不负责

### 已知的GitHub镜像(含失效站点)
|                  域名                  | https | 克隆加速 | zip加速 | releases加速 | 主机服务商 | 服务器所在地 |   提供者   |
| :------------------------------------: | :---: | :------: | :-----: | :----------: | :--------: | :----------: | :--------: |
|          https://hub.sqyun.tk          |   ✓   |    ✓     |    ✓    |      ✓       | Cloudflare |     美国     |     SQ     |
| ~~http://github-mirror.bugkiller.org~~ |   ✗   |    ✓     |    ✗    |      ✓       |     ?      |     日本     |    未知    |
|          https://hub.njuu.cf           |   ✓   |    ✓     |    ✓    |      ✓       |    未知    |     美国     | SciHub Pro |
|          https://hub.yzuu.cf           |   ✓   |    ✗     |    ✓    |      ✓       | Cloudflare |     美国     | SciHub Pro |
|          https://hub.nuaa.cf           |   ✓   |    ✓     |    ✓    |      ✓       | Cloudflare |     香港     | SciHub Pro |

tips:如果你有好用的镜像站，也欢迎提供给我



### 更新日志

v1.0.0
1. 初始版本构架
2. 弹出页面再改版，支持手机浏览
4. 适配Github新UI样式

### 使用 Cloudflare 搭建Github镜像(实为代理)
[基础教程](https://github.com/EtherDream/jsproxy/tree/master/cf-worker)

只需要将基础教程中[index.js](https://raw.githubusercontent.com/EtherDream/jsproxy/master/cf-worker/index.js)的代码：
```
const ASSET_URL = 'https://etherdream.github.io/jsproxy'
```
改为
```
const ASSET_URL = 'https://github.com'
```
即可
