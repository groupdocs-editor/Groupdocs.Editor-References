---
title: "GetCssContent"
second_title: "Référence API GroupDocs.Editor pour .NET"
description: "Renvoie le contenu de toutes les feuilles de style externes sous forme de liste de chaînes où chaque chaîne représente une feuille de style. Renvoie une liste vide s'il n'y a aucun CSS pour ce document."
type: docs
weight: 140
url: /fr/net/groupdocs.editor/editabledocument/getcsscontent/
---
## GetCssContent() {#getcsscontent}

Renvoie le contenu de toutes les feuilles de style externes sous forme d'une liste de chaînes, chaque chaîne représentant une feuille de style. Renvoie une liste vide s'il n'existe aucun CSS pour ce document.

```csharp
public List<string> GetCssContent()
```

### Valeur de retour

Une liste de chaînes, où chaque chaîne contient le contenu d'un document CSS.

### Voir aussi

* class [EditableDocument](../../editabledocument)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## GetCssContent(string, string) {#getcsscontent_1}

Renvoie le contenu de toutes les feuilles de style externes sous forme d'une liste de chaînes, chaque chaîne représentant une feuille de style. Le préfixe spécifié sera appliqué à chaque lien vers la ressource externe dans chaque feuille de style résultante. Renvoie une liste vide s'il n'existe aucun CSS pour ce document.

```csharp
public List<string> GetCssContent(string externalImagesPrefix, string externalFontsPrefix)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| externalImagesPrefix | String | Grâce à ce paramètre, il est possible de spécifier un préfixe qui sera ajouté aux liens de toutes les images externes présentes dans les déclarations CSS des chaînes CSS résultantes. Si NULL ou vide, aucun préfixe ne sera ajouté. |
| externalFontsPrefix | String | Grâce à ce paramètre, il est possible de spécifier un préfixe qui sera ajouté aux liens de toutes les polices externes dans les règles @font-face des chaînes CSS résultantes. Si NULL ou vide, aucun préfixe ne sera ajouté. |

### Valeur de retour

Une liste de chaînes, où chaque chaîne contient le contenu d'un document CSS.

### Voir aussi

* class [EditableDocument](../../editabledocument)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.editor.dll -->
