该文件夹下存放mpv的脚本

| 脚本名 | 简要说明 |
| --- | --- |
| autoload.lua | 自动加载同级目录的文件 |
| cycle_adevice.lua | 快捷键切换音频 |
| ontop_playback.lua | 仅在播放时启用置顶 |
| open_file.lua | 快捷键载入文件 |
| osc_lazy.lua | 增强OSC界面 |
| playlistmanager.lua | 高级播放列表 |
| Thumbnailer*.lua (2) | 缩略图引擎 |

所有脚本均无预绑定的静态键位，查看 [input.conf](../input.conf)  的"LUA脚本"部分示例参考  
playlistmanager.lua存在动态绑定键位，查看对应配置文件 [playlistmanager.conf](../script-opts/playlistmanager.conf) 的相关部分

所有脚本除 **缩略图引擎** 外均可独立使用，该例外需要搭配 **增强OSC界面** 或 [Thumbnailer_OSC.lua](https://github.com/deus0ww/mpv-conf/tree/master/scripts) 使用
