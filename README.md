# 2026netlab

## 文件管理
- `docs` 里储存页面 `markdown` 文件
- `mkdocs.yml` 里储存页面设置
- 代码管理在 `main` 分支下
- 页面展示在 `gh-pages` 分支下

## 环境配置
```bash
pip install mkdocs-material
pip install mkdocs-glightbox
```

## 页面编写
- 在 `docs` 中增加新的（或修改已有的）markdown 文件
- `mkdocs.yml` `nav` 条目下添加页面索引
- 运行 `mkdocs serve` 可以本地预览网页
- 运行 `mkdocs gh-deploy --force` 生成页面并自动 push 进 gh-pages
