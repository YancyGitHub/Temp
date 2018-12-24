下载完成后，解压并进入目录中，继续执行：

sudo cp * /usr/share/fonts

2. 执行以下命令,生成字体的索引信息：

sudo mkfontscale

sudo mkfontdir

3. 运行fc-cache命令更新字体缓存。

sudo fc-cache