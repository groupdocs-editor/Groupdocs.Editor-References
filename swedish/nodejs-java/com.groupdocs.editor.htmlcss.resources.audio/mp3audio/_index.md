---
title: "Mp3Audio"
second_title: "GroupDocs.Editor för Node.js via Java API-referens"
description: "Representerar en ljudresurs av godtyckligt format"
type: docs
weight: 11
url: /sv/nodejs-java/com.groupdocs.editor.htmlcss.resources.audio/mp3audio/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.IHtmlResource](../../com.groupdocs.editor.htmlcss.resources/ihtmlresource)
```
public final class Mp3Audio implements IHtmlResource
```

Representerar en ljudresurs av godtyckligt format

## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
|  | [Mp3Audio(String name, System.IO.Stream binaryContent, boolean leaveOpen)](#Mp3Audio-java.lang.String-com.aspose.ms.System.IO.Stream-boolean-) | Skapar en ny Mp3Audio‑klass från MP3‑innehåll, representerat som byte‑ström, och med angivet namn |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [isValid(System.IO.Stream binaryContent)](#isValid-com.aspose.ms.System.IO.Stream-) | Kontrollerar om den angivna strömmen är ett giltigt MP3‑innehåll |
|
|  | [getName()](#getName--) | Returnerar namn på detta MP3‑innehåll. |
|
|  | [getFilenameWithExtension()](#getFilenameWithExtension--) | Returnerar korrekt filnamn för detta MP3‑innehåll, som består av namn och filändelse. |
|
|  | [getType()](#getType--) | Returnerar en AudioFormat.Mp3 (uppfyller också IHtmlResource.getFormat() via kovariant retur) |
|
|  | [getByteContent()](#getByteContent--) | Returnerar innehållet i detta teckensnitt som byte stream |
|
|  | [getByteContentInternal()](#getByteContentInternal--) | Returnerar innehållet i denna MP3 audioresurs som byte stream med originalposition |
|
|  | [getTextContent()](#getTextContent--) | Returnerar innehållet i denna MP3‑resurs som base64‑kodad sträng. |
|
|  | [save(String fullPathToFile)](#save-java.lang.String-) | Sparar denna MP3‑resurs till den angivna filen |
|
|  | [equals(IHtmlResource other)](#equals-com.groupdocs.editor.htmlcss.resources.IHtmlResource-) | Kontrollerar denna instans med angiven HTML‑resurs för referenslikhet |
|
|  | [equals(Mp3Audio other)](#equals-com.groupdocs.editor.htmlcss.resources.audio.Mp3Audio-) | Kontrollerar denna instans med angiven teckensnitt‑resurs för referenslikhet |
|
|  | [dispose()](#dispose--) | Avslutar denna MP3‑resurs, frigör dess innehåll och gör de flesta metoder och egenskaper oanvändbara |
|
|  | [isDisposed()](#isDisposed--) | Avgör om detta MP3‑innehåll är avslutat eller inte |
|
| [addDisposedListener(EventHandler value)](#addDisposedListener-com.groupdocs.editor.handler.EventHandler-) |  |
| [removeDisposedListener(EventHandler value)](#removeDisposedListener-com.groupdocs.editor.handler.EventHandler-) |  |
### Mp3Audio(String name, System.IO.Stream binaryContent, boolean leaveOpen) {#Mp3Audio-java.lang.String-com.aspose.ms.System.IO.Stream-boolean-}
```
public Mp3Audio(String name, System.IO.Stream binaryContent, boolean leaveOpen)
```


Skapar en ny Mp3Audio‑klass från MP3‑innehåll, representerat som byte‑ström, och med angivet namn


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | namn | java.lang.String | Namn på MP3‑innehållet. Får inte vara null, tomt eller bara mellanslag. |
|
|  | binaryContent | com.aspose.ms.System.IO.Stream | Innehåll som byte stream. Läsning börjar från originalposition. Får inte vara null. Bör vara läsbar och sökbar. Om denna instans avslutas, avslutas även detta stream. |
|
|  | leaveOpen | boolean | Avgör om den angivna streamen ska avslutas när Mp3Audio‑instansen avslutas |
|

### isValid(System.IO.Stream binaryContent) {#isValid-com.aspose.ms.System.IO.Stream-}
```
public static boolean isValid(System.IO.Stream binaryContent)
```


Kontrollerar om den angivna strömmen är ett giltigt MP3‑innehåll


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | binaryContent | com.aspose.ms.System.IO.Stream | Byte stream som förmodligen innehåller ett MP3‑innehåll |
|

**Returns:**
boolean - Sant om den angivna streamen innehåller giltigt MP3‑innehåll, annars falskt

### getName() {#getName--}
```
public String getName()
```


Returnerar namnet på detta MP3‑innehåll. Innehåller vanligtvis inte filnamnstillägg och kan teoretiskt skilja sig från filnamnet.


**Returns:**
java.lang.String
### getFilenameWithExtension() {#getFilenameWithExtension--}
```
public String getFilenameWithExtension()
```


Returnerar korrekt filnamn för detta MP3‑innehåll, som består av namn och filändelse. Teoretiskt kan det skilja sig från namnet.


**Returns:**
java.lang.String
### getType() {#getType--}
```
public AudioType getType()
```


Returnerar en AudioFormat.Mp3 (uppfyller också IHtmlResource.getFormat() via kovariant retur)


**Returns:**
[AudioType](../../com.groupdocs.editor.htmlcss.resources.audio/audiotype)
### getByteContent() {#getByteContent--}
```
public InputStream getByteContent()
```


Returnerar innehållet i detta teckensnitt som byte stream


**Returns:**
java.io.InputStream
### getByteContentInternal() {#getByteContentInternal--}
```
public System.IO.Stream getByteContentInternal()
```


Returnerar innehållet i denna MP3 audioresurs som byte stream med originalposition


**Returns:**
com.aspose.ms.System.IO.Stream
### getTextContent() {#getTextContent--}
```
public String getTextContent()
```


Returnerar innehållet i denna MP3‑resurs som base64‑kodad sträng. Detta värde cachas efter första anropet.


**Returns:**
java.lang.String
### save(String fullPathToFile) {#save-java.lang.String-}
```
public void save(String fullPathToFile)
```


Sparar denna MP3‑resurs till den angivna filen


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | fullPathToFile | java.lang.String | Fullständig sökväg till filen som kommer att skapas eller skrivas om |
|

### equals(IHtmlResource other) {#equals-com.groupdocs.editor.htmlcss.resources.IHtmlResource-}
```
public boolean equals(IHtmlResource other)
```


Kontrollerar denna instans med angiven HTML‑resurs för referenslikhet


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | other | [IHtmlResource](../../com.groupdocs.editor.htmlcss.resources/ihtmlresource) | Annan implementering av IHtmlResource‑gränssnittet |
|

**Returns:**
boolean - Sant om de är lika, falskt om de är olika

### equals(Mp3Audio other) {#equals-com.groupdocs.editor.htmlcss.resources.audio.Mp3Audio-}
```
public boolean equals(Mp3Audio other)
```


Kontrollerar denna instans med angiven teckensnitt‑resurs för referenslikhet


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | other | [Mp3Audio](../../com.groupdocs.editor.htmlcss.resources.audio/mp3audio) | Annan instans av Mp3Audio‑klassen |
|

**Returns:**
boolean - Sant om de är lika, falskt om de är olika

### dispose() {#dispose--}
```
public void dispose()
```


Avslutar denna MP3‑resurs, frigör dess innehåll och gör de flesta metoder och egenskaper oanvändbara


### isDisposed() {#isDisposed--}
```
public boolean isDisposed()
```


Avgör om detta MP3‑innehåll är avslutat eller inte


**Returns:**
boolean
### addDisposedListener(EventHandler value) {#addDisposedListener-com.groupdocs.editor.handler.EventHandler-}
```
public void addDisposedListener(EventHandler value)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [EventHandler](../../com.groupdocs.editor.handler/eventhandler) |  |

### removeDisposedListener(EventHandler value) {#removeDisposedListener-com.groupdocs.editor.handler.EventHandler-}
```
public void removeDisposedListener(EventHandler value)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [EventHandler](../../com.groupdocs.editor.handler/eventhandler) |  |

