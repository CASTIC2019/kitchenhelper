# kitchenhelper
A robot for kitchen
一、痛点
现在的生活节奏加快，年轻人的做菜水准降低，需要依靠网络查找菜谱，却因无法酱汁找到正确的配比而头疼烦恼。为此应该减轻厨房工作的量，用机器代替人工。
二、解决
使用机器人辅助烹饪（调配酱料），将烹饪时间压缩，同时采用不同食谱改进口味。
三、原理
	利用语音识别技术、图像识别技术、开源硬件等实现自主调配酱料、调整口味、模块化的厨房助手机器人。
四、特点
	通过设置多个模块，实现不同酱料的搭配使用，在识别菜品名称之后依据菜谱决定并配置酱料，根据菜品的完成进度给出不同调料，并根据使用者口味微调。

![](concept.png)

五、设计方案
					  _固体调料：研磨器，对粗盐、胡椒；螺旋，对糖、味精等等
					 /
	关键技术路线 配酱料-半固半液：螺旋
					\
					 \_液体调料：阀门，对酱油、油、醋等等