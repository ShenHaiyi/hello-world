```java
@Override
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_main);
        int[] a = {R.id.button1, R.id.button2, R.id.button3, R.id.button4, R.id.button5};
        for (int i = 0; i < a.length; i++) {
            findViewById(a[i]).setOnClickListener(this);
        }
    }
```
标题1
=
标题2
-
# 一级标题
## 二级标题
### 三级标题
#### 四级标题
##### 五级标题
###### 六级标题
这是一段普通的文本，
直接回车不能换行，<br>
要使用\<br> 用’\`‘可以实现`高亮文本`
[文字链接](http://www.baidu.com "悬停显示")
# 列表
Markdown 支持有序列表和无序列表。
### 无序列表使用星号、加号或是减号作为列表标记：
*   Red
*   Green
*   Blue
### 等同于：
+   Red
+   Green
+   Blue
### 也等同于：
-   Red
-   Green
-   Blue
### 有序列表则使用数字接着一个英文句点：
1.  Bird
2.  McHale
3.  Parish
### 很重要的一点是，你在列表标记上使用的数字并不会影响输出的 HTML 结果，上面的列表所产生的 HTML 标记为：
<ol>
<li>Bird</li>
<li>McHale</li>
<li>Parish</li>
</ol>
### 如果你的列表标记写成：
1.  Bird
1.  McHale
1.  Parish
### 或甚至是：
3. Bird
1. McHale
8. Parish
### 多级显示：
* 1
  * 1.1
    * 1.1.1
    * 1.1.2
  * 1.2
    * 1.2.1
    * 1.2.2
* 2
  * 2.1
    * 2.1.1
    * 2.1.2
  * 2.2
    * 2.2.1
    * 2.2.2
### 树型结构：
>数据结构
>>树
>>>二叉树
>>>>平衡二叉树
>>>>>满二叉树
# 代码区块
<p>这是一个普通段落：</p>
<pre><code>这是一个代码区块。
</code></pre>
# 分隔线
* * *
***
*****
- - -
---------------------------------------
# 图片
![baidu](http://www.baidu.com/img/bdlogo.gif "百度logo")
