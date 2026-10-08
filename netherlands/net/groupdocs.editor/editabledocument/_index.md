---
title: "EditableDocument"
second_title: "GroupDocs.Editor voor .NET API-referentie"
description: "Tussentijds document dat inhoud bevat vóór en na bewerking"
type: docs
weight: 10
url: /nl/net/groupdocs.editor/editabledocument/
---
## EditableDocument class

Tussentijds document dat inhoud bevat vóór en na het bewerken

```csharp
public sealed class EditableDocument : IAuxDisposable
```

## Properties

| Name | Beschrijving |
| --- | --- |
| [AllResources](../../groupdocs.editor/editabledocument/allresources) { get; } | Retourneert een lijst van alle bestaande bronnen: alle stylesheets, afbeeldingen uit HTML en alle stylesheets, lettertypen, audio |
| [Audio](../../groupdocs.editor/editabledocument/audio) { get; } | Retourneert een lijst van audio‑bronnen |
| [Css](../../groupdocs.editor/editabledocument/css) { get; } | Staat toe stylesheet‑ (CSS‑)bronnen te verkrijgen (zowel extern als ingebed, maar niet inline) die door dit HTML‑document worden gebruikt |
| [Fonts](../../groupdocs.editor/editabledocument/fonts) { get; } | Staat toe externe lettertype‑bronnen te verkrijgen die door dit HTML‑document worden gebruikt |
| [Images](../../groupdocs.editor/editabledocument/images) { get; } | Staat toe externe afbeeldingsbronnen (raster‑ en vectorafbeeldingen) te verkrijgen die door dit HTML‑document worden gebruikt |
| [IsDisposed](../../groupdocs.editor/editabledocument/isdisposed) { get; } | Bepaalt of dit Editable‑document al is vrijgegeven (true) of niet (false) |

## Methods

