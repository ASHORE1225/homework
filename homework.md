## 题目：基于RTMPose的耳朵穴位关键点检测

**背景**：根据中医的“倒置胎儿”学说，耳朵的穴位反映了人体全身脏器的健康，耳穴按摩可以缓解失眠多梦、内分泌失调等疾病。耳朵面积较小，但穴位密集，涉及耳舟、耳轮、三角窝、耳甲艇、对耳轮等三维轮廓，普通人难以精准定位耳朵穴位。

**任务**
1.Labelme标注关键点检测数据集（子豪兄已经帮你完成了）
2.划分训练集和测试集（子豪兄已经帮你完成了）
3.Labelme标注转MS COCO格式（子豪兄已经帮你完成了）
4.使用MMDetection算法库，训练RTMDet耳朵目标检测算法，提交测试集评估指标
5.使用MMPose算法库，训练RTMPose耳朵关键点检测算法，提交测试集评估指标
6.用自己耳朵的图像预测，将预测结果发到群里
7.用自己耳朵的视频预测，将预测结果发到群里
需提交的测试集评估指标（不能低于baseline指标的50%）
**结果**
目标检测Baseline模型（RTMDet-tiny）
![在这里插入图片描述](https://img-blog.csdnimg.cn/f1c3d4519d3e4599bc27b355ca8835f7.png#pic_center)
目标检测Baseline模型（RTMpose）
![在这里插入图片描述](https://img-blog.csdnimg.cn/0f63a6e9405e4a3bb09c4e48c221af80.png#pic_center)
预测结果
![在这里插入图片描述](https://img-blog.csdnimg.cn/bf7b6e042a9d4c3aa95d873c50e6aa15.png#pic_center)
![在这里插入图片描述](https://img-blog.csdnimg.cn/6e5c8e0a1247470ab9e7ad08e6aa15ec.png#pic_center)



















