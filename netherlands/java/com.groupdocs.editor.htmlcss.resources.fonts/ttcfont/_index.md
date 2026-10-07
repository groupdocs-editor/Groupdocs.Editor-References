---
title: "TtcFont"
second_title: "GroupDocs.Editor for Java API-referentie"
description: "Stelt één lettertype voor in het TTC TrueType Collection-formaat"
type: docs
weight: 14
url: /nl/java/com.groupdocs.editor.htmlcss.resources.fonts/ttcfont/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.fonts.FontResourceBase](../../com.groupdocs.editor.htmlcss.resources.fonts/fontresourcebase)
```
public final class TtcFont extends FontResourceBase
```

Stelt één lettertype in het TTC (TrueType Collection) formaat voor.


Bekijk meer: https://docs.fileformat.com/font/ttc/

## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [TtcFont(String name, String contentInBase64)](#TtcFont-java.lang.String-java.lang.String-) | Maakt een nieuwe TtcFont-klasse aan vanuit inhoud, weergegeven als base64-gecodeerd |
tekenreeks, en met opgegeven naam
|
|  | [TtcFont(String name, InputStream binaryContent)](#TtcFont-java.lang.String-java.io.InputStream-) | Maakt een nieuwe TtcFont-klasse aan vanuit inhoud, weergegeven als byte‑stroom, en |
met opgegeven naam
|
## Velden

| Veld | Beschrijving |
| --- | --- |
|  | [RequiredHeaderSize](#RequiredHeaderSize) | TTC-headergrootte (in bytes), die vereist is voor de validatie |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | Controleert of de opgegeven stroom een geldig TTC-lettertype is |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | Controleert of de opgegeven base64-gecodeerde string een geldig TTC-lettertype is |
|
|  | [getType()](#getType--) | Retourneert FontType.Ttc |
|
|  | [getHeaderVersion()](#getHeaderVersion--) | TTC-headerversie, kan "1" of "2" zijn |
|
|  | [getFontsNumber()](#getFontsNumber--) | Aantal lettertypen in deze TTC |
|
|  | [getHasDsigTable()](#getHasDsigTable--) | Geeft aan of deze TTC een DSIG-tabel heeft. |
|
### TtcFont(String name, String contentInBase64) {#TtcFont-java.lang.String-java.lang.String-}
```
public TtcFont(String name, String contentInBase64)
```


Maakt een nieuwe TtcFont-klasse aan vanuit inhoud, weergegeven als base64-gecodeerd
tekenreeks, en met opgegeven naam


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | naam | java.lang.String | Naam van het TTC-lettertype. Mag niet null, leeg of alleen witruimte zijn. |
|
|  | contentInBase64 | java.lang.String | Inhoud als base64-gecodeerde string. Mag niet null, leeg of alleen witruimte zijn. Als het geen TTC-inhoud is, wordt er een uitzondering gegooid. |
|

### TtcFont(String name, InputStream binaryContent) {#TtcFont-java.lang.String-java.io.InputStream-}
```
public TtcFont(String name, InputStream binaryContent)
```


Maakt een nieuwe TtcFont-klasse aan vanuit inhoud, weergegeven als byte‑stroom, en
met opgegeven naam


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | naam | java.lang.String | Naam van het TTC-lettertype. Mag niet null, leeg of alleen witruimte zijn. |
|
|  | binaryContent | java.io.InputStream | Inhoud als byte‑stroom. Lezen begint vanaf de oorspronkelijke positie. Mag niet null zijn. Moet leesbaar en doorzoekbaar zijn. Als deze instantie wordt verwijderd, wordt deze stroom ook verwijderd. |
|

### RequiredHeaderSize {#RequiredHeaderSize}
```
public static final int RequiredHeaderSize
```


TTC-headergrootte (in bytes), die vereist is voor de validatie


### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


Controleert of de opgegeven stroom een geldig TTC-lettertype is


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | Byte‑stroom die vermoedelijk een TTC-resource bevat |
|

**Returns:**
boolean - True als de opgegeven stroom een geldig TTC-lettertype bevat, false anders

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


Controleert of de opgegeven base64-gecodeerde string een geldig TTC-lettertype is


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | Inhoud van het vermoedelijke TTC-lettertype in de vorm van een base64-gecodeerde string |
|

**Returns:**
boolean - True als de opgegeven string een geldig TTC-lettertype bevat, false anders

### getType() {#getType--}
```
public FontType getType()
```


Retourneert FontType.Ttc


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype)
### getHeaderVersion() {#getHeaderVersion--}
```
public byte getHeaderVersion()
```


TTC-headerversie, kan "1" of "2" zijn


**Returns:**
byte
### getFontsNumber() {#getFontsNumber--}
```
public long getFontsNumber()
```


Aantal lettertypen in deze TTC


**Returns:**
long
### getHasDsigTable() {#getHasDsigTable--}
```
public boolean getHasDsigTable()
```


Geeft aan of deze TTC een DSIG-tabel heeft. DSIG-tabel kan aanwezig zijn
alleen als TTC een headerversie 2.0 heeft.


**Returns:**
boolean
