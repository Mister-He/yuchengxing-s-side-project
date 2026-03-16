# 🔬 Paper of Computational Pathology

A curated collection of papers in computational pathology. Searchable and filterable by venue, topic, and year.

🔗 **Browse online**: [https://yucheng-xing.github.io/Paper-of-Computational-Pathology/](https://yucheng-xing.github.io/Paper-of-Computational-Pathology/)

---

## ➕ Contributing

Contributions are welcome! If you'd like to add a paper, edit `papers.json` and submit a Pull Request.

Each entry follows this format:

```json
{
  "title": "Paper title",
  "authors": "Author1, Author2, Author3",
  "venue": "CVPR",
  "year": 2024,
  "topics": ["Segmentation", "Transformer"],
  "url": "https://arxiv.org/abs/..."
}
```

You can also use the **＋** button on the website to generate a formatted JSON entry — just copy and paste it into `papers.json`.

> ⚠️ Make sure the last entry in the array does **not** have a trailing comma.

## 📁 Structure

```
├── index.html     # Web interface
├── papers.json    # Paper data (edit this to add papers)
└── README.md
```

## 📄 License

MIT
