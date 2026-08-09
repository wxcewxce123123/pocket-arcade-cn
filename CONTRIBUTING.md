# 参与贡献

感谢你愿意让口袋电玩城变得更好。Bug 报告、玩法建议、文档改进和无障碍反馈都很有价值。

## 提交 Issue

提交前请先搜索现有 Issue，避免重复。Bug 报告请尽量包含：

- 设备与浏览器版本
- 可以稳定复现的步骤
- 预期结果与实际结果
- 不包含私人信息的截图或录屏（如适用）

新玩法建议请说明核心规则、手机端的操作方式，以及一局大约需要多久。

## 本地预览

当前仓库保存 GitHub Pages 的静态发布版本。它使用 `/pocket-arcade-cn/` 作为基础路径：

```bash
git clone https://github.com/wxcewxce123123/pocket-arcade-cn.git
cd pocket-arcade-cn
python3 -m http.server 8000 --directory ..
```

访问 <http://localhost:8000/pocket-arcade-cn/>。

## Pull Request

1. 对较大的功能改动，先开 Issue 对齐范围。
2. 从 `main` 创建一个目标单一的分支。
3. 不要修改与本次改动无关的版本化资源。
4. 在手机和桌面浏览器上检查首页、至少一款游戏和返回流程。
5. 清楚说明改了什么、为什么改，以及如何验证。

当前仓库中的 JavaScript/CSS 是预构建产物。涉及游戏逻辑的大改动请先开 Issue；可读源代码工程的公开整理已列入路线图。

提交贡献即表示你同意按本项目的 MIT License 发布你的贡献。参与社区时请遵守 [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md)。
