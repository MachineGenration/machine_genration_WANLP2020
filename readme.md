#### This an announcement repo for our work 
*Fifth Arabic Natural Language Processing Workshop (WANLP 2020), Barcelona, Spain, 12 Dec. 2020*
# Machine Generation and Detection of Arabic Manipulated and Fake News (WANLP 2020)
<img src="https://github.com/MachineGenration/machine_genration_WANLP2020/blob/master/news_map.jpg" width="55%" style="border: 1px solid black;" align="right"/>
Fake news and deceptive machine-generated text comprise a serious problem threatening modern societies, including in the Arab world. This motivates work on detecting false and manipulated stories online. However, a bottleneck for this research is lack of sufficient data to train detection models. In this work, we present a simple method for automatically generating Arabic manipulated and fake news stories. Our method is simple, and only depends on availability of legitimate stories, which are abundant online, and a part of speech tagger (POS). To facilitate future work, we dispense with both of these requirements altogether by providing AraNews, a novel and large POS-tagged news dataset that can be used off-the-shelf. Using stories generated based on AraNews, we carry out a human annotation study that casts light on the effects of machine manipulation on text veracity. The study also measures human ability to detect Arabic machine manipulated text generated by our method. Finally, we develop the first Arabic news manipulation detection models and a new SOTA model for detecting Arabic fake news Our models and data will be publicly released upon paper acceptance.

## Datasets

### ATB: Arabic TreeBank

Arabic Treebank (ATB) which are a collection of Arabic news stories built as part of   of the [DARPA TIDES project](https://www.ldc.upenn.edu/collaborations/past-projects):
 - Part 1 v 4.1 (LDC2010T13)
 - Part 2 v 3.1 (LDC2011T09)
 - Part 3 v 3.2 (LDC2010T08)
 - Broadcast News v 1.0 (LDC2012T07)
 
### AraNews: A New Large-Scale Arabic News Dataset

In order to study misinformation/disinformation in Arabic news, we develop, **AraNews**, a large-scale, multi-topic, and  multi-country Arabic news dataset. To create the dataset, we start by manually creating a list of 50 newspapers belonging to 15 Arab countries, the United States of America (USA), and the United Kingdom (UK). Then, we  scrape the news articles from this list of newspapers. Ultimately, we collected a total of  5,187,957 news articles.

#### Donwload AraNews:

  - [ArNews_train_GW_order_0.tar.gz](https://github.com/MachineGenration/machine_genration_WANLP2020/blob/master/ArNews_train_GW_order_0.tar.gz)
  - [ArNews_dev_GW_order_0.tar.gz](https://github.com/MachineGenration/machine_genration_WANLP2020/blob/master/ArNews_dev_GW_order_0.tar.gz)
  - [ArNews_test_GW_order_0.tar.gz](https://github.com/MachineGenration/machine_genration_WANLP2020/blob/master/ArNews_test_GW_order_0.tar.gz)
  - [ZeroShot_train_ArNews_2X.rar](https://github.com/MachineGenration/machine_genration_WANLP2020/blob/master/ZeroShot_train_ArNews_2X.rar)
  - [ZeroShot_train_ArNews_5X.part01.rar](https://github.com/MachineGenration/machine_genration_WANLP2020/blob/master/ZeroShot_train_ArNews_5X.part01.rar)
  - [ZeroShot_train_ArNews_5X.part02.rar](https://github.com/MachineGenration/machine_genration_WANLP2020/blob/master/ZeroShot_train_ArNews_5X.part02.rar)
  
### ANS: Arabic News Stance Corpus 
You can donwload the Khouja's dataset from [Github](https://github.com/latynt/ans)

