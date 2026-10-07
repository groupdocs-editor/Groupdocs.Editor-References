---
title: "FontEmbeddingOptions"
second_title: "GroupDocs.Editor för Java API-referens"
description: "Font‑inbäddningsalternativ styr vilka teckensnittresurser som ska bäddas in i det utgående WordProcessing‑dokumentet"
type: docs
weight: 17
url: /sv/java/com.groupdocs.editor.options/fontembeddingoptions/
---
**Inheritance:**
java.lang.Object
```
public final class FontEmbeddingOptions
```

Font‑inbäddningsalternativ styr vilka teckensnittresurser som ska bäddas in i
det utgående WordProcessing‑dokumentet


*** ** * ** ***

Font‑inbäddningsalternativ tillämpas under dokumentets sparande (från mellansteg EditableDocument till utgående WordProcessing‑format), detta enum inkluderas som en egenskap i WordProcessingSaveOptions, varifrån det ska användas

<br />


## Fält

| Fält | Beskrivning |
| --- | --- |
|  | [NotEmbed](#NotEmbed) | Bädda inte in någon teckensnittresurs vare sig från EditableDocument eller från |
systemet.
|
|  | [EmbedAll](#EmbedAll) | Analysera dokumentets innehåll från inmatnings‑EditableDocument, hitta alla använda teckensnitt |
och bädda in dem i det utgående WordProcessing‑dokumentet.
|
|  | [EmbedWithoutSystem](#EmbedWithoutSystem) | Exakt som [EmbedAll](../../com.groupdocs.editor.options/fontembeddingoptions#EmbedAll), men exkludera de teckensnitt, |
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


Bädda inte in någon teckensnittresurs vare sig från EditableDocument eller från
system. Standardvärde.


### EmbedAll {#EmbedAll}
```
public static final int EmbedAll
```


Analysera dokumentets innehåll från inmatnings‑EditableDocument, hitta alla använda teckensnitt
och bädda in dem i det utgående WordProcessing‑dokumentet. I första hand
GroupDocs.Editor hämtar teckensnitt från teckensnittresurser inom EditableDocument.
Om de är otillräckliga eller saknas, tar GroupDocs.Editor teckensnitt
från OS.


*** ** * ** ***

Först analyserar GroupDocs.Editor innehållet i EditableDocument och skapar en lista över alla använda teckensnitt. Därefter söks dessa teckensnitt i teckensnittresurserna i EditableDocument. Om EditableDocument innehåller vissa teckensnittresurser som inte är involverade i dokumentets innehåll, ignoreras sådana resurser. Om det finns teckensnitt som används i dokumentets innehåll men som saknar motsvarande teckensnittresurser i EditableDocument, försöker GroupDocs.Editor hitta dem i OS. Detta alternativ liknar alternativet "Bädda in teckensnitt i filen" med alla underalternativ avstängda i Microsoft Word 2007 och senare.

<br />



### EmbedWithoutSystem {#EmbedWithoutSystem}
```
public static final int EmbedWithoutSystem
```


Exakt som [EmbedAll](../../com.groupdocs.editor.options/fontembeddingoptions#EmbedAll), men exkludera de teckensnitt,
som behandlas av OS som systemteckensnitt


*** ** * ** ***

MS Windows har ett koncept av systemteckensnitt, som är de mest grundläggande och använda teckensnitten av Windows själv. När detta alternativ används agerar GroupDocs.Editor som för [EmbedAll](../../com.groupdocs.editor.options/fontembeddingoptions#EmbedAll)-fallet, men granskar slutligen en uppsättning erhållna teckensnitt och exkluderar de som behandlas av OS som systemteckensnitt. Detta alternativ liknar alternativen "Bädda in teckensnitt i filen" + "Bädda inte in vanliga systemteckensnitt" i Microsoft Word 2007 och senare

<br />



### getFontEmbeddingOptions() {#getFontEmbeddingOptions--}
```
public static int[] getFontEmbeddingOptions()
```




**Returns:**
int[]
