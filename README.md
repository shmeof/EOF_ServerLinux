# Linux
	鸟哥的Linux私房菜
	http://linux.vbird.org/

	Linux 目录结构
	http://www.cnblogs.com/CoderJYF/p/6092604.html
	
	安装 CentOS 后的系统配置及软件安装备忘
	http://www.cnblogs.com/liuyang1012525/p/5024377.html#sec-1-1

	Centos 安装Emacs
	http://www.cnblogs.com/dason-hu/articles/5947105.html
	
	Linux中环境变量文件profile、bashrc、bash_profile之间的区别和联系
	http://blog.csdn.net/huangjin0507/article/details/45769217

	Centos操作：
		查看文件：cat filename
		查找目录/文件夹： find /（查找范围） -name '查找关键字' -type d
		查找文件： find /（查找范围） -name 查找关键字 -print

    yum：
		yum list java*
		yum list mysql*
		yum install mysql
		
	Windows如何压缩tar.gz格式
		http://www.cnblogs.com/jinjiangongzuoshi/p/3778926.html
		
	上传到Linux及从Linux下载文件：
		rz –bey （本地win上传文件到远端linux）
		sz –bey 文件名 （远端linux传输文件到本地win）
		http://blog.csdn.net/huaweitman/article/details/42169247

	linux访问外网代理：
		linux内网机器访问外网代理设置
		http://blog.csdn.net/u012454773/article/details/65441887
		centos中代理的设置
		http://www.cnblogs.com/piaomiao1314/p/centos-proxy.html
		
		临时启用代理，启动emacs：
			# export https_proxy=http://proxy_ip:proxy_port; emacs
			举例： export https_proxy=10.202.6.29:8443; emacs
			参考： http://blog.csdn.net/redguardtoo/article/details/7326702
		
	查看端口占用：
		netstat -an|grep 8000
		
	查看进程：
		top		
	
	查看操作说明（manual）：
		man 命令名字
		按"q"即可退出man界面
		
		试试：
			man man
			
	在Shell界面：
		Shift + PgUp
		Shift + PgDn
	在Man界面：
		PgUp
		PgDn
		
	回到上一次的目录
		cd -
		
	阿里云端口配置：
		关于阿里云服务器中Tomcat的<Host name="localhost">中的localhost改为外网ip无法访问的问题
		http://blog.csdn.net/zhang41228/article/details/74457093
		
		
	cat相关操作：
		cat -n 5 | tail 10 | head 3
		tail -n 3
		tail -n 10 error.log -f
		
	ps aux | grep tomcat
	netstat -apn
	ps aux | grep java
	
	ps aux | grep pid
	netstat -apn | grep 8080
	
	netstat -apn ：查看
	ps -aux ：查看进行信息
	lsof -i ：端口号查看某个端口是否被占用 
	
	.sh文件语法:
		linux 下 .sh 文件语法
		http://blog.sina.com.cn/s/blog_54f82cc201010hfz.html
	
	拷贝当前路径到剪切板：pwd|pbcopy
	将json数据格式化为json样式：cat xxx.json|python -m json.tool
# 工具
		SecureCRT
		WinSCP
		
# 环境
## Python
123456
	
## Java
	
	http://blog.csdn.net/nxstack/article/details/54380837
	http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html
	
## Djangon
	Django 教程
	http://www.runoob.com/django/django-tutorial.html

## Vim
	跟我一起学习VIM - vim插件合集
	http://blog.csdn.net/mergerly/article/details/51671890
	
