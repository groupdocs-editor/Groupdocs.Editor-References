---
title: "EditableDocument"
second_title: "Référence API de GroupDocs.Editor pour Java"
description: "Document intermédiaire qui contient le contenu avant et après l'édition"
type: docs
weight: 10
url: /fr/java/com.groupdocs.editor/editabledocument/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.IAuxDisposable](../../com.groupdocs.editor.htmlcss.resources/iauxdisposable)
```
public final class EditableDocument implements IAuxDisposable
```

Document intermédiaire, qui contient le contenu avant et après l'édition


*** ** * ** ***

Une instance de la classe EditableDocument peut être produite par la méthode Editor.edit() ou créée par l'utilisateur lui‑même à l'aide de fabriques statiques. EditableDocument stocke en interne le document dans son propre format fermé, qui est compatible (convertible) avec tous les formats d'importation et d'exportation pris en charge par GroupDocs.Editor. Afin de rendre le document modifiable dans n'importe quel éditeur WYSIWYG côté client (comme CKEditor ou TinyMCE), EditableDocument fournit des méthodes pour générer du balisage HTML et produire des ressources pouvant être acceptées par l'utilisateur.

<br />


## Champs

| Champ | Description |
| --- | --- |
| [Disposed](#Disposed) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getImages()](#getImages--) | Permet d'obtenir des ressources d'images externes (images raster), qui sont utilisées |
par ce document HTML
|
|  | [getFonts()](#getFonts--) | Permet d'obtenir des ressources de polices externes, qui sont utilisées par ce HTML |
document
|
|  | [getCss()](#getCss--) | Renvoie une liste de ressources CSS |
|
|  | [getAudio()](#getAudio--) | Renvoie une liste de ressources audio |
|
|  | [getAllResources()](#getAllResources--) | Renvoie une liste de toutes les ressources existantes : toutes les feuilles de style, les images provenant de |
HTML et toutes les feuilles de style, polices
|
|  | [getContent(OutputStream storage, Charset encoding)](#getContent-java.io.OutputStream-java.nio.charset.Charset-) | Renvoie le contenu complet du document HTML sous forme de flux d'octets en écrivant ce contenu dans le flux spécifié avec l'encodage texte spécifié |
|
|  | [getBodyContent()](#getBodyContent--) | Renvoie le corps du document HTML (contenu entre l'ouverture et la fermeture |
des balises BODY sans ces balises) sous forme de chaîne.
|
|  | [getBodyContent(String externalImagesTemplate)](#getBodyContent-java.lang.String-) | Renvoie le corps du document HTML (contenu entre l'ouverture et la fermeture |
Balises BODY sans ces balises) sous forme de chaîne, où les liens vers les ressources externes
contiennent le préfixe spécifié.
|
|  | [getContent()](#getContent--) | Renvoie le contenu complet du document HTML sous forme de chaîne. |
|
|  | [getContentString(String externalImagesTemplate, String externalCssTemplate)](#getContentString-java.lang.String-java.lang.String-) | Renvoie le contenu complet du document HTML sous forme de chaîne, où les liens vers |
les ressources externes contiennent le préfixe spécifié.
|
|  | [getCssContent()](#getCssContent--) | Renvoie le contenu de toutes les feuilles de style externes sous forme d'une liste de chaînes, où |
une chaîne représente une feuille de style.
|
|  | [getCssContent(String externalImagesPrefix, String externalFontsPrefix)](#getCssContent-java.lang.String-java.lang.String-) | Renvoie le contenu de toutes les feuilles de style externes sous forme d'une liste de chaînes, où |
une chaîne représente une feuille de style.
|
|  | [getEmbeddedHtml()](#getEmbeddedHtml--) | Renvoie tout le contenu de ce document HTML avec toutes les ressources associées dans un |
format de chaîne unique, où toutes les ressources sont intégrées dans le HTML
marquage sous forme codée en base64.
|
|  | [save(String htmlFilePath)](#save-java.lang.String-) | Enregistre ce document HTML dans le fichier sur le chemin spécifié, où le balisage HTML |
sera stocké, ainsi que dans le dossier associé contenant les ressources.
|
|  | [save(String htmlFilePath, String resourcesFolderPath)](#save-java.lang.String-java.lang.String-) | Enregistre ce document HTML dans le fichier sur le chemin spécifié, où le balisage HTML |
sera stocké, ainsi que dans le dossier associé contenant les ressources, qui est
situé sur le chemin spécifié.
|
| [save(Writer htmlMarkup, HtmlSaveOptions saveOptions)](#save-java.io.Writer-com.groupdocs.editor.options.HtmlSaveOptions-) |  |
|  | [fromMarkup(String newHtmlContent, List<IHtmlResource> resources)](#fromMarkup-java.lang.String-java.util.List-com.groupdocs.editor.htmlcss.resources.IHtmlResource--) | Fabrique statique, qui crée une instance de EditableDocument à partir de |
du balisage HTML spécifié et d'un ensemble de ressources liées correspondantes
|
|  | [fromMarkupAndResourceFolder(String newHtmlContent, String resourceFolderPath)](#fromMarkupAndResourceFolder-java.lang.String-java.lang.String-) | Fabrique statique, qui crée une instance de EditableDocument à partir d'un balisage HTML spécifié et à partir des ressources, situées dans le dossier spécifié par le chemin complet |
|
|  | [fromFile(String htmlFilePath, String resourceFolderPath)](#fromFile-java.lang.String-java.lang.String-) | Fabrique statique, qui crée une instance de EditableDocument à partir d'un HTML |
fichier, qui est spécifié par un chemin vers le fichier \*.html lui-même et un dossier
avec des ressources liées
|
|  | [dispose()](#dispose--) | Libère cette instance de document Editable, en libérant son contenu et |
rendant ses méthodes et propriétés non fonctionnelles
|
|  | [isDisposed()](#isDisposed--) | Détermine si ce document Editable a déjà été libéré (true) ou |
pas (false)
|
### Disposed {#Disposed}
```
public final Event<EventHandler> Disposed
```


### getImages() {#getImages--}
```
public final List<IImageResource> getImages()
```


Permet d'obtenir des ressources d'images externes (images raster), qui sont utilisées
par ce document HTML


**Returns:**
java.util.List<com.groupdocs.editor.htmlcss.resources.images.IImageResource>
### getFonts() {#getFonts--}
```
public final List<FontResourceBase> getFonts()
```


Permet d'obtenir des ressources de polices externes, qui sont utilisées par ce HTML
document


**Returns:**
java.util.List<com.groupdocs.editor.htmlcss.resources.fonts.FontResourceBase>
### getCss() {#getCss--}
```
public final List<CssText> getCss()
```


Renvoie une liste de ressources CSS


**Returns:**
java.util.List<com.groupdocs.editor.htmlcss.resources.textual.CssText>
### getAudio() {#getAudio--}
```
public final List<Mp3Audio> getAudio()
```


Renvoie une liste de ressources audio


**Returns:**
java.util.List<com.groupdocs.editor.htmlcss.resources.audio.Mp3Audio>
### getAllResources() {#getAllResources--}
```
public final List<IHtmlResource> getAllResources()
```


Renvoie une liste de toutes les ressources existantes : toutes les feuilles de style, les images provenant de
HTML et toutes les feuilles de style, polices


*** ** * ** ***

Cette propriété renvoie un résultat concaténé des propriétés 'Images', 'Fonts' et 'Css'

<br />



**Returns:**
java.util.List<com.groupdocs.editor.htmlcss.resources.IHtmlResource>
### getContent(OutputStream storage, Charset encoding) {#getContent-java.io.OutputStream-java.nio.charset.Charset-}
```
public OutputStream getContent(OutputStream storage, Charset encoding)
```


Renvoie le contenu complet du document HTML sous forme de flux d'octets en écrivant ce contenu dans le flux spécifié avec l'encodage texte spécifié


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | stockage | java.io.OutputStream | Flux d'octets non nul, qui prend en charge l'écriture |
|
|  | encodage | java.nio.charset.Charset | Encodage de texte non nul, qui doit être appliqué lors de l'écriture du contenu texte dans le stockage spécifié |


TStream
: Toute implémentation de java.io.InputStream
|

**Returns:**
java.io.OutputStream - Instance du stockage spécifié

### getBodyContent() {#getBodyContent--}
```
public final String getBodyContent()
```


Renvoie le corps du document HTML (contenu entre l'ouverture et la fermeture
des balises BODY sans ces balises) sous forme de chaîne.


**Returns:**
java.lang.String - Chaîne, qui contient le corps du document HTML


*** ** * ** ***

Les éditeurs WYSIWYG fonctionnent avec le corps du document et ne peuvent pas traiter correctement ses méta‑informations provenant du bloc HEAD. Cette méthode est conçue pour de tels cas. Cette surcharge ne permet pas d'ajuster les URI pour les requêtes de ressources externes.

<br />


### getBodyContent(String externalImagesTemplate) {#getBodyContent-java.lang.String-}
```
public final String getBodyContent(String externalImagesTemplate)
```


Renvoie le corps du document HTML (contenu entre l'ouverture et la fermeture
Balises BODY sans ces balises) sous forme de chaîne, où les liens vers les ressources externes
contiennent le préfixe spécifié.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | externalImagesTemplate | java.lang.String | Grâce à ce paramètre, il est possible de spécifier un préfixe qui sera ajouté aux liens de toutes les images externes dans les éléments IMG, qui seront présents dans la chaîne HTML résultante. Si NULL ou vide, aucun préfixe ne sera ajouté. |


*** ** * ** ***

Les éditeurs WYSIWYG fonctionnent avec le corps du document et ne peuvent pas traiter correctement ses méta‑informations provenant du bloc HEAD. Cette méthode est conçue pour de tels cas. Cette surcharge permet d'ajuster les URI pour les requêtes de ressources externes.

<br />

|

**Returns:**
java.lang.String - String, qui contient le corps du document HTML avec des liens, ajusté aux images externes

### getContent() {#getContent--}
```
public String getContent()
```


Renvoie le contenu complet du document HTML sous forme de chaîne.


**Returns:**
java.lang.String - String, qui contient le contenu du document HTML

### getContentString(String externalImagesTemplate, String externalCssTemplate) {#getContentString-java.lang.String-java.lang.String-}
```
public String getContentString(String externalImagesTemplate, String externalCssTemplate)
```


Renvoie le contenu complet du document HTML sous forme de chaîne, où les liens vers
les ressources externes contiennent le préfixe spécifié.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | externalImagesTemplate | java.lang.String | Grâce à ce paramètre, il est possible de spécifier un préfixe qui sera ajouté aux liens de toutes les images externes dans les éléments IMG, qui seront présents dans la chaîne HTML résultante. Si NULL ou vide, aucun préfixe ne sera ajouté. |
|
|  | externalCssTemplate | java.lang.String | Grâce à ce paramètre, il est possible de spécifier un préfixe qui sera ajouté aux liens de toutes les feuilles de style externes dans les éléments LINK, qui seront présents dans la chaîne HTML résultante. Si NULL ou vide, les préfixes ne seront pas ajoutés. |
|

**Returns:**
java.lang.String - String, qui contient le contenu du document HTML avec des liens, ajusté aux ressources externes

### getCssContent() {#getCssContent--}
```
public final List<String> getCssContent()
```


Renvoie le contenu de toutes les feuilles de style externes sous forme d'une liste de chaînes, où
une chaîne représente une feuille de style. Retourne une liste vide, s'il n'y a pas
CSS pour ce document.


**Returns:**
java.util.List<java.lang.String> - Une liste de chaînes, où chaque chaîne contient le contenu d'un document CSS

### getCssContent(String externalImagesPrefix, String externalFontsPrefix) {#getCssContent-java.lang.String-java.lang.String-}
```
public final List<String> getCssContent(String externalImagesPrefix, String externalFontsPrefix)
```


Renvoie le contenu de toutes les feuilles de style externes sous forme d'une liste de chaînes, où
une chaîne représente une feuille de style. Le préfixe spécifié sera appliqué à
tous les liens vers la ressource externe dans chaque feuille de style résultante.
Retourne une liste vide, s'il n'y a pas de CSS pour ce document.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | externalImagesPrefix | java.lang.String | Grâce à ce paramètre, il est possible de spécifier un préfixe qui sera ajouté aux liens de toutes les images externes, qui seront présentes dans les déclarations CSS des chaînes CSS résultantes. Si NULL ou vide, les préfixes ne seront pas ajoutés. |
|
|  | externalFontsPrefix | java.lang.String | Grâce à ce paramètre, il est possible de spécifier un préfixe qui sera ajouté aux liens de toutes les polices externes dans le |
|

**Returns:**
java.util.List<java.lang.String> - Une liste de chaînes, où chaque chaîne contient le contenu d'un document CSS

### getEmbeddedHtml() {#getEmbeddedHtml--}
```
public final String getEmbeddedHtml()
```


Renvoie tout le contenu de ce document HTML avec toutes les ressources associées dans un
format de chaîne unique, où toutes les ressources sont intégrées dans le HTML
marquage sous forme codée en base64.


**Returns:**
java.lang.String - String, qui n'est jamais NULL ou vide

### save(String htmlFilePath) {#save-java.lang.String-}
```
public final void save(String htmlFilePath)
```


Enregistre ce document HTML dans le fichier sur le chemin spécifié, où le balisage HTML
sera stocké, ainsi que dans le dossier associé contenant les ressources.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | htmlFilePath | java.lang.String | Chemin complet vers le fichier où le balisage HTML sera stocké. Le fichier sera créé ou écrasé s'il existe. Le dossier de ressources associé sera créé dans le même dossier où le fichier HTML existe. |
|

### save(String htmlFilePath, String resourcesFolderPath) {#save-java.lang.String-java.lang.String-}
```
public final void save(String htmlFilePath, String resourcesFolderPath)
```


Enregistre ce document HTML dans le fichier sur le chemin spécifié, où le balisage HTML
sera stocké, ainsi que dans le dossier associé contenant les ressources, qui est
situé sur le chemin spécifié.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | htmlFilePath | java.lang.String | Chemin complet vers le fichier où le balisage HTML sera stocké. Ne peut pas être NULL ou vide. Le fichier sera créé ou écrasé s'il existe. |
|
|  | resourcesFolderPath | java.lang.String | Chemin complet vers le dossier associé où toutes les ressources liées seront stockées. Si NULL ou vide, le dossier sera créé automatiquement dans le même répertoire que le fichier \*.html. Si spécifié et n'existe pas, il sera créé. |
|

### save(Writer htmlMarkup, HtmlSaveOptions saveOptions) {#save-java.io.Writer-com.groupdocs.editor.options.HtmlSaveOptions-}
```
public void save(Writer htmlMarkup, HtmlSaveOptions saveOptions)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| htmlMarkup | java.io.Writer |  |
| saveOptions | [HtmlSaveOptions](../../com.groupdocs.editor.options/htmlsaveoptions) |  |

### fromMarkup(String newHtmlContent, List<IHtmlResource> resources) {#fromMarkup-java.lang.String-java.util.List-com.groupdocs.editor.htmlcss.resources.IHtmlResource--}
```
public static EditableDocument fromMarkup(String newHtmlContent, List<IHtmlResource> resources)
```


Fabrique statique, qui crée une instance de EditableDocument à partir de
du balisage HTML spécifié et d'un ensemble de ressources liées correspondantes


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | newHtmlContent | java.lang.String | String, qui contient le balisage HTML brut qui doit être analysé. Ne peut pas être NULL, vide ou invalide. |
|
|  | ressources | java.util.List<com.groupdocs.editor.htmlcss.resources.IHtmlResource> | Collection de toutes les ressources (images, feuilles de style, polices), qui sont utilisées dans le document HTML, spécifiées dans le paramètre newHtmlContent. Peut être absent (NULL ou collection vide). |
|

**Returns:**
[EditableDocument](../../com.groupdocs.editor/editabledocument) - New non-null instance of EditableDocument

### fromMarkupAndResourceFolder(String newHtmlContent, String resourceFolderPath) {#fromMarkupAndResourceFolder-java.lang.String-java.lang.String-}
```
public static EditableDocument fromMarkupAndResourceFolder(String newHtmlContent, String resourceFolderPath)
```


Fabrique statique, qui crée une instance de EditableDocument à partir d'un balisage HTML spécifié et à partir des ressources, situées dans le dossier spécifié par le chemin complet


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | newHtmlContent | java.lang.String | String, qui contient le balisage HTML brut qui doit être analysé. Ne peut pas être NULL, vide ou invalide. |
|
|  | resourceFolderPath | java.lang.String | Chemin obligatoire vers le dossier contenant les ressources. Toutes les feuilles de style situées dans ce dossier seront utilisées. Ne peut pas être NULL ou une chaîne vide, et ce dossier doit exister. |

<br />

*** ** * ** ***

Cette fabrique statique est utile lorsque le contenu du document HTML est présenté sous forme de chaîne, mais que toutes les ressources se trouvent dans un dossier, et que les liens vers ces ressources dans le balisage HTML sont souvent invalides ou absents. Lors de l'appel de cette méthode, elle parcourt le dossier spécifié et applique automatiquement toutes les feuilles de style trouvées au document. Cette méthode est très utile lors de l'obtention de contenu provenant de différents éditeurs HTML, qui coupent généralement les métadonnées du document, etc.

<br />

|

**Returns:**
[EditableDocument](../../com.groupdocs.editor/editabledocument) - New non-null instance of EditableDocument

### fromFile(String htmlFilePath, String resourceFolderPath) {#fromFile-java.lang.String-java.lang.String-}
```
public static EditableDocument fromFile(String htmlFilePath, String resourceFolderPath)
```


Fabrique statique, qui crée une instance de EditableDocument à partir d'un HTML
fichier, qui est spécifié par un chemin vers le fichier \*.html lui-même et un dossier
avec des ressources liées


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | htmlFilePath | java.lang.String | Chaîne contenant le chemin complet vers le fichier HTML. Ne peut pas être null, doit être un chemin de fichier valide, et le fichier lui‑même doit exister. |
|
|  | resourceFolderPath | java.lang.String | Chemin optionnel vers le dossier contenant les ressources HTML. Si NULL, invalide ou si ce dossier n'existe pas, l'éditeur essaiera de trouver ce dossier lui‑même en analysant le balisage HTML. |
|

**Returns:**
[EditableDocument](../../com.groupdocs.editor/editabledocument) - New non-null instance of EditableDocument

### dispose() {#dispose--}
```
public final void dispose()
```


Libère cette instance de document Editable, en libérant son contenu et
rendant ses méthodes et propriétés non fonctionnelles


### isDisposed() {#isDisposed--}
```
public final boolean isDisposed()
```


Détermine si ce document Editable a déjà été libéré (true) ou
pas (false)


**Returns:**
boolean
