---
title: "LocaleFarEast"
second_title: "GroupDocs.Editor для .NET справочник API"
description: "Позволяет переопределить язык локали для документа WordProcessing для EastAsian‑текста, который будет применён при его создании. Если не указано, значение по умолчанию — MS Word или другая программа определит или выберет EastAsian‑локаль документа в соответствии со своими настройками или другими факторами."
type: docs
weight: 60
url: /ru/net/groupdocs.editor.options/wordprocessingsaveoptions/localefareast/
---
## WordProcessingSaveOptions.LocaleFarEast property

Позволяет переопределить локаль (язык) для документа WordProcessing для восточноазиатского текста, которое будет применено при его создании. Если не указано (значение по умолчанию), MS Word (или другая программа) определит (или выберет) восточноазиатскую локаль документа в соответствии со своими настройками или другими факторами.

```csharp
public CultureInfo LocaleFarEast { get; set; }
```

### Замечания

Эта опция принудительно применяет указанную локаль ко всему East‑Asian‑тексту в документе. Не используйте её, если документ содержит разные части текста, написанные на разных языках.

### См. также

* class [WordProcessingSaveOptions](../../wordprocessingsaveoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.editor.dll -->
