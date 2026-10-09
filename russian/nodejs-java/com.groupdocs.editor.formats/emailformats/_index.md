---
title: "EmailFormats"
second_title: "GroupDocs.Editor для Node.js через Java API Reference"
description: "Инкапсулирует все форматы электронной почты."
type: docs
weight: 11
url: /ru/nodejs-java/com.groupdocs.editor.formats/emailformats/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.formats.abstraction.FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase), [com.groupdocs.editor.formats.abstraction.DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase)
```
public class EmailFormats extends DocumentFormatBase
```

Инкапсулирует все форматы электронных писем. Включает следующие типы файлов:
[Tnef](../../com.groupdocs.editor.formats/emailformats#Tnef),
[Eml](../../com.groupdocs.editor.formats/emailformats#Eml),
[Emlx](../../com.groupdocs.editor.formats/emailformats#Emlx),
[Msg](../../com.groupdocs.editor.formats/emailformats#Msg),
[Html](../../com.groupdocs.editor.formats/emailformats#Html),
[Mhtml](../../com.groupdocs.editor.formats/emailformats#Mhtml).

<br />

*** ** * ** ***

Узнайте больше о формате электронных писем [здесь](../https://docs.fileformat.com/email/).

<br />


## Поля

| Поле | Описание |
| --- | --- |
|  | [Tnef](#Tnef) | Transport Neutral Encapsulation Format (TNEF) — это проприетарный формат Microsoft для инкапсуляции вложений электронной почты, основанный на Messaging Application Programming Interface (MAPI). |
|
|  | [Eml](#Eml) | Формат файлов EML представляет электронные сообщения, сохранённые с помощью Outlook и других соответствующих приложений. |
|
|  | [Emlx](#Emlx) | Формат файлов EMLX реализован и разработан компанией Apple. |
|
|  | [Msg](#Msg) | MSG — это формат файлов, используемый Microsoft Outlook и Exchange для хранения электронных сообщений, контактов, встреч или других задач. |
|
|  | [Html](#Html) | Электронные письма в формате HTML. |
|
|  | [Mhtml](#Mhtml) | MHTML, аббревиатура от «MIME encapsulation of aggregate HTML documents». |
|
|  | [Ics](#Ics) | Internet Calendaring and Scheduling Core Object Specification (iCalendar) — это интернет-стандарт (RFC 2445) для обмена и развертывания календарных событий и планирования. |
|
|  | [Vcf](#Vcf) | VCF (Virtual Card Format) или vCard — цифровой формат файла для хранения контактной информации. |
|
|  | [Pst](#Pst) | Файлы с расширением .pst представляют Outlook Personal Storage Files (также называемые Personal Storage Table), которые хранят разнообразную пользовательскую информацию. |
|
|  | [Mbox](#Mbox) | Формат файла MBox — это общее название контейнера для коллекции электронных сообщений. |
|
|  | [Oft](#Oft) | Файлы с расширением .oft являются шаблонными файлами, создаваемыми с помощью Microsoft Outlook. |
|
|  | [Ost](#Ost) | Файл Offline Storage Table (OST) представляет данные почтового ящика пользователя в автономном режиме на локальном компьютере после регистрации на Exchange Server с использованием Microsoft Outlook. |
|
## Методы

| Метод | Описание |
| --- | --- |
|  | [getAll()](#getAll--) | Получает перечисляемую коллекцию всех [EmailFormats](../../com.groupdocs.editor.formats/emailformats). |
|
|  | [fromExtension(String extension)](#fromExtension-java.lang.String-) | Возвращает экземпляр указанного типа [EmailFormats](../../com.groupdocs.editor.formats/emailformats), имеющий указанное расширение файла. |
|
|  | [fromString(String extension)](#fromString-java.lang.String-) | Преобразует строку, представляющую расширение файла, в объект [EmailFormats](../../com.groupdocs.editor.formats/emailformats). |
|
### Tnef {#Tnef}
```
public static final EmailFormats Tnef
```


Transport Neutral Encapsulation Format (TNEF) — это проприетарный формат Microsoft для инкапсуляции вложений электронной почты, основанный на Messaging Application Programming Interface (MAPI).
Узнайте больше об этом формате файла
[here](../https://docs.fileformat.com/email/tnef/)
.


### Eml {#Eml}
```
public static final EmailFormats Eml
```


Формат файлов EML представляет электронные сообщения, сохранённые с помощью Outlook и других соответствующих приложений.
Узнайте больше об этом формате файла
[here](../https://docs.fileformat.com/email/eml/)
.


### Emlx {#Emlx}
```
public static final EmailFormats Emlx
```


Формат файла EMLX реализован и разработан компанией Apple. Приложение Apple Mail использует формат EMLX для экспорта электронных писем.
Узнайте больше об этом формате файла
[here](../https://docs.fileformat.com/email/emlx/)
.


### Msg {#Msg}
```
public static final EmailFormats Msg
```


MSG — это формат файлов, используемый Microsoft Outlook и Exchange для хранения электронных сообщений, контактов, встреч или других задач.
Узнайте больше об этом формате файла
[here](../https://docs.fileformat.com/email/msg/)
.


### Html {#Html}
```
public static final EmailFormats Html
```


Электронные письма в формате HTML.


### Mhtml {#Mhtml}
```
public static final EmailFormats Mhtml
```


MHTML, аббревиатура от «MIME encapsulation of aggregate HTML documents».


### Ics {#Ics}
```
public static final EmailFormats Ics
```


Internet Calendaring and Scheduling Core Object Specification (iCalendar) — это интернет-стандарт (RFC 2445) для обмена и развертывания календарных событий и планирования.
Узнайте больше об этом формате файла
[here](../https://docs.fileformat.com/email/ics/)
.


### Vcf {#Vcf}
```
public static final EmailFormats Vcf
```


VCF (Virtual Card Format) или vCard — цифровой формат файла для хранения контактной информации.
Узнайте больше об этом формате файла
[here](../https://docs.fileformat.com/email/vcf/)
.


### Pst {#Pst}
```
public static final EmailFormats Pst
```


Файлы с расширением .pst представляют Outlook Personal Storage Files (также называемые Personal Storage Table), которые хранят разнообразную пользовательскую информацию.
Узнайте больше об этом формате файла
[here](../https://docs.fileformat.com/email/pst/)
.


### Mbox {#Mbox}
```
public static final EmailFormats Mbox
```


Формат файла MBox — это общее название контейнера для коллекции электронных сообщений.
Узнайте больше об этом формате файла
[here](../https://docs.fileformat.com/email/mbox/)
.


### Oft {#Oft}
```
public static final EmailFormats Oft
```


Файлы с расширением .oft являются шаблонными файлами, создаваемыми с помощью Microsoft Outlook.
Узнайте больше об этом формате файла
[here](../https://docs.fileformat.com/email/oft/)
.


### Ost {#Ost}
```
public static final EmailFormats Ost
```


Файл Offline Storage Table (OST) представляет данные почтового ящика пользователя в автономном режиме на локальном компьютере после регистрации на Exchange Server с использованием Microsoft Outlook.
Узнайте больше об этом формате файла
[here](../https://docs.fileformat.com/email/ost/)
.


### getAll() {#getAll--}
```
public static List<EmailFormats> getAll()
```


Получает перечисляемую коллекцию всех [EmailFormats](../../com.groupdocs.editor.formats/emailformats).
Значение: IEnumerable{EmailFormats}, содержащий все экземпляры [EmailFormats](../../com.groupdocs.editor.formats/emailformats).


**Returns:**
java.util.List<com.groupdocs.editor.formats.EmailFormats>
### fromExtension(String extension) {#fromExtension-java.lang.String-}
```
public static EmailFormats fromExtension(String extension)
```


Возвращает экземпляр указанного типа [EmailFormats](../../com.groupdocs.editor.formats/emailformats), имеющий указанное расширение файла.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | расширение | java.lang.String | Расширение файла формата документа. |
|

**Returns:**
[EmailFormats](../../com.groupdocs.editor.formats/emailformats) - An instance of the specified type [EmailFormats](../../com.groupdocs.editor.formats/emailformats) with the specified file extension.

### fromString(String extension) {#fromString-java.lang.String-}
```
public static EmailFormats fromString(String extension)
```


Преобразует строку, представляющую расширение файла, в объект [EmailFormats](../../com.groupdocs.editor.formats/emailformats).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | расширение | java.lang.String | Расширение файла для конвертации. Если расширение содержит несколько точек, используется часть после последней точки. |
|

**Returns:**
[EmailFormats](../../com.groupdocs.editor.formats/emailformats) - A [EmailFormats](../../com.groupdocs.editor.formats/emailformats) object corresponding to the specified file extension.

