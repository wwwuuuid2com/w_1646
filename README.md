# w_1646
Hellohao全网对象存储图床源码
<br/></br>
[下载地址](https://www.uuid2.com/1646.html "下载地址")
<br/></br>
<h3>源码简介：</h3>
<p>Hellohao图像托管程序这是一个基于多家对象存储源的SpringBoot开源图像托管程序。 目前已经支持对接本地、网易、阿里、又拍、七牛、腾讯、FTP、U-File、Backblaze、Minio等存储源。功能强悍，作者立志要把图像托管一步一步开发到极致。未来，Hellohao图像托管程序不仅仅是图床那么简单。<p>
<p>底层上将目前的JDK1.8升级为JDK11。 程序后端框架将升级Springboot框架，接口采用统一标准格式。 同时前端UI将完全重构采用Vue+iviewUI+Axios+router前后端分离式开发（至于最终是否采用前分离式部署，到时候再定）。 本次重构也将会在功能上实现突破。 同时，在完成重构后的，我着重把重心放在图像的整合和管理，解决图像量大的站点更加方便的查找 管理 归类后台图像。<p>
<p>多主题支持：炫酷壁纸、简约蓝白<p>
<p>支持 图片拖拽、截图软件直接(Ctrl+V)和图片URL地址上传。<p>
<p>图片定期暂存（到期自动删除）<p>
<p>支持画廊分享模式(用户可把自己当前上传的图片以图片集的形式批量分享给好友)<p>
<p>重复图片检测<p>
<p>支持上传者IP记录，并可配置IP黑名单操作<p>
<p>支持链接生成二维码。<p>
<p>支持开启/关闭API接口。<p>
<p>设置用户可用容量<p>
<p>扩容码生成（用户可使用扩容码进行容量扩充）<p>
<p>分发群组（配置用户群组，不同群组分发图片到不同对象存储）<p>
<p>首页背景动态/静态，以及简约模式设置<p>
<p>URL列表、缩略图。查看原图等功能。<p>
<p>图片鉴黄配置（开启后，每天固定时间进行非法图片监测）<p>
<p>游客、用户的上传管理<p>
<p>邮箱注册激活。<p>
<p>站点样式设置和上传规则配置等。<p>
<p>运行环境：JDK 1.8，MySQL5.5+<p>
<p>修改配置文件<p>
<p>打开 application.properties 修改 MySQL 和 服务器端口 等连接信息.<p>
<p>前提是你的服务器必须要有JDK1.8环境，和mysql数据库。<p>
<p>#JDK安装命令<p>
<p>把Tbed.jar和application.properties放到服务器你想存放的目录比如/home，注意这两个文件必须要在同一目录下不能分开。 依次运行如下命令：<p>
<p>启动项目<p>
<p>启动后访问地址为：http://localhost:8088 , 8088就是你配置server.port=8088的端口.<p>
<p>初始用户名：admin 初始邮箱：admin 初始密码admin<p>
<p>注意：上边的/home是你的jar包和application.properties文件放的目录。 项目运行起来不要关闭Xshell窗口，否则项目将不能访问。可以使用一些后台命令把项目锁定后台。如nohup或screen，推荐使用screen<p>
<h3>截图：</h3>
<img src="https://www.uuid2.com/wp-content/uploads/img/202109/00b30ba876.jpg" alt="Hellohao全网对象存储图床源码"><img src="https://www.uuid2.com/wp-content/uploads/img/202109/385b1d7472.jpg" alt="Hellohao全网对象存储图床源码">
