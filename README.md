# MARS-Attribute
## Tracket-level person attributes on the MARS dataset.
We firstly annotate 32 attributes for [MARS](http://www.liangzheng.com.cn/1320.pdf), all of the attributes is from the [MARKET-1501_Attribute](https://github.com/vana77/Market-1501_Attribute), the difference between these two attributes dataset is that [MARKET-1501_Attribute](https://github.com/vana77/Market-1501_Attribute) is instance-level, while ours is **trackets-level**.

The detailed information of MARS can be found at http://www.liangzheng.com.cn/Project/project_mars.html, for the reason that in the test-set of MARS, the trackets which belong to the ID "0000" and "00-1" is junk images and distractors, which can't be used to do perdestrian recognition, so these trackets is excluded from the MARS-attribute dataset.


![attributes](attr.jpg)


## Explanition of the data
The attributes data is organised as follows:

\| id | camera | tracklet | Tops.c | Bottoms.c | Age | Tops.l | Bottoms.l | shoulder | bag | backpack | hat | handbag | hair | gender | Bottoms.t |
| --: | --: | --: | --: | --: | --: | --: | --: | --: | --: | --: | --: | --: | --: | --: |
| 1 | 2 | 58 | 8 | 0 | 1 | 1 | 1 | 0 | 0 | 0 | 0 | 1 | 1 | 0 |



## Motion attributes
Except for the origion 32 attributes, we also  
