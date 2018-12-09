# node-server
> nodejs 实现后端服务器

- routes 针对同不同url进行处理
- routePath  解析url得到pathname，和routes中url进行匹配，判断handleFn是否存在，不存在则当做静态文件处理，
- 若存在则在handleFn进行处理，POST数据通过 req.on('data', function)进行处理
- 调用  parseBody 解析POST数据


- req.query 调用 GET 数据
- req.body 调用 POST 数据
