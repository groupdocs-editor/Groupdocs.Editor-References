---
title: EditableDocument
second_title: GroupDocs.Editor voor .NET API-referentie
description: Tussendocument dat inhoud bevat voor en na bewerking
type: docs
weight: 10
url: /nl/net/groupdocs.editor/editabledocument/
---
## EditableDocument class

Tussendocument, dat inhoud bevat voor en na bewerking

```csharp
public sealed class EditableDocument : IAuxDisposable
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [AllResources](../../groupdocs.editor/editabledocument/allresources) { get; } | Geeft een lijst terug van alle bestaande bronnen: alle stylesheets, afbeeldingen uit HTML en alle stylesheets, fonts, audio |
| [Audio](../../groupdocs.editor/editabledocument/audio) { get; } | Retourneert een lijst met audiobronnen |
| [Css](../../groupdocs.editor/editabledocument/css) { get; } | Retourneert een lijst met CSS-bronnen |
| [Fonts](../../groupdocs.editor/editabledocument/fonts) { get; } | Maakt het mogelijk om externe bronnen voor lettertypen te verkrijgen, die worden gebruikt door dit HTML-document |
| [Images](../../groupdocs.editor/editabledocument/images) { get; } | Maakt het verkrijgen van externe afbeeldingsbronnen (raster- en vectorafbeeldingen) mogelijk, die door dit HTML-document worden gebruikt |
| [IsDisposed](../../groupdocs.editor/editabledocument/isdisposed) { get; } | Bepaalt of dit bewerkbare document al verwijderd was (true) of niet (false) |

## methoden

| Naam | Beschrijving |
| --- | --- |
| static [FromFile](../../groupdocs.editor/editabledocument/fromfile)(string, string) | Statische fabriek, die een exemplaar van EditableDocument maakt van een HTML-bestand, dat wordt gespecificeerd door een pad naar het *.html-bestand zelf en een map met gekoppelde bronnen |
| static [FromMarkup](../../groupdocs.editor/editabledocument/frommarkup)(string, IEnumerable&lt;IHtmlResource&gt;) | Statische fabriek, die een exemplaar van EditableDocument maakt op basis van opgegeven HTML-opmaak en een set overeenkomstige gekoppelde bronnen |
| static [FromMarkupAndResourceFolder](../../groupdocs.editor/editabledocument/frommarkupandresourcefolder)(string, string) | Statische fabriek, die een exemplaar van EditableDocument maakt van een opgegeven HTML-opmaak en van bronnen in de map, gespecificeerd door het volledige pad |
| [Dispose](../../groupdocs.editor/editabledocument/dispose)() | Verwijdert deze bewerkbare documentinstantie, verwijdert de inhoud en zorgt ervoor dat de methoden en eigenschappen ervan niet meer werken |
| [GetBodyContent](../../groupdocs.editor/editabledocument/getbodycontent#getbodycontent)() | Retourneert een body van het HTML-document (innerlijke inhoud tussen het openen en sluiten van BODY-tags zonder deze tags) als een tekenreeks. |
| [GetBodyContent](../../groupdocs.editor/editabledocument/getbodycontent#getbodycontent_1)(string) | Retourneert een hoofdtekst van het HTML-document (innerlijke inhoud tussen het openen en sluiten van BODY-tags zonder deze tags) als een tekenreeks, waar links naar de externe bronnen een gespecificeerd voorvoegsel bevatten. |
| [GetContent](../../groupdocs.editor/editabledocument/getcontent#getcontent)() | Retourneert de algemene inhoud van het HTML-document als een tekenreeks. |
| [GetContent](../../groupdocs.editor/editabledocument/getcontent#getcontent_1)(string, string) | Retourneert de algemene inhoud van het HTML-document als een tekenreeks, waarbij koppelingen naar de externe bronnen een gespecificeerd voorvoegsel bevatten. |
| [GetCssContent](../../groupdocs.editor/editabledocument/getcsscontent#getcsscontent)() | Retourneert de inhoud van alle externe stylesheets als een lijst met strings, waarbij één string één stylesheet vertegenwoordigt. Retourneert een lege lijst, als er geen CSS is voor dit document. |
| [GetCssContent](../../groupdocs.editor/editabledocument/getcsscontent#getcsscontent_1)(string, string) | Retourneert inhoud van alle externe stylesheets als een lijst met strings, waarbij één string één stylesheet vertegenwoordigt. Opgegeven prefix wordt toegepast op elke link naar de externe bron in elke resulterende stylesheet. Retourneert lege lijst, als er geen CSS voor is document. |
| [GetEmbeddedHtml](../../groupdocs.editor/editabledocument/getembeddedhtml)() | Retourneert alle inhoud van dit HTML-document met alle gerelateerde bronnen in de vorm van een enkele tekenreeks, waarbij alle bronnen zijn ingesloten in de HTML-opmaak in een base64-gecodeerde vorm. |
| [Save](../../groupdocs.editor/editabledocument/save#save)(string) | Slaat dit HTML-document op in het bestand op het opgegeven pad, waar HTML-opmaak wordt opgeslagen, en in de bijbehorende map met bronnen. |
| [Save](../../groupdocs.editor/editabledocument/save#save_1)(string, string) | Slaat dit HTML-document op in het bestand op het opgegeven pad, waar de HTML-opmaak wordt opgeslagen, en in de bijbehorende map met bronnen, die zich op het opgegeven pad bevindt. |

## Evenementen

| Naam | Beschrijving |
| --- | --- |
| event [Disposed](../../groupdocs.editor/editabledocument/disposed) | Gebeurtenis die optreedt wanneer dit bewerkbare document wordt verwijderd, direct nadat het verwijderingsproces is voltooid |

### Opmerkingen

Instantie van de klasse EditableDocument kan worden geproduceerd door de '[`Edit`](../editor/edit) methode of gemaakt door de gebruiker zelf met behulp van statische fabrieken. EditableDocument slaat het document intern op in zijn eigen gesloten formaat, dat compatibel (converteerbaar) is met alle import- en exportformaten, die GroupDocs.Editor ondersteunt. Om documenten bewerkbaar te maken in elke WYSIWYG client-side editor (zoals CKEditor of TinyMCE), biedt EditableDocument methoden voor het genereren van HTML-opmaak en het produceren van bronnen die door de gebruiker kunnen worden geaccepteerd.

### Zie ook

* interface [IAuxDisposable](../../groupdocs.editor.htmlcss.resources/iauxdisposable)
* naamruimte [GroupDocs.Editor](../../groupdocs.editor)
* montage [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
