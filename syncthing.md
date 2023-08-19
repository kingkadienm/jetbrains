1. 下载golang  
https://dl.google.com/go/go1.19.12.windows-amd64.msi
2. 配置gopath 环境变量
3. 下载syncthing
   ```
   git clone https://github.com/syncthing/syncthing.git
   ```
4. 进入syncthing目录 下载  goversioninfo 
```
 go get github.com/josephspurrier/goversioninfo/cmd/goversioninfo
```
5. 将goversioninfo 添加在环境变量里
6. 运行  go run build.go
7.  1. 修改图标 syncthing/gui/default/assets 按文件名修改对于图标
    2. syncthing/assets 修改对于图标