## Spacemacs
	spacemacs操作：
		Spacemacs buffer, file, project and layout management
		http://v.youku.com/v_show/id_XMTM5NDI3NjQxMg==.html
		spacemacs-tutor
		http://v.youku.com/v_show/id_XMTI4MjY5ODIyOA==.html?spm=a2h0k.8191407.0.0&from=s1.8-1-1.2

	spacemacs安装：
		1、先安装好emacs
		http://www.linuxidc.com/Linux/2015-04/116351.htm
		2、再按以下链接配置好spacemacs
		http://book.emacs-china.org/#orgheadline73
	spacemacs中运行shell：
		1、根据以下链接配置好shell layer
		http://blog.csdn.net/csfreebird/article/details/53011171
		http://spacemacs.org/layers/+tools/shell/README.html
		2、快捷键：M-m ' 即可打开shell layer
		3、再按一次 M-m ' 即可关闭shell layer
	SecureCRT 下使用emacs， backspace被改成C-h的问题解决
		http://blog.csdn.net/ruglcc/article/details/7826758
	SecureCRT 修改显示颜色
		如何让secureCRT显示Linux的颜色 
		http://blog.chinaunix.net/uid-20696246-id-1892128.html
		Securecrt emacs/vi 代码无法高亮、无颜色
		http://www.cnblogs.com/justinzhang/p/4233319.html
		设置SecureCRT自定义颜色
		http://www.cnblogs.com/imsoft/p/SecureCRT.html
	spacemacs添加行号显示：
		.spacemacs文件中查找dotspacemacs-line-numbers。
		默认配置为：
		dotspacemacs-line-numbers nil
		修改为：
		dotspacemacs-line-numbers t
	spacemacs查看全部安装包：
		M-x list-packages
		点击进去看详情即可安装
	spacemacs中使用mysql：
		安装sql layer
		https://github.com/shmeof/spacemacs/tree/master/layers/%2Blang/sql
		快捷键： M-x sql-mysql
		
	
	spacemacs完整教程（推荐）
		http://book.emacs-china.org/#orgheadline1
		
	打开文件：
		快捷键：M-m f f
	在文件中查找/搜索内容：
		快捷键：
			C-s 搜索
			C-r 搜索上一个
	保存文件：
		快捷键：
			C-x C-s
	最近打开的文件：
		快捷键：M-m f r
		
	跳到打开文件的目录：
		快捷键：M-m f j
		
	跳到Home Buffer（即Spacemacs主页面）：
		快捷键：M-m b h
		
	跳到Scratch Buffer（可以用于测试或临时编码用）：
		快捷键：M-m b s
	
	在目录页面将目录变成可编辑模式（用于直接对目录列表的目录名或文件进行直接操作）：
		快捷键：M-m b w
		完成后，按C-c C-c即可完成编辑
	
	跳到上一个/下一个Buffer：
		快捷键：M-m b p
		快捷键：M-m b n
		
	列出内置布局：
		快捷键：M-m l o
		
	保存工作区间：
		快捷键：M-m 
	
	查找
		M-x grep 命令会在一组文件或者一个目录中查找所有text出现的地方。
		默认情况下，grep会在当前文件所属的目录下查找，
		grep -nH -e "ngx_http_ssl" *.c 会在当前目录的所有.c文件中查找ngx_http_ssl出现的地方，输出跟上面的输出类似，将光标定位到某一行再按回车会跳转到该行。
	
		
	C-x 0 关闭当前窗口
	C-x 1 只保留当前窗口
	C-x o 切换窗口
	
	M-< 页首
	M-> 页尾
	M-f 前进一个单词
	M-b 后退一个单词
	行移：C- p n
	字符：C- b f
	首尾：C- a e
	行数：M-g M-g 行数
	
	选中段落：M-h
	开始选择：C-@
	复制：M-w
	剪切：C-w
	粘贴：C-y
	
	C-g 中断，放弃之前按的命令
	
	M- ;  注释一段代码
	M-/   补全（主要针对英文啦），比如，输入 fr ，将光标移到 fr 后面，执行 M-/ 将补全为 from
	
	列出代码中全部的方法名：
		快捷键：M-m s j 或 M-m s l （按M-m s 显示内容之后，选择jump-in-buffer）
	
	待处理：
		emacs和gnu global，搜索利器
		http://blog.csdn.net/lihenair/article/details/26583727

		搜索速度
			ag / pt（支持win） > ack > grep

## Git
	Git
	https://git-scm.com/book/zh/v1/%E8%B5%B7%E6%AD%A5

	猴子都能懂的GIT入门
	http://backlogtool.com/git-guide/cn/intro/intro1_1.html
	图解Git
	https://marklodato.github.io/visual-git-guide/index-zh-cn.html
	Git book
	https://git-scm.com/book/zh/v2
	
	在Github上下载单个文件夹
		方法一：
			DownGit
			https://minhaskamal.github.io/DownGit/#/home
		方法二：
			作者：gece
			链接：https://www.zhihu.com/question/25369412/answer/96174755
			来源：知乎
			著作权归作者所有。商业转载请联系作者获得授权，非商业转载请注明出处。

			Git1.7.0以后加入了Sparse Checkout模式，这使得Check Out指定文件或者文件夹成为可能。具体实现如下：$mkdir project_folder
			$cd project_folder
			$git init
			$git remote add -f origin <url>
			上面的代码会帮助你创建一个空的本地仓库，同时将远程Git Server URL加入到Git Config文件中。 接下来，我们在Config中允许使用Sparse Checkout模式：$git config core.sparsecheckout true
			接下来你需要告诉Git哪些文件或者文件夹是你真正想Check Out的，你可以将它们作为一个列表保存在 .git/info/sparse-checkout 文件中。 例如：$echo “libs” >> .git/info/sparse-checkout
			$echo “apps/register.go” >> .git/info/sparse-checkout
			$echo “resource/css” >> .git/info/sparse-checkout
			最后，你只要以正常方式从你想要的分支中将你的项目拉下来就可以了：$git pull origin master
			具体可参考Git的Sparse checkout文档：http://schacon.github.io/git/git-read-tree.html#_sparse_checkout
			
	git分支
		git拉取远程分支并创建本地分支和Git中从远程的分支获取最新的版本到本地
		http://blog.csdn.net/jtracydy/article/details/53174175
		
	git常用命令：
		git fetch origin
		git pull
		git push
		git branch
		git checkout
		git add
		git commit
		git status
		
		查看远程仓库分支： git branch -r
		查看所有分支： git barnch -a
		
		在本地仓库创建分支： git branch 分支名
		切换到特定分支进行工作： git checkout 分支名
		
		在本地仓库建立分支并和远程仓库分支关联，同时本地切换到分支上进行工作： git checkout -b [分支名] [远程名]/[分支名]
	
