---
title: "VectorImageResourceBase"
second_title: "GroupDocs.Editor for Java API-referentie"
description: "Basisklasse voor elke ondersteunde vectorafbeelding."
type: docs
weight: 13
url: /nl/java/com.groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.images.IImageResource](../../com.groupdocs.editor.htmlcss.resources.images/iimageresource)
```
public abstract class VectorImageResourceBase implements IImageResource
```

Basisklasse voor elke ondersteunde vectorafbeelding.

## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [VectorImageResourceBase()](#VectorImageResourceBase--) |  |
## Velden

| Veld | Beschrijving |
| --- | --- |
| [Disposed](#Disposed) |  |
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getName()](#getName--) | Retourneert de naam van deze vectorafbeelding. |
|
|  | [getFilenameWithExtension()](#getFilenameWithExtension--) | Retourneert de juiste bestandsnaam van deze vectorafbeelding, die bestaat uit naam en |
extensie.
|
|  | [getAspectRatio()](#getAspectRatio--) | Retourneert de beeldverhouding van deze vectorafbeelding |
|
|  | [getLinearDimensions()](#getLinearDimensions--) | Retourneert de lineaire afmetingen van deze vectorafbeelding (breedte en hoogte) |
|
|  | [equals(IHtmlResource other)](#equals-com.groupdocs.editor.htmlcss.resources.IHtmlResource-) | Controleert deze instantie op referentie-gelijkheid met de opgegeven. |
|
|  | [isDisposed()](#isDisposed--) | Bepaalt of deze rasterafbeelding is verwijderd of niet |
|
|  | [getType()](#getType--) | In de implementerende type moet informatie over het type van de vector worden geretourneerd |
afbeelding
|
|  | [getByteContent()](#getByteContent--) | In de implementerende type moet de inhoud van deze vectorafbeelding als byte worden geretourneerd |
stream
|
|  | [getTextContent()](#getTextContent--) | In de implementerende type moet de inhoud van deze vectorafbeelding in tekst worden geretourneerd |
formaat: base64-gecodeerd van XML met betrekking tot het afbeeldingstype
|
|  | [save(String fullPathToFile)](#save-java.lang.String-) | In de implementerende type moet deze afbeelding op de schijf worden opgeslagen via het opgegeven pad |
|
|  | [saveToPng(OutputStream outputPngContent)](#saveToPng-java.io.OutputStream-) | In de implementerende type moet de huidige vectorafbeelding worden opgeslagen als raster-PNG |
formatteer naar de opgegeven byte‑stroom
|
|  | [dispose()](#dispose--) | In de implementerende type moet deze instantie worden vrijgegeven |
|
### VectorImageResourceBase() {#VectorImageResourceBase--}
```
public VectorImageResourceBase()
```


### Disposed {#Disposed}
```
public final Event<EventHandler> Disposed
```


### getName() {#getName--}
```
public final String getName()
```


Retourneert de naam van deze vectorafbeelding. Bevat meestal geen bestandsnaam
extensie en kan theoretisch verschillen van de bestandsnaam.


**Returns:**
java.lang.String
### getFilenameWithExtension() {#getFilenameWithExtension--}
```
public final String getFilenameWithExtension()
```


Retourneert de juiste bestandsnaam van deze vectorafbeelding, die bestaat uit naam en
extensie. Theoretisch kan dit verschillen van de naam.


**Returns:**
java.lang.String
### getAspectRatio() {#getAspectRatio--}
```
public final Ratio getAspectRatio()
```


Retourneert de beeldverhouding van deze vectorafbeelding


**Returns:**
[Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio)
### getLinearDimensions() {#getLinearDimensions--}
```
public final Dimensions getLinearDimensions()
```


Retourneert de lineaire afmetingen van deze vectorafbeelding (breedte en hoogte)


**Returns:**
[Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions)
### equals(IHtmlResource other) {#equals-com.groupdocs.editor.htmlcss.resources.IHtmlResource-}
```
public final boolean equals(IHtmlResource other)
```


Controleert deze instantie op referentie-gelijkheid met de opgegeven.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | other | [IHtmlResource](../../com.groupdocs.editor.htmlcss.resources/ihtmlresource) | Andere instantie van vectorafbeelding |
|

**Returns:**
boolean - True als ze gelijk zijn, false als ze ongelijk zijn

### isDisposed() {#isDisposed--}
```
public final boolean isDisposed()
```


Bepaalt of deze rasterafbeelding is verwijderd of niet


**Returns:**
boolean -
### getType() {#getType--}
```
public abstract ImageType getType()
```


In de implementerende type moet informatie over het type van de vector worden geretourneerd
afbeelding


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) - 
### getByteContent() {#getByteContent--}
```
public InputStream getByteContent()
```


In de implementerende type moet de inhoud van deze vectorafbeelding als byte worden geretourneerd
stream


**Returns:**
java.io.InputStream -
### getTextContent() {#getTextContent--}
```
public abstract String getTextContent()
```


In de implementerende type moet de inhoud van deze vectorafbeelding in tekst worden geretourneerd
formaat: base64-gecodeerd van XML met betrekking tot het afbeeldingstype


**Returns:**
java.lang.String -
### save(String fullPathToFile) {#save-java.lang.String-}
```
public abstract void save(String fullPathToFile)
```


In de implementerende type moet deze afbeelding op de schijf worden opgeslagen via het opgegeven pad


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fullPathToFile | java.lang.String |  |

### saveToPng(OutputStream outputPngContent) {#saveToPng-java.io.OutputStream-}
```
public abstract void saveToPng(OutputStream outputPngContent)
```


In de implementerende type moet de huidige vectorafbeelding worden opgeslagen als raster-PNG
formatteer naar de opgegeven byte‑stroom


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | outputPngContent | java.io.OutputStream | Byte‑stroom, waarin de PNG-versie van deze rasterafbeelding wordt opgeslagen. Mag niet NULL zijn en moet schrijven ondersteunen. |
|

### dispose() {#dispose--}
```
public abstract void dispose()
```


In de implementerende type moet deze instantie worden vrijgegeven