| Name | Beschrijving |
| --- | --- |
| static [FromFile](../../groupdocs.editor/editabledocument/fromfile)(string, string) | Statische fabriek die een instantie van EditableDocument maakt vanuit een HTML‑bestand, gespecificeerd door een pad naar het *.html‑bestand zelf en een map met gekoppelde bronnen |
| static [FromMarkup](../../groupdocs.editor/editabledocument/frommarkup#frommarkup)(string) | Statische fabriek die een instantie van [`EditableDocument`](../editabledocument) maakt vanuit opgegeven HTML‑markup |
| static [FromMarkup](../../groupdocs.editor/editabledocument/frommarkup#frommarkup_1)(string, IEnumerable&lt;IHtmlResource&gt;) | Statische fabriek die een instantie van EditableDocument maakt vanuit opgegeven HTML‑markup en een set van bijbehorende gekoppelde bronnen |
| static [FromMarkupAndResourceFolder](../../groupdocs.editor/editabledocument/frommarkupandresourcefolder)(string, string) | Statische fabriek die een instantie van EditableDocument maakt vanuit opgegeven HTML‑markup en vanuit bronnen, gelegen in de map die is gespecificeerd door het volledige pad |
| [Dispose](../../groupdocs.editor/editabledocument/dispose)() | Geeft deze Editable‑document‑instantie vrij, waarbij de inhoud wordt vrijgegeven en de methoden en eigenschappen niet meer werken |
| [GetBodyContent](../../groupdocs.editor/editabledocument/getbodycontent#getbodycontent)() | Retourneert de body van het HTML‑document (interne inhoud tussen de opening‑ en sluit‑BODY‑tags zonder deze tags) als een string. |
| [GetBodyContent](../../groupdocs.editor/editabledocument/getbodycontent#getbodycontent_1)(string) | Retourneert de body van het HTML‑document (interne inhoud tussen de opening‑ en sluit‑BODY‑tags zonder deze tags) als een string, waarbij links naar de externe bronnen een opgegeven sjabloon met plaatsaanduidingen bevatten. |
| [GetContent](../../groupdocs.editor/editabledocument/getcontent#getcontent)() | Retourneert de volledige inhoud van het HTML‑document als een string. |
| [GetContent](../../groupdocs.editor/editabledocument/getcontent#getcontent_1)(string, string) | Retourneert de volledige inhoud van het HTML‑document als een string, waarbij links naar de externe bronnen een opgegeven sjabloon met plaatsaanduidingen bevatten. |
| [GetContent&lt;TStream&gt;](../../groupdocs.editor/editabledocument/getcontent#getcontent_2)(TStream, Encoding) | Retourneert de volledige inhoud van het HTML‑document als een byte‑stroom door deze inhoud naar een opgegeven stroom te schrijven met de opgegeven tekencodering |
| [GetCssContent](../../groupdocs.editor/editabledocument/getcsscontent#getcsscontent)() | Retourneert de inhoud van alle externe stylesheets als een lijst van strings, waarbij één string één stylesheet vertegenwoordigt. Retourneert een lege lijst als er geen CSS voor dit document is. |
| [GetCssContent](../../groupdocs.editor/editabledocument/getcsscontent#getcsscontent_1)(string, string) | Retourneert de inhoud van alle externe stylesheets als een lijst van strings, waarbij één string één stylesheet vertegenwoordigt. Het opgegeven voorvoegsel wordt toegepast op elke link naar de externe bron in elke resulterende stylesheet. Retourneert een lege lijst als er geen CSS voor dit document is. |
| [GetEmbeddedHtml](../../groupdocs.editor/editabledocument/getembeddedhtml)() | Retourneert alle inhoud van dit HTML‑document met alle gerelateerde bronnen in de vorm van één string, waarbij alle bronnen zijn ingebed in de HTML‑markup in base64‑gecodeerde vorm. |
| [Save](../../groupdocs.editor/editabledocument/save#save_1)(string) | Slaat dit HTML‑document op naar het bestand op het opgegeven pad, waar de HTML‑markup wordt opgeslagen, en naar de bijbehorende map met bronnen. |
| [Save](../../groupdocs.editor/editabledocument/save#save_2)(string, string) | Slaat dit HTML‑document op naar het bestand op het opgegeven pad, waar de HTML‑markup wordt opgeslagen, en naar de bijbehorende map met bronnen, die zich op het opgegeven pad bevindt. |
| [Save](../../groupdocs.editor/editabledocument/save#save)(TextWriter, HtmlSaveOptions) | Slaat de inhoud van dit [`EditableDocument`](../editabledocument) op als het HTML‑document naar de opgegeven tekstschrijver, terwijl de tweede optionele parameter het mogelijk maakt de opslagprocedure aan te passen en de callback voor het opslaan van bronnen op te geven. |

## Evenementen

| Name | Beschrijving |
| --- | --- |
| event [Disposed](../../groupdocs.editor/editabledocument/disposed) | Evenement dat optreedt wanneer dit Editable document wordt verwijderd, direct nadat het verwijderingsproces is voltooid. |

### Opmerkingen

Een instantie van de `EditableDocument`-klasse kan worden verkregen via de '[`Edit`](../editor/edit)'-methode of door de gebruiker zelf met behulp van statische factories te worden aangemaakt. `EditableDocument` slaat intern het document op in een eigen gesloten formaat, dat compatibel (converteerbaar) is met alle import- en exportformaten die GroupDocs.Editor ondersteunt. Om het document bewerkbaar te maken in elke WYSIWYG client‑side editor (zoals CKEditor of TinyMCE), biedt `EditableDocument` methoden voor het genereren van HTML‑markup en het produceren van bronnen die door de gebruiker geaccepteerd kunnen worden.

### Zie ook

* interface [IAuxDisposable](../../groupdocs.editor.htmlcss.resources/iauxdisposable)
* namespace [GroupDocs.Editor](../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.editor.dll -->
