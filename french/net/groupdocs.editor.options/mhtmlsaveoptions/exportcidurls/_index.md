---
title: "ExportCidUrls"
second_title: "Référence API GroupDocs.Editor pour .NET"
description: "Spécifie s'il faut utiliser les URL CID ContentID pour référencer les ressources images, polices, CSS incluses dans les documents MHTML. La valeur par défaut est false."
type: docs
weight: 20
url: /fr/net/groupdocs.editor.options/mhtmlsaveoptions/exportcidurls/
---
## MhtmlSaveOptions.ExportCidUrls property

Spécifie s’il faut utiliser des URL CID (Content-ID) pour référencer les ressources (images, polices, CSS) incluses dans les documents MHTML. La valeur par défaut est `false`.

```csharp
public bool ExportCidUrls { get; set; }
```

### Remarques

Par défaut, les ressources dans les documents MHTML sont référencées par le nom de fichier (par exemple, "image.png"), qui sont comparés aux en-têtes "Content-Location" des parties MIME. Cette option active une méthode alternative, où les références aux fichiers de ressources sont écrites sous forme d'URL CID (Content-ID) (par exemple, "cid:image.png") et sont comparées aux en-têtes "Content-ID".

En théorie, il ne devrait y avoir aucune différence entre les deux méthodes de référencement et chacune d'elles devrait fonctionner correctement dans n'importe quel navigateur ou client de messagerie. En pratique, cependant, certains agents échouent à récupérer les ressources par nom de fichier. Si votre navigateur ou client de messagerie refuse de charger les ressources incluses dans un document MTHML (n'affiche pas les images ou ne charge pas les styles CSS), essayez d'exporter le document avec des URL CID.

### Voir aussi

* class [MhtmlSaveOptions](../../mhtmlsaveoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.editor.dll -->
