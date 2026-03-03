# İnfaz Hesaplama Robotu

Ceza infaz süresi için **simülasyon** amaçlı web aracı. Girilen ceza ve bazı niteliklere göre:

- Koşullu salıverilme (KS) tarihi
- Denetimli serbestlik (DS) ayrılış tarihi
- Hak ederek tahliye (HET) tarihi
- Zaman çizelgesi (timeline) görselleştirmesi

üretir.

> Bu proje **resmî hesaplama aracı değildir**. Sonuçlar bilgilendirme amaçlıdır.

---

## Özellikler

- 3 adımlı form (temel bilgiler → detaylar → suç niteliği)
- Süreli hapis + müebbet / ağırlaştırılmış müebbet senaryoları
- Tekerrür (1. tekerrür, 2. tekerrür) etkileri
- Örgütlü / terör işareti
- Mahsup (gün) desteği
- 70+ ve 6 yaş altı çocuğu olan anne için DS özel durum bilgilendirmesi
- Sonuçlar paneli + “Hesaplama Notları” ve “Hukuki Uyarılar” sekmeleri
- Zaman çizelgesi: başlangıç → DS → KS → HET noktaları

---

## Kurulum ve Çalıştırma

Bu proje saf HTML/CSS/JS çalışır.

### Yöntem 1: Dosyayı aç
- `index.html` dosyasını indirip tarayıcıda açın.

### Yöntem 2: Basit yerel sunucu (önerilir)
Bazı tarayıcılar yerel dosyada tarih/JS davranışlarını farklı ele alabilir. Yerel sunucu daha stabil olur.

Python ile:
```bash
python -m http.server 8000
