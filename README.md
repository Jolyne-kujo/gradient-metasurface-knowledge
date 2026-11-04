# 梯度超表面高效宽带异常反射知识库

阅读网址：https://jolyne-kujo.github.io/gradient-metasurface-knowledge/

工程光学课程学习资料：100个术语、26组公式、12张论文原图、7张概念示意和5张2026年10月30日实际 FDTD 结果图。
支持手机排版、统一术语释义、阅读回退与图片放大。网页与附件公开可读，无需登录。

## 内容与来源

- 主文：Sun et al., *High-Efficiency Broadband Anomalous Reflection by Gradient Meta-Surfaces*, Nano Letters 2012，DOI: 10.1021/nl3032668。
- `sources/` 保存主文、补充材料、课程要求与课程实现/结果快照；各图附来源页码。
- `data/knowledge_base.json` 是知识内容主数据，`data/visuals.json` 记录图片来源。
- `review/assets/` 保存论文裁图、SVG概念图和历史仿真图。
- 论文、补充材料和原图的权利归原作者与出版方；本站未对这些材料授予开源许可。

仿真图来自既有5 nm网格运行，当前效率仍需网格收敛验证。候选文献的全文阅读状态在页面中单独列出。
发布副本去除了本地用户名、设备名和来源清单中的原始绝对路径，物理参数与仿真数值保持原值。

## 更新

站点由 GitHub Actions 将 `main` 分支中的 `site-bundle.zip` 展开、校验后发布到 GitHub Pages。
本地知识库维护完成后，重新运行独立发布目录中的 `prepare_publication.py`，生成发布包与文件清单。
将新的 `site-bundle.zip` 和 `publication_manifest.json` 一起上传到仓库根目录并提交，GitHub 自动更新站点，阅读网址不变。
发布包中包含全部静态页面、图片、脚本、JSON数据及相关附件；组员直接访问阅读网址即可。

## 本地阅读

下载并解压 `site-bundle.zip`，打开 `index.html`；图片、术语释义和论文附件可离线使用。
