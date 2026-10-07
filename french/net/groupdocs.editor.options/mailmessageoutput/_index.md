---
title: "MailMessageOutput"
second_title: "Référence API GroupDocs.Editor pour .NET"
description: "Contrôle quelles parties du message électronique doivent être transmises au traitement de sortie"
type: docs
weight: 960
url: /fr/net/groupdocs.editor.options/mailmessageoutput/
---
## MailMessageOutput enumeration

Contrôle quelles parties du message électronique doivent être transmises au traitement de sortie

```csharp
[Flags]
public enum MailMessageOutput
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| None | `0` | Aucune partie du message électronique ne sera traitée |
| Body | `1` | Traiter le corps du message électronique |
| Subject | `2` | Traiter l'objet du message électronique |
| Date | `4` | Traiter la date et l'heure de la livraison du message |
| To | `8` | Traiter tous les destinataires du message électronique |
| Cc | `10` | Traiter tous les destinataires en copie carbone (CC) du message électronique |
| Bcc | `20` | Traiter tous les destinataires en copie carbone invisible (BCC) du message électronique |
| From | `40` | Traiter l'expéditeur du message électronique |
| Attachments | `80` | Traiter toutes les pièces jointes du message électronique |
| Metadata | `100` | Traiter toutes les autres métadonnées techniques (sensibilité, priorité, encodage, MIME, X-Mailer, etc.) |
| Common | `7B` | Sortie commune - corps avec toutes les métadonnées principales |
| All | `1FF` | Sortie complète - corps avec toutes les métadonnées |

### Voir aussi

* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.editor.dll -->
