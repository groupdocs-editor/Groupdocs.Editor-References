---
title: "ResourceTypeDetector"
second_title: "GroupDocs.Editor per Java Riferimento API"
description: "Metodi statici di utilità per rilevare i formati dei tipi di risorsa"
type: docs
weight: 10
url: /it/java/com.groupdocs.editor.htmlcss.resources/resourcetypedetector/
---
**Inheritance:**
java.lang.Object
```
public class ResourceTypeDetector
```

Metodi statici di utilità per rilevare i tipi di risorsa (formati).

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [ResourceTypeDetector()](#ResourceTypeDetector--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [detectTypeFromFilename(String filename)](#detectTypeFromFilename-java.lang.String-) | Rileva un tipo dal nome file specificato e restituisce un'istanza di |
rispettivo IResourceType
|
|  | [tryDetectResource(InputStream inputResourceStream, String name, IResourceType assumptiveFormat)](#tryDetectResource-java.io.InputStream-java.lang.String-com.groupdocs.editor.htmlcss.resources.IResourceType-) | Cerca di analizzare un flusso di input e crea uno dei formati HTML supportati |
risorse da esso, tenendo conto di un tipo presumibile specificato, se è
non è nullo
|
### ResourceTypeDetector() {#ResourceTypeDetector--}
```
public ResourceTypeDetector()
```


### detectTypeFromFilename(String filename) {#detectTypeFromFilename-java.lang.String-}
```
public static IResourceType detectTypeFromFilename(String filename)
```


Rileva un tipo dal nome file specificato e restituisce un'istanza di
rispettivo IResourceType


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | nome file | java.lang.String | Nome file di input, dal quale questo metodo cercherà di estrarre l'implementazione IResourceType risultante |
|

**Returns:**
[IResourceType](../../com.groupdocs.editor.htmlcss.resources/iresourcetype) - IResourceType implementation on success or NULL on failure

### tryDetectResource(InputStream inputResourceStream, String name, IResourceType assumptiveFormat) {#tryDetectResource-java.io.InputStream-java.lang.String-com.groupdocs.editor.htmlcss.resources.IResourceType-}
```
public static IHtmlResource tryDetectResource(InputStream inputResourceStream, String name, IResourceType assumptiveFormat)
```


Cerca di analizzare un flusso di input e crea uno dei formati HTML supportati
risorse da esso, tenendo conto di un tipo presumibile specificato, se è
non è nullo


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | inputResourceStream | java.io.InputStream | Flusso di input, che presumibilmente contiene una risorsa HTML. Se non valido, verrà generata un'eccezione. |
|
|  | nome | java.lang.String | Nome della risorsa, che sarà usato per la risorsa creata e restituita in caso di successo. Non può essere NULL, vuoto o solo spazi |
|
|  | assumptiveFormat | [IResourceType](../../com.groupdocs.editor.htmlcss.resources/iresourcetype) | Formato presunto della risorsa HTML di input, utile per ottenere le migliori prestazioni. Se completamente sconosciuto, utilizzare il valore NULL. Potrebbe essere errato, il che peggiorerà solo le prestazioni. |
|

**Returns:**
[IHtmlResource](../../com.groupdocs.editor.htmlcss.resources/ihtmlresource) - Instance, which implements 'IHtmlResource' interface and represents one of supportable HTML resources on success, or NULL on failure

