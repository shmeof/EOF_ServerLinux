# Linux
	Linux 目录结构
	http://www.cnblogs.com/CoderJYF/p/6092604.html
	
	安装 CentOS 后的系统配置及软件安装备忘
	http://www.cnblogs.com/liuyang1012525/p/5024377.html#sec-1-1

	Centos 安装Emacs
	http://www.cnblogs.com/dason-hu/articles/5947105.html

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
		sz –bey  （远端linux传输文件到本地win）
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
		
	阿里云端口配置：
		关于阿里云服务器中Tomcat的<Host name="localhost">中的localhost改为外网ip无法访问的问题
		http://blog.csdn.net/zhang41228/article/details/74457093
		
		
# 工具
		SecureCRT
		WinSCP
		
# 环境
## Python
## djangon
	
## spacemacs
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
		
	
	spacemacs完整教程
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
		
	
	

## git
	
	
	猴子都能懂的GIT入门
	http://backlogtool.com/git-guide/cn/intro/intro1_1.html
	图解Git
	https://marklodato.github.io/visual-git-guide/index-zh-cn.html
	Git book
	https://git-scm.com/book/zh/v2
	
## mysql安装：
	http://blog.csdn.net/wendellup/article/details/27671725
	http://blog.csdn.net/gongchenupc/article/details/68066990
	
	http://www.cnblogs.com/liuyi2614/p/6382183.html

## Web服务器：
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
		
## Servlet
	
## Java
	
## openresty
