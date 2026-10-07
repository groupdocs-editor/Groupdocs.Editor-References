---
title: "EditableDocument"
second_title: "GroupDocs.Editor for Java API-referentie"
description: "Tussentijds document dat inhoud bevat vóór en na bewerking"
type: docs
weight: 10
url: /nl/java/com.groupdocs.editor/editabledocument/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.IAuxDisposable](../../com.groupdocs.editor.htmlcss.resources/iauxdisposable)
```
public final class EditableDocument implements IAuxDisposable
```

Tussendocument dat inhoud bevat vóór en na het bewerken.


*** ** * ** ***

Een instantie van de EditableDocument‑klasse kan worden geproduceerd door de Editor.edit()‑methode of door de gebruiker zelf worden aangemaakt met behulp van statische factories. EditableDocument slaat intern het document op in een eigen gesloten formaat, dat compatibel (converteerbaar) is met alle import‑ en exportformaten die GroupDocs.Editor ondersteunt. Om het document bewerkbaar te maken in elke WYSIWYG client‑side editor (zoals CKEditor of TinyMCE), biedt EditableDocument methoden voor het genereren van HTML‑markup en het produceren van bronnen die door de gebruiker geaccepteerd kunnen worden.

<br />


## Velden

| Veld | Beschrijving |
| --- | --- |
| [Disposed](#Disposed) |  |
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getImages()](#getImages--) | Staat toe om externe afbeeldingsbronnen (rasterafbeeldingen) te verkrijgen, die worden gebruikt |
door dit HTML-document
|
|  | [getFonts()](#getFonts--) | Staat toe om externe lettertypebronnen te verkrijgen, die door dit HTML worden gebruikt |
document
|
|  | [getCss()](#getCss--) | Retourneert een lijst met CSS-bronnen |
|
|  | [getAudio()](#getAudio--) | Retourneert een lijst met audiobronnen |
|
|  | [getAllResources()](#getAllResources--) | Retourneert een lijst van alle bestaande bronnen: alle stylesheets, afbeeldingen van |
HTML en alle stylesheets, lettertypen
|
|  | [getContent(OutputStream storage, Charset encoding)](#getContent-java.io.OutputStream-java.nio.charset.Charset-) | Retourneert de volledige inhoud van het HTML-document als een byte‑stroom door deze inhoud naar de opgegeven stroom te schrijven met de opgegeven tekencodering |
|
|  | [getBodyContent()](#getBodyContent--) | Retourneert een body van het HTML-document (inhoud tussen de opening en sluiting |
BODY‑tags zonder deze tags) als een string.
|
|  | [getBodyContent(String externalImagesTemplate)](#getBodyContent-java.lang.String-) | Retourneert een body van het HTML-document (inhoud tussen de opening en sluiting |
BODY‑tags zonder deze tags) als een string, waarbij links naar de externe
bronnen de opgegeven prefix bevatten.
|
|  | [getContent()](#getContent--) | Retourneert de volledige inhoud van het HTML-document als een string. |
|
|  | [getContentString(String externalImagesTemplate, String externalCssTemplate)](#getContentString-java.lang.String-java.lang.String-) | Retourneert de volledige inhoud van het HTML-document als een string, waarbij links naar |
de externe bronnen de opgegeven prefix bevatten.
|
|  | [getCssContent()](#getCssContent--) | Retourneert de inhoud van alle externe stylesheets als een lijst van strings, waarbij |
een string één stylesheet vertegenwoordigt.
|
|  | [getCssContent(String externalImagesPrefix, String externalFontsPrefix)](#getCssContent-java.lang.String-java.lang.String-) | Retourneert de inhoud van alle externe stylesheets als een lijst van strings, waarbij |
een string één stylesheet vertegenwoordigt.
|
|  | [getEmbeddedHtml()](#getEmbeddedHtml--) | Retourneert alle inhoud van dit HTML-document met alle gerelateerde bronnen in een |
vorm van één enkele string, waarbij alle bronnen zijn ingebed in de HTML
markup in een base64‑gecodeerde vorm.
|
|  | [save(String htmlFilePath)](#save-java.lang.String-) | Slaat dit HTML-document op in het bestand op het opgegeven pad, waar HTML-markup |
wordt opgeslagen, en in de bijbehorende map met bronnen.
|
|  | [save(String htmlFilePath, String resourcesFolderPath)](#save-java.lang.String-java.lang.String-) | Slaat dit HTML-document op in het bestand op het opgegeven pad, waar HTML-markup |
wordt opgeslagen, en in de bijbehorende map met bronnen, die is
geplaatst op het opgegeven pad.
|
| [save(Writer htmlMarkup, HtmlSaveOptions saveOptions)](#save-java.io.Writer-com.groupdocs.editor.options.HtmlSaveOptions-) |  |
|  | [fromMarkup(String newHtmlContent, List<IHtmlResource> resources)](#fromMarkup-java.lang.String-java.util.List-com.groupdocs.editor.htmlcss.resources.IHtmlResource--) | Statische fabriek, die een instantie van EditableDocument maakt van |
gespecificeerde HTML-markup en een set van bijbehorende gekoppelde bronnen
|
|  | [fromMarkupAndResourceFolder(String newHtmlContent, String resourceFolderPath)](#fromMarkupAndResourceFolder-java.lang.String-java.lang.String-) | Statische fabriek, die een instantie van EditableDocument maakt van een gespecificeerde HTML-markup en van bronnen, die zich bevinden in de map, gespecificeerd door het volledige pad |
|
|  | [fromFile(String htmlFilePath, String resourceFolderPath)](#fromFile-java.lang.String-java.lang.String-) | Statische fabriek, die een instantie van EditableDocument maakt van een HTML |
bestand, dat wordt gespecificeerd door een pad naar het \\*.html-bestand zelf en een map
met gekoppelde bronnen
|
|  | [dispose()](#dispose--) | Verwijdert deze Editable-documentinstantie, waarbij de inhoud wordt verwijderd en |
waardoor de methoden en eigenschappen niet meer werken
|
|  | [isDisposed()](#isDisposed--) | Bepaalt of dit Editable-document al is verwijderd (true) of |
niet (false)
|
### Disposed {#Disposed}
```
public final Event<EventHandler> Disposed
```


### getImages() {#getImages--}
```
public final List<IImageResource> getImages()
```


Staat toe om externe afbeeldingsbronnen (rasterafbeeldingen) te verkrijgen, die worden gebruikt
door dit HTML-document


**Returns:**
java.util.List<com.groupdocs.editor.htmlcss.resources.images.IImageResource>
### getFonts() {#getFonts--}
```
public final List<FontResourceBase> getFonts()
```


Staat toe om externe lettertypebronnen te verkrijgen, die door dit HTML worden gebruikt
document


**Returns:**
java.util.List<com.groupdocs.editor.htmlcss.resources.fonts.FontResourceBase>
### getCss() {#getCss--}
```
public final List<CssText> getCss()
```


Retourneert een lijst met CSS-bronnen


**Returns:**
java.util.List<com.groupdocs.editor.htmlcss.resources.textual.CssText>
### getAudio() {#getAudio--}
```
public final List<Mp3Audio> getAudio()
```


Retourneert een lijst met audiobronnen


**Returns:**
java.util.List<com.groupdocs.editor.htmlcss.resources.audio.Mp3Audio>
### getAllResources() {#getAllResources--}
```
public final List<IHtmlResource> getAllResources()
```


Retourneert een lijst van alle bestaande bronnen: alle stylesheets, afbeeldingen van
HTML en alle stylesheets, lettertypen


*** ** * ** ***

Deze eigenschap retourneert een samengevoegd resultaat van de eigenschappen 'Images', 'Fonts' en 'Css'

<br />



**Returns:**
java.util.List<com.groupdocs.editor.htmlcss.resources.IHtmlResource>
### getContent(OutputStream storage, Charset encoding) {#getContent-java.io.OutputStream-java.nio.charset.Charset-}
```
public OutputStream getContent(OutputStream storage, Charset encoding)
```


Retourneert de volledige inhoud van het HTML-document als een byte‑stroom door deze inhoud naar de opgegeven stroom te schrijven met de opgegeven tekencodering


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | opslag | java.io.OutputStream | Niet-nulle byte‑stroom, die schrijven ondersteunt |
|
|  | codering | java.nio.charset.Charset | Niet-nulle tekencodering, die moet worden toegepast bij het schrijven van tekstinhoud naar de gespecificeerde opslag |


TStream
: Elke implementatie van de java.io.InputStream
|

**Returns:**
java.io.OutputStream - Instantie van gespecificeerde opslag

### getBodyContent() {#getBodyContent--}
```
public final String getBodyContent()
```


Retourneert een body van het HTML-document (inhoud tussen de opening en sluiting
BODY‑tags zonder deze tags) als een string.


**Returns:**
java.lang.String - String, die de body van het HTML-document bevat


*** ** * ** ***

WYSIWYG-editors werken met de body van het document en kunnen de meta‑informatie uit het HEAD‑blok niet correct verwerken. Deze methode is ontworpen voor dergelijke gevallen. Deze overload staat niet toe om URI's aan te passen voor verzoeken naar externe bronnen.

<br />


### getBodyContent(String externalImagesTemplate) {#getBodyContent-java.lang.String-}
```
public final String getBodyContent(String externalImagesTemplate)
```


Retourneert een body van het HTML-document (inhoud tussen de opening en sluiting
BODY‑tags zonder deze tags) als een string, waarbij links naar de externe
bronnen de opgegeven prefix bevatten.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | externalImagesTemplate | java.lang.String | Via deze parameter kan een prefix worden opgegeven, die aan de links naar alle externe afbeeldingen in IMG‑elementen wordt toegevoegd en die aanwezig zullen zijn in de resulterende HTML‑string. Als NULL of leeg, worden er geen prefixen toegevoegd. |


*** ** * ** ***

WYSIWYG-editors werken met de body van het document en kunnen de meta‑informatie uit het HEAD‑blok niet correct verwerken. Deze methode is voor dergelijke gevallen ontworpen. Deze overload maakt het mogelijk om URI's voor externe resource‑verzoeken aan te passen.

<br />

|

**Returns:**
java.lang.String - String, die de body van het HTML-document bevat met links, aangepast aan de externe afbeeldingen

### getContent() {#getContent--}
```
public String getContent()
```


Retourneert de volledige inhoud van het HTML-document als een string.


**Returns:**
java.lang.String - String, die de inhoud van het HTML-document bevat

### getContentString(String externalImagesTemplate, String externalCssTemplate) {#getContentString-java.lang.String-java.lang.String-}
```
public String getContentString(String externalImagesTemplate, String externalCssTemplate)
```


Retourneert de volledige inhoud van het HTML-document als een string, waarbij links naar
de externe bronnen de opgegeven prefix bevatten.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | externalImagesTemplate | java.lang.String | Via deze parameter kan een prefix worden opgegeven, die aan de links naar alle externe afbeeldingen in IMG‑elementen wordt toegevoegd en die aanwezig zullen zijn in de resulterende HTML‑string. Als NULL of leeg, worden er geen prefixen toegevoegd. |
|
|  | externalCssTemplate | java.lang.String | Via deze parameter kan een prefix worden opgegeven, die aan de links naar alle externe stylesheets in LINK‑elementen wordt toegevoegd en die aanwezig zullen zijn in de resulterende HTML‑string. Indien NULL of leeg, worden er geen prefixes toegevoegd. |
|

**Returns:**
java.lang.String - String, die de inhoud van het HTML-document bevat met links, aangepast aan de externe resources

### getCssContent() {#getCssContent--}
```
public final List<String> getCssContent()
```


Retourneert de inhoud van alle externe stylesheets als een lijst van strings, waarbij
een string vertegenwoordigt één stylesheet. Retourneert een lege lijst als er geen
CSS voor dit document.


**Returns:**
java.util.List<java.lang.String> - Een lijst van strings, waarbij elke string de inhoud van één CSS‑document bevat

### getCssContent(String externalImagesPrefix, String externalFontsPrefix) {#getCssContent-java.lang.String-java.lang.String-}
```
public final List<String> getCssContent(String externalImagesPrefix, String externalFontsPrefix)
```


Retourneert de inhoud van alle externe stylesheets als een lijst van strings, waarbij
een string vertegenwoordigt één stylesheet. Het opgegeven prefix wordt toegepast op
elke link naar de externe resource in elke resulterende stylesheet.
Retourneert een lege lijst als er geen CSS voor dit document is.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | externalImagesPrefix | java.lang.String | Via deze parameter kan een prefix worden opgegeven, die aan de links naar alle externe afbeeldingen wordt toegevoegd en die aanwezig zullen zijn in CSS‑declaraties in de resulterende CSS‑strings. Indien NULL of leeg, worden er geen prefixes toegevoegd. |
|
|  | externalFontsPrefix | java.lang.String | Via deze parameter kan een prefix worden opgegeven, die aan de links naar alle externe fonts in de |
|

**Returns:**
java.util.List<java.lang.String> - Een lijst van strings, waarbij elke string de inhoud van één CSS‑document bevat

### getEmbeddedHtml() {#getEmbeddedHtml--}
```
public final String getEmbeddedHtml()
```


Retourneert alle inhoud van dit HTML-document met alle gerelateerde bronnen in een
vorm van één enkele string, waarbij alle bronnen zijn ingebed in de HTML
markup in een base64‑gecodeerde vorm.


**Returns:**
java.lang.String - String, die in geen geval NULL of leeg is

### save(String htmlFilePath) {#save-java.lang.String-}
```
public final void save(String htmlFilePath)
```


Slaat dit HTML-document op in het bestand op het opgegeven pad, waar HTML-markup
wordt opgeslagen, en in de bijbehorende map met bronnen.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | htmlFilePath | java.lang.String | Volledig pad naar het bestand waarin de HTML-markup wordt opgeslagen. Het bestand wordt aangemaakt of overschreven als het bestaat. De bijbehorende resource‑map wordt aangemaakt in dezelfde map waar het HTML‑bestand zich bevindt. |
|

### save(String htmlFilePath, String resourcesFolderPath) {#save-java.lang.String-java.lang.String-}
```
public final void save(String htmlFilePath, String resourcesFolderPath)
```


Slaat dit HTML-document op in het bestand op het opgegeven pad, waar HTML-markup
wordt opgeslagen, en in de bijbehorende map met bronnen, die is
geplaatst op het opgegeven pad.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | htmlFilePath | java.lang.String | Volledig pad naar het bestand waarin de HTML-markup wordt opgeslagen. Mag niet NULL of leeg zijn. Het bestand wordt aangemaakt of overschreven als het bestaat. |
|
|  | resourcesFolderPath | java.lang.String | Volledig pad naar de bijbehorende map waarin alle gerelateerde resources worden opgeslagen. Indien NULL of leeg, wordt de map automatisch aangemaakt in dezelfde directory als het \*.html‑bestand. Indien opgegeven en niet bestaand, wordt deze aangemaakt. |
|

### save(Writer htmlMarkup, HtmlSaveOptions saveOptions) {#save-java.io.Writer-com.groupdocs.editor.options.HtmlSaveOptions-}
```
public void save(Writer htmlMarkup, HtmlSaveOptions saveOptions)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| htmlMarkup | java.io.Writer |  |
| saveOptions | [HtmlSaveOptions](../../com.groupdocs.editor.options/htmlsaveoptions) |  |

### fromMarkup(String newHtmlContent, List<IHtmlResource> resources) {#fromMarkup-java.lang.String-java.util.List-com.groupdocs.editor.htmlcss.resources.IHtmlResource--}
```
public static EditableDocument fromMarkup(String newHtmlContent, List<IHtmlResource> resources)
```


Statische fabriek, die een instantie van EditableDocument maakt van
gespecificeerde HTML-markup en een set van bijbehorende gekoppelde bronnen


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | newHtmlContent | java.lang.String | String, die ruwe HTML-markup bevat, die moet worden geparseerd. Mag niet NULL, leeg of ongeldig zijn. |
|
|  | bronnen | java.util.List<com.groupdocs.editor.htmlcss.resources.IHtmlResource> | Collectie van alle bronnen (afbeeldingen, stylesheets, lettertypen), die worden gebruikt in het HTML-document, gespecificeerd in de parameter newHtmlContent. Kan afwezig zijn (NULL of lege collectie). |
|

**Returns:**
[EditableDocument](../../com.groupdocs.editor/editabledocument) - New non-null instance of EditableDocument

### fromMarkupAndResourceFolder(String newHtmlContent, String resourceFolderPath) {#fromMarkupAndResourceFolder-java.lang.String-java.lang.String-}
```
public static EditableDocument fromMarkupAndResourceFolder(String newHtmlContent, String resourceFolderPath)
```


Statische fabriek, die een instantie van EditableDocument maakt van een gespecificeerde HTML-markup en van bronnen, die zich bevinden in de map, gespecificeerd door het volledige pad


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | newHtmlContent | java.lang.String | String, die ruwe HTML-markup bevat, die moet worden geparseerd. Mag niet NULL, leeg of ongeldig zijn. |
|
|  | resourceFolderPath | java.lang.String | Verplichte pad naar de map met bronnen. Alle stylesheets die zich in deze map bevinden, worden gebruikt. Mag niet NULL of een lege string zijn, en deze map moet bestaan. |

<br />

*** ** * ** ***

Deze statische fabriek is handig wanneer de inhoud van een HTML-document wordt gepresenteerd als een string, maar alle bronnen zich in een map bevinden, en vaak zijn links naar deze bronnen in de HTML-markup ongeldig of afwezig. Bij het aanroepen van deze methode scant hij de opgegeven map en past automatisch alle gevonden stylesheets toe op het document. Deze methode is zeer nuttig bij het verkrijgen van inhoud uit verschillende HTML-editors, die meestal de documentmetadata wegsnijden enzovoort.

<br />

|

**Returns:**
[EditableDocument](../../com.groupdocs.editor/editabledocument) - New non-null instance of EditableDocument

### fromFile(String htmlFilePath, String resourceFolderPath) {#fromFile-java.lang.String-java.lang.String-}
```
public static EditableDocument fromFile(String htmlFilePath, String resourceFolderPath)
```


Statische fabriek, die een instantie van EditableDocument maakt van een HTML
bestand, dat wordt gespecificeerd door een pad naar het \\*.html-bestand zelf en een map
met gekoppelde bronnen


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | htmlFilePath | java.lang.String | String, die een volledig pad naar het HTML-bestand bevat. Mag niet null zijn, moet een geldig bestandspad zijn, en het bestand zelf moet bestaan. |
|
|  | resourceFolderPath | java.lang.String | Optioneel pad naar de map met HTML-bronnen. Als NULL, ongeldig of zo'n map niet bestaat, zal de Editor proberen deze map zelf te vinden door de HTML-markup te analyseren. |
|

**Returns:**
[EditableDocument](../../com.groupdocs.editor/editabledocument) - New non-null instance of EditableDocument

### dispose() {#dispose--}
```
public final void dispose()
```


Verwijdert deze Editable-documentinstantie, waarbij de inhoud wordt verwijderd en
waardoor de methoden en eigenschappen niet meer werken


### isDisposed() {#isDisposed--}
```
public final boolean isDisposed()
```


Bepaalt of dit Editable-document al is verwijderd (true) of
niet (false)


**Returns:**
boolean
