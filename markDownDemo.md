# 标题
# 一级标题
## 二级标题
### 三级标题
#### 四级标题
##### 五级标题

# 字体
**这是加粗的文字**
*这是倾斜的文字*
***这是即粗又斜的字体***
~~这是加删除线的文字~~

# 引用
>引用1
>>引用1.1
>>>引用1.1.1
>
>引用2
>>2. 混用列表

# 分割线
---
----
***
*****

# 列表
## 无序列表
- 列表内容
+ 列表内容
* 列表内容

## 有序列表
1. 列表内容
2. 列表内容
3. 列表内容

## 嵌套列表(四个空格或一个tab)
1. 列表内容
	- 子内容
	- 子内容
2. 列表内容
	* 子内容
    * 子内容

# 表格
姓名|技能|排行
:--|:--:|--:
刘备|哭|大哥
关羽|打|二哥
张飞|骂|三弟

# 图片
![gril](F:\pictures\飞鸟.jpg "飞鸟")

# 超链接<!-- ([超链接名](超链接地址 "超链接title")) -->
[百度](http://www.baidu.com)
[知乎](http://www.zhihu.com "知乎")

# 代码
## 单行代码
`code`
## 代码块
(```)
	public class MathUtil{
		public static int add(int a, int b) {
			return a + b;
		}
	}
(```)
<pre><code>
public class MathUtil{
	public static int add(int a, int b) {
		return a + b;
	}
}
</code></pre>

# 流程图
	```flow
	st=>start: 开始
	op=>operation: My Operation
	cond=>condition: Yes or No?
	e=>end
	st->op->cond
	cond(yes)->e
	cond(no)->op
	&```

# 注脚
这是脚注[^1]这是脚注二[^2]
[^1]: 这是脚注说明，会在文章的末尾显示.
[^2]: 我是注脚二

# 样式
<p style="color: red;">红色字体</p>

# 自动链接
## 邮件
Email:<lwy@139.com>

# 说明
    1. markdown最终会转换为可运行的html文件
	2. markdown支持html标签
	3. 转义字符为"\"
	4. html中的一些特殊字符会自动的转换(@cope转换为cope符号)
