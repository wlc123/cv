 <center>
     <h1>汪路超</h1>
     <div>
         <span>
             <img src="assets/phone-solid.svg" width="18px">
             13128974798
         </span>
         ·
         <span>
             <img src="assets/envelope-solid.svg" width="18px">
             410530459@qq.com
         </span>
         ·
         <span>
             <img src="assets/github-brands.svg" width="18px">
             <a href="https://github.com/wlc123/cv">resume</a>
         </span>
     </div>
 </center>

 ## <img src="assets/info-circle-solid.svg" width="30px"> 个人信息 

 - 年龄：&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;30(1992)
 - 工作经验：&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;5年
 - 工作地点：&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;深圳

## <img src="assets/graduation-cap-solid.svg" width="30px"> 教育经历

- 硕士&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;哈尔滨工业大学&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;微电子学与固体电子学&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;2014.09~2017.01
- 学士&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;哈尔滨工业大学&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;电子信息科学与技术&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;2010.09~2014.07

## <img src="assets/briefcase-solid.svg" width="30px"> 工作经历

-  OPPO广东移动通信有限公司&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;高级影像算法工程师&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;2019.06至今
-  北京初速度科技有限公司(Momenta)&ensp;&ensp;&ensp;&ensp;SLAM算法工程师&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;2018.06-2019.04
-  深圳商汤科技有限公司&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;研究员&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;2016.09-2018.06

## <img src="assets/project-diagram-solid.svg" width="30px"> 项目经历

