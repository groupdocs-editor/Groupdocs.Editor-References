---
title: "WorksheetNumber"
second_title: "GroupDocs.Editor for .NET API Referansı"
description: "Düzenlenen çalışma sayfasını yeni tek‑çalışma‑sayfası elektronik tablo oluşturmak yerine mevcut bir elektronik tablonun kopyasına eklemeye izin verir (varsayılan davranış). WorksheetNumber, Editor sınıfına yüklenen elektronik tabloda bir çalışma sayfasının 1 tabanlı numarasıdır. Değer 0 ise, yeni elektronik tablo tek bir düzenlenmiş çalışma sayfası ile oluşturulur. Değer sıfırdan büyük veya küçük ve Editor sınıfında geçerli bir elektronik tablo yüklüyse, giriş EditableDocument örneğiyle temsil edilen düzenlenmiş çalışma sayfası bu elektronik tabloya eklenir."
type: docs
weight: 50
url: /tr/net/groupdocs.editor.options/spreadsheetsaveoptions/worksheetnumber/
---
## SpreadsheetSaveOptions.WorksheetNumber property

Yeni tek çalışma sayfası içeren bir elektronik tablo oluşturmak yerine (varsayılan davranış) düzenlenmiş çalışma sayfasını mevcut elektronik tablonun bir kopyasına eklemeye izin verir. WorksheetNumber, Editor sınıfında yüklü elektronik tablodaki çalışma sayfasının 1 tabanlı numarasıdır. 0 (varsayılan değer) ise yeni elektronik tablo tek düzenlenmiş çalışma sayfası ile oluşturulur. Sıfırdan büyük veya küçük bir değer ve Editor sınıfında geçerli bir elektronik tablo yüklüyse, giriş EditableDocument örneğiyle temsil edilen düzenlenmiş çalışma sayfası bu elektronik tabloya eklenir.

```csharp
public int WorksheetNumber { get; set; }
```

### Açıklamalar

WorksheetNumber tam sayı özelliği, varsayılan durumda (ayrılmış değer '0') değilse bir çalışma sayfası numarasını temsil eder; yani sıfırdan değil 1'den başlar ve maksimum değeri bir sunumdaki mevcut tüm slaytların sayısıdır. Ancak belirtilen değer tüm slaytların sayısından büyükse, GroupDocs.Editor bunu son çalışma sayfasını işaret edecek şekilde ayarlar. Negatif değerler de izin verilir ve çalışma sayfalarını sondan sayar. Örneğin, "-1" elektronik tabloda son çalışma sayfasını, "-2" ise sondan bir önceki sayfayı ifade eder. Pozitif değerlerde olduğu gibi, negatif çalışma sayfası numarası verilen elektronik tablodaki toplam çalışma sayısını aşarsa, ilk çalışma sayfasına ayarlanır. [`InsertAsNewWorksheet`](../insertasnewworksheet) boolean özelliği bu özellik ile sıkı bir şekilde ilişkilidir.

### Örnekler

Verilen elektronik tablo 5 çalışma sayfasına sahiptir: WorksheetNumber = 0; — verilen elektronik tabloyu yok say, yeni bir elektronik tablo oluştur ve düzenlenmiş çalışma sayfasını içine koy. WorksheetNumber = 1; — ilk çalışma sayfasını düzenlenmiş olanla değiştir. WorksheetNumber = 2; — ikinci çalışma sayfasını düzenlenmiş olanla değiştir. WorksheetNumber = 5; — son (5.) çalışma sayfasını düzenlenmiş olanla değiştir. WorksheetNumber = 6; — son (5.) çalışma sayfasını düzenlenmiş olanla değiştir, çünkü 6, 5'ten büyük ve bu yüzden ayarlanır. WorksheetNumber = -1; — son (5.) çalışma sayfasını düzenlenmiş olanla değiştir, çünkü "-1" "son mevcut" anlamına gelir. WorksheetNumber = -2; — 4. çalışma sayfasını düzenlenmiş olanla değiştir. WorksheetNumber = -3; — 3. çalışma sayfasını düzenlenmiş olanla değiştir. WorksheetNumber = -4; — 2. çalışma sayfasını düzenlenmiş olanla değiştir. WorksheetNumber = -5; — ilk çalışma sayfasını düzenlenmiş olanla değiştir. WorksheetNumber = -6; — ilk çalışma sayfasını düzenlenmiş olanla değiştir, çünkü "-6" 5'ten büyük ve bu yüzden ayarlanır

### Ayrıca Bakınız

* class [SpreadsheetSaveOptions](../../spreadsheetsaveoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- DÜZENLEMEYİN: GroupDocs.editor.dll için xmldocmd tarafından oluşturuldu -->
