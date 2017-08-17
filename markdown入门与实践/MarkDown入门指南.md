# 标题
标题是每篇文章必备而且最常用的格式。

在Markdown中，如果想将一段文字定义为标题，只需要在这段文字前面加上 #，再在 # 后加一个空格即可。还可增加二、三、四、五、六级标题，总共六级，只需要增加 # ，增加一个 # ，标题字号相应降低一级。如下：
# 一号标题
## 二号标题
### 三号标题
#### 四号标题
##### 五号标题
###### 六号标题

# 空行
对于空行，需要在编辑模式下空整整一行，才能被认定为是空行，但是对于空一行和空两行在预览模式下没有任何的区别。

# 换行
对于编辑模式中即使使用回车键换行，实际显示的是一个小空格编辑模式中由于单行位置不够导致的换行，在实际显示中会由于显示页面的大小自行更改。  
==正式的换行应该为在两个空格后使用换行符(Enter键)==

# 强调
markdown中使用两个连等号括起来的部分表示强调其中的内容==强调==
```
==强调==
```

# 编辑器
对于编辑器我觉得最好的编辑器是==Atom==，这个编辑器是Github公司开发的并且支持开源，而且有相当多的插件，支持代码表格，代码向下滚动，导出为PDF格式，插入图片，插入代码自动提醒等功能。==更主要的是在国外有大量的用户，并且能够对其进行及时维护。==

# 列表
- ## 无序列表
列表格式也很常用，它可以让你的文稿变得井井有条。在Markdown 中，你只需要在文字前面加上-就可以了;如果你希望是有序列表，在文字前面加上 1. 2. 3. 即可。  
==注意-和1.与文字之间要保留一个字符的空格==
- 列表1
    - 列表1.1 ==（在一行的开头Tab- 列表1.1）==
        - 列表1.1.1（转到下一行后紧接着上一行开头使用Tab- 列表1.1.1即可）
            - 列表1.1.1.1(同上，是一种递归的过程)
                - 列表1.1.1.1.1（同上，是一种递归的过程）
- 列表2
- 列表3

- ## 有序列表
- #### 对于列表和标题也可以相互嵌套使用，具体是先使用列表样式在使用标题样式
1. ## 列表1
    1. 列表1.1 ==注意只能使用1.或者2.类似标注，1.1这样标注不支持==
    1. 列表1.2 ==注意1.和2.的效果相同，形式相同即可，与具体数字符号无关==
    2. 列表1.3
        1. 列表1.3.1 
        2. 列表1.3.2
            1. 列表1.3.2.1==第四级==
2. ## 列表2 

# 引用
如果你需要在文稿中引用一段别处的句子，那么就要用到「引用」格式。

在引用文字前加上 > 并与文字保留一个字符的空格，即可。
> Github about Me https://github.com/Asurada2015

# 粗体和斜体
Markdown 的粗体和斜体也非常简单：

用两个 * 包含一段文本就是粗体的语法；

用一个 * 包含一段文本就是斜体的语法。  
*斜体*  
## *斜体*  
**粗体**  
## **粗体**  
 
```
代码为
*斜体*  
## *斜体*  
**粗体**  
## **粗体**  
```
#### 对于斜体和粗体都可以进行嵌套使用，并且符号与文本之间无需空格


# 代码
代码使用三个顿号包括的代码块包围起来  
例如：  
```
这是代码
```  
    ```
    这是代码
    ```

# 数学公式
例如：
```math
E = mc^2
```
    ```math
    E = mc^2
    ```


# 中划线
### ~~中划线~~
```
代码为
~~中划线~~
```

# 下划线
++下划线++
```
++下划线++
```
# 水平分界线

---
```
---
```


