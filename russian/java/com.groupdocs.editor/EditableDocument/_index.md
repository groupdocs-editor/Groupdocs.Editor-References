---
title: "EditableDocument"
second_title: "GroupDocs.Editor for Java API Справка"
description: "Промежуточный документ, содержащий содержимое до и после редактирования"
type: docs
weight: 10
url: /ru/java/com.groupdocs.editor/editabledocument/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.IAuxDisposable](../../com.groupdocs.editor.htmlcss.resources/iauxdisposable)
```
public final class EditableDocument implements IAuxDisposable
```

Промежуточный документ, содержащий содержимое до и после редактирования


*** ** * ** ***

Экземпляр класса EditableDocument может быть получен с помощью метода Editor.edit() или создан пользователем самостоятельно с использованием статических фабрик. EditableDocument внутри хранит документ в собственном закрытом формате, совместимом (конвертируемом) со всеми форматами импорта и экспорта, поддерживаемыми GroupDocs.Editor. Чтобы сделать документ редактируемым в любом WYSIWYG клиентском редакторе (например, CKEditor или TinyMCE), EditableDocument предоставляет методы для генерации HTML‑разметки и создания ресурсов, которые могут быть приняты пользователем.

<br />


## Поля

| Поле | Описание |
| --- | --- |
| [Disposed](#Disposed) |  |
## Методы

| Метод | Описание |
| --- | --- |
|  | [getImages()](#getImages--) | Позволяет получать внешние ресурсы изображений (растровые изображения), которые используются |
по этому HTML документу
|
|  | [getFonts()](#getFonts--) | Позволяет получать внешние ресурсы шрифтов, которые используются этим HTML |
документа
|
|  | [getCss()](#getCss--) | Возвращает список ресурсов CSS |
|
|  | [getAudio()](#getAudio--) | Возвращает список аудиоресурсов |
|
|  | [getAllResources()](#getAllResources--) | Возвращает список всех существующих ресурсов: все таблицы стилей, изображения из |
HTML и все таблицы стилей, шрифты
|
|  | [getContent(OutputStream storage, Charset encoding)](#getContent-java.io.OutputStream-java.nio.charset.Charset-) | Возвращает полное содержимое HTML‑документа в виде байтового потока, записывая это содержимое в указанный поток с указанной кодировкой текста |
|
|  | [getBodyContent()](#getBodyContent--) | Возвращает тело HTML‑документа (содержимое между открывающим и закрывающим |
тегами BODY без этих тегов) в виде строки.
|
|  | [getBodyContent(String externalImagesTemplate)](#getBodyContent-java.lang.String-) | Возвращает тело HTML‑документа (содержимое между открывающим и закрывающим |
тегами BODY без этих тегов) в виде строки, где ссылки на внешние
ресурсы содержат указанный префикс.
|
|  | [getContent()](#getContent--) | Возвращает полное содержимое HTML‑документа в виде строки. |
|
|  | [getContentString(String externalImagesTemplate, String externalCssTemplate)](#getContentString-java.lang.String-java.lang.String-) | Возвращает полное содержимое HTML‑документа в виде строки, где ссылки на |
внешние ресурсы содержат указанный префикс.
|
|  | [getCssContent()](#getCssContent--) | Возвращает содержимое всех внешних таблиц стилей в виде списка строк, где |
одна строка представляет одну таблицу стилей.
|
|  | [getCssContent(String externalImagesPrefix, String externalFontsPrefix)](#getCssContent-java.lang.String-java.lang.String-) | Возвращает содержимое всех внешних таблиц стилей в виде списка строк, где |
одна строка представляет одну таблицу стилей.
|
|  | [getEmbeddedHtml()](#getEmbeddedHtml--) | Возвращает всё содержимое этого HTML‑документа со всеми связанными ресурсами в |
в виде единой строки, где все ресурсы встроены в HTML
разметку в виде base64‑закодированного формата.
|
|  | [save(String htmlFilePath)](#save-java.lang.String-) | Сохраняет этот HTML‑документ в файл по указанному пути, где HTML‑разметка |
будет сохранена, а также в сопутствующую папку с ресурсами.
|
|  | [save(String htmlFilePath, String resourcesFolderPath)](#save-java.lang.String-java.lang.String-) | Сохраняет этот HTML‑документ в файл по указанному пути, где HTML‑разметка |
будет сохранена, а также в сопутствующую папку с ресурсами, которая
расположена по указанному пути.
|
| [save(Writer htmlMarkup, HtmlSaveOptions saveOptions)](#save-java.io.Writer-com.groupdocs.editor.options.HtmlSaveOptions-) |  |
|  | [fromMarkup(String newHtmlContent, List<IHtmlResource> resources)](#fromMarkup-java.lang.String-java.util.List-com.groupdocs.editor.htmlcss.resources.IHtmlResource--) | Статическая фабрика, создающая экземпляр EditableDocument из |
указанной HTML‑разметки и набора соответствующих связанных ресурсов
|
|  | [fromMarkupAndResourceFolder(String newHtmlContent, String resourceFolderPath)](#fromMarkupAndResourceFolder-java.lang.String-java.lang.String-) | Статическая фабрика, создающая экземпляр EditableDocument из указанной разметки HTML и из ресурсов, расположенных в папке, указанной полным путём |
|
|  | [fromFile(String htmlFilePath, String resourceFolderPath)](#fromFile-java.lang.String-java.lang.String-) | Статическая фабрика, создающая экземпляр EditableDocument из HTML |
файл, указанный путем к самому файлу \*.html и папке
с связанными ресурсами
|
|  | [dispose()](#dispose--) | Освобождает этот экземпляр EditableDocument, освобождая его содержимое и |
делая его методы и свойства неработоспособными
|
|  | [isDisposed()](#isDisposed--) | Определяет, был ли этот EditableDocument уже освобождён (true) или |
нет (false)
|
### Disposed {#Disposed}
```
public final Event<EventHandler> Disposed
```


### getImages() {#getImages--}
```
public final List<IImageResource> getImages()
```


Позволяет получать внешние ресурсы изображений (растровые изображения), которые используются
по этому HTML документу


**Returns:**
java.util.List<com.groupdocs.editor.htmlcss.resources.images.IImageResource>
### getFonts() {#getFonts--}
```
public final List<FontResourceBase> getFonts()
```


Позволяет получать внешние ресурсы шрифтов, которые используются этим HTML
документа


**Returns:**
java.util.List<com.groupdocs.editor.htmlcss.resources.fonts.FontResourceBase>
### getCss() {#getCss--}
```
public final List<CssText> getCss()
```


Возвращает список ресурсов CSS


**Returns:**
java.util.List<com.groupdocs.editor.htmlcss.resources.textual.CssText>
### getAudio() {#getAudio--}
```
public final List<Mp3Audio> getAudio()
```


Возвращает список аудиоресурсов


**Returns:**
java.util.List<com.groupdocs.editor.htmlcss.resources.audio.Mp3Audio>
### getAllResources() {#getAllResources--}
```
public final List<IHtmlResource> getAllResources()
```


Возвращает список всех существующих ресурсов: все таблицы стилей, изображения из
HTML и все таблицы стилей, шрифты


*** ** * ** ***

Это свойство возвращает конкатенированный результат свойств 'Images', 'Fonts' и 'Css'

<br />



**Returns:**
java.util.List<com.groupdocs.editor.htmlcss.resources.IHtmlResource>
### getContent(OutputStream storage, Charset encoding) {#getContent-java.io.OutputStream-java.nio.charset.Charset-}
```
public OutputStream getContent(OutputStream storage, Charset encoding)
```


Возвращает полное содержимое HTML‑документа в виде байтового потока, записывая это содержимое в указанный поток с указанной кодировкой текста


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | хранилище | java.io.OutputStream | Ненулевой поток байтов, поддерживающий запись |
|
|  | кодировка | java.nio.charset.Charset | Ненулевое текстовое кодирование, которое должно применяться при записи текстового содержимого в указанное хранилище |


TStream
: Любая реализация java.io.InputStream
|

**Returns:**
java.io.OutputStream - Экземпляр указанного хранилища

### getBodyContent() {#getBodyContent--}
```
public final String getBodyContent()
```


Возвращает тело HTML‑документа (содержимое между открывающим и закрывающим
тегами BODY без этих тегов) в виде строки.


**Returns:**
java.lang.String - Строка, содержащая тело HTML‑документа


*** ** * ** ***

WYSIWYG‑редакторы работают с телом документа и не могут корректно обрабатывать его мета‑информацию из блока HEAD. Этот метод предназначен для таких случаев. Эта перегрузка не позволяет настраивать URI для запросов внешних ресурсов.

<br />


### getBodyContent(String externalImagesTemplate) {#getBodyContent-java.lang.String-}
```
public final String getBodyContent(String externalImagesTemplate)
```


Возвращает тело HTML‑документа (содержимое между открывающим и закрывающим
тегами BODY без этих тегов) в виде строки, где ссылки на внешние
ресурсы содержат указанный префикс.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | externalImagesTemplate | java.lang.String | С помощью этого параметра можно указать префикс, который будет добавлен к ссылкам на все внешние изображения в элементах IMG, присутствующих в результирующей строке HTML. Если NULL или пустой, префиксы добавляться не будут. |


*** ** * ** ***

WYSIWYG‑редакторы работают с телом документа и не могут корректно обрабатывать его мета‑информацию из блока HEAD. Этот метод предназначен для таких случаев. Эта перегрузка позволяет настраивать URI для запросов внешних ресурсов.

<br />

|

**Returns:**
java.lang.String - String, который содержит тело HTML‑документа со ссылками, адаптированными к внешним изображениям

### getContent() {#getContent--}
```
public String getContent()
```


Возвращает полное содержимое HTML‑документа в виде строки.


**Returns:**
java.lang.String - String, который содержит содержимое HTML‑документа

### getContentString(String externalImagesTemplate, String externalCssTemplate) {#getContentString-java.lang.String-java.lang.String-}
```
public String getContentString(String externalImagesTemplate, String externalCssTemplate)
```


Возвращает полное содержимое HTML‑документа в виде строки, где ссылки на
внешние ресурсы содержат указанный префикс.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | externalImagesTemplate | java.lang.String | С помощью этого параметра можно указать префикс, который будет добавлен к ссылкам на все внешние изображения в элементах IMG, присутствующих в результирующей строке HTML. Если NULL или пустой, префиксы добавляться не будут. |
|
|  | externalCssTemplate | java.lang.String | С помощью этого параметра можно указать префикс, который будет добавлен к ссылкам на все внешние таблицы стилей в элементах LINK, присутствующих в результирующей строке HTML. Если значение NULL или пустое, префиксы добавляться не будут. |
|

**Returns:**
java.lang.String - String, который содержит содержимое HTML‑документа со ссылками, адаптированными к внешним ресурсам

### getCssContent() {#getCssContent--}
```
public final List<String> getCssContent()
```


Возвращает содержимое всех внешних таблиц стилей в виде списка строк, где
одна строка представляет одну таблицу стилей. Возвращает пустой список, если нет
CSS для этого документа.


**Returns:**
java.util.List<java.lang.String> - Список строк, где каждая строка содержит содержимое одного CSS‑документа

### getCssContent(String externalImagesPrefix, String externalFontsPrefix) {#getCssContent-java.lang.String-java.lang.String-}
```
public final List<String> getCssContent(String externalImagesPrefix, String externalFontsPrefix)
```


Возвращает содержимое всех внешних таблиц стилей в виде списка строк, где
одна строка представляет одну таблицу стилей. Указанный префикс будет применён к
каждой ссылке на внешний ресурс в каждой результирующей таблице стилей.
Возвращает пустой список, если для этого документа нет CSS.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | externalImagesPrefix | java.lang.String | С помощью этого параметра можно указать префикс, который будет добавлен к ссылкам на все внешние изображения, присутствующие в CSS‑объявлениях в результирующих строках CSS. Если значение NULL или пустое, префиксы добавляться не будут. |
|
|  | externalFontsPrefix | java.lang.String | С помощью этого параметра можно указать префикс, который будет добавлен к ссылкам на все внешние шрифты в |
|

**Returns:**
java.util.List<java.lang.String> - Список строк, где каждая строка содержит содержимое одного CSS‑документа

### getEmbeddedHtml() {#getEmbeddedHtml--}
```
public final String getEmbeddedHtml()
```


Возвращает всё содержимое этого HTML‑документа со всеми связанными ресурсами в
в виде единой строки, где все ресурсы встроены в HTML
разметку в виде base64‑закодированного формата.


**Returns:**
java.lang.String - String, который в любом случае не является NULL или пустым

### save(String htmlFilePath) {#save-java.lang.String-}
```
public final void save(String htmlFilePath)
```


Сохраняет этот HTML‑документ в файл по указанному пути, где HTML‑разметка
будет сохранена, а также в сопутствующую папку с ресурсами.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | htmlFilePath | java.lang.String | Полный путь к файлу, в котором будет сохранён HTML‑разметка. Файл будет создан или перезаписан, если существует. Сопутствующая папка ресурсов будет создана в той же папке, где находится HTML‑файл. |
|

### save(String htmlFilePath, String resourcesFolderPath) {#save-java.lang.String-java.lang.String-}
```
public final void save(String htmlFilePath, String resourcesFolderPath)
```


Сохраняет этот HTML‑документ в файл по указанному пути, где HTML‑разметка
будет сохранена, а также в сопутствующую папку с ресурсами, которая
расположена по указанному пути.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | htmlFilePath | java.lang.String | Полный путь к файлу, в котором будет сохранён HTML‑разметка. Не может быть NULL или пустым. Файл будет создан или перезаписан, если существует. |
|
|  | resourcesFolderPath | java.lang.String | Полный путь к сопутствующей папке, где будут храниться все связанные ресурсы. Если значение NULL или пустое, папка будет создана автоматически в том же каталоге, где находится файл \\*.html. Если указано и папка не существует, она будет создана. |
|

### save(Writer htmlMarkup, HtmlSaveOptions saveOptions) {#save-java.io.Writer-com.groupdocs.editor.options.HtmlSaveOptions-}
```
public void save(Writer htmlMarkup, HtmlSaveOptions saveOptions)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| htmlMarkup | java.io.Writer |  |
| saveOptions | [HtmlSaveOptions](../../com.groupdocs.editor.options/htmlsaveoptions) |  |

### fromMarkup(String newHtmlContent, List<IHtmlResource> resources) {#fromMarkup-java.lang.String-java.util.List-com.groupdocs.editor.htmlcss.resources.IHtmlResource--}
```
public static EditableDocument fromMarkup(String newHtmlContent, List<IHtmlResource> resources)
```


Статическая фабрика, создающая экземпляр EditableDocument из
указанной HTML‑разметки и набора соответствующих связанных ресурсов


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | newHtmlContent | java.lang.String | String, содержащий необработанную HTML‑разметку, которую необходимо разобрать. Не может быть NULL, пустым или недействительным. |
|
|  | ресурсы | java.util.List<com.groupdocs.editor.htmlcss.resources.IHtmlResource> | Коллекция всех ресурсов (изображения, таблицы стилей, шрифты), используемых в HTML‑документе, указанном в параметре  newHtmlContent . Может отсутствовать (NULL или пустая коллекция). |
|

**Returns:**
[EditableDocument](../../com.groupdocs.editor/editabledocument) - New non-null instance of EditableDocument

### fromMarkupAndResourceFolder(String newHtmlContent, String resourceFolderPath) {#fromMarkupAndResourceFolder-java.lang.String-java.lang.String-}
```
public static EditableDocument fromMarkupAndResourceFolder(String newHtmlContent, String resourceFolderPath)
```


Статическая фабрика, создающая экземпляр EditableDocument из указанной разметки HTML и из ресурсов, расположенных в папке, указанной полным путём


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | newHtmlContent | java.lang.String | String, содержащий необработанную HTML‑разметку, которую необходимо разобрать. Не может быть NULL, пустым или недействительным. |
|
|  | resourceFolderPath | java.lang.String | Обязательный путь к папке с ресурсами. Все таблицы стилей, находящиеся в этой папке, будут использованы. Не может быть NULL или пустой строкой, и эта папка должна существовать. |

<br />

*** ** * ** ***

Эта статическая фабрика полезна, когда содержимое HTML‑документа представлено в виде строки, но все ресурсы находятся в какой‑то папке, и часто ссылки на эти ресурсы в разметке HTML являются недействительными или отсутствуют. При вызове этого метода он сканирует указанную папку и автоматически применяет все найденные таблицы стилей к документу. Этот метод очень полезен при получении содержимого из различных HTML‑редакторов, которые обычно отрезают метаданные документа и т.п.

<br />

|

**Returns:**
[EditableDocument](../../com.groupdocs.editor/editabledocument) - New non-null instance of EditableDocument

### fromFile(String htmlFilePath, String resourceFolderPath) {#fromFile-java.lang.String-java.lang.String-}
```
public static EditableDocument fromFile(String htmlFilePath, String resourceFolderPath)
```


Статическая фабрика, создающая экземпляр EditableDocument из HTML
файл, указанный путем к самому файлу \*.html и папке
с связанными ресурсами


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | htmlFilePath | java.lang.String | Строка, содержащая полный путь к HTML‑файлу. Не может быть null, должна быть корректным путём к файлу, и сам файл должен существовать. |
|
|  | resourceFolderPath | java.lang.String | Необязательный путь к папке с HTML‑ресурсами. Если NULL, недействителен или такая папка не существует, редактор попытается найти эту папку самостоятельно, анализируя разметку HTML. |
|

**Returns:**
[EditableDocument](../../com.groupdocs.editor/editabledocument) - New non-null instance of EditableDocument

### dispose() {#dispose--}
```
public final void dispose()
```


Освобождает этот экземпляр EditableDocument, освобождая его содержимое и
делая его методы и свойства неработоспособными


### isDisposed() {#isDisposed--}
```
public final boolean isDisposed()
```


Определяет, был ли этот EditableDocument уже освобождён (true) или
нет (false)


**Returns:**
boolean
