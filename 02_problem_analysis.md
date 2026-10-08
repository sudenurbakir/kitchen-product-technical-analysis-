# 02 — Problem Analysis

Bir ürünle ilgili problem bildirildiğinde ilk amacım problemi hemen çözmek değil, **problemi doğru anlamak ve yeterli bilgi toplamaktır.**

Çünkü ilk bildirilen belirti her zaman problemin gerçek nedeni olmayabilir.

---

## 1. Problemi Tanımla

Öncelikle gelen şikâyeti mümkün olduğunca net hale getiririm.

Örneğin:

> "Evye su kaçırıyor."

Bu ifade başlangıç için yeterlidir ancak analiz için eksiktir.

Problemi şu şekilde detaylandırabilirim:

* Hangi ürün?
* Ürün kodu nedir?
* Problem tam olarak nerede?
* Su hangi noktadan geliyor?
* Problem ne zaman başladı?
* İlk kullanımdan itibaren mi vardı?
* Sonradan mı oluştu?
* Montaj ne zaman yapıldı?
* Montajı kim yaptı?
* Üründe daha önce işlem yapıldı mı?

Böylece:

```text
Genel şikâyet
      ↓
Detaylı problem tanımı
      ↓
İncelenebilir problem
```

haline gelir.

---

## 2. Gerekli Bilgileri Topla

Problemin türüne göre farklı bilgiler gerekebilir.

Temel olarak şu bilgileri toplamaya çalışırım:

### Ürün bilgisi

* Ürün adı
* Ürün kodu
* Model
* LOT / parti bilgisi
* Üretim veya satın alma bilgisi

### Problem bilgisi

* Sorun nedir?
* Nerede oluşuyor?
* Ne zaman başladı?
* Sürekli mi, ara sıra mı?
* İlk kullanımdan beri mi var?
* Daha önce tekrarlandı mı?

### Kullanım bilgisi

* Ürün nasıl kullanıldı?
* Hangi temizlik ürünleri kullanıldı?
* Ürüne fiziksel bir darbe geldi mi?
* Kullanım koşullarında farklılık var mı?

### Montaj bilgisi

* Nasıl monte edildi?
* Montaj talimatına uygun mu?
* Montaj sırasında değişiklik yapıldı mı?
* Bağlantılar doğru mu?

### Görsel bilgi

Mümkünse:

* Fotoğraf
* Video
* Problemli bölgenin yakın görüntüsü
* Ürünün genel görüntüsü

istenebilir.

---

## 3. Problemi Sınıflandır

Toplanan bilgilerden sonra problemin hangi kategoriye daha yakın olduğunu belirlemeye çalışırım.

Örneğin:

```text
                  Problem
                     ↓
        ┌────────────┼────────────┐
        ↓            ↓            ↓
     Ürün          Montaj       Kullanım
     kaynaklı      kaynaklı     kaynaklı
        ↓            ↓            ↓
    Kaplama       Conta        Kimyasal
    hasarı       bağlantısı    kullanımı
```

Bu sınıflandırma kesin sonuç değildir.

Sadece **hangi ihtimalleri araştırmam gerektiğini** belirlememe yardımcı olur.

---

## 4. Olası Nedenleri Belirle

Örneğin problem:

> "Ürünün yüzeyinde renk değişimi var."

Olası nedenler:

* Uygun olmayan temizlik ürünü
* Kimyasalın yüzeyde uzun süre kalması
* Fiziksel hasar
* Yanlış kullanım
* Montaj sırasında oluşan hasar
* Yüzey işlemi veya kaplama kaynaklı problem
* Üretim kaynaklı problem

Bu aşamada tek bir nedeni doğru kabul etmem.

Bunun yerine:

> **"Hangi bilgi bu ihtimali destekliyor veya eliyor?"**

diye düşünürüm.

---

## 5. Olasılıkları Ele

Şimdi elimizdeki bilgileri olası nedenlerle karşılaştırırım.

Örneğin:

**Problem:** Yüzeyde renk değişimi

**Bulgular:**

