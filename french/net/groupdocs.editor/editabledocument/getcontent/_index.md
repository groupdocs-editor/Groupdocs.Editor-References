---
title: "GetContent"
second_title: "Référence API GroupDocs.Editor pour .NET"
description: "Renvoie le contenu complet du document HTML sous forme de flux d'octets en écrivant ce contenu dans le flux spécifié avec l'encodage texte indiqué"
type: docs
weight: 130
url: /fr/net/groupdocs.editor/editabledocument/getcontent/
---
## GetContent&lt;TStream&gt;(TStream, Encoding) {#getcontent_2}

Renvoie le contenu complet du document HTML sous forme de flux d'octets en écrivant ce contenu dans le flux spécifié avec l'encodage texte indiqué

```csharp
public TStream GetContent<TStream>(TStream storage, Encoding encoding)
    where TStream : Stream
```

| Paramètre | Description |
| --- | --- |
| TStream | Toute implémentation du Stream |
| storage | Flux d'octets non nul, qui prend en charge l'écriture |
| encoding | Encodage de texte non nul, qui doit être appliqué lors de l'écriture du contenu texte dans le *storage* spécifié |

### Valeur de retour

Instance du *storage* spécifié

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Un des arguments d'entrée est nul |
| ArgumentException | Le flux spécifié n'est pas accessible en écriture |

### Voir aussi

* class [EditableDocument](../../editabledocument)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## GetContent() {#getcontent}

Renvoie le contenu complet du document HTML sous forme de chaîne.

```csharp
public string GetContent()
```

### Valeur de retour

Chaîne contenant le contenu du document HTML

### Voir aussi

* class [EditableDocument](../../editabledocument)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## GetContent(string, string) {#getcontent_1}

Renvoie le contenu complet du document HTML sous forme de chaîne, où les liens vers les ressources externes contiennent le modèle spécifié avec des espaces réservés.

```csharp
public string GetContent(string externalImagesTemplate, string externalCssTemplate)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| externalImagesTemplate | String | Grâce à ce paramètre, l'utilisateur peut spécifier un modèle de chaîne avec un espace réservé, qui sera appliqué aux liens de toutes les images externes dans les éléments IMG présents dans la chaîne HTML résultante. Si NULL ou vide, le modèle ne sera pas ajouté et seuls les noms de fichiers seront présents dans le balisage HTML résultant. Si le modèle est invalide, il sera traité comme un préfixe, de sorte que les noms de fichiers seront concaténés à sa fin. |
| externalCssTemplate | String | Grâce à ce paramètre, il est possible de spécifier un modèle de chaîne avec un espace réservé, qui sera ajouté aux liens de toutes les feuilles de style externes dans les éléments LINK, présents dans la chaîne HTML résultante. Si NULL ou vide, le modèle ne sera pas ajouté et seuls les noms de fichiers seront présents dans le balisage HTML résultant. Si le modèle est invalide, il sera traité comme un préfixe, de sorte que les noms de fichiers seront concaténés à sa fin. |

### Valeur de retour

Chaîne contenant le contenu du document HTML avec les liens, ajustée aux ressources externes

### Voir aussi

* class [EditableDocument](../../editabledocument)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.editor.dll -->
