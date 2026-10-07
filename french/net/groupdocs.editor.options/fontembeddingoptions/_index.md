---
title: "FontEmbeddingOptions"
second_title: "Référence API GroupDocs.Editor pour .NET"
description: "Les options d'incorporation de police contrôlent quelles ressources de police doivent être intégrées dans le document WordProcessing ou PDF de sortie"
type: docs
weight: 880
url: /fr/net/groupdocs.editor.options/fontembeddingoptions/
---
## FontEmbeddingOptions enumeration

Les options d'incorporation de police contrôlent quelles ressources de police doivent être intégrées dans le document WordProcessing ou PDF de sortie

```csharp
public enum FontEmbeddingOptions
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| NotEmbed | `0` | N'intègre aucune ressource de police, ni depuis EditableDocument ni depuis le système. Valeur par défaut. |
| EmbedAll | `1` | Analyse le contenu du document à partir de l'EditableDocument d'entrée, trouve toutes les polices utilisées et les intègre dans le document WordProcessing ou PDF de sortie. Dans un premier temps, GroupDocs.Editor récupère les polices à partir des ressources de police présentes dans l'EditableDocument. Si elles sont insuffisantes ou manquantes, alors GroupDocs.Editor récupère les polices depuis le système d'exploitation. |
| EmbedWithoutSystem | `2` | Identique à EmbedAll, mais exclut les polices que le système d'exploitation considère comme polices système. |

### Remarques

Les options d'intégration des polices sont appliquées lors de l'enregistrement du document (du EditableDocument intermédiaire vers le format WordProcessing ou PDF de sortie). Cette énumération est incluse en tant que propriété dans WordProcessingSaveOptions et PdfSaveOptions, d'où elle doit être utilisée.

### Voir aussi

* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.editor.dll -->
