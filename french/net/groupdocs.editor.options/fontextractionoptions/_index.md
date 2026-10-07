---
title: "FontExtractionOptions"
second_title: "Référence API GroupDocs.Editor pour .NET"
description: "Les options d'extraction de police contrôlent quelles polices doivent être extraites et d'où"
type: docs
weight: 890
url: /fr/net/groupdocs.editor.options/fontextractionoptions/
---
## FontExtractionOptions enumeration

Les options d'extraction de police contrôlent quelles polices doivent être extraites et d'où

```csharp
public enum FontExtractionOptions
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| NotExtract | `0` | N'extrait aucune ressource de police, ni du document ni du système. Valeur par défaut. |
| ExtractAllEmbedded | `1` | Extrait toutes les ressources de police qui sont incorporées dans le document Word d'entrée, quel que soit leur type : personnalisé ou système. |
| ExtractEmbeddedWithoutSystem | `2` | Extrait uniquement les ressources de police incorporées qui sont personnalisées (et non système). |
| ExtractAll | `3` | Tente d'extraire toutes les polices utilisées dans le document WordProcessing d'entrée, y compris les polices système. |

### Voir aussi

* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.editor.dll -->