* Ürün yaklaşık 6 aydır kullanılıyor.
* Kullanıcı güçlü bir kimyasal temizleyici kullandığını belirtiyor.
* Renk değişimi yalnızca temizleyicinin uygulandığı bölgede.
* Aynı üründen farklı kullanıcıların benzer şikâyeti bulunmuyor.

Bu bilgiler, **kullanım/temizlik kaynaklı olma ihtimalini** güçlendirebilir.

Ancak yine de bunu kesin kök neden olarak kabul etmeden önce gerekli doğrulama yapılmalıdır.

---

## 6. Kanıt ile Varsayımı Ayır

Teknik problem analizinde önemli bir nokta:

> **Tahmin ile kanıt aynı şey değildir.**

Örneğin:

❌ "PVD kaplama bozulmuş."

Bu bir sonuçtur ve kanıt olmadan söylenmemelidir.

Daha doğru yaklaşım:

✅ "Yüzeyde renk değişimi gözlemlendi. Kullanılan temizlik ürünü ve uygulama şekli inceleniyor."

Böylece bildiğim bilgi ile henüz doğrulamadığım ihtimali birbirinden ayırırım.

---

## 7. Basit Bir Analiz Tablosu

Problemleri incelerken aşağıdaki gibi bir tablo kullanılabilir:

| Bulgular                             | Olası neden             | Kontrol                      |
| ------------------------------------ | ----------------------- | ---------------------------- |
| Yüzeyde renk değişimi                | Kimyasal kullanım       | Kullanılan ürün incelenir    |
| Yalnızca tek bölgede hasar           | Fiziksel etki           | Bölgenin konumu incelenir    |
| Birden fazla aynı LOT üründe problem | Üretim/kaplama ihtimali | LOT bazlı kayıtlar incelenir |
| Montaj sonrası su sızıntısı          | Montaj/conta            | Bağlantılar kontrol edilir   |

Bu tablo sayesinde **belirti → ihtimal → kontrol** ilişkisini kurabilirim.

---

## 8. Problemi Doğru Ekibe Aktarma

Her problemi kendim çözmem gerekmeyebilir.

Bazı durumlarda problem:

* Teknik ekibe
* Kalite ekibine
* Üretime
* Satış ekibine
* Yetkili servise

aktarılabilir.

Ancak yalnızca:

> "Müşteri şikâyet ediyor, bakabilir misiniz?"

demek yerine elimdeki bilgileri düzenli aktarmak daha faydalıdır.

### Örnek aktarım

**Ürün:** Kurgusal Evye Modeli
**Problem:** Yüzeyde renk değişimi
**Başlangıç:** Kullanımdan yaklaşık 6 ay sonra
**Bölge:** Gider çevresi
**Kullanım:** Güçlü kimyasal temizleyici kullanılmış
**Görsel:** Mevcut
**LOT:** Mevcut
**İlk değerlendirme:** Kullanım/kimyasal kaynaklı olasılık inceleniyor

Bu şekilde teknik ekip problemin geçmişini tekrar baştan toplamak zorunda kalmadan incelemeye başlayabilir.

---

## 9. Analiz Sürecinin Kısa Akışı

```text
Problem bildirildi
       ↓
Problemi tanımla
       ↓
Bilgi ve kanıtları topla
       ↓
Problemi sınıflandır
       ↓
Olası nedenleri oluştur
       ↓
Kanıtlarla karşılaştır
       ↓
Olasılıkları ele
       ↓
Gerekirse ilgili ekibe aktar
       ↓
Kök nedeni doğrula
```

---

## Bu Bölümden Çıkardığım Temel Fikir

Bir teknik problemle karşılaştığımda:

**Hemen çözüm söylemem.**

Önce:

> **Ne oldu?**

Sonra:

> **Nerede ve ne zaman oldu?**

Sonra:

> **Hangi koşullarda oldu?**

Ardından:

> **Bunun olası nedenleri neler?**

Ve son olarak:

> **Hangi kanıt bize gerçek nedeni gösteriyor?**

şeklinde ilerlerim.

Bu yaklaşım sayesinde problemi yalnızca **çözmeye değil, neden oluştuğunu anlamaya** çalışırım.
