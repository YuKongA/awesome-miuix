# Contributing

[English](#english) | [简体中文](#简体中文)

## English

### Inclusion criteria

- Resources must relate directly to Miuix: applications, extensions, themes, templates, or learning material.
- Applications must use Miuix to build their interfaces. A similar visual style alone is not accepted.
- Applications must remain open source under a license that permits reuse. Resources must be accessible without login or payment.
- Links must work, and descriptions must reflect the project's current state. Disclose archived status and important limitations.
- Code and documentation must have no obvious AI-generation artifacts. AI-assisted work requires human review, testing, and maintenance.
- Community source repositories must have **at least 50 GitHub Stars** at review time. This threshold does not replace quality review.
- Applications must handle display cutouts and safe areas properly. There must be no obvious overlap, clipping, duplicate padding, or excessive blank space.

### Categories

Top-level categories follow **resource type**:

- **Official Resources**: the library and official documentation.
- **Examples and Demos**: resources demonstrating Miuix usage.
- **Applications**: projects with interfaces built using Miuix, ordered alphabetically:
  - **AI**: AI assistants, agents, and LLM clients.
  - **Media**: music, video, and other media players or managers.
  - **Productivity**: schedule, note-taking, and daily productivity tools.
  - **Root**: solutions and tools for obtaining or managing root access.
  - **System Tools**: update, extraction, and installation utilities.
  - **VPN / Proxy**: VPN and network proxy clients.
  - **Xposed**: Xposed applications or modules, including system customization and lyrics modules.

Use one category per entry, based on its primary purpose. Requiring root access or offering optional root support alone does not place a tool in Root. Xposed applications and modules belong in Xposed even when they require root access. Do not classify complete applications by individual UI components.

Propose a new category when needed. Add sections for extensions, themes, templates, or tutorials only when suitable entries are available. Do not create empty sections.

### Pull request checklist

- Use `- [Name](https://github.com/owner/repo) ![GitHub Stars](https://img.shields.io/github/stars/owner/repo?style=flat) - Short, factual description.` for GitHub repositories (omit the stars badge for non-GitHub links). End descriptions with a period.
- Use official project names and canonical links. For code projects, prefer source repositories.
- Append new projects to the bottom of their category by default, preserving the order of existing entries.
- Review each [inclusion criterion above](#inclusion-criteria) before submitting, and confirm that the project and supporting materials meet the requirements.
- Applications must include evidence of Miuix-based interfaces, such as a dependency declaration, UI source file, or screenshots.
- Keep both READMEs consistent in names, links, and categories. Update both tables of contents when changing sections.
- Contributions use the repository's [CC0 license](LICENSE). Linked projects retain their own licenses.

## 简体中文

### 收录要求

- 资源须与 Miuix 直接相关，包括应用、扩展、主题、模板及学习资料。
- 应用须使用 Miuix 构建界面，仅有相似的视觉风格不予以收录。
- 应用须保持开源，并采用允许复用的许可证。资源要求无须登录或付费即可访问。
- 链接须有效，描述须符合项目现状。已归档状态及重要限制须明确说明。
- 代码和文档不得有明显的 AI 生成痕迹。AI 辅助成果须经人工审阅、测试和维护。
- 社区源码仓库在审核时须有 **至少 50 个 GitHub Stars**。但该门槛不会替代质量审核。
- 应用须正确处理屏幕缺口及安全区。不得有明显遮挡、裁切、重复或异常留白。

### 分类规则

一级分类按**资源类型**划分：

- **官方资源**：库本身及官方文档。
- **示例与演示**：展示 Miuix 用法的资源。
- **应用**：使用 Miuix 构建界面的项目，子分类按英文名称字母顺序排列：
  - **AI**：AI 助手、Agent 及大模型客户端。
  - **影音媒体**：音乐、视频等媒体播放与管理应用。
  - **效率工具**：课表、笔记及日常效率类工具。
  - **Root**：用于获取或管理 Root 权限的方案及工具。
  - **系统工具**：更新、提取、安装类工具。
  - **VPN / 代理**：VPN 及网络代理客户端。
  - **Xposed**：Xposed 应用或模块，包括系统定制和歌词模块。

每个条目按核心用途仅归入一个分类。仅依赖 Root 权限或支持可选 Root 功能的工具，不因此归入 Root。Xposed 应用或模块即使依赖 Root 权限，也归入 Xposed。完整应用不按单个 UI 组件分类。

现有分类不适用时，可提出新分类。扩展、主题、模板或教程等分类须有实际条目，不预建空章节。

### Pull Request 检查清单

- GitHub 仓库使用 `- [名称](https://github.com/owner/repo) ![GitHub Stars](https://img.shields.io/github/stars/owner/repo?style=flat) - 简短、客观的描述。` 格式（非 GitHub 链接可省略 Stars 徽章），描述以句号结尾。
- 使用项目正式名称及规范链接，代码项目优先链接源码仓库。
- 新增项目默认追加到所属类别的底部，保留现有条目的排列顺序。
- 提交前逐项核对[上述收录要求](#收录要求)，确认项目及所附材料均符合要求。
- 应用须附使用 Miuix 构建界面的证据，如依赖声明、界面源码或截图。
- 两个 README 的名称、链接及分类须一致。修改章节时请同步更新目录。
- 贡献遵循本仓库的 [CC0 许可证](LICENSE)。被链接的项目保留各自的许可证。
