---
title: "TextResourceBase"
second_title: "GroupDocs.Editor for Java API-referentie"
description: "Basisklasse voor elke ondersteunde tekstbron met tekstinhoud en codering"
type: docs
weight: 11
url: /nl/java/com.groupdocs.editor.htmlcss.resources.textual/textresourcebase/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.IHtmlResource](../../com.groupdocs.editor.htmlcss.resources/ihtmlresource)
```
public abstract class TextResourceBase implements IHtmlResource
```

Basisklasse voor elke ondersteunde tekstbron met tekstinhoud en codering

## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [TextResourceBase(String name, String textualContent, Charset originalEncoding)](#TextResourceBase-java.lang.String-java.lang.String-java.nio.charset.Charset-) | Maakt een nieuwe tekstresource aan van opgegeven tekstinhoud met codering |
|
|  | [TextResourceBase(String name, InputStream binaryContent, Charset originalEncoding)](#TextResourceBase-java.lang.String-java.io.InputStream-java.nio.charset.Charset-) | Maakt een nieuwe tekstresource aan van opgegeven byte‑stroom en codering |
|
## Velden

| Veld | Beschrijving |
| --- | --- |
| [Disposed](#Disposed) |  |
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getName()](#getName--) | Retourneert de naam van deze tekstresource zonder bestandsextensie |
|
|  | [getFilenameWithExtension()](#getFilenameWithExtension--) | Retourneert de juiste bestandsnaam van deze tekstresource, die bestaat uit de naam |
en extensie
|
|  | [getEncoding()](#getEncoding--) | Retourneert de codering van deze tekstuele bron. |
|
|  | [getByteContent()](#getByteContent--) | Retourneert de inhoud van deze tekstbron als byte‑stroom met originele |
codering
|
|  | [getTextContent()](#getTextContent--) | Retourneert de inhoud van deze tekstbron als een standaard tekenreeks |
|
|  | [save(String fullPathToFile)](#save-java.lang.String-) | Slaat deze tekstbron op in het opgegeven bestand |
|
|  | [equals(IHtmlResource other)](#equals-com.groupdocs.editor.htmlcss.resources.IHtmlResource-) | Controleert deze instantie op gelijkheid met de opgegeven. |
|
|  | [dispose()](#dispose--) | Verwijdert deze tekstbron, waarbij de inhoud wordt verwijderd en de meeste |
methoden en eigenschappen niet-werkend.
|
|  | [isDisposed()](#isDisposed--) | Bepaalt of deze tekstbron is verwijderd of niet |
|
|  | [getType()](#getType--) | In een implementatietype moet informatie over het type tekst worden geretourneerd |
bron
|
### TextResourceBase(String name, String textualContent, Charset originalEncoding) {#TextResourceBase-java.lang.String-java.lang.String-java.nio.charset.Charset-}
```
public TextResourceBase(String name, String textualContent, Charset originalEncoding)
```


Maakt een nieuwe tekstresource aan van opgegeven tekstinhoud met codering


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | naam | java.lang.String | Verplichte naam van de bron, die dient als unieke identifier. Meestal is dit een bestandsnaam. |
|
|  | tekstueleInhoud | java.lang.String | Tekstuele inhoud van de bron, mag niet NULL of leeg zijn |
|
|  | origineleCodering | java.nio.charset.Charset | Originele codering van de bron, mag niet NULL of leeg zijn |
|

### TextResourceBase(String name, InputStream binaryContent, Charset originalEncoding) {#TextResourceBase-java.lang.String-java.io.InputStream-java.nio.charset.Charset-}
```
public TextResourceBase(String name, InputStream binaryContent, Charset originalEncoding)
```


Maakt een nieuwe tekstresource aan van opgegeven byte‑stroom en codering


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | naam | java.lang.String | Verplichte naam van de bron, die dient als unieke identifier. Meestal is dit een bestandsnaam. |
|
|  | binaryContent | java.io.InputStream | Binaire inhoud van een bron als een byte‑stroom. Mag niet NULL zijn, mag niet verwijderd zijn, moet leesbaar en doorzoekbaar zijn. |
|
|  | origineleCodering | java.nio.charset.Charset | Originele codering van de bron, mag niet NULL of leeg zijn |
|

### Disposed {#Disposed}
```
public final Event<EventHandler> Disposed
```


### getName() {#getName--}
```
public final String getName()
```


Retourneert de naam van deze tekstresource zonder bestandsextensie


**Returns:**
java.lang.String
### getFilenameWithExtension() {#getFilenameWithExtension--}
```
public final String getFilenameWithExtension()
```


Retourneert de juiste bestandsnaam van deze tekstresource, die bestaat uit de naam
en extensie


**Returns:**
java.lang.String
### getEncoding() {#getEncoding--}
```
public final Charset getEncoding()
```


Retourneert de codering van deze tekstuele bron. Retourneert meestal UTF-8.


**Returns:**
java.nio.charset.Charset -
### getByteContent() {#getByteContent--}
```
public final InputStream getByteContent()
```


Retourneert de inhoud van deze tekstbron als byte‑stroom met originele
codering


**Returns:**
java.io.InputStream -
### getTextContent() {#getTextContent--}
```
public final String getTextContent()
```


Retourneert de inhoud van deze tekstbron als een standaard tekenreeks


**Returns:**
java.lang.String -
### save(String fullPathToFile) {#save-java.lang.String-}
```
public final void save(String fullPathToFile)
```


Slaat deze tekstbron op in het opgegeven bestand


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | fullPathToFile | java.lang.String | Volledig pad naar het bestand, dat wordt aangemaakt of herschreven als het al bestaat |
|

### equals(IHtmlResource other) {#equals-com.groupdocs.editor.htmlcss.resources.IHtmlResource-}
```
public final boolean equals(IHtmlResource other)
```


Controleert deze instantie op gelijkheid met de opgegeven.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | other | [IHtmlResource](../../com.groupdocs.editor.htmlcss.resources/ihtmlresource) | Andere HTML-bron van onbekend type, die vermoedelijk ook een TextResourceBase‑erfgenaam is |
|

**Returns:**
boolean - Retourneert true als ze gelijk zijn, of false als ze ongelijk zijn

### dispose() {#dispose--}
```
public final void dispose()
```


Verwijdert deze tekstbron, waarbij de inhoud wordt verwijderd en de meeste
methoden en eigenschappen werken niet. Tolerant voor meerdere oproepen.


### isDisposed() {#isDisposed--}
```
public final boolean isDisposed()
```


Bepaalt of deze tekstbron is verwijderd of niet


**Returns:**
boolean -
### getType() {#getType--}
```
public abstract TextType getType()
```


In een implementatietype moet informatie over het type tekst worden geretourneerd
bron


**Returns:**
[TextType](../../com.groupdocs.editor.htmlcss.resources.textual/texttype)
