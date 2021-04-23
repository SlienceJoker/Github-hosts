# Github-hosts
github的ipv4地址，加速github访问

### 立项原因
>写了githubPage，使用 `git push` 频繁报错，原因懂的都懂。每次报错后在 [IPAddress.com](https://www.ipaddress.com/) 查看github.com的IPV4地址经常发现变动，故添加此项目解决git命令痛点。

### 维护时间
>取决于笔者的网络环境，和git命令的便利程度。

### 维护终止
>目前笔者github访问基本正常，故终止维护。

### Note
> 添加hosts后注意刷新DNS，mac、Linux、Windows刷新DNS的指令各不相同。
> - mac
>   - `sudo dscacheutil -flushcache `
> - Windows
>   - `ipfonfig /flushdns`
> - Linux
>   - `sudo /etc/init.d/nscd restart`
>   - `sudo systemctl restart nscd`