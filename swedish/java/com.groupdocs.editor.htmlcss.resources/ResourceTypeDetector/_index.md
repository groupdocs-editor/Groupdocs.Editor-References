---
title: "ResourceTypeDetector"
second_title: "GroupDocs.Editor för Java API-referens"
description: "Statisk verktygsmetoder för att upptäcka resursers typer och format"
type: docs
weight: 10
url: /sv/java/com.groupdocs.editor.htmlcss.resources/resourcetypedetector/
---
**Inheritance:**
java.lang.Object
```
public class ResourceTypeDetector
```

Statisk verktygsmetoder för att upptäcka resurstyp (format).

## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [ResourceTypeDetector()](#ResourceTypeDetector--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [detectTypeFromFilename(String filename)](#detectTypeFromFilename-java.lang.String-) | Detekterar en typ från angivet filnamn och returnerar en instans av |
respektive IResourceType
|
|  | [tryDetectResource(InputStream inputResourceStream, String name, IResourceType assumptiveFormat)](#tryDetectResource-java.io.InputStream-java.lang.String-com.groupdocs.editor.htmlcss.resources.IResourceType-) | Försöker analysera en indataström och skapar en av de stödjade HTML |
resurser från den, med hänsyn till en angiven antagen typ, om den
är inte null
|
### ResourceTypeDetector() {#ResourceTypeDetector--}
```
public ResourceTypeDetector()
```


### detectTypeFromFilename(String filename) {#detectTypeFromFilename-java.lang.String-}
```
public static IResourceType detectTypeFromFilename(String filename)
```


Detekterar en typ från angivet filnamn och returnerar en instans av
respektive IResourceType


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | filnamn | java.lang.String | Indatafilnamn, från vilket denna metod kommer att försöka extrahera den resulterande IResourceType‑implementeringen |
|

**Returns:**
[IResourceType](../../com.groupdocs.editor.htmlcss.resources/iresourcetype) - IResourceType implementation on success or NULL on failure

### tryDetectResource(InputStream inputResourceStream, String name, IResourceType assumptiveFormat) {#tryDetectResource-java.io.InputStream-java.lang.String-com.groupdocs.editor.htmlcss.resources.IResourceType-}
```
public static IHtmlResource tryDetectResource(InputStream inputResourceStream, String name, IResourceType assumptiveFormat)
```


Försöker analysera en indataström och skapar en av de stödjade HTML
resurser från den, med hänsyn till en angiven antagen typ, om den
är inte null


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | inputResourceStream | java.io.InputStream | Indataström, som förmodligen innehåller en HTML-resurs. Om den är ogiltig kastas ett undantag. |
|
|  | namn | java.lang.String | Resursnamn, som kommer att användas för den skapade och returnerade resursen vid lyckat resultat. Får inte vara NULL, tomt eller enbart blanksteg |
|
|  | assumptiveFormat | [IResourceType](../../com.groupdocs.editor.htmlcss.resources/iresourcetype) | Antaget format för den indatade HTML-resursen, vilket är användbart för att uppnå bästa prestanda. Om det är helt okänt, använd NULL‑värdet. Kan vara felaktigt, vilket bara försämrar prestandan. |
|

**Returns:**
[IHtmlResource](../../com.groupdocs.editor.htmlcss.resources/ihtmlresource) - Instance, which implements 'IHtmlResource' interface and represents one of supportable HTML resources on success, or NULL on failure

