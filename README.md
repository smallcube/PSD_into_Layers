# PSD_into_Layers
This is the official repo for turning an image into layers


# 2026.10.10

(1)数据预处理方面，进行数据扩充：同一个jpg，设置不同的n，使用单个照片生成多组数据；
(2)各种超参数需要设置：例如batch size;
(3)预训练or微调：CLIP，Segment Anything（SAM）
(4)知识蒸馏


# 2026 11.10
(1)数据处理1-n分层都要 
(2)根据sigraph论文调整网络架构 
(3)技术细节：论文中高斯去噪、加条件 
(4)创新点：考虑一致性问题
