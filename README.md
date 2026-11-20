# PDF Fiyat Kataloğu → Excel Dönüştürücü

Grafik tasarım programında hazırlanmış çok sayfalı ürün ve fiyat kataloglarını (PDF) yapılandırılmış Excel ürün listesine çeviren ve sonucu doğrulayan araç seti.

> Bu depo bir proje vitrinidir. Kaynak kod paylaşılmamaktadır.

## Problem

Fiyat listesi yalnızca tasarım dosyası olarak tutuluyordu. ERP'deki kayıtlarla karşılaştırmak veya bayilere Excel göndermek için yüzlerce ürünün elle yazılması gerekiyordu.

## Özellikler

- Sayfa ve kategori bazında PDF metin çıkarma
- Ürün kodu, açıklama, ambalaj, minimum sipariş miktarı (MOQ) ve fiyatı düzenli ifadelerle ayrıştırma
- PDF kodlama hatalarından gelen bozuk karakterleri temizleme
- **Çok aşamalı doğrulama:** Kod öneki analizi, uyuşmazlık incelemesi ve anlamsal karşılaştırma ile çıktının katalogla birebir aynı olduğu kontrol edilir
- Renk ve aroma gibi varyant adlarını İngilizceden Türkçeye eşleme
- Biçimlendirilmiş, filtrelenebilir Excel çıktısı

## Teknolojiler

`Python` · `PyMuPDF` · `pandas` · `openpyxl` · `regex`
