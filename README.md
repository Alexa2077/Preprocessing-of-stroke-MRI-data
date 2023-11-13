# Preprocessing-of-stroke-MRI-data
用于对脑卒中的MRI数据进行预处理，包括颅骨剥离，配准，以及归一化。其中包括原理解释和代码说明

# 0 介绍
颅骨剥离使用FSL工具箱中的bet2 配准操作使用antspy 归一化与标准化

1，颅骨剥离    
	1.1 FSL的安装  
  1.2 nrrd格式转nii.gz   
  1.3 FSL之bet2颅骨剥离  

2，配准操作   
  2.1 什么是医学图像配准？   
  2.2 医学图像配准专业名词   
  2.3 模板和图谱降采样   
  2.4 ANTspy图像配准   
  2.5 ISLES22公开数据集配准  

3，归一化   
  3.1 标准化与归一化   
  3.2 代码操作与小trick  

  

commit1: ver-20230829，weiwang 创建DWI预处理文件，完成1，2，3章版本0829写作 后续添加3.2 代码操作及小trick

commit: 后续加入docker，在docker里面构建后续工作。
