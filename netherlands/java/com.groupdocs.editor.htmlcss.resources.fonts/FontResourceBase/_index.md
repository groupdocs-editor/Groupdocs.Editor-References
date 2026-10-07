---
title: "FontResourceBase"
second_title: "GroupDocs.Editor for Java API-referentie"
description: "Basisklasse voor elk ondersteund lettertype als een resource voor het HTML‑document met al zijn eigenschappen"
type: docs
weight: 11
url: /nl/java/com.groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.IHtmlResource](../../com.groupdocs.editor.htmlcss.resources/ihtmlresource)
```
public abstract class FontResourceBase implements IHtmlResource
```

Basisklasse voor elk ondersteund lettertype als een resource voor het HTML‑document
met al zijn eigenschappen

## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [FontResourceBase()](#FontResourceBase--) |  |
## Velden

| Veld | Beschrijving |
| --- | --- |
|  | [Disposed](#Disposed) | Evenement dat plaatsvindt wanneer dit lettertype wordt verwijderd |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getName()](#getName--) | Retourneert de naam van deze lettertype‑resource. |
|
|  | [getFilenameWithExtension()](#getFilenameWithExtension--) | Retourneert de juiste bestandsnaam van deze lettertype‑resource, die bestaat uit de naam |
en extensie.
|
|  | [getByteContent()](#getByteContent--) | Retourneert de inhoud van dit lettertype als byte-stroom |
|
|  | [getTextContent()](#getTextContent--) | Retourneert de inhoud van dit lettertype als base64‑gecodeerde string. |
|
|  | [save(String fullPathToFile)](#save-java.lang.String-) | Slaat dit lettertype op in het opgegeven bestand |
|
|  | [equals(IHtmlResource other)](#equals-com.groupdocs.editor.htmlcss.resources.IHtmlResource-) | Controleert deze instantie met de opgegeven HTML‑resource op referentie‑gelijkheid |
|
|  | [equals(FontResourceBase other)](#equals-com.groupdocs.editor.htmlcss.resources.fonts.FontResourceBase-) | Controleert deze instantie met de opgegeven lettertype‑resource op referentie‑gelijkheid |
|
|  | [dispose()](#dispose--) | Verwijdert deze lettertype‑resource, verwijdert de inhoud en maakt de meeste |
methoden en eigenschappen niet-werkend
|
|  | [isDisposed()](#isDisposed--) | Bepaalt of dit lettertype is verwijderd of niet |
|
|  | [getType()](#getType--) | In de implementerende type moet informatie worden geretourneerd over het type van specifieke |
lettertype‑resource als een instantie van een specifiek FontType‑type, die
alle type‑specifieke informatie encapsuleert
|
### FontResourceBase() {#FontResourceBase--}
```
public FontResourceBase()
```


### Disposed {#Disposed}
```
public final Event<EventHandler> Disposed
```


Evenement dat plaatsvindt wanneer dit lettertype wordt verwijderd


### getName() {#getName--}
```
public final String getName()
```


Retourneert de naam van deze lettertype‑resource. Bevat meestal geen bestandsnaam
extensie en kan theoretisch verschillen van de bestandsnaam.


**Returns:**
java.lang.String
### getFilenameWithExtension() {#getFilenameWithExtension--}
```
public final String getFilenameWithExtension()
```


Retourneert de juiste bestandsnaam van deze lettertype‑resource, die bestaat uit de naam
en extensie. Theoretisch kan dit verschillen van de naam.


**Returns:**
java.lang.String
### getByteContent() {#getByteContent--}
```
public final InputStream getByteContent()
```


Retourneert de inhoud van dit lettertype als byte-stroom


**Returns:**
java.io.InputStream -
### getTextContent() {#getTextContent--}
```
public final String getTextContent()
```


Retourneert de inhoud van dit lettertype als base64‑gecodeerde string. Deze waarde is
gecacht na de eerste aanroep.


**Returns:**
java.lang.String -
### save(String fullPathToFile) {#save-java.lang.String-}
```
public final void save(String fullPathToFile)
```


Slaat dit lettertype op in het opgegeven bestand


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | fullPathToFile | java.lang.String | Volledig pad naar het bestand, dat zal worden aangemaakt of herschreven |
|

### equals(IHtmlResource other) {#equals-com.groupdocs.editor.htmlcss.resources.IHtmlResource-}
```
public final boolean equals(IHtmlResource other)
```


Controleert deze instantie met de opgegeven HTML‑resource op referentie‑gelijkheid


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | other | [IHtmlResource](../../com.groupdocs.editor.htmlcss.resources/ihtmlresource) | Andere implementatie van de IHtmlResource‑interface |
|

**Returns:**
boolean - True als ze gelijk zijn, false als ze ongelijk zijn

### equals(FontResourceBase other) {#equals-com.groupdocs.editor.htmlcss.resources.fonts.FontResourceBase-}
```
public final boolean equals(FontResourceBase other)
```


Controleert deze instantie met de opgegeven lettertype‑resource op referentie‑gelijkheid


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | other | [FontResourceBase](../../com.groupdocs.editor.htmlcss.resources.fonts/fontresourcebase) | Andere afstammeling van de abstracte klasse FontResourceBase |
|

**Returns:**
boolean - True als ze gelijk zijn, false als ze ongelijk zijn

### dispose() {#dispose--}
```
public final void dispose()
```


Verwijdert deze lettertype‑resource, verwijdert de inhoud en maakt de meeste
methoden en eigenschappen niet-werkend


### isDisposed() {#isDisposed--}
```
public final boolean isDisposed()
```


Bepaalt of dit lettertype is verwijderd of niet


**Returns:**
boolean -
### getType() {#getType--}
```
public abstract FontType getType()
```


In de implementerende type moet informatie worden geretourneerd over het type van specifieke
lettertype‑resource als een instantie van een specifiek FontType‑type, die
alle type‑specifieke informatie encapsuleert


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype)
