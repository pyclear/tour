《Go 语言之旅》是官方 Go Tour 的中文翻译版。
这份fork将代码运行的环境修改为docker，并禁止了自动打开浏览器，
你需要在docker容器运行之后手动大开浏览器输入localhost:3999
要安装到本地，请先安装docker，之后执行以下命令：

	$./run.sh
	

（如果安装过程中出现 `package` 或 `import`
字样的错误提示，那么说明依赖库的导入路径又挂了。
这时请猛戳 @OlingCat 并督促其解决= =||）

翻译贡献者名单：

	@qiansen138	#224
	@tiant16	#206 
	@ybi		#198
	@anamewin	#191

除特别声明外，go-tour 源码文件均采用 `LICENSE` 文件中BSD风格的授权许可分发。
