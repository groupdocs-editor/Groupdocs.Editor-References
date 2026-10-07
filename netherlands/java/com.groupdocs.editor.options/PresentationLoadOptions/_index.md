---
title: "PresentationLoadOptions"
second_title: "GroupDocs.Editor for Java API-referentie"
description: "Staat toe aangepaste opties op te geven voor het laden van documenten van alle ondersteunde Presentatieformaten, zoals PPTX, PPTM, PPSX enz."
type: docs
weight: 33
url: /nl/java/com.groupdocs.editor.options/presentationloadoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ILoadOptions](../../com.groupdocs.editor.options/iloadoptions)
```
public class PresentationLoadOptions implements ILoadOptions
```

Staat toe aangepaste opties op te geven voor het laden van documenten van alle ondersteunde
Presentatieformaten zoals PPT(X), PPTM, PPS(X) enz.

## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [PresentationLoadOptions()](#PresentationLoadOptions--) |  |
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getPassword()](#getPassword--) | Staat toe het wachtwoord op te geven, te wijzigen en te verkrijgen, dat zal worden gebruikt voor |
het openen van het Presentatiedocument, indien het gecodeerd is.
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Staat toe het wachtwoord op te geven, te wijzigen en te verkrijgen, dat zal worden gebruikt voor |
het openen van het Presentatiedocument, indien het gecodeerd is.
|
### PresentationLoadOptions() {#PresentationLoadOptions--}
```
public PresentationLoadOptions()
```


### getPassword() {#getPassword--}
```
public final String getPassword()
```


Staat toe het wachtwoord op te geven, te wijzigen en te verkrijgen, dat zal worden gebruikt voor
het openen van het Presentatiedocument, indien het gecodeerd is. Stel in op NULL of leeg
string om het wachtwoord te verwijderen.


*** ** * ** ***

Standaard heeft deze eigenschap de waarde NULL \u2014 wachtwoord is niet ingesteld. Als het invoer‑Presentatiedocument met een wachtwoord is beveiligd, is het wachtwoord verplicht en wordt er een uitzondering gegooid als het wachtwoord niet is opgegeven of ongeldig is. Als het invoer‑Presentatiedocument NIET met een wachtwoord is beveiligd, maar er wel een wachtwoord is ingesteld, wordt het genegeerd.

<br />



**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Staat toe het wachtwoord op te geven, te wijzigen en te verkrijgen, dat zal worden gebruikt voor
het openen van het Presentatiedocument, indien het gecodeerd is. Stel in op NULL of leeg
string om het wachtwoord te verwijderen.


*** ** * ** ***

Standaard heeft deze eigenschap de waarde NULL \u2014 wachtwoord is niet ingesteld. Als het invoer‑Presentatiedocument met een wachtwoord is beveiligd, is het wachtwoord verplicht en wordt er een uitzondering gegooid als het wachtwoord niet is opgegeven of ongeldig is. Als het invoer‑Presentatiedocument NIET met een wachtwoord is beveiligd, maar er wel een wachtwoord is ingesteld, wordt het genegeerd.

<br />



**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

