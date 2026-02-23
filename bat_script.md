脚本名称：微信应用 windows 下多开

```bat
@echo off
REM 如果你想三开，就再复制一行 start 命令，以此类推
REM 版本更新可能导致脚本失效，因为 exe 的名称会发生改变，只需要手动修改脚本下文件名为正确的文件名即可
start "" "D:\Tool\...\Weixin.exe"
start "" "D:\Tool\...\Weixin.exe"
exit
```
