---
title: "SaveOneResource"
second_title: "Référence API GroupDocs.Editor pour .NET"
description: "Méthode d'instance déclenchée lors de l’appel de la méthode Savegroupdocs.editor/editabledocument/save et qui doit être implémentée par l'utilisateur final afin d'obtenir et d'enregistrer la ressource HTML fournie, puis de renvoyer un lien vers cette ressource à l'appelant."
type: docs
weight: 10
url: /fr/net/groupdocs.editor.options/ihtmlsavingcallback/saveoneresource/
---
## IHtmlSavingCallback.SaveOneResource method

Méthode d'instance, déclenchée lors de l’appel de la méthode [`Save`](../../../groupdocs.editor/editabledocument/save) et qui doit être implémentée par l'utilisateur final afin d'obtenir et d'enregistrer la ressource HTML fournie, puis de renvoyer un lien vers cette ressource à l'appelant.

```csharp
public string SaveOneResource(IHtmlResource resource)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| ressource | IHtmlResource | Ressource HTML de tout type (images et polices, éventuellement des feuilles de style si elles ne sont pas intégrées dans le balisage HTML), qui est transmise par GroupDocs.Editor à l’implémentation définie par l’utilisateur de cette interface, obtenue par l’utilisateur, et l’utilisateur peut effectuer toutes les procédures nécessaires telles que l’enregistrement, l’envoi, la conversion, etc. GroupDocs.Editor ne transmettra jamais une ressource HTML `null` à cette méthode. |

### Valeur de retour

Un lien (référence) vers la ressource, obtenu dans le paramètre *resource*, que l'utilisateur doit fournir à GroupDocs.Editor, afin que GroupDocs.Editor insère ce lien dans le balisage HTML.

### Remarques

GroupDocs.Editor s’attend à ce que l’implémentation définie par l’utilisateur de cette méthode ne lève pas d’exception pendant son exécution. Cependant, lorsqu’une exception se produit, GroupDocs.Editor écrira la valeur de la propriété [`FilenameWithExtension`](../../../groupdocs.editor.htmlcss.resources/ihtmlresource/filenamewithextension) dans le balisage HTML.

### Voir aussi

* interface [IHtmlResource](../../../groupdocs.editor.htmlcss.resources/ihtmlresource)
* interface [IHtmlSavingCallback](../../ihtmlsavingcallback)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.editor.dll -->
