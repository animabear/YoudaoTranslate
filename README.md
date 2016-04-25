YoudaoTranslate
===============

#### 我的修改
修改 translate.php 中$workflows->result的第二个参数为 $query，这样配置"Open URL" Action的时候，{query}的值为用户输入的值，而非搜索结果。

#### 在Alfred中配置 "Open URL" Action 实现回车跳转有道搜索

URL设置为：http://dict.youdao.com/w/{query}

---

Alfred Youdao Translate Workflow

![screenshot](https://raw.githubusercontent.com/wensonsmith/YoudaoTranslate/master/src/screenshot.png)

![screenshot2](https://raw.githubusercontent.com/wensonsmith/YoudaoTranslate/master/src/screenshot2.png)
#### 更新

- 2016年3月24日

  内置四个api key, 随机调用解决有道每小时1000次调用次数的限制。





### 添加自己的API KEY

有能力的同学可以添加自己的API KEY, 有道翻译API 申请地址：[点此申请，很容易申请](http://fanyi.youdao.com/openapi?path=data-mode)



申请后会得到 `API Key`和 `keyfrom`, 记下这两个值。

#### Step 1

打开程序目录

 ![Step 1](src/Step 1.png)

 ![Step2 ](src/Step2 .png)



#### step 2

打开 `translate.php` ， 按照如下格式将 `key `和 `keyfrom` 添加进去就可以啦！

 ![Step 3](src/Step 3.png)
