---
title: "LocaleBi"
second_title: "GroupDocs.Editor для .NET справочник API"
description: "Позволяет задать переопределяющий язык локали для документа WordProcessing для RTL‑текста (right‑to‑left), который будет применён при его создании. Если не указано, значение по умолчанию — MS Word или другая программа определит или выберет RTL‑локаль документа в соответствии со своими настройками или другими факторами."
type: docs
weight: 50
url: /ru/net/groupdocs.editor.options/wordprocessingsaveoptions/localebi/
---
## WordProcessingSaveOptions.LocaleBi property

Позволяет задать переопределение локали (языка) для документа WordProcessing для RTL‑текста (справа налево), которое будет применено при его создании. Если не указано (значение по умолчанию), MS Word (или другая программа) определит (или выберет) RTL‑локаль документа в соответствии со своими настройками или другими факторами.

```csharp
public CultureInfo LocaleBi { get; set; }
```

### Замечания

Эта опция принудительно применяет указанную локаль ко всему RTL‑тексту в документе. Не используйте её, если документ содержит разные части текста, написанные на разных языках.

### См. также

* class [WordProcessingSaveOptions](../../wordprocessingsaveoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.editor.dll -->
