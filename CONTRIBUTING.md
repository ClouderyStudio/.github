# 🤝 贡献指南

欢迎参与 Cloudery Studio 的项目贡献！请仔细阅读以下指南。

## 🛠 开发流程

1. Fork 本仓库
2. 创建特性分支 (`git checkout -b feat/your-feature`)
3. 提交更改 (`git commit -m "feat: add your feature"`)
4. 推送到分支 (`git push origin feat/your-feature`)
5. 创建 Pull Request

## ✍️ Commit 信息规范

我们采用 [Angular Commit 信息规范](https://github.com/angular/angular/blob/main/CONTRIBUTING.md#-commit-message-format)，格式如下：

```
<type>(<scope>): <subject>
<BLANK LINE>
<body>
<BLANK LINE>
<footer>
```

其中 ``<type>`` 和 ``<subject>`` 是必填项，``<body>`` 和 ``<footer>`` 是可填项。
### 类型 (type)

| 类型       | 说明                          |
|------------|-------------------------------|
| feat       | 新增功能                      |
| fix        | 修复bug                       |
| docs       | 文档变更                      |
| style      | 代码格式/样式变更             |
| refactor   | 代码重构                      |
| perf       | 性能优化                      |
| test       | 测试相关                      |
| chore      | 构建/依赖项/工具等变更        |
| revert     | 回退提交                      |

### 示例

```
feat(auth): add JWT authentication

- add login endpoint
- implement token validation

Closes #123
```

## ⚠️ 注意事项

1. **代码风格**：请遵循项目现有的代码风格
2. **测试**：新增功能请包含相应测试用例
3. **文档**：如果变更影响使用方式，请更新相关文档
4. **单一职责**：每个PR应只解决一个问题
5. **描述清晰**：在PR中详细说明变更内容和动机

## 🎯 首次贡献

如果你是首次贡献者，可以查看标有 `good first issue` 的议题。

感谢你的贡献！🎉
