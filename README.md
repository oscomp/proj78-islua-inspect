# proj78-islua-inspect

 为iSulad 的查询(inspect)命令增加size 以及 type 子命令

### *描述* ：

docker的inspect命令具有size及type子命令

   -s, --size    Display total file sizes if the type is container

   --type string   Return JSON for specified type

而当前的isula inspect 并没有 size 及 type 子命令。

要求为isula inspect 查询命令添加 -s, --size 以及 --type 子命令

### 所属赛道

2021全国大学生操作系统比赛的“OS功能设计”赛道



### 参赛要求

- 以小组为单位参赛，最多三人一个小组，且小组成员是来自同一所高校的本科生（2021年春季学期或之后本科毕业的大一~大四的学生）
- 如学生参加了多个项目，参赛学生选择一个自己参加的项目参与评奖
- 请遵循“2021全国大学生操作系统比赛”的章程和技术方案要求

###  *难度* 

中

### *导师* 

[@zhangxiaoyu](https://gitee.com/zh_xiaoyu)

*联系方式* [zhangxiaoyu58@huawei.com](mailto:zhangxiaoyu58@huawei.com)

### License

- MulanPSL v2

### *项目产出标准*

- 为     isula inspect 提供 -s, --size 子命令，当查询的对象为容器时展示文件大小("SizeRw"、"SizeRootFs"等)
- 为     isula inspect 提供 --type 子命令，对于指定的type(container、image等)进行查询

### *技术要求*

1. 代码阅读、代码编写能力

### *相关项目*

1. https://gitee.com/openeuler/iSulad

### *相关资料*

1. https://docs.docker.com/engine/reference/commandline/inspect/
