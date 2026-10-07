---
title: "Woff2Font"
second_title: "GroupDocs.Editor for Java API-referentie"
description: "Stelt één lettertype voor in het WOFF2 Web Open Font Format-formaat"
type: docs
weight: 16
url: /nl/java/com.groupdocs.editor.htmlcss.resources.fonts/woff2font/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.fonts.FontResourceBase](../../com.groupdocs.editor.htmlcss.resources.fonts/fontresourcebase)
```
public final class Woff2Font extends FontResourceBase
```

Stelt één lettertype in het WOFF2 (Web Open Font Format) formaat voor.

## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [Woff2Font(String name, String contentInBase64)](#Woff2Font-java.lang.String-java.lang.String-) | Maakt een nieuwe Woff2Font-klasse aan vanuit inhoud, weergegeven als base64-gecodeerd |
tekenreeks, en met opgegeven naam
|
|  | [Woff2Font(String name, InputStream binaryContent)](#Woff2Font-java.lang.String-java.io.InputStream-) | Maakt een nieuwe Woff2Font-klasse aan vanuit inhoud, weergegeven als byte‑stroom, en |
met opgegeven naam
|
## Velden

| Veld | Beschrijving |
| --- | --- |
|  | [RequiredHeaderSize](#RequiredHeaderSize) | WOFF2-headergrootte (in bytes), die vereist is voor de validatie |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | Controleert of de opgegeven stroom een geldig WOFF2-lettertype is |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | Controleert of de opgegeven base64-gecodeerde tekenreeks een geldig WOFF2-lettertype is |
|
|  | [getType()](#getType--) | Retourneert FontType.Woff2 |
|
### Woff2Font(String name, String contentInBase64) {#Woff2Font-java.lang.String-java.lang.String-}
```
public Woff2Font(String name, String contentInBase64)
```


Maakt een nieuwe Woff2Font-klasse aan vanuit inhoud, weergegeven als base64-gecodeerd
tekenreeks, en met opgegeven naam


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | naam | java.lang.String | Naam van het WOFF2-lettertype. Mag niet null, leeg of alleen witruimte zijn. |
|
|  | contentInBase64 | java.lang.String | Inhoud als base64-gecodeerde tekenreeks. Mag niet null, leeg of alleen witruimte zijn. Als het geen WOFF2-inhoud is, wordt er een uitzondering gegooid. |
|

### Woff2Font(String name, InputStream binaryContent) {#Woff2Font-java.lang.String-java.io.InputStream-}
```
public Woff2Font(String name, InputStream binaryContent)
```


Maakt een nieuwe Woff2Font-klasse aan vanuit inhoud, weergegeven als byte‑stroom, en
met opgegeven naam


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | naam | java.lang.String | Naam van het WOFF2-lettertype. Mag niet null, leeg of alleen witruimte zijn. |
|
|  | binaryContent | java.io.InputStream | Inhoud als byte‑stroom. Lezen begint vanaf de oorspronkelijke positie. Mag niet null zijn. Moet leesbaar en doorzoekbaar zijn. Als deze instantie wordt vrijgegeven, wordt deze stroom ook vrijgegeven. |
|

### RequiredHeaderSize {#RequiredHeaderSize}
```
public static final int RequiredHeaderSize
```


WOFF2-headergrootte (in bytes), die vereist is voor de validatie


### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


Controleert of de opgegeven stroom een geldig WOFF2-lettertype is


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | Byte‑stroom die vermoedelijk een WOFF2‑resource bevat |
|

**Returns:**
boolean - Waar als de opgegeven stroom een geldig WOFF2-lettertype bevat, anders onwaar

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


Controleert of de opgegeven base64-gecodeerde tekenreeks een geldig WOFF2-lettertype is


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | Inhoud van het vermoedelijke WOFF2-lettertype in de vorm van een base64-gecodeerde tekenreeks |
|

**Returns:**
boolean - Waar als de opgegeven tekenreeks een geldig WOFF2-lettertype bevat, anders onwaar

### getType() {#getType--}
```
public FontType getType()
```


Retourneert FontType.Woff2


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype)
