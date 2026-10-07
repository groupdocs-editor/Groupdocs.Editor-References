---
title: "Mp3Audio"
second_title: "GroupDocs.Editor for Java API-referentie"
description: "Stelt één audiobron van willekeurig formaat voor"
type: docs
weight: 11
url: /nl/java/com.groupdocs.editor.htmlcss.resources.audio/mp3audio/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.IHtmlResource](../../com.groupdocs.editor.htmlcss.resources/ihtmlresource)
```
public final class Mp3Audio implements IHtmlResource
```

Stelt één audiobron van willekeurig formaat voor

## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [Mp3Audio(String name, System.IO.Stream binaryContent, boolean leaveOpen)](#Mp3Audio-java.lang.String-com.aspose.ms.System.IO.Stream-boolean-) | Maakt een nieuwe Mp3Audio-klasse aan vanuit MP3-inhoud, weergegeven als byte-stroom, en met de opgegeven naam |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [isValid(System.IO.Stream binaryContent)](#isValid-com.aspose.ms.System.IO.Stream-) | Controleert of de opgegeven stroom een geldige MP3-inhoud is |
|
|  | [getName()](#getName--) | Retourneert de naam van deze MP3-inhoud. |
|
|  | [getFilenameWithExtension()](#getFilenameWithExtension--) | Retourneert de juiste bestandsnaam van deze MP3-inhoud, die bestaat uit naam en extensie. |
|
|  | [getType()](#getType--) | Retourneert een AudioFormat.Mp3 (voldoet ook aan IHtmlResource.getFormat() via covariant retour) |
|
|  | [getByteContent()](#getByteContent--) | Retourneert de inhoud van dit lettertype als byte-stroom |
|
|  | [getByteContentInternal()](#getByteContentInternal--) | Retourneert de inhoud van deze MP3-audiobron als byte-stroom met de oorspronkelijke positie |
|
|  | [getTextContent()](#getTextContent--) | Retourneert de inhoud van deze MP3-bron als base64-gecodeerde string. |
|
|  | [save(String fullPathToFile)](#save-java.lang.String-) | Slaat deze MP3-bron op in het opgegeven bestand |
|
|  | [equals(IHtmlResource other)](#equals-com.groupdocs.editor.htmlcss.resources.IHtmlResource-) | Controleert deze instantie met de opgegeven HTML‑resource op referentie‑gelijkheid |
|
|  | [equals(Mp3Audio other)](#equals-com.groupdocs.editor.htmlcss.resources.audio.Mp3Audio-) | Controleert deze instantie met de opgegeven lettertype‑resource op referentie‑gelijkheid |
|
|  | [dispose()](#dispose--) | Verwijdert deze MP3‑resource, waarbij de inhoud wordt verwijderd en de meeste methoden en eigenschappen niet meer werken |
|
|  | [isDisposed()](#isDisposed--) | Bepaalt of deze MP3‑inhoud is verwijderd of niet |
|
| [addDisposedListener(EventHandler value)](#addDisposedListener-com.groupdocs.editor.handler.EventHandler-) |  |
| [removeDisposedListener(EventHandler value)](#removeDisposedListener-com.groupdocs.editor.handler.EventHandler-) |  |
### Mp3Audio(String name, System.IO.Stream binaryContent, boolean leaveOpen) {#Mp3Audio-java.lang.String-com.aspose.ms.System.IO.Stream-boolean-}
```
public Mp3Audio(String name, System.IO.Stream binaryContent, boolean leaveOpen)
```


Maakt een nieuwe Mp3Audio-klasse aan vanuit MP3-inhoud, weergegeven als byte-stroom, en met de opgegeven naam


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | naam | java.lang.String | Naam van de MP3‑inhoud. Mag niet null, leeg of alleen witruimte zijn. |
|
|  | binaryContent | com.aspose.ms.System.IO.Stream | Inhoud als byte‑stroom. Lezen begint vanaf de oorspronkelijke positie. Mag niet null zijn. Moet leesbaar en doorzoekbaar zijn. Als deze instantie wordt verwijderd, wordt deze stroom ook verwijderd. |
|
|  | leaveOpen | boolean | Bepaalt of de opgegeven stroom wel of niet wordt verwijderd wanneer de Mp3Audio‑instantie wordt verwijderd |
|

### isValid(System.IO.Stream binaryContent) {#isValid-com.aspose.ms.System.IO.Stream-}
```
public static boolean isValid(System.IO.Stream binaryContent)
```


Controleert of de opgegeven stroom een geldige MP3-inhoud is


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | binaryContent | com.aspose.ms.System.IO.Stream | Byte‑stroom, die vermoedelijk een MP3‑inhoud bevat |
|

**Returns:**
boolean - Waar als de opgegeven stroom geldige MP3‑inhoud bevat, anders onwaar

### getName() {#getName--}
```
public String getName()
```


Retourneert de naam van deze MP3‑inhoud. Bevat meestal geen bestandsextensie en kan theoretisch verschillen van de bestandsnaam.


**Returns:**
java.lang.String
### getFilenameWithExtension() {#getFilenameWithExtension--}
```
public String getFilenameWithExtension()
```


Retourneert de juiste bestandsnaam van deze MP3‑inhoud, die bestaat uit naam en extensie. Theoretisch kan deze verschillen van de naam.


**Returns:**
java.lang.String
### getType() {#getType--}
```
public AudioType getType()
```


Retourneert een AudioFormat.Mp3 (voldoet ook aan IHtmlResource.getFormat() via covariant retour)


**Returns:**
[AudioType](../../com.groupdocs.editor.htmlcss.resources.audio/audiotype)
### getByteContent() {#getByteContent--}
```
public InputStream getByteContent()
```


Retourneert de inhoud van dit lettertype als byte-stroom


**Returns:**
java.io.InputStream
### getByteContentInternal() {#getByteContentInternal--}
```
public System.IO.Stream getByteContentInternal()
```


Retourneert de inhoud van deze MP3-audiobron als byte-stroom met de oorspronkelijke positie


**Returns:**
com.aspose.ms.System.IO.Stream
### getTextContent() {#getTextContent--}
```
public String getTextContent()
```


Retourneert de inhoud van deze MP3‑resource als base64‑gecodeerde string. Deze waarde wordt gecached na de eerste aanroep.


**Returns:**
java.lang.String
### save(String fullPathToFile) {#save-java.lang.String-}
```
public void save(String fullPathToFile)
```


Slaat deze MP3-bron op in het opgegeven bestand


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | fullPathToFile | java.lang.String | Volledig pad naar het bestand, dat zal worden aangemaakt of herschreven |
|

### equals(IHtmlResource other) {#equals-com.groupdocs.editor.htmlcss.resources.IHtmlResource-}
```
public boolean equals(IHtmlResource other)
```


Controleert deze instantie met de opgegeven HTML‑resource op referentie‑gelijkheid


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | other | [IHtmlResource](../../com.groupdocs.editor.htmlcss.resources/ihtmlresource) | Andere implementatie van de IHtmlResource‑interface |
|

**Returns:**
boolean - True als ze gelijk zijn, false als ze ongelijk zijn

### equals(Mp3Audio other) {#equals-com.groupdocs.editor.htmlcss.resources.audio.Mp3Audio-}
```
public boolean equals(Mp3Audio other)
```


Controleert deze instantie met de opgegeven lettertype‑resource op referentie‑gelijkheid


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | other | [Mp3Audio](../../com.groupdocs.editor.htmlcss.resources.audio/mp3audio) | Andere instantie van de Mp3Audio‑klasse |
|

**Returns:**
boolean - True als ze gelijk zijn, false als ze ongelijk zijn

### dispose() {#dispose--}
```
public void dispose()
```


Verwijdert deze MP3‑resource, waarbij de inhoud wordt verwijderd en de meeste methoden en eigenschappen niet meer werken


### isDisposed() {#isDisposed--}
```
public boolean isDisposed()
```


Bepaalt of deze MP3‑inhoud is verwijderd of niet


**Returns:**
boolean
### addDisposedListener(EventHandler value) {#addDisposedListener-com.groupdocs.editor.handler.EventHandler-}
```
public void addDisposedListener(EventHandler value)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [EventHandler](../../com.groupdocs.editor.handler/eventhandler) |  |

### removeDisposedListener(EventHandler value) {#removeDisposedListener-com.groupdocs.editor.handler.EventHandler-}
```
public void removeDisposedListener(EventHandler value)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [EventHandler](../../com.groupdocs.editor.handler/eventhandler) |  |

