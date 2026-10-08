---
title: "MhtmlSaveOptions"
second_title: "GroupDocs.Editor для .NET справочник API"
description: "Позволяет указать пользовательские параметры для генерации и сохранения MIME‑инкапсуляции MHTML агрегированных HTML‑документов документов"
type: docs
weight: 1020
url: /ru/net/groupdocs.editor.options/mhtmlsaveoptions/
---
## MhtmlSaveOptions class

Позволяет задавать пользовательские параметры для создания и сохранения документов MHTML (MIME‑инкапсуляция агрегированных HTML‑документов)

```csharp
public sealed class MhtmlSaveOptions : ISaveOptions
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [MhtmlSaveOptions](mhtmlsaveoptions)() | Конструктор по умолчанию. |

## Свойства

| Имя | Описание |
| --- | --- |
| [ExportCidUrls](../../groupdocs.editor.options/mhtmlsaveoptions/exportcidurls) { get; set; } | Указывает, использовать ли CID (Content-ID) URL для ссылки на ресурсы (изображения, шрифты, CSS), включённые в документы MHTML. Значение по умолчанию — `false`. |
| [ExportDocumentProperties](../../groupdocs.editor.options/mhtmlsaveoptions/exportdocumentproperties) { get; set; } | Указывает, экспортировать ли встроенные и пользовательские свойства документа в MHTML. Значение по умолчанию — `false`. |
| [ExportLanguageInformation](../../groupdocs.editor.options/mhtmlsaveoptions/exportlanguageinformation) { get; set; } | Указывает, экспортировать ли информацию о языке в MHTML. Значение по умолчанию — `false`. |

### См. также

* interface [ISaveOptions](../isaveoptions)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.editor.dll -->
