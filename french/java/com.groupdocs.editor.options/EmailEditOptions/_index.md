---
title: "EmailEditOptions"
second_title: "Référence API de GroupDocs.Editor pour Java"
description: "Permet de spécifier des options personnalisées pour la modification de documents dans les différents formats de courrier électronique"
type: docs
weight: 14
url: /fr/java/com.groupdocs.editor.options/emaileditoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public final class EmailEditOptions implements IEditOptions
```

Permet de spécifier des options personnalisées pour l'édition de documents dans les différents formats de courrier électronique (email)

## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [EmailEditOptions()](#EmailEditOptions--) | Initialise une nouvelle instance de la classe [EmailEditOptions](../../com.groupdocs.editor.options/emaileditoptions), où toutes les options sont définies à leurs valeurs par défaut |
|
|  | [EmailEditOptions(int mailMessageOutput)](#EmailEditOptions-int-) | Initialise une nouvelle instance de la classe [EmailEditOptions](../../com.groupdocs.editor.options/emaileditoptions) avec |
MailMessageOutput
(#getMailMessageOutput.getMailMessageOutput/#setMailMessageOutput.setMailMessageOutput) paramètre
|
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getMailMessageOutput()](#getMailMessageOutput--) | Permet de contrôler quelles parties du message électronique doivent être livrées à la sortie [EditableDocument](../../com.groupdocs.editor/editabledocument) puis au HTML généré |
|
|  | [setMailMessageOutput(int value)](#setMailMessageOutput-int-) | Permet de contrôler quelles parties du message électronique doivent être livrées à la sortie [EditableDocument](../../com.groupdocs.editor/editabledocument) puis au HTML généré |
|
### EmailEditOptions() {#EmailEditOptions--}
```
public EmailEditOptions()
```


Initialise une nouvelle instance de la classe [EmailEditOptions](../../com.groupdocs.editor.options/emaileditoptions), où toutes les options sont définies à leurs valeurs par défaut


### EmailEditOptions(int mailMessageOutput) {#EmailEditOptions-int-}
```
public EmailEditOptions(int mailMessageOutput)
```


Initialise une nouvelle instance de la classe [EmailEditOptions](../../com.groupdocs.editor.options/emaileditoptions) avec
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


Permet de contrôler quelles parties du message électronique doivent être livrées à la sortie [EditableDocument](../../com.groupdocs.editor/editabledocument) puis au HTML généré
Valeur : énumération à indicateurs qui contrôle les parties du message électronique à traiter. La valeur par défaut est MailMessageOutput.All


**Returns:**
int
### setMailMessageOutput(int value) {#setMailMessageOutput-int-}
```
public final void setMailMessageOutput(int value)
```


Permet de contrôler quelles parties du message électronique doivent être livrées à la sortie [EditableDocument](../../com.groupdocs.editor/editabledocument) puis au HTML généré
Valeur : énumération à indicateurs qui contrôle les parties du message électronique à traiter. La valeur par défaut est MailMessageOutput.All


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

