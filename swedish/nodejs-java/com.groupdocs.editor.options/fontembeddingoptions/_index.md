---
title: "FontEmbeddingOptions"
second_title: "GroupDocs.Editor för Node.js via Java API-referens"
description: "Alternativ för teckensnittsinbäddning styr vilka teckensnittresurser som ska bäddas in i utdata‑WordProcessing‑dokumentet"
type: docs
weight: 17
url: /sv/nodejs-java/com.groupdocs.editor.options/fontembeddingoptions/
---
**Inheritance:**
java.lang.Object
```
public final class FontEmbeddingOptions
```

Alternativ för teckensnittsinbäddning styr vilka teckensnittresurser som ska bäddas in i
utdata‑WordProcessing‑dokumentet


*** ** * ** ***

Alternativ för teckensnittsinbäddning tillämpas under dokumentlagring (från mellansteg‑EditableDocument till utdata‑WordProcessing‑format), denna enum inkluderas som en egenskap i WordProcessingSaveOptions, varifrån den bör användas

<br />


## Fält

| Fält | Beskrivning |
| --- | --- |
|  | [NotEmbed](#NotEmbed) | Bädda inte in någon teckensnittresurs varken från EditableDocument eller från |
systemet.
|
|  | [EmbedAll](#EmbedAll) | Analysera dokumentinnehåll från inmatnings‑EditableDocument, hitta alla använda teckensnitt |
och bädda in dem i utdata‑WordProcessing‑dokumentet.
|
|  | [EmbedWithoutSystem](#EmbedWithoutSystem) | Exakt som [EmbedAll](../../com.groupdocs.editor.options/fontembeddingoptions#EmbedAll), men uteslut de teckensnitten, |
som behandlas av OS som systemteckensnitt
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getFontEmbeddingOptions()](#getFontEmbeddingOptions--) |  |
### NotEmbed {#NotEmbed}
```
public static final int NotEmbed
```


Bädda inte in någon teckensnittresurs varken från EditableDocument eller från
system. Standardvärde.


### EmbedAll {#EmbedAll}
```
public static final int EmbedAll
```


Analysera dokumentinnehåll från inmatnings‑EditableDocument, hitta alla använda teckensnitt
och bädda in dem i utdata WordProcessing-dokumentet. Till att börja med
GroupDocs.Editor hämtar teckensnitt från teckensnittresurser inom EditableDocument.
Om de är otillräckliga eller saknas, tar GroupDocs.Editor teckensnitt
från OS.


*** ** * ** ***

Först analyserar GroupDocs.Editor innehållet i EditableDocument och skapar en lista över alla använda teckensnitt. Därefter söks dessa teckensnitt i teckensnittresurserna i EditableDocument. Om EditableDocument innehåller vissa teckensnittresurser som inte är involverade i dokumentets innehåll, ignoreras sådana resurser. Om det finns teckensnitt som används i dokumentets innehåll men som saknar motsvarande teckensnittresurser i EditableDocument, försöker GroupDocs.Editor hitta dem i OS. Detta alternativ liknar alternativet "Embed fonts in the file" med alla underalternativ avstängda i Microsoft Word 2007 och senare.

<br />



### EmbedWithoutSystem {#EmbedWithoutSystem}
```
public static final int EmbedWithoutSystem
```


Exakt som [EmbedAll](../../com.groupdocs.editor.options/fontembeddingoptions#EmbedAll), men uteslut de teckensnitten,
som behandlas av OS som systemteckensnitt


*** ** * ** ***

MS Windows har ett koncept för systemteckensnitt, som är de mest grundläggande och använda teckensnitten av Windows själv. När detta alternativ används agerar GroupDocs.Editor som i fallet [EmbedAll](../../com.groupdocs.editor.options/fontembeddingoptions#EmbedAll), men granskar slutligen en uppsättning erhållna teckensnitt och utesluter de som behandlas av OS som systemteckensnitt. Detta alternativ liknar alternativen "Embed fonts in the file" + "Do not embed common system fonts" i Microsoft Word 2007 och senare

<br />



### getFontEmbeddingOptions() {#getFontEmbeddingOptions--}
```
public static int[] getFontEmbeddingOptions()
```




**Returns:**
int[]
