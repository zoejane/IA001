# ch0 检索实操题 - 寻找搜索全球书籍信息的网站

~在此撰写本章检索实操题信息分析报告。

## 0. 摘要

这是开智学堂「信息分析」课程第 0 周检索实操题任务报告，包含分析背景、思路与分析步骤、主要结论、进一步讨论、参考文献等内容，完整重现我获取此题目答案的过程。

本次任务中我共进行了 2 次 Google 关键词尝试, 对结果进行了 3 个方面的验证, 详细步骤参见正文。

最后，我得出的结论是 WorldCat.org: The World's Largest Library Catalog - https://www.worldcat.org/ 就是我们需要找的网站.

在进一步讨论中，我分享了自己从中学到的一些经验，可能对小伙伴们有启发。期待与小伙伴们多交流!

## 1. 背景

任务卡片:

> 有一个 w 开头的网站，可以搜索全球书籍信息。尝试找到这个网站，并记录你的检索时间和过程。完成 300 字左右的信息分析报告。

> 提交方式：fork 课程仓库，生成个人学习仓库，上传截图、过程和思考至 ch0 > RepSearchPractice.md，获取文档链接，按要求回复在相应 Issue 下。

## 2. 分析过程

### 2.1 搜索方式选择 - Google + 英文

- 既然是搜索全球书籍信息的服务, 用英文搜到的结果应该是最准确的
- 选定了用 Google + 英文 的方式

### 2.2 具体步骤 - 关键词尝试

- 第一次搜索 - 关键词 world book - 20180429 13:22
    - 发现第一页都是卖书的, 以及一些童书有关的网站
    - 这让我觉得我的关键词选择有问题
    - 回过头来看任务的内容, 是要找一个 `搜索全球书籍信息` 的网站, 之前没有关注到 `搜索` 这个关键词, 于是添加上
