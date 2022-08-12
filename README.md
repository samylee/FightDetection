# FightDetectionDemo  
基于视频分类的GPU实时打架检测  

# 算法效率  
| 数据类型 | 取帧间隔 | 取帧数量 | 输入图像尺寸(n-c-h-w) | 耗时(基于GTX-1080) | 准确率(业务数据) |
|:------:|:------:|:------:|:------:|:------:|:------:|
| 视频/连续帧图像  | 7帧 | 8帧 | 8x3x320x320 | 80ms |89%|

# 获取源代码
**纯c++代码，请联系作者微信：samylee_csdn**

# 软硬件要求  
1. windows7/10  
2. cuda10.1  
3. cudnn7.6.5  
4. nvidia-gpu-10系列/20系列  

# 模型和第三方库下载
1. 模型下载：[百度网盘](https://pan.baidu.com/s/1H_u8is_LD8WKgwuRRV2IFQ) `提取码: 5sob`  
2. 第三方库下载：[百度网盘](https://pan.baidu.com/s/1Zu_h_pZC4xtqfJUzT1Kd9A) `提取码：zet6`  

# 测试方式  
1. 将下载的模型和第三方库放到`FightDemo.exe`的同级目录  
2. 用`notepad++`打开`video_demo.cmd`  
3. 修改第二个参数`video_path`为视频路径  
4. 保存后双击测试，结果呈现在图片中，**绿色表示正常，黄色表示疑似打架，红色表示打架**

# 参考链接  
1. [百度飞浆](https://github.com/PaddlePaddle/PaddleVideo)
2. [samylee中文博客](https://blog.csdn.net/samylee/article/details/126305702?spm=1001.2014.3001.5502)
