- 记一次使用chatgpt写程序成功的过程
- 需求：帮老师重命名文件名，80多个，不算多。手动可以完成。但我想试试用python或者脚本可不可以完成
- 第一次，尝试改网站上现成的代码
- [python办公自动化--批量修改文件/文件夹名称 - 知乎 (zhihu.com)](https://zhuanlan.zhihu.com/p/311614377)
- 失败，只改了一半的数据，剩下的手动改的
- 第二天，尝试找有没有类似的重命名软件，真找到了几个
	- renamer
	  logseq.order-list-type:: number
		- "D:\ReNamer\ReNamer.exe"
		- 但是这个软件主要的方向是按照固定的规则来重命名，但我需要按照我的表格里的数据一一进行重命名，这个软件不适用于我的场景
	- logseq.order-list-type:: number
	  2. 太极重命名（b站找的）
		- {{video https://www.bilibili.com/video/BV1Eo4y1f7p8/?spm_id_from=333.880.my_history.page.click}}
		- "C:\Users\柳林康\Downloads\Compressed\太极重命名.v16.4\太极重命名.exe"
- 然后看到了一个用chatgpt来写了一个重命名小工具的up主
	- {{video https://www.bilibili.com/video/BV1Fj411278a/?spm_id_from=333.880.my_history.page.click}}
	- 我也想自己写一个
	- ![image.png](../assets/image_1694849488244_0.png)
	- 写了
	- "D:\Users\柳林康\Desktop\批量改文件名小工具2（表格里一一对应）（无对比界面）.py"
	- 第一次的代码不能运行，问了几次chatgpt，可以运行了
	- ![image.png](../assets/image_1694849674703_0.png)
	- 重命名完成
	- 然后觉得界面还是不太好用，就让chatgpt做了一下修改，改为选择文件夹后能看到文件名，导入表格后也能看到更改后的文件名
	- "D:\Users\柳林康\Desktop\批量改文件名小工具2（表格里一一对应）（无对比界面）.py"
	- ![image.png](../assets/image_1694849809208_0.png)
	- 然后排查了一下问题，运行
	- ![image.png](../assets/image_1694849615398_0.png)
	- 效果不错
	- 修改前文件名
	- ![image.png](../assets/image_1694849978890_0.png)
	- 修改后文件名
	- ![image.png](../assets/image_1694849999551_0.png)
	-
-
-