---
title: "FontResourceBase"
second_title: "GroupDocs.Editor för Node.js via Java API-referens"
description: "Basklass för alla stödda typsnittstyper som en resurs för HTML-dokumentet med alla dess egenskaper"
type: docs
weight: 11
url: /sv/nodejs-java/com.groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.IHtmlResource](../../com.groupdocs.editor.htmlcss.resources/ihtmlresource)
```
public abstract class FontResourceBase implements IHtmlResource
```

Basklass för alla stödda typsnittstyper som en resurs för HTML-dokumentet
med alla dess egenskaper

## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [FontResourceBase()](#FontResourceBase--) |  |
## Fält

| Fält | Beskrivning |
| --- | --- |
|  | [Disposed](#Disposed) | Händelse som inträffar när detta typsnitt har frigjorts |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getName()](#getName--) | Returnerar namn på denna typsnittresurs. |
|
|  | [getFilenameWithExtension()](#getFilenameWithExtension--) | Returnerar korrekt filnamn för denna typsnittresurs, som består av namn |
och filändelse.
|
|  | [getByteContent()](#getByteContent--) | Returnerar innehållet i detta teckensnitt som byte stream |
|
|  | [getTextContent()](#getTextContent--) | Returnerar innehållet i detta typsnitt som en base64-kodad sträng. |
|
|  | [save(String fullPathToFile)](#save-java.lang.String-) | Sparar detta typsnitt till den angivna filen |
|
|  | [equals(IHtmlResource other)](#equals-com.groupdocs.editor.htmlcss.resources.IHtmlResource-) | Kontrollerar denna instans med angiven HTML‑resurs för referenslikhet |
|
|  | [equals(FontResourceBase other)](#equals-com.groupdocs.editor.htmlcss.resources.fonts.FontResourceBase-) | Kontrollerar denna instans med angiven teckensnitt‑resurs för referenslikhet |
|
|  | [dispose()](#dispose--) | Frigör denna typsnittresurs, frigör dess innehåll och gör mest |
metoder och egenskaper icke-fungerande
|
|  | [isDisposed()](#isDisposed--) | Avgör om detta typsnitt är frigjort eller inte |
|
|  | [getType()](#getType--) | I implementeringen bör typen returnera information om typen av specifik |
typsnittresurs som en instans av en specifik FontType-typ, som
inkapslar all typ-specifik information
|
### FontResourceBase() {#FontResourceBase--}
```
public FontResourceBase()
```


### Disposed {#Disposed}
```
public final Event<EventHandler> Disposed
```


Händelse som inträffar när detta typsnitt har frigjorts


### getName() {#getName--}
```
public final String getName()
```


Returnerar namn på denna typsnittresurs. Innehåller vanligtvis inte filnamn
filändelse och kan teoretiskt skilja sig från filnamnet.


**Returns:**
java.lang.String
### getFilenameWithExtension() {#getFilenameWithExtension--}
```
public final String getFilenameWithExtension()
```


Returnerar korrekt filnamn för denna typsnittresurs, som består av namn
och filändelse. Kan teoretiskt skilja sig från namnet.


**Returns:**
java.lang.String
### getByteContent() {#getByteContent--}
```
public final InputStream getByteContent()
```


Returnerar innehållet i detta teckensnitt som byte stream


**Returns:**
java.io.InputStream -
### getTextContent() {#getTextContent--}
```
public final String getTextContent()
```


Returnerar innehållet i detta typsnitt som en base64-kodad sträng. Detta värde är
cachat efter första anropet.


**Returns:**
java.lang.String -
### save(String fullPathToFile) {#save-java.lang.String-}
```
public final void save(String fullPathToFile)
```


Sparar detta typsnitt till den angivna filen


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | fullPathToFile | java.lang.String | Fullständig sökväg till filen som kommer att skapas eller skrivas om |
|

### equals(IHtmlResource other) {#equals-com.groupdocs.editor.htmlcss.resources.IHtmlResource-}
```
public final boolean equals(IHtmlResource other)
```


Kontrollerar denna instans med angiven HTML‑resurs för referenslikhet


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | other | [IHtmlResource](../../com.groupdocs.editor.htmlcss.resources/ihtmlresource) | Annan implementering av IHtmlResource‑gränssnittet |
|

**Returns:**
boolean - Sant om de är lika, falskt om de är olika

### equals(FontResourceBase other) {#equals-com.groupdocs.editor.htmlcss.resources.fonts.FontResourceBase-}
```
public final boolean equals(FontResourceBase other)
```


Kontrollerar denna instans med angiven teckensnitt‑resurs för referenslikhet


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | other | [FontResourceBase](../../com.groupdocs.editor.htmlcss.resources.fonts/fontresourcebase) | Annan ärvd klass av den abstrakta klassen FontResourceBase |
|

**Returns:**
boolean - Sant om de är lika, falskt om de är olika

### dispose() {#dispose--}
```
public final void dispose()
```


Frigör denna typsnittresurs, frigör dess innehåll och gör mest
metoder och egenskaper icke-fungerande


### isDisposed() {#isDisposed--}
```
public final boolean isDisposed()
```


Avgör om detta typsnitt är frigjort eller inte


**Returns:**
boolean -
### getType() {#getType--}
```
public abstract FontType getType()
```


I implementeringen bör typen returnera information om typen av specifik
typsnittresurs som en instans av en specifik FontType-typ, som
inkapslar all typ-specifik information


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype)
