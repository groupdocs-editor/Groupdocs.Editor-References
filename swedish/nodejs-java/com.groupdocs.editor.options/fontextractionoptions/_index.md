---
title: "FontExtractionOptions"
second_title: "GroupDocs.Editor för Node.js via Java API-referens"
description: "Alternativ för teckensnittsextraktion styr vilka teckensnitt som ska extraheras och från var."
type: docs
weight: 18
url: /sv/nodejs-java/com.groupdocs.editor.options/fontextractionoptions/
---
**Inheritance:**
java.lang.Object
```
public final class FontExtractionOptions
```

Alternativ för teckensnittsextraktion styr vilka teckensnitt som ska extraheras och från
var

## Fält

| Fält | Beskrivning |
| --- | --- |
|  | [NotExtract](#NotExtract) | Extraherar inte någon teckensnittresurs varken från dokumentet eller från den |
systemet.
|
|  | [ExtractAllEmbedded](#ExtractAllEmbedded) | Extraherar alla teckensnittresurser som är inbäddade i den inmatade Word |
dokumentet, oavsett vad de är: anpassade eller system.
|
|  | [ExtractEmbeddedWithoutSystem](#ExtractEmbeddedWithoutSystem) | Extraherar endast de inbäddade teckensnittresurserna som är anpassade (inte |
system)
|
|  | [ExtractAll](#ExtractAll) | Försöker extrahera alla teckensnitt som används i den inmatade WordProcessing |
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


Extraherar inte någon teckensnittresurs varken från dokumentet eller från den
system. Standardvärde.


### ExtractAllEmbedded {#ExtractAllEmbedded}
```
public static final int ExtractAllEmbedded
```


Extraherar alla teckensnittresurser som är inbäddade i den inmatade Word
dokumentet, oavsett vad de är: anpassade eller system.


*** ** * ** ***

Converter hittar och extraherar alla 100 % teckensnittresurser som är inbäddade i det inmatade WordProcessing-dokumentet, men den avgör inte om de är system eller anpassade; den rör inte Windows-registret eller systemmapparna alls.

<br />



### ExtractEmbeddedWithoutSystem {#ExtractEmbeddedWithoutSystem}
```
public static final int ExtractEmbeddedWithoutSystem
```


Extraherar endast de inbäddade teckensnittresurserna som är anpassade (inte
system)


*** ** * ** ***

Converter hittar och extraherar alla inbäddade teckensnittresurser och försöker sedan avgöra vilka av dessa teckensnitt som är system och vilka som inte är det. För att uppnå detta försöker konverteraren hämta en lista över alla systemteckensnitt genom att använda Windows-registret och systemmappar, och jämför sedan denna lista med en uppsättning inbäddade teckensnitt. Som resultat returneras endast den delmängd av de inbäddade teckensnitten som inte hittades i systemet.

<br />



### ExtractAll {#ExtractAll}
```
public static final int ExtractAll
```


Försöker extrahera alla teckensnitt som används i den inmatade WordProcessing
dokumentet, inklusive systemteckensnitt.


*** ** * ** ***

Converter analyserar ett inmatat WordProcessing-dokument och hittar alla teckensnitt som används där. Om alla dessa teckensnitt är inbäddade i inmatningsdokumentet extraherar och returnerar konverteraren dem. Annars, om en samling inbäddade teckensnitt inte täcker alla använda teckensnitt i dokumentet, eller är tom, försöker konverteraren extrahera dessa teckensnittresurser från systemet genom att använda Windows-registret och systemmappar.

<br />



### getFontExtractionOptions() {#getFontExtractionOptions--}
```
public static int[] getFontExtractionOptions()
```




**Returns:**
int[]
