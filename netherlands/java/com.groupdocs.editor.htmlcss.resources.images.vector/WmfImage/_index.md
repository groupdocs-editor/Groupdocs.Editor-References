---
title: "WmfImage"
second_title: "GroupDocs.Editor for Java API-referentie"
description: "Stelt één vectorafbeelding in WMF Windows MetaFile-formaat voor met zijn metadata en extra methoden"
type: docs
weight: 14
url: /nl/java/com.groupdocs.editor.htmlcss.resources.images.vector/wmfimage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.images.vector.VectorImageResourceBase](../../com.groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase), [com.groupdocs.editor.htmlcss.resources.images.vector.MetaImageBase](../../com.groupdocs.editor.htmlcss.resources.images.vector/metaimagebase)
```
public final class WmfImage extends MetaImageBase
```

Stelt één vectorafbeelding in WMF (Windows MetaFile)-formaat voor met zijn
metadata en extra methoden

## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [WmfImage(String name, String contentInBase64)](#WmfImage-java.lang.String-java.lang.String-) | Maakt een nieuw WmfImage‑object aan vanuit inhoud, weergegeven als base64‑gecodeerd |
tekenreeks, en met opgegeven naam
|
|  | [WmfImage(String name, InputStream binaryContent)](#WmfImage-java.lang.String-java.io.InputStream-) | Maakt een nieuw WmfImage‑object aan vanuit inhoud, weergegeven als byte‑stroom, |
en met opgegeven naam
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | Controleert of de opgegeven stream een geldige WMF-afbeelding is |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | Controleert of de opgegeven base64‑gecodeerde tekenreeks een geldige WMF-afbeelding is |
|
|  | [getType()](#getType--) | Retourneert ImageType.Wmf |
|
|  | [getByteContent()](#getByteContent--) | Retourneert de inhoud van deze WMF-afbeelding als een binaire stroom |
|
|  | [getTextContent()](#getTextContent--) | Retourneert de inhoud van deze WMF-afbeelding als platte tekst |
|
|  | [save(String fullPathToFile)](#save-java.lang.String-) | Slaat deze WMF-afbeelding op in het bestand |
|
|  | [saveToPng(OutputStream outputPngContent)](#saveToPng-java.io.OutputStream-) | Slaat deze vector‑WMF‑afbeelding op als raster‑PNG‑afbeelding |
|
|  | [saveToSvg(OutputStream outputSvgContent)](#saveToSvg-java.io.OutputStream-) | Slaat deze vector‑WMF‑afbeelding op als vector‑SVG‑afbeelding |
|
|  | [dispose()](#dispose--) | Verwijdert deze WMF-afbeelding door de inhoud te verwijderen en het grootste deel ervan |
methoden en eigenschappen niet-werkend
|
### WmfImage(String name, String contentInBase64) {#WmfImage-java.lang.String-java.lang.String-}
```
public WmfImage(String name, String contentInBase64)
```


Maakt een nieuw WmfImage‑object aan vanuit inhoud, weergegeven als base64‑gecodeerd
tekenreeks, en met opgegeven naam


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | naam | java.lang.String | Naam van de WMF-afbeelding. Mag niet null, leeg of alleen witruimte zijn. |
|
|  | contentInBase64 | java.lang.String | Inhoud als base64‑gecodeerde tekenreeks. Mag niet null, leeg of alleen witruimte zijn. Als het geen WMF‑inhoud is, wordt er een uitzondering gegooid. |
|

### WmfImage(String name, InputStream binaryContent) {#WmfImage-java.lang.String-java.io.InputStream-}
```
public WmfImage(String name, InputStream binaryContent)
```


Maakt een nieuw WmfImage‑object aan vanuit inhoud, weergegeven als byte‑stroom,
en met opgegeven naam


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | naam | java.lang.String | Naam van de WMF-afbeelding. Mag niet null, leeg of alleen witruimte zijn. |
|
|  | binaryContent | java.io.InputStream | Inhoud als byte‑stroom. Lezen begint vanaf de oorspronkelijke positie. Mag niet null zijn. Moet leesbaar en doorzoekbaar zijn. Als deze instantie wordt verwijderd, wordt deze stroom ook verwijderd. |
|

### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


Controleert of de opgegeven stream een geldige WMF-afbeelding is


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | Invoerstroom als bytes. Mag niet NULL zijn, moet lezen en zoeken ondersteunen. |
|

**Returns:**
boolean - True als de opgegeven stream een geldige WMF‑afbeelding bevat, anders false

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


Controleert of de opgegeven base64‑gecodeerde tekenreeks een geldige WMF-afbeelding is


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | Invoertekenreeks, waarin de inhoud van de WMF‑afbeelding is opgeslagen in base64‑codering. Mag niet NULL of leeg zijn. |
|

**Returns:**
boolean - True als de opgegeven tekenreeks een geldige WMF‑afbeelding bevat, anders false

### getType() {#getType--}
```
public ImageType getType()
```


Retourneert ImageType.Wmf


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) - 
### getByteContent() {#getByteContent--}
```
public InputStream getByteContent()
```


Retourneert de inhoud van deze WMF-afbeelding als een binaire stroom


**Returns:**
java.io.InputStream -
### getTextContent() {#getTextContent--}
```
public String getTextContent()
```


Retourneert de inhoud van deze WMF-afbeelding als platte tekst


**Returns:**
java.lang.String -
### save(String fullPathToFile) {#save-java.lang.String-}
```
public void save(String fullPathToFile)
```


Slaat deze WMF-afbeelding op in het bestand


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | fullPathToFile | java.lang.String | Volledig pad naar het bestand, dat wordt aangemaakt (als het niet bestaat) of overschreven (als het bestaat) met de inhoud van deze WMF‑afbeelding |
|

### saveToPng(OutputStream outputPngContent) {#saveToPng-java.io.OutputStream-}
```
public void saveToPng(OutputStream outputPngContent)
```


Slaat deze vector‑WMF‑afbeelding op als raster‑PNG‑afbeelding


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | outputPngContent | java.io.OutputStream | Uitvoerstroom, waarin de inhoud van de PNG-afbeelding zal worden geschreven. Mag niet NULL zijn en moet schrijfbaar zijn. |
|

### saveToSvg(OutputStream outputSvgContent) {#saveToSvg-java.io.OutputStream-}
```
public void saveToSvg(OutputStream outputSvgContent)
```


Slaat deze vector‑WMF‑afbeelding op als vector‑SVG‑afbeelding


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | outputSvgContent | java.io.OutputStream | Uitvoerstroom, waarin de inhoud van de SVG-afbeelding zal worden geschreven. Mag niet NULL zijn en moet schrijfbaar zijn. |
|

### dispose() {#dispose--}
```
public void dispose()
```


Verwijdert deze WMF-afbeelding door de inhoud te verwijderen en het grootste deel ervan
methoden en eigenschappen niet-werkend


