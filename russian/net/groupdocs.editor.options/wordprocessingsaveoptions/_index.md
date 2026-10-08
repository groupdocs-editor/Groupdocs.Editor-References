---
title: "WordProcessingSaveOptions"
second_title: "GroupDocs.Editor для .NET справочник API"
description: "Позволяет указывать пользовательские параметры для создания и сохранения совместимых с WordProcessing документов после их редактирования"
type: docs
weight: 1240
url: /ru/net/groupdocs.editor.options/wordprocessingsaveoptions/
---
## WordProcessingSaveOptions class

Позволяет задавать пользовательские параметры для создания и сохранения документов, совместимых с обработкой текста, после их редактирования

```csharp
public sealed class WordProcessingSaveOptions : ICloneable, ISaveOptions
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [WordProcessingSaveOptions](wordprocessingsaveoptions#constructor)() | Этот конструктор без параметров создаёт новый экземпляр WordProcessingSaveOptions с форматом вывода DOCX (может быть изменён позже через свойство [`OutputFormat`](./outputformat)) |
| [WordProcessingSaveOptions](wordprocessingsaveoptions#constructor_1)(WordProcessingFormats) | Создаёт новый экземпляр WordProcessingSaveOptions с указанным обязательным форматом вывода WordProcessing, при этом все остальные параметры имеют значения по умолчанию |

## Свойства

| Имя | Описание |
| --- | --- |
| [EnablePagination](../../groupdocs.editor.options/wordprocessingsaveoptions/enablepagination) { get; set; } | Позволяет включать или отключать разбиение на страницы, которое будет использоваться при сохранении документа WordProcessing. Если исходный документ был открыт и отредактирован в режиме разбиения на страницы, эту опцию также следует включить. По умолчанию отключено. |
| [FontEmbedding](../../groupdocs.editor.options/wordprocessingsaveoptions/fontembedding) { get; set; } | Отвечает за встраивание ресурсов шрифтов в выходной документ WordProcessing. По умолчанию не встраивает никакие шрифты (NotEmbed). |
| [Locale](../../groupdocs.editor.options/wordprocessingsaveoptions/locale) { get; set; } | Позволяет задать переопределение локали (языка) по умолчанию для документа WordProcessing, которое будет применено при его создании. Если не указано (значение по умолчанию), MS Word (или другая программа) определит (или выберет) локаль документа в соответствии со своими настройками или другими факторами. |
| [LocaleBi](../../groupdocs.editor.options/wordprocessingsaveoptions/localebi) { get; set; } | Позволяет задать переопределение локали (языка) для документа WordProcessing для RTL‑текста (справа налево), которое будет применено при его создании. Если не указано (значение по умолчанию), MS Word (или другая программа) определит (или выберет) RTL‑локаль документа в соответствии со своими настройками или другими факторами. |
| [LocaleFarEast](../../groupdocs.editor.options/wordprocessingsaveoptions/localefareast) { get; set; } | Позволяет переопределить локаль (язык) для документа WordProcessing для восточноазиатского текста, которое будет применено при его создании. Если не указано (значение по умолчанию), MS Word (или другая программа) определит (или выберет) восточноазиатскую локаль документа в соответствии со своими настройками или другими факторами. |
| [OptimizeMemoryUsage](../../groupdocs.editor.options/wordprocessingsaveoptions/optimizememoryusage) { get; set; } | Включает механизмы оптимизации памяти при генерации документа из HTML, что снижает производительность в качестве цены за уменьшение использования памяти. Установка этой опции в true может значительно снизить потребление памяти при генерации больших документов за счёт более медленного времени сохранения. По умолчанию false (оптимизация памяти отключена ради лучшей производительности). |
| [OutputFormat](../../groupdocs.editor.options/wordprocessingsaveoptions/outputformat) { get; set; } | Позволяет указать формат WordProcessing, который будет использоваться для сохранения документа |
| [Password](../../groupdocs.editor.options/wordprocessingsaveoptions/password) { get; set; } | Позволяет указывать, изменять, получать или удалять пароль, который будет использоваться для кодирования сгенерированного документа WordProcessing. Укажите NULL или пустую строку для удаления (очистки) пароля. |
| [Protection](../../groupdocs.editor.options/wordprocessingsaveoptions/protection) { get; set; } | Позволяет управлять и применять параметры защиты документа для любого формата документа WordProcessing, поддерживающего защиту. По умолчанию NULL — защита документа не будет использоваться. |

## Методы

| Имя | Описание |
| --- | --- |
| [Clone](../../groupdocs.editor.options/wordprocessingsaveoptions/clone)() | Создаёт и возвращает полную копию данного экземпляра класса WordProcessingSaveOptions |

### Замечания

WordProcessingSaveOptions применяется в ситуациях, когда существует экземпляр класса EditableDocument, содержащий отредактированное содержимое документа, и требуется сохранить это содержимое в новый документ формата WordProcessing.

### См. также

* interface [ISaveOptions](../isaveoptions)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.editor.dll -->
