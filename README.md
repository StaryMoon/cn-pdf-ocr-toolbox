# PDF、OCR 与文档处理工具

> 整理 PDF 合并拆分、OCR、格式转换、电子书管理、扫描件归档和数学公式识别工具。

<p align="left">
  <a href="https://github.com/StaryMoon/cn-pdf-ocr-toolbox"><img alt="stars" src="https://img.shields.io/github/stars/StaryMoon/cn-pdf-ocr-toolbox?style=flat&label=stars"></a>
  <img alt="category" src="https://img.shields.io/badge/%E6%96%87%E6%A1%A3%20%20%2F%20%20OCR-curated-blue">
  <img alt="language" src="https://img.shields.io/badge/language-中文-brightgreen">
</p>

![preview](assets/preview.png)

<sub>图片来源：公开入口预览图，[https://github.com/Stirling-Tools/Stirling-PDF](https://github.com/Stirling-Tools/Stirling-PDF)，截取/整理日期：2026-07-02。</sub>

## 定位

本仓库是一份面向中文用户的主题索引，重点整理常用、稳定、值得优先了解的工具入口，并补充适用场景、选型建议和风险边界。目标不是追求数量，而是降低第一次检索和筛选的成本。

- **主题**：文档 / OCR
- **适合人群**：处理论文、扫描件、合同、电子书和课件的人
- **首批重点**：Stirling PDF / PDF24 / OCRmyPDF / Tesseract OCR / Paperless-ngx
- **为什么值得整理**：PDF 是学生和办公人群最高频痛点之一，好用工具贴长期有收藏价值。

## 使用方式

1. 先看 [精选资源](#精选资源)，按自己的场景挑 2-3 个入口试用。
2. 再看 [选型建议](#选型建议)，避免一上来把同类工具全装一遍。
3. 如果用于课程、论文、开源项目或生产环境，务必看 [风险提醒](#风险提醒)。

## 收录口径

按扫描、OCR、格式转换、论文管理、批处理五类收录。

优先收录：

- 官方文档、官网、活跃 GitHub 仓库；
- 免费可试用或开源项目；
- 中文用户高频搜索、收藏、复用的工具；
- 入口稳定、说明清楚、维护状态可判断的资源。

暂不收录：

- 破解软件、灰色下载、账号代认证、返利推广；
- 长期不可访问或入口频繁变化的镜像；
- 只有营销话术、没有清晰文档的产品；
- 与本主题关系很弱的泛泛工具。

## 精选资源

| 名称 | 适合场景 | 入口 |
| --- | --- | --- |
| Stirling PDF | 可自托管的 PDF 工具箱。 | [访问](https://github.com/Stirling-Tools/Stirling-PDF) |
| PDF24 | 在线/桌面 PDF 工具。 | [访问](https://www.pdf24.org/en/) |
| OCRmyPDF | 给扫描 PDF 加 OCR 文本层。 | [访问](https://ocrmypdf.readthedocs.io/) |
| Tesseract OCR | 开源 OCR 引擎。 | [访问](https://github.com/tesseract-ocr/tesseract) |
| Paperless-ngx | 文档归档和 OCR 管理。 | [访问](https://github.com/paperless-ngx/paperless-ngx) |
| Pandoc | 文档格式转换瑞士军刀。 | [访问](https://pandoc.org/) |
| Calibre | 电子书管理和转换。 | [访问](https://calibre-ebook.com/) |
| Mathpix | 公式和文档 OCR。 | [访问](https://mathpix.com/) |
| NAPS2 | 扫描、OCR 和 PDF 处理。 | [访问](https://www.naps2.com/) |
| PyMuPDF | Python PDF 解析和处理库。 | [访问](https://pymupdf.readthedocs.io/) |
| Docling | 文档解析和结构化工具。 | [访问](https://github.com/docling-project/docling) |
| Marker | PDF 转 Markdown/OCR 工作流。 | [访问](https://github.com/VikParuchuri/marker) |

## 选型建议

- 扫描件先 OCR，再归档。
- 论文 PDF 用 Zotero 管理，办公 PDF 用 Stirling/PDF24。
- 大批量转换优先 Pandoc 或脚本。

## 风险提醒

- 敏感文件不应上传到未知在线工具。
- OCR 结果必须人工核对。

## 维护说明

- 本仓库会优先更新失效链接、官方入口变更和明显过时的描述。
- 新增资源请尽量给出官网、GitHub 仓库、文档页或可验证的公开说明。
- 推荐新资源时，请说明具体场景和选择理由，避免只写泛泛评价。

## 数据文件

结构化数据见 [`data/links.json`](data/links.json)，可用于脚本生成网页、表格或个人导航页。

## Contributing

欢迎提交 PR 修正链接、补充官方文档、更新截图或改进中文说明。请保持描述短、准、可验证。

## License

MIT。第三方商标、截图、网页内容和产品名称归各自权利方所有，本仓库只做索引和学习整理。
