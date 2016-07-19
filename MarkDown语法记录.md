这是一个关于MarkDown的语法记录
包括标题、菜单、插入图片、链接、文字高亮、还有_斜体_、**加粗**、 > 引用、还有CHECK BOX - []




首先是引用
引用的语法是：
（空格加上一个>）（结尾要加一个回车就断掉这个引用了）

Example：
> 作者是入门的萌新   
还有很多地方不是很会。




# 在往下讲之前先讲两点

## 一个是星号、下划线是可以互相替换的

## 第二个是关于分割线。由`=`、`-`、`_`、`*`号以3个以上的形式聚在一起结尾加上回车即可，这一行除了分隔符不能有其他的东西。
`=`号的：`对应的是一级标题`
=============================================================
`-`号的：`对应的是二级标题`
-------------------------------------------------------------
`*`号的：`普通的分割线`
*************************************************************
`_`的：`普通的分割线`
_____________________________________________________________


然后是标题

第 i 标题的语法是（i个井号+一个空格+标题名称）

Example:

# 一级标题
## 二级标题
### 三级标题

### 菜单
下面是菜单的语法是：
有序的菜单的语法是（数字+.+空格）

Example:

1. First
2. Second
3. Third

而没有顺序标号的菜单的语法是（i个空格+横杠+空格）

Example:
 - 1一级菜单
  - 1.1二级菜单
  _ 1.2
  
 - 2另外一个一级菜单
  * 2.1
  + 2.2
  
### 插入

首先是插入图片的语法是：
`![Image](ImageURL)`
`![Image](ImageURL"Opotional Title")`

Example:


![Image](https://raw.githubusercontent.com/LoyaltyWu/hello-world-Repository-name-/NewBranch_1/%E6%97%A0%E6%A0%87%E9%A2%98.jpg)


![Image](https://raw.githubusercontent.com/LoyaltyWu/hello-world-Repository-name-/NewBranch_1/%E6%97%A0%E6%A0%87%E9%A2%98.jpg "Android Studio")


然后是插入链接的语法：
`[Name](URL)`

Example:
[To Home.Give Me A Star](https://github.com/LoyaltyWu)

### 高亮
用的是Esc下面的那个键那个小点点
`HighLight`

```
//HAHA
//Finaylly find the proper way to highlight...........
//开头位置用三个那个小点点！结尾也是。
//那个斜体和粗体呢？我试试
//C++
#include <iostream>

using namespace std;

int main ()
{
	cout << "Hello World!" << endl;
	return 0;
}
```

### 斜体

斜体的语法是：  
在要斜体的语句的最开始前面加上下划线  
再在最后一句的末尾（不要换行）加上下划线  
（换行的方法是在要换行的地方先加上两个或以上的空格，然后再换行就可以了）

Example:

_Lovely   
Octocat_

_Is it kind of boring?_
_I have no idea._

### 加粗

加粗的语法是：  
在要加粗的语句最开始前面加上两个星号  
再在最后一句的末尾（不要换行）加上两个星号  
（换行的方法是在要换行的地方先加上两个或以上的空格，然后再换行就可以了）
（和斜体很像）

Example:

**Maybe it is not boring but necessary I think.   
It is said that `don't get confused and do something.`**
__Lovely cat__
###CHECK BOX

CHECK BOX 打勾勾的语法是：
横杠+空格+【+空格+】

Example:
- [ ] Got a cat. 
- [ ] Got a fat cat.

> 好像是comment的时候那个勾才能打上去的样子？？


> 表格是我觉得 Markdown 比较累人的地方，例子如下：   
> | Tables        | Are           | Cool  |   
> | ------------- |:-------------:| -----:|   
> | col 3 is      | right-aligned | $1600 |   
> | col 2 is      | centered      |   $12 |  
> | zebra stripes | are neat      |    $1 |  
> 这种语法生成的表格如下：  

Example:


| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |



> 表格这部分是从Te_Lee那边引用过来的，附上简书链接

[简书Te_Lee](http://www.jianshu.com/p/1e402922ee32/)
> 以下介绍换行的方法：   
代码的话就是连用3个\`就可以的呀   
如果像是引用、加粗、斜体什么的怎么换行呢？？    
就是在每个要换行的句子末尾加上两个或以上的空格在换行即可  
高亮的好像不行

`Lovely  
Octocat`

