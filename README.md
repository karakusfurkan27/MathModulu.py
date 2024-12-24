## Python Matematik Fonksiyonları ve Hesaplamalar

Bu Python dosyası, matematiksel hesaplamalar yapmak için `math` modülünü kullanarak çeşitli örnekler sunmaktadır. Aşağıda, dosyada kullanılan fonksiyonlar ve her birinin ne işe yaradığı açıklanmıştır.

### İçerik

1. **`math.ceil(x)`**: Sayıyı bir üst tamsayıya yuvarlar.
   - `math.ceil(2.9)` → 3
   - `math.ceil(-2.9)` → -2

2. **`math.floor(x)`**: Sayıyı bir alt tamsayıya yuvarlar.
   - `math.floor(2.9)` → 2
   - `math.floor(-2.9)` → -3

3. **`//` (Tam Bölme Operatörü)**: Sayıyı en yakın tam sayıya yuvarlar (negatif sayılar için daha "küçük" bir sayıya yuvarlar).
   - `-2.9 // 1` → -3

4. **`math.factorial(x)`**: Bir sayının faktöriyelini hesaplar.
   - `math.factorial(5)` → 120

5. **Çevre Hesaplama**: Bir çemberin çevresini hesaplamak için iki farklı yöntem kullanılmıştır.
   - `math.pi` kullanılarak: Çevre = \( 2 \times \text{radius} \times \pi \)
   - `math.tau` kullanılarak: Çevre = \( \text{radius} \times \tau \) (Bu, \( \tau = 2\pi \) olduğu için aynı sonuca ulaşılır).

6. **Üs Alma**:
   - `3.0 ** 2` → 9.0
   - `math.pow(3, 2)` → 9.0

### Kullanım

Bu dosya, Python'daki temel matematiksel işlemleri anlamak ve uygulamak için basit bir örnek sunmaktadır. `math` modülü ile yapılan hesaplamalar, matematiksel işlemleri doğru ve verimli bir şekilde gerçekleştirmenizi sağlar.

### Kod Çıktıları

Aşağıdaki çıktılar, dosyanın çalıştırılmasıyla elde edilecektir:

```
3
-2
2
-3
-3
120
Circumference of a circle with radius 2: 12.566370614359172
Circumference of a circle with radius 2: 12.566370614359172
9.0
9.0
```

### Gereksinimler

- Python 3.x
- `math` modülü (Python ile birlikte gelir, ek bir yükleme gerektirmez)

### Sonuç

Bu dosya, Python'daki matematiksel hesaplamalar için temel işlevlerin nasıl kullanılacağını gösteren bir örnektir. Hem pozitif hem de negatif sayılar için çeşitli yuvarlama ve hesaplama fonksiyonlarını içerir.
