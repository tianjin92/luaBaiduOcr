# luaBaiduOcr
using Python flask to support Lua Baidu Ocr

使用方法：
Python 文件放在服务器


Lua 文件放到你的项目文件中
使用Python3

1. 使用 pip install Flask 安装 Flask
2. 运行 python 脚本 端口为 8090
3. 更改 main.lua 中的 API Key,Secret Key （具体获得请百度）
4. 更改 BaiduOcr.lua 中ip地址为你的服务器地址
5. 测试看看


Q&A:
在使用百度云过程中发现尽然无法访问api地址，最后发现是百度云dns有问题。手动改dns到114.114.114.114就可以正常使用了。
