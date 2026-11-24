# 贡献指南

谢谢你愿意参与 KeepEssence。English issues and pull requests are welcome too.

## 先读什么

1. [spec](https://github.com/KeepEssenceApp/spec) 的 `product/`：产品是什么、术语、必须遵守的规则。
2. 你要改的那个仓库的 README。

全套文档、界面和接口只用 [术语表](https://github.com/KeepEssenceApp/spec/blob/main/product/glossary.md) 里的词，一词一义。

## 改动该去哪个仓库

| 你想改的 | 仓库 |
|---|---|
| 产品行为、规则、术语、接口契约 | [spec](https://github.com/KeepEssenceApp/spec) |
| 服务器、数据、MCP 端点、部署 | [core](https://github.com/KeepEssenceApp/core) |
| 网页客户端 | [web](https://github.com/KeepEssenceApp/web) |
| 浏览器扩展 | [extension](https://github.com/KeepEssenceApp/extension) |
| 助手接入指南、插件、agent 示例 | [agents](https://github.com/KeepEssenceApp/agents) |
| 官网 | [site](https://github.com/KeepEssenceApp/site) |

接口只在 spec 的 `contract/` 里定。要改接口，先在 spec 提 PR，合并后再改 core 和客户端；不要在代码仓库里先改接口。

## 流程

1. 小改动（错字、明显的缺陷）直接提 PR。
2. 新功能或会改变行为的改动，先开 issue 说清楚要解决什么，等维护者回复后再动手，免得白做。
3. fork 仓库，从 `main` 拉分支，改完提 PR 到 `main`。
4. 一个 PR 只做一件事。说明里写：改了什么、为什么、怎么验证的。
5. 有测试的仓库，PR 要带测试并通过检查。

## 规则

- 密钥、令牌、个人数据不进仓库，也不贴进 issue。
- 改动和产品规格冲突时以规格为准；觉得规格不对，去 spec 开 issue。
- 提交即表示你同意以该仓库的许可证（AGPL-3.0）发布你的贡献。

## 路线和优先级

做什么、先做什么由维护者定。issue 上的 `help wanted` 和 `good first issue` 标签是欢迎外部贡献的部分。
