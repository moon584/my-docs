# my-docs

使用 **MkDocs Material** 编写的技术文档示例，通过 **GitHub Actions** 自动构建并部署到 **GitHub Pages**。

## 本地预览

```bash
pip install mkdocs-material
mkdocs serve
```

## 部署

推送到 `main` 分支且 `docs/` 或 `mkdocs.yml` 有变化时，GitHub Actions 会自动执行
`mkdocs build` 并把 `site/` 部署到 `gh-pages` 分支。

访问地址：https://moon584.github.io/my-docs/

## 目录结构

```text
my-docs/
├── docs/
│   ├── index.md
│   ├── about.md
│   ├── guide.md
│   └── api.md
├── .github/
│   └── workflows/
│       └── deploy.yml
├── mkdocs.yml
└── README.md
```
