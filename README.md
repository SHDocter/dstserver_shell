# 自用<br>

文件在Windows编辑过 Windows每一行结尾是\n\r Linux是\n<br>
文件中行尾的\r替换为空白<br>
```
sed -i 's/\r$//' dst
sed -i 's/\r$//' update
sed -i 's/\r$//' update.cmd
```
dst->一键启动脚本<br>
update->一键更新脚本<br>
update.cmd->steamcmd命令<br>

## 路径

dst-> /<br>
update-> /<br>
update.cmd-> ~/ （root)<br>