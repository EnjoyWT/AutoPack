# AutoPack
自动打包脚本[来源][1] ,这个版本是在原作者的基础上添加了自动上传至蒲公英的代码,邮件自动发送功能.以及一些简单的bash注释.
[1]:https://github.com/wangliang0585/xcode_shell-master

>在dandelion.sh文件配置相关选项.请确保你的蒲公英apikey,uKey的正确配置.

####使用方法:
代码内有相关介绍,详情看ipa-build,cocoapods-build

####注意: 
      1.电脑需要[安装jq][2](解析蒲公英返回结果使用).
      2.请确保你的蒲公英apikey,uKey的正确配置.
      3.邮件自动发送功能默认关闭.控制台输入参数 -m 即可开启.
      4.cocoapods-build依赖于ipa-build脚本.
      [2]:http://brew.sh/index_zh-cn.html


>qq邮箱收不到邮件时,找回邮件方法:邮箱首页-->自助查询(模块最底部)-->邮件查询-->进行白名单设置.
其他的邮箱如:126的是在垃圾邮箱内直接查找即可.


Todo:
1.公司邮箱(内网)的发送
  
  
欢迎issues,Pull request!
  
