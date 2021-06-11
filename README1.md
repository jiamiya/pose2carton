# Pose2Carton 

EE228 课程大作业，利用3D骨架控制3D卡通人物。



# Maya 环境配置

下载Maya教育版，安装后将……/Maya2022/bin添加到系统环境变量，该目录下应该包括mayapy，在终端中即可运行mayapy，对于一些IDE也可以手动选择mayapy作为解释器来运行代码。

在此基础上使用mayapy -m pip install 可以安装一些python库。



# 匹配流程

1.对于从网上下载的模型需要进行此步，对于提供的obj和txt跳过此步骤。将fbx_parser.py中的第166行代码文件路径改为相应fbx模型的路径，选择mayapy作为解释器后运行fbx_parser.py
可以得到obj格式的模型，包含joint和skin信息的txt文件，



# 新增脚本说明

如果你写了自己的脚本来处理数据或进行可视化，请在这里进行相关说明(如何使用等)； 如果没有，请忽略该模块。



# 项目结果

这里放置来自你最终匹配结果的截图， 如

![image](../img/pose2carton.png)





# 协议 
本项目在 Apache-2.0 协议下开源

所涉及代码及数据的最终解释权归倪冰冰老师课题组所有

Group xx
