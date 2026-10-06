---
title: "EditableDocument"
second_title: "GroupDocs.Editor für Java API-Referenz"
description: "Zwischendokument, das Inhalte vor und nach der Bearbeitung enthält"
type: docs
weight: 10
url: /de/java/com.groupdocs.editor/editabledocument/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.IAuxDisposable](../../com.groupdocs.editor.htmlcss.resources/iauxdisposable)
```
public final class EditableDocument implements IAuxDisposable
```

Zwischendokument, das Inhalte vor und nach der Bearbeitung enthält.


*** ** * ** ***

Eine Instanz der Klasse EditableDocument kann durch die Methode Editor.edit() erzeugt oder vom Benutzer selbst mithilfe statischer Fabriken erstellt werden. EditableDocument speichert das Dokument intern in einem eigenen geschlossenen Format, das mit allen Import‑ und Exportformaten, die GroupDocs.Editor unterstützt, kompatibel (konvertierbar) ist. Um das Dokument in jedem clientseitigen WYSIWYG‑Editor (wie CKEditor oder TinyMCE) editierbar zu machen, stellt EditableDocument Methoden zum Erzeugen von HTML‑Markup und zum Erzeugen von Ressourcen bereit, die vom Benutzer akzeptiert werden können.

<br />


## Felder