## mysql安装：	
	推荐
	http://www.cnblogs.com/jimboi/p/6405560.html
	mysql安装成功后创建的超级用户'root'@'localhost'的密码会被存储在/var/log/mysqld.log
	
	ERROR 1820 (HY000): You must reset your password using ALTER USER statement before executing this statement.
	ERROR 1819 (HY000): Your password does not satisfy the current policy requirements
	http://blog.sina.com.cn/s/blog_a0d71a9d0102wlz3.html
	
	启动mysql： service mysqld start
	登录mysql：mysql -u root -p 
	端口是否打开：lsof -i:3306
	状态：service mysqld status
	日志：/var/log/mysqld.log
	查看进程：
	关闭进程： sudo kill -9 PID
	
	SELECT head_item, count(1) AS counts FROM raw_log GROUP BY head_item;
	
## Web服务器
### Tomcat
	Tomcat
	http://blog.csdn.net/justfy_it/article/details/70948926
	
	设置tomcat CLASSPATH
	http://www.runoob.com/servlet/servlet-environment-setup.html
	
	开启tomcat：
		/usr/local/tomcat/bin/startup.sh
		
	关闭tomcat：
		/usr/local/tomcat/bin/shutdown.sh
		
	查看tomcat：
		ps -ef | grep tomcat
			
### Nginx：
	
	
## Openresty

	http://jinnianshilongnian.iteye.com/blog/2190344
		
	yum install readline-devel pcre-devel openssl-devel gcc
		
## Servlet
	Servlet 教程
	http://www.runoob.com/servlet/servlet-tutorial.html

	
	

## RPC
### Thrift
	Centos 6.5 下安装Thrift
	http://blog.csdn.net/adparking/article/details/44621205
	Apache Thrift 配置环境（推荐）
	http://blog.csdn.net/isea533/article/details/48574687
	Apache Thrift 官方JAVA教程
	http://blog.csdn.net/isea533/article/details/48574961
	thrift 0.9.0
	http://running.iteye.com/blog/1983463	
	安装Thrift参考：
	http://shiyanjun.cn/archives/107.html
	
	报错：g++: Internal error: Killed (program cc1plus)
	编译Thrift的IDL编译器时，make的时候，错误提示：g++: Internal error: Killed (program cc1plus)
	http://www.cnblogs.com/573583868wuy/p/6799311.html
	sudo dd if=/dev/zero of=/swapfile bs=64M count=16 
	sudo mkswap /swapfile 
	sudo swapon /swapfile

	报错：src/generate/thrift-t_c_glib_generator.o: file not recognized
	http://blog.csdn.net/chenycbbc0101/article/details/71108166
	http://bbs.chinaunix.net/thread-4175420-1-1.html

	报错：
	./src/thrift/server/TNonblockingServer.h:43:33: error: event2/event_compat.h: No such file or directory
	./src/thrift/server/TNonblockingServer.h:44:33: error: event2/event_struct.h: No such file or directory
	http://blog.csdn.net/isea533/article/details/48574687
	https://github.com/libevent/libevent/releases/download/release-2.0.22-stable/libevent-2.0.22-stable.tar.gz

	报错：
	THeaderTransport.h:79: error: class ‘apache::thrift::transport::THeaderTransport’ does not have any field named ‘TVirtualTransport’
	src/thrift/transport/libthriftz_la-THeaderTransport.lo] Error 1
	先确认你的thrift是不是0.9.2版本，因为更新的版本make的时候可能出现上面的这个错误
	
	报错：
	../../../lib/cpp/.libs/libthriftnb.so: undefined reference to `evutil_make_socket_closeonexec'
	../../../lib/cpp/.libs/libthriftnb.so: undefined reference to `evbuffer_get_length'
	../../../lib/cpp/.libs/libthriftnb.so: undefined reference to `evbuffer_pullup
	collect2: ld returned 1 exit status
	http://www.cnblogs.com/zhaochunhua/p/7069054.html
	解决方案是：我的 libevent 安装在了 /usr/lib 下，只需要在 /usr/lib64 下将所有 /usr/lib 下的 libevent 文件软链接过去就行了。ln -s /usr/lib/libevent* /usr/lib64。
	
	错误：
	./src/thrift/cxxfunctional.h:108:28: tr1/functional: No such file or directory
	./src/thrift/cxxfunctional.h:111: error: `std::tr1' has not been declared
	./src/thrift/async/TAsyncChannel.h:41: error: ISO C++ forbids declaration of `function' with no type
	解决方法：
		出错,则根据出错信息修改#include <tr1/functional> 为#include <boost/tr1/tr1/functional> make &&make install 
		这个方法有点暴力，有更好方法的请提出建议。如添加编译参数。
	
	错误：		
	error: `TLSv1_1_method' was not declared in this scope
	http://blog.csdn.net/agul_/article/details/50998187
	
	生成*.thrift文件对应的代码时，提示：Service "fb303.FacebookService" has not been defined
	http://running.iteye.com/blog/1983463
			
	[Thrift]Apache Thrift入门Java实例
	http://blog.csdn.net/sunnyyoona/article/details/52606287
		
