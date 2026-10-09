---
title: "WordProcessingSaveOptions"
second_title: "GroupDocs.Editor för Node.js via Java API-referens"
description: "Tillåter att ange anpassade alternativ för att generera och spara WordProcessing‑kompatibla dokument efter att de har redigerats"
type: docs
weight: 48
url: /sv/nodejs-java/com.groupdocs.editor.options/wordprocessingsaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class WordProcessingSaveOptions implements ISaveOptions
```

Tillåter att ange anpassade alternativ för att generera och spara
WordProcessing‑kompatibla dokument efter att de har redigerats


*** ** * ** ***

WordProcessingSaveOptions används i situationer där det finns en instans av klassen EditableDocument som innehåller redigerat dokumentinnehåll, och det krävs att detta innehåll sparas till ett nytt dokument i WordProcessing‑format.

<br />


## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
|  | [WordProcessingSaveOptions()](#WordProcessingSaveOptions--) | Denna parameterlösa konstruktor skapar en ny instans av WordProcessingSaveOptions med DOCX‑utdataformat (kan sedan ändras via |
OutputFormat
(#getOutputFormat.getOutputFormat/#setOutputFormat(WordProcessingFormats).setOutputFormat(WordProcessingFormats)) property)
|
|  | [WordProcessingSaveOptions(WordProcessingFormats outputFormat)](#WordProcessingSaveOptions-com.groupdocs.editor.formats.WordProcessingFormats-) | Skapar en ny instans av WordProcessingSaveOptions med angivet |
obligatoriskt WordProcessing‑utdataformat, medan alla andra parametrar är
standard
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getEnablePagination()](#getEnablePagination--) | Tillåter att aktivera eller inaktivera paginering som kommer att användas för att spara |
dokumentet.
|
|  | [setEnablePagination(boolean value)](#setEnablePagination-boolean-) | Tillåter att aktivera eller inaktivera paginering som kommer att användas för att spara |
dokumentet.
|
|  | [getPassword()](#getPassword--) | Tillåter att ange, ändra, hämta eller ta bort ett lösenord som kommer att |
används för att koda det genererade WordProcessing dokumentet.
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Tillåter att ange, ändra, hämta eller ta bort ett lösenord som kommer att |
används för att koda det genererade WordProcessing dokumentet.
|
|  | [getOutputFormat()](#getOutputFormat--) | Tillåter att ange ett WordProcessing-format som kommer att användas för att spara |
dokumentet
|
|  | [setOutputFormat(WordProcessingFormats value)](#setOutputFormat-com.groupdocs.editor.formats.WordProcessingFormats-) | Tillåter att ange ett WordProcessing-format som kommer att användas för att spara |
dokumentet
|
|  | [getLocale()](#getLocale--) | Tillåter att ange en överskrivning av standardlokal (språk) för WordProcessing |
dokument, som kommer att tillämpas under dess skapande.
|
|  | [setLocale(Locale value)](#setLocale-java.util.Locale-) | Tillåter att ange en överskrivning av standardlokal (språk) för WordProcessing |
dokument, som kommer att tillämpas under dess skapande.
|
|  | [getLocaleBi()](#getLocaleBi--) | Tillåter att ange en överskrivning av lokal (språk) för WordProcessing dokumentet |
för RTL (right-to-left) text, som kommer att tillämpas under dess
skapande.
|
|  | [setLocaleBi(Locale value)](#setLocaleBi-java.util.Locale-) | Tillåter att ange en överskrivning av lokal (språk) för WordProcessing dokumentet |
för RTL (right-to-left) text, som kommer att tillämpas under dess
skapande.
|
|  | [getLocaleFarEast()](#getLocaleFarEast--) | Tillåter att överskriva lokal (språk) för WordProcessing dokumentet |
för den östasiatiska texten, som kommer att tillämpas under dess skapande.
|
|  | [setLocaleFarEast(Locale value)](#setLocaleFarEast-java.util.Locale-) | Tillåter att överskriva lokal (språk) för WordProcessing dokumentet |
för den östasiatiska texten, som kommer att tillämpas under dess skapande.
|
|  | [getOptimizeMemoryUsage()](#getOptimizeMemoryUsage--) | Aktiverar minnesoptimeringsmekanismer under dokumentgenerering från |
HTML, vilket försämrar prestanda som en kostnad för minskat minnesanvändning.
|
|  | [setOptimizeMemoryUsage(boolean value)](#setOptimizeMemoryUsage-boolean-) | Aktiverar minnesoptimeringsmekanismer under dokumentgenerering från |
HTML, vilket försämrar prestanda som en kostnad för minskat minnesanvändning.
|
|  | [getProtection()](#getProtection--) | Tillåter att styra och tillämpa dokumentskyddsalternativen för |
WordProcessing dokument av vilket format som helst, som stödjer dokument
skydd.
|
|  | [setProtection(WordProcessingProtection value)](#setProtection-com.groupdocs.editor.options.WordProcessingProtection-) | Tillåter att styra och tillämpa dokumentskyddsalternativen för |
WordProcessing dokument av vilket format som helst, som stödjer dokument
skydd.
|
|  | [getFontEmbedding()](#getFontEmbedding--) | Ansvarig för att bädda in teckensnittresurser i utdata WordProcessing |
dokumentet.
|
|  | [setFontEmbedding(int value)](#setFontEmbedding-int-) | Ansvarig för att bädda in teckensnittresurser i utdata WordProcessing |
dokumentet.
|
|  | [deepClone()](#deepClone--) | Skapar och returnerar en fullständig kopia av denna instans av |
WordProcessingSaveOptions-klass
|
### WordProcessingSaveOptions() {#WordProcessingSaveOptions--}
```
public WordProcessingSaveOptions()
```


Denna parameterlösa konstruktor skapar en ny instans av WordProcessingSaveOptions med DOCX‑utdataformat (kan sedan ändras via
OutputFormat
(#getOutputFormat.getOutputFormat/#setOutputFormat(WordProcessingFormats).setOutputFormat(WordProcessingFormats)) property)


### WordProcessingSaveOptions(WordProcessingFormats outputFormat) {#WordProcessingSaveOptions-com.groupdocs.editor.formats.WordProcessingFormats-}
```
public WordProcessingSaveOptions(WordProcessingFormats outputFormat)
```


Skapar en ny instans av WordProcessingSaveOptions med angivet
obligatoriskt WordProcessing‑utdataformat, medan alla andra parametrar är
standard


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | outputFormat | [WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats) | Obligatoriskt utdataformat, i vilket WordProcessing dokumentet ska sparas |
|

### getEnablePagination() {#getEnablePagination--}
```
public final boolean getEnablePagination()
```


Tillåter att aktivera eller inaktivera paginering som kommer att användas för att spara
dokument. Om originaldokumentet öppnades och redigerades i paginerings
läge, bör detta alternativ också aktiveras. Som standard är det inaktiverat.


**Returns:**
boolean -
### setEnablePagination(boolean value) {#setEnablePagination-boolean-}
```
public final void setEnablePagination(boolean value)
```


Tillåter att aktivera eller inaktivera paginering som kommer att användas för att spara
dokument. Om originaldokumentet öppnades och redigerades i paginerings
läge, bör detta alternativ också aktiveras. Som standard är det inaktiverat.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Tillåter att ange, ändra, hämta eller ta bort ett lösenord som kommer att
används för att koda det genererade WordProcessing dokumentet. Ange NULL eller
tom sträng för att ta bort (rensa) lösenordet.


**Returns:**
java.lang.String -
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Tillåter att ange, ändra, hämta eller ta bort ett lösenord som kommer att
används för att koda det genererade WordProcessing dokumentet. Ange NULL eller
tom sträng för att ta bort (rensa) lösenordet.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### getOutputFormat() {#getOutputFormat--}
```
public final WordProcessingFormats getOutputFormat()
```


Tillåter att ange ett WordProcessing-format som kommer att användas för att spara
dokumentet


**Returns:**
[WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats) - 
### setOutputFormat(WordProcessingFormats value) {#setOutputFormat-com.groupdocs.editor.formats.WordProcessingFormats-}
```
public final void setOutputFormat(WordProcessingFormats value)
```


Tillåter att ange ett WordProcessing-format som kommer att användas för att spara
dokumentet


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats) |  |

### getLocale() {#getLocale--}
```
public final Locale getLocale()
```


Tillåter att ange en överskrivning av standardlokal (språk) för WordProcessing
dokument, som kommer att tillämpas under dess skapande. När det inte är
specificerat (standardvärde), MS Word (eller annat program) kommer att upptäcka (eller
choose) dokumentets språkregion enligt dess egna inställningar eller andra
faktorer.


*** ** * ** ***

Det här alternativet tillämpar tvångsmässigt den angivna språkregionen på all text i dokumentet. Använd det inte om dokumentet innehåller olika delar av text som är skrivna på olika språk.

<br />



**Returns:**
java.util.Locale -
### setLocale(Locale value) {#setLocale-java.util.Locale-}
```
public final void setLocale(Locale value)
```


Tillåter att ange en överskrivning av standardlokal (språk) för WordProcessing
dokument, som kommer att tillämpas under dess skapande. När det inte är
specificerat (standardvärde), MS Word (eller annat program) kommer att upptäcka (eller
choose) dokumentets språkregion enligt dess egna inställningar eller andra
faktorer.

*** ** * ** ***


Det här alternativet tillämpar tvångsmässigt den angivna språkregionen på all text i
dokumentet. Använd det inte om dokumentet innehåller olika delar av
text som är skrivna på olika språk.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.util.Locale |  |

### getLocaleBi() {#getLocaleBi--}
```
public final Locale getLocaleBi()
```


Tillåter att ange en överskrivning av lokal (språk) för WordProcessing dokumentet
för RTL (right-to-left) text, som kommer att tillämpas under dess
skapande. När den inte är specificerad (standardvärde), MS Word (eller annat
program) kommer att upptäcka (eller välja) dokumentets RTL-språkregion enligt dess
egna inställningar eller andra faktorer.

*** ** * ** ***


Det här alternativet tillämpar tvångsmässigt den angivna språkregionen på all RTL-text
i dokumentet. Använd det inte om dokumentet innehåller olika delar av
text som är skrivna på olika språk.


**Returns:**
java.util.Locale -
### setLocaleBi(Locale value) {#setLocaleBi-java.util.Locale-}
```
public final void setLocaleBi(Locale value)
```


Tillåter att ange en överskrivning av lokal (språk) för WordProcessing dokumentet
för RTL (right-to-left) text, som kommer att tillämpas under dess
skapande. När den inte är specificerad (standardvärde), MS Word (eller annat
program) kommer att upptäcka (eller välja) dokumentets RTL-språkregion enligt dess
egna inställningar eller andra faktorer.

*** ** * ** ***


Det här alternativet tillämpar tvångsmässigt den angivna språkregionen på all RTL-text
i dokumentet. Använd det inte om dokumentet innehåller olika delar av
text som är skrivna på olika språk.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.util.Locale |  |

### getLocaleFarEast() {#getLocaleFarEast--}
```
public final Locale getLocaleFarEast()
```


Tillåter att överskriva lokal (språk) för WordProcessing dokumentet
för den östasiatiska texten, som kommer att tillämpas under dess skapande. När
den inte är specificerad (standardvärde), MS Word (eller annat program) kommer att upptäcka
(eller välja) dokumentets östasiatiska språkregion enligt dess egna inställningar
eller andra faktorer.

*** ** * ** ***


Det här alternativet tillämpar tvångsmässigt den angivna språkregionen på all
östasiatisk text i dokumentet. Använd det inte om dokumentet innehåller
olika delar av text som är skrivna på olika
språk.


**Returns:**
java.util.Locale -
### setLocaleFarEast(Locale value) {#setLocaleFarEast-java.util.Locale-}
```
public final void setLocaleFarEast(Locale value)
```


Tillåter att överskriva lokal (språk) för WordProcessing dokumentet
för den östasiatiska texten, som kommer att tillämpas under dess skapande. När
den inte är specificerad (standardvärde), MS Word (eller annat program) kommer att upptäcka
(eller välja) dokumentets östasiatiska språkregion enligt dess egna inställningar
eller andra faktorer.

*** ** * ** ***


Det här alternativet tillämpar tvångsmässigt den angivna språkregionen på all
östasiatisk text i dokumentet. Använd det inte om dokumentet innehåller
olika delar av text som är skrivna på olika
språk.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.util.Locale |  |

### getOptimizeMemoryUsage() {#getOptimizeMemoryUsage--}
```
public final boolean getOptimizeMemoryUsage()
```


Aktiverar minnesoptimeringsmekanismer under dokumentgenerering från
HTML, vilket försämrar prestanda som en kostnad för minskat minnesanvändning.
Att sätta detta alternativ till true kan avsevärt minska minnesförbrukningen
vid generering av stora dokument på bekostnad av långsammare sparningstid.
Standard är false (minnesoptimering är inaktiverad för att förbättra
prestanda).


**Returns:**
boolean -
### setOptimizeMemoryUsage(boolean value) {#setOptimizeMemoryUsage-boolean-}
```
public final void setOptimizeMemoryUsage(boolean value)
```


Aktiverar minnesoptimeringsmekanismer under dokumentgenerering från
HTML, vilket försämrar prestanda som en kostnad för minskat minnesanvändning.
Att sätta detta alternativ till true kan avsevärt minska minnesförbrukningen
vid generering av stora dokument på bekostnad av långsammare sparningstid.
Standard är false (minnesoptimering är inaktiverad för att förbättra
prestanda).


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### getProtection() {#getProtection--}
```
public final WordProcessingProtection getProtection()
```


Tillåter att styra och tillämpa dokumentskyddsalternativen för
WordProcessing dokument av vilket format som helst, som stödjer dokument
skydd. Som standard är NULL - dokumentskydd kommer inte att användas.


**Returns:**
[WordProcessingProtection](../../com.groupdocs.editor.options/wordprocessingprotection) - 
### setProtection(WordProcessingProtection value) {#setProtection-com.groupdocs.editor.options.WordProcessingProtection-}
```
public final void setProtection(WordProcessingProtection value)
```


Tillåter att styra och tillämpa dokumentskyddsalternativen för
WordProcessing dokument av vilket format som helst, som stödjer dokument
skydd. Som standard är NULL - dokumentskydd kommer inte att användas.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [WordProcessingProtection](../../com.groupdocs.editor.options/wordprocessingprotection) |  |

### getFontEmbedding() {#getFontEmbedding--}
```
public final int getFontEmbedding()
```


Ansvarig för att bädda in teckensnittresurser i utdata WordProcessing
dokument. Som standard bäddar den inte in några typsnitt (NotEmbed).


**Returns:**
int -
### setFontEmbedding(int value) {#setFontEmbedding-int-}
```
public final void setFontEmbedding(int value)
```


Ansvarig för att bädda in teckensnittresurser i utdata WordProcessing
dokument. Som standard bäddar den inte in några typsnitt (NotEmbed).


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### deepClone() {#deepClone--}
```
public final WordProcessingSaveOptions deepClone()
```


Skapar och returnerar en fullständig kopia av denna instans av
WordProcessingSaveOptions-klass


**Returns:**
[WordProcessingSaveOptions](../../com.groupdocs.editor.options/wordprocessingsaveoptions) - New WordProcessingSaveOptions instance

