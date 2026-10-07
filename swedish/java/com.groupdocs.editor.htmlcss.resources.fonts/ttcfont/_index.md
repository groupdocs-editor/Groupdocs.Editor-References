---
title: "TtcFont"
second_title: "GroupDocs.Editor för Java API-referens"
description: "Representerar ett teckensnitt i TTC TrueType Collection-formatet"
type: docs
weight: 14
url: /sv/java/com.groupdocs.editor.htmlcss.resources.fonts/ttcfont/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.fonts.FontResourceBase](../../com.groupdocs.editor.htmlcss.resources.fonts/fontresourcebase)
```
public final class TtcFont extends FontResourceBase
```

Representerar ett teckensnitt i TTC‑formatet (TrueType Collection).


Se mer: https://docs.fileformat.com/font/ttc/

## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
|  | [TtcFont(String name, String contentInBase64)](#TtcFont-java.lang.String-java.lang.String-) | Skapar en ny TtcFont-klass från innehåll, representerat som base64-kodad |
sträng, och med angivet namn
|
|  | [TtcFont(String name, InputStream binaryContent)](#TtcFont-java.lang.String-java.io.InputStream-) | Skapar en ny TtcFont-klass från innehåll, representerat som byte-ström, och |
med angivet namn
|
## Fält

| Fält | Beskrivning |
| --- | --- |
|  | [RequiredHeaderSize](#RequiredHeaderSize) | TTC-headerstorlek (i byte), som krävs för dess validering |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | Kontrollerar om den angivna strömmen är ett giltigt TTC-teckensnitt |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | Kontrollerar om den angivna base64-kodade strängen är ett giltigt TTC-teckensnitt |
|
|  | [getType()](#getType--) | Returnerar FontType.Ttc |
|
|  | [getHeaderVersion()](#getHeaderVersion--) | TTC-headerversion, kan vara "1" eller "2" |
|
|  | [getFontsNumber()](#getFontsNumber--) | Antal teckensnitt i detta TTC |
|
|  | [getHasDsigTable()](#getHasDsigTable--) | Indikerar om detta TTC har en DSIG-tabell. |
|
### TtcFont(String name, String contentInBase64) {#TtcFont-java.lang.String-java.lang.String-}
```
public TtcFont(String name, String contentInBase64)
```


Skapar en ny TtcFont-klass från innehåll, representerat som base64-kodad
sträng, och med angivet namn


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | namn | java.lang.String | Namn på TTC-teckensnittet. Får inte vara null, tomt eller bara whitespace. |
|
|  | contentInBase64 | java.lang.String | Innehåll som base64-kodad sträng. Får inte vara null, tomt eller bara whitespace. Om det inte är TTC-innehåll kommer ett undantag att kastas. |
|

### TtcFont(String name, InputStream binaryContent) {#TtcFont-java.lang.String-java.io.InputStream-}
```
public TtcFont(String name, InputStream binaryContent)
```


Skapar en ny TtcFont-klass från innehåll, representerat som byte-ström, och
med angivet namn


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | namn | java.lang.String | Namn på TTC-teckensnittet. Får inte vara null, tomt eller bara whitespace. |
|
|  | binaryContent | java.io.InputStream | Innehåll som byte-ström. Läsning börjar från ursprunglig position. Får inte vara null. Ska vara läsbar och sökbar. Om detta objekt frigörs, frigörs även denna ström. |
|

### RequiredHeaderSize {#RequiredHeaderSize}
```
public static final int RequiredHeaderSize
```


TTC-headerstorlek (i byte), som krävs för dess validering


### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


Kontrollerar om den angivna strömmen är ett giltigt TTC-teckensnitt


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | Byte-ström som förmodligen innehåller en TTC-resurs |
|

**Returns:**
boolesk - True om den angivna strömmen innehåller ett giltigt TTC-teckensnitt, annars false

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


Kontrollerar om den angivna base64-kodade strängen är ett giltigt TTC-teckensnitt


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | Innehåll av det förmodade TTC-teckensnittet i form av en base64-kodad sträng |
|

**Returns:**
boolean - Sant om den angivna strängen innehåller ett giltigt TTC-typsnitt, falskt annars

### getType() {#getType--}
```
public FontType getType()
```


Returnerar FontType.Ttc


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype)
### getHeaderVersion() {#getHeaderVersion--}
```
public byte getHeaderVersion()
```


TTC-headerversion, kan vara "1" eller "2"


**Returns:**
byte
### getFontsNumber() {#getFontsNumber--}
```
public long getFontsNumber()
```


Antal teckensnitt i detta TTC


**Returns:**
long
### getHasDsigTable() {#getHasDsigTable--}
```
public boolean getHasDsigTable()
```


Anger om detta TTC har en DSIG-tabell. DSIG-tabellen kan finnas.
endast om TTC har en Header version 2.0.


**Returns:**
boolean
