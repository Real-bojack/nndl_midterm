data aug:数据增强可视化

train: 训练模型
使用以下指令进行训练 其中method为数据增强方法
0：无  1：cutout  2: mixup  3: cutmix
$ python train.py -net resnet18 -gpu -method 3

test: 测试模型
utils: 工具，包括3种数据增强的方法
conf: 全局变量设置

