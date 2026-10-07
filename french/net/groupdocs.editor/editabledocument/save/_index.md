---
title: "Save"
second_title: "Référence API GroupDocs.Editor pour .NET"
description: "Enregistre ce document HTML dans le fichier au chemin spécifié où le balisage HTML sera stocké et dans le dossier d'accompagnement contenant les ressources."
type: docs
weight: 160
url: /fr/net/groupdocs.editor/editabledocument/save/
---
## Save(string) {#save_1}

Enregistre ce document HTML dans le fichier au chemin spécifié, où le balisage HTML sera stocké, ainsi que dans le dossier d'accompagnement contenant les ressources.

```csharp
public void Save(string htmlFilePath)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| htmlFilePath | String | Chemin complet du fichier où le balisage HTML sera stocké. Le fichier sera créé ou écrasé s'il existe. Le dossier de ressources d'accompagnement sera créé dans le même répertoire où le fichier HTML existe. |

### Voir aussi

* class [EditableDocument](../../editabledocument)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## Save(string, string) {#save_2}

Enregistre ce document HTML dans le fichier au chemin spécifié, où le balisage HTML sera stocké, ainsi que dans le dossier d'accompagnement contenant les ressources, qui se trouve au chemin indiqué.

```csharp
public void Save(string htmlFilePath, string resourcesFolderPath)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| htmlFilePath | String | Chemin complet du fichier où le balisage HTML sera stocké. Ne peut pas être NULL ou vide. Le fichier sera créé ou écrasé s'il existe. |
| resourcesFolderPath | String | Chemin complet du dossier d'accompagnement où toutes les ressources associées seront stockées. Si NULL ou vide, le dossier sera créé automatiquement dans le même répertoire que le fichier *.html. S'il est spécifié et n'existe pas, il sera créé. |

### Voir aussi

* class [EditableDocument](../../editabledocument)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## Save(TextWriter, HtmlSaveOptions) {#save}

Enregistre le contenu de ce [`EditableDocument`](../../editabledocument) en tant que document HTML vers le TextWriter spécifié, tandis que le deuxième paramètre d'options permet de personnaliser la procédure d'enregistrement et de spécifier le rappel d'enregistrement des ressources.

```csharp
public void Save(TextWriter htmlMarkup, HtmlSaveOptions saveOptions)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| htmlMarkup | TextWriter | Implémentation du TextWriter dans lequel le balisage HTML sera écrit. Ne peut pas être nul. |
| saveOptions | HtmlSaveOptions | Options d'enregistrement HTML qui contrôlent la procédure d'enregistrement : comment le balisage HTML est stocké (noms des balises, types de guillemets) et comment et où seront enregistrés les CSS et autres ressources comme les images ou les polices. L'utilisateur doit spécifier l'implémentation de l'interface dans la propriété [`SavingCallback`](../../../groupdocs.editor.options/htmlsaveoptions/savingcallback) pour contrôler la façon dont les ressources doivent être enregistrées et référencées depuis le balisage HTML. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | L'un des arguments spécifiés ou la propriété `SavingCallback` dans *saveOptions* est `null`. |

### Voir aussi

* class [HtmlSaveOptions](../../../groupdocs.editor.options/htmlsaveoptions)
* class [EditableDocument](../../editabledocument)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.editor.dll -->
