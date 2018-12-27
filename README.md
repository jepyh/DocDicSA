# DocDicSA
基于情感词典篇章级情感分析  
项目基于liuhuanyong编写的[代码项目](https://github.com/liuhuanyong/DocSentimentAnalysis/)  
## 情感词典  
dict下的desc_words.txt和sentiment_words.txt  
desc_words.txt实例：

    极其	2.0
    最	2.0
    百分之百	2.0
    倍加	2.0
    备至	2.0
    不得了	2.0
    不堪	2.0
    不可开交	2.0
    不亦乐乎	2.0
    ......
sentiment_words.txt实例：

    绷脸	-0.6
    惊惶	-0.6
    七零八落	-0.6
    死者	-0.6
    奸伪	-0.6
    己见	-0.6
    纹裂	-0.6
    讳言	-0.6
    道德败坏	-0.6
    ......
## 语言技术平台模型
语言技术平台（Language Technology Platform，LTP）是由哈尔滨工业大学社会计算与信息检索研究中心历时十年开发的一整套中文语言处理系统  
ltp_data下用到ner.model parser.model pos.model三个模型（由于文件>100M，故后两个文件未上传到库请前往[该网址](https://pan.baidu.com/s/1xzvuyutjy4dBLCSTYxXptA)(key:u7l1)自行下载）
