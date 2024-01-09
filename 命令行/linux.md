1. where are you？

   ```
   pwd #print working directory
   ```

2. ls命令

   ```
   ls
   ls [ options ] /path/to/directory
   ls -a	显示所有文件，包括隐藏文件
   ls -l	以长列表格式显示文件
   ls -la
   ls -F   区分Linux中的目录和文件,该-F选项向目录添加正斜杠(/)
   ```

3. 更改目录change directory

   ```
   cd /绝对地址 
   cd 相对地址/../..
   cd [dirName] 路径可以是绝对路径也可以是相对路径
   cd .. 跳回上一个目录
   cd .  当前目录
   cd ~  切换到主目录home
   cd -  回到上一次的目录
   cd /  回到主目录
   ```

4. 查看文件内容**concatenate** 

   ```
   cat [OPTION] [FILE]...
   ```

5. 辨识该文件的类型

   ```
   file filename
   file ./* 当前目录下所有文件类型
   ```

6. 粉碎文件

   ```
   shred 文件名
   ```

7. 创建新目录

   ```
   mkdir 目录名
   ```

8. 清空屏幕

   ```
   clear
   ```

9. 创建新用户

   ```
   useradd 用户名
   ```

10. 显示用户手册

   ```
   man 命令名
   ```

   