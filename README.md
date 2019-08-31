# nlg-yongzhuo


# nlg_yongzhuo
    - text_summary
    - text_augnment(todo)
    - text_generation(todo)
    - text_translation(todo)


# run(运行, 以text_teaser为例)
    - 1. 直接进入目录文件运行即可, 例如进入:nlg_yongzhuo/text_summary/feature_base/
    - 2. 运行: python text_teaser.py


# nlg_yongzhuo/data
    - 数据下载
      ** github项目中只是上传部分数据，需要的前往链接: https://pan.baidu.com/s/1I3vydhmFEQ9nuPG2fDou8Q 提取码: rket


# 项目说明
  - 1. 构建了base基类(网络(graph)、向量嵌入(词、字、句子embedding)),后边的具体模型继承它们，代码简单
  - 2. keras_layers存放一些常用的layer, conf存放项目数据、模型的地址, data存放数据和语料, data_preprocess为数据预处理模块,


# 模型与论文paper题与地址
* pagerank:     [The PageRank citation ranking: Bringing order to the Web. 1999](http://dbpubs.stanford.edu:8090/pub/showDoc.Fulltext?lang=en&doc=1999-66&format=pdf)
* textrank:     [TextRank: Bringing Order into Texts](https://www.researchgate.net/publication/200042361_TextRank_Bringing_Order_into_Text)
* textteaser:   [Automatic Text Summarization for Indonesian Language Using TextTeaser]
* significance: [The Automatic Creation of Literature Abstracts*](http://courses.ischool.berkeley.edu/i256/f06/papers/luhn58.pdf)
* LDA:          [Text summarization using Latent Semantic Analysis](https://www.researchgate.net/publication/220195824_Text_summarization_using_Latent_Semantic_Analysis)


# 参考/感谢
* 文本摘要综述:   [https://github.com/icoxfog417/awesome-text-summarization](https://github.com/icoxfog417/awesome-text-summarization)


*希望对你有所帮助!
