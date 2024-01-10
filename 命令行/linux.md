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

4. 查看文件内容**concatenate** （要是文本文档）

   **cat命令打开二进制文件，那么，不好意思，会是乱码哦**，**二进制文件的查看通常是反编译或者使用strings命令查看二进制文件的某些细节**

   ```
   cat [OPTION] [FILE]...
   ```

5. 辨识该文件的类型

   ```
   file filename
   file ./* 当前目录下所有文件类型
   ```

6. find（搜索符合条件文件名）

   ```
   find [路径] [匹配条件] [动作]
   路径是要查找的目录路径，可以是一个目录或文件名，也可以是多个路径，多个路径之间用空格分隔，如果未指定路径，则默认为当前目录
   
   find . -size 1M 在当前目录下按文件大小搜索
   单位可以是 c（字节）、w（字数）、b（块数）、k（KB）、M（MB）或 G（GB）
   find . -user username：按文件所有者查找。
   find . -group groupname：按文件所属组查找
   ```

7. grep(global regular expression)（在文件中搜索字符串）

   ```
   grep  <Options> <Search String>  <File-Name>使用指定字符串运行 grep 命令时，如果匹配，则它将显示包含该字符串的所在行，而不修改现有文件的内容
   ```

8. sort排序 uniq去重

   uniq 命令用于检查及删除文本文件中重复出现的行列，当重复的行并不相邻时，uniq 命令是不起作用的，所以一般与 sort 命令结合使用

   ```
   sort filename  默认为升序
   uniq filename
   ```

9. 粉碎文件

    ```
    shred 文件名
    ```

10. 创建新目录

    ```
    mkdir 目录名
    ```

11. 清空屏幕

         ```
         clear
         ```

12. 创建新用户

         ```
         useradd 用户名
         ```

13. 显示用户手册

         ```
         man 命令名
         ```

14. base64编码/解码

    ```
    base64 [OPTION]... [FILE]
    -d, --decode         # 解码
    ```

