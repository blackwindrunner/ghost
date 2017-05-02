
:cn:
# 问题管理 :question:
* Assignees
* Labels 按特殊标记索引，可加入"新需求"这样的标签，
* Projects 新建项目，tool，runtime等吧
* Milestone 时间，进度，可关闭

***

# issue :bug:
- 可以使用Markdown
- 可以使用#issue号来引入问题，例如：#3
- 利用多任务标示，来查看issue的解决进度,例如如下（必须要创建issue里写-[]的形式，也就是issus中第一个留言）
- [x] 字体不清晰 
- [ ] 边框要波浪
- 自动关闭：包含`fix/fixes/fixed`, `close/closes/closed`或者`resolve/resolves/resolved` #问题编号的提交记录，将自动关闭该问题。

```git
$ git commit -m "Fix screwup, fixes #12"
```
- 在其他仓库中关闭issue的时候，使用这个语法username/repository#issue_number，例如
```git
$ git commit -m "Closes example_user/example_repo#76"
```
- 同时关闭多个issue
```git
$ git commit -m "This closes #34, closes #23, and closes example_user/example_repo#42"
```
- 必须是提交到默认分支的时候这个功能才可以使用

# 代码提交 :arrow_up:
- 在commit的时候可以用#符号带引入issue

# Labels
- 可以写例如bug，feature，新需求，讨论等

# Milestone里程碑
- 里程碑中可以把feature,issue等都标记在同一个里程碑中，这样里程碑中的效果如下
![an example](https://assets-cdn.github.com/images/modules/site/product-illo/img-projects-milestones.png)
 
# project 项目

- 项目中可以列出来当前任务列表
- 任务可以转换成issue，用来分配处理者
- 任务可以拖拽到不同的columns，用来表示不同的状态
- 通过card功能，可以把和当前项目关联的issue拖拽到当前任务中
 
# 魔性的zenhub `魔性的不忍直视`
https://www.zenhub.com/
 
