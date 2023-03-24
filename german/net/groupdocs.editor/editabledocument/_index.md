---
title: EditableDocument
second_title: GroupDocs.Editor für .NET-API-Referenz
description: Zwischendokument das Inhalte vor und nach der Bearbeitung enthält
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
| [AllResources](../../groupdocs.editor/editabledocument/allresources) { get; } | Gibt eine Liste aller vorhandenen Ressourcen zurück: alle Stylesheets, Bilder aus HTML und alle Stylesheets, Schriftarten, Audio |
| [Audio](../../groupdocs.editor/editabledocument/audio) { get; } | Gibt eine Liste von Audioressourcen zurück |
| [Css](../../groupdocs.editor/editabledocument/css) { get; } | Gibt eine Liste von CSS-Ressourcen zurück |
| [Fonts](../../groupdocs.editor/editabledocument/fonts) { get; } | Ermöglicht das Abrufen externer Schriftartressourcen, die von diesem HTML-Dokument verwendet werden |
| [Images](../../groupdocs.editor/editabledocument/images) { get; } | Ermöglicht das Abrufen externer Bildressourcen (Raster- und Vektorbilder), die von diesem HTML-Dokument verwendet werden |
| [IsDisposed](../../groupdocs.editor/editabledocument/isdisposed) { get; } | Bestimmt, ob dieses bearbeitbare Dokument bereits verworfen wurde (true) oder nicht (false) |

## Methoden

| Name | Beschreibung |
| --- | --- |
| static [FromFile](../../groupdocs.editor/editabledocument/fromfile)(string, string) | Statische Factory, die eine Instanz von EditableDocument aus einer HTML-Datei erstellt, die durch einen Pfad zur *.html-Datei selbst und einen Ordner mit verknüpften Ressourcen angegeben wird |
| static [FromMarkup](../../groupdocs.editor/editabledocument/frommarkup)(string, IEnumerable&lt;IHtmlResource&gt;) | Statische Factory, die eine Instanz von EditableDocument aus dem angegebenen HTML-Markup und einem Satz entsprechender verknüpfter Ressourcen erstellt |
| static [FromMarkupAndResourceFolder](../../groupdocs.editor/editabledocument/frommarkupandresourcefolder)(string, string) | Statische Factory, die eine Instanz von EditableDocument aus einem angegebenen HTML-Markup und aus Ressourcen erstellt, die sich in dem Ordner befinden, der durch den vollständigen Pfad angegeben wird |
| [Dispose](../../groupdocs.editor/editabledocument/dispose)() | Löscht diese bearbeitbare Dokumentinstanz, löscht ihren Inhalt und macht ihre Methoden und Eigenschaften nicht funktionsfähig |
| [GetBodyContent](../../groupdocs.editor/editabledocument/getbodycontent#getbodycontent)() | Gibt einen Hauptteil des HTML-Dokuments (innerer Inhalt zwischen öffnenden und schließenden BODY-Tags ohne diese Tags) als Zeichenfolge zurück. |
| [GetBodyContent](../../groupdocs.editor/editabledocument/getbodycontent#getbodycontent_1)(string) | Gibt einen Hauptteil des HTML-Dokuments (innerer Inhalt zwischen öffnenden und schließenden BODY-Tags ohne diese Tags) als Zeichenfolge zurück, wobei Links zu externen Ressourcen das angegebene Präfix enthalten. |
| [GetContent](../../groupdocs.editor/editabledocument/getcontent#getcontent)() | Gibt den gesamten Inhalt des HTML-Dokuments als Zeichenfolge zurück. |
| [GetContent](../../groupdocs.editor/editabledocument/getcontent#getcontent_1)(string, string) | Gibt den gesamten Inhalt des HTML-Dokuments als Zeichenfolge zurück, wobei Links zu externen Ressourcen das angegebene Präfix enthalten. |
| [GetCssContent](../../groupdocs.editor/editabledocument/getcsscontent#getcsscontent)() | Gibt den Inhalt aller externen Stylesheets als Liste von Strings zurück, wobei ein String ein Stylesheet darstellt. Gibt eine leere Liste zurück, wenn es kein CSS für dieses Dokument gibt. |
| [GetCssContent](../../groupdocs.editor/editabledocument/getcsscontent#getcsscontent_1)(string, string) | Gibt den Inhalt aller externen Stylesheets als Liste von Strings zurück, wobei ein String ein Stylesheet darstellt. Das angegebene Präfix wird auf jeden Link auf die externe Ressource in jedem resultierenden Stylesheet angewendet. Gibt eine leere Liste zurück, wenn es kein CSS dafür gibt Dokument. |
| [GetEmbeddedHtml](../../groupdocs.editor/editabledocument/getembeddedhtml)() | Gibt den gesamten Inhalt dieses HTML-Dokuments mit allen zugehörigen Ressourcen in Form einer einzelnen Zeichenfolge zurück, wobei alle Ressourcen innerhalb des -HTML-Markups in base64-codierter Form eingebettet sind. |
| [Save](../../groupdocs.editor/editabledocument/save#save)(string) | Speichert dieses HTML-Dokument in der Datei im angegebenen Pfad, in der das HTML-Markup gespeichert wird, und im zugehörigen Ordner mit Ressourcen. |
| [Save](../../groupdocs.editor/editabledocument/save#save_1)(string, string) | Speichert dieses HTML-Dokument in der Datei im angegebenen Pfad, in der das HTML-Markup gespeichert wird, und im zugehörigen Ordner mit den Ressourcen , der sich im angegebenen Pfad befindet. |

## Veranstaltungen

| Name | Beschreibung |
| --- | --- |
| event [Disposed](../../groupdocs.editor/editabledocument/disposed) | Ereignis, das eintritt, wenn dieses bearbeitbare Dokument verworfen wird, direkt nach Abschluss des Vernichtungsprozesses |

### Bemerkungen

Eine Instanz der EditableDocument-Klasse kann durch die '[`Edit`](../editor/edit) Methode oder vom Benutzer selbst unter Verwendung statischer Fabriken erstellt. EditableDocument speichert Dokumente intern in einem eigenen geschlossenen Format, das mit allen Import- und Exportformaten kompatibel (konvertierbar) ist, die von GroupDocs.Editor unterstützt werden. Um das Dokument in jedem clientseitigen WYSIWYG-Editor (wie CKEditor oder TinyMCE) bearbeitbar zu machen, bietet EditableDocument Methoden zum Generieren von HTML-Markup und zum Produzieren von Ressourcen, die vom Benutzer akzeptiert werden können.

### Siehe auch

* interface [IAuxDisposable](../../groupdocs.editor.htmlcss.resources/iauxdisposable)
* namensraum [GroupDocs.Editor](../../groupdocs.editor)
* Montage [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
