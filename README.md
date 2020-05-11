# Unity-Autosave-System
Unity自动保存系统
# 最终效果：
备份场景文件将会出现在原场景文件同一文件夹中，名称为BackupScene1 或BackupScene2，交替出现，名字变更时即表示场景文件已经发生迭代。该脚本将会每15分钟为用户保存一次原场景并保存于BackupScene1(2)中。
双击即可进入备份场景。

==注意：若要启用备份场景，应删除原场景，并将备份文件改名。当备份文件名为BackupScene1(2)时，保存将无法进行。==

详情如下图所示：
![最终效果](https://img-blog.csdnimg.cn/20200511212130336.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L0xfQ2hlZQ==,size_16,color_FFFFFF,t_70)
#	具体使用方法

 1. 添加Assets/Editor文件夹
打开要添加自动保存功能的Unity项目，在工程目录根目录下右键Create-Folder新建文件夹，将新文件夹名称改为Editor，文件夹路径为Assets/Editor。详情如下图所示：
![在这里插入图片描述](https://img-blog.csdnimg.cn/20200511212042726.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L0xfQ2hlZQ==,size_16,color_FFFFFF,t_70)

3.向Editor文件夹中拖入脚本
左键将文件拖入文件夹，出现加号后松开左键。详情如下图所示：
![在这里插入图片描述](https://img-blog.csdnimg.cn/20200511212345781.png)

4.启动自动保存功能
在工具栏中点击Extras-AutoSave按钮，或使用Ctrl+W启动自动保存。详情如下图所示：
![在这里插入图片描述](https://img-blog.csdnimg.cn/20200511212455415.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L0xfQ2hlZQ==,size_16,color_FFFFFF,t_70)

5.放置活动窗口
自动保存操作需要在窗口保持开启的情况下完成，故而可以将Extras弹出窗口放置在某个子选项卡中。该窗口将会显示距离下一次保存的剩余时间长度和场景保存情况。详情如下图所示：
![在这里插入图片描述](https://img-blog.csdnimg.cn/20200511212700897.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L0xfQ2hlZQ==,size_16,color_FFFFFF,t_70)

6.启用备份文件
首先查找备份文件。备份场景文件将会出现在原场景文件同一文件夹中，名称为BackupScene1 或BackupScene2，交替出现，名字变更时即表示场景文件已经发生迭代。双击即可进入备份场景中。注意：若要启用备份场景，应删除原场景，并将备份文件改名。当备份文件名为BackupScene1(2)时，保存将无法进行。
最终结果如下图所示：
![在这里插入图片描述](https://img-blog.csdnimg.cn/2020051121273974.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L0xfQ2hlZQ==,size_16,color_FFFFFF,t_70)
