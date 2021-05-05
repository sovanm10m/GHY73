# BiaoZhuTool
## 方便的文本标注工具
# 环境配置
# 文件说明
## data文件夹
###   data/example.json：包含待标注文件
###   data/record/record_01.txt:标注结果
## data_process文件夹
###   file2file.py：文件处理工具，用来处理自己的数据，生成最终的符合要求的.json数据
## tool文件夹
###   basewin.py:主要是界面布局
###   mainwin.py:包含标注的主要逻辑，包含主函数，继承了basewin.py中的类。
# 使用步骤
## 在运行mainwin.py前，需要依据自己的.json数据以及标签（tags）需求，对标注工具进行一些设置。设置分为3步。
## 查看mainwin.py，依据提示，依次进行设置。
# 界面展示
![](https://github.com/GHY73/BiaoZhuTool/blob/master/%E6%A0%87%E6%B3%A8%E4%B8%BB%E7%95%8C%E9%9D%A2.png?raw=true)
