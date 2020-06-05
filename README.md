## 启动应用

`node server.js 8888`

或者

`node server 8888`

## 添加路由

1. 编辑 server.js 文件，添加 if else
2. 重新运行 node server.js 8888

## 用node-dev工具打开服务器
//先下载工具包
npm install -g node-dev

//再输入命令
node-dev server.js 888

## 后台启动应用

touch log
`node server.js 8888 >log log 2>&1 &`
