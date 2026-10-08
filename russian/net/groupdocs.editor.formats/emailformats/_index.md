---
title: "EmailFormats"
second_title: "GroupDocs.Editor для .NET справочник API"
description: "Инкапсулирует все форматы электронных писем. Включает следующие типы файлов Tnef./emailformats/tnef Eml./emailformats/eml Emlx./emailformats/emlx Msg./emailformats/msg Html./emailformats/html Mhtml./emailformats/mhtml."
type: docs
weight: 90
url: /ru/net/groupdocs.editor.formats/emailformats/
---
## EmailFormats class

Инкапсулирует все форматы электронных писем. Включает следующие типы файлов: [`Tnef`](./tnef), [`Eml`](./eml), [`Emlx`](./emlx), [`Msg`](./msg), [`Html`](./html), [`Mhtml`](./mhtml).

```csharp
public class EmailFormats : DocumentFormatBase
```

## Свойства

| Имя | Описание |
| --- | --- |
| [Extension](../../groupdocs.editor.formats.abstraction/documentformatbase/extension) { get; } | Возвращает расширение файла формата документа. |
| [FormatFamily](../../groupdocs.editor.formats.abstraction/documentformatbase/formatfamily) { get; } | Возвращает семейство форматов, к которому относится формат документа. |
| [Id](../../groupdocs.editor.formats.abstraction/formatfamilybase/id) { get; } | Возвращает уникальный идентификатор семейства форматов. |
| [Mime](../../groupdocs.editor.formats.abstraction/documentformatbase/mime) { get; } | Возвращает MIME‑тип формата документа. |
| [Name](../../groupdocs.editor.formats.abstraction/formatfamilybase/name) { get; } | Возвращает название семейства форматов. |
| static [All](../../groupdocs.editor.formats/emailformats/all) { get; } | Получает перечисляемую коллекцию всех [`EmailFormats`](../emailformats). |

## Методы

| Имя | Описание |
| --- | --- |
| static [FromExtension](../../groupdocs.editor.formats/emailformats/fromextension)(string) | Возвращает экземпляр указанного типа [`EmailFormats`](../emailformats), имеющего заданное расширение файла. |
| [Equals](../../groupdocs.editor.formats.abstraction/formatfamilybase/equals)(FormatFamilyBase) | Определяет, равен ли данный экземпляр указанному экземпляру [`FormatFamilyBase`](../../groupdocs.editor.formats.abstraction/formatfamilybase). |
| [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals)(IDocumentFormat) | Определяет, равен ли данный экземпляр указанному экземпляру [`IDocumentFormat`](../../groupdocs.editor.formats.abstraction/idocumentformat). |
| override [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals)(object) | Определяет, равен ли данный экземпляр указанному экземпляру [`DocumentFormatBase`](../../groupdocs.editor.formats.abstraction/documentformatbase). |
| override [GetHashCode](../../groupdocs.editor.formats.abstraction/documentformatbase/gethashcode)() | Возвращает хеш‑код текущего объекта. |
| override [ToString](../../groupdocs.editor.formats.abstraction/formatfamilybase/tostring)() | Возвращает строку, представляющую текущий объект. |
| [explicit operator](../../groupdocs.editor.formats/emailformats/op_explicit) | Преобразует строку, представляющую расширение файла, в объект [`EmailFormats`](../emailformats). |

## Поля

| Имя | Описание |
| --- | --- |
| static readonly [Eml](../../groupdocs.editor.formats/emailformats/eml) | Формат файла EML представляет электронные сообщения, сохранённые с помощью Outlook и других соответствующих приложений. Узнайте больше о этом формате файла [здесь](https://docs.fileformat.com/email/eml/). |
| static readonly [Emlx](../../groupdocs.editor.formats/emailformats/emlx) | Формат файла EMLX реализован и разработан компанией Apple. Приложение Apple Mail использует формат EMLX для экспорта электронных писем. Узнайте больше о этом формате файла [здесь](https://docs.fileformat.com/email/emlx/). |
| static readonly [Html](../../groupdocs.editor.formats/emailformats/html) | Электронные письма в формате HTML. |
| static readonly [Ics](../../groupdocs.editor.formats/emailformats/ics) | Internet Calendaring and Scheduling Core Object Specification (iCalendar) — это интернет-стандарт (RFC 2445) для обмена и развертывания календарных событий и планирования. Узнайте больше о этом формате файла [здесь](https://docs.fileformat.com/email/ics/). |
| static readonly [Mbox](../../groupdocs.editor.formats/emailformats/mbox) | Формат файла MBox — это общее название, обозначающее контейнер для коллекции электронных сообщений. Узнайте больше о этом формате файла [здесь](https://docs.fileformat.com/email/mbox/). |
| static readonly [Mhtml](../../groupdocs.editor.formats/emailformats/mhtml) | MHTML, аббревиатура от "MIME encapsulation of aggregate HTML documents". |
| static readonly [Msg](../../groupdocs.editor.formats/emailformats/msg) | MSG — это формат файла, используемый Microsoft Outlook и Exchange для хранения электронных сообщений, контактов, встреч или других задач. Узнайте больше о этом формате файла [здесь](https://docs.fileformat.com/email/msg/). |
| static readonly [Oft](../../groupdocs.editor.formats/emailformats/oft) | Файлы с расширением .oft являются шаблонными файлами, создаваемыми с помощью Microsoft Outlook. Узнайте больше о этом формате файла [здесь](https://docs.fileformat.com/email/oft/). |
| static readonly [Ost](../../groupdocs.editor.formats/emailformats/ost) | Файл Offline Storage Table (OST) представляет данные почтового ящика пользователя в автономном режиме на локальном компьютере после регистрации на Exchange Server с помощью Microsoft Outlook. Узнайте больше о этом формате файла [здесь](https://docs.fileformat.com/email/ost/). |
| static readonly [Pst](../../groupdocs.editor.formats/emailformats/pst) | Файлы с расширением .pst представляют Outlook Personal Storage Files (также называемые Personal Storage Table), которые хранят разнообразную информацию о пользователе. Узнайте больше о этом формате файла [здесь](https://docs.fileformat.com/email/pst/). |
| static readonly [Tnef](../../groupdocs.editor.formats/emailformats/tnef) | Transport Neutral Encapsulation Format (TNEF) — это проприетарный формат Microsoft для инкапсуляции вложений электронной почты на основе Messaging Application Programming Interface (MAPI). Узнайте больше о этом формате файла [здесь](https://docs.fileformat.com/email/tnef/). |
| static readonly [Vcf](../../groupdocs.editor.formats/emailformats/vcf) | VCF (Virtual Card Format) или vCard — это цифровой формат файла для хранения контактной информации. Узнайте больше о этом формате файла [здесь](https://docs.fileformat.com/email/vcf/). |

### Замечания

Узнайте больше о формате электронной почты [здесь](https://docs.fileformat.com/email/).

### См. также

* class [DocumentFormatBase](../../groupdocs.editor.formats.abstraction/documentformatbase)
* namespace [GroupDocs.Editor.Formats](../../groupdocs.editor.formats)
* assembly [GroupDocs.Editor](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.editor.dll -->
