<div align="center">

<img src="docs/01-kapak.png" alt="GraphQL Subscriptions Studio — Enes Öztürk imzalı proje" width="100%">

# GraphQL Subscriptions Studio

**Ödev 3 — tarayıcı içi PubSub, dört subscription testi ve canlı veri akışı içeren GraphQL stüdyosu.**

[![GraphQL](https://img.shields.io/badge/GraphQL-58BDF8?style=for-the-badge&logo=github&logoColor=white)](https://github.com/EnesBinMalik/graphql-subscriptions-studio)
[![PubSub](https://img.shields.io/badge/PubSub-58BDF8?style=for-the-badge&logo=github&logoColor=white)](https://github.com/EnesBinMalik/graphql-subscriptions-studio)
[![React](https://img.shields.io/badge/React-58BDF8?style=for-the-badge&logo=github&logoColor=white)](https://github.com/EnesBinMalik/graphql-subscriptions-studio)
[![Realtime](https://img.shields.io/badge/Realtime-58BDF8?style=for-the-badge&logo=github&logoColor=white)](https://github.com/EnesBinMalik/graphql-subscriptions-studio)
[![Doğrulama](https://img.shields.io/badge/Do%C4%9Frulama-lint%20%2B%20build%20ge%C3%A7ti-2EA043?style=for-the-badge)](https://github.com/EnesBinMalik/graphql-subscriptions-studio)
[![Enes Öztürk](https://img.shields.io/badge/Enes%20%C3%96zt%C3%BCrk-imzal%C4%B1-EA4338?style=for-the-badge&logo=badge&logoColor=white)](https://github.com/EnesBinMalik)

<img src="docs/rozet-enes-ozturk.png" alt="Enes Öztürk imzalı tasarım rozeti" width="420">

</div>

---

## Hakkında

Bu stüdyo, GraphQL Subscription mekanizmasını harici bir sunucu olmadan gösterir. Tarayıcı içi PubSub motoru userCreated, eventCreated ve participantAdded olaylarını yayınlar; dört doğrulama testi aboneliklerin doğru çalıştığını kanıtlar. Canlı akış paneli olayları anında görüntüler.

> Bu proje **Enes Öztürk** tarafından tasarlanmış, geliştirilmiş ve imzalanmıştır.

---

## Öne çıkan özellikler

| Özellik | Açıklama |
| --- | --- |
| **4 subscription testi** | Aboneliklerin doğruluğunu otomatik denetler. |
| **PubSub motoru** | Tarayıcı içinde olay yayını ve abonelik. |
| **Canlı akış** | Olayları anlık olarak listeler. |
| **Hızlı oluşturma** | Tek tıkla kullanıcı, etkinlik ve katılımcı ekleme. |
| **GraphQL Playground** | Mutation ve subscription sorgularını çalıştırma. |
| **Şema & çözücüler** | Tiplerin ve resolver'ların görsel dökümü. |

---

## Doğrulama

| Ölçü | Değer |
| --- | --- |
| Test | 4 |
| Olay | 3 tip |
| Motor | PubSub |
| Sunucu | Gerekmez |

---

## Galeri

<img src="docs/02-ekran.png" alt="GraphQL Subscriptions Studio ana ekran" width="100%">

<img src="docs/03-ekran.png" alt="GraphQL Subscriptions Studio etkileşimli görünüm" width="100%">

<img src="docs/04-ekran.png" alt="GraphQL Subscriptions Studio detay görünümü" width="100%">

---

## Kurulum

**Gereksinim:** Node.js 20+

```bash
git clone https://github.com/EnesBinMalik/graphql-subscriptions-studio.git
cd graphql-subscriptions-studio
npm install
npm run dev
```

> Tüm akış istemci tarafında çalışır; ek sunucu kurulumu gerekmez.

Diğer komutlar:

```bash
npm run build     # Üretim derlemesi
npm run preview   # Derlemeyi önizle
npm run lint      # TypeScript tip kontrolü
```

---

## Teknik mimari

```text
src/graphql/pubsub.ts       Tarayıcı içi olay motoru
src/graphql/schema.ts        Şema ve resolver'lar
src/graphql/executor.ts      Sorgu çalıştırıcı
src/components/LiveStreamFeed.tsx  Canlı akış
src/components/VerificationModal.tsx  Test sonuçları
```

---

## İmza

<div align="center">

[![Geliştirici](https://img.shields.io/badge/Geli%C5%9Ftirici-Enes%20%C3%96zt%C3%BCrk-EA4338?style=for-the-badge&logo=github&logoColor=white)](https://github.com/EnesBinMalik)
[![İmza](https://img.shields.io/badge/%C4%B0mza-Enes%20%C3%96zt%C3%BCrk-FFD700?style=for-the-badge&logo=verified&logoColor=white)](https://github.com/EnesBinMalik)

**Bu kod, tasarım ve deneyim Enes Öztürk'ün kişisel imzasını taşır.**

© 2026 Enes Öztürk — Tüm hakları saklıdır.

</div>
