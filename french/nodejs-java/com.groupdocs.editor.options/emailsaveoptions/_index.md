---
title: "EmailSaveOptions"
second_title: "Référence d'API GroupDocs.Editor pour Node.js via Java"
description: "Permet de spécifier des options personnalisées pour la génération et l'enregistrement de documents de courrier électronique."
type: docs
weight: 15
url: /fr/nodejs-java/com.groupdocs.editor.options/emailsaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class EmailSaveOptions implements ISaveOptions
```

Permet de spécifier des options personnalisées pour générer et enregistrer des documents de courrier électronique (email)

## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [EmailSaveOptions()](#EmailSaveOptions--) | Initialise une nouvelle instance de la classe [EmailSaveOptions](../../com.groupdocs.editor.options/emailsaveoptions), où toutes les options sont définies à leurs valeurs par défaut. |
|
|  | [EmailSaveOptions(int mailMessageOutput)](#EmailSaveOptions-int-) | Initialise une nouvelle instance de la classe [EmailSaveOptions](../../com.groupdocs.editor.options/emailsaveoptions) avec |
MailMessageOutput
(#getMailMessageOutput.getMailMessageOutput/#setMailMessageOutput.setMailMessageOutput) paramètre
|
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getMailMessageOutput()](#getMailMessageOutput--) | Permet de contrôler quelles parties du message électronique doivent être livrées au document de sortie, qui sera généré et enregistré avec la méthode [Editor.save(EditableDocument,Stream,ISaveOptions)](../../com.groupdocs.editor/editor#save-EditableDocument-Stream-ISaveOptions-). |
|
|  | [setMailMessageOutput(int value)](#setMailMessageOutput-int-) | Permet de contrôler quelles parties du message électronique doivent être livrées au document de sortie, qui sera généré et enregistré avec la méthode [Editor.save(EditableDocument,Stream,ISaveOptions)](../../com.groupdocs.editor/editor#save-EditableDocument-Stream-ISaveOptions-). |
|
### EmailSaveOptions() {#EmailSaveOptions--}
```
public EmailSaveOptions()
```


Initialise une nouvelle instance de la classe [EmailSaveOptions](../../com.groupdocs.editor.options/emailsaveoptions), où toutes les options sont définies à leurs valeurs par défaut.


### EmailSaveOptions(int mailMessageOutput) {#EmailSaveOptions-int-}
```
public EmailSaveOptions(int mailMessageOutput)
```


Initialise une nouvelle instance de la classe [EmailSaveOptions](../../com.groupdocs.editor.options/emailsaveoptions) avec
MailMessageOutput
(#getMailMessageOutput.getMailMessageOutput/#setMailMessageOutput.setMailMessageOutput) paramètre


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | mailMessageOutput | int | La sortie du message électronique, qui peut également être spécifiée via la propriété |
|

### getMailMessageOutput() {#getMailMessageOutput--}
```
public final int getMailMessageOutput()
```


Permet de contrôler quelles parties du message électronique doivent être livrées au document de sortie, qui sera généré et enregistré avec la méthode [Editor.save(EditableDocument,Stream,ISaveOptions)](../../com.groupdocs.editor/editor#save-EditableDocument-Stream-ISaveOptions-).
Valeur : énumération à drapeaux qui contrôle les parties du message électronique qui doivent être traitées. La valeur par défaut est MailMessageOutput.All


**Returns:**
int
### setMailMessageOutput(int value) {#setMailMessageOutput-int-}
```
public final void setMailMessageOutput(int value)
```


Permet de contrôler quelles parties du message électronique doivent être livrées au document de sortie, qui sera généré et enregistré avec la méthode [Editor.save(EditableDocument,Stream,ISaveOptions)](../../com.groupdocs.editor/editor#save-EditableDocument-Stream-ISaveOptions-).
Valeur : énumération à drapeaux qui contrôle les parties du message électronique qui doivent être traitées. La valeur par défaut est MailMessageOutput.All


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

