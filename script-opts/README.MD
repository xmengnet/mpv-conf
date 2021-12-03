### 该文件夹下存放mpv脚本的对应设置文件  

通常脚本设置文件名与所属脚本文件同名，实际遵脚本开发者设定为准。  
脚本设置文件切勿美化格式（例如加入无意义的空格）；切勿在参数后注释（应单独另起一行写注释）；  
脚本及其设置文件可能不支持windows的CRLF换行（尝试更改为LF）。  
以上所述情况在自行修改的过程中都可能导致脚本设置文件（部分）失效。

以下为mpv内置脚本所使用的设置文件：
```
console.conf
osc.conf
stats.conf
ytdl_hook.conf
```

_为什么不在 mpv.conf 中用官方的mpv参数 `--script-opts=key1=value1,key2=value2,...`  
不嫌烦和乱的话完全没有问题，只有在脚本所需更改的选项数量极少的情况下，我才会使用。  
[#options-script-opts](https://mpv.io/manual/master/#options-script-opts)_
