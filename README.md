# workbuddy

WorkBuddy 制作的 skill 集合。

## 技能清单

| 技能 | 版本 | 简介 | 目录 |
|---|---|---|---|
| **mao-methodology**（毛泽东思想方法论工作法） | v1.5 | 以 1981 年《关于建国以来党的若干历史问题的决议》确认的「活的灵魂」（实事求是、群众路线、独立自主）为总纲，把《实践论》《矛盾论》《反对本本主义》《论持久战》《党委会的工作方法》等经典著作中的思想方法、工作方法、领导方法、战略方法，蒸馏为 **50 件可操作思维工具**与五步工作流「查·析·聚·试·结」。内置先诊断后开方的交互协议、五席位专家团会诊模式、多模态输入协议，覆盖六类问题模式与五类思想问题，并按七类人群做表达转译。 | [`skills/mao-methodology/`](skills/mao-methodology/) |

## 安装方式

将 `skills/` 下对应技能整个目录复制到本地技能目录，重启会话即可：

```bash
# WorkBuddy / CodeBuddy（用户级）
cp -r skills/mao-methodology ~/.workbuddy/skills/

# 项目级
cp -r skills/mao-methodology <项目目录>/.workbuddy/skills/
```

其他 AI 助手：把 `SKILL.md` 全文粘贴进系统提示词即可生效（`references/` 按需附上）。

## 目录约定

```
skills/<skill-name>/
├── SKILL.md        # 主文件，技能入口（必需）
├── README.md       # 安装与触发说明
└── references/     # 被引用的参考资料（按需加载）
```
