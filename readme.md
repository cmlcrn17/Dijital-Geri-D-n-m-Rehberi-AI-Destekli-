# 🌍 Dijital Geri Dönüşüm Rehberi (AI Destekli)

Bu proje, kullanıcıların evlerinde bulunan **geri dönüştürülebilir ürünleri** (ör. elektronik cihaz, pil, plastik vb.) yazarak,  
AI destekli bir rehber aracılığıyla bu ürünlerin nasıl geri dönüştürüleceğini öğrenmelerini sağlar.  
Ekstra olarak, harita entegrasyonu ile en yakın geri dönüşüm noktaları da gösterilebilir.  

---

## 🎯 Amaç
- Kullanıcıya **ürün bazlı geri dönüşüm rehberi** sunmak.  
- **AI (ChatGPT API)** entegrasyonu ile doğru yönlendirmeler sağlamak.  
- Harita entegrasyonu ile **yakındaki geri dönüşüm merkezlerini** göstermek.  

---

## 🏗️ Proje Yapısı
- `/backend` → GPT API Projesi  
- `/frontend` → Web Arayüzü Projesi  

---

## ✅ İş Listesi

### 1. GPT API Projesi (Backend)
- [ ] Proje kurulumu (Python FastAPI veya .NET Core tercih edilebilir).  
- [ ] `/recycle` endpoint’i oluştur.  
- [ ] Kullanıcıdan **ürün adı** al ve GPT API’sine gönder.  
- [ ] GPT’den dönen cevabı JSON formatında dön.  
- [ ] Ekstra: Konum parametresi alıp **Harita API** (Google Maps veya OpenStreetMap) ile en yakın geri dönüşüm noktalarını getir.  
- [ ] Postman collection hazırlanıp dokümantasyon eklenmeli.  

### 2. Web Projesi (Frontend)
- [ ] React.js veya basit HTML+JS tabanlı web uygulaması kurulumu.  
- [ ] Ana sayfada arama formu: kullanıcı ürün adını yazabilmeli.  
- [ ] API’den dönen yanıt kart formatında ekrana basılmalı.  
- [ ] Ekstra: Konum bilgisini alarak harita üzerinde geri dönüşüm noktaları gösterilmeli.  
- [ ] Tasarımda yeşil/mavi tonlarda sürdürülebilirlik teması kullanılmalı.  

### 3. UI/UX Tasarımı
- [ ] Figma üzerinde wireframe ve mockup hazırlanmalı.  
- [ ] Hero section (arama kutusu + görsel).  
- [ ] Sonuç kartları (ürün ikonu, GPT açıklaması, “Haritada Göster” butonu).  
- [ ] Harita alanı (pinler + popup detayları).  
- [ ] Responsive (mobil + masaüstü) tasarım yapılmalı.  

### 4. Dokümantasyon & Teslim
- [ ] README.md dosyası hazırlanmalı.  
- [ ] Backend ve frontend kurulum talimatları yazılmalı.  
- [ ] Örnek API isteği/cevabı eklenmeli.  
- [ ] Web uygulamasından ekran görüntüleri eklenmeli.  

---

## 🚀 Popüler Kullanım Senaryoları
- Plastik atıkların ayrıştırılması.  
- Tekstil atıklarının değerlendirilmesi.  
- Elektronik atık (telefon, bilgisayar, pil) geri dönüşümü.  
- Su ve enerji tasarrufu önerileri.  

---

## 📌 Notlar
- Backend ve frontend **ayrı repo** veya tek repo altında klasörler halinde tutulabilir.  
- Minimum MVP için: sadece ürün adı alınıp GPT cevabı gösterilebilir.  
- Ekstra özellikler (konum + harita entegrasyonu) stajyerlerin araştırma geliştirme çalışması olabilir.  

---


![Geri Dönüşüm İkonu]([https://cdn-icons-png.flaticon.com/512/126/126122.png](https://github.com/cmlcrn17/Dijital-Geri-D-n-m-Rehberi-AI-Destekli-/blob/main/Screenshot%202025-09-09%20at%2010.01.31.png))
