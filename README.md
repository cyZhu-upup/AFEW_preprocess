# AFEW_preprocess
preprocessing AFEW from video to images

## problems remaining:
不包含face bounding box extent ；检测效率低下

对AFEW数据集进行预处理来符合Emotion-FAN项目的条件

将视频通过ffmpeg分成001-xxx.jpg的图片，再通过dlib和opencv检测人脸并分割，最后resize为224*224的图片
