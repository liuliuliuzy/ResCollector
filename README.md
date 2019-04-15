# ResCollector

## 目前已修改：
修改了首页的搜索框大小<br>
修改了select框位置<br>
修改了模板文件和css文件名<br>
删除了模板html文件中无用的部分<br>
注释掉了mybt的settings.py中的`import sys`和`sys.path.append('C:/Users/13774/Desktop/ResCollector')`两行代码<br>
## 尚未解决的问题：
首页背景图片自适应大小且屏幕无滚动条<br>
搜索结果页面表格中限制结果字数显示<br>
谷歌浏览器首页刷新壁纸最多只能6次，这个可能是和浏览器有关<br>
可以考虑在结果页面增加提示信息，告诉用户搜索的过程是否已经结束，如果没结束，提示其刷新以更新结果<br>
## 如何使用
### Windows:
python版本要求：3.7<br>
确保位于项目根目录，运行命令，使用pip安装相关python依赖包<br>
`$ pip install -r requirements.txt`<br>
启动执行脚本<br>`$ runserver.bat`<br>
之后就可以用浏览器访问 http://127.0.0.1:8000/bt/<br>
输入你想要搜索的资源名称并选择相应种类之后，点击搜索，等待8秒就能跳转到结果页面<br>
一开始可能显示没有结果，手动刷新页面5~6次，就能看到所有的结果了。
