# BOZ213u02a07-2.4.10-25040109
# Python Operatörler ve İfadeler

## Proje Hakkında
Bu proje, Python programlama dilinde aritmetik operatörlerin, değişkenlerin ve matematiksel ifadelerin kullanımını öğrenmek amacıyla hazırlanmıştır.

Proje kapsamında aynı matematiksel ifade, iki farklı Python koduyla hesaplanmıştır.

## Projenin Amacı
- Python'da aritmetik operatörleri kullanmak.
- Matematiksel ifadeleri Python koduna dönüştürmek.
- Değişkenlerle işlem yapmak.
- `float()` fonksiyonuyla veri tipi dönüşümü gerçekleştirmek.
- `print()` fonksiyonuyla sonuçları ekrana yazdırmak.
- Farklı x değerlerinin sonuç üzerindeki etkisini incelemek.

## Kullanılan Teknolojiler
- Python 3
- Python IDLE

## Matematiksel İfade

**y = 3x³ - 2x² + 3x - 1**

## 1. Kod: x = 1

```python
x = 1
x = float(x)

y = 3 * x ** 3 - 2 * x ** 2 + 3 * x - 1

print("y =", y)
```

### Beklenen Çıktı
```text
y = 3.0
```

## 2. Kod: x = 0

```python
x = 0
x = float(x)

y = 3 * x ** 3 - 2 * x ** 2 + 3 * x - 1

print("y =", y)
```

### Beklenen Çıktı
```text
y = -1.0
```

## Kodların Açıklaması

- `x`: Matematiksel ifadede kullanılan değişkendir.
- `float(x)`: x değerini ondalıklı sayı türüne dönüştürür.
- `**`: Üs alma operatörüdür.
- `*`: Çarpma operatörüdür.
- `+`: Toplama operatörüdür.
- `-`: Çıkarma operatörüdür.
- `y`: Hesaplanan sonucu saklayan değişkendir.
- `print()`: Hesaplanan sonucu ekrana yazdırır.

## Program Nasıl Çalıştırılır?
1. Python IDLE açılır.
2. İlgili Python dosyası açılır.
3. F5 tuşuna basılarak program çalıştırılır.
4. Hesaplanan y değeri ekranda görüntülenir.

## Sonuç

Bu çalışmada aynı matematiksel ifade iki farklı x değeriyle hesaplanmıştır.

| x Değeri | y Sonucu |
|---|---|
| 1 | 3.0 |
| 0 | -1.0 |

Böylece değişkenlerin aldığı farklı değerlerin matematiksel işlemlerin sonuçlarını nasıl etkilediği gözlemlenmiştir.

## Lisans
Bu proje MIT lisansı ile lisanslanmıştır.
