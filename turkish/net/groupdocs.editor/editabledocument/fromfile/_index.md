---
title: FromFile
second_title: .NET API Başvurusu için GroupDocs.Editor
description: Bir HTML dosyasından EditableDocument örneğini oluşturan statik fabrika .html dosyasının kendisine giden bir yol ve bağlantılı kaynaklara sahip bir klasör
type: docs
weight: 10
url: /tr/net/groupdocs.editor/editabledocument/fromfile/
---
## EditableDocument.FromFile method

Bir HTML dosyasından EditableDocument örneğini oluşturan statik fabrika, *.html dosyasının kendisine giden bir yol ve bağlantılı kaynaklara sahip bir klasör

```csharp
public static EditableDocument FromFile(string htmlFilePath, string resourceFolderPath)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| htmlFilePath | String | HTML dosyasının tam yolunu içeren dize. Boş olamaz, geçerli dosya yolu olmalı ve dosyanın kendisi mevcut olmalıdır. |
| resourceFolderPath | String | HTML kaynaklarına sahip klasörün isteğe bağlı yolu. NULL, geçersiz veya böyle bir klasör yoksa Editör, HTML işaretlemesini analiz ederek bu klasörü kendi başına bulmaya çalışacaktır. |

### Geri dönüş değeri

DüzenlenebilirDocument'in boş olmayan yeni örneği

### istisnalar

| istisna | şart |
| --- | --- |
| ArgumentException | HTML dosya yolu ve/veya kaynak klasör yolu geçersizdir/geçersizdir |
| FileNotFoundException | Belirtilen HTML dosyası bulunamadı |

### Ayrıca bakınız

* class [EditableDocument](../../editabledocument)
* ad alanı [GroupDocs.Editor](../../editabledocument)
* toplantı [GroupDocs.Editor](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
