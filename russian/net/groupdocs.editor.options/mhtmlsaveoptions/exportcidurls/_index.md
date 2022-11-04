---
title: ExportCidUrls
second_title: Справочник по API GroupDocs.Editor для .NET
description: Указывает следует ли использовать URLадреса CID ContentID для ссылки на ресурсы изображения шрифты CSS включенные в документы MHTML. Значение по умолчаниюЛОЖЬ .
type: docs
weight: 20
url: /ru/net/groupdocs.editor.options/mhtmlsaveoptions/exportcidurls/
---
## MhtmlSaveOptions.ExportCidUrls property

Указывает, следует ли использовать URL-адреса CID (Content-ID) для ссылки на ресурсы (изображения, шрифты, CSS), включенные в документы MHTML. Значение по умолчанию`ЛОЖЬ` .

```csharp
public bool ExportCidUrls { get; set; }
```

### Примечания

По умолчанию на ресурсы в документах MHTML ссылаются по имени файла (например, «image.png»), которое сопоставляется с заголовками «Content-Location» частей MIME. Этот параметр включает альтернативный метод, при котором ссылки на файлы ресурсов записываются как URL-адреса CID (Content-ID) (например, «cid:image.png») и сопоставляются с заголовками «Content-ID».

Теоретически между двумя способами ссылки не должно быть разницы, и любой из них должен нормально работать в любом браузере или почтовом агенте. Однако на практике некоторым агентам не удается получить ресурсы по имени файла. Если ваш браузер или почтовый агент отказывается загружать ресурсы, включенные в документ MTHML (не показывает изображения или не загружает стили CSS), попробуйте экспортировать документ с URL-адресами CID.

### Смотрите также

* class [MhtmlSaveOptions](../../mhtmlsaveoptions)
* пространство имен [GroupDocs.Editor.Options](../../mhtmlsaveoptions)
* сборка [GroupDocs.Editor](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->