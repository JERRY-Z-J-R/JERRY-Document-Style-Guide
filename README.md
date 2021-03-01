

# JERRY-Document-Style-Guide

**《JERRY 中文技术文档的写作规范》**

> 主要内容基于阮一峰[《中文技术文档的写作规范》](https://github.com/ruanyf/document-style-guide)，个别内容进行了个人补充。
>
> 转载请注明出处，请勿用于商业用途！

**目录**

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
**Table of Contents**  *generated with [DocToc](https://github.com/thlorenz/doctoc)*

- [一、标题](#%E4%B8%80%E6%A0%87%E9%A2%98)
  - [1.1 层级](#11-%E5%B1%82%E7%BA%A7)
  - [1.2 原则](#12-%E5%8E%9F%E5%88%99)
- [二、文本](#%E4%BA%8C%E6%96%87%E6%9C%AC)
  - [2.1 字间距](#21-%E5%AD%97%E9%97%B4%E8%B7%9D)
  - [2.2 句子](#22-%E5%8F%A5%E5%AD%90)
  - [2.3 写作风格](#23-%E5%86%99%E4%BD%9C%E9%A3%8E%E6%A0%BC)
  - [2.4 英文处理](#24-%E8%8B%B1%E6%96%87%E5%A4%84%E7%90%86)
- [三、段落](#%E4%B8%89%E6%AE%B5%E8%90%BD)
  - [3.1 原则](#31-%E5%8E%9F%E5%88%99)
  - [3.2 引用](#32-%E5%BC%95%E7%94%A8)
- [四、数值](#%E5%9B%9B%E6%95%B0%E5%80%BC)
  - [4.1 半角数字](#41-%E5%8D%8A%E8%A7%92%E6%95%B0%E5%AD%97)
  - [4.2 千分号](#42-%E5%8D%83%E5%88%86%E5%8F%B7)
  - [4.3 货币](#43-%E8%B4%A7%E5%B8%81)
  - [4.4 数值范围](#44-%E6%95%B0%E5%80%BC%E8%8C%83%E5%9B%B4)
  - [4.5 变化程度的表示法](#45-%E5%8F%98%E5%8C%96%E7%A8%8B%E5%BA%A6%E7%9A%84%E8%A1%A8%E7%A4%BA%E6%B3%95)
- [五、标点符号](#%E4%BA%94%E6%A0%87%E7%82%B9%E7%AC%A6%E5%8F%B7)
  - [5.1 原则](#51-%E5%8E%9F%E5%88%99)
  - [5.2 句号](#52-%E5%8F%A5%E5%8F%B7)
  - [5.3 逗号](#53-%E9%80%97%E5%8F%B7)
  - [5.4 顿号](#54-%E9%A1%BF%E5%8F%B7)
  - [5.5 分号](#55-%E5%88%86%E5%8F%B7)
  - [5.6 引号](#56-%E5%BC%95%E5%8F%B7)
  - [5.7 括号](#57-%E6%8B%AC%E5%8F%B7)
  - [5.8 冒号](#58-%E5%86%92%E5%8F%B7)
  - [5.9 省略号](#59-%E7%9C%81%E7%95%A5%E5%8F%B7)
  - [5.10 感叹号](#510-%E6%84%9F%E5%8F%B9%E5%8F%B7)
  - [5.11 破折号](#511-%E7%A0%B4%E6%8A%98%E5%8F%B7)
  - [5.12 连接号](#512-%E8%BF%9E%E6%8E%A5%E5%8F%B7)
- [六、Markdown](#%E5%85%ADmarkdown)
  - [6.1 标题](#61-%E6%A0%87%E9%A2%98)
  - [6.2 段落](#62-%E6%AE%B5%E8%90%BD)
  - [6.3 列表](#63-%E5%88%97%E8%A1%A8)
  - [6.4 区块](#64-%E5%8C%BA%E5%9D%97)
  - [6.5 代码](#65-%E4%BB%A3%E7%A0%81)
  - [6.6 链接](#66-%E9%93%BE%E6%8E%A5)
  - [6.7 图片](#67-%E5%9B%BE%E7%89%87)
  - [6.8 表格](#68-%E8%A1%A8%E6%A0%BC)
  - [6.9 高级](#69-%E9%AB%98%E7%BA%A7)
- [七、文档体系](#%E4%B8%83%E6%96%87%E6%A1%A3%E4%BD%93%E7%B3%BB)
  - [7.1 结构](#71-%E7%BB%93%E6%9E%84)
  - [7.2 文件名](#72-%E6%96%87%E4%BB%B6%E5%90%8D)
- [八、重要问题](#%E5%85%AB%E9%87%8D%E8%A6%81%E9%97%AE%E9%A2%98)
  - [8.1 为什么文件名要小写？](#81-%E4%B8%BA%E4%BB%80%E4%B9%88%E6%96%87%E4%BB%B6%E5%90%8D%E8%A6%81%E5%B0%8F%E5%86%99)
  - [8.2 技术文档与文章的区别？](#82-%E6%8A%80%E6%9C%AF%E6%96%87%E6%A1%A3%E4%B8%8E%E6%96%87%E7%AB%A0%E7%9A%84%E5%8C%BA%E5%88%AB)
  - [8.3 技术文档与文章的核心？](#83-%E6%8A%80%E6%9C%AF%E6%96%87%E6%A1%A3%E4%B8%8E%E6%96%87%E7%AB%A0%E7%9A%84%E6%A0%B8%E5%BF%83)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

# 一、标题

## 1.1 层级

标题分为四级。

- 一级标题：文章的标题
- 二级标题：文章主要部分的大标题
- 三级标题：二级标题下面一级的小标题
- 四级标题：三级标题下面某一方面的小标题

下面是示例。

```markdown
# 一级标题

## 二级标题

### 三级标题

#### 四级标题
```

## 1.2 原则

**（1）一级标题下，不能直接出现三级标题**

示例：下面的文章结构，缺少二级标题。

```markdown
# 一级标题

### 三级标题
```

**（2）标题要避免孤立编号（即同级标题只有一个）**

示例：下面的文章结构，`二级标题 A` 只包含一个三级标题，完全可以省略 `三级标题 A`。

```markdown
## 二级标题 A

### 三级标题 A

## 二级标题 B
```

**（3）下级标题不重复上一级标题的名字**

示例：下面的文章结构，二级标题与下属的三级标题同名，建议避免。

```markdown
## 概述

### 概述
```

**（4）谨慎使用四级标题，尽量避免出现，保持层级的简单，防止出现过于复杂的章节**

如果三级标题下有并列性的内容，建议只使用项目列表（Item list）。

示例：下面的结构二要好于结构一。结构一适用的场景，主要是较长篇幅的内容。

```markdown
结构一

### 三级标题

#### 四级标题 A

#### 四级标题 B

#### 四级标题 C

结构二

### 三级标题

**（1）A**

**（2）B**

**（3）C**
```

# 二、文本

## 2.1 字间距

**（1）全角中文字符与半角英文字符之间，应有一个半角空格**

```text
错误：本文介绍如何快速启动Windows系统。

正确：本文介绍如何快速启动 Windows 系统。
```

**（2）全角中文字符与半角阿拉伯数字之间，有没有半角空格都可，但必须保证风格统一，不能两种风格混杂**

```text
正确：2011年5月15日，我订购了5台笔记本电脑与10台平板电脑。

正确：2011 年 5 月 15 日，我订购了 5 台笔记本电脑与 10 台平板电脑。(个人推荐)
```

半角的百分号，视同阿拉伯数字。

```text
正确：今年我国经济增长率是6.5%。

正确：今年我国经济增长率是 6.5%。（个人推荐）
```

**（3）英文单位若不翻译，单位前的阿拉伯数字与单位符号之间，应留出适当的空隙**

```text
例1：一部容量为 16 GB 的智能手机

例2：1 h = 60 min = 3,600 s
```

**（4）半角英文字符和半角阿拉伯数字，与全角标点符号之间不留空格**

```text
错误：他的电脑是 MacBook Air 。

正确：他的电脑是 MacBook Air。
```

## 2.2 句子

**（1）避免使用长句**

不包含任何标点符号的单个句子，或者以逗号分隔的句子构件，长度尽量保持在 20 个字以内；20～29 个字的句子，可以接受；30～39 个字的句子，语义必须明确，才能接受；多于 40 个字的句子，任何情况下都不能接受。

```text
错误：本产品适用于从由一台服务器进行动作控制的单一节点结构到由多台服务器进行动作控制的并行处理程序结构等多种体系结构。

正确：本产品适用于多种体系结构。无论是由一台服务器（单一节点结构），还是由多台服务器（并行处理结构）进行动作控制，均可以使用本产品。
```

逗号分割的长句，总长度不应该超过 100 字或者正文的 3 行。

**（2）尽量使用简单句和并列句，避免使用复合句**

```text
并列句：他昨天生病了，没有参加会议。

复合句：那个昨天生病的人没有参加会议。
```

**（3）同样一个意思，尽量使用肯定句表达，不使用否定句表达**

```text
错误：请确认没有接通装置的电源。

正确：请确认装置的电源已关闭。
```

**（4）避免使用双重否定句**

```text
错误：没有删除权限的用户，不能删除此文件。

正确：用户必须拥有删除权限，才能删除此文件。
```

## 2.3 写作风格

**（1）尽量不使用被动语态，改为使用主动语态**

```text
错误：假如此软件尚未被安装，

正确：假如尚未安装这个软件，
```

**（2）不使用非正式的语言风格**

```text
错误：Lady Gaga 的演唱会真是酷毙了，从没看过这么给力的表演！！！

正确：无法参加本次活动，我深感遗憾。
```

**（3）不使用冷僻、生造或者文言文的词语，而要使用现代汉语的常用表达方式**

```text
错误：这是唯二的快速启动的方法。

正确：这是仅有的两种快速启动的方法。
```

**（4）用对 “的”、“地”、“得”**

```text
她露出了开心的笑容。
（形容词＋的＋名词）

她开心地笑了。
（副词＋地＋动词）

她笑得很开心。
（动词＋得＋副词）
```

**（5）使用代词时（比如 “其”、“该”、“此”、“这” 等词），必须明确指代的内容，保证只有一个含义**

```text
错误：从管理系统可以监视中继系统和受其直接控制的分配系统。

正确：从管理系统可以监视两个系统：中继系统和受中继系统直接控制的分配系统。
```

**（6）名词前不要使用过多的形容词**

```text
错误：此设备的使用必须在接受过本公司举办的正式的设备培训的技师的指导下进行。

正确：此设备必须在技师的指导下使用，且指导技师必须接受过由本公司举办的正式设备培训。
```

## 2.4 英文处理

**（1）英文原文如果使用了复数形式，翻译成中文时，应该将其还原为单数形式**

```text
英文：⋯information stored in random access memory (RAMs)⋯

中文：……存储在随机存取存储器（RAM）里的信息……
```

**（2）外文缩写可以使用半角圆点(`.`)表示缩写**

```text
U.S.A.
Apple, Inc.
```

**（3）表示中文时，英文省略号（`⋯`）应改为中文省略号（`……`）**

```text
英文：5 minutes later⋯

中文：5 分钟过去了……
```

**（4）英文书名或电影名改用中文表达时，双引号应改为书名号**

```text
英文：He published an article entitled "The Future of the Aviation".

中文：他发表了一篇名为《航空业的未来》的文章。
```

**（5）第一次出现英文词汇时，在括号中给出中文标注。此后再次出现时，直接使用英文缩写即可**

```text
IOC（International Olympic Committee，国际奥林匹克委员会）。这样定义后，便可以直接使用 “IOC” 了。
```

**（6）专有名词中每个词第一个字母均应大写，非专有名词则不需要大写**

```text
“American Association of Physicists in Medicine”（美国医学物理学家协会）是专有名词，需要大写。

“online transaction processing”（在线事务处理）不是专有名词，不应大写。
```

# 三、段落

## 3.1 原则

- 一个段落只能有一个主题，或一个中心句子
- 段落的中心句子放在段首，对全段内容进行概述。后面陈述的句子为核心句服务
- 一个段落的长度不能超过七行，最佳段落长度小于等于四行
- 段落的句子语气要使用陈述和肯定语气，避免使用感叹语气
- 段落之间使用一个空行隔开
- 段落开头不要留出空白字符
- 文本句子正常情况下均该以句号结尾

## 3.2 引用

引用第三方内容时，应注明出处。

```text
One man’s constant is another man’s variable. — Alan Perlis
```

如果是全篇转载，请在全文开头显著位置注明作者和出处，并链接至原文。

```text
本文转载自 WikiQuote
```

使用外部图片时，必须在图片下方或文末标明来源。

```text
本文部分图片来自 Wikipedia
```

# 四、数值

## 4.1 半角数字

阿拉伯数字一律使用半角形式，不得使用全角形式。

```text
错误：这件商品的价格是１０００元。

正确：这件商品的价格是 1000 元。
```

## 4.2 千分号

数值为千位以上，应添加千分号（半角逗号）。

```text
XXX 公司的实收资本为 ￥1,258,000 人民币。
```

对于 4 位以下的数值，千分号是选用的，比如 `1000` 和 `1,000` 都可以接受。对于 4 位以上的数值，千分号是必须的。

## 4.3 货币

货币应为阿拉伯数字，并在数字前写出货币符号，或在数字后写出货币中文名称。

```text
$1,000
1,000 美元
```

英文的货币名称，建议参考国际标准 [ISO 4217](https://en.wikipedia.org/wiki/ISO_4217)。

## 4.4 数值范围

表示数值范围时，用 `～` 或 `——` 连接。参见《标点符号》一节的 “连接号” 部分。

带有单位或百分号时，两个数字建议都要加上单位或百分号。

```text
132kg～234kg

67%～89%
```

## 4.5 变化程度的表示法

数字的增加要使用 “增加了”、“增加到”。“了” 表示增量，“到” 表示定量。

```text
增加到过去的两倍
（过去为一，现在为二）

增加了两倍
（过去为一，现在为三）
```

数字的减少要使用 “降低了”、“降低到”。“了” 表示增量，“到” 表示定量。

```text
降低到百分之八十
（定额是一百，现在是八十）

降低了百分之八十
（原来是一百，现在是二十）
```

不能用 “降低 N 倍 ” 或 “减少 N 倍” 的表示法，要用 “降低百分之几” 或 “减少百分之几”。因为减少（或降低）一倍表示数值原来为一百，现在等于零。

# 五、标点符号

## 5.1 原则

**（1）中文语句的标点符号，均应该采取全角符号，这样可以与全角文字保持视觉的一致**

**（2）如果整句为英文，则该句使用英文/半角标点**

**（3）句号、问号、叹号、逗号、顿号、分号和冒号不得出现在一行之首**

**（4）点号（句号、逗号、顿号、分号、冒号）不得出现在标题的末尾，而标号（引号、括号、破折号、省略号、书名号、着重号、间隔号、叹号、问号）可以**

## 5.2 句号

**（1）中文语句的结尾处应该用全角句号（`。`）**

**（2）句子末尾用括号加注时，句号应在括号之外**

```text
错误：关于文件的输出，请参照第 1.3 节（见第 26 页。）

正确：关于文件的输出，请参照第 1.3 节（见第 26 页）。
```

## 5.3 逗号

**（1）逗号（`，`）表示句子内部的一般性停顿**

**（2）注意避免 “一逗到底”，即整个段落除了结尾，全部停顿都使用逗号**

## 5.4 顿号

**（1）中文句子内部的并列词，应该用全角顿号(`、`) 分隔，而不用逗号，即使存在并列词是英语也是如此**

```text
错误：我最欣赏的科技公司有 Google, Facebook, 腾讯, 阿里和百度等。

正确：我最欣赏的科技公司有 Google、Facebook、腾讯、阿里和百度等。
```

**（2）英文句子中，并列词语之间使用半角逗号（`,`）分隔**

```text
例句：Microsoft Office includes Word, Excel, PowerPoint, Outlook and other components.
```

**（3）中文句子内部的并列词，最后一个尽量使用（`和`）来连接，使句子读起来更加连贯，下面两个句子都可以，第二个更优**

```text
正确：我最欣赏的科技公司有 Google、Facebook、腾讯、阿里，以及百度等。

正确：我最欣赏的科技公司有 Google、Facebook、腾讯、阿里和百度等。
```

## 5.5 分号

**（1）分号（`；`）表示复句内部并列分句之间的停顿**

## 5.6 引号

**（1）引用时，应该使用全角双引号（`“ ”`），注意前后双引号不同**

```text
例句：许多人都认为客户服务的核心是 “友好” 和 “专业”。
```

**（2）引号里面还要用引号时，外面一层用双引号，里面一层用单引号（`‘ ’`），注意前后单引号不同**

```text
例句：鲍勃解释道：“我要放音乐，可萨利说，‘不行！’。”
```

**（3）引号与前后文字之间应该用一个空格隔开，与标点符号之间则不用**

## 5.7 括号

**（1）使用全角圆括号（`（）`），括号前后不加空格。使用半角圆括号（`()`），括号前后加一个空格**

```text
例句：请确认所有的连接（电缆和接插件）均安装牢固。

例句：I love you (GitHub).
```

圆括号前后遇到标点符号不用加空格。

**（2）几种括号的中英文名称**

|       |            英文             |   中文 |
| ----- | :-------------------------: | -----: |
| `{ }` |  braces 或 curly brackets   | 大括号 |
| `[ ]` | square brackets 或 brackets | 方括号 |
| `< >` |       angled brackets       | 尖括号 |
| `( )` |         parentheses         | 圆括号 |

**（3）中文句子中只能出现全角圆括号（`（）`），无论括号中是中文还是英文。英文句子中只能出现半角圆括号（`()`），无论括号中是英文还是中文**

## 5.8 冒号

**（1）全角冒号（`：`）常用在需要解释的词语后边，引出解释和说明**

```text
例句：请确认以下几项内容：时间、地点、活动名称和来宾数量。
```

**（2）中文句子中一律使用全角冒号（`：`），无论冒号前是中文还是英文。英文句子中一律使用半角冒号（`:`），无论冒号前是英文还是中文**

```text
Markdown：是一种轻量级标记语言，它允许人们使用易读易写的纯文本格式编写文档。
```

**（3）表示时间时，应使用半角冒号（`:`）**

```text
例句：早上 8:00
```

## 5.9 省略号

**（1）省略号（`……`）表示语句未完、或者语气的不连续**

**（2）省略号占两个汉字空间、包含六个省略点，不要使用 `。。。` 或 `...` 等非标准形式**

**（3）省略号不应与 “等” 这个词一起使用**

```text
错误：我们为会餐准备了香蕉、苹果、梨…等各色水果。

正确：我们为会餐准备了各色水果，有香蕉、苹果、梨……

正确：我们为会餐准备了香蕉、苹果、梨等各色水果。
```

## 5.10 感叹号

**（1）应该使用平静的语气叙述，尽量避免使用感叹号（`！`）**

**（2）不得多个感叹号连用，比如 `！！` 和 `!!!`**

## 5.11 破折号

**（1）破折号 `————` 一般用于进一步解释**

**（2）破折号应占两个汉字的位置。如果破折号本身只占一个汉字的位置，那么前后应该留出一个半角空格**

```text
例句：直觉————尽管它并不总是可靠的————告诉我，这事可能出了些问题。

例句：直觉 —— 尽管它并不总是可靠的 —— 告诉我，这事可能出了些问题。
```

## 5.12 连接号

**（1）连接号用于连接两个类似的词**

**（2）以下场合应该使用直线连接号（`-`），占一个半角字符的位置**

- 两个名词的复合
- 图表编号

```text
例句：氧化-还原反应

例句：图 1-1
```

**（3）数值范围（例如日期、时间或数字）应该使用波浪连接号（`～`），占一个全角字符的位置**

```text
例句：2009 年～2011 年
```

注意，波浪连接号前后两个值都应该加上单位。

**（4）波浪连接号也可以用汉字 “至” 代替**

```text
例句：周围温度：-20°C 至 -10°C
```

# 六、Markdown

>  Markdown 中所有文本内容均建议按照上述规范来书写。

## 6.1 标题

只使用三级标题。

```markdown
# 一级标题

## 二级标题

### 三级标题
```

四级标题。

```markdown
<!-- 全角圆括号加粗 -->
**（1）标题**
```

一到四级标题末尾不能出现句号。

单个四级标题直接加粗即可，不要写序号。

四级标题后请使用列表。

**开头规范**

```markdown
# 名称

**第二名称**

> 声明

**目录**

# 一、一级标题
或者
# 第一章 一级标题

## 1.1 二级标题

## 1.1.1 三级标题

**（1）四级标题**
```

## 6.2 段落

四级标题及关键字才能使用 “加粗”，不要使用 “斜体” 及 “高亮”。

```markdown
**Markdown**：是一种轻量级标记语言，它允许人们使用易读易写的纯文本格式编写文档。
```

>  **Markdown**：是一种轻量级标记语言，它允许人们使用易读易写的纯文本格式编写文档。

标题上下不要使用分割线。

```markdown
---
```

## 6.3 列表

同一列表不能分隔开，建议列表元素单行字数不要过长。

两个及以上元素才能使用列表，单个元素不能用列表表示。

列表每行的结束不加句号。

```markdown
<!-- 无序列表 -->
- 第一项
- 第二项
- 第三项

<!-- 有序列表 -->
1. 第一项
2. 第二项
3. 第三项
```

## 6.4 区块

区块使用在声明、引用、特殊强调和非主体内容部分。

区块严禁嵌套，区块中可以使用列表。

```markdown
> 区块中使用列表
> 1. 第一项
> 2. 第二项
> 3. 第三项
> - 第一项
> - 第二项
> - 第三项
```

> 区块中使用列表
> 1. 第一项
> 2. 第二项
> 3. 第三项
> - 第一项
> - 第二项
> - 第三项

## 6.5 代码

段落中的片段代码适量使用，关键字不要重复使用片段代码。

片段代码前后遇到文字留一个空格，遇到标点符号不用留空格。

```markdown
这是一个 `片段代码` 示 `例`。
```

> 这是一个 `片段代码` 示 `例`。

代码块严格标注类型。

```markdown
<!-- 普通文本 -->
​```text
普通文字标注 text 类型
​```

<!-- markdown -->
​```markdown
### Markdown 文本标注为 markdown 类型。
​```

<!-- 命令行 -->
​```bash
$ javac Test.java
# 编译 Test.java 文件。
# 命令行统一为 bash 类型，且每条命令前加上 '$'，其中 '#' 为 bash 注释。
​```

<!-- 代码 -->
​```java
System.out.println("Hello World!");
// 打印 Hello World!
/* 根据不同的编程语言选择不同的类型。 */
​```
```

>  <!-- 普通文本 -->

```text
普通文字标注 text 类型
```

>  <!-- markdown -->

```markdown
### Markdown 文本标注为 markdown 类型。
```

>  <!-- 命令行 -->

```bash
$ javac Test.java
# 编译 Test.java 文件。
# 命令行统一为 bash 类型，且每条命令前加上 '$'，其中 '#' 为 bash 注释。
```

>  <!-- 代码 -->

```java
System.out.println("Hello World!");
// 打印 Hello World!
/* 根据不同的编程语言选择不同的类型。 */
```

## 6.6 链接

非特殊情况不要直接暴露链接地址。

链接左右为文字时留一个空格，为标点符号时不用。

```markdown
建议：[bilibili](https://www.bilibili.com/)

不建议：<https://www.bilibili.com/>
```

> 建议：[bilibili](https://www.bilibili.com/)
>
> 不建议：<https://www.bilibili.com/>

## 6.7 图片

合理调整图片大小。

```markdown
![RUNOOB 图标](http://static.runoob.com/images/runoob-logo.png "RUNOOB")

<img src="http://static.runoob.com/images/runoob-logo.png" width="50%">
```

## 6.8 表格

表格非特殊情况一律默认左对齐。

```markdown
|  表头   | 表头  |
|  ----  | ----  |
| 单元格  | 单元格 |
| 单元格  | 单元格 |
```

| 表头   | 表头   |
| ------ | ------ |
| 单元格 | 单元格 |
| 单元格 | 单元格 |

## 6.9 高级

> 以下用法存在一定风险，不建议使用

```markdown
<!-- 键盘按键 -->
使用 <kbd>Ctrl</kbd>+<kbd>Alt</kbd>+<kbd>Del</kbd> 重启电脑
```

>  使用 <kbd>Ctrl</kbd>+<kbd>Alt</kbd>+<kbd>Del</kbd> 重启电脑

```markdown
<!-- 转义 -->
**文本加粗** 
\*\* 正常显示星号 \*\*
```

> **文本加粗** 
> \*\* 正常显示星号 \*\*

```markdown
<!-- 居中 -->
<center>中<center>
```

> <center>中<center>

```markdown
<!-- 左对齐 -->
<p align="left">左</p>
```

> <p align="left">左</p>

```markdown
<!-- 右对齐 -->
<p align="right">右</p>
```

> <p align="right">右</p>


# 七、文档体系

## 7.1 结构

软件手册是一部完整的书，建议采用下面的结构。

- **简介**（Introduction）： [必备] [文件] 提供对产品和文档本身的总体的、扼要的说明
- **快速上手**（Getting Started）：[可选] [文件] 如何最快速地使用产品
- **入门篇**（Basics）： [必备] [目录] 又称 “使用篇”，提供初级的使用教程
  - **环境准备**（Prerequisite）：[必备] [文件] 软件使用需要满足的前置条件
  - **安装**（Installation）：[可选] [文件] 软件的安装方法
  - **设置**（Configuration）：[必备] [文件] 软件的设置
- **进阶篇**（Advanced)：[可选] [目录] 又称 “开发篇”，提供中高级的开发教程
- **API**（Reference）：[可选] [目录|文件] 软件 API 的逐一介绍
- **FAQ**：[可选] [文件] 常见问题解答
- **附录**（Appendix）：[可选] [目录] 不属于教程本身、但对阅读教程有帮助的内容
  - **Glossary**：[可选] [文件] 名词解释
  - **Recipes**：[可选] [文件] 最佳实践
  - **Troubleshooting**：[可选] [文件] 故障处理
  - **ChangeLog**：[可选] [文件] 版本说明
  - **Feedback**：[可选] [文件] 反馈方式

下面是两个真实范例，可参考。

- [Redux 手册](https://redux.js.org/introduction/getting-started)
- [Atom 手册](http://flight-manual.atom.io/)

## 7.2 文件名

文档的文件名不得含有空格。

文件名必须使用半角字符，不得使用全角字符。这也意味着，中文不能用于文件名。

```text
错误：名词解释.md

正确：glossary.md
```

文件名建议只使用小写字母，不使用大写字母。

```text
错误：TroubleShooting.md

正确：troubleshooting.md 
```

为了醒目，某些说明文件的文件名，可以使用大写字母，比如 `README`、`LICENSE`。

文件名包含多个单词时，单词之间建议使用半角的连词线（`-`）分隔。

```text
不佳：advanced_usage.md

正确：advanced-usage.md
```

# 八、重要问题

## 8.1 为什么文件名要小写？

**（1）可移植性**

Linux 系统是大小写敏感的，而 Windows 系统和 Mac 系统正好相反，大小写不敏感。一般来说，这不是大问题。

但是，如果两个文件名只有大小写不同，其他都相同，跨平台就会出问题。

 - `foobar`
 - `Foobar`
 - `FOOBAR`
 - `fOObAr`

上面四个文件名，Windows 系统会把它们都当作 `foobar`。如果它们同时存在，你可能没办法打开后面三个文件。

另一方面，在 Mac 系统上开发时，有时会疏忽，写错大小写。

 ```javascript
 // 正确文件名是 MyModule.js
 const module = require('./myModule');
 ```

上面的代码在 Mac 上面可以运行，因为 Mac 认为 `MyModule.js` 和 `myModule.js` 是同一个文件。但是，一旦代码到服务器运行就会报错，因为 Linux 系统找不到 `myModule.js`。

如果所有的文件名都采用小写，就不会出现上面的问题，可以保证项目有良好的可移植性。

**（2）易读性**

小写文件名通常比大写文件名更易读，比如 `accessibility.txt` 就比 `ACCESSIBILITY.TXT` 易读。

有人习惯使用 [驼峰命名法](https://baike.baidu.com/item/%E9%AA%86%E9%A9%BC%E5%91%BD%E5%90%8D%E6%B3%95?fromtitle=%E9%A9%BC%E5%B3%B0%E5%91%BD%E5%90%8D%E6%B3%95&fromid=7560610)，单词的第一个字母大写，其他字母小写。这种方法的问题是，如果遇到全部是大写的缩略词，就会不适用。

比如，一个姓李的纽约特警，无论写成 `NYPoliceSWATLee` 还是 `NyPoliceSwatlee`，都怪怪的，还是写成 `ny-police-swat-lee` 比较容易接受。

**（3）易用性**

某些系统会生成一些预置的用户目录，采用首字母大写的目录名。比如，Ubuntu 在用户主目录会默认生成  `Downloads`、 `Pictures`、`Documents ` 等目录。

Mac 系统一部分系统目录也是大写的，比如 `/Library/Audio/Apple Loops/`。

另外，某些常见的配置文件或说明文件，也采用大写的文件名，比如 `Makefile`、`INSTALL`、`CHANGELOG`、`.Xclients` 和 `.Xauthority` 等等。

所以，用户的文件都采用小写文件名，就很方便与上面这些目录或文件相区分。

那问到底，为什么操作系统会采用这样的大写文件名？原因也很简单，因为早期 Unix 系统上，`ls` 命令先列出大写字母，再列出小写字母，大写的路径会排在前面。因此，如果目录名或文件名是大写的，就比较容易被用户首先看到。

**（4）便捷性**

文件名全部小写，还有利于命令行操作。比如，某些命令可以不使用 `-i` 参数了。

 ```bash
 # 大小写敏感的搜索
 $ find . -name abc
 $ locate "*.htmL"
 
 # 大小写不敏感的搜索
 $ find . -iname abc
 $ locate -i "*.HtmL"
 ```

另外，大写字母需要按下 Shift 键，多多少少有些麻烦。如果文件名小写，就不用碰这个键了，不仅省事，还可以提高打字速度。

程序员长时间使用键盘，每分钟少按几次 Shift，一天下来就可以省掉很多手指动作。长年累月，也是对自己身体的一种保护。

综上所述，文件名全部使用小写字母和连词线（all-lowercase-with-dashes），是一种值得推广的正确做法。

## 8.2 技术文档与文章的区别？

- 技术文档注重：专业、严谨、严肃、简练
- 技术文章注重：图文并茂、通俗易懂、妙趣横生

## 8.3 技术文档与文章的核心？

**（1）技术文档**

- 必要的声明

- 清晰严谨的章节安排
- 单独设计合理的目录导航页
- 删减一切非必要图片
- 严谨地运用链接
- 合理留白

**（2）技术文章**

- 必要的声明
- 清晰直观的目录
- 合理布局图文内容
- 图片适量且具有代表性
- 注意文章的平台可移植性
- 搭建合理的分享传播途径
- 注重通俗易懂
- 注重趣味
- 注重美观
- 合理留白