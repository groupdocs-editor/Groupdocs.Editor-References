---
title: "ExportCidUrls"
second_title: "GroupDocs.Editor для .NET справочник API"
description: "Указывает, использовать ли CID ContentID URL для ссылки на ресурсы (изображения, шрифты, CSS), включённые в документы MHTML. Значение по умолчанию — false."
type: docs
weight: 20
url: /ru/net/groupdocs.editor.options/mhtmlsaveoptions/exportcidurls/
---
## MhtmlSaveOptions.ExportCidUrls property

Указывает, использовать ли CID (Content-ID) URL для ссылки на ресурсы (изображения, шрифты, CSS), включённые в документы MHTML. Значение по умолчанию — `false`.

```csharp
public bool ExportCidUrls { get; set; }
```

### Замечания

По умолчанию ресурсы в документах MHTML ссылаются по имени файла (например, "image.png"), которое сопоставляется с заголовками "Content-Location" MIME‑частей. Эта опция включает альтернативный метод, при котором ссылки на файлы ресурсов записываются как CID (Content-ID) URL (например, "cid:image.png") и сопоставляются с заголовками "Content-ID".

Теоретически между двумя методами ссылки не должно быть различий, и любой из них должен работать в любом браузере или почтовом клиенте. На практике же некоторые клиенты не могут получить ресурсы по имени файла. Если ваш браузер или почтовый клиент отказывается загружать ресурсы, включённые в документ MTHML (не отображаются изображения или не загружаются стили CSS), попробуйте экспортировать документ с CID‑URL.

### См. также

* class [MhtmlSaveOptions](../../mhtmlsaveoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.editor.dll -->
