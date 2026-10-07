---
title: "EmfImage"
second_title: "GroupDocs.Editor for Java API-referentie"
description: "Stelt één vectorafbeelding in Enhanced Metafile (EMF) formaat voor, met zijn metadata en extra methoden"
type: docs
weight: 10
url: /nl/java/com.groupdocs.editor.htmlcss.resources.images.vector/emfimage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.images.vector.VectorImageResourceBase](../../com.groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase), [com.groupdocs.editor.htmlcss.resources.images.vector.MetaImageBase](../../com.groupdocs.editor.htmlcss.resources.images.vector/metaimagebase)
```
public final class EmfImage extends MetaImageBase
```

Stelt één vectorafbeelding in Enhanced Metafile (EMF) formaat voor, met zijn
metadata en extra methoden

## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [EmfImage(String name, String contentInBase64)](#EmfImage-java.lang.String-java.lang.String-) | Maakt een nieuw EmfImage‑object aan vanuit inhoud, weergegeven als base64‑gecodeerd |
tekenreeks, en met opgegeven naam
|
|  | [EmfImage(String name, InputStream binaryContent)](#EmfImage-java.lang.String-java.io.InputStream-) | Maakt een nieuw EmfImage‑object aan vanuit inhoud, weergegeven als byte‑stroom, |
en met opgegeven naam
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | Controleert of de opgegeven stroom een geldige EMF-afbeelding is |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | Controleert of de opgegeven base64‑gecodeerde string een geldige EMF-afbeelding is |
|
|  | [getType()](#getType--) | Retourneert ImageType.Emf |
|
|  | [getByteContent()](#getByteContent--) | Retourneert de inhoud van deze EMF-afbeelding als een binaire stroom |
|
|  | [getTextContent()](#getTextContent--) | Retourneert de inhoud van deze EMF-afbeelding als platte tekst |
|
|  | [save(String fullPathToFile)](#save-java.lang.String-) | Slaat deze EMF-afbeelding op in het bestand |
|
|  | [saveToPng(OutputStream outputPngContent)](#saveToPng-java.io.OutputStream-) | Slaat deze vector‑EMF‑afbeelding op als raster‑PNG‑afbeelding |
|
|  | [saveToSvg(OutputStream outputSvgContent)](#saveToSvg-java.io.OutputStream-) | Slaat deze vector‑EMF‑afbeelding op als vector‑SVG‑afbeelding |
|
|  | [dispose()](#dispose--) | Disposeert deze EMF-afbeelding door de inhoud te verwijderen en het grootste deel van zijn |
methoden en eigenschappen niet-werkend
|
### EmfImage(String name, String contentInBase64) {#EmfImage-java.lang.String-java.lang.String-}
```
public EmfImage(String name, String contentInBase64)
```


Maakt een nieuw EmfImage‑object aan vanuit inhoud, weergegeven als base64‑gecodeerd
tekenreeks, en met opgegeven naam


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | naam | java.lang.String | Naam van de EMF-afbeelding. Mag niet null, leeg of alleen witruimte zijn. |
|
|  | contentInBase64 | java.lang.String | Inhoud als base64‑gecodeerde string. Mag niet null, leeg of alleen witruimte zijn. Als het geen EMF‑inhoud is, wordt een uitzondering gegooid. |
|

### EmfImage(String name, InputStream binaryContent) {#EmfImage-java.lang.String-java.io.InputStream-}
```
public EmfImage(String name, InputStream binaryContent)
```


Maakt een nieuw EmfImage‑object aan vanuit inhoud, weergegeven als byte‑stroom,
en met opgegeven naam


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | naam | java.lang.String | Naam van de EMF-afbeelding. Mag niet null, leeg of alleen witruimte zijn. |
|
|  | binaryContent | java.io.InputStream | Inhoud als byte‑stroom. Lezen begint vanaf de oorspronkelijke positie. Mag niet null zijn. Moet leesbaar en doorzoekbaar zijn. Als deze instantie wordt verwijderd, wordt deze stroom ook verwijderd. |
|

### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


Controleert of de opgegeven stroom een geldige EMF-afbeelding is


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | Invoerstroom als bytes. Mag niet NULL zijn, moet lezen en zoeken ondersteunen. |
|

**Returns:**
boolean - Waar als de opgegeven stream een geldige EMF-afbeelding bevat, anders onwaar

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


Controleert of de opgegeven base64‑gecodeerde string een geldige EMF-afbeelding is


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | Invoertekenreeks, waarin de inhoud van de EMF-afbeelding is opgeslagen in base64-codering. Mag niet NULL of leeg zijn. |
|

**Returns:**
boolean - Waar als de opgegeven tekenreeks een geldige EMF-afbeelding bevat, anders onwaar

### getType() {#getType--}
```
public ImageType getType()
```


Retourneert ImageType.Emf


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getByteContent() {#getByteContent--}
```
public InputStream getByteContent()
```


Retourneert de inhoud van deze EMF-afbeelding als een binaire stroom


**Returns:**
java.io.InputStream
### getTextContent() {#getTextContent--}
```
public String getTextContent()
```


Retourneert de inhoud van deze EMF-afbeelding als platte tekst


**Returns:**
java.lang.String -
### save(String fullPathToFile) {#save-java.lang.String-}
```
public void save(String fullPathToFile)
```


Slaat deze EMF-afbeelding op in het bestand


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | fullPathToFile | java.lang.String | Volledig pad naar het bestand, dat zal worden aangemaakt (als het niet bestaat) of overschreven (als het bestaat) met de inhoud van deze EMF-afbeelding |
|

### saveToPng(OutputStream outputPngContent) {#saveToPng-java.io.OutputStream-}
```
public void saveToPng(OutputStream outputPngContent)
```


Slaat deze vector‑EMF‑afbeelding op als raster‑PNG‑afbeelding


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | outputPngContent | java.io.OutputStream | Uitvoerstroom, waarin de inhoud van de PNG-afbeelding zal worden geschreven. Mag niet NULL zijn en moet schrijfbaar zijn. |
|

### saveToSvg(OutputStream outputSvgContent) {#saveToSvg-java.io.OutputStream-}
```
public void saveToSvg(OutputStream outputSvgContent)
```


Slaat deze vector‑EMF‑afbeelding op als vector‑SVG‑afbeelding


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | outputSvgContent | java.io.OutputStream | Uitvoerstroom, waarin de inhoud van de SVG-afbeelding zal worden geschreven. Mag niet NULL zijn en moet schrijfbaar zijn. |
|

### dispose() {#dispose--}
```
public void dispose()
```


Disposeert deze EMF-afbeelding door de inhoud te verwijderen en het grootste deel van zijn
methoden en eigenschappen niet-werkend


