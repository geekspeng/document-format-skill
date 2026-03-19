# document-format-skill

Claude Code Skill for formatting Chinese documents according to the [Fengchao Document Style Guide](https://www.fengchao.pro/blog/document-style-guide).

## 安装

在 Claude Code 中运行：

```bash
/plugin install kiro-skill:document-format
```

或下载 `.skill` 文件并手动安装。

## 功能

- 中文 Markdown 文档格式化
- 标点符号规范化（全角/半角）
- 中英文混排空格处理
- 标题层级检查
- 段落长度优化
- 数字格式规范
- 台规引号转换

## 核心规则

| 类别 | 规则数 |
|------|--------|
| 标点符号 | 8 项 |
| 字间距 | 3 项 |
| 标题层级 | 3 项 |
| 段落规范 | 5 项 |
| 句子规范 | 7 项 |
| 数字规范 | 6 项 |
| 列表规范 | 3 项 |
| 代码规范 | 3 项 |
| 英文处理 | 5 项 |
| 文件名规范 | 5 项 |

## 使用示例

**输入：**
```markdown
Git是一个分布式版本控制系统。
```

**输出：**
```markdown
Git 是一个分布式版本控制系统。
```

## 许可

MIT