## Ant
	安装Ant：
		http://blog.csdn.net/ljg888/article/details/17331591
		jdk1.8.x及以上，使用：http://ftp.jaist.ac.jp/pub/apache/ant/binaries/apache-ant-1.10.1-bin.tar.gz
		jdk1.7.x及以下，使用：http://ftp.jaist.ac.jp/pub/apache/ant/binaries/apache-ant-1.9.9-bin.tar.gz
		
	错误：
		java.lang.UnsupportedClassVersionError: org/apache/tools/ant/launch/Launcher : Unsupported major.minor version 52.0
		ant与jdk的版本不对应
		http://www.cnblogs.com/lemon1991/p/6657496.html
	
## Maven
	安装Maven：
		http://www.cnblogs.com/debiao/p/6230053.html
		http://mirrors.hust.edu.cn/apache/maven/maven-3/3.5.0/binaries/apache-maven-3.5.0-bin.tar.gz
		
## log4j
	JavaWeb应用中初始化Log4j的两种方式
	http://www.cnblogs.com/Michaelwjw/p/6655490.html
	log4j.properties配置详解与实例-全部测试通过
	http://blog.csdn.net/qq_30175203/article/details/52084127

## 定时任务
	CentOS环境编写定时任务的方法
	http://www.iplaypy.com/linux/l6631.html
	
	使用Python crontab设置Linux定时任务
	http://www.linuxidc.com/Linux/2016-12/138058.htm
		
## Android
	【推荐】Centos 7 使用jenkins 打包android项目
	http://www.cnblogs.com/AwenDF/p/5912130.html
	
	错误提示：
		You have not accepted the license agreements of the following SDK components:
		[Android SDK Build-Tools 25.0.2, Android SDK Platform 25].
		You have not accepted the license agreements of the following SDK components:
		[Android SDK Platform 25].
	解决方案：
		在服务器上使用 gradle 打包 android 源码
		https://segmentfault.com/a/1190000008395219

	Linux中Jenkins+Git+Gradle自动化打包Android
	http://m.blog.csdn.net/ywl5320/article/details/75003972
	
## 代理服务搭建
	http://www.cnblogs.com/networking/p/4507673.html

## 机器学习

	Tensorflow
		基于Centos7的pip安装tensorflow
		http://blog.csdn.net/w12345_ww/article/details/52291055
		yum install python-devel libffi-devel openssl-devel
		yum install -y openssl openssl-devel
		yum install gcc
		yum install glibc-headers
		yum install gcc-c++
		yum install zlib-devel bzip2-devel openssl-devel ncurscs-devel sqlite-devel readline-devel tk-devel gcc make
		
		tensorflow-1.0.0-cp27-none-linux_x86_64.whl
		http://download.csdn.net/download/rockingdingo/9762565#comment		
		
	PaddlePaddle
		http://paddlepaddle.org/
		http://bit.baidu.com/Course/datalist/column/117.html
		http://bit.baidu.com/course/detail/id/137.html
		
		概念：
			机器学习：从数据中产生模型
			监督学习
			无监督学习
			样本
			数据集
			模型
			拟合
			
			假设函数（hypothesis function）
			损失函数（cost function）：如均方差损失函数（MSE）
			优化算法（最常见的是gradient descent算法，即梯度下降算法）
				三种梯度下降框架：

	
		
			
		
		
		
		
		
		
		
		
		
		
		
		
		
