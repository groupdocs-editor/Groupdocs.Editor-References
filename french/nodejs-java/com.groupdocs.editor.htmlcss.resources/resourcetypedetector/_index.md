---
title: "ResourceTypeDetector"
second_title: "Référence d'API GroupDocs.Editor pour Node.js via Java"
description: "Méthodes statiques utilitaires pour détecter les types et formats de ressources"
type: docs
weight: 10
url: /fr/nodejs-java/com.groupdocs.editor.htmlcss.resources/resourcetypedetector/
---
**Inheritance:**
java.lang.Object
```
public class ResourceTypeDetector
```

Méthodes statiques utilitaires pour détecter les types de ressources (formats).

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [ResourceTypeDetector()](#ResourceTypeDetector--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [detectTypeFromFilename(String filename)](#detectTypeFromFilename-java.lang.String-) | Détecte un type à partir du nom de fichier spécifié et renvoie une instance de |
IResourceType respectif
|
|  | [tryDetectResource(InputStream inputResourceStream, String name, IResourceType assumptiveFormat)](#tryDetectResource-java.io.InputStream-java.lang.String-com.groupdocs.editor.htmlcss.resources.IResourceType-) | Essaie d'analyser un flux d'entrée et crée l'un des HTML supportables |
ressources à partir de celui-ci, en tenant compte d'un type supposé spécifié, si celui-ci
n'est pas nul
|
### ResourceTypeDetector() {#ResourceTypeDetector--}
```
public ResourceTypeDetector()
```


### detectTypeFromFilename(String filename) {#detectTypeFromFilename-java.lang.String-}
```
public static IResourceType detectTypeFromFilename(String filename)
```


Détecte un type à partir du nom de fichier spécifié et renvoie une instance de
IResourceType respectif


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | nom de fichier | java.lang.String | Nom de fichier d'entrée, à partir duquel cette méthode tentera d'extraire l'implémentation IResourceType résultante |
|

**Returns:**
[IResourceType](../../com.groupdocs.editor.htmlcss.resources/iresourcetype) - IResourceType implementation on success or NULL on failure

### tryDetectResource(InputStream inputResourceStream, String name, IResourceType assumptiveFormat) {#tryDetectResource-java.io.InputStream-java.lang.String-com.groupdocs.editor.htmlcss.resources.IResourceType-}
```
public static IHtmlResource tryDetectResource(InputStream inputResourceStream, String name, IResourceType assumptiveFormat)
```


Essaie d'analyser un flux d'entrée et crée l'un des HTML supportables
ressources à partir de celui-ci, en tenant compte d'un type supposé spécifié, si celui-ci
n'est pas nul


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | inputResourceStream | java.io.InputStream | Flux d'entrée, qui contient probablement une ressource HTML. Si invalide, une exception sera levée. |
|
|  | name | java.lang.String | Nom de la ressource, qui sera utilisé pour la ressource créée et renvoyée en cas de succès. Ne peut pas être NULL, vide ou contenant uniquement des espaces |
|
|  | assumptiveFormat | [IResourceType](../../com.groupdocs.editor.htmlcss.resources/iresourcetype) | Format supposé de la ressource HTML d'entrée, qui est utile pour obtenir les meilleures performances. Si complètement inconnu, utilisez la valeur NULL. Peut être incorrect, cela ne fera qu'aggraver les performances. |
|

**Returns:**
[IHtmlResource](../../com.groupdocs.editor.htmlcss.resources/ihtmlresource) - Instance, which implements 'IHtmlResource' interface and represents one of supportable HTML resources on success, or NULL on failure

