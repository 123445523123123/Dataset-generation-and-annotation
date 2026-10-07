#各个代码结构的作用如下：
zimage_gen.py：用于构造提示函数并生成数据集图像。
llmdet_label.py：对于自定义数据集，它包括缺陷类别和数据集的注释自动化以及可视化显示。
get_yolo_txt.py：用于将数据集的VOC格式标注文件转换为txt格式。
Summary.py：用于统计数据集的数量和缺陷标注的数量。
split_data.py：用于将数据集按比例划分为训练集、验证集和测试集。
requirements.txt：环境版本配置文件

