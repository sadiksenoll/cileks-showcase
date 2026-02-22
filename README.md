# Çileks (Showcase)

Çileks, müşteriler ile yerel hizmet sağlayıcılarını buluşturan bir mobil uygulamadır.

> Bu repo bir **tanıtım (showcase)** reposudur. Kaynak kodlar burada paylaşılmamaktadır.

## Nedir?
- Müşteri tarafı: hizmet keşfetme, ilan oluşturma, teklif alma, sipariş verme  
- Hizmet sağlayıcı tarafı: ilan oluşturma, teklif gönderme, sipariş yönetimi  
- Konum bazlı keşif  
- Bildirimler ve sipariş takibi

## Teknoloji
- Mobil: Android (Kotlin, Jetpack Compose)
- Backend: Supabase (PostgreSQL, Auth, Storage, RLS)
- Realtime: Supabase Realtime

## Ekran Görüntüleri
Ekran görüntülerini `assets/screenshots/` klasörüne ekleyebilirsiniz.

## Mimari (Özet)
- Mobil uygulama → Supabase API  
- Yetkilendirme: Supabase Auth  
- Veri güvenliği: Row Level Security (RLS)

## Yol Haritası
- Ödeme entegrasyonu  
- Değerlendirme & puanlama  
- Harita tabanlı keşif  
- iOS versiyonu
