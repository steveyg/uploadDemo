#### 入口为index.html, 随便一个静态服务器都可以,个人比较喜欢`browser-sync`, 即改即看效果

#### node端的代码在nodeServer下, 进入cd nodeServer, 然后npm install, 安装所有的依赖, node upload.js启动服务, 这样node环境就启动完成
#### *#注意:node的版本必须>=7.6*, 因为里面使用了async和await语法, 属于ES7规范, 低版本Node不支持