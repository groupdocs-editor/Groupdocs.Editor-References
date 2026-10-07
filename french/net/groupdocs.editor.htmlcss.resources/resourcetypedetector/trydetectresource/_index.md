---
title: "TryDetectResource"
second_title: "Référence API GroupDocs.Editor pour .NET"
description: "Tente d'analyser un flux d'entrée et crée l'une des ressources HTML prises en charge à partir de celui-ci en tenant compte d'un type supposé spécifié s'il n'est pas null"
type: docs
weight: 20
url: /fr/net/groupdocs.editor.htmlcss.resources/resourcetypedetector/trydetectresource/
---
## ResourceTypeDetector.TryDetectResource method

Tente d'analyser un flux d'entrée et crée l'une des ressources HTML prises en charge à partir de celui-ci, en tenant compte d'un type supposé spécifié, s'il n'est pas nul

```csharp
public static IHtmlResource TryDetectResource(Stream inputResourceStream, string name, 
    IResourceType assumptiveFormat)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| inputResourceStream | Stream | Flux d'entrée, qui contient probablement une ressource HTML. Si invalide, une exception sera levée. |
| nom | String | Nom de la ressource, qui sera utilisé pour la ressource créée et renvoyée en cas de succès. Ne peut pas être NULL, vide ou composé d'espaces |
| assumptiveFormat | IResourceType | Format supposé de la ressource HTML d'entrée, utile pour obtenir les meilleures performances. Si complètement inconnu, utilisez la valeur NULL. Peut être incorrect, cela ne fera qu'aggraver les performances. |

### Valeur de retour

Instance qui implémente l'interface 'IHtmlResource' et représente l'une des ressources HTML prises en charge en cas de succès, ou NULL en cas d'échec

### Voir aussi

* interface [IHtmlResource](../../ihtmlresource)
* interface [IResourceType](../../iresourcetype)
* class [ResourceTypeDetector](../../resourcetypedetector)
* namespace [GroupDocs.Editor.HtmlCss.Resources](../../../groupdocs.editor.htmlcss.resources)
* assembly [GroupDocs.Editor](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.editor.dll -->
