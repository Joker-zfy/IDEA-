# IDEA-
IDEA工具基本使用笔记
#1
建立项目
cmd————java -version检查JDK版本（存在即可）
项目路径一般为：C:\Users\...IdeaPoject\(Project name)
src中建立一个包，命名为：com.包名，在包里面新建一个java类(首字母大写)

#2
项目打包
settings————Project Structure—————Artifacts——————Add—————Apply——————Build
在终端运行即可验证：在当前文件夹下进入cmd————cd 文件位置————java -cp test+table+包名.类名

#3
基本设置
打开设置：ctrl+out+s ;设置(ctrl+鼠标滑轮)改变字体大小：Editor————General————Mouse;鼠标悬浮提示：settings————Editor————General——Other
自动导包：Editor————General————Auto import—————java选项中勾选；方法间的分隔符：Editor————General————Apperance—————Show mothod ...
忽略大小写提示：Editor————General————Code Completion————不勾选Math case;自动编译：Build Execution...—————Compiler—————...automathtically

#4
快捷键
 * alt+/代码自动补全
 * alt+insert 自动生成构造方法等
 * ctrl+shift+回车 补全结尾
 * ctrl+j 自动代码生成模板
 * table 自动将缩写补全，如psvs+table
 * alt+回车 导包或者修正已经导入的包（已经设置自动导包）
 * ctrl+alt+l 格式化代码（直接用）
 * ctrl+alt+i 自动缩进（选定代码）
 * ctrl+e 显示最近更改的代码
 * ctrl+p 方法参数提示
 * ctrl+out+t 把一部分内容放在各种结构里（选定代码）
 * ctrl+d 复制单行
 * ctrl+d 删除单行
 * ctrl+w 自动选中 ctrl+shift+w 反选代码
 * ctrl+g 跳转到某一行
 * psvm+table
 * 支持断点调试
 * ctrl+n 查找类 ctrl+shift+n 查找文件
 
 #5
 Java模板:File and Code Templates   Live Templates:Editor————Live Templates,内含各种缩写，
 支持新建自己的模板（最后要在Change中选择Java中的Statement）
 
 #6
 maven：项目开发和管理工具（maven.apache.org）
 (待补充)
 #7
 users目录下用户名为中文是无法Debug的，解决方法（暂定可行）：在settings中的Build,Execution,...目录下找到Debugger下的Asysnc...并不勾选第一项即可。
 
 

