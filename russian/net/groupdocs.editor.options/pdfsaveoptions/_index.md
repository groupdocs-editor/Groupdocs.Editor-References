---
title: "PdfSaveOptions"
second_title: "GroupDocs.Editor для .NET справочник API"
description: "Позволяет задавать пользовательские параметры для создания и сохранения документов PDF (Portable Document Format)."
type: docs
weight: 1070
url: /ru/net/groupdocs.editor.options/pdfsaveoptions/
---
## PdfSaveOptions class

Позволяет задавать пользовательские параметры для создания и сохранения PDF‑документов (Portable Document Format)

```csharp
public sealed class PdfSaveOptions : ISaveOptions
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [PdfSaveOptions](pdfsaveoptions)() | Конструктор по умолчанию. |

## Свойства

| Имя | Описание |
| --- | --- |
| [Compliance](../../groupdocs.editor.options/pdfsaveoptions/compliance) { get; set; } | Указывает уровень соответствия стандартам PDF для выходных документов. По умолчанию — PdfCompliance.Pdf17. |
| [FontEmbedding](../../groupdocs.editor.options/pdfsaveoptions/fontembedding) { get; set; } | Отвечает за встраивание ресурсов шрифтов, используемых в оригинальном документе, в результирующий PDF‑документ. По умолчанию не встраивает шрифты (NotEmbed). |
| [OptimizeMemoryUsage](../../groupdocs.editor.options/pdfsaveoptions/optimizememoryusage) { get; set; } | Включает механизмы оптимизации памяти при генерации документа из HTML, что снижает производительность в качестве цены за уменьшение использования памяти. Установка этой опции в true может значительно снизить потребление памяти при генерации больших документов за счёт более медленного времени сохранения. По умолчанию false (оптимизация памяти отключена ради лучшей производительности). |
| [Password](../../groupdocs.editor.options/pdfsaveoptions/password) { get; set; } | Пароль, который будет применён к созданному PDF‑документу как пользовательский пароль, требуемый для открытия. Если NULL или пустой, пароль к документу применён не будет. В противном случае документ будет зашифрован с помощью RC4 (длина ключа 128 бит). По умолчанию — NULL — пароль не применяется. |

### См. также

* interface [ISaveOptions](../isaveoptions)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.editor.dll -->
