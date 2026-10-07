---
title: "FontEmbeddingOptions"
second_title: "GroupDocs.Editor for Java API-referentie"
description: "Lettertype‑insluitopties bepalen welke lettertype‑bronnen moeten worden ingebed in het uitvoer‑WordProcessing‑document"
type: docs
weight: 17
url: /nl/java/com.groupdocs.editor.options/fontembeddingoptions/
---
**Inheritance:**
java.lang.Object
```
public final class FontEmbeddingOptions
```

Lettertype‑insluitopties bepalen welke lettertype‑bronnen moeten worden ingebed in
het uitvoer‑WordProcessing‑document


*** ** * ** ***

Lettertype‑insluitopties worden toegepast tijdens het opslaan van het document (van een tussen‑EditableDocument naar het uitvoer‑WordProcessing‑formaat), deze enum is opgenomen als een eigenschap in de WordProcessingSaveOptions, van waaruit deze moet worden gebruikt

<br />


## Velden

| Veld | Beschrijving |
| --- | --- |
|  | [NotEmbed](#NotEmbed) | Embed geen enkele lettertype‑bron, noch vanuit EditableDocument, noch vanuit de |
systeem.
|
|  | [EmbedAll](#EmbedAll) | Analyseer de documentinhoud van de invoer‑EditableDocument, vind alle gebruikte lettertypen |
en embed ze in het uitvoer‑WordProcessing‑document.
|
|  | [EmbedWithoutSystem](#EmbedWithoutSystem) | Exact gelijk aan [EmbedAll](../../com.groupdocs.editor.options/fontembeddingoptions#EmbedAll), maar sluit die lettertypen uit, |
die door het besturingssysteem worden beschouwd als systeemlettertypen
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getFontEmbeddingOptions()](#getFontEmbeddingOptions--) |  |
### NotEmbed {#NotEmbed}
```
public static final int NotEmbed
```


Embed geen enkele lettertype‑bron, noch vanuit EditableDocument, noch vanuit de
systeem. Standaardwaarde.


### EmbedAll {#EmbedAll}
```
public static final int EmbedAll
```


Analyseer de documentinhoud van de invoer‑EditableDocument, vind alle gebruikte lettertypen
en embed ze in het uitvoer WordProcessing-document. In eerste instantie
GroupDocs.Editor haalt lettertypen uit de lettertypebronnen binnen EditableDocument.
Als ze onvoldoende of ontbrekend zijn, haalt GroupDocs.Editor lettertypen
van het besturingssysteem.


*** ** * ** ***

Allereerst analyseert GroupDocs.Editor de inhoud van EditableDocument en vormt een lijst van alle gebruikte lettertypen. Vervolgens worden deze lettertypen gezocht in de lettertypebronnen van EditableDocument. Als EditableDocument enkele lettertypebronnen bevat die niet in de documentinhoud voorkomen, worden die bronnen genegeerd. Als er lettertypen zijn die in de documentinhoud worden gebruikt maar geen overeenkomstige lettertypebronnen in EditableDocument hebben, probeert GroupDocs.Editor ze te vinden in het besturingssysteem. Deze optie lijkt op de optie \"Lettertypen insluiten in het bestand\" waarbij alle subopties zijn uitgeschakeld in Microsoft Word 2007 en hoger.

<br />



### EmbedWithoutSystem {#EmbedWithoutSystem}
```
public static final int EmbedWithoutSystem
```


Exact gelijk aan [EmbedAll](../../com.groupdocs.editor.options/fontembeddingoptions#EmbedAll), maar sluit die lettertypen uit,
die door het besturingssysteem worden beschouwd als systeemlettertypen


*** ** * ** ***

MS Windows heeft een concept van systeemlettertypen, die de meest basale en gebruikte lettertypen door Windows zelf zijn. Bij het gebruik van deze optie gedraagt GroupDocs.Editor zich zoals in het geval van [EmbedAll](../../com.groupdocs.editor.options/fontembeddingoptions#EmbedAll) case, maar bekijkt uiteindelijk een set verkregen lettertypen en sluit die uit die door het besturingssysteem als systeemlettertypen worden beschouwd. Deze optie lijkt op de opties \"Lettertypen insluiten in het bestand\" + \"Gemeenschappelijke systeemlettertypen niet insluiten\" in Microsoft Word 2007 en hoger

<br />



### getFontEmbeddingOptions() {#getFontEmbeddingOptions--}
```
public static int[] getFontEmbeddingOptions()
```




**Returns:**
int[]
