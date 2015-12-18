# Command Line Interface 教程

## 背景

## 安装

## 配置

## 使用

## 体验

## 路径  
$ pwd    print working directory    
$ cd file-name    
$ cd 返回主目录    
$ cd -  返回原先的目录    
$ cd .. 返回上层    
$ cd ~ 返回用户主目录   

## 查看 
ls  
ls/directory_path  指定目录列出内容  
ls -l 目录内容详细格式的输出  (只读还是可读写 貌似还有字数和时间 格式)
ls -a 列出隐藏文件在内的所有文件  
ls -f 直接列出结果不排序

## 查看属性及内容  
$ file file-name  
$ cat file-name 显示文档全部内容  
$ less file-name浏览文件内容  退出用q  

## 创建文件夹  
$ mkdir folders-name  新建文件夹  
$ rmdir folders-name  删除空文件夹  

## 创建文件  
$ touch file-name  
$ > file-name  
$ echo "words" > file-name  

## 复制  
$ cp -l file-name directory_path  
$ cp -l  已存在目标文件，覆盖前询问  
$ cp -a 连同文件特性一起复制  
$ cp -r 复制目录  递归  持续复制（r代表循环）  

## 移动  
$ mv file-name directory_path  

