# 额。。

自己整理的目录扫描字典，准确的说是dirsearch的目录扫描字典，因为字典里保留了8个带有/%EXT%类似的字典。

# 一个好的目录扫描字典能带来哪些好处？栗子：

- 很多nacos的/路径为404，访问/nacos/路径，才能访问nacos。
- 某系统/wx/目录下，是微信小程序的管理后台，且登录无验证码。
- 某系统/report/目录下，是月报，季度报和年报，存在未授权访问。
- 某系统/api/user/all，接口下未授权列出了系统的所有用户名及其加密后的密码。

# 优势对比

| 字典            | 是否维护？ | 字典大小精简？ | 对国内系统（组件）目录的支持？ |
|:-------------------|:--------:|:------:|:--------:|
| dirsearch字典      |    ✅     |   ❌    |    ❌     |
| 网上的字典 |    ❌     |   ❌    |    ❌     |
| 本字典           |    ✅     |   ✅    |    ✅     |
