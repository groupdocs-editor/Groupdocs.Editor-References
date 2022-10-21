---
title: EmailFormats
second_title: Справочник по API GroupDocs.Editor для .NET
description: Инкапсулирует все форматы электронных писем. Включает следующие типы файлов Tnef./emailformats/tnef  Eml./emailformats/eml  Emlx./emailformats/emlx  Msg./emailformats/msg  Html./emailformats/html  Mhtml./emailformats/mhtml .
type: docs
weight: 60
url: /ru/net/groupdocs.editor.formats/emailformats/
---
## EmailFormats structure

Инкапсулирует все форматы электронных писем. Включает следующие типы файлов: [`Tnef`](./tnef) , [`Eml`](./eml) , [`Emlx`](./emlx) , [`Msg`](./msg) , [`Html`](./html) , [`Mhtml`](./mhtml) .

```csharp
public struct EmailFormats : IDocumentFormat, IEquatable<EmailFormats>
```

## Характеристики

| Имя | Описание |
| --- | --- |
| [Extension](../../groupdocs.editor.formats/emailformats/extension) { get; } | В реализации тип должен возвращать расширение файла формата (без начального символа точки). |
| [Mime](../../groupdocs.editor.formats/emailformats/mime) { get; } | При реализации тип должен возвращать MIME-код для заданного формата |
| [Name](../../groupdocs.editor.formats/emailformats/name) { get; } | В реализации тип должен возвращать имя полного формального формата name |

## Методы

| Имя | Описание |
| --- | --- |
| static [FromExtension](../../groupdocs.editor.formats/emailformats/fromextension)(string) | Возвращает экземпляр[`EmailFormats`](../emailformats)структура, связанная с указанным расширением имени файла, или выдает исключение, если расширение не может быть правильно проанализировано |
| [Equals](../../groupdocs.editor.formats/emailformats/equals#equals)(EmailFormats) | Определяет, равен ли этот экземпляр другому указанному экземпляру Email |
| [Equals](../../groupdocs.editor.formats/emailformats/equals#equals_1)(IDocumentFormat) | Определяет, равен ли этот экземпляр другому указанному IDocumentFormat instance |
| override [Equals](../../groupdocs.editor.formats/emailformats/equals#equals_2)(object) | Определяет, равен ли этот экземпляр другому указанному объекту, который предположительно представляет собой упакованный Email |
| override [GetHashCode](../../groupdocs.editor.formats/emailformats/gethashcode)() | Возвращает хеш-код, неизменяемый для данного экземпляра |
| override [ToString](../../groupdocs.editor.formats/emailformats/tostring)() | Возвращает имя формата этого формата |
| [operator ==](../../groupdocs.editor.formats/emailformats/op_equality) | Проверяет два заданных экземпляра электронной почты на равенство |
| [operator !=](../../groupdocs.editor.formats/emailformats/op_inequality) | Проверяет два заданных экземпляра электронной почты на неравенство |

## Поля

| Имя | Описание |
| --- | --- |
| static readonly [Eml](../../groupdocs.editor.formats/emailformats/eml) | Формат файла EML представляет сообщения электронной почты, сохраненные с помощью Outlook и других соответствующих приложений. Узнайте больше об этом формате файла[здесь](https://docs.fileformat.com/email/eml/) . |
| static readonly [Emlx](../../groupdocs.editor.formats/emailformats/emlx) | Формат файла EMLX реализован и разработан Apple. Приложение Apple Mail использует формат файла EMLX для экспорта электронных писем. Узнайте больше об этом формате файла[здесь](https://docs.fileformat.com/email/emlx/) . |
| static readonly [Html](../../groupdocs.editor.formats/emailformats/html) | Электронные письма в формате HTML. |
| static readonly [Ics](../../groupdocs.editor.formats/emailformats/ics) | Спецификация основных объектов календаря и планирования Интернета (iCalendar) представляет собой интернет-стандарт (RFC 2445) для обмена и развертывания событий календаря и планирования. Узнайте больше об этом формате файла[здесь](https://docs.fileformat.com/email/ics/) . |
| static readonly [Mbox](../../groupdocs.editor.formats/emailformats/mbox) | Формат файла MBox — это общий термин, обозначающий контейнер для сбора сообщений электронной почты. Узнайте больше об этом формате файла[здесь](https://docs.fileformat.com/email/mbox/) . |
| static readonly [Mhtml](../../groupdocs.editor.formats/emailformats/mhtml) | MHTML, инициализм «MIME-инкапсуляции совокупных документов HTML» |
| static readonly [Msg](../../groupdocs.editor.formats/emailformats/msg) | MSG — это формат файла, используемый Microsoft Outlook и Exchange для хранения сообщений электронной почты, контактов, встреч и других задач. Подробнее об этом формате файла[здесь](https://docs.fileformat.com/email/msg/) . |
| static readonly [Oft](../../groupdocs.editor.formats/emailformats/oft) | Файлы с расширением .oft — это файлы шаблонов, созданные с помощью Microsoft Outlook. Подробнее об этом формате файлов[здесь](https://docs.fileformat.com/email/oft/) . |
| static readonly [Ost](../../groupdocs.editor.formats/emailformats/ost) | Файл таблицы автономного хранилища (OST) представляет данные почтового ящика пользователя в автономном режиме на локальном компьютере после регистрации на сервере Exchange с помощью Microsoft Outlook. Подробнее об этом формате файла[здесь](https://docs.fileformat.com/email/ost/) . |
| static readonly [Pst](../../groupdocs.editor.formats/emailformats/pst) | Файлы с расширением .pst представляют собой файлы личного хранилища Outlook (также называемые таблицей личного хранилища), в которых хранится разнообразная информация о пользователях. Узнайте больше об этом формате файла[здесь](https://docs.fileformat.com/email/pst/) . |
| static readonly [Tnef](../../groupdocs.editor.formats/emailformats/tnef) | Транспортно-нейтральный формат инкапсуляции (TNEF) — это проприетарный формат Microsoft для инкапсуляции вложений электронной почты на основе интерфейса программирования приложений для обмена сообщениями (MAPI). Подробнее об этом формате файла[здесь](https://docs.fileformat.com/email/tnef/) . |
| static readonly [Vcf](../../groupdocs.editor.formats/emailformats/vcf) | VCF (формат виртуальной карты) или vCard — это цифровой формат файла для хранения контактной информации. Узнайте больше об этом формате файла[здесь](https://docs.fileformat.com/email/vcf/) . |
| static readonly [All](../../groupdocs.editor.formats/emailformats/all) | Возвращает внутренний класс, который предоставляет перечисляемые возможности для всех существующих форматов электронной почты |

## Другие члены

| Имя | Описание |
| --- | --- |
| class [AllEnumerable](emailformats.allenumerable) | Реализует общий интерфейс IEnumerable, который включает возможность foreach для типа электронной почты |

### Примечания

Подробнее о формате электронных писем[здесь](https://docs.fileformat.com/email/) .

### Смотрите также

* interface [IDocumentFormat](../idocumentformat)
* пространство имен [GroupDocs.Editor.Formats](../../groupdocs.editor.formats)
* сборка [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