| Feld | Beschreibung |
| --- | --- |
| [Disposed](#Disposed) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getImages()](#getImages--) | Ermöglicht das Abrufen externer Bildressourcen (Rasterbilder), die verwendet werden |
von diesem HTML-Dokument
|
|  | [getFonts()](#getFonts--) | Ermöglicht das Abrufen externer Schriftressourcen, die von diesem HTML verwendet werden |
Dokument
|
|  | [getCss()](#getCss--) | Gibt eine Liste von CSS‑Ressourcen zurück |
|
|  | [getAudio()](#getAudio--) | Gibt eine Liste von Audio‑Ressourcen zurück |
|
|  | [getAllResources()](#getAllResources--) | Gibt eine Liste aller vorhandenen Ressourcen zurück: alle Stylesheets, Bilder von |
HTML und allen Stylesheets, Schriften
|
|  | [getContent(OutputStream storage, Charset encoding)](#getContent-java.io.OutputStream-java.nio.charset.Charset-) | Gibt den gesamten Inhalt des HTML-Dokuments als Bytestrom zurück, indem dieser Inhalt in den angegebenen Stream mit der angegebenen Textkodierung geschrieben wird |
|
|  | [getBodyContent()](#getBodyContent--) | Gibt den Body des HTML-Dokuments zurück (Inhalt zwischen öffnenden und schließenden |
BODY‑Tags ohne diese Tags) als Zeichenkette.
|
|  | [getBodyContent(String externalImagesTemplate)](#getBodyContent-java.lang.String-) | Gibt den Body des HTML-Dokuments zurück (Inhalt zwischen öffnenden und schließenden |
BODY‑Tags ohne diese Tags) als Zeichenkette, wobei Links zu den externen
Ressourcen das angegebene Präfix enthalten.
|
|  | [getContent()](#getContent--) | Gibt den gesamten Inhalt des HTML-Dokuments als Zeichenkette zurück. |
|
|  | [getContentString(String externalImagesTemplate, String externalCssTemplate)](#getContentString-java.lang.String-java.lang.String-) | Gibt den gesamten Inhalt des HTML-Dokuments als Zeichenkette zurück, wobei Links zu |
den externen Ressourcen das angegebene Präfix enthalten.
|
|  | [getCssContent()](#getCssContent--) | Gibt den Inhalt aller externen Stylesheets als Liste von Zeichenketten zurück, wobei |
eine Zeichenkette ein Stylesheet darstellt.
|
|  | [getCssContent(String externalImagesPrefix, String externalFontsPrefix)](#getCssContent-java.lang.String-java.lang.String-) | Gibt den Inhalt aller externen Stylesheets als Liste von Zeichenketten zurück, wobei |
eine Zeichenkette ein Stylesheet darstellt.
|
|  | [getEmbeddedHtml()](#getEmbeddedHtml--) | Gibt den gesamten Inhalt dieses HTML-Dokuments mit allen zugehörigen Ressourcen in einer |
Form einer einzelnen Zeichenkette zurück, wobei alle Ressourcen im HTML eingebettet sind
Markup in einer base64-codierten Form.
|
|  | [save(String htmlFilePath)](#save-java.lang.String-) | Speichert dieses HTML-Dokument in die Datei am angegebenen Pfad, wo das HTML-Markup |
gespeichert wird, und in den zugehörigen Ordner mit Ressourcen.
|
|  | [save(String htmlFilePath, String resourcesFolderPath)](#save-java.lang.String-java.lang.String-) | Speichert dieses HTML-Dokument in die Datei am angegebenen Pfad, wo das HTML-Markup |
gespeichert wird, und in den zugehörigen Ordner mit Ressourcen, welcher
am angegebenen Pfad liegt.
|
| [save(Writer htmlMarkup, HtmlSaveOptions saveOptions)](#save-java.io.Writer-com.groupdocs.editor.options.HtmlSaveOptions-) |  |
|  | [fromMarkup(String newHtmlContent, List<IHtmlResource> resources)](#fromMarkup-java.lang.String-java.util.List-com.groupdocs.editor.htmlcss.resources.IHtmlResource--) | Statische Fabrik, die eine Instanz von EditableDocument erstellt aus |
spezifiziertem HTML-Markup und einem Satz entsprechender verknüpfter Ressourcen
|
|  | [fromMarkupAndResourceFolder(String newHtmlContent, String resourceFolderPath)](#fromMarkupAndResourceFolder-java.lang.String-java.lang.String-) | Statische Fabrik, die eine Instanz von EditableDocument aus einem angegebenen HTML-Markup und aus Ressourcen erstellt, die im Ordner liegen, der durch den vollständigen Pfad angegeben ist |
|
|  | [fromFile(String htmlFilePath, String resourceFolderPath)](#fromFile-java.lang.String-java.lang.String-) | Statische Fabrik, die eine Instanz von EditableDocument aus einem HTML |
Datei, die durch einen Pfad zur \*.html-Datei selbst und einen Ordner angegeben ist
mit verknüpften Ressourcen
|
|  | [dispose()](#dispose--) | Entsorgt diese Editable-Dokument-Instanz, wobei ihr Inhalt entsorgt wird und |
wodurch ihre Methoden und Eigenschaften nicht mehr funktionieren
|
|  | [isDisposed()](#isDisposed--) | Bestimmt, ob dieses Editable-Dokument bereits entsorgt wurde (true) oder |
nicht (false)
|
### Disposed {#Disposed}
```
public final Event<EventHandler> Disposed
```


### getImages() {#getImages--}
```
public final List<IImageResource> getImages()
```


Ermöglicht das Abrufen externer Bildressourcen (Rasterbilder), die verwendet werden
von diesem HTML-Dokument


**Returns:**
java.util.List<com.groupdocs.editor.htmlcss.resources.images.IImageResource>
### getFonts() {#getFonts--}
```
public final List<FontResourceBase> getFonts()
```


Ermöglicht das Abrufen externer Schriftressourcen, die von diesem HTML verwendet werden
Dokument


**Returns:**
java.util.List<com.groupdocs.editor.htmlcss.resources.fonts.FontResourceBase>
### getCss() {#getCss--}
```
public final List<CssText> getCss()
```


Gibt eine Liste von CSS‑Ressourcen zurück


**Returns:**
java.util.List<com.groupdocs.editor.htmlcss.resources.textual.CssText>
### getAudio() {#getAudio--}
```
public final List<Mp3Audio> getAudio()
```


Gibt eine Liste von Audio‑Ressourcen zurück


**Returns:**
java.util.List<com.groupdocs.editor.htmlcss.resources.audio.Mp3Audio>
### getAllResources() {#getAllResources--}
```
public final List<IHtmlResource> getAllResources()
```


Gibt eine Liste aller vorhandenen Ressourcen zurück: alle Stylesheets, Bilder von
HTML und allen Stylesheets, Schriften


*** ** * ** ***

Diese Eigenschaft gibt ein zusammengefügtes Ergebnis der Eigenschaften 'Images', 'Fonts' und 'Css' zurück

<br />



**Returns:**
java.util.List<com.groupdocs.editor.htmlcss.resources.IHtmlResource>
### getContent(OutputStream storage, Charset encoding) {#getContent-java.io.OutputStream-java.nio.charset.Charset-}
```
public OutputStream getContent(OutputStream storage, Charset encoding)
```


Gibt den gesamten Inhalt des HTML-Dokuments als Bytestrom zurück, indem dieser Inhalt in den angegebenen Stream mit der angegebenen Textkodierung geschrieben wird


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Speicher | java.io.OutputStream | Nicht-null Byte-Stream, der Schreiben unterstützt |
|
|  | Kodierung | java.nio.charset.Charset | Nicht-null Textkodierung, die beim Schreiben von Textinhalt in den angegebenen Speicher angewendet werden sollte |


TStream
: Jede Implementierung des java.io.InputStream
|

**Returns:**
java.io.OutputStream - Instanz des angegebenen Speichers

### getBodyContent() {#getBodyContent--}
```
public final String getBodyContent()
```


Gibt den Body des HTML-Dokuments zurück (Inhalt zwischen öffnenden und schließenden
BODY‑Tags ohne diese Tags) als Zeichenkette.


**Returns:**
java.lang.String - Zeichenkette, die den Body des HTML-Dokuments enthält


*** ** * ** ***

WYSIWYG-Editoren arbeiten mit dem Body des Dokuments und können dessen Metainformationen aus dem HEAD-Block nicht korrekt verarbeiten. Diese Methode ist für solche Fälle vorgesehen. Diese Überladung erlaubt es nicht, URIs für externe Ressourcenanfragen anzupassen.

<br />


### getBodyContent(String externalImagesTemplate) {#getBodyContent-java.lang.String-}
```
public final String getBodyContent(String externalImagesTemplate)
```


Gibt den Body des HTML-Dokuments zurück (Inhalt zwischen öffnenden und schließenden
BODY‑Tags ohne diese Tags) als Zeichenkette, wobei Links zu den externen
Ressourcen das angegebene Präfix enthalten.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | externalImagesTemplate | java.lang.String | Über diesen Parameter kann ein Präfix angegeben werden, das zu den Links aller externen Bilder in IMG-Elementen hinzugefügt wird, die im resultierenden HTML-String vorkommen. Wenn NULL oder leer, werden keine Präfixe hinzugefügt. |


*** ** * ** ***

WYSIWYG-Editoren arbeiten mit dem Body des Dokuments und können dessen Metainformationen aus dem HEAD-Block nicht korrekt verarbeiten. Diese Methode ist für solche Fälle vorgesehen. Diese Überladung ermöglicht es, URIs für externe Ressourcenanfragen anzupassen.

<br />

|

**Returns:**
java.lang.String - Zeichenkette, die den Body des HTML-Dokuments mit Links enthält, angepasst an die externen Bilder

### getContent() {#getContent--}
```
public String getContent()
```


Gibt den gesamten Inhalt des HTML-Dokuments als Zeichenkette zurück.


**Returns:**
java.lang.String - Zeichenkette, die den Inhalt des HTML-Dokuments enthält

### getContentString(String externalImagesTemplate, String externalCssTemplate) {#getContentString-java.lang.String-java.lang.String-}
```
public String getContentString(String externalImagesTemplate, String externalCssTemplate)
```


Gibt den gesamten Inhalt des HTML-Dokuments als Zeichenkette zurück, wobei Links zu
den externen Ressourcen das angegebene Präfix enthalten.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | externalImagesTemplate | java.lang.String | Über diesen Parameter kann ein Präfix angegeben werden, das zu den Links aller externen Bilder in IMG-Elementen hinzugefügt wird, die im resultierenden HTML-String vorkommen. Wenn NULL oder leer, werden keine Präfixe hinzugefügt. |
|
|  | externalCssTemplate | java.lang.String | Über diesen Parameter kann ein Präfix angegeben werden, das zu den Links aller externen Stylesheets in LINK-Elementen hinzugefügt wird, die im resultierenden HTML-String vorkommen. Wenn NULL oder leer, werden keine Präfixe hinzugefügt. |
|

**Returns:**
java.lang.String - Zeichenkette, die den Inhalt des HTML-Dokuments mit Links enthält, angepasst an die externen Ressourcen

### getCssContent() {#getCssContent--}
```
public final List<String> getCssContent()
```


Gibt den Inhalt aller externen Stylesheets als Liste von Zeichenketten zurück, wobei
Eine Zeichenkette repräsentiert ein Stylesheet. Gibt eine leere Liste zurück, wenn es kein
CSS für dieses Dokument.


**Returns:**
java.util.List<java.lang.String> - Eine Liste von Zeichenketten, wobei jede Zeichenkette den Inhalt eines CSS-Dokuments enthält

### getCssContent(String externalImagesPrefix, String externalFontsPrefix) {#getCssContent-java.lang.String-java.lang.String-}
```
public final List<String> getCssContent(String externalImagesPrefix, String externalFontsPrefix)
```


Gibt den Inhalt aller externen Stylesheets als Liste von Zeichenketten zurück, wobei
Eine Zeichenkette repräsentiert ein Stylesheet. Das angegebene Präfix wird angewendet auf
jeden Link zur externen Ressource in jedem resultierenden Stylesheet.
Gibt eine leere Liste zurück, wenn kein CSS für dieses Dokument vorhanden ist.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | externalImagesPrefix | java.lang.String | Über diesen Parameter kann ein Präfix angegeben werden, das zu den Links aller externen Bilder hinzugefügt wird, die in CSS-Deklarationen in den resultierenden CSS-Strings vorkommen. Wenn NULL oder leer, werden keine Präfixe hinzugefügt. |
|
|  | externalFontsPrefix | java.lang.String | Über diesen Parameter kann ein Präfix angegeben werden, das zu den Links aller externen Schriftarten in dem |
|

**Returns:**
java.util.List<java.lang.String> - Eine Liste von Zeichenketten, wobei jede Zeichenkette den Inhalt eines CSS-Dokuments enthält

### getEmbeddedHtml() {#getEmbeddedHtml--}
```
public final String getEmbeddedHtml()
```


Gibt den gesamten Inhalt dieses HTML-Dokuments mit allen zugehörigen Ressourcen in einer
Form einer einzelnen Zeichenkette zurück, wobei alle Ressourcen im HTML eingebettet sind
Markup in einer base64-codierten Form.


**Returns:**
java.lang.String - Zeichenkette, die in keinem Fall NULL oder leer ist

### save(String htmlFilePath) {#save-java.lang.String-}
```
public final void save(String htmlFilePath)
```


Speichert dieses HTML-Dokument in die Datei am angegebenen Pfad, wo das HTML-Markup
gespeichert wird, und in den zugehörigen Ordner mit Ressourcen.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | htmlFilePath | java.lang.String | Vollständiger Pfad zur Datei, in der das HTML-Markup gespeichert wird. Die Datei wird erstellt oder überschrieben, falls sie existiert. Der zugehörige Ressourcenordner wird im selben Verzeichnis erstellt, in dem die HTML-Datei existiert. |
|

### save(String htmlFilePath, String resourcesFolderPath) {#save-java.lang.String-java.lang.String-}
```
public final void save(String htmlFilePath, String resourcesFolderPath)
```


Speichert dieses HTML-Dokument in die Datei am angegebenen Pfad, wo das HTML-Markup
gespeichert wird, und in den zugehörigen Ordner mit Ressourcen, welcher
am angegebenen Pfad liegt.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | htmlFilePath | java.lang.String | Vollständiger Pfad zur Datei, in der das HTML-Markup gespeichert wird. Darf nicht NULL oder leer sein. Die Datei wird erstellt oder überschrieben, falls sie existiert. |
|
|  | resourcesFolderPath | java.lang.String | Vollständiger Pfad zum zugehörigen Ordner, in dem alle zugehörigen Ressourcen gespeichert werden. Wenn NULL oder leer, wird der Ordner automatisch im selben Verzeichnis wie die \\*.html-Datei erstellt. Wenn angegeben und nicht vorhanden, wird er erstellt. |
|

### save(Writer htmlMarkup, HtmlSaveOptions saveOptions) {#save-java.io.Writer-com.groupdocs.editor.options.HtmlSaveOptions-}
```
public void save(Writer htmlMarkup, HtmlSaveOptions saveOptions)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| htmlMarkup | java.io.Writer |  |
| saveOptions | [HtmlSaveOptions](../../com.groupdocs.editor.options/htmlsaveoptions) |  |

### fromMarkup(String newHtmlContent, List<IHtmlResource> resources) {#fromMarkup-java.lang.String-java.util.List-com.groupdocs.editor.htmlcss.resources.IHtmlResource--}
```
public static EditableDocument fromMarkup(String newHtmlContent, List<IHtmlResource> resources)
```


Statische Fabrik, die eine Instanz von EditableDocument erstellt aus
spezifiziertem HTML-Markup und einem Satz entsprechender verknüpfter Ressourcen


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | newHtmlContent | java.lang.String | String, der das rohe HTML-Markup enthält, das geparst werden soll. Darf nicht NULL, leer oder ungültig sein. |
|
|  | resources | java.util.List<com.groupdocs.editor.htmlcss.resources.IHtmlResource> | Sammlung aller Ressourcen (Bilder, Stylesheets, Schriftarten), die im HTML-Dokument verwendet werden, angegeben im Parameter  newHtmlContent . Kann fehlen (NULL oder leere Sammlung). |
|

**Returns:**
[EditableDocument](../../com.groupdocs.editor/editabledocument) - New non-null instance of EditableDocument

### fromMarkupAndResourceFolder(String newHtmlContent, String resourceFolderPath) {#fromMarkupAndResourceFolder-java.lang.String-java.lang.String-}
```
public static EditableDocument fromMarkupAndResourceFolder(String newHtmlContent, String resourceFolderPath)
```


Statische Fabrik, die eine Instanz von EditableDocument aus einem angegebenen HTML-Markup und aus Ressourcen erstellt, die im Ordner liegen, der durch den vollständigen Pfad angegeben ist


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | newHtmlContent | java.lang.String | String, der das rohe HTML-Markup enthält, das geparst werden soll. Darf nicht NULL, leer oder ungültig sein. |
|
|  | resourceFolderPath | java.lang.String | Erforderlicher Pfad zum Ordner mit Ressourcen. Alle Stylesheets, die sich in diesem Ordner befinden, werden verwendet. Darf nicht NULL oder ein leerer String sein, und dieser Ordner muss existieren. |

<br />

*** ** * ** ***

Diese statische Fabrik ist nützlich, wenn der Inhalt eines HTML-Dokuments als Zeichenkette vorliegt, die Ressourcen jedoch in einem Ordner liegen und häufig Links zu diesen Ressourcen im HTML-Markup ungültig oder nicht vorhanden sind. Beim Aufruf dieser Methode wird der angegebene Ordner durchsucht und automatisch alle gefundenen Stylesheets auf das Dokument angewendet. Diese Methode ist sehr hilfreich beim Einbinden von Inhalten aus verschiedenen HTML-Editoren, die normalerweise die Dokumentmetadaten usw. abschneiden.

<br />

|

**Returns:**
[EditableDocument](../../com.groupdocs.editor/editabledocument) - New non-null instance of EditableDocument

### fromFile(String htmlFilePath, String resourceFolderPath) {#fromFile-java.lang.String-java.lang.String-}
```
public static EditableDocument fromFile(String htmlFilePath, String resourceFolderPath)
```


Statische Fabrik, die eine Instanz von EditableDocument aus einem HTML
Datei, die durch einen Pfad zur \*.html-Datei selbst und einen Ordner angegeben ist
mit verknüpften Ressourcen


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | htmlFilePath | java.lang.String | String, der einen vollständigen Pfad zur HTML-Datei enthält. Darf nicht null sein, muss ein gültiger Dateipfad sein und die Datei selbst muss existieren. |
|
|  | resourceFolderPath | java.lang.String | Optionaler Pfad zum Ordner mit HTML-Ressourcen. Wenn NULL, ungültig oder ein solcher Ordner nicht existiert, versucht der Editor, diesen Ordner selbst zu finden, indem er das HTML-Markup analysiert. |
|

**Returns:**
[EditableDocument](../../com.groupdocs.editor/editabledocument) - New non-null instance of EditableDocument

### dispose() {#dispose--}
```
public final void dispose()
```


Entsorgt diese Editable-Dokument-Instanz, wobei ihr Inhalt entsorgt wird und
wodurch ihre Methoden und Eigenschaften nicht mehr funktionieren


### isDisposed() {#isDisposed--}
```
public final boolean isDisposed()
```


Bestimmt, ob dieses Editable-Dokument bereits entsorgt wurde (true) oder
nicht (false)


**Returns:**
boolean
