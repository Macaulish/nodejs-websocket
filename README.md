# nodejs-websocket
HTML5+NodeJs实现WebSocket即时通讯
参考：https://www.cnblogs.com/axes/p/3586132.html
	  https://segmentfault.com/q/1010000012930521

使用方法：
一、你可以使用git clone方法：
# 1，首先需要把项目clone到本地:
git clone git@github.com:Macaulish/nodejs-websocket.git
# 2，之后cd进项目目录(这里是nodejs-websocket)
cd nodejs-websocket
# 3，npm按照package.json安装相关插件
npm install
# 4，安装完毕后运行nodejs服务器
node ./webpack.js
# 5，这时候，双击打开game1.html，game2.html。点击game1.html中的方框，就可以在game2.html和服务器控制台中看到收发过来的消息了。



二、若本地安装
# 1，首先新建文件：
mkdir websocket_test
# 2，进入目录：
cd websocket_test
# 3，项目初始化：
npm init    
当然也可用npm init -f(这里的-f是强制安装，不然就会让你输入好多信息，诸如项目名，版本信息等等..可参考https://segmentfault.com/q/1010000012930521)
# 4，加载package.json中的安装包：
npm install
这一步是：通过npm install命令，按照package.json中的配置信息，安装需要的组件/插件
# 5,安装完毕后运行nodejs服务器
node ./webpack.js
# 6,这时候，双击打开game1.html，game2.html。点击game1.html中的方框，就可以在game2.html和服务器控制台中看到收发过来的消息了。
