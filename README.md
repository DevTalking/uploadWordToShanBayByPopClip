# 将选中的单词上传至扇贝单词词库
Upload select word to ShanBay library by PopClip extension.

技巧：通过PopClip将选中的单词上传至扇贝单词词库
平台：Mac
插件下载：https://github.com/DevTalking/uploadWordToShanBayByPopClip.git
要点：
1.解压通过上面的链接下载的压缩包，然后继续解压uploadWordToShanBay.popclipext.zip文件。
2.鼠标右键点击uploadWordToShanBay.popclipext文件，选择显示包内容，用文本编辑器打开uploadWord.sh文件，替换脚本中的TOKEN，获取TOKEN的方式可参见Hum的文章http://sspai.com/35857。
3.因为扇贝查询单词id的API返回的是JSON格式的数据，所以在命令行中解析JSON数据要用到jq工具，打开终端，输入brew install jq命令安装jq，没有安装homebrew的同学可自行Google，安装了homebrew的同学在安装jq之前可能需要执行brew update命令更新一下brew管理的软件版本。
4.双击uploadWordToShanBay.popclipext文件安装PopClip插件。
