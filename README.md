# 📚 PaperShelf

> 顶会顶刊论文收藏 · 可搜索、可筛选的静态网页

🔗 **在线访问**: [https://你的用户名.github.io/PaperShelf/](https://你的用户名.github.io/PaperShelf/)

![HTML](https://img.shields.io/badge/HTML-静态网页-E34F26?logo=html5&logoColor=white)
![Papers](https://img.shields.io/badge/论文数量-持续更新-4F7CFF)
![License](https://img.shields.io/badge/License-MIT-green)

---

## ✨ 功能

- 🔍 **全文搜索** — 按标题、作者、关键词实时搜索，匹配高亮
- 🏷️ **多维筛选** — 按会议/期刊、研究主题、年份自由组合筛选
- 📱 **响应式布局** — 桌面端和移动端均可使用
- ⚡ **纯静态** — 无需后端，GitHub Pages 直接部署

## 📖 收录范围

| 类别 | 会议 / 期刊 |
|------|------------|
| AI / 机器学习 | NeurIPS · ICML · ICLR · AAAI · IJCAI |
| 计算机视觉 | CVPR · ICCV · ECCV |
| NLP / 大语言模型 | ACL · EMNLP · NAACL |
| 期刊 | Nature 及子刊 · JMLR · TPAMI |

## 🚀 部署方式

1. Fork 或 clone 本仓库
2. 进入仓库 **Settings → Pages**
3. Source 选择 **Deploy from a branch**，Branch 选 `main`，文件夹选 `/ (root)`
4. 保存后等待 1-2 分钟，即可通过 `https://你的用户名.github.io/仓库名/` 访问

## ➕ 如何添加论文

### 方式一：通过网页表单（推荐）

点击网页右下角的 **＋** 按钮，填写论文信息后点击「生成 JSON」，复制生成的代码粘贴到 `papers.json` 数组中即可。

### 方式二：直接编辑 papers.json

打开 `papers.json`，在数组中添加一条：

```json
{
  "title": "论文标题",
  "authors": "作者1, 作者2, 作者3",
  "venue": "NeurIPS",
  "year": 2024,
  "topics": ["LLM", "Transformer"],
  "url": "https://arxiv.org/abs/..."
}
```

> ⚠️ 注意 JSON 格式：最后一条数据后面**不要**加逗号。

### 当前支持的主题标签

`Transformer` · `LLM` · `Diffusion Model` · `Detection` · `Segmentation` · `Generation` · `Representation Learning` · `Reinforcement Learning` · `Optimization` · `Multimodal` · `Graph Neural Network` · `Robotics` · `Neuroscience / Bio`

> 💡 添加新主题时，可在 `topicClassMap` 中配置对应的颜色样式。

## 📁 项目结构

```
PaperShelf/
├── index.html     # 主页面（样式 + 逻辑）
├── papers.json    # 论文数据（只需编辑这个文件）
└── README.md      # 说明文档
```

## 📄 License

MIT
