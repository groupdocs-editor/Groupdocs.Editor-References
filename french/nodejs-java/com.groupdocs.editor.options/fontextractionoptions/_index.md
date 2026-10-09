---
title: "FontExtractionOptions"
second_title: "Référence d'API GroupDocs.Editor pour Node.js via Java"
description: "Les options d'extraction de polices contrôlent quelles polices doivent être extraites et d'où"
type: docs
weight: 18
url: /fr/nodejs-java/com.groupdocs.editor.options/fontextractionoptions/
---
**Inheritance:**
java.lang.Object
```
public final class FontExtractionOptions
```

Les options d'extraction de polices contrôlent quelles polices doivent être extraites et de
où

## Champs

| Champ | Description |
| --- | --- |
|  | [NotExtract](#NotExtract) | N'extrait aucune ressource de police ni du document ni du |
système.
|
|  | [ExtractAllEmbedded](#ExtractAllEmbedded) | Extrait toutes les ressources de police, qui sont incorporées dans le document Word d'entrée |
document, quel que soit son type : personnalisé ou système.
|
|  | [ExtractEmbeddedWithoutSystem](#ExtractEmbeddedWithoutSystem) | Extrait uniquement les ressources de police intégrées qui sont personnalisées (pas |
système)
|
|  | [ExtractAll](#ExtractAll) | Essaie d'extraire toutes les polices utilisées dans le document WordProcessing d'entrée |
document, y compris les polices système.
|
## Méthodes

| Méthode | Description |
| --- | --- |
| [getFontExtractionOptions()](#getFontExtractionOptions--) |  |
### NotExtract {#NotExtract}
```
public static final int NotExtract
```


N'extrait aucune ressource de police ni du document ni du
système. Valeur par défaut.


### ExtractAllEmbedded {#ExtractAllEmbedded}
```
public static final int ExtractAllEmbedded
```


Extrait toutes les ressources de police, qui sont incorporées dans le document Word d'entrée
document, quel que soit son type : personnalisé ou système.


*** ** * ** ***

Le convertisseur trouve et extrait toutes les ressources de police à 100 % qui sont intégrées dans le document WordProcessing d'entrée, mais il ne détermine pas si elles sont système ou personnalisées ; il ne touche pas du tout au Registre Windows ni aux dossiers système.

<br />



### ExtractEmbeddedWithoutSystem {#ExtractEmbeddedWithoutSystem}
```
public static final int ExtractEmbeddedWithoutSystem
```


Extrait uniquement les ressources de police intégrées qui sont personnalisées (pas
système)


*** ** * ** ***

Le convertisseur trouve et extrait toutes les ressources de police intégrées, puis tente de déterminer lesquelles de ces polices sont système et lesquelles ne le sont pas. Pour ce faire, le convertisseur obtient une liste de toutes les polices système en utilisant le Registre Windows et les dossiers système, puis compare cette liste avec l'ensemble des polices intégrées. En conséquence, seul le sous‑ensemble de ces polices intégrées qui n'a pas été trouvé dans le système sera retourné.

<br />



### ExtractAll {#ExtractAll}
```
public static final int ExtractAll
```


Essaie d'extraire toutes les polices utilisées dans le document WordProcessing d'entrée
document, y compris les polices système.


*** ** * ** ***

Le convertisseur analyse un document WordProcessing d'entrée et trouve toutes les polices qui y sont utilisées. Si toutes ces polices sont intégrées dans le document d'entrée, le convertisseur les extrait et les renvoie. Sinon, si la collection de polices intégrées ne couvre pas toutes les polices utilisées dans le document, ou est vide, le convertisseur tente d'extraire ces ressources de police depuis le système, en utilisant le Registre Windows et les dossiers système.

<br />



### getFontExtractionOptions() {#getFontExtractionOptions--}
```
public static int[] getFontExtractionOptions()
```




**Returns:**
int[]
