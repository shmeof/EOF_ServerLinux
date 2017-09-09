# EOF_ServerLinux
## Linux
	Linux 目录结构
	http://www.cnblogs.com/CoderJYF/p/6092604.html

	Centos 安装Emacs
	http://www.cnblogs.com/dason-hu/articles/5947105.html

	Centos操作：
		查看文件：cat filename
		查找目录：find /（查找范围） -name '查找关键字' -type d
		查找文件：find /（查找范围） -name 查找关键字 -print

	yum：
		yum list java*
		yum list mysql*
		yum install mysql
		
	Windows如何压缩tar.gz格式
		http://www.cnblogs.com/jinjiangongzuoshi/p/3778926.html
		
	linux访问外网代理：
		linux内网机器访问外网代理设置
		http://blog.csdn.net/u012454773/article/details/65441887
		centos中代理的设置
		http://www.cnblogs.com/piaomiao1314/p/centos-proxy.html
		
	查看端口占用：
		netstat -an|grep 8000
		
	阿里云端口配置：
		关于阿里云服务器中Tomcat的<Host name="localhost">中的localhost改为外网ip无法访问的问题
		http://blog.csdn.net/zhang41228/article/details/74457093
		
		
## 工具
		SecureCRT
		WinSCP
		
## 环境
	### Python
	### djangon
		
	### spacemacs
		spacemacs操作：
			Spacemacs buffer, file, project and layout management
			http://v.youku.com/v_show/id_XMTM5NDI3NjQxMg==.html

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
		
		http://book.emacs-china.org
			
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
			
		C-x 0 关闭当前窗口
		C-x 1 只保留当前窗口
		C-x o 切换窗口

	### git
		
		
	### mysql安装：
		http://blog.csdn.net/wendellup/article/details/27671725
		http://blog.csdn.net/gongchenupc/article/details/68066990
		
		http://www.cnblogs.com/liuyi2614/p/6382183.html

	### Web服务器：
		Tomcat：
			http://blog.csdn.net/justfy_it/article/details/70948926
			
			设置tomcat CLASSPATH
			http://www.runoob.com/servlet/servlet-environment-setup.html
			
			开启tomcat：
				/usr/local/tomcat/bin/startup.sh
				
			关闭tomcat：
				/usr/local/tomcat/bin/shutdown.sh
				
			查看tomcat：
				ps -ef | grep tomcat
				
		Nginx：
			
	### Servlet
		
	### Java
		
	### openresty
	
