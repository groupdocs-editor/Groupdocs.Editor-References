---
title: "ResourceTypeDetector"
second_title: "GroupDocs.Editor for Java API-referentie"
description: "Utility statische methoden voor het detecteren van resource‑type‑formaten"
type: docs
weight: 10
url: /nl/java/com.groupdocs.editor.htmlcss.resources/resourcetypedetector/
---
**Inheritance:**
java.lang.Object
```
public class ResourceTypeDetector
```

Utility statische methoden voor het detecteren van resource types (formaten)

## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [ResourceTypeDetector()](#ResourceTypeDetector--) |  |
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [detectTypeFromFilename(String filename)](#detectTypeFromFilename-java.lang.String-) | Detecteert een type op basis van de opgegeven bestandsnaam en retourneert een instantie van |
respectieve IResourceType
|
|  | [tryDetectResource(InputStream inputResourceStream, String name, IResourceType assumptiveFormat)](#tryDetectResource-java.io.InputStream-java.lang.String-com.groupdocs.editor.htmlcss.resources.IResourceType-) | Probeert een invoerstroom te analyseren en maakt een van de ondersteunde HTML |
resources ervan, rekening houdend met een gespecificeerd verondersteld type, indien het
is niet null
|
### ResourceTypeDetector() {#ResourceTypeDetector--}
```
public ResourceTypeDetector()
```


### detectTypeFromFilename(String filename) {#detectTypeFromFilename-java.lang.String-}
```
public static IResourceType detectTypeFromFilename(String filename)
```


Detecteert een type op basis van de opgegeven bestandsnaam en retourneert een instantie van
respectieve IResourceType


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | bestandsnaam | java.lang.String | Invoernaam, waarvan deze methode zal proberen de resulterende IResourceType-implementatie te extraheren |
|

**Returns:**
[IResourceType](../../com.groupdocs.editor.htmlcss.resources/iresourcetype) - IResourceType implementation on success or NULL on failure

### tryDetectResource(InputStream inputResourceStream, String name, IResourceType assumptiveFormat) {#tryDetectResource-java.io.InputStream-java.lang.String-com.groupdocs.editor.htmlcss.resources.IResourceType-}
```
public static IHtmlResource tryDetectResource(InputStream inputResourceStream, String name, IResourceType assumptiveFormat)
```


Probeert een invoerstroom te analyseren en maakt een van de ondersteunde HTML
resources ervan, rekening houdend met een gespecificeerd verondersteld type, indien het
is niet null


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | inputResourceStream | java.io.InputStream | Invoerstroom, die vermoedelijk een HTML-resource bevat. Indien ongeldig, wordt er een uitzondering gegooid. |
|
|  | naam | java.lang.String | Resourcenaam, die zal worden gebruikt voor de gecreëerde en geretourneerde resource bij succes. Mag niet NULL, leeg of witruimte zijn |
|
|  | assumptiveFormat | [IResourceType](../../com.groupdocs.editor.htmlcss.resources/iresourcetype) | Aangenomen formaat van de invoer‑HTML-resource, wat nuttig is voor het behalen van de beste prestaties. Indien volledig onbekend, gebruik de NULL‑waarde. Kan onjuist zijn; dit zal alleen de prestaties verslechteren. |
|

**Returns:**
[IHtmlResource](../../com.groupdocs.editor.htmlcss.resources/ihtmlresource) - Instance, which implements 'IHtmlResource' interface and represents one of supportable HTML resources on success, or NULL on failure

