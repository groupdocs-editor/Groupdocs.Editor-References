---
title: "WordProcessingProtectionType"
second_title: "Référence d'API GroupDocs.Editor pour Node.js via Java"
description: "Représente tous les types de protection disponibles du document WordProcessing."
type: docs
weight: 47
url: /fr/nodejs-java/com.groupdocs.editor.options/wordprocessingprotectiontype/
---
**Inheritance:**
java.lang.Object
```
public final class WordProcessingProtectionType
```

Représente tous les types de protection disponibles du document WordProcessing.

## Champs

| Champ | Description |
| --- | --- |
|  | [NoProtection](#NoProtection) | Le document n'est pas protégé. |
|
|  | [AllowOnlyRevisions](#AllowOnlyRevisions) | L'utilisateur ne peut ajouter que des marques de révision au document |
|
|  | [AllowOnlyComments](#AllowOnlyComments) | L'utilisateur ne peut modifier que les commentaires du document |
|
|  | [AllowOnlyFormFields](#AllowOnlyFormFields) | L'utilisateur ne peut saisir que des données dans les champs de formulaire du document |
|
|  | [ReadOnly](#ReadOnly) | Aucun changement n'est autorisé dans le document |
|
## Méthodes

| Méthode | Description |
| --- | --- |
| [getAll()](#getAll--) |  |
### NoProtection {#NoProtection}
```
public static final int NoProtection
```


Le document n'est pas protégé. Valeur par défaut.


### AllowOnlyRevisions {#AllowOnlyRevisions}
```
public static final int AllowOnlyRevisions
```


L'utilisateur ne peut ajouter que des marques de révision au document


### AllowOnlyComments {#AllowOnlyComments}
```
public static final int AllowOnlyComments
```


L'utilisateur ne peut modifier que les commentaires du document


### AllowOnlyFormFields {#AllowOnlyFormFields}
```
public static final int AllowOnlyFormFields
```


L'utilisateur ne peut saisir que des données dans les champs de formulaire du document


### ReadOnly {#ReadOnly}
```
public static final int ReadOnly
```


Aucun changement n'est autorisé dans le document


### getAll() {#getAll--}
```
public static Map<Integer,String> getAll()
```




**Returns:**
java.util.Map<java.lang.Integer,java.lang.String>
