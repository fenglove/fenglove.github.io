[Blog Website](https://blog.itcpay.com)

## What is the main blog? 
**Mainly introduce related technologies**

>Java (Spring boot/Spring cloud)
>
>Bigdata (Hadoop/Hbase/Spark/Flink)
>
>Rabbtimq/Mysql
>
>Docker
>
>Kubernetes
>
>EFK (Elasticsearch/Filebeat/Kafka)
>
>Nacos
>
>Tools (jenkins/gitlab/idea/maven)
>
>Tomcat/Jetty
>
>React/Vue

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
  icp: 粤ICP备xxxxxx号

github_banner:    # Modify github banner address
  enable: true
  permalink: https://github.com/fenglove

social:            # Edit social addresses and icons
  GitHub: https://github.com/fenglove || github
  E-Mail: mailto:xxxxxx@qq.com || envelope
#  Weibo: https://weibo.com || weibo
  QQ: tencent://message/?uin=xxxxxxxxx&Site=&menu=yes || qq

links:        # Modify recommended reading
  派|Pyker: https://www.ipyker.com
  echarts可视化库: https://echarts.baidu.com/index.html

avatar:
  url: /images/avatar.jpg      #Modify the blog avatar

reward:        #Modify the reward QR code
  wechatpay: /images/reward/wechatpay.png
  alipay: /images/reward/alipay.png

livere_uid: xxxxxxx==   # Modify to force the comment key, otherwise you can't manage the comment
```
