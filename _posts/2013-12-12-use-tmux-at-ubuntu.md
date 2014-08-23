---
layout: post
title:  "use tmux at ubuntu"
date:   2013-12-12 
categories: jekyll update
---
##ubuntu下使用tmux，非常好用，尤其喜欢用命令和vim的。 
   
- `ctrl + b` 激活控制台一下都所有操作均要先激活工作台   
  - 窗口操作  
   - ` c`新建一个窗口  
   - ` &`关闭当前窗口  
   - ` p ` ` n ` 切换都到前面后面的窗口  
   - `,` 重命名当前窗口  
   - `.` 修改当前序号，排序  
   - ` f ` 在所有窗口中查找文本     
 - 面板操作(pane)    
   - `s`垂直分割面板  
   - `%`水平分割面板  
   - `x`关闭当前面板  
   - 方向键在各个面板中切换    
   - ctrl + 方向键 以五个单元格移动    
   - alt + 方向键 以一个单元格移动    
   - `{}`切换面板位置    
powerline 配置   
  - 和配置vim powline的方法差不多，主要是   
    - 下载字体  
    - 配置文件  
    - 快捷键     
```全屏(屏太小，所以一般<F11>全屏开发)```       
####配置tmux  
&nbsp;&nbsp;&nbsp;&nbsp;其实tmux和vim一样也可以自己配置快捷键等操作都，主要就是在home目录下新建(如果没有)一个[.tmux_conf](https://github.com/polandeme/tmux_config)文件，然后再进行操作即可。  
