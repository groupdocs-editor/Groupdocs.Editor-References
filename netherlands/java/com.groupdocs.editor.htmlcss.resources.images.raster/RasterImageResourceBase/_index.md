---
title: "RasterImageResourceBase"
second_title: "GroupDocs.Editor for Java API-referentie"
description: "Basisklasse voor elke ondersteunde rasterafbeelding met vaste naam, afmetingen, beeldverhouding, type, grootte en inhoud."
type: docs
weight: 15
url: /nl/java/com.groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.images.IImageResource](../../com.groupdocs.editor.htmlcss.resources.images/iimageresource)
```
public abstract class RasterImageResourceBase implements IImageResource
```

Basisklasse voor elke ondersteunde rasterafbeelding met vaste naam, afmetingen, beeldverhouding
verhouding, type, grootte en inhoud.

## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [RasterImageResourceBase()](#RasterImageResourceBase--) |  |
## Velden

| Veld | Beschrijving |
| --- | --- |
| [Disposed](#Disposed) |  |
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getName()](#getName--) | Retourneert de naam van deze rasterafbeelding. |
|
|  | [getFilenameWithExtension()](#getFilenameWithExtension--) | Retourneert de juiste bestandsnaam van deze rasterafbeelding, die bestaat uit naam en |
extensie.
|
|  | [getLinearDimensions()](#getLinearDimensions--) | Retourneert de lineaire afmetingen van deze rasterafbeelding (breedte en hoogte) |
|
|  | [getAspectRatio()](#getAspectRatio--) | Retourneert een beeldverhouding van deze afbeelding als de breedte‑tot‑hoogte‑relatie |
|
|  | [getLength()](#getLength--) | Retourneert de lengte van dit rasterafbeeldingsbestand in bytes |
|
|  | [getByteContent()](#getByteContent--) | Retourneert de inhoud van deze rasterafbeelding als byte‑stroom |
|
|  | [getTextContent()](#getTextContent--) | Retourneert de inhoud van deze rasterafbeelding als base64‑gecodeerde tekenreeks |
|
|  | [save(String fullPathToFile)](#save-java.lang.String-) | Slaat deze rasterafbeelding op in het opgegeven bestand |
|
|  | [equals(IHtmlResource other)](#equals-com.groupdocs.editor.htmlcss.resources.IHtmlResource-) | Controleert deze instantie op referentie-gelijkheid met de opgegeven. |
|
|  | [dispose()](#dispose--) | Verwijdert deze rasterafbeelding, waarbij de inhoud wordt verwijderd en de meeste methoden |
en eigenschappen niet-werkend
|
|  | [isDisposed()](#isDisposed--) | Bepaalt of deze rasterafbeelding is verwijderd of niet |
|
|  | [getType()](#getType--) | In de implementatie moet het type informatie over het type van de rasterafbeelding retourneren |
afbeelding
|
### RasterImageResourceBase() {#RasterImageResourceBase--}
```
public RasterImageResourceBase()
```


### Disposed {#Disposed}
```
public final Event<EventHandler> Disposed
```


### getName() {#getName--}
```
public final String getName()
```


Retourneert de naam van deze rasterafbeelding. Bevat meestal geen bestandsnaam
extensie en kan theoretisch verschillen van de bestandsnaam.


**Returns:**
java.lang.String
### getFilenameWithExtension() {#getFilenameWithExtension--}
```
public final String getFilenameWithExtension()
```


Retourneert de juiste bestandsnaam van deze rasterafbeelding, die bestaat uit naam en
extensie. Theoretisch kan dit verschillen van de naam.


**Returns:**
java.lang.String
### getLinearDimensions() {#getLinearDimensions--}
```
public final Dimensions getLinearDimensions()
```


Retourneert de lineaire afmetingen van deze rasterafbeelding (breedte en hoogte)


**Returns:**
[Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions)
### getAspectRatio() {#getAspectRatio--}
```
public final Ratio getAspectRatio()
```


Retourneert een beeldverhouding van deze afbeelding als de breedte‑tot‑hoogte‑relatie


**Returns:**
[Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio)
### getLength() {#getLength--}
```
public final int getLength()
```


Retourneert de lengte van dit rasterafbeeldingsbestand in bytes


**Returns:**
int -
### getByteContent() {#getByteContent--}
```
public final InputStream getByteContent()
```


Retourneert de inhoud van deze rasterafbeelding als byte‑stroom


**Returns:**
java.io.InputStream -
### getTextContent() {#getTextContent--}
```
public final String getTextContent()
```


Retourneert de inhoud van deze rasterafbeelding als base64‑gecodeerde tekenreeks


**Returns:**
java.lang.String -
### save(String fullPathToFile) {#save-java.lang.String-}
```
public final void save(String fullPathToFile)
```


Slaat deze rasterafbeelding op in het opgegeven bestand


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | fullPathToFile | java.lang.String | Volledig pad naar het bestand, dat zal worden aangemaakt of herschreven |
|

### equals(IHtmlResource other) {#equals-com.groupdocs.editor.htmlcss.resources.IHtmlResource-}
```
public final boolean equals(IHtmlResource other)
```


Controleert deze instantie op referentie-gelijkheid met de opgegeven.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | other | [IHtmlResource](../../com.groupdocs.editor.htmlcss.resources/ihtmlresource) | Andere IHtmlResource-erfgenaam |
|

**Returns:**
boolean - True als ze gelijk zijn, false als ze ongelijk zijn

### dispose() {#dispose--}
```
public final void dispose()
```


Verwijdert deze rasterafbeelding, waarbij de inhoud wordt verwijderd en de meeste methoden
en eigenschappen niet-werkend


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


In de implementatie moet het type informatie over het type van de rasterafbeelding retourneren
afbeelding


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) - 
