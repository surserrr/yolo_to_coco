# yolo_to_coco
Convert yolo format to coco format


运行步骤：
1、将要转化的数据放到当前目录下，在当前目录创建文件夹Annotations。在yolotovoc.py主函数中更改路径，运行yolotovoc.py。
  成功运行后，Annotations里会生成相应的xml格式数据。
2、把所有图片复制到Annotations中，voctococo.py中的train_ratio控制train和val的比例，train_ratio=1是全部生成为train数据。运voctococo.py即可。
