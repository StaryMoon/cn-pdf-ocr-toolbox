# 中文 PDF 与 OCR 工具箱

![preview](assets/preview.png)

PDF 工具是那种平时想不起来，真要用时到处找的东西。这个仓库按论文、扫描件、办公文件和批量转换几个场景来收。

敏感文件不要随便上传在线工具。扫描件先 OCR 再归档，后面会少很多痛苦。

## 先看这几个

Stirling PDF / PDF24 / OCRmyPDF / Tesseract OCR

日常 PDF 处理看 Stirling PDF / PDF24；批量转换看 Pandoc；文献管理交给 Zotero。

## 入口

| 名称 | 我为什么留它 |
| --- | --- |
| [Stirling PDF](https://github.com/Stirling-Tools/Stirling-PDF) | 可自托管的 PDF 工具箱。 |
| [PDF24](https://www.pdf24.org/en/) | 在线/桌面 PDF 工具。 |
| [OCRmyPDF](https://ocrmypdf.readthedocs.io/) | 给扫描 PDF 加 OCR 文本层。 |
| [Tesseract OCR](https://github.com/tesseract-ocr/tesseract) | 开源 OCR 引擎。 |
| [Paperless-ngx](https://github.com/paperless-ngx/paperless-ngx) | 文档归档和 OCR 管理。 |
| [Pandoc](https://pandoc.org/) | 文档格式转换瑞士军刀。 |
| [Calibre](https://calibre-ebook.com/) | 电子书管理和转换。 |
| [Mathpix](https://mathpix.com/) | 公式和文档 OCR。 |

## 我的使用顺序

- 扫描件先 OCR，再归档。
- 论文 PDF 用 Zotero 管理，办公 PDF 用 Stirling/PDF24。
- 大批量转换优先 Pandoc 或脚本。

## 别踩坑

- 敏感文件不要上传到未知在线工具。
- OCR 结果必须人工核对。

## 截图来源

这张图来自公开页面：[https://github.com/Stirling-Tools/Stirling-PDF](https://github.com/Stirling-Tools/Stirling-PDF)。如果页面改版，截图可能会和当前官网略有出入。

## 维护方式

链接数据放在 [`data/links.json`](data/links.json)。我倾向于少而准：入口失效就换，说明过时就改，不把这里做成什么都往里塞的大杂烩。

## License

MIT. 第三方商标、页面截图和网站内容归原权利方所有；本仓库只做中文导航和使用笔记。
