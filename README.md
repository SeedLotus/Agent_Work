# Agent_Work

本目录用于收纳所有未来开发的多个项目。各项目应当保持独立目录，根目录统一管理文档与规范。

## 目录规范

- `projects/`：存放各个独立项目，每个项目一个子目录
- `docs/`：根目录统一管理文档、方案、标准、模板等
- `tools/`：存放通用脚本、配置、自动化工具
- `templates/`：存放项目启动模板、代码片段、README 模板
- `assets/`：存放根级公共资源，如图标、图片等

## 开发规范

1. 每个项目目录下应包含独立 `README.md`，建议加 `LICENSE`、`CHANGELOG.md`
2. 根目录统一维护 `README.md`、`CONTRIBUTING.md`、`CODE_OF_CONDUCT.md`
3. 根目录可维护 `projects.yaml` 或 `projects.json`，记录子项目清单与简介
4. 安装配置、CI/CD 脚本、公共工具应归类到 `tools/`

## 目录示例

- `projects/`
  - `project-a/`
  - `project-b/`
- `docs/`
  - `architecture.md`
  - `standards.md`
- `tools/`
  - `dev-setup/`
- `templates/`
  - `project-readme.md`
- `assets/`
  - `logo.svg`

---

## 使用说明

当前目录结构适合作为多项目托管仓库的起点；
后续在此目录下新增项目时，请先在 `projects/` 下创建项目文件夹，并在 `docs/` 中补充项目相关说明。
