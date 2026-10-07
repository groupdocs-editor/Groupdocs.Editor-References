---
title: "FontExtractionOptions"
second_title: "GroupDocs.Editor för Java API-referens"
description: "Inställningarna för teckensnittsextraktion styr vilka teckensnitt som ska extraheras och varifrån"
type: docs
weight: 18
url: /sv/java/com.groupdocs.editor.options/fontextractionoptions/
---
**Inheritance:**
java.lang.Object
```
public final class FontExtractionOptions
```

Inställningarna för teckensnittsextraktion styr vilka teckensnitt som ska extraheras och från
var

## Fält

| Fält | Beskrivning |
| --- | --- |
|  | [NotExtract](#NotExtract) | Extraherar inte någon teckensnittresurs varken från dokumentet eller från |
systemet.
|
|  | [ExtractAllEmbedded](#ExtractAllEmbedded) | Extraherar alla teckensnittresurser som är inbäddade i den angivna Word |
dokumentet, oavsett vad de är: anpassade eller system.
|
|  | [ExtractEmbeddedWithoutSystem](#ExtractEmbeddedWithoutSystem) | Extraherar endast de inbäddade teckensnittresurserna som är anpassade (inte |
system)
|
|  | [ExtractAll](#ExtractAll) | Försöker extrahera alla teckensnitt som används i den angivna WordProcessing |
dokumentet, inklusive systemteckensnitt.
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getFontExtractionOptions()](#getFontExtractionOptions--) |  |
### NotExtract {#NotExtract}
```
public static final int NotExtract
```


Extraherar inte någon teckensnittresurs varken från dokumentet eller från
system. Standardvärde.


### ExtractAllEmbedded {#ExtractAllEmbedded}
```
public static final int ExtractAllEmbedded
```


Extraherar alla teckensnittresurser som är inbäddade i den angivna Word
dokumentet, oavsett vad de är: anpassade eller system.


*** ** * ** ***

Konverteraren hittar och extraherar alla 100 % teckensnittresurser som är inbäddade i det angivna WordProcessing-dokumentet, men den avgör inte om de är system- eller anpassade; den rör inte Windows-registret eller systemmapparna alls.

<br />



### ExtractEmbeddedWithoutSystem {#ExtractEmbeddedWithoutSystem}
```
public static final int ExtractEmbeddedWithoutSystem
```


Extraherar endast de inbäddade teckensnittresurserna som är anpassade (inte
system)


*** ** * ** ***

Konverteraren hittar och extraherar alla inbäddade teckensnittresurser och försöker sedan avgöra vilka av dessa teckensnitt som är system och vilka som inte är det. För att uppnå detta försöker konverteraren hämta en lista över alla systemteckensnitt genom att använda Windows-registret och systemmapparna och jämför sedan denna lista med en uppsättning inbäddade teckensnitt. Som resultat returneras endast den del av de inbäddade teckensnitten som inte hittades i systemet.

<br />



### ExtractAll {#ExtractAll}
```
public static final int ExtractAll
```


Försöker extrahera alla teckensnitt som används i den angivna WordProcessing
dokumentet, inklusive systemteckensnitt.


*** ** * ** ***

Konverteraren analyserar ett WordProcessing-dokument och hittar alla teckensnitt som används där. Om alla dessa teckensnitt är inbäddade i det angivna dokumentet extraherar och returnerar konverteraren dem. Om en samling inbäddade teckensnitt däremot inte täcker alla använda teckensnitt i dokumentet, eller är tom, försöker konverteraren extrahera dessa teckensnittresurser från systemet genom att använda Windows-registret och systemmapparna.

<br />



### getFontExtractionOptions() {#getFontExtractionOptions--}
```
public static int[] getFontExtractionOptions()
```




**Returns:**
int[]
