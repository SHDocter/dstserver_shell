自用<br>
文件在Windows编辑过 Windows每一行结尾是\n\r Linux是\n<br>
文件中行尾的\r替换为空白<br>
sed -i 's/\r$//' dst<br>
sed -i 's/\r$//' update<br>
sed -i 's/\r$//' update.cmd