# EntranceExamForBackEnd2015
> 当你看到这个长的一逼的文档的时候，不要伤心，不要失望。考虑到各位的考核时间很短，所以我帮各位规避了很多难题，所以篇幅比较长。希望大家能够认真读题，完成整个考核，保持一个平和的心态。通过这次面试我想看到大家的能力，不一定要全部做完，但希望你能体现出你的能力与价值。
 
# 2015后端学员转正考核

## 考核方式
转正考核分两部分: 

1. `撸代码` 
2. `面试`

## 笔试考核安排
- 时间: 2015年5月31日 8:00am - 10:00pm 共14个小时
- 地点: 网校A区（若有其他特殊安排请先给老李说明）

### 关于时间安排的建议
- 看到前端的东西了以后, 首先规划一下网站由哪些`模块`构成
- 可以考虑画画草图(Processon.com)
- 然后预估一下每个模块需要的时间, 复杂程度
- 按照模块进行功能实现


## 关于午饭和晚饭问题
- 根据自己的进度自行安排
- 若是点的外卖, 记得`在网校门外吃`, 不要把味道带进网校里面来. 给大家提供一个比较舒适的环境

## 笔试具体内容

### 前提: 关于框架

> 使用框架对于考核来说是一件非常幸福的事情，因为很多重复性的代码你都不需要写，数据库也是封装好了的可以直接用。因为咱们只有14个小时的时间。

- 可以开始提前准备框架方面的事情了。
- 尽量使用自己写的MVC框架（模板引擎可以使用smarty）
- 如果自己写的MVC框架还有不少bug，觉得不太适合做考核的话， 请马上开始学习ThinkPHP/Laravel框架(前者比后者要简单一些, 但后者比较优雅)

### 基本要求

#### Step1: 扒扒戴老板~

> 咱们后端有时候想做点东西，但出于不太优秀的前端能力以及有点懒，便可以有这样一个思路：把自己觉得还不错的网站扒下来为自己所用。（其实也就是代码复制下来改改各个资源的路径什么的233）要求如下：

1. 我们的首要目标就是把戴老板的博客模板扒下来为Step2用： http://blog.toruneko.net
2. 需要扒下：
	1. 文章列表页（ 即 http://blog.toruneko.net ）
	2. 文章详情页（ 如 http://blog.toruneko.net/35 ）
3. 去其糟粕，画龙点睛：
	1. 读一读Step2中要实现的功能，把多余的功能去掉，把不够的功能自己想个地方加上

#### Step2: 博客!

- 页面构成:
	- 公共部分: 头部(LOGO + 登录 + 登录后的发表文章) 尾部（copyright）
	- 登录页: 这里有个框框的样式可以用： http://blog.toruneko.net/admin/account/login
	- 首页: 博文列表 + 博文分类的侧边栏（日期归档和友情链接就可以不要了）
	- 博文详情页: 文章详情(标题/内容/分类/发布时间) + 评论
- 功能:
	- 分页(只要出现有列表的地方就需要有分页)
	- 面包屑(进到某个文章后, 可以看到这篇文章属于哪个分类，一条链)
	- 文章分类
	- 博文的添加，删除，编辑（这些在模板上面没有，可以往登录后的页面加几个按钮以满足功能）
	- 评论
- 考察的主要方面:
 	- 数据库的设计
	- 代码的规整性
	- 文件的目录结构规范条理性
	- 面向对象的思想（MVC等）

- 注意：
	- 请不要再网校内大声喧哗，大声讨论问题，或者做任何影响他人情绪的行为   
	- 以上要求如果不能全部完成，请将你能完成的部分做到最好   
	
### 进阶要求

- 可以使用Ajax，从js到php都要写
- 良好的数据库设计(三范式)
- 注意Web安全(XSS, SQL注入等)


### 评判标准
1. 30分:扒网站以及添加功能模块的合理性以及美观程度
2. 70分:后台逻辑，代码规范，功能完善程度，面向对象思想。
3. 加分项50分:
	1. 使用了自己写的MVC框架
	2. 代码注释习惯比较好
	3. 进阶模块的进度

## 面试时间待定

## 面试的预计内容
- 基础知识
- 学员对自己的总结和规划
- 学员对网校的看法
- 学员对导师的看法
- 对网校的建议(随意说)
