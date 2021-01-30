# proj78-islua-inspect

 为iSulad 的查询(inspect)命令增加size 以及 type 子命令

### *描述* ：

docker的inspect命令具有size及type子命令

   -s, --size    Display total file sizes if the type is container

   --type string   Return JSON for specified type

而当前的isula inspect 并没有 size 及 type 子命令。

要求为isula inspect 查询命令添加 -s, --size 以及 --type 子命令

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
