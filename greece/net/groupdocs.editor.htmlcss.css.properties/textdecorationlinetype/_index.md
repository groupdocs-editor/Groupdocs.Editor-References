---
title: "TextDecorationLineType"
second_title: "GroupDocs.Editor για .NET αναφορά API"
description: "Αναπαριστά τύπους της γραμμής διακόσμησης κειμένου underline, underscore, overline και linethrough (strikethrough)."
type: docs
weight: 290
url: /el/net/groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/
---
## TextDecorationLineType structure

Αντιπροσωπεύει τύπους της γραμμής διακόσμησης κειμένου: υπογράμμιση (underscore), υπεργράμμιση και διαγράμμιση (strikethrough)

```csharp
public struct TextDecorationLineType : IEquatable<TextDecorationLineType>
```

## Properties

| Name | Περιγραφή |
| --- | --- |
| [IsInitial](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/isinitial) { get; } | Δείχνει αν αυτή η παρουσία έχει αρχική τιμή — None. |
| [IsLineThrough](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/islinethrough) { get; } | Δείχνει αν η γραμμή-μέσω (strikethrough) είναι ενεργοποιημένη. |
| [IsOverline](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/isoverline) { get; } | Δείχνει αν η overline είναι ενεργοποιημένη. |
| [IsUnderline](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/isunderline) { get; } | Δείχνει αν η underline (underscore) είναι ενεργοποιημένη. |
| [Value](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/value) { get; } | Επιστρέφει μια τιμή όλων των σημαιών σε αυτή την παρουσία ως κείμενο. |

## Methods

| Name | Περιγραφή |
| --- | --- |
| static [FromFlags](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/fromflags)(bool, bool, bool) | Δημιουργεί και επιστρέφει μια παρουσία [`TextDecorationLineType`](../textdecorationlinetype) με σημαιές, ορισμένες από τις καθορισμένες παραμέτρους. |
| override [Equals](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/equals#equals_1)(object) | Δείχνει εάν αυτή η παρουσία του [`TextDecorationLineType`](../textdecorationlinetype) είναι ίση με το καθορισμένο μη μετατρεπόμενο |
| [Equals](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/equals#equals)(TextDecorationLineType) | Δείχνει εάν αυτή η παρουσία του [`TextDecorationLineType`](../textdecorationlinetype) είναι ίση με το καθορισμένο |
| override [GetHashCode](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/gethashcode)() | Επιστρέφει έναν κωδικό hash αυτής της παρουσίας |
| override [ToString](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/tostring)() | Επιστρέφει μια τιμή όλων των σημαιών σε αυτή την παρουσία ως κείμενο. |
| static [TryParse](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/tryparse)(string, out TextDecorationLineType) | Προσπαθεί να αναλύσει μια καθορισμένη συμβολοσειρά και να επιστρέψει μια έγκυρη παρουσία του [`TextDecorationLineType`](../textdecorationlinetype) |
| [operator +](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/op_addition) | Συνδυάζει (συγχωνεύει) δύο καθορισμένους τύπους γραμμής και παράγει νέο αποτέλεσμα τύπου γραμμής, όπου οι σημαίες συγχωνεύονται (ένωση) |
| [operator /](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/op_division) | Επιστρέφει μια τομή μεταξύ του πρώτου και του δεύτερου τύπου γραμμής, όπου ενεργοποιούνται μόνο εκείνες οι σημαίες που είναι ενεργές ταυτόχρονα και στα δύο τελεστέα. Έχει την υψηλότερη προτεραιότητα μεταξύ όλων των τελεστών (υψηλότερη από την ένωση και τη διαφορά) |
| [operator ==](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/op_equality) | Ελέγχει εάν δύο τιμές "TextDecorationLineType" είναι ίσες |
| [explicit operator](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/op_explicit#op_explicit_1) | Μετατρέπει συγκεκριμένο Byte (8-bit octet) στον αντίστοιχο [`TextDecorationLineType`](../textdecorationlinetype), ρίχνει εξαίρεση εάν η μετατροπή είναι μη έγκυρη (2 τελεστές) |
| [operator !=](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/op_inequality) | Ελέγχει εάν δύο τιμές "TextDecorationLineType" δεν είναι ίσες |
| [operator -](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/op_subtraction) | Αφαιρεί τον δεύτερο καθορισμένο τύπο γραμμής από τον πρώτο καθορισμένο τύπο γραμμής και παράγει νέο αποτέλεσμα τύπου γραμμής, όπου εμφανίζονται μόνο εκείνες οι σημαίες από το πρώτο τελεστέο που δεν βρίσκονται στο δεύτερο τελεστέο (διαφορά) |

## Πεδία

| Name | Περιγραφή |
| --- | --- |
| static readonly [LineThrough](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/linethrough) | Κάθε γραμμή κειμένου έχει μια γραμμή στη μέση. |
| static readonly [None](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/none) | Παράγει καμία διακόσμηση κειμένου. Αρχική τιμή. |
| static readonly [Overline](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/overline) | Κάθε γραμμή κειμένου έχει μια γραμμή πάνω από αυτήν. |
| static readonly [Underline](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/underline) | Κάθε γραμμή κειμένου είναι υπογραμμισμένη. |

### Σχόλια

Αμετάβλητη δομή. Παρόμοια με το https://developer.mozilla.org/en-US/docs/Web/CSS/text-decoration-line

### Δείτε επίσης

* namespace [GroupDocs.Editor.HtmlCss.Css.Properties](../../groupdocs.editor.htmlcss.css.properties)
* assembly [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.editor.dll -->
