---
title: "MetaImageBase"
second_title: "GroupDocs.Editor for Java API-referentie"
description: "Abstracte basisklasse voor WMF- en EMF-afbeeldingsformaten."
type: docs
weight: 11
url: /nl/java/com.groupdocs.editor.htmlcss.resources.images.vector/metaimagebase/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.images.vector.VectorImageResourceBase](../../com.groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase)
```
public abstract class MetaImageBase extends VectorImageResourceBase
```

Abstracte basisklasse voor WMF- en EMF-afbeeldingsformaten.

## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [MetaImageBase(String name, String contentInBase64, boolean isWmf)](#MetaImageBase-java.lang.String-java.lang.String-boolean-) | Gemeenschappelijke constructor, die een WMF- of EMF‑instantie voorbereidt vanuit |
base64-gecodeerde string
|
|  | [MetaImageBase(String name, InputStream binaryContent, boolean isWmf)](#MetaImageBase-java.lang.String-java.io.InputStream-boolean-) | Gemeenschappelijke constructor, die een WMF- of EMF‑instantie voorbereidt vanuit |
byte‑stroom
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [isValidWmf(InputStream binaryContent)](#isValidWmf-java.io.InputStream-) | Bepaalt of de opgegeven byte‑stroom een geldige WMF-afbeelding bevat |
|
|  | [isValidWmf(String contentInBase64)](#isValidWmf-java.lang.String-) | Bepaalt of de opgegeven string een geldige WMF-afbeelding bevat, die is |
gecodeerd met base64
|
|  | [isValidEmf(InputStream binaryContent)](#isValidEmf-java.io.InputStream-) | Bepaalt of de opgegeven byte‑stroom een geldige EMF-afbeelding bevat |
|
|  | [isValidEmf(String contentInBase64)](#isValidEmf-java.lang.String-) | Bepaalt of de opgegeven string een geldige EMF-afbeelding bevat, die is |
gecodeerd met base64
|
|  | [saveToSvg(OutputStream outputSvgContent)](#saveToSvg-java.io.OutputStream-) | In de implementerende type moet de huidige vector‑meta‑afbeelding opslaan naar de |
vector‑SVG‑indeling in de opgegeven byte‑stroom
|
### MetaImageBase(String name, String contentInBase64, boolean isWmf) {#MetaImageBase-java.lang.String-java.lang.String-boolean-}
```
public MetaImageBase(String name, String contentInBase64, boolean isWmf)
```


Gemeenschappelijke constructor, die een WMF- of EMF‑instantie voorbereidt vanuit
base64-gecodeerde string


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | naam | java.lang.String | Verplichte naam |
|
|  | contentInBase64 | java.lang.String | Inhoud als base64-string. Mag niet NULL of leeg zijn. |
|
|  | isWmf | boolean | true voor WMF, false voor EMF |
|

### MetaImageBase(String name, InputStream binaryContent, boolean isWmf) {#MetaImageBase-java.lang.String-java.io.InputStream-boolean-}
```
public MetaImageBase(String name, InputStream binaryContent, boolean isWmf)
```


Gemeenschappelijke constructor, die een WMF- of EMF‑instantie voorbereidt vanuit
byte‑stroom


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | naam | java.lang.String | Verplichte naam |
|
|  | binaryContent | java.io.InputStream | Inhoud als byte‑stroom. Moet geldig zijn. |
|
|  | isWmf | boolean | true voor WMF, false voor EMF |
|

### isValidWmf(InputStream binaryContent) {#isValidWmf-java.io.InputStream-}
```
public static boolean isValidWmf(InputStream binaryContent)
```


Bepaalt of de opgegeven byte‑stroom een geldige WMF-afbeelding bevat


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | Invoerstroom. Moet geldig zijn. |
|

**Returns:**
boolean - Retourneert 'true' als geldig en 'false' als ongeldig

### isValidWmf(String contentInBase64) {#isValidWmf-java.lang.String-}
```
public static boolean isValidWmf(String contentInBase64)
```


Bepaalt of de opgegeven string een geldige WMF-afbeelding bevat, die is
gecodeerd met base64


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | String, die verondersteld wordt een base64-gecodeerde WMF-afbeelding te bevatten |
|

**Returns:**
boolean - Retourneert 'true' als geldig en 'false' als ongeldig

### isValidEmf(InputStream binaryContent) {#isValidEmf-java.io.InputStream-}
```
public static boolean isValidEmf(InputStream binaryContent)
```


Bepaalt of de opgegeven byte‑stroom een geldige EMF-afbeelding bevat


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | Invoerstroom. Moet geldig zijn. |
|

**Returns:**
boolean - Retourneert 'true' als geldig en 'false' als ongeldig

### isValidEmf(String contentInBase64) {#isValidEmf-java.lang.String-}
```
public static boolean isValidEmf(String contentInBase64)
```


Bepaalt of de opgegeven string een geldige EMF-afbeelding bevat, die is
gecodeerd met base64


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | String, die verondersteld wordt een base64-gecodeerde EMF-afbeelding te bevatten |
|

**Returns:**
boolean - Retourneert 'true' als geldig en 'false' als ongeldig

### saveToSvg(OutputStream outputSvgContent) {#saveToSvg-java.io.OutputStream-}
```
public abstract void saveToSvg(OutputStream outputSvgContent)
```


In de implementerende type moet de huidige vector‑meta‑afbeelding opslaan naar de
vector‑SVG‑indeling in de opgegeven byte‑stroom


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | outputSvgContent | java.io.OutputStream | Byte‑stroom waarin de SVG‑versie van deze vector‑meta‑afbeelding wordt opgeslagen. Mag niet NULL zijn en moet schrijven ondersteunen. |
|

