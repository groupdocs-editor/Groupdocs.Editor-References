---
title: "GetBodyContent"
second_title: "Référence API GroupDocs.Editor pour .NET"
description: "Renvoie le corps du contenu interne du document HTML situé entre les balises d'ouverture et de fermeture BODY, sans ces balises, sous forme de chaîne."
type: docs
weight: 120
url: /fr/net/groupdocs.editor/editabledocument/getbodycontent/
---
## GetBodyContent() {#getbodycontent}

Renvoie le corps du document HTML (contenu interne entre les balises BODY d'ouverture et de fermeture, sans ces balises) sous forme de chaîne.

```csharp
public string GetBodyContent()
```

### Valeur de retour

Chaîne contenant le corps du document HTML (sans les balises d'ouverture et de fermeture BODY).

### Remarques

La plupart des éditeurs WYSIWYG opèrent généralement avec le contenu interne du BODY du document et ne peuvent pas traiter correctement ses métadonnées provenant du bloc HEAD. Cette méthode est conçue pour ces cas. Cette surcharge ne permet pas d'ajuster les URI pour les requêtes de ressources externes.

### Voir aussi

* class [EditableDocument](../../editabledocument)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## GetBodyContent(string) {#getbodycontent_1}

Renvoie le corps du document HTML (contenu interne entre les balises BODY d'ouverture et de fermeture, sans ces balises) sous forme de chaîne, où les liens vers les ressources externes contiennent le modèle spécifié avec des espaces réservés.

```csharp
public string GetBodyContent(string externalImagesTemplate)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| externalImagesTemplate | String | Grâce à ce paramètre, l'utilisateur peut spécifier un modèle de chaîne avec un espace réservé, qui sera appliqué aux liens de toutes les images externes dans les éléments IMG présents dans la chaîne HTML résultante. Si NULL ou vide, le modèle ne sera pas ajouté et seuls les noms de fichiers seront présents dans le balisage HTML résultant. Si le modèle est invalide, il sera traité comme un préfixe, de sorte que les noms de fichiers seront concaténés à sa fin. |

### Valeur de retour

Chaîne contenant le corps du document HTML (sans les balises d'ouverture et de fermeture BODY) avec des liens ajustés aux images externes.

### Remarques

La plupart des éditeurs WYSIWYG opèrent généralement avec le contenu interne du BODY du document et ne peuvent pas traiter correctement ses métadonnées provenant du bloc HEAD. Cette méthode est conçue pour ces cas. Cette surcharge permet d'ajuster les URI pour les requêtes de ressources externes.

### Voir aussi

* class [EditableDocument](../../editabledocument)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.editor.dll -->
