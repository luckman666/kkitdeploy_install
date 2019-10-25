# 项目部署：

```
git clone https://github.com/luckman666/kkitdeploy_install.git
cd kkitdeploy_install && chmod 755 -R .
# 修改base.config里面的参数
./kkitdeploy.sh
```

部署完毕访问服务器IP即可，默认是80端口，登录认证设计的是假认证，直接点击登录即可。

重启项目：

```

# 关闭
docker-compose -f *.yml down -v 
# 启动
docker-compose -f *.yml up -d
```

相关详细介绍和使用教程我会在后面陆续更新。该项目波哥长期维护。如果项目有问题，请在公众号留言。

项目的更新及任何问题都会在公众号统一发布及回复，公众号也会给该项目设计专题栏目。以后将很少发布独立脚本，各类实用工具及脚本会统一由kkitDeploy版本迭代后更新。

你们的支持就是波哥的动力，请帮忙转发和start哦！

* * *

扫码关注，回复“全栈资料”会有

意想不到的收获哦


![image](https://upload-images.jianshu.io/upload_images/14069013-9e9bed4ff95ffc41?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)



**长按识别二维码关注我们**
