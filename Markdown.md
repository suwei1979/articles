# 1. 标题

语法：

```
## 这是二级标题
### 这是三级标题
#### 这是四级标题
##### 这是五级标题
###### 这是六级标题
```

效果：

## 这是二级标题
### 这是三级标题
#### 这是四级标题
##### 这是五级标题
###### 这是六级标题



# 2. 引用

语法：

```markdown
> 区块引用，用一个> 加空格
>> 嵌套引用，用两个>加空格
>>> 三嵌套引用，用三个>加空格
>>>> 四嵌套引用
>>>>> 五嵌套引用
```



> 区块引用，用一个> 加空格
> > 嵌套引用，用两个>加空格
> > > 三嵌套引用，用三个>加空格
> > > > 四嵌套引用
> > > >
> > > > > 五嵌套引用



#3. 字体示例

-  **加粗**，左右各两个*
- *斜体*，左右各一个*
- ***斜体加粗***，左右各三个*
- ~~删除线~~，左右各两个~



# 4. 代码

- 语法：

```markdown
​```java
// 这是代码块注释，前后各三个`
​```

​```java
/**
 * 这是代码块
 * My Application 
 */
@SpringBootApplication
public class MyApp {
  public static void main(String args[]) {
    SpringApplication.run(MyApp.class, args);
  }
}

​```

单行代码，前后各一个`
`create database hero`
```



- 效果：

```java
// 这是代码块注释，前后各三个`
```

```java
/**
 * 这是代码块
 * My Application 
 */
@SpringBootApplication
public class MyApp {
  public static void main(String args[]) {
    SpringApplication.run(MyApp.class, args);
  }
}

```



单行代码，前后各一个`

`create database hero`

# 5. 图片

语法：

```markdown
![图片alt](图片地址 ''图片title'')

图片alt就是显示在图片下面的文字，相当于对图片内容的解释。
图片title是图片的标题，当鼠标移到图片上时显示的内容。title可加可不加
```

示例：

```markdown
![blockchain](https://ss0.bdstatic.com/70cFvHSh_Q1YnxGkpoWK1HF6hhy/it/
u=702257389,1274025419&fm=27&gp=0.jpg "区块链")
```

效果：

![](https://ws3.sinaimg.cn/large/006tNc79ly1g2rougj8njj30fa08cjrz.jpg)



# 6. 超链接

语法：

``` markdown
[超链接名](超链接地址 "超链接Title")    
```

示例：

```markdown
[简书](http://jianshu.com)
[百度](http://baidu.com)
```

效果：

[简书](http://jianshu.com)
[百度](http://baidu.com)

# 7. 列表

- ## 无序列表

语法：

```markdown
- 列表内容
+ 列表内容
* 列表内容
```



效果：

- 列表内容
+ 列表内容

* 列表内容



- ## 有序列表

语法：

数字加点

```markdown
1. 列表内容
2. 列表内容
3. 列表内容
```

效果：

1. 列表内容
2. 列表内容
3. 列表内容

- ## 列表嵌套

语法：

​	上一级和下一级之间敲三个空格即可

```markdown
* 一级无序列表内容
   - 二级无序列表内容
   - 二级无序列表内容
   - 二级无序列表内容
* 一级无序列表内容
   1. 二级有序列表内容
   2. 二级有序列表内容
   3. 二级有序列表内容
1. 一级有序列表内容
   - 二级无序列表内容
   - 二级无序列表内容
2. 一级有序列表内容
   1. 二级有序列表内容
   2. 二级有序列表内容
   3. 二级有序列表内容
```



效果：

 * 一级无序列表
   * 二级无序列表内容
   * 二级无序列表内容

* 一级无序列表内容
  1. 二级有序列表内容
  2. 二级有序列表内容
  3. 二级有序列表内容

1. 一级有序列表内容
   * 二级无序列表内容
   * 二级无序列表内容
   * 二级无序列表内容
2. 一级有序列表内容
   1. 二级有序列表内容
   2. 二级有序列表内容
   3. 二级有序列表内容

# 8. 表格

语法：

```markdown
表头|表头|表头
---|:--:|---:
内容|内容|内容
内容|内容|内容

第二行分割表头和内容。
- 有一个就行，为了对齐，多加了几个
文字默认居左
-两边加：表示文字居中
-右边加：表示文字居右
注：原生的语法两边都要用 | 包起来。此处省
```



示例：

| 表头 | 表头 | 表头 |
| :--- | :--: | ---: |
| 内容 | 内容 | 内容 |
| 内容 | 内容 | 内容 |



# 9. 流程图

语法：

```markdown
​```flow
st=>start: 开始
op=>operation: My Operation
cond=>condition: Yes or No?
e=>end
st->op->cond
cond(yes)->e
cond(no)->op
&```
```



效果：

```flow
st=>start: 开始
op=>operation: My Operation
cond=>condition: Yes or No?
e=>end
st->op->cond
cond(yes)->e
cond(no)->op
```



