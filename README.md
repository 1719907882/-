# transmission lines object detection - yolo11 model weights

基于yolo11s的输电线线路异物识别模型权重。

训练数据包括：
1、输电线异物检测数据集（1300张）。包含4类遮挡："balloon","kite","nest","trash"。
2、电线杆和输电线路攀援藤蔓数据集（2000张1类别）。包含1类遮挡：”vine”。

使用方法：
利用environment.yml配置环境，启动conda环境
cd到模型权重路径，使用如下命令进行预测
yolo predict model=best.pt source="<path_to_dataset>" save_txt=True
