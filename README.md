 **处理图床无法显示 `raw.githubusercontent.com` 的方法**

1. 在 [转换网站](https://ping.eu/nslookup)  （[备用网址](https://www.ipaddress.com/)）首页搜索raw.githubusercontent.com，查询真实的ip地址；
2. 鼠标右键点击桌面左下角的开始菜单，选择Windows PowerShell（管理员）
3. 在打开的 窗口中输入notepad, 回车, 会打开记事本
4. 选择文件 -> 打开
5. 在弹出的文件选择窗口中, 选择 C:\Windows\System32\drivers\etc\hosts
6. 在最底下添加该内容即可
7. 其实这样保存后就ok了，不放心就刷新一下dns—在小黑窗口（win+r -> cmd -> ipconfig/flushdns -> 回车）

添加内容

```bash
185.199.108.133 raw.githubusercontent.com
```

