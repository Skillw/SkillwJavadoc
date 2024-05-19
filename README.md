
# SkillwJavadoc 项目文档

## 简介

SkillwJavadoc 是 Skillw 组织下的一个中心化文档仓库，用于存储和展示旗下各项目的 Javadoc 文档。  
Javadoc 是一种从 Java 源代码中提取注释生成 HTML 文档的工具，对于理解和使用各种 Java 项目至关重要。

## 主要功能

- **集中管理**：所有项目的 Javadoc 文档集中在一个仓库，方便访问和管理。
- **自动更新**：通过 Git 子模块机制自动更新各个项目的最新文档。
- **便于协作**：统一的文档结构使得跨项目的协作更为便捷。

## 安装指南

### 克隆仓库

要获取 SkillwJavadoc 项目的副本，您可以使用下面的命令克隆整个仓库，包括其所有子模块：

```bash
git clone --recursive https://github.com/Skillw/SkillwJavadoc.git
```

如果已经克隆了主仓库但未初始化子模块，运行：

```bash
git submodule update --init --recursive
```

### 更新子模块

要更新所有子模块至最新提交，执行：

```bash
git submodule update --remote --recursive
```

## 使用说明

克隆并初始化子模块后，您可以直接访问各个目录下的 HTML 文件，使用浏览器打开即可查看文档。

## 贡献指南

我们欢迎所有形式的贡献，包括但不限于文档更新、功能改进和错误修复。请提交 Pull Requests 或为项目开新的 Issue。

## 许可证

本项目采用 MIT 许可证。详情请见 [LICENSE](LICENSE) 文件。

## 联系方式

如有任何问题或建议，请通过以下方式联系我们：

- 邮件: [glom@skillw.com](mailto:glom@skillw.com)
- GitHub Issue: [SkillwJavadoc issues](https://github.com/Skillw/SkillwJavadoc/issues)
- QQ 群:  [Skillw 社区](https://qm.qq.com/cgi-bin/qm/qr?k=lI34n84yXduDyfGIt0xNuVu6VJHulzoN&jump_from=webapi&authKey=yEH2xolLDeivi1W67qcY4cFmPA8QAGmvnW5Uc64WMr8V7RlvD5X+MDZXRcNuxxnj)

感谢您对 Skillw 的关注和支持！
