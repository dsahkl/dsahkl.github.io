---
layout: post
title:  Markdown基本语法
date:   2019-06-13 22:10:00 +0800
categories: document
tag: 记录
---

* content
{:toc}
---


背影			{#yungentie}
====================================
北国风光
# 这是一级标题
## 这是二级标题
### 这是三级标题
#### 这是四级标题
##### 这是五级标题
###### 这是六级标题
---
**这是加粗的文字**
*这是倾斜的文字*`
***这是斜体加粗的文字***
~~这是加删除线的文字~~
---
>这是引用的内容
>>这是引用的内容
>>>>>>>>>>这是引用的内容
---
---
----
***
*****
---
![blockchain](https://ss0.bdstatic.com/70cFvHSh_Q1YnxGkpoWK1HF6hhy/it/
u=702257389,1274025419&fm=27&gp=0.jpg "区块链")
---
[简书](http://jianshu.com)
[百度](http://baidu.com)
---
- 列表内容
+ 列表内容
* 列表内容

注意：- + * 跟内容之间都要有一个空格
---
1.列表内容
2.列表内容
3.列表内容

注意：序号跟内容之间要有空格
---
表头|表头|表头
---|:--:|---:
内容|内容|内容
内容|内容|内容

第二行分割表头和内容。
- 有一个就行，为了对齐，多加了几个
文字默认居左
-两边加：表示文字居中
-右边加：表示文字居右
注：原生的语法两边都要用 | 包起来。此处省略

---
姓名|技能|排行
--|:--:|--:
刘备|哭|大哥
关羽|打|二哥
张飞|骂|三弟
---
(```)
  import requests
r = requests.get('https://music.163.com/playlist?id=2828733216')
r.encoding = 'utf-8'
print(r.text)
(```)
---
---
```flow
st=>start: 开始
op=>operation: My Operation
cond=>condition: Yes or No?
e=>end
st->op->cond
cond(yes)->e
cond(no)->op
&```
---


