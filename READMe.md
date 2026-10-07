#各个代码结构的作用如下：
zimage_gen.py：Used to construct the prompt function and generate the dataset images.
llmdet_label.py：For the custom dataset, it includes the automation of defect categories and annotations as well as the visualization display of the dataset.
get_yolo_txt.py：Used to convert the VOC format annotation files of the dataset into txt format.
Summary.py：The quantity of the statistical data set and the number of defect annotations.
split_data.py：Used to divide the dataset into training set, validation set and test set in a proportional manner.
requirements.txt：Environment version configuration file

