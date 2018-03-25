# Study-Notes

大标题
====

中标题
-------

# 一级标题
## 二级标题
### 三级标题
#### 四级标题
##### 五级标题
###### 六级标题

* 列表一
* 列表二
* 列表三

* 列表一
    * 列表二
      * 列表三

>缩进一
>>缩进二
>>>缩进三
>>>>缩进四
>>>>>缩进五

[百度](http://baidu.com)

![baidu](http://www.baidu.com/img/bdlogo.gif "百度logo")  

```java
public static void main(String[] args){}
```

```javascript
document.getElementById("ts").innerHTML="Hello"
```
换行<br>
      单行文本

      多行文本
      多行文本
      多行文本

``部分文字高亮``

[文字超链接](https://www.cnblogs.com/shiy/p/6526868.html"鼠标悬停显示")


新建项目到github
```
touch README.md //新建说明文件
git init //在当前项目目录中生成本地git管理,并建立一个隐藏.git目录
git add . //添加当前目录中的所有文件到索引
git commit -m "first commit" //提交到本地源码库，并附加提交注释
git remote add origin https://github.com/chape/test.git //添加到远程项目，别名为origin
git push -u origin master //把本地源码库push到github 别名为origin的远程项目中，确认提交
```

提交本地代码到github
```
git add .
git commit -m "update test" //检测文件改动并附加提交注释
git push -u origin master //提交修改到项目主线
```

github常用命令
```
git push origin master //把本地源码库push到Github上
git pull origin master //从Github上pull到本地源码库
git config --list //查看配置信息
git status //查看项目状态信息
git branch //查看项目分支
git checkout -b host//添加一个名为host的分支
git checkout master //切换到主干
git merge host //合并分支host到主干
git branch -d host //删除分支host
```
