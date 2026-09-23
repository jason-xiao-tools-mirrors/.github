# 🚀 Jason Xiao Tools & Mirrors Hub

欢迎来到开源工具与镜像聚合中心！本项目组用于集中维护、镜像与管理常用开源工具及定制化分叉仓库。

## 📌 组织定位与特性
- **🔗 原生 Fork 链路**：与上游主仓库保持追溯关系，方便向上游提交 PR 及持续跟踪 Issue。
- **🔄 自动化同步机制**：配置定时工作流定期拉取上游最新发布与提交，杜绝代码滞后。
- **🛠️ 本地与团队统一索引**：集中沉淀经过团队验证的最佳配置与补丁改动。

---

## 📂 常用开源工具与镜像索引

| 仓库名称 | 类别 / 用途 | 上游原始仓库 | 同步状态 | 说明 |
| :--- | :--- | :--- | :---: | :--- |
| [**open-saas**](https://github.com/jason-xiao-tools-mirrors/open-saas) | SaaS 模板 / 全栈脚手架 | [`wasp-lang/open-saas`](https://github.com/wasp-lang/open-saas) | 🟢 实时同步 | 现代化免费全栈 SaaS 启动套件（React, Node.js, Prisma, 认证/支付/邮件集成） |
| [**Mole**](https://github.com/jason-xiao-tools-mirrors/Mole) | macOS 系统优化 / 效率工具 | [`tw93/Mole`](https://github.com/tw93/Mole) | 🟢 实时同步 | 🐹 Mac 深度清理、应用卸载、状态监控与系统优化工具（原生 App + CLI） |

---

## 💡 如何将新的开源软件收纳到此组织？

### 方法 1：网页端一键 Fork（推荐）
1. 打开任意开源仓库（如 `https://github.com/foo/bar`）。
2. 点击右上角 **Fork** 按钮。
3. 在 **Owner** 下拉菜单中选择 `jason-xiao-tools-mirrors` 即可。

### 方法 2：使用命令行（GitHub CLI）一键收录
在终端中执行：
```bash
gh repo fork <owner/repo> --org jason-xiao-tools-mirrors --clone=false
```
例如：
```bash
gh repo fork wasp-lang/open-saas --org jason-xiao-tools-mirrors --clone=false
```
