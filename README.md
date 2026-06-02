# Yemeksepeti Klonu — React Native Ödevi

**Ders:** React Native ile Uygulama Geliştirme  
**Referans uygulama:** [Yemeksepeti](https://www.yemeksepeti.com) (restoran listesi + menü ekranı)

Bu proje, Yemeksepeti’nin restoran listesi ve menü akışının basitleştirilmiş bir Expo klonudur. Tüm veriler `src/data/mockData.js` içinde sabit (mock) olarak tutulur; gerçek API kullanılmaz.

## Teknik gereksinimler (özet)

| Gereksinim | Durum |
|------------|--------|
| Expo (`create-expo-app`) | Evet |
| 2 ekran, Stack navigasyon | Restoran listesi + Menü |
| `FlatList` | Her iki ekranda |
| `useState` | Arama filtresi + sepet adedi |
| `StyleSheet.create()` | Tüm stiller |
| Ayrı component | `src/components/RestaurantCard.js`, `MenuItem.js` |
| Mock veri | `src/data/mockData.js` |

## Kurulum ve çalıştırma

```bash
npm install
npx expo start
```

Ardından terminalde çıkan QR kodu ile **Expo Go** uygulamasından (Android/iOS) test edin.

> **Önemli:** Proje **Expo SDK 54** kullanır. Telefonunuzdaki **Expo Go** sürümü SDK 54 ile uyumlu olmalıdır.

### Telefonda açılmıyorsa

1. **SDK uyumsuzluğu** — Bu proje **SDK 54** içindir; farklı SDK ile oluşturulmuş projeler Expo Go’da açılmaz.
2. **Aynı Wi‑Fi** — Bilgisayar ve telefon aynı ağda olmalı.
3. **Tunnel modu** — Wi‑Fi sorununda: `npm run start:tunnel` (QR kodu tekrar tarayın).
4. **Önbellek temizleme:**
   ```bash
   npx expo start -c
   ```

## Proje yapısı

```
├── App.js                          # Navigasyon girişi
├── src/
│   ├── components/
│   │   ├── RestaurantCard.js
│   │   └── MenuItem.js
│   ├── screens/
│   │   ├── RestaurantListScreen.js
│   │   └── MenuScreen.js
│   ├── data/mockData.js
│   └── theme/colors.js
```

## Ekranlar

1. **Restoran listesi** — <img width="945" height="2048" alt="WhatsApp Image 2026-06-02 at 20 50 17" src="https://github.com/user-attachments/assets/b5a1c66b-dabc-406e-99ee-f0cb5df382dc" />

2. **Menü** — <img width="945" height="2048" alt="WhatsApp Image 2026-06-02 at 20 50 17 (1)" src="https://github.com/user-attachments/assets/87004052-d38f-4fb6-8e9a-595aa683ec1b" />

3. **Gerçek yemeksepeti"" - <img width="945" height="2048" alt="WhatsApp Image 2026-06-02 at 21 16 45" src="https://github.com/user-attachments/assets/e39517fc-8788-41c5-9c42-d53d0badec5d" />


## GitHub repository


```
https://github.com/AAPlus5/React-Native-Odev
```



Word belgesine ve ALMS’e eklemeniz gereken görseller:

1. `npm install` çıktısı  
2. `npx expo start` çıktısı  
3. Restoran listesi ekranı (uygulama)  
4. Menü ekranı, sepet dolu (uygulama)  
5. Orijinal Yemeksepeti restoran listesi (referans)  
6. Orijinal Yemeksepeti menü ekranı (referans)





