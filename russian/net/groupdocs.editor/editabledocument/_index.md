---
title: "EditableDocument"
second_title: "GroupDocs.Editor для .NET справочник API"
description: "Промежуточный документ, содержащий контент до и после редактирования"
type: docs
weight: 10
url: /ru/net/groupdocs.editor/editabledocument/
---
## EditableDocument class

Промежуточный документ, содержащий содержимое до и после редактирования

```csharp
public sealed class EditableDocument : IAuxDisposable
```

## Свойства

| Имя | Описание |
| --- | --- |
| [AllResources](../../groupdocs.editor/editabledocument/allresources) { get; } | Возвращает список всех существующих ресурсов: все таблицы стилей, изображения из HTML и все таблицы стилей, шрифты, аудио |
| [Audio](../../groupdocs.editor/editabledocument/audio) { get; } | Возвращает список аудио ресурсов |
| [Css](../../groupdocs.editor/editabledocument/css) { get; } | Позволяет получить ресурсы таблиц стилей (CSS) (как внешние, так и встроенные, но не inline), которые используются этим HTML‑документом |
| [Fonts](../../groupdocs.editor/editabledocument/fonts) { get; } | Позволяет получить внешние ресурсы шрифтов, которые используются этим HTML‑документом |
| [Images](../../groupdocs.editor/editabledocument/images) { get; } | Позволяет получить внешние ресурсы изображений (растровые и векторные), которые используются этим HTML‑документом |
| [IsDisposed](../../groupdocs.editor/editabledocument/isdisposed) { get; } | Определяет, был ли этот Editable документ уже удалён (true) или нет (false) |

## Методы

| Имя | Описание |
| --- | --- |
| static [FromFile](../../groupdocs.editor/editabledocument/fromfile)(string, string) | Статическая фабрика, создающая экземпляр EditableDocument из HTML‑файла, указанный путем к самому файлу *.html и папкой со связанными ресурсами |
| static [FromMarkup](../../groupdocs.editor/editabledocument/frommarkup#frommarkup)(string) | Статическая фабрика, создающая экземпляр [`EditableDocument`](../editabledocument) из указанной разметки HTML |
| static [FromMarkup](../../groupdocs.editor/editabledocument/frommarkup#frommarkup_1)(string, IEnumerable&lt;IHtmlResource&gt;) | Статическая фабрика, создающая экземпляр EditableDocument из указанной разметки HTML и набора соответствующих связанных ресурсов |
| static [FromMarkupAndResourceFolder](../../groupdocs.editor/editabledocument/frommarkupandresourcefolder)(string, string) | Статическая фабрика, создающая экземпляр EditableDocument из указанной разметки HTML и из ресурсов, расположенных в папке, указанной полным путём |
| [Dispose](../../groupdocs.editor/editabledocument/dispose)() | Удаляет экземпляр этого Editable документа, удаляя его содержимое и делая методы и свойства неработоспособными |
| [GetBodyContent](../../groupdocs.editor/editabledocument/getbodycontent#getbodycontent)() | Возвращает тело HTML‑документа (внутреннее содержимое между открывающим и закрывающим тегами BODY без самих тегов) в виде строки. |
| [GetBodyContent](../../groupdocs.editor/editabledocument/getbodycontent#getbodycontent_1)(string) | Возвращает тело HTML‑документа (внутреннее содержимое между открывающим и закрывающим тегами BODY без самих тегов) в виде строки, где ссылки на внешние ресурсы содержат указанный шаблон с заполнителями. |
| [GetContent](../../groupdocs.editor/editabledocument/getcontent#getcontent)() | Возвращает полное содержимое HTML‑документа в виде строки. |
| [GetContent](../../groupdocs.editor/editabledocument/getcontent#getcontent_1)(string, string) | Возвращает полное содержимое HTML‑документа в виде строки, где ссылки на внешние ресурсы содержат указанный шаблон с заполнителями. |
| [GetContent&lt;TStream&gt;](../../groupdocs.editor/editabledocument/getcontent#getcontent_2)(TStream, Encoding) | Возвращает полное содержимое HTML‑документа в виде байтового потока, записывая это содержимое в указанный поток с заданной кодировкой текста |
| [GetCssContent](../../groupdocs.editor/editabledocument/getcsscontent#getcsscontent)() | Возвращает содержимое всех внешних таблиц стилей в виде списка строк, где каждая строка представляет одну таблицу стилей. Возвращает пустой список, если для этого документа нет CSS. |
| [GetCssContent](../../groupdocs.editor/editabledocument/getcsscontent#getcsscontent_1)(string, string) | Возвращает содержимое всех внешних таблиц стилей в виде списка строк, где каждая строка представляет одну таблицу стилей. Указанный префикс будет применён к каждой ссылке на внешний ресурс в каждой полученной таблице стилей. Возвращает пустой список, если для этого документа нет CSS. |
| [GetEmbeddedHtml](../../groupdocs.editor/editabledocument/getembeddedhtml)() | Возвращает всё содержимое этого HTML‑документа со всеми связанными ресурсами в виде единой строки, где все ресурсы встроены в разметку HTML в виде base64‑закодированных данных. |
| [Save](../../groupdocs.editor/editabledocument/save#save_1)(string) | Сохраняет этот HTML‑документ в файл по указанному пути, где будет храниться разметка HTML, и в сопутствующую папку с ресурсами. |
| [Save](../../groupdocs.editor/editabledocument/save#save_2)(string, string) | Сохраняет этот HTML‑документ в файл по указанному пути, где будет храниться разметка HTML, и в сопутствующую папку с ресурсами, расположенную по указанному пути. |
| [Save](../../groupdocs.editor/editabledocument/save#save)(TextWriter, HtmlSaveOptions) | Сохраняет содержимое этого [`EditableDocument`](../editabledocument) как HTML‑документ в указанный текстовый писатель, при этом второй параметр options позволяет настроить процесс сохранения и указать обратный вызов сохранения ресурсов |

## События

| Имя | Описание |
| --- | --- |
| event [Disposed](../../groupdocs.editor/editabledocument/disposed) | Событие, которое происходит, когда этот Editable документ освобождается, сразу после завершения процесса освобождения. |

### Замечания

Экземпляр класса `EditableDocument` может быть создан с помощью метода '[`Edit`](../editor/edit)' или пользователем вручную с использованием статических фабрик. `EditableDocument` внутренне хранит документ в собственном закрытом формате, который совместим (преобразуем) со всеми форматами импорта и экспорта, поддерживаемыми GroupDocs.Editor. Чтобы сделать документ редактируемым в любом клиентском WYSIWYG‑редакторе (например, CKEditor или TinyMCE), `EditableDocument` предоставляет методы для генерации HTML‑разметки и создания ресурсов, которые могут быть приняты пользователем.

### См. также

* interface [IAuxDisposable](../../groupdocs.editor.htmlcss.resources/iauxdisposable)
* namespace [GroupDocs.Editor](../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.editor.dll -->
