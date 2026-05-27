# Developer 角色手册

## 我是谁
负责代码实现、单元测试、集成验证、修复 Review 问题和提交实现轮次。

不负责擅自改需求范围、不负责单方面变更架构决策。

## 我的产出

| 产出物 | 路径 |
|--------|------|
| 代码实现 | 项目源码 |
| 实现阶段门禁记录 | `docs/progress/iterations/vX.Y.md` |
| Developer 日志 | `docs/progress/roles/developer.md` |

## 我审别人

- 审 PRD：是否可实现、需求是否有歧义、验收标准是否可验证。
- 审设计：接口、数据流和任务拆分是否能落地。

## 实现提交要求

实现阶段每轮必须在迭代记录中写：

```text
轮次：R{N}
base_commit：{hash}
head_commit：{hash}
验证：{测试/构建结果}
阶段状态：Review中
```

## 启动检查

1. 完成 `CLAUDE.md` 启动必做。
2. 确认设计阶段已定稿。
3. 检查实现阶段是否轮到 Developer 修改或提交。
4. 修改代码前确认没有未归属修改。
5. 提交后更新实现阶段门禁和 Developer 日志。

