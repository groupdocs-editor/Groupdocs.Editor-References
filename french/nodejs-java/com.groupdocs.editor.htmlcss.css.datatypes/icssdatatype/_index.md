---
title: "ICssDataType"
second_title: "Référence d'API GroupDocs.Editor pour Node.js via Java"
description: "Interface commune à tous les types de données CSS utilisés dans les propriétés CSS"
type: docs
weight: 15
url: /fr/nodejs-java/com.groupdocs.editor.htmlcss.css.datatypes/icssdatatype/
---
**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable
```
public interface ICssDataType extends System.IEquatable<ICssDataType>
```

Interface commune pour tous les types de données CSS, qui sont utilisés dans les propriétés CSS

## Méthodes

| Méthode | Description |
| --- | --- |
|  | [serializeDefault()](#serializeDefault--) | Doit renvoyer une représentation chaîne par défaut de la valeur actuelle de |
type de données
|
|  | [isDefault()](#isDefault--) | Doit définir si la valeur actuelle du type de données est la valeur par défaut |
valeur pour ce type de données spécifique ou non
|
### serializeDefault() {#serializeDefault--}
```
public abstract String serializeDefault()
```


Doit renvoyer une représentation chaîne par défaut de la valeur actuelle de
type de données


**Returns:**
java.lang.String -
### isDefault() {#isDefault--}
```
public abstract boolean isDefault()
```


Doit définir si la valeur actuelle du type de données est la valeur par défaut
valeur pour ce type de données spécifique ou non


**Returns:**
booléen -
