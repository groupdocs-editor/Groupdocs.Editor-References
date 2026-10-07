---
title: "TtfFont"
second_title: "GroupDocs.Editor for Java API-referentie"
description: "Stelt één lettertype voor in het TTF TrueType Font-formaat"
type: docs
weight: 15
url: /nl/java/com.groupdocs.editor.htmlcss.resources.fonts/ttffont/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.fonts.FontResourceBase](../../com.groupdocs.editor.htmlcss.resources.fonts/fontresourcebase)
```
public final class TtfFont extends FontResourceBase
```

Stelt één lettertype in het TTF (TrueType Font) formaat voor.

## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [TtfFont(String name, String contentInBase64)](#TtfFont-java.lang.String-java.lang.String-) | Maakt een nieuwe TtfFont-klasse aan vanuit inhoud, weergegeven als base64-gecodeerd |
tekenreeks, en met opgegeven naam
|
|  | [TtfFont(String name, InputStream binaryContent)](#TtfFont-java.lang.String-java.io.InputStream-) | Maakt een nieuwe TtfFont-klasse aan vanuit inhoud, weergegeven als byte‑stroom, en |
met opgegeven naam
|
## Velden

| Veld | Beschrijving |
| --- | --- |
|  | [RequiredHeaderSize](#RequiredHeaderSize) | TTF-headergrootte (in bytes), die vereist is voor de validatie |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | Controleert of de opgegeven stroom een geldig TTF-lettertype is |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | Controleert of de opgegeven base64-gecodeerde tekenreeks een geldig TTF-lettertype is |
|
|  | [getType()](#getType--) | Retourneert FontType.Ttf |
|
### TtfFont(String name, String contentInBase64) {#TtfFont-java.lang.String-java.lang.String-}
```
public TtfFont(String name, String contentInBase64)
```


Maakt een nieuwe TtfFont-klasse aan vanuit inhoud, weergegeven als base64-gecodeerd
tekenreeks, en met opgegeven naam


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | naam | java.lang.String | Naam van het TTF-lettertype. Mag niet null, leeg of alleen witruimte zijn. |
|
|  | contentInBase64 | java.lang.String | Inhoud als base64-gecodeerde tekenreeks. Mag niet null, leeg of alleen witruimte zijn. Als het geen TTF-inhoud is, wordt er een uitzondering gegooid. |
|

### TtfFont(String name, InputStream binaryContent) {#TtfFont-java.lang.String-java.io.InputStream-}
```
public TtfFont(String name, InputStream binaryContent)
```


Maakt een nieuwe TtfFont-klasse aan vanuit inhoud, weergegeven als byte‑stroom, en
met opgegeven naam


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | naam | java.lang.String | Naam van het TTF-lettertype. Mag niet null, leeg of alleen witruimte zijn. |
|
|  | binaryContent | java.io.InputStream | Inhoud als byte‑stroom. Lezen begint vanaf de oorspronkelijke positie. Mag niet null zijn. Moet leesbaar en doorzoekbaar zijn. Als deze instantie wordt verwijderd, wordt deze stroom ook verwijderd. |
|

### RequiredHeaderSize {#RequiredHeaderSize}
```
public static final int RequiredHeaderSize
```


TTF-headergrootte (in bytes), die vereist is voor de validatie


### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


Controleert of de opgegeven stroom een geldig TTF-lettertype is


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | Byte‑stroom, die vermoedelijk een TTF‑resource bevat |
|

**Returns:**
boolean - True als de opgegeven stroom een geldig TTF‑lettertype bevat, false anders

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


Controleert of de opgegeven base64-gecodeerde tekenreeks een geldig TTF-lettertype is


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | Inhoud van het vermoedelijke TTF‑lettertype in de vorm van een base64‑gecodeerde string |
|

**Returns:**
boolean - True als de opgegeven string een geldig TTF‑lettertype bevat, false anders

### getType() {#getType--}
```
public FontType getType()
```


Retourneert FontType.Ttf


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype)