### &ensp;&ensp;<img src="assets/rss-solid.svg" width="15px">  深度学习&机器学习类
- **OPPO：动漫人脸生成**
	- 描述：依据当前人脸，生成画风与指定动漫IP相像的人脸
	- 职责：负责整体算法方案设计与实现，包括网络结构和loss设计，数据集预处理
	- 效果：[效果图](https://github.com/wlc123/cv/blob/main/anime_face/README.md)
- **OPPO：AI调色**
	- 描述：照图修图，将风格图的颜色信息应用于原始图
	- 职责：独立完成整体算法方案设计与安卓端工程化，包括设计传统算法生成数据集，设计网络进行训练，设计预处理算法消除色阶，安卓端落地及优化
	- 效果：[效果图](https://github.com/wlc123/cv/blob/main/AI_toning/README.md)，在安卓端8350芯片3000x4000图像约85ms；于FindX3落地
- **OPPO：老照片修复**
  - 描述：对老照片进行翻新
  - 职责：设计轻量化的网络结构，端到端的修复人脸；通过两次退化（传统+网络）方法，构建数据集
  - 效果：[效果图](https://github.com/wlc123/cv/blob/main/face_restore/README.md)，已在相册上线
- **OPPO：视频插帧**
	- 描述：将现有视频帧率插值2倍
	- 职责：独立完成整体算法方案设计与实现，包括网络结构和loss设计，在转场等失败情况实现同步自检
	- 效果：[效果图](https://github.com/wlc123/cv/blob/main/video_frame_interpolate/README.md)，在Vimeo90K测试集上PSNR33.5，1080x1920图像每帧计算量仅4GFlops，在服务器端前向时间9ms
- **OPPO：游戏数字识别**
	- 描述：识别游戏截屏中的数字，做为闪回键倒计时依据
	- 职责：独立完成整体算法方案设计与实现，使用神经网络对数字进行分类
	- 效果：[视频](https://github.com/wlc123/cv/blob/main/game_ocr/README.md)，落地于ColorOS闪回键模块
- **初速度：相机自检**
	- 描述：通过传统机器学习方法，完成车载鱼眼相机自检
	- 职责：设计和实现自检算法，训练BRIEF描述子应用于相机自检
	- 效果：准确率达到85%，召回率90%；优化运行速度，在CPUI5上大约在0.5ms
- **商汤：人脸光照均匀化**
	- 描述：改善人脸照片光照情况，矫正“阴阳脸”，缓解过曝
	- 职责：独立完成整体算法方案设计与实现，包括使用统计学习方案拟合光照变换曲线，使用HDR压缩的方法消除高光
- **商汤：远近脸变换**
	- 描述：将一张近距离的自拍照中人脸，变换成远距离人脸，消除透视畸变
	- 职责：独立完成整体算法方案设计与实现，包括使用3D人脸数据库生成数据集，使用人脸关键点回归向量场
	- 效果：[效果图](https://github.com/wlc123/cv/blob/main/face_distortion_elimination/README.md)

### &ensp;&ensp;<img src="assets/rss-solid.svg" width="15px">  3D视觉类
- **OPPO：三维小物体重建**
	- 描述：使用低成本TOF相机实现桌面级小物体重建
	- 职责：独立完成整体算法方案设计与实现，包括回环检测与全局优化，深度图融合，纹理贴图
	- 效果：[效果图](https://github.com/wlc123/cv/blob/main/object_recon/README.md)，平均误差5.5mm，对标三方达到业界领先水平，在安卓端流畅运行
- **初速度：基于车道线的车辆定位**
	- 描述：已知车道线的点云地图和当前车道线分割图，计算车辆SE3pose
	- 职责：独立完成算法原理公式推倒和验证，实现快速的车辆定位功能
	- 结果：[文档](https://github.com/wlc123/cv/blob/main/se3track/README.pdf)
- **初速度：鱼眼特征点匹配和相机标定**
	- 描述：车载四路鱼眼相机之间的特征点匹配，并用以完成相机标定
	- 职责：改进特征点匹配算法；通过一致性筛选特征点；使用鱼眼特征点完成相机标定
- **初速度：APA(Automatic Parking Assist)**
	- 描述：带车位线场景的自动泊车
	- 职责：优化算法，提升精度；识别车位信息
	- 效果：平均误差达到9.17cm；车位提取，从车位线中提取结构化的车位框，测试446个数据包全部通过
- **商汤：animoji**
	- 描述：通过视频驱动卡通人物做相应的表情
	- 职责：完整算法实现；工程化，优化时间空间在安卓千元机实时运行
	- 效果：[视频](https://github.com/wlc123/cv/blob/main/face_recon/README.md)，落地于华为、华硕、小米
- **商汤：memoji**
	- 描述：生成和图像相近的，具有个人特色的卡通人脸模型
	- 职责：算法的设计和实现，通过模型师构建的少量卡通模型生成与真人人脸模型数据库对应的7050个模型，以迁移blendshape参数的方式生成与个人相像的卡通人脸模型
- **商汤：三维人脸重建**
	- 描述：通过人脸图像（单张或多张）完成人脸3D重建
	- 职责：负责整个算法流程的设计、实现、改进和优化；3D人脸数据采集；纹理贴图及光照去除
	- 效果：[视频](https://github.com/wlc123/cv/blob/main/face_recon/README.md)
- **毕设：基于图案轮廓的视觉SLAM算法**
	- 描述：通过轮廓线的几何形状作为特征，完成SLAM主要功能
	- 效果：平均消耗时间大约是ORB-SLAM的44.6%，结果轨迹与ORB-SLAM接近，误差在1e-2左右
  
### &ensp;&ensp;<img src="assets/rss-solid.svg" width="15px">  技术管理类
- **OPPO：智能创作引擎**
  - 描述：将创作理解为根据用户喜好选择合适的图像处理算法进行修图，即智能创作=丰富的素材库+多样的算法库+个性化的美学推荐，智能创作引擎提供一键式的图像&视频处理能力
  - 职责：智能创作引擎架构设计；完成人像时刻项目，从人像视频中选择高光帧，对标三星一键多拍，80%选帧效果大于等于三星；领导AI人像项目，实现自动人像处理
  - 效果：人像时刻作为版本重点需求，从ColorOS12.1开始，逐步上线；智能创作引擎在软工STAC顺利结项，且作为公司TSP项目开展二期
- **OPPO：部落版本SE**
  - 描述：作为智能产品部落ColorOS13.0版本SE，构建AI能力，主要有超级文本和AON
  - 职责：参与产品规划，梳理行业前景；承接产品策划，明确算法规格；设计技术方案，拆分模块，落实到具体团队，明确验收方法和验收标准；识别项目风险，保证项目交付
  - 效果：获得部落优秀个人荣誉；智能产品部落在版本过点多次被表扬，STR2B位列第一，STR2第三
- **OPPO：相册AI能力构建**
  - 描述：根据相机18个月产品规划构建技术栈，并规划技术演进
  - 职责：分析相册痛点分析，给出技术解决方案；制定相册AI技术规划；设计技术评估方案，制定算法准入标准
  - 效果：在OS13.1相册标签标签逐渐扩展到1000类、视频标签500类；OS13.1增加OLIVE实况图像，算法从中选出推荐帧，并实现后处理效果，包括超分、长曝光等

## <img src="assets/tools-solid.svg" width="30px"> 技能清单
- 深度学习
- 三维视觉
- C++、Python、MATLAB
- 数字图像处理

