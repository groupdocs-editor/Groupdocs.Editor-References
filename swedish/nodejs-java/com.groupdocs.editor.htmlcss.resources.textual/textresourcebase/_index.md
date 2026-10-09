---
title: "TextResourceBase"
second_title: "GroupDocs.Editor för Node.js via Java API-referens"
description: "Basklass för alla stödjade textresurser med textinnehåll och kodning"
type: docs
weight: 11
url: /sv/nodejs-java/com.groupdocs.editor.htmlcss.resources.textual/textresourcebase/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.IHtmlResource](../../com.groupdocs.editor.htmlcss.resources/ihtmlresource)
```
public abstract class TextResourceBase implements IHtmlResource
```

Basklass för alla stödjade textresurser med textinnehåll och kodning

## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
|  | [TextResourceBase(String name, String textualContent, Charset originalEncoding)](#TextResourceBase-java.lang.String-java.lang.String-java.nio.charset.Charset-) | Skapar en ny textresurs från angivet textinnehåll med kodning |
|
|  | [TextResourceBase(String name, InputStream binaryContent, Charset originalEncoding)](#TextResourceBase-java.lang.String-java.io.InputStream-java.nio.charset.Charset-) | Skapar en ny textresurs från specificerad byte‑ström och kodning |
|
## Fält

| Fält | Beskrivning |
| --- | --- |
| [Disposed](#Disposed) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getName()](#getName--) | Returnerar namn på denna textresurs utan filändelse |
|
|  | [getFilenameWithExtension()](#getFilenameWithExtension--) | Returnerar korrekt filnamn för denna textresurs, som består av namn |
och filändelse
|
|  | [getEncoding()](#getEncoding--) | Returnerar kodning för denna textresurs. |
|
|  | [getByteContent()](#getByteContent--) | Returnerar innehållet i denna textresurs som en byte‑ström med original |
kodning
|
|  | [getTextContent()](#getTextContent--) | Returnerar innehållet i denna textresurs som en standardsträng |
|
|  | [save(String fullPathToFile)](#save-java.lang.String-) | Sparar denna textresurs till den angivna filen |
|
|  | [equals(IHtmlResource other)](#equals-com.groupdocs.editor.htmlcss.resources.IHtmlResource-) | Kontrollerar detta objekt mot det angivna för likhet. |
|
|  | [dispose()](#dispose--) | Avslutar denna textresurs, avslutar dess innehåll och gör de flesta |
metoder och egenskaper oanvändbara.
|
|  | [isDisposed()](#isDisposed--) | Bestämmer om denna textresurs är avslutad eller inte |
|
|  | [getType()](#getType--) | I implementerande typ bör returnera information om textens typ. |
resurs
|
### TextResourceBase(String name, String textualContent, Charset originalEncoding) {#TextResourceBase-java.lang.String-java.lang.String-java.nio.charset.Charset-}
```
public TextResourceBase(String name, String textualContent, Charset originalEncoding)
```


Skapar en ny textresurs från angivet textinnehåll med kodning


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | namn | java.lang.String | Obligatoriskt namn på resursen, som fungerar som dess unika identifierare. Vanligtvis är det ett filnamn. |
|
|  | textualContent | java.lang.String | Textinnehåll för resursen, får inte vara NULL eller tomt |
|
|  | originalEncoding | java.nio.charset.Charset | Originalkodning för resursen, får inte vara NULL eller tomt |
|

### TextResourceBase(String name, InputStream binaryContent, Charset originalEncoding) {#TextResourceBase-java.lang.String-java.io.InputStream-java.nio.charset.Charset-}
```
public TextResourceBase(String name, InputStream binaryContent, Charset originalEncoding)
```


Skapar en ny textresurs från specificerad byte‑ström och kodning


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | namn | java.lang.String | Obligatoriskt namn på resursen, som fungerar som dess unika identifierare. Vanligtvis är det ett filnamn. |
|
|  | binaryContent | java.io.InputStream | Binärt innehåll för en resurs som en byte‑ström. Får inte vara NULL, avslutad, bör vara läsbar och sökbar. |
|
|  | originalEncoding | java.nio.charset.Charset | Originalkodning för resursen, får inte vara NULL eller tomt |
|

### Disposed {#Disposed}
```
public final Event<EventHandler> Disposed
```


### getName() {#getName--}
```
public final String getName()
```


Returnerar namn på denna textresurs utan filändelse


**Returns:**
java.lang.String
### getFilenameWithExtension() {#getFilenameWithExtension--}
```
public final String getFilenameWithExtension()
```


Returnerar korrekt filnamn för denna textresurs, som består av namn
och filändelse


**Returns:**
java.lang.String
### getEncoding() {#getEncoding--}
```
public final Charset getEncoding()
```


Returnerar kodning för denna textresurs. Returnerar vanligtvis UTF-8.


**Returns:**
java.nio.charset.Charset -
### getByteContent() {#getByteContent--}
```
public final InputStream getByteContent()
```


Returnerar innehållet i denna textresurs som en byte‑ström med original
kodning


**Returns:**
java.io.InputStream -
### getTextContent() {#getTextContent--}
```
public final String getTextContent()
```


Returnerar innehållet i denna textresurs som en standardsträng


**Returns:**
java.lang.String -
### save(String fullPathToFile) {#save-java.lang.String-}
```
public final void save(String fullPathToFile)
```


Sparar denna textresurs till den angivna filen


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | fullPathToFile | java.lang.String | Fullständig sökväg till filen, som kommer att skapas eller skrivas om om den redan finns |
|

### equals(IHtmlResource other) {#equals-com.groupdocs.editor.htmlcss.resources.IHtmlResource-}
```
public final boolean equals(IHtmlResource other)
```


Kontrollerar detta objekt mot det angivna för likhet.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | other | [IHtmlResource](../../com.groupdocs.editor.htmlcss.resources/ihtmlresource) | Annan HTML-resurs av okänd typ, som också sannolikt är en TextResourceBase-arvtagare |
|

**Returns:**
boolean - Returnerar true om de är lika, eller false om de är olika

### dispose() {#dispose--}
```
public final void dispose()
```


Avslutar denna textresurs, avslutar dess innehåll och gör de flesta
metoder och egenskaper fungerar inte. Tolerant mot flera anrop.


### isDisposed() {#isDisposed--}
```
public final boolean isDisposed()
```


Bestämmer om denna textresurs är avslutad eller inte


**Returns:**
boolean -
### getType() {#getType--}
```
public abstract TextType getType()
```


I implementerande typ bör returnera information om textens typ.
resurs


**Returns:**
[TextType](../../com.groupdocs.editor.htmlcss.resources.textual/texttype)
