ubuntu科学上网配置（超级简单，一步到位）
​
Linux通过clash来实现科学滴上网配置教程，超级简单，2分钟实现。
​​​​


安装clash
如果你是x86_64系统，使用

wget https://github.com/clashdownload/Clash_for_Windows/releases/download/0.20.39/Clash.for.Windows-0.20.39-x64-linux.tar.gz
否则

wget https://github.com/clashdownload/Clash_for_Windows/releases/download/0.20.39/Clash.for.Windows-0.20.39-arm64-linux.tar.gz
安装完成之后选中压缩包，右键提取到此处。

进入提取完成之后的文件夹：Clash.for.Windows-0.20.39-x64-linux .tar.gz------->>>Clash for Windows-0.20.39-x64-linux,然后找到一个叫cfw的启动项。双击运行，如果无法运行>>>>>

在这个文件夹中打开终端，然后输入

/cfw
就可以看到clash的界面了。

然后进入这个界面（profiles）    将自己的URL粘贴到这个界面，然后点击Download.



然后打开系统的设置--->>>网络----->>>点击网络代理---->>>>选择手动，最后将设置改成如下：
127.0.0.1    7890
然后你就可以进入浏览器使用你的网络了。

​
