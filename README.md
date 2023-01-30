# cors-test

用来看看CORS下会发生什么

1. main.go和html的静态文件服务跑在不同于源上

2. f12看看控制台

3. 改一下后端返回头看看

顺带发现 `Allow-Methods` 中不加 `POST` 也可以发，see: https://stackoverflow.com/questions/71409753/do-browsers-block-post-requests-if-post-isn-t-in-the-access-control-allow-method