- 第二次搜索 - 关键词 world book search engine - 20180429 13:25
    - 除了前两个是卖书的网站, 第三个网站引起了我的兴趣
    - WorldCat.org: The World's Largest Library Catalog
        - https://www.worldcat.org/
        - Find what you want in a library near you with WorldCat, a global catalog of library collections.
    - 看这个描述, 非常有可能就是我们想要找的网站
    
     ![](http://zoejane.net/img/23554487.jpg)


### 2.3 结果验证

####  2.3.1 验证网站搜索图书的能力

- 先挑选了一本我爱看的书 [树上的男爵](https://book.douban.com/subject/6789605/)
- 分别用 英文名 The Baron in the Trees/ 中文名 树上的男爵/ 意大利名 Il barone rampante /  ISBN 9787544722803 进行搜索, 都找到了相应的许多版本的图书的信息
- 初步验证了网站的搜索的功能

#### 2.3.2 通过与课程的联系进一步验证

- 推测这里要我们找的`搜索全球书籍信息`的网站和可能就是我们接下来的课程中就会要用的, 很可能是为了让我们方便的在 Zotero 中添加相应的图书信息
- 作为一个常用的信息检索网站, Zotero 中有很大可能是会有对应的 translator 方便进行信息抓取的
- 于是进入到 Zotero 对应的 translators 目录下, 把所有 w 开头的 translator 都扫视了一遍
    - 发现 `WorldCat Discovery Service.js` 就是对应我们刚刚找到的 `WorldCat` 的网站的
    - 同时根据网站内容, 排除了另外 w 开头的网站
- 至此, 我已经有比较大的把握觉得这就是我们想要找的网站了

#### 2.3.3 通过网站的自述 [About WorldCat](https://www.worldcat.org/whatis/default.jsp) 进一步了解

- 通过网站的自述内容了解到
    - What is WorldCat? 
        - `WorldCat is the world's largest network of library content and services...`
    - What will I find?
        - `You can search for popular books, music CDs and videos—all of the physical items you're used to getting from libraries. You can also discover many new kinds of digital content, such as downloadable audiobooks. You may also find article citations with links to their full text; authoritative research materials, such as documents and photos of local or historic significance; and digital versions of rare items that aren't available to the public. Because WorldCat libraries serve diverse communities in dozens of countries, resources are available in many languages.`
- 验证了网站所具有的功能之一也是方便我们搜索到全球的书籍信息

## 3. 结论

WorldCat.org: The World's Largest Library Catalog - https://www.worldcat.org/ 就是我们需要找的可以搜索全球书籍信息的网站.

## 4. 讨论

- 善用英文 Google 搜索
    - 很多优质的资源都是英文形式的, Google 的英文搜索帮助很大.
- 及时调整关键词
    - 当出现的结果和自己的预期有所偏离时, 不应该漫无目的的顺着搜索结果一页页翻下去,而是应该及时调整搜索关键词, 马上就柳暗花明了.
- 使用合理推测
    - 上面通过对课程设计的推测, 配合 Zotero 使用的 translator , 对结果进行了进一步的验证, 大大增强了我对搜索结果的信心. 
- 时间记录
    - 搜索 耗时约 4 mins
    - 后续的验证加初步撰写文章等 耗时约 50 mins
    - 把文章修订为任务报告形式 耗时约 26 mins
- 课程笔记
    - 检索流程(自检清单, 对于搜索结果不满意时,反思哪个环节出了偏差, 可以优化)
        - 明确检索目的
        - 选择检索工具
            - 储存更多优质信息的网站, 检索事半功倍
        - 确定关键词(核心) 需反复训练
        - 构造检索式
            - 对关键词的补充, 让搜索殷勤更了解你想要的是什么 
        - 筛选检索结果
            - 除了人工判断, 多数搜索殷勤都会提供进一步筛选选项, 比如指定搜索结果日期 
        - 调整检索策略
    - 布尔逻辑 
        - 与 AND
        - 或 OR 提高查全率
        - 非 NOT 注意格式 `A -B` 
    - 其他检索技巧
        - 精确搜索 双引号 "" 如: "创新算法"
        - inurl intext intitle
            - 在网页标题内搜索 intitle 如: intitle: 创新算法
            - 在链接中搜索 inurl
            - 在网页主体中搜索 intext
        - 在指定网站内搜索 site 
            - 如: 创新算法 site:douban.com
            - site:.gov
            - site:https://www.douban.com/doulist/ 创新
        - 制定搜索类型 filetype 如: 创新算法 filetype:pdf
        - 模糊匹配 星号* 如: 第 * 届挑战杯大赛 
    - 以图搜图
        - 搜索对应地名 / 景点
        - 相似图片
        - 相关文章
        - 用剧照找电影
        - 识别他人头像出处 / 是否情侣头像
        - 搜索产品图片了解相关报道 
    - 调整关键词
        - 关键词选择 (可借助工具获取关键词)
            - 上位词
                - 概念上外延更广的词 
                - 搜索结果过少时使用
            - 主题词(等同词) - 同类词 
                - 提高查全率 
            - 下位词
                - 概念上内涵更窄的词 
                - 搜索结果过多时使用
            - 英文关键词
        - 案例 
            - 万方的智能拓展功能 - 适合探索专业领域时调整关键词 
            - 拆解相关关键词, 构造检索式
                - 如 军事心理学 
                    - 两个下位词 军事(查找其定义)和心理学(查找相关研究方向)
                    -(战争 OR 军队 OR 军人) AND (军事绩效 OR 人的因素 ... OR)
    - 检索如此重要, 为什么多数人没有养成良好的检索习惯?
        - 搜索成了下意识动作, 易于被忽视
        - 搜索过程容易被各种页面带跑, 无形中花费大量时间
            - 使用树状试图, 跟踪访问归集, 可以帮助你察觉当前所处搜索阶段, 避免注意力沦陷
            - Chrome 插件
                - Tabs Outliner
                - Sidewise Tree Style Tabs 
               

## 5. 参考文献

- [WorldCat.org: The World's Largest Library Catalog](https://www.worldcat.org/)
- [Zotero（1）：文献管理软件Zotero基础及进阶示范 - 阳志平的网志](http://www.yangzhiping.com/tech/zotero1.html) 其中提到了 Zotero 的 Web Translators 功能

## Changelog

- 180502 zoejane - add more course notes 15 mins
- 180502 zoejane - learn course and add course notes 30 mins
- 180429 zoejane - change the draft to report 26 mins
- 180429 zoejane - finish task and add process part - 60 mins
- 180428 zoejane - init and add task card


