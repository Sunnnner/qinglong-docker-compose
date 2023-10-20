# qinglong-docker-compose
- 青龙(qinglong)与傻妞机器人(SillyGirl)docker-compose部署,并自动更新网站证书
- 修改以下内容为自己的
  ```yaml
  # 需要证书的域名
  - LETSENCRYPT_HOST=xx.com.cn
  # 自己的邮箱
  - LETSENCRYPT_EMAIL=xx@163.com
  # 自己域名
  - VIRTUAL_HOST=xx.com.cn
  ```
