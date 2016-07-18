这是一个关于MarkDown的语法记录
包括标题、菜单、插入图片、链接、文字高亮、还有_斜体_、**加粗**、 > 引用、还有CHECK BOX - []

首先是引用
引用的语法是：
（空格加上一个>）（结尾要加一个回车就断掉这个引用了）

Example：
> 作者是入门的萌新
还有很多地方不是很会。

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
  - 1.2
  
 - 2另外一个一级菜单
  - 2.1
  - 2.2
  
### 插入

首先是插入图片的语法是：
`![Image](ImageURL)`

Example:
![Image](https://raw.githubusercontent.com/LoyaltyWu/hello-world-Repository-name-/NewBranch_1/%E6%97%A0%E6%A0%87%E9%A2%98.jpg)


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
（换行的方法貌似和高亮换行的方法是一样的）

Example:

__
果然呀，斜体的语法也是这样的吧
哈哈？？
__

_Is it kind of boring?_
_I have no idea._

### 加粗

加粗的语法是：
在要加粗的语句最开始前面加上两个*号
再在最后一句的末尾（不要换行）加上两个*号
（换行的方法貌似和高亮换行的方法是一样的）
（和斜体很像）

Example:

**
如果是对的话，加粗的语法有点麻烦呢。。2乘3。。6个*号
**

**Maybe it is not boring but neccary I think.
It is said that `don't get confused and do something.`**

###CHECK BOX

CHECK BOX 打勾勾的语法是：
横杠+空格+【+空格+】

Example:
- [ ] Got a cat. 
- [ ] Got a fat cat.

> 好像是comment的时候那个勾才能打上去的样子？？



> 怎么说呢？怎么换行这么奇怪的呢？我试了几种都不行，最后用的就是像代码那段高亮的一样的方法来换的行，好奇怪，总觉得好像格多了一行的样子但是，不那样做又会整条连起来。
