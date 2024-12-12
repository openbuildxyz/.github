[English](./en.md) | 简体中文

# 协作指南

## 领取任务

我们使用 GitHub Projects 进行任务管理，因而要领取任务，就得先找到想参与的项目所对应的 Project。

由于不同项目在代码管理策略上有所差异，会造成项目与仓库之间是一对一或一对多的这两种关系情况；一对一关系时 Project 是在仓库里，一对多关系时 Project 则在 GitHub 组织里。

为方便查找，下表整理了项目与仓库之间的包含关系，且点击项目名即可访问相应的 Project：

| 项目 | 包含仓库（已开放） |
| --- | --- |
| [OpenBuild 官网](https://github.com/orgs/openbuildxyz/projects/9) | [openbuild-frontend](https://github.com/openbuildxyz/openbuild-frontend) |

每个 Project 基本都会包含 Board 和 Roadmap 这两个视图，一般只需关注 Board 视图，根据任务的状态分成了 5 栏：

1. No Status——尚未被分配；
2. Todo——已被分配执行人，但还未开始做；
3. In Progress——正在处理中，在进入此状态之前，任务需被设置起始时间与结束时间；
4. Dev Done——开发完成并发起 PR 等待审核；
5. Closed——PR 审核通过并将代码合入代码库。

仅状态为「No Status」的任务可以领取，从中选择感兴趣的，然后：

1. 将「Assignees」字段设置为自己；
2. 更改「Status」字段为「Todo」；
3. 设置表示任务起止时间的「Start from」与「Finish at」字段。

按步骤完成以上操作，就代表领取完某个任务了。

**请记得自己设置的起止时间，这相当于一个承诺，要尽量在这期间完成任务，遵守并履行自己的承诺。**

## 反馈问题

TODO

## 提出建议

TODO
