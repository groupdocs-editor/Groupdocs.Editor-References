---
title: "Локаль"
second_title: "GroupDocs.Editor для .NET справочник API"
description: "Позволяет задать переопределяющий язык локали по умолчанию для документа WordProcessing, который будет применён при его создании. Если не указано, значение по умолчанию — MS Word или другая программа определит или выберет локаль документа в соответствии со своими настройками или другими факторами."
type: docs
weight: 40
url: /ru/net/groupdocs.editor.options/wordprocessingsaveoptions/locale/
---
## WordProcessingSaveOptions.Locale property

Позволяет задать переопределение локали (языка) по умолчанию для документа WordProcessing, которое будет применено при его создании. Если не указано (значение по умолчанию), MS Word (или другая программа) определит (или выберет) локаль документа в соответствии со своими настройками или другими факторами.

```csharp
public CultureInfo Locale { get; set; }
```

### Замечания

Эта опция принудительно применяет указанную локаль ко всему тексту в документе. Не используйте её, если документ содержит разные части текста, написанные на разных языках.

### См. также

* class [WordProcessingSaveOptions](../../wordprocessingsaveoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.editor.dll -->
