---
title: "EditableDocument"
second_title: "GroupDocs.Editor für .NET API-Referenz"
description: "Zwischendokument, das den Inhalt vor und nach der Bearbeitung enthält."
type: docs
weight: 10
url: /de/net/groupdocs.editor/editabledocument/
---
## EditableDocument class

Zwischendokument, das Inhalte vor und nach der Bearbeitung enthält

```csharp
public sealed class EditableDocument : IAuxDisposable
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AllResources](../../groupdocs.editor/editabledocument/allresources) { get; } | Gibt eine Liste aller vorhandenen Ressourcen zurück: alle Stylesheets, Bilder aus HTML sowie alle Stylesheets, Schriftarten, Audio. |
| [Audio](../../groupdocs.editor/editabledocument/audio) { get; } | Gibt eine Liste von Audio-Ressourcen zurück. |
| [Css](../../groupdocs.editor/editabledocument/css) { get; } | Ermöglicht das Abrufen von Stylesheet‑ (CSS‑)Ressourcen (sowohl extern als auch eingebettet, jedoch nicht inline), die von diesem HTML-Dokument verwendet werden. |
| [Fonts](../../groupdocs.editor/editabledocument/fonts) { get; } | Ermöglicht das Abrufen externer Schriftart‑Ressourcen, die von diesem HTML-Dokument verwendet werden. |
| [Images](../../groupdocs.editor/editabledocument/images) { get; } | Ermöglicht das Abrufen externer Bild‑Ressourcen (Raster‑ und Vektor‑Bilder), die von diesem HTML-Dokument verwendet werden. |
| [IsDisposed](../../groupdocs.editor/editabledocument/isdisposed) { get; } | Bestimmt, ob dieses Editable‑Dokument bereits freigegeben wurde (true) oder nicht (false). |

## Methoden

| Name | Beschreibung |
| --- | --- |
| static [FromFile](../../groupdocs.editor/editabledocument/fromfile)(string, string) | Statische Fabrik, die eine Instanz von EditableDocument aus einer HTML‑Datei erstellt, die durch einen Pfad zur *.html‑Datei selbst und einen Ordner mit verknüpften Ressourcen angegeben ist. |
| static [FromMarkup](../../groupdocs.editor/editabledocument/frommarkup#frommarkup)(string) | Statische Fabrik, die eine Instanz von [`EditableDocument`](../editabledocument) aus angegebenem HTML‑Markup erstellt. |
| static [FromMarkup](../../groupdocs.editor/editabledocument/frommarkup#frommarkup_1)(string, IEnumerable&lt;IHtmlResource&gt;) | Statische Fabrik, die eine Instanz von EditableDocument aus angegebenem HTML‑Markup und einem Satz entsprechender verknüpfter Ressourcen erstellt. |
| static [FromMarkupAndResourceFolder](../../groupdocs.editor/editabledocument/frommarkupandresourcefolder)(string, string) | Statische Fabrik, die eine Instanz von EditableDocument aus angegebenem HTML‑Markup und aus Ressourcen erstellt, die sich in dem Ordner befinden, der durch den vollständigen Pfad angegeben ist. |
| [Dispose](../../groupdocs.editor/editabledocument/dispose)() | Gibt diese Editable document Instanz frei, entsorgt deren Inhalt und macht deren Methoden und Eigenschaften funktionsunfähig. |
| [GetBodyContent](../../groupdocs.editor/editabledocument/getbodycontent#getbodycontent)() | Gibt den Body des HTML-Dokuments zurück (innerer Inhalt zwischen öffnenden und schließenden BODY-Tags ohne diese Tags) als Zeichenkette. |
| [GetBodyContent](../../groupdocs.editor/editabledocument/getbodycontent#getbodycontent_1)(string) | Gibt den Body des HTML-Dokuments zurück (innerer Inhalt zwischen öffnenden und schließenden BODY-Tags ohne diese Tags) als Zeichenkette, wobei Links zu externen Ressourcen das angegebene Template mit Platzhaltern enthalten. |
| [GetContent](../../groupdocs.editor/editabledocument/getcontent#getcontent)() | Gibt den gesamten Inhalt des HTML-Dokuments als Zeichenkette zurück. |
| [GetContent](../../groupdocs.editor/editabledocument/getcontent#getcontent_1)(string, string) | Gibt den gesamten Inhalt des HTML-Dokuments als Zeichenkette zurück, wobei Links zu externen Ressourcen das angegebene Template mit Platzhaltern enthalten. |
| [GetContent&lt;TStream&gt;](../../groupdocs.editor/editabledocument/getcontent#getcontent_2)(TStream, Encoding) | Gibt den gesamten Inhalt des HTML-Dokuments als Byte-Stream zurück, indem dieser Inhalt in den angegebenen Stream mit der angegebenen Textkodierung geschrieben wird. |
| [GetCssContent](../../groupdocs.editor/editabledocument/getcsscontent#getcsscontent)() | Gibt den Inhalt aller externen Stylesheets als Liste von Zeichenketten zurück, wobei jede Zeichenkette ein Stylesheet darstellt. Gibt eine leere Liste zurück, wenn für dieses Dokument kein CSS vorhanden ist. |
| [GetCssContent](../../groupdocs.editor/editabledocument/getcsscontent#getcsscontent_1)(string, string) | Gibt den Inhalt aller externen Stylesheets als Liste von Zeichenketten zurück, wobei jede Zeichenkette ein Stylesheet darstellt. Das angegebene Präfix wird auf jeden Link zur externen Ressource in jedem resultierenden Stylesheet angewendet. Gibt eine leere Liste zurück, wenn für dieses Dokument kein CSS vorhanden ist. |
| [GetEmbeddedHtml](../../groupdocs.editor/editabledocument/getembeddedhtml)() | Gibt den gesamten Inhalt dieses HTML-Dokuments mit allen zugehörigen Ressourcen als einzelne Zeichenkette zurück, wobei alle Ressourcen im HTML-Markup in Base64-kodierter Form eingebettet sind. |
| [Save](../../groupdocs.editor/editabledocument/save#save_1)(string) | Speichert dieses HTML-Dokument in die Datei am angegebenen Pfad, wobei das HTML-Markup gespeichert wird, sowie in den zugehörigen Ordner mit Ressourcen. |
| [Save](../../groupdocs.editor/editabledocument/save#save_2)(string, string) | Speichert dieses HTML-Dokument in die Datei am angegebenen Pfad, wobei das HTML-Markup gespeichert wird, und in den zugehörigen Ordner mit Ressourcen, der sich am angegebenen Pfad befindet. |
| [Save](../../groupdocs.editor/editabledocument/save#save)(TextWriter, HtmlSaveOptions) | Speichert den Inhalt dieses [`EditableDocument`](../editabledocument) als HTML-Dokument in den angegebenen Textwriter, wobei der zweite Optionsparameter es ermöglicht, den Speicherungsprozess anzupassen und den Rückruf zum Speichern von Ressourcen anzugeben. |

## Ereignisse

| Name | Beschreibung |
| --- | --- |
| event [Disposed](../../groupdocs.editor/editabledocument/disposed) | Ereignis, das auftritt, wenn dieses Editable-Dokument freigegeben wird, unmittelbar nach Abschluss des Freigabevorgangs. |

### Hinweise

Eine Instanz der Klasse `EditableDocument` kann durch die Methode '[`Edit`](../editor/edit)' erzeugt oder vom Benutzer selbst über statische Fabriken erstellt werden. `EditableDocument` speichert das Dokument intern in einem eigenen geschlossenen Format, das mit allen Import‑ und Exportformaten, die GroupDocs.Editor unterstützt, kompatibel (konvertierbar) ist. Um das Dokument in einem beliebigen WYSIWYG‑Client‑Editor (wie CKEditor oder TinyMCE) editierbar zu machen, stellt `EditableDocument` Methoden zum Erzeugen von HTML‑Markup und zum Erzeugen von Ressourcen bereit, die vom Benutzer akzeptiert werden können.

### Siehe auch

* interface [IAuxDisposable](../../groupdocs.editor.htmlcss.resources/iauxdisposable)
* namespace [GroupDocs.Editor](../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.editor.dll -->
