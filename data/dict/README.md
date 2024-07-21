# data/dict

## 0. intro
1. read dict file and save to dict.json or dict.csv, and construct the dict file for LLM.
2. get dict data by `api`
3. get dict data from `db` or `csv` etc.
4. crawler

## 1. purpose
- get dict data for siyong_tutor and other LLMs.

## 2. format
- mdd,mdx
- eudic
### 2.1 mdd,mdx


#### ref
- [MDX/MDD 文件格式解析](https://einverne.github.io/post/2018/08/mdx-mdd-file-format.html)
    - 介绍了文件格式`html`组成
    - 给出了相关`repo`参考
    - 作者其他博文不错,有涉猎NLP

### 2.2eudic

#### intro

#### official
- [《法语助手》、《德语助手》、《欧路词典》部分扩充词典库整理](https://www.eudic.net/Product/dictionary_resource.aspx)
- [欧路词库编辑器  -《欧路词典》的词库制作工具](https://www.eudic.net/eudic/builder.aspx)

#### ref
- [https://www.pdawiki.com/forum/thread-43473-1-1.html?_dsign=79490114](https://www.pdawiki.com/forum/thread-43473-1-1.html?_dsign=79490114)
    - pda论坛上的,但是需要注册才可以看到附属内容
    - https://gitee.com/wp19991/eudic-dictionary-making
- [\[使用求助\] 欧路扩充词典能否转为mdx?](https://www.pdawiki.com/forum/thread-19155-1-1.html?_dsign=65d1c566)
    - https://github.com/ilius/pyglossary python 的转换词典工具
        - [Read eudic (Chinese dictionary) files #5](https://github.com/ilius/pyglossary/issues/5)有关于支持`eudict`格式的讨论.
    - `欧陆的词典基本都是从灵格斯词典转来的，你可以从灵格斯的词典入手。不过，虽然灵格斯的词典可以转为TXT的格式，不过怎么转化成MDX，我也很为难，提问至今无人回答。`
- [[Python 转载] 欧路词典爬虫](https://www.52pojie.cn/thread-1623828-1-1.html)
- https://downloads.freemdict.com/ 免费词典下载站
#### repo
- https://github.com/eudic/online-dict/tree/main Eudic-Online-Dict 欧路词典在线查词引擎
- https://github.com/sarkrui/Eudic-for-Mac 一键安装欧路词典并导入第三方 mdict 词库（牛津高阶词典）
    - 还可以注册?
- https://github.com/zenghongtu/saladict-desktop 沙拉词典 一款跨平台词典app

