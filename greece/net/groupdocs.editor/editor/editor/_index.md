---
title: "Editor"
second_title: "GroupDocs.Editor για .NET αναφορά API"
description: "Αρχικοποιεί ένα νέο παράδειγμα της κλάσης Editorgroupdocs.editor/editor και δημιουργεί ένα νέο κενό έγγραφο βάσει της καθορισμένης μορφής."
type: docs
weight: 10
url: /el/net/groupdocs.editor/editor/editor/
---
## Editor(DocumentFormatBase) {#constructor}

Αρχικοποιεί ένα νέο παράδειγμα της κλάσης [`Editor`](../../editor) και δημιουργεί ένα νέο κενό έγγραφο βάσει της καθορισμένης μορφής.

```csharp
public Editor(DocumentFormatBase format)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| μορφή | DocumentFormatBase | Αναπαριστά τη μορφή αρχείου του εγγράφου που θα δημιουργηθεί. |

### Σχόλια

**Learn more**

* More about file types supported by GroupDocs.Editor: [Document formats supported by GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Supported+Document+Formats)
* More about GroupDocs.Editor for .NET features: [Developer Guide](https://docs.groupdocs.com/display/editornet/Developer+Guide)

### Παραδείγματα

```csharp
IDocumentFormat format = new WordProcessingFormats.Docx();
using (Editor editor = new Editor(format))
{
    // Χρησιμοποιήστε το παράδειγμα του επεξεργαστή για να επεξεργαστείτε και να αποθηκεύσετε έγγραφα
}
```

### Δείτε επίσης

* class [DocumentFormatBase](../../../groupdocs.editor.formats.abstraction/documentformatbase)
* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## Editor(Stream) {#constructor_1}

Αρχικοποιεί νέα παρουσία του Editor με το καθορισμένο έγγραφο εισόδου (ως ροή).

```csharp
public Editor(Stream document)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| έγγραφο | Ρεύμα | Ροή που περιέχει το περιεχόμενο του εγγράφου. Δεν πρέπει να είναι null. |

### Σχόλια

**Learn more**

* More about file types supported by GroupDocs.Editor: [Document formats supported by GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Supported+Document+Formats)
* More about GroupDocs.Editor for .NET features: [Developer Guide](https://docs.groupdocs.com/display/editornet/Developer+Guide)

### Παραδείγματα

```csharp
using (FileStream fs = new FileStream("input.docx", FileMode.Open, FileAccess.Read))
{
    using (Editor editor = new Editor(fs))
    {
        // Χρησιμοποιήστε το παράδειγμα του επεξεργαστή για να επεξεργαστείτε και να αποθηκεύσετε έγγραφα
    }
}
```

### Δείτε επίσης

* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## Editor(Stream, ILoadOptions) {#constructor_2}

Αρχικοποιεί νέα παρουσία του Editor με το καθορισμένο έγγραφο εισόδου (ως ροή) με τις επιλογές φόρτωσής του.

```csharp
public Editor(Stream document, ILoadOptions loadOptions)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| έγγραφο | Ρεύμα | Ροή που περιέχει το περιεχόμενο του εγγράφου. Δεν πρέπει να είναι null. |
| loadOptions | ILoadOptions | Επιλογές φόρτωσης εγγράφου. Μπορεί να είναι null. |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| ArgumentNullException | Εκτοπίζεται όταν η ροή του εγγράφου είναι null. |
| ArgumentException | Εκτοπίζεται όταν η ροή του εγγράφου είναι άκυρη. |

### Σχόλια

**Learn more**

* More about file types supported by GroupDocs.Editor: [Document formats supported by GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Supported+Document+Formats)
* More about GroupDocs.Editor for .NET features: [Developer Guide](https://docs.groupdocs.com/display/editornet/Developer+Guide)

### Παραδείγματα

```csharp
using (FileStream fs = new FileStream("input.docx", FileMode.Open, FileAccess.Read))
{
    ILoadOptions loadOptions = new WordProcessingLoadOptions();
    using (Editor editor = new Editor(fs, loadOptions))
    {
        // Χρησιμοποιήστε το παράδειγμα του επεξεργαστή για να επεξεργαστείτε και να αποθηκεύσετε έγγραφα
    }
}
```

### Δείτε επίσης

* interface [ILoadOptions](../../../groupdocs.editor.options/iloadoptions)
* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## Editor(string, ILoadOptions) {#constructor_4}

Αρχικοποιεί νέα παρουσία του Editor με το καθορισμένο έγγραφο εισόδου (ως πλήρης διαδρομή αρχείου) με τις επιλογές φόρτωσής του.

```csharp
public Editor(string filePath, ILoadOptions loadOptions)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| filePath | String | Πλήρης διαδρομή προς το αρχείο. Δεν πρέπει να είναι null, κενό ή να περιέχει μόνο κενά διαστήματα. Πρέπει να είναι έγκυρη και το αρχείο πρέπει να υπάρχει. |
| loadOptions | ILoadOptions | Επιλογές φόρτωσης εγγράφου. Μπορεί να είναι null. |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| ArgumentException | Εκτοπίζεται όταν η διαδρομή του αρχείου είναι άκυρη. |
| FileNotFoundException | Εκτοπίζεται όταν το αρχείο δεν υπάρχει. |

### Σχόλια

**Learn more**

* More about file types supported by GroupDocs.Editor: [Document formats supported by GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Supported+Document+Formats)
* More about GroupDocs.Editor for .NET features: [Developer Guide](https://docs.groupdocs.com/display/editornet/Developer+Guide)

### Παραδείγματα

```csharp
string filePath = "input.docx";
ILoadOptions loadOptions = new WordProcessingLoadOptions();
using (Editor editor = new Editor(filePath, loadOptions))
{
    // Χρησιμοποιήστε το παράδειγμα του επεξεργαστή για να επεξεργαστείτε και να αποθηκεύσετε έγγραφα
}
```

### Δείτε επίσης

* interface [ILoadOptions](../../../groupdocs.editor.options/iloadoptions)
* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## Editor(string) {#constructor_3}

Αρχικοποιεί νέα παρουσία του Editor με το καθορισμένο έγγραφο εισόδου (ως πλήρης διαδρομή αρχείου) και τις ρυθμίσεις του Editor

```csharp
public Editor(string filePath)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| filePath | String | Πλήρης διαδρομή προς το αρχείο. Δεν πρέπει να είναι NULL. Πρέπει να είναι έγκυρη και το αρχείο πρέπει να υπάρχει. |

### Δείτε επίσης

* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.editor.dll -->
