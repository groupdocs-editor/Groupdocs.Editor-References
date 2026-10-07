---
title: "GroupDocs.Editor"
second_title: "Référence API GroupDocs.Editor pour .NET"
description: "L'espace de noms GroupDocs.Editor fournit des classes pour modifier des documents en utilisant des éditeurs WYSIWYG frontaux tiers sans aucune application supplémentaire."
type: docs
weight: 10
url: /fr/net/groupdocs.editor/
---
L’espace de noms GroupDocs.Editor fournit des classes pour éditer des documents en utilisant des éditeurs WYSIWYG front‑end tiers sans aucune application supplémentaire.

## Classes

| Classe | Description |
| --- | --- |
| [EditableDocument](./editabledocument) | Document intermédiaire, qui contient le contenu avant et après la modification. |
| [Editor](./editor) | Classe principale, qui encapsule les méthodes de conversion. La classe Editor fournit des méthodes de chargement, de modification et d'enregistrement des documents de tous les formats pris en charge. Elle est jetable, donc utilisez une directive 'using' ou libérez ses ressources manuellement via l'appel de la méthode 'Dispose()'. Le chargement du document est effectué via les constructeurs. La modification du document – via la méthode 'Edit' – et l'enregistrement du document résultant après modification – via la méthode 'Save'. |
| [EncryptedException](./encryptedexception) | L'exception qui est levée lorsque l'utilisateur tente d'ouvrir un document qui a été chiffré à l'aide des X509Certificates. |
| [FormFieldManager](./formfieldmanager) | Gérez un formulaire avec des champs de formulaire hérités. Les champs de formulaire hérités sont les types de champs qui étaient disponibles dans les versions antérieures du traitement de texte. Le groupe Legacy Forms (visible après avoir cliqué sur l'icône Legacy Tools) comprend trois types de champs de formulaire que vous pouvez insérer dans un document : texte, case à cocher, liste déroulante, date, etc., voir plus [`FormFieldType`](../groupdocs.editor.words.fieldmanagement/formfieldtype). Chacun de ces champs de formulaire permet à l'utilisateur du formulaire de sélectionner ou de saisir des informations du type que vous jugez approprié. |
| [IncorrectPasswordException](./incorrectpasswordexception) | L'exception qui est levée lorsque le mot de passe spécifié est incorrect. |
| [InvalidFormatException](./invalidformatexception) | L'exception qui est levée lorsque l'utilisateur tente d'ouvrir un document avec des options spécifiques au format qui sont incompatibles avec le format du document original. |
| [License](./license) | Fournit des méthodes pour licencier le composant. En savoir plus sur la licence [ici](https://purchase.groupdocs.com/faqs/licensing). |
| [Metered](./metered) | Fournit des méthodes pour appliquer une licence [Metered](https://purchase.groupdocs.com/faqs/licensing/metered). |
| [PasswordRequiredException](./passwordrequiredexception) | L'exception qui est levée lorsque l'utilisateur tente d'ouvrir un document chiffré protégé par mot de passe d'un certain format et ne fournit pas de mot de passe pour ouvrir ce document. |

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.editor.dll -->
