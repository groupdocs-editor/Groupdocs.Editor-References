---
title: "PresentationEditOptions"
second_title: "GroupDocs.Editor for Java API-referentie"
description: "Staat toe aangepaste opties op te geven voor het bewerken van documenten van alle ondersteunde presentatie‑PowerPoint‑compatibele formaten"
type: docs
weight: 32
url: /nl/java/com.groupdocs.editor.options/presentationeditoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public class PresentationEditOptions implements IEditOptions
```

Staat toe om aangepaste opties op te geven voor het bewerken van alle ondersteunde documenten
Presentatie (PowerPoint‑compatibele) formaten

## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [PresentationEditOptions()](#PresentationEditOptions--) |  |
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getSlideNumber()](#getSlideNumber--) | Staat toe de slide‑nummers op te geven die geopend moeten worden voor bewerking |
|
|  | [setSlideNumber(int value)](#setSlideNumber-int-) | Staat toe de slide‑nummers op te geven die geopend moeten worden voor bewerking |
|
|  | [getShowHiddenSlides()](#getShowHiddenSlides--) | Specificeert of de verborgen slides moeten worden opgenomen of niet. |
|
|  | [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Specificeert of de verborgen slides moeten worden opgenomen of niet. |
|
### PresentationEditOptions() {#PresentationEditOptions--}
```
public PresentationEditOptions()
```


### getSlideNumber() {#getSlideNumber--}
```
public final int getSlideNumber()
```


Staat toe de slide‑nummers op te geven die geopend moeten worden voor bewerking


*** ** * ** ***

Slide‑nummer is een nulgebaseerde index van een slide, die het mogelijk maakt een specifieke slide uit een presentatie te specificeren en te selecteren voor bewerking. Als het kleiner is dan 0, wordt de eerste slide geselecteerd (hetzelfde als SlideNumber = 0). Als het groter is dan het aantal slides in de presentatie, wordt de laatste slide geselecteerd. Als de invoerpresentatie slechts één slide bevat, wordt deze optie genegeerd en wordt die ene slide bewerkt. Als geprobeerd wordt een verborgen slide te openen voor bewerking, terwijl de ShowHiddenSlides‑optie (#getShowHiddenSlides.getShowHiddenSlides/#setShowHiddenSlides(boolean).setShowHiddenSlides(boolean)) is ingesteld op 'false', wordt er een uitzondering gegooid.

<br />



**Returns:**
int
### setSlideNumber(int value) {#setSlideNumber-int-}
```
public final void setSlideNumber(int value)
```


Staat toe de slide‑nummers op te geven die geopend moeten worden voor bewerking


*** ** * ** ***

Slide‑nummer is een nulgebaseerde index van een slide, die het mogelijk maakt een specifieke slide uit een presentatie te specificeren en te selecteren voor bewerking. Als het kleiner is dan 0, wordt de eerste slide geselecteerd (hetzelfde als SlideNumber = 0). Als het groter is dan het aantal slides in de presentatie, wordt de laatste slide geselecteerd. Als de invoerpresentatie slechts één slide bevat, wordt deze optie genegeerd en wordt die ene slide bewerkt. Als geprobeerd wordt een verborgen slide te openen voor bewerking, terwijl de ShowHiddenSlides‑optie (#getShowHiddenSlides.getShowHiddenSlides/#setShowHiddenSlides(boolean).setShowHiddenSlides(boolean)) is ingesteld op 'false', wordt er een uitzondering gegooid.

<br />



**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```


Specificeert of de verborgen slides moeten worden opgenomen of niet. Standaard is
false - verborgen slides worden niet getoond en er wordt een uitzondering gegooid tijdens
het proberen ze te bewerken.


**Returns:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```


Specificeert of de verborgen slides moeten worden opgenomen of niet. Standaard is
false - verborgen slides worden niet getoond en er wordt een uitzondering gegooid tijdens
het proberen ze te bewerken.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