# 链接与图片
### 链接  
在 Markdown 中，插入链接只需要使用 [显示文本](链接地址) 即可。
### 图片  
在 Markdown 中，插入图片只需要使用 ![显示文本](图片链接地址)即可。
### 注意：
> 插入图片和链接的语法很像，只是前面多了一个 ！感叹号
#### 插入链接
[My Github](https://github.com/Asurada2015)
#### 插入图片
![My Github](https://avatars1.githubusercontent.com/u/14261323?v=200&s=300)

# 分割线
分割线的语法只需要另起一行，连续输入三个星号 *** 即可分割两段文字内容。  
[My Github](https://github.com/Asurada2015)
***  
[My Blog](https://home.cnblogs.com/u/cloud-ken/)

# 表格
当你需要在Markdown中键入表格
![插入表格](http://note.youdao.com/iyoudao/wp-content/uploads/2016/09/2-6%E8%A1%A8%E6%A0%BC.png) 
参考
![image](http://note.youdao.com/iyoudao/wp-content/uploads/2016/09/2-6-7.png)

# 待办与清单
待办事项和清单在日常工作、生活中经常被使用。

在Markdown中，你只需要在待办的事项文本或者清单文本前加上- [ ]、- [x]即可。

    - [ ] 表示未完成，- [x] 表示已完成。

==注：键入字符与字符之间都要保留一个字符的空格==
### To-do List

    -[x] 已完成项目1
        -[x] 已完成事项1
        -[x] 已完成事项2
    -[ ] 待办事项1
    -[ ] 待办事项2
- [x] 已完成项目1
   - [x] 已完成事项1
   - [x] 已完成事项2
- [ ] 待办事项1
- [ ] 待办事项2

# 流程图
在Markdown中，一段流程图语法以三个上撇号开头，以三个上撇号结尾。

在三个上撇号后另起一行，书写graphXX，用以确定将要绘制的流程图及其类型（XX表示流程图类型）。

流程图分为竖向和横向两大类，竖向包括自上而下和自下而上两种顺序，横向包括从右到左和从左到右两种顺序。

其对应语法分别为：graph TB/graph BT/graph RL/graph LR。

TB - top bottom（自上而下）
BT - bottom top（自下而上）
RL - right left（从右到左）
LR - left right（从左到右）

### 简单示例
#### 自上而下
```
graph TB
A-->B
```
    ```
    graph TB
    A-->B
    ```
#### 自下而上
```
graph BT
A-->B
```
    ```
    graph BT
    A-->B
    ```
#### 自左向右
```
graph LR
A-->B
```
    ```
    graph LR
    A-->B
    ```
#### 自右向左
```
graph RL
A-->B
```
    ```
    graph RL
    A-->B
    ```

## 具体示例
### 流程图
```
graph TD
    A[Christmas方括号]-->B(Go shopping圆括号)
    B-->|选择括号|C{Let me think}
    C---|直线| D[Laptop]
    C-->|箭头| E[iPhone]
    C-->|标签三| F[Car]
```
    ```
     graph TD
        A[Christmas方括号]-->B(Go shopping圆括号)
        B-->|选择括号|C{Let me think}
        C---|直线| D[Laptop]
        C-->|箭头| E[iPhone]
        C-->|标签三| F[Car]
    ```

## ==For More==
### [更多流程图语法](https://mermaidjs.github.io/)

# 甘特图
### ==注意这里的冒号，逗号都要使用英文的符号的形式== 
```
gantt
dateFormat YYYY-MM-DD
title 产品计划表
section 初期阶段
明确需求:2016-03-01, 10d
section 中期阶段
跟进阶段:2016-03-11, 18d
section 后期阶段
走查阶段:2016-03-20, 23d
```
     ```
    gantt
    dateFormat YYYY-MM-DD
    title 产品计划表
    section 初期阶段
    明确需求:2016-03-01, 10d
    section 中期阶段
    跟进阶段:2016-03-11, 18d
    section 后期阶段
    走查阶段:2016-03-20, 23d
    ```

## ==For More==
### [更多甘特图语法](https://mermaidjs.github.io/)

### 数据流图例子
```
graph TD;
    A-->B;
    A-->C;
    B-->D;
    C-->D;
```
    ```
    graph TD;
    A-->B;
    A-->C;
    B-->D;
    C-->D;
    ```
### 流程图例子
```
sequenceDiagram
    participant Alice
    participant Bob
    Alice->John: Hello John, how are you?
    loop Healthcheck
        John->John: Fight against hypochondria
    end
    Note right of John: Rational thoughts <br/>prevail...
    John-->Alice: Great!
    John->Bob: How about you?
    Bob-->John: Jolly good!
```
    ```
    sequenceDiagram
    participant Alice
    participant Bob
    Alice->John: Hello John, how are you?
    loop Healthcheck
        John->John: Fight against hypochondria
    end
    Note right of John: Rational thoughts <br/>prevail...
    John-->Alice: Great!
    John->Bob: How about you?
    Bob-->John: Jolly good!
    ```
### 甘特图例子
```
gantt
        dateFormat  YYYY-MM-DD
        title Adding GANTT diagram functionality to mermaid
        section A section
        Completed task            :done,    des1, 2014-01-06,2014-01-08
        Active task               :active,  des2, 2014-01-09, 3d
        Future task               :         des3, after des2, 5d
        Future task2               :         des4, after des3, 5d
        section Critical tasks
        Completed task in the critical line :crit, done, 2014-01-06,24h
        Implement parser and jison          :crit, done, after des1, 2d
        Create tests for parser             :crit, active, 3d
        Future task in critical line        :crit, 5d
        Create tests for renderer           :2d
        Add to mermaid                      :1d
```
    ```
    gantt
        dateFormat  YYYY-MM-DD
        title Adding GANTT diagram functionality to mermaid
        section A section
        Completed task            :done,    des1, 2014-01-06,2014-01-08
        Active task               :active,  des2, 2014-01-09, 3d
        Future task               :         des3, after des2, 5d
        Future task2               :         des4, after des3, 5d
        section Critical tasks
        Completed task in the critical line :crit, done, 2014-01-06,24h
        Implement parser and jison          :crit, done, after des1, 2d
        Create tests for parser             :crit, active, 3d
        Future task in critical line        :crit, 5d
        Create tests for renderer           :2d
        Add to mermaid                      :1d
    ```
    
    ### 参考资料[有道云笔记Markdown教程](http://note.youdao.com/iyoudao/?p=2411)