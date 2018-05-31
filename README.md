---

https://github.com/guodongxiaren/README/blob/master/README.md

https://www.webpagefx.com/tools/emoji-cheat-sheet/

https://daringfireball.net/projects/markdown/syntax

https://www.jianshu.com/p/82e730892d42




标题
--

# 一级标题
## 二级标题
### 三级标题
#### 四级标题
##### 五级标题
###### 六级标题

这是一级标题
==
这是二级标题
--

>'-'上面的文本会被转成二级标题  
'='上面的文本会被转成一级标题  
'#'加空格加标题，有几个'#'就是几级标题，最大六级


## 普通文本
直接回车不能换行  
在末尾加两个空格后回车可以换行

或者在两行文本之间加一个空行

就是行间距有点大<br>
或者可以使用\<br>标签换行


## 文本块
    1个tab
    4个空格
      6个空格

```
三个反引号
```


## 表格
| 左对齐   |   右对齐 | 居中 |
| :------- | -------: | :---:|
| Computer | 1600 USD | 5    |
| Phone    |   12 USD | 12   |
| Pipe     |    1 USD | 234  |


## 代码块
```c++
// c++
#include <iostream>
using namespace std;
int main(int argc, char **argv)
{
    cout << "Hello World!" << endl;
    return 0;
}
```
```java
// java
public class Hello {
    public static void main(String []args) {
        System.out.println("Hello World!");
    }
}
```
```js
// js
document.getElementById("myH1").innerHTML="Hello World!";
```
```sh
# sh
echo "Hello World!"
```
```python
# python
print("Hello World!")
```


## 引用
> 记录，成为更好的自己。 ——有道云笔记

## 区块引用
> 数据结构
>> 树
>>> 二叉树
>>>> 平衡二叉树
>>>>> 满二叉树


## 无序列表
- 列表 1
    - 列表 1.1
    - 列表 1.2
        - 列表 1.2.1
        - 列表 1.2.2
- 列表 2

## 有序列表
1. 列表 1
    1. 列表 1.1
    2. 列表 1.2
        1. 列表 1.2.1
        2. 列表 1.2.2
2. 列表 2

## 任务列表
- [x] 已完成
    - [x] 已完成
- [ ] 待办
    - [ ] 待办
        - [x] 已完成
        - [ ] 待办
    - [x] 待办


## 分割线 ***/___/---
这是分割线上面的内容
***
___
---
这是分割线下面的内容


## 锚点（有道云笔记不支持）
[返回标题](#标题)


## 代码/高亮/标签
| # | 语法 | 效果 |
| - | ---- | ---- |
| 1 | \`代码\` , \`高亮\` , \`标签\` | `代码` , `高亮` , `标签` |


## 字体格式
| # | 语法 | 效果 |
| - | ---- | ---- |
| 1 | `*这是斜体*` | *这是斜体* |
| 2 | `_这是斜体_` | _这是斜体_ |
| 3 | `**这是粗体**` | **这是粗体** |
| 4 | `__这是粗体__` | __这是粗体__ |
| 5 | `~~这是删除线~~` | ~~这是删除线~~ |
| 6 | `++这是下划线++` | ++这是下划线++ |
> 注意：符号和文本之间没有空格


## 超链接
| # | 语法 | 效果 
| - | ---- | ---- 
| 1 | `[有道云笔记官网](http://note.youdao.com/ "http://note.youdao.com/")` | [有道云笔记官网](http://note.youdao.com/ "http://note.youdao.com/") 


## 图片
| # | 语法 | 效果 
| - | ---- | ---- 
| 1 | `![Logo](http://note.youdao.com/favicon.ico "有道云笔记Logo")` | ![Logo](http://note.youdao.com/favicon.ico "有道云笔记Logo")


## 图片链接
| # | 语法 | 效果 |
| - | ---- | ---- |
| 1 | `[![YDNote-Logo]](http://note.youdao.com/ "YDNote官网")`  |[![YDNote-Logo]](http://note.youdao.com/ "YDNote官网") |
| 2 |`[![](http://note.youdao.com/favicon.ico "有道云笔记官网 http://note.youdao.com/")][YDNote]` | [![](http://note.youdao.com/favicon.ico "有道云笔记官网 http://note.youdao.com/")][YDNote] |
| 3 | `[![YDNote-Logo]] [YDNote]` | [![YDNote-Logo]][YDNote] |

[YDNote]:http://note.youdao.com/ "有道云笔记官网"
[YDNote-Logo]:http://note.youdao.com/favicon.ico "有道云笔记LOGO"

> URL标识符  
> 1. `[YDNote]:http://note.youdao.com/ "有道云笔记官网"`
> 2. `[YDNote-Logo]:http://note.youdao.com/favicon.ico "有道云笔记LOGO"`


## diff
```diff
+ 鸟宿池边树，僧敲月下门
- 鸟宿池边树，僧推月下门
```


## 书写数学公式
### Mathematical formula `$ y = x^2 $`
Inline math: `$ \dfrac{\tfrac{1}{2}[1-(\tfrac{1}{2})^n]}{1-\tfrac{1}{2}} = s_n $`

Math block:
```math
\oint_C x^3\, dx + 4y^2\, dy

2 = \left(\frac{\left(3-x\right) \times 2}{3-x}\right)
```


## 表情（有道云笔记不支持）
:blush: 

## 流程图（有道云笔记特有的）
```
graph TB
    A[Christmas] --> B(Go shopping)
    B --> C{Let me think}
    C --> |One| D[Laptop]
    C --> |Two| E[iPhone]
    C --> |Three| F[Car]
```

### 从上到下
```
graph TB
A-->B
```
### 从下到上
```
graph BT
A-->B
```
### 从左到右
```
graph LR
A-->B
```
### 从右到左
```
graph RL
A-->B
```

### 形状
```
graph LR
A[直角四边形]
B(圆角四边形)
C((圆形))
D{菱形}
```

### 箭头
```
graph LR
A[A]---B[B]
C[A]-->D[B]
E[A]-->|条件|F[B]
```

## 序列图
```
sequenceDiagram
    loop every day
        Alice ->> John : Hello John, How are you?
        John ->> Alice : Great!
    end
```

## 甘特图
```
gantt
dateFormat YYYY-MM-DD
title 产品计划表
section 初期阶段
明确需求: 2018-06-01, 10d
section 中期阶段
跟进开发: 2018-06-05, 15d
section 后期阶段
走查测试: 2018-06-20, 9d
```

