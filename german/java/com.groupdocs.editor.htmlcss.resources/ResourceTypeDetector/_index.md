---
title: "ResourceTypeDetector"
second_title: "GroupDocs.Editor für Java API-Referenz"
description: "Hilfs‑statische Methoden zum Erkennen von Ressourcentypen und -formaten"
type: docs
weight: 10
url: /de/java/com.groupdocs.editor.htmlcss.resources/resourcetypedetector/
---
**Inheritance:**
java.lang.Object
```
public class ResourceTypeDetector
```

Statische Hilfsmethoden zum Erkennen von Ressourcentypen (Formaten).

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [ResourceTypeDetector()](#ResourceTypeDetector--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [detectTypeFromFilename(String filename)](#detectTypeFromFilename-java.lang.String-) | Erkennt einen Typ anhand des angegebenen Dateinamens und gibt eine Instanz zurück von |
der jeweiligen IResourceType
|
|  | [tryDetectResource(InputStream inputResourceStream, String name, IResourceType assumptiveFormat)](#tryDetectResource-java.io.InputStream-java.lang.String-com.groupdocs.editor.htmlcss.resources.IResourceType-) | Versucht, einen Eingabestream zu analysieren und erstellt eines der unterstützten HTML |
Ressourcen daraus, wobei ein angegebener angenommener Typ berücksichtigt wird, falls er
nicht null ist
|
### ResourceTypeDetector() {#ResourceTypeDetector--}
```
public ResourceTypeDetector()
```


### detectTypeFromFilename(String filename) {#detectTypeFromFilename-java.lang.String-}
```
public static IResourceType detectTypeFromFilename(String filename)
```


Erkennt einen Typ anhand des angegebenen Dateinamens und gibt eine Instanz zurück von
der jeweiligen IResourceType


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Dateiname | java.lang.String | Eingabedateiname, aus dem diese Methode versucht, die resultierende IResourceType-Implementierung zu extrahieren |
|

**Returns:**
[IResourceType](../../com.groupdocs.editor.htmlcss.resources/iresourcetype) - IResourceType implementation on success or NULL on failure

### tryDetectResource(InputStream inputResourceStream, String name, IResourceType assumptiveFormat) {#tryDetectResource-java.io.InputStream-java.lang.String-com.groupdocs.editor.htmlcss.resources.IResourceType-}
```
public static IHtmlResource tryDetectResource(InputStream inputResourceStream, String name, IResourceType assumptiveFormat)
```


Versucht, einen Eingabestream zu analysieren und erstellt eines der unterstützten HTML
Ressourcen daraus, wobei ein angegebener angenommener Typ berücksichtigt wird, falls er
nicht null ist


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | inputResourceStream | java.io.InputStream | Eingabestream, der vermutlich eine HTML‑Ressource enthält. Bei Ungültigkeit wird eine Ausnahme ausgelöst. |
|
|  | Name | java.lang.String | Ressourcenname, der bei Erfolg für die erstellte und zurückgegebene Ressource verwendet wird. Darf nicht NULL, leer oder nur Leerzeichen sein |
|
|  | assumptiveFormat | [IResourceType](../../com.groupdocs.editor.htmlcss.resources/iresourcetype) | Angenommenes Format der Eingabe‑HTML‑Ressource, das für die bestmögliche Leistung nützlich ist. Wenn völlig unbekannt, verwenden Sie den NULL‑Wert. Kann inkorrekt sein, was die Leistung nur verschlechtern wird. |
|

**Returns:**
[IHtmlResource](../../com.groupdocs.editor.htmlcss.resources/ihtmlresource) - Instance, which implements 'IHtmlResource' interface and represents one of supportable HTML resources on success, or NULL on failure

