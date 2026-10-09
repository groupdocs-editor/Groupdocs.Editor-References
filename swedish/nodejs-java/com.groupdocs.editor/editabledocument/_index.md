---
title: "EditableDocument"
second_title: "GroupDocs.Editor för Node.js via Java API-referens"
description: "Mellanliggande dokument som innehåller innehåll före och efter redigering"
type: docs
weight: 10
url: /sv/nodejs-java/com.groupdocs.editor/editabledocument/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.IAuxDisposable](../../com.groupdocs.editor.htmlcss.resources/iauxdisposable)
```
public final class EditableDocument implements IAuxDisposable
```

Mellanliggande dokument som innehåller innehåll före och efter redigering


*** ** * ** ***

En instans av klassen EditableDocument kan skapas med metoden Editor.edit() eller av användaren själv via statiska fabriker. EditableDocument lagrar internt dokumentet i sitt eget slutna format, vilket är kompatibelt (konverterbart) med alla import‑ och exportformat som stöds av GroupDocs.Editor. För att göra dokumentet redigerbart i någon WYSIWYG‑klient‑side‑editor (som CKEditor eller TinyMCE) tillhandahåller EditableDocument metoder för att generera HTML‑markup och producera resurser som kan accepteras av användaren.

<br />


## Fält

| Fält | Beskrivning |
| --- | --- |
| [Disposed](#Disposed) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getImages()](#getImages--) | Tillåter att hämta externa bildresurser (rasterbilder) som används |
av detta HTML-dokument
|
|  | [getFonts()](#getFonts--) | Tillåter att hämta externa teckensnittresurser som används av detta HTML |
dokument
|
|  | [getCss()](#getCss--) | Returnerar en lista med CSS‑resurser |
|
|  | [getAudio()](#getAudio--) | Returnerar en lista med ljudresurser |
|
|  | [getAllResources()](#getAllResources--) | Returnerar en lista med alla befintliga resurser: alla stilmallar, bilder från |
HTML och alla stilmallar, teckensnitt
|
|  | [getContent(OutputStream storage, Charset encoding)](#getContent-java.io.OutputStream-java.nio.charset.Charset-) | Returnerar det totala innehållet i HTML-dokumentet som en byte‑ström genom att skriva detta innehåll till den angivna strömmen med angiven textkodning |
|
|  | [getBodyContent()](#getBodyContent--) | Returnerar en kropp av HTML-dokumentet (innehåll mellan öppnings- och stängnings |
BODY‑taggar utan dessa taggar) som en sträng.
|
|  | [getBodyContent(String externalImagesTemplate)](#getBodyContent-java.lang.String-) | Returnerar en kropp av HTML-dokumentet (innehåll mellan öppnings- och stängnings |
BODY‑taggar utan dessa taggar) som en sträng, där länkar till den externa
resurser innehåller angivet prefix.
|
|  | [getContent()](#getContent--) | Returnerar hela innehållet i HTML-dokumentet som en sträng. |
|
|  | [getContentString(String externalImagesTemplate, String externalCssTemplate)](#getContentString-java.lang.String-java.lang.String-) | Returnerar hela innehållet i HTML-dokumentet som en sträng, där länkar till |
de externa resurserna innehåller angivet prefix.
|
|  | [getCssContent()](#getCssContent--) | Returnerar innehållet i alla externa stilmallar som en lista av strängar, där |
en sträng representerar en stilmall.
|
|  | [getCssContent(String externalImagesPrefix, String externalFontsPrefix)](#getCssContent-java.lang.String-java.lang.String-) | Returnerar innehållet i alla externa stilmallar som en lista av strängar, där |
en sträng representerar en stilmall.
|
|  | [getEmbeddedHtml()](#getEmbeddedHtml--) | Returnerar allt innehåll i detta HTML-dokument med alla relaterade resurser i en |
form av en enda sträng, där alla resurser är inbäddade i HTML-markup
markup i en base64-kodad form.
|
|  | [save(String htmlFilePath)](#save-java.lang.String-) | Sparar detta HTML-dokument till filen på angiven sökväg, där HTML-markup |
kommer att lagras, och till den medföljande mappen med resurser.
|
|  | [save(String htmlFilePath, String resourcesFolderPath)](#save-java.lang.String-java.lang.String-) | Sparar detta HTML-dokument till filen på angiven sökväg, där HTML-markup |
kommer att lagras, och till den medföljande mappen med resurser, som är
placerad på angiven sökväg.
|
| [save(Writer htmlMarkup, HtmlSaveOptions saveOptions)](#save-java.io.Writer-com.groupdocs.editor.options.HtmlSaveOptions-) |  |
|  | [fromMarkup(String newHtmlContent, List<IHtmlResource> resources)](#fromMarkup-java.lang.String-java.util.List-com.groupdocs.editor.htmlcss.resources.IHtmlResource--) | Statisk fabrik, som skapar en instans av EditableDocument från |
angiven HTML-markup och en uppsättning motsvarande länkade resurser
|
|  | [fromMarkupAndResourceFolder(String newHtmlContent, String resourceFolderPath)](#fromMarkupAndResourceFolder-java.lang.String-java.lang.String-) | Statisk fabrik, som skapar en instans av EditableDocument från en angiven HTML-markup och från resurser, placerade i mappen, specificerad av den fullständiga sökvägen |
|
|  | [fromFile(String htmlFilePath, String resourceFolderPath)](#fromFile-java.lang.String-java.lang.String-) | Statisk fabrik, som skapar en instans av EditableDocument från en HTML |
fil, som är specificerad av en sökväg till själva \*.html-filen och en mapp
med länkade resurser
|
|  | [dispose()](#dispose--) | Avslutar denna Editable-dokumentinstans, avslutar dess innehåll och |
gör dess metoder och egenskaper icke-fungerande
|
|  | [isDisposed()](#isDisposed--) | Bestämmer om detta Editable-dokument redan har avslutats (true) eller |
inte (false)
|
### Disposed {#Disposed}
```
public final Event<EventHandler> Disposed
```


### getImages() {#getImages--}
```
public final List<IImageResource> getImages()
```


Tillåter att hämta externa bildresurser (rasterbilder) som används
av detta HTML-dokument


**Returns:**
java.util.List<com.groupdocs.editor.htmlcss.resources.images.IImageResource>
### getFonts() {#getFonts--}
```
public final List<FontResourceBase> getFonts()
```


Tillåter att hämta externa teckensnittresurser som används av detta HTML
dokument


**Returns:**
java.util.List<com.groupdocs.editor.htmlcss.resources.fonts.FontResourceBase>
### getCss() {#getCss--}
```
public final List<CssText> getCss()
```


Returnerar en lista med CSS‑resurser


**Returns:**
java.util.List<com.groupdocs.editor.htmlcss.resources.textual.CssText>
### getAudio() {#getAudio--}
```
public final List<Mp3Audio> getAudio()
```


Returnerar en lista med ljudresurser


**Returns:**
java.util.List<com.groupdocs.editor.htmlcss.resources.audio.Mp3Audio>
### getAllResources() {#getAllResources--}
```
public final List<IHtmlResource> getAllResources()
```


Returnerar en lista med alla befintliga resurser: alla stilmallar, bilder från
HTML och alla stilmallar, teckensnitt


*** ** * ** ***

Denna egenskap returnerar ett sammanfogat resultat av egenskaperna 'Images', 'Fonts' och 'Css'.

<br />



**Returns:**
java.util.List<com.groupdocs.editor.htmlcss.resources.IHtmlResource>
### getContent(OutputStream storage, Charset encoding) {#getContent-java.io.OutputStream-java.nio.charset.Charset-}
```
public OutputStream getContent(OutputStream storage, Charset encoding)
```


Returnerar det totala innehållet i HTML-dokumentet som en byte‑ström genom att skriva detta innehåll till den angivna strömmen med angiven textkodning


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | lagring | java.io.OutputStream | Icke-null byte-ström som stöder skrivning |
|
|  | kodning | java.nio.charset.Charset | Icke-null textkodning som bör tillämpas vid skrivning av textinnehåll till angiven lagring |


TStream
: Valfri implementation av java.io.InputStream
|

**Returns:**
java.io.OutputStream - Instans av angiven lagring

### getBodyContent() {#getBodyContent--}
```
public final String getBodyContent()
```


Returnerar en kropp av HTML-dokumentet (innehåll mellan öppnings- och stängnings
BODY‑taggar utan dessa taggar) som en sträng.


**Returns:**
java.lang.String - Sträng som innehåller kroppen i HTML-dokumentet


*** ** * ** ***

WYSIWYG-redigerare arbetar med dokumentets kropp och kan inte korrekt bearbeta dess meta-information från HEAD-blocket. Denna metod är avsedd för sådana fall. Denna överlagring tillåter inte att justera URI:er för externa resursförfrågningar.

<br />


### getBodyContent(String externalImagesTemplate) {#getBodyContent-java.lang.String-}
```
public final String getBodyContent(String externalImagesTemplate)
```


Returnerar en kropp av HTML-dokumentet (innehåll mellan öppnings- och stängnings
BODY‑taggar utan dessa taggar) som en sträng, där länkar till den externa
resurser innehåller angivet prefix.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | externalImagesTemplate | java.lang.String | Genom denna parameter kan du ange ett prefix som kommer att läggas till länkarna till alla externa bilder i IMG-element, som kommer att finnas i den resulterande HTML-strängen. Om NULL eller tomt kommer prefix inte att läggas till. |


*** ** * ** ***

WYSIWYG-redigerare arbetar med dokumentets kropp och kan inte korrekt bearbeta dess meta-information från HEAD-blocket. Denna metod är avsedd för sådana fall. Denna överlagring tillåter att justera URI:er för externa resursförfrågningar.

<br />

|

**Returns:**
java.lang.String - Sträng som innehåller kroppen i HTML-dokumentet med länkar, justerade för de externa bilderna

### getContent() {#getContent--}
```
public String getContent()
```


Returnerar hela innehållet i HTML-dokumentet som en sträng.


**Returns:**
java.lang.String - Sträng som innehåller innehållet i HTML-dokumentet

### getContentString(String externalImagesTemplate, String externalCssTemplate) {#getContentString-java.lang.String-java.lang.String-}
```
public String getContentString(String externalImagesTemplate, String externalCssTemplate)
```


Returnerar hela innehållet i HTML-dokumentet som en sträng, där länkar till
de externa resurserna innehåller angivet prefix.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | externalImagesTemplate | java.lang.String | Genom denna parameter kan du ange ett prefix som kommer att läggas till länkarna till alla externa bilder i IMG-element, som kommer att finnas i den resulterande HTML-strängen. Om NULL eller tomt kommer prefix inte att läggas till. |
|
|  | externalCssTemplate | java.lang.String | Genom denna parameter kan du ange ett prefix som kommer att läggas till länkarna till alla externa stilmallar i LINK-element, som kommer att finnas i den resulterande HTML-strängen. Om NULL eller tomt kommer prefix inte att läggas till. |
|

**Returns:**
java.lang.String - Sträng som innehåller innehållet i HTML-dokumentet med länkar, justerade för de externa resurserna

### getCssContent() {#getCssContent--}
```
public final List<String> getCssContent()
```


Returnerar innehållet i alla externa stilmallar som en lista av strängar, där
en sträng representerar en stilmall. Returnerar en tom lista om det inte finns någon
CSS för detta dokument.


**Returns:**
java.util.List<java.lang.String> - En lista med strängar, där varje sträng innehåller innehållet i ett CSS-dokument

### getCssContent(String externalImagesPrefix, String externalFontsPrefix) {#getCssContent-java.lang.String-java.lang.String-}
```
public final List<String> getCssContent(String externalImagesPrefix, String externalFontsPrefix)
```


Returnerar innehållet i alla externa stilmallar som en lista av strängar, där
en sträng representerar en stilmall. Angivet prefix kommer att tillämpas på
varje länk till den externa resursen i varje resulterande stilmall.
Returnerar en tom lista om det inte finns någon CSS för detta dokument.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | externalImagesPrefix | java.lang.String | Genom den här parametern kan du ange ett prefix som kommer att läggas till länkarna till alla externa bilder som finns i CSS‑deklarationer i de resulterande CSS‑strängarna. Om NULL eller tomt kommer prefix inte att läggas till. |
|
|  | externalFontsPrefix | java.lang.String | Genom den här parametern kan du ange ett prefix som kommer att läggas till länkarna till alla externa typsnitt i |
|

**Returns:**
java.util.List<java.lang.String> - En lista med strängar, där varje sträng innehåller innehållet i ett CSS-dokument

### getEmbeddedHtml() {#getEmbeddedHtml--}
```
public final String getEmbeddedHtml()
```


Returnerar allt innehåll i detta HTML-dokument med alla relaterade resurser i en
form av en enda sträng, där alla resurser är inbäddade i HTML-markup
markup i en base64-kodad form.


**Returns:**
java.lang.String - Sträng, som inte är NULL eller tom i något fall

### save(String htmlFilePath) {#save-java.lang.String-}
```
public final void save(String htmlFilePath)
```


Sparar detta HTML-dokument till filen på angiven sökväg, där HTML-markup
kommer att lagras, och till den medföljande mappen med resurser.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | htmlFilePath | java.lang.String | Fullständig sökväg till filen där HTML‑markup kommer att lagras. Filen kommer att skapas eller skrivas över om den finns. Tillhörande resursmapp kommer att skapas i samma mapp där HTML‑filen finns. |
|

### save(String htmlFilePath, String resourcesFolderPath) {#save-java.lang.String-java.lang.String-}
```
public final void save(String htmlFilePath, String resourcesFolderPath)
```


Sparar detta HTML-dokument till filen på angiven sökväg, där HTML-markup
kommer att lagras, och till den medföljande mappen med resurser, som är
placerad på angiven sökväg.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | htmlFilePath | java.lang.String | Fullständig sökväg till filen där HTML‑markup kommer att lagras. Får inte vara NULL eller tom. Filen kommer att skapas eller skrivas över om den finns. |
|
|  | resourcesFolderPath | java.lang.String | Fullständig sökväg till den medföljande mappen där alla relaterade resurser kommer att lagras. Om NULL eller tom kommer mappen att skapas automatiskt i samma katalog där \\*.html‑filen finns. Om den anges och inte finns, kommer den att skapas. |
|

### save(Writer htmlMarkup, HtmlSaveOptions saveOptions) {#save-java.io.Writer-com.groupdocs.editor.options.HtmlSaveOptions-}
```
public void save(Writer htmlMarkup, HtmlSaveOptions saveOptions)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| htmlMarkup | java.io.Writer |  |
| saveOptions | [HtmlSaveOptions](../../com.groupdocs.editor.options/htmlsaveoptions) |  |

### fromMarkup(String newHtmlContent, List<IHtmlResource> resources) {#fromMarkup-java.lang.String-java.util.List-com.groupdocs.editor.htmlcss.resources.IHtmlResource--}
```
public static EditableDocument fromMarkup(String newHtmlContent, List<IHtmlResource> resources)
```


Statisk fabrik, som skapar en instans av EditableDocument från
angiven HTML-markup och en uppsättning motsvarande länkade resurser


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | newHtmlContent | java.lang.String | Sträng som innehåller rå HTML‑markup som ska parsas. Får inte vara NULL, tom eller ogiltig. |
|
|  | resources | java.util.List<com.groupdocs.editor.htmlcss.resources.IHtmlResource> | Samling av alla resurser (bilder, stilmallar, typsnitt) som används i HTML‑dokumentet, specificerade i parametern  newHtmlContent . Kan vara frånvarande (NULL eller tom samling). |
|

**Returns:**
[EditableDocument](../../com.groupdocs.editor/editabledocument) - New non-null instance of EditableDocument

### fromMarkupAndResourceFolder(String newHtmlContent, String resourceFolderPath) {#fromMarkupAndResourceFolder-java.lang.String-java.lang.String-}
```
public static EditableDocument fromMarkupAndResourceFolder(String newHtmlContent, String resourceFolderPath)
```


Statisk fabrik, som skapar en instans av EditableDocument från en angiven HTML-markup och från resurser, placerade i mappen, specificerad av den fullständiga sökvägen


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | newHtmlContent | java.lang.String | Sträng som innehåller rå HTML‑markup som ska parsas. Får inte vara NULL, tom eller ogiltig. |
|
|  | resourceFolderPath | java.lang.String | Obligatorisk sökväg till mappen med resurser. Alla stilmallar som finns i denna mapp kommer att användas. Får inte vara NULL eller en tom sträng, och mappen måste finnas. |

<br />

*** ** * ** ***

Denna statiska fabrik är användbar när innehållet i ett HTML‑dokument presenteras som en sträng, men alla resurser finns i en mapp och länkarna till dessa resurser i HTML‑markup ofta är ogiltiga eller saknas. Vid anrop av metoden skannas den angivna mappen och alla hittade stilmallar appliceras automatiskt på dokumentet. Metoden är mycket användbar när man hämtar innehåll från olika HTML‑redigerare, som vanligtvis klipper bort dokumentets metadata med mera.

<br />

|

**Returns:**
[EditableDocument](../../com.groupdocs.editor/editabledocument) - New non-null instance of EditableDocument

### fromFile(String htmlFilePath, String resourceFolderPath) {#fromFile-java.lang.String-java.lang.String-}
```
public static EditableDocument fromFile(String htmlFilePath, String resourceFolderPath)
```


Statisk fabrik, som skapar en instans av EditableDocument från en HTML
fil, som är specificerad av en sökväg till själva \*.html-filen och en mapp
med länkade resurser


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | htmlFilePath | java.lang.String | Sträng som innehåller en fullständig sökväg till HTML‑filen. Får inte vara null, bör vara en giltig filsökväg och filen själv måste finnas. |
|
|  | resourceFolderPath | java.lang.String | Valfri sökväg till mappen med HTML‑resurser. Om NULL, ogiltig eller om en sådan mapp inte finns, kommer redigeraren att försöka hitta denna mapp själv genom att analysera HTML‑markup. |
|

**Returns:**
[EditableDocument](../../com.groupdocs.editor/editabledocument) - New non-null instance of EditableDocument

### dispose() {#dispose--}
```
public final void dispose()
```


Avslutar denna Editable-dokumentinstans, avslutar dess innehåll och
gör dess metoder och egenskaper icke-fungerande


### isDisposed() {#isDisposed--}
```
public final boolean isDisposed()
```


Bestämmer om detta Editable-dokument redan har avslutats (true) eller
inte (false)


**Returns:**
boolean
