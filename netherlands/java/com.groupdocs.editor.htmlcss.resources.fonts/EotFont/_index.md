---
title: "EotFont"
second_title: "GroupDocs.Editor for Java API-referentie"
description: "Stelt één lettertype voor in het EOT Embedded OpenType‑formaat"
type: docs
weight: 10
url: /nl/java/com.groupdocs.editor.htmlcss.resources.fonts/eotfont/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.fonts.FontResourceBase](../../com.groupdocs.editor.htmlcss.resources.fonts/fontresourcebase)
```
public final class EotFont extends FontResourceBase
```

Stelt één lettertype in het EOT (Embedded OpenType) formaat voor.

## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [EotFont(String name, String contentInBase64)](#EotFont-java.lang.String-java.lang.String-) | Maakt een nieuwe EotFont‑klasse aan vanuit inhoud, weergegeven als base64‑gecodeerd |
tekenreeks, en met opgegeven naam
|
|  | [EotFont(String name, InputStream binaryContent)](#EotFont-java.lang.String-java.io.InputStream-) | Maakt een nieuwe EotFont‑klasse aan vanuit inhoud, weergegeven als byte‑stroom, en |
met opgegeven naam
|
## Velden

| Veld | Beschrijving |
| --- | --- |
|  | [RequiredHeaderSize](#RequiredHeaderSize) | EOT‑headergrootte (in bytes), die nodig is voor de validatie |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | Controleert of de opgegeven stroom een geldig EOT‑lettertype is |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | Controleert of de opgegeven base64‑gecodeerde string een geldig EOT‑lettertype is |
|
|  | [getType()](#getType--) | Retourneert FontType.Eot |
|
### EotFont(String name, String contentInBase64) {#EotFont-java.lang.String-java.lang.String-}
```
public EotFont(String name, String contentInBase64)
```


Maakt een nieuwe EotFont‑klasse aan vanuit inhoud, weergegeven als base64‑gecodeerd
tekenreeks, en met opgegeven naam


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | naam | java.lang.String | Naam van het EOT-lettertype. Mag niet null, leeg of witruimte zijn. |
|
|  | contentInBase64 | java.lang.String | Inhoud als base64-gecodeerde string. Mag niet null, leeg of witruimte zijn. Als het geen EOT-inhoud is, wordt er een uitzondering gegooid. |
|

### EotFont(String name, InputStream binaryContent) {#EotFont-java.lang.String-java.io.InputStream-}
```
public EotFont(String name, InputStream binaryContent)
```


Maakt een nieuwe EotFont‑klasse aan vanuit inhoud, weergegeven als byte‑stroom, en
met opgegeven naam


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | naam | java.lang.String | Naam van het EOT-lettertype. Mag niet null, leeg of witruimte zijn. |
|
|  | binaryContent | java.io.InputStream | Inhoud als byte‑stroom. Lezen begint vanaf de oorspronkelijke positie. Mag niet null zijn. Moet leesbaar en doorzoekbaar zijn. Als deze instantie wordt verwijderd, wordt deze stroom ook verwijderd. |
|

### RequiredHeaderSize {#RequiredHeaderSize}
```
public static final int RequiredHeaderSize
```


EOT‑headergrootte (in bytes), die nodig is voor de validatie


### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


Controleert of de opgegeven stroom een geldig EOT‑lettertype is


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | Byte‑stroom, die vermoedelijk een EOT‑resource bevat |
|

**Returns:**
boolean - Waar als de opgegeven stroom een geldig EOT-lettertype bevat, anders onwaar

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


Controleert of de opgegeven base64‑gecodeerde string een geldig EOT‑lettertype is


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | Inhoud van het vermoedelijke EOT-lettertype in de vorm van een base64-gecodeerde string |
|

**Returns:**
boolean - Waar als de opgegeven string een geldig EOT-lettertype bevat, anders onwaar

### getType() {#getType--}
```
public FontType getType()
```


Retourneert FontType.Eot


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype)
