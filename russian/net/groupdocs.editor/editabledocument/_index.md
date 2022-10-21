---
title: EditableDocument
second_title: Справочник по API GroupDocs.Editor для .NET
description: Промежуточный документ содержащий содержимое до и после редактирования
type: docs
weight: 10
url: /ru/net/groupdocs.editor/editabledocument/
---
## EditableDocument class

Промежуточный документ, содержащий содержимое до и после редактирования

```csharp
public sealed class EditableDocument : IAuxDisposable
```

## Характеристики

| Имя | Описание |
| --- | --- |
| [AllResources](../../groupdocs.editor/editabledocument/allresources) { get; } | Возвращает список всех существующих ресурсов: все таблицы стилей, изображения из HTML и все таблицы стилей, шрифты |
| [Audio](../../groupdocs.editor/editabledocument/audio) { get; } | Возвращает список аудиоресурсов |
| [Css](../../groupdocs.editor/editabledocument/css) { get; } | Возвращает список ресурсов CSS |
| [Fonts](../../groupdocs.editor/editabledocument/fonts) { get; } | Позволяет получить внешние ресурсы шрифта, используемые этим HTML-документом |
| [Images](../../groupdocs.editor/editabledocument/images) { get; } | Позволяет получить внешние ресурсы изображений (растровые изображения), которые используются данным HTML-документом |
| [IsDisposed](../../groupdocs.editor/editabledocument/isdisposed) { get; } | Определяет, был ли этот редактируемый документ уже удален (true) или нет (false) |

## Методы

| Имя | Описание |
| --- | --- |
| static [FromFile](../../groupdocs.editor/editabledocument/fromfile)(string, string) | Статическая фабрика, создающая экземпляр EditableDocument из файла HTML, указанный путем к самому файлу *.html и папке со связанными ресурсами |
| static [FromMarkup](../../groupdocs.editor/editabledocument/frommarkup)(string, IEnumerable&lt;IHtmlResource&gt;) | Статическая фабрика, которая создает экземпляр EditableDocument из указанной HTML-разметки и набора соответствующих связанных ресурсов |
| static [FromMarkupAndResourceFolder](../../groupdocs.editor/editabledocument/frommarkupandresourcefolder)(string, string) | Статическая фабрика, создающая экземпляр EditableDocument из указанной HTML-разметки и из ресурсов, расположенных в папке, указанной полным путем |
| [Dispose](../../groupdocs.editor/editabledocument/dispose)() | Удаляет этот экземпляр редактируемого документа, удаляя его содержимое и делая его методы и свойства нерабочими |
| [GetBodyContent](../../groupdocs.editor/editabledocument/getbodycontent#getbodycontent)() | Возвращает тело HTML-документа (содержимое между открывающим и закрывающим тегами BODY без этих тегов) в виде строки. |
| [GetBodyContent](../../groupdocs.editor/editabledocument/getbodycontent#getbodycontent_1)(string) | Возвращает тело HTML-документа (содержимое между открывающим и закрывающим тегами BODY без этих тегов) в виде строки, , где ссылки на внешние ресурсы содержат указанный префикс. |
| [GetContent](../../groupdocs.editor/editabledocument/getcontent#getcontent)() | Возвращает общее содержимое HTML-документа в виде строки. |
| [GetContent](../../groupdocs.editor/editabledocument/getcontent#getcontent_1)(string, string) | Возвращает общее содержимое HTML-документа в виде строки, в которой ссылки на внешние ресурсы содержат указанный префикс. |
| [GetCssContent](../../groupdocs.editor/editabledocument/getcsscontent#getcsscontent)() | Возвращает содержимое всех внешних таблиц стилей в виде списка строк, где одна строка представляет одну таблицу стилей. Возвращает пустой список, если для этого документа нет CSS. |
| [GetCssContent](../../groupdocs.editor/editabledocument/getcsscontent#getcsscontent_1)(string, string) | Возвращает содержимое всех внешних таблиц стилей в виде списка строк, где одна строка представляет одну таблицу стилей. Указанный префикс будет применяться к каждой ссылке на внешний ресурс в каждой результирующей таблице стилей. Возвращает пустой список, если для этого нет CSS документ. |
| [GetEmbeddedHtml](../../groupdocs.editor/editabledocument/getembeddedhtml)() | Возвращает все содержимое этого HTML-документа со всеми связанными ресурсами в виде одной строки, где все ресурсы встроены в HTML-разметку в формате с кодировкой base64. |
| [Save](../../groupdocs.editor/editabledocument/save#save)(string) | Сохраняет этот HTML-документ в файл по указанному пути, где будет храниться HTML-разметка, и в сопутствующую папку с ресурсами. |
| [Save](../../groupdocs.editor/editabledocument/save#save_1)(string, string) | Сохраняет этот HTML-документ в файл по указанному пути, где будет храниться HTML-разметка, и в сопутствующую папку с ресурсами, , расположенную по указанному пути. |

## События

| Имя | Описание |
| --- | --- |
| event [Disposed](../../groupdocs.editor/editabledocument/disposed) | Событие, возникающее при удалении этого редактируемого документа сразу после завершения процесса удаления |

### Примечания

Экземпляр класса EditableDocument может быть создан '[`Edit`](../editor/edit) метод или созданный самим пользователем с использованием статических фабрик. EditableDocument внутренне хранит документ в собственном закрытом формате, который совместим (конвертируемый) со всеми форматами импорта и экспорта, которые поддерживает GroupDocs.Editor. Чтобы сделать документ редактируемым в любом клиентском редакторе WYSIWYG (например, CKEditor или TinyMCE), EditableDocument предоставляет методы для создания HTML-разметки и создания ресурсов, которые могут быть приняты пользователем.

### Смотрите также

* interface [IAuxDisposable](../../groupdocs.editor.htmlcss.resources/iauxdisposable)
* пространство имен [GroupDocs.Editor](../../groupdocs.editor)
* сборка [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
