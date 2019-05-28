[![](https://img.shields.io/badge/Hexo-brightgreen.svg?style=plastic)](https://hexo.io/)
[![](https://img.shields.io/badge/nexT-pyker-yellow.svg?style=plastic)](https://github.com/theme-next/hexo-theme-next)

[中文介绍](/README.md) | [Blog Website](https://blog.itcpay.com)

## Hexo theme should be ignored by the file
**After downloading to local, remember to change the .gitignore file to the following**

>.DS_Store
>
>Thumbs.db
>
>db.json
>
>*.log
>
>node_modules/
>
>public/
>
>.deploy*/

### Master configuration file _config.yml parameter
```yaml
$ vi <folder>/_config.yml
title: 别说你不在状态   #Edit blog title
description: 余生很长，记得善良。     #Modify description blogger description
url: https://blog.itcpay.com    # Modify your website address
deploy:
  repository: https://github.com/fenglove/fenglove.github.io    #Modify into your own github pages address
```
### Theme configuration file _config.yml parameter
```yaml
favicon:    # Edit website icon
  small: /images/favicon-16x16-next.png
  medium: /images/favicon-32x32-next.png
  apple_touch_icon: /images/apple-touch-icon-next.png
  safari_pinned_tab: /images/logo.svg

beian:      # Modify the record number 
  enable: true
  icp: 粤ICP备18075460号

github_banner:    # Modify github banner address
  enable: true
  permalink: https://github.com/fenglove

social:            # Edit social addresses and icons
  GitHub: https://github.com/fenglove || github
  E-Mail: mailto:826634596@qq.com || envelope
#  Weibo: https://weibo.com/viszhang || weibo
  QQ: tencent://message/?uin=xxxxxxxxx&Site=&menu=yes || qq

links:        # Modify recommended reading
  派|Pyker: https://www.ipyker.com
  echarts可视化库: https://echarts.baidu.com/index.html

avatar:
  url: /images/avatar.jpg      #Modify the blog avatar

reward:        #Modify the reward QR code
  wechatpay: /images/reward/wechatpay.png
  alipay: /images/reward/alipay.png

livere_uid: MTAyMC80NDM5Mi8yMDkyNA==   # Modify to force the comment key, otherwise you can't manage the comment
```
