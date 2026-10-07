---
title: "ICssDataType"
second_title: "GroupDocs.Editor Java için API Referansı"
description: "CSS özelliklerinde kullanılan tüm CSS veri tipleri için ortak arayüz"
type: docs
weight: 15
url: /tr/java/com.groupdocs.editor.htmlcss.css.datatypes/icssdatatype/
---
**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable
```
public interface ICssDataType extends System.IEquatable<ICssDataType>
```

CSS özelliklerinde kullanılan tüm CSS veri tipleri için ortak arayüz.

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [serializeDefault()](#serializeDefault--) | Mevcut değerin varsayılan dize temsili döndürmelidir |
veri tipi
|
|  | [isDefault()](#isDefault--) | Veri tipinin mevcut değerinin varsayılan olup olmadığını tanımlamalıdır |
bu belirli veri tipi için değer olup olmadığını
|
### serializeDefault() {#serializeDefault--}
```
public abstract String serializeDefault()
```


Mevcut değerin varsayılan dize temsili döndürmelidir
veri tipi


**Returns:**
java.lang.String -
### isDefault() {#isDefault--}
```
public abstract boolean isDefault()
```


Veri tipinin mevcut değerinin varsayılan olup olmadığını tanımlamalıdır
bu belirli veri tipi için değer olup olmadığını


**Returns:**
boolean -
