---
title: GroupDocs.Editor.Options
second_title: GroupDocs.Editor for .NET API 参考
description: GroupDocs.Editor.Options 命名空间为加载和保存选项提供接口
type: docs
weight: 130
url: /zh/net/groupdocs.editor.options/
---
GroupDocs.Editor.Options 命名空间为加载和保存选项提供接口。

## 课程

| 班级 | 描述 |
| --- | --- |
| [Azw3SaveOptions](./azw3saveoptions) | 允许指定用于生成和保存 AZW3 电子书的自定义选项，也称为 Kindle Format 8 (KF8) |
| [DelimitedTextEditOptions](./delimitedtexteditoptions) | 用于加载使用分隔符（分隔符）的基于文本的电子表格文档（CSV、基于制表符等）的选项 |
| [DelimitedTextSaveOptions](./delimitedtextsaveoptions) | 包含用于生成和保存基于文本的电子表格文档（CSV、基于制表符等）的选项，这些文档使用分隔符（分隔符） |
| [EbookEditOptions](./ebookeditoptions) | 允许指定和调整用于编辑所有支持格式的电子书文档的自定义选项：ePub、MOBI 和 AZW3。 |
| [EmailEditOptions](./emaileditoptions) | 允许指定自定义选项以编辑不同电子邮件（电子邮件）格式的文档 |
| [EmailSaveOptions](./emailsaveoptions) | 允许指定用于生成和保存电子邮件（电子邮件）文档的自定义选项 |
| [EpubSaveOptions](./epubsaveoptions) | 允许指定用于生成和保存 IDPF EPUB 文档的自定义选项（国际数字出版论坛创建的电子书开放标准） |
| [FixedLayoutEditOptionsBase](./fixedlayouteditoptionsbase) | 用于固定布局格式（如 PDF 和 XPS）的所有文档的选项的基本抽象类 |
| [MhtmlSaveOptions](./mhtmlsaveoptions) | 允许指定用于生成和保存 MHTML（聚合 HTML 文档的 MIME 封装）文档的自定义选项 |
| [PdfEditOptions](./pdfeditoptions) | 允许指定用于编辑 PDF 文档的自定义选项 |
| [PdfLoadOptions](./pdfloadoptions) | 包含将 PDF 文档加载到编辑器的选项类 |
| [PdfSaveOptions](./pdfsaveoptions) | 允许指定用于生成和保存 PDF（便携式文档格式）文档的自定义选项 |
| [PresentationEditOptions](./presentationeditoptions) | 允许为编辑所有可支持的演示文稿（PowerPoint 兼容）格式的文档指定自定义选项 |
| [PresentationLoadOptions](./presentationloadoptions) | 允许指定自定义选项以加载所有可支持的演示文稿格式的文档，如 PPT(X)、PPTM、PPS(X) 等。 |
| [PresentationSaveOptions](./presentationsaveoptions) | 允许指定用于生成和保存演示文稿（PowerPoint 兼容）文档的自定义选项 |
| [SpreadsheetEditOptions](./spreadsheeteditoptions) | 允许为编辑所有支持的电子表格（Excel 兼容）格式的文档指定自定义选项 |
| [SpreadsheetLoadOptions](./spreadsheetloadoptions) | 包含将二进制电子表格（单元格、Excel 兼容）文档（如 XLS(X)、ODS 等）加载到编辑器中的选项 class |
| [SpreadsheetSaveOptions](./spreadsheetsaveoptions) | 允许指定用于生成和保存电子表格（Excel 兼容）文档的自定义选项 |
| [TextEditOptions](./texteditoptions) | 允许指定用于加载纯文本 (TXT) 文档的自定义选项 |
| [TextSaveOptions](./textsaveoptions) | 允许指定用于生成和保存纯文本 (TXT) 文档的自定义选项 |
| [WordProcessingEditOptions](./wordprocessingeditoptions) | 允许指定自定义选项以编辑所有可支持的文字处理（Words-compliant）格式的文档，如 DOC(X)、RTF、ODT 等。 |
| [WordProcessingLoadOptions](./wordprocessingloadoptions) | 包含用于将 DOC(X)、RTF、ODT 等 WordProcessing（Word 兼容）文档加载到编辑器中的选项 class |
| [WordProcessingProtection](./wordprocessingprotection) | 封装 WordProcessing 文档的文档保护选项，由 HTML 生成 |
| [WordProcessingSaveOptions](./wordprocessingsaveoptions) | 允许指定自定义选项以在编辑后生成和保存符合 WordProcessing 的文档 |
| [WorksheetProtection](./worksheetprotection) | 封装工作表保护选项，允许保护输出电子表格文档中的工作表不被修改指定类型 与指定的密码。 |
| [XmlEditOptions](./xmleditoptions) | 允许指定自定义选项以加载 XML（可扩展标记语言）文档并将它们转换为 HTML |
| [XmlHighlightOptions](./xmlhighlightoptions) | 包含允许在 XML 到 HTML 转换期间自定义 XML 突出显示的选项 |
| [XpsEditOptions](./xpseditoptions) | 允许指定用于编辑（XML 纸张规格）文档的自定义选项 |
| [XpsSaveOptions](./xpssaveoptions) | 允许指定用于生成和保存 XPS（XML 纸张规范）文档的自定义选项 |
## 结构

| 结构 | 描述 |
| --- | --- |
| [PageRange](./pagerange) | 封装一个页面范围，可以有开放或封闭的边界。默认情况下是“完全打开” - 它包括所有现有页面。页码从 1 开始，而不是从 0. |
## 接口

| 界面 | 描述 |
| --- | --- |
| [IEditOptions](./ieditoptions) | 所有选项的通用接口，负责文档到 HTML 的转换。声明没有成员。 |
| [ILoadOptions](./iloadoptions) | 所有选项类的通用接口，负责加载不同类型格式的文档 |
| [ISaveOptions](./isaveoptions) | 所有文档类型的所有保存选项的接口。声明没有成员。 |
## 枚举

| 枚举 | 描述 |
| --- | --- |
| [FontEmbeddingOptions](./fontembeddingoptions) | 字体嵌入选项控制应将哪些字体资源嵌入到输出字处理或 PDF 文档中 |
| [FontExtractionOptions](./fontextractionoptions) | 字体提取选项控制应该提取哪些字体以及从哪里提取 |
| [MailMessageOutput](./mailmessageoutput) | 控制应将邮件消息的哪些部分传送到输出处理 |
| [PdfCompliance](./pdfcompliance) | 指定 PDF 标准合规级别 |
| [TextDirection](./textdirection) | 表示 3 种可能的变体如何处理纯文本文档中的文本方向 |
| [TextLeadingSpacesOptions](./textleadingspacesoptions) | 包含在打开纯文本文档 (TXT) 期间用于前导空格处理的可用选项 |
| [TextTrailingSpacesOptions](./texttrailingspacesoptions) | 包含在打开纯文本文档 (TXT) 期间用于尾随空格处理的可用选项 |
| [WordProcessingProtectionType](./wordprocessingprotectiontype) | 表示文字处理文档的所有可用保护类型 |
| [WorksheetProtectionType](./worksheetprotectiontype) | 表示电子表格工作表（选项卡）保护类型 |

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->