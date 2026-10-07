---
title: "OtfFont"
second_title: "GroupDocs.Editor for Java API-referentie"
description: "Stelt één lettertype voor in het OTF Open Type Format-formaat"
type: docs
weight: 13
url: /nl/java/com.groupdocs.editor.htmlcss.resources.fonts/otffont/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.fonts.FontResourceBase](../../com.groupdocs.editor.htmlcss.resources.fonts/fontresourcebase)
```
public final class OtfFont extends FontResourceBase
```

Stelt één lettertype in het OTF (Open Type Format) formaat voor.

## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [OtfFont(String name, String contentInBase64)](#OtfFont-java.lang.String-java.lang.String-) | Maakt een nieuwe OtfFont-klasse aan vanuit inhoud, weergegeven als base64-gecodeerd |
tekenreeks, en met opgegeven naam
|
|  | [OtfFont(String name, InputStream binaryContent)](#OtfFont-java.lang.String-java.io.InputStream-) | Maakt een nieuwe OtfFont-klasse aan vanuit inhoud, weergegeven als byte‑stroom, en |
met opgegeven naam
|
## Velden

| Veld | Beschrijving |
| --- | --- |
|  | [RequiredHeaderSize](#RequiredHeaderSize) | OTF-headergrootte (in bytes), die nodig is voor de validatie |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | Controleert of de opgegeven stroom een geldig OTF-lettertype is |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | Controleert of de opgegeven base64-gecodeerde string een geldig OTF-lettertype is |
|
|  | [getType()](#getType--) | Retourneert |
FontType.Otf
([FontType.getOtf](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype#getOtf))
|
### OtfFont(String name, String contentInBase64) {#OtfFont-java.lang.String-java.lang.String-}
```
public OtfFont(String name, String contentInBase64)
```


Maakt een nieuwe OtfFont-klasse aan vanuit inhoud, weergegeven als base64-gecodeerd
tekenreeks, en met opgegeven naam


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | naam | java.lang.String | Naam van het OTF-lettertype. Mag niet null, leeg of alleen witruimte zijn. |
|
|  | contentInBase64 | java.lang.String | Inhoud als base64-gecodeerde string. Mag niet null, leeg of alleen witruimte zijn. Als het geen OTF-inhoud is, wordt er een uitzondering gegooid. |
|

### OtfFont(String name, InputStream binaryContent) {#OtfFont-java.lang.String-java.io.InputStream-}
```
public OtfFont(String name, InputStream binaryContent)
```


Maakt een nieuwe OtfFont-klasse aan vanuit inhoud, weergegeven als byte‑stroom, en
met opgegeven naam


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | naam | java.lang.String | Naam van het OTF-lettertype. Mag niet null, leeg of alleen witruimte zijn. |
|
|  | binaryContent | java.io.InputStream | Inhoud als byte‑stroom. Lezen begint vanaf de oorspronkelijke positie. Mag niet null zijn. Moet leesbaar en doorzoekbaar zijn. Als deze instantie wordt verwijderd, wordt deze stroom ook verwijderd. |
|

### RequiredHeaderSize {#RequiredHeaderSize}
```
public static final int RequiredHeaderSize
```


OTF-headergrootte (in bytes), die nodig is voor de validatie


### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


Controleert of de opgegeven stroom een geldig OTF-lettertype is


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | Byte‑stroom, die vermoedelijk een OTF‑resource bevat |
|

**Returns:**
boolean - True als de opgegeven stroom een geldig OTF-lettertype bevat, false anders

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


Controleert of de opgegeven base64-gecodeerde string een geldig OTF-lettertype is


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | Inhoud van het vermoedelijke OTF-lettertype in de vorm van een base64-gecodeerde string |
|

**Returns:**
boolean - True als de opgegeven string een geldig OTF-lettertype bevat, false anders

### getType() {#getType--}
```
public FontType getType()
```


Retourneert
FontType.Otf
([FontType.getOtf](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype#getOtf))


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - 
