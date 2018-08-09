## 中文语音识别
##### 1. 环境
- Python：3.6.5
- Tensorflow : 1.8.0
------
##### 2. 训练数据下载
- 清华大学中文语料库（thchs30）[下载地址](http://www.openslr.org/18/)

------

##### 3. 训练
- 配置conf.ini
[FILE_DATA] 
  2 wav_path=/home/speech.AI/github/speech_recognition/opt/wav/test/
  3 label_file=/home/speech.AI/github/speech_recognition/opt/wav/test.word.txt
  4 savedir=/home/speech.AI/github/speech_recognition/opt/tf/speechtest/
  5 savefile=speech.cpkt
  6 tensorboardfile=/home/speech.AI/github/speech_recognition/opt/tf/logs
  
- 在终端运行 ```python train.py``` 开始训练
- 在终端运行 ```python test.py``` 测试
- 也可以使用PyCharm打开

------

##### 4. 测试效果
![test-image](https://github.com/jx1100370217/ASR_dosmono/blob/master/images/1.png)
