# Super Agent Harness

Super Agent Harness 的架构提案与 prototype 代码。PPT 参考材料仅保留在本地，不纳入仓库。

## 文档与代码

- [Harness 架构评审](./harness-architecture-review.md)：当前代码架构、Proposal 和待讨论的设计边界。
- [DSH Superagent Prototype](./dsh-superagent-prototype/README.md)：参考实现及其说明。

当前处于架构评审阶段，尚未开始实现 Proposal。

## Prototype 来源

- 上游仓库：[deepseek-ai/dsh-superagent-prototype](https://github.com/deepseek-ai/dsh-superagent-prototype)
- 导入基线：`8c32a9dc5d72c033816c6a8110b37f40cf94fba4`
- 导入方式：将该版本的源码作为普通目录纳入本仓库统一跟踪，后续修改在本仓库提交。
- 上游的 MIT [LICENSE](./dsh-superagent-prototype/LICENSE) 和原始项目说明保持在源码目录中。

首次导入没有修改 prototype 的文件内容。原 clone 的 Git 元数据保留在本机 `.git/upstream/dsh-superagent-prototype.git`，该本地备份不随 push 上传；上游提交历史可从上游仓库获取。
