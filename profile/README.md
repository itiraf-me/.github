<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&height=220&color=0:0b0614,45:e11d48,100:8b5cf6&text=itiraf.me&fontColor=ffffff&fontSize=58&fontAlignY=38&desc=Okul%20bazl%C4%B1%20anonim%20itiraflar%C4%B1%20modern%20web%20teknolojileriyle%20g%C3%BCvenle%20bulu%C5%9Fturan%20platform.&descAlignY=58&animation=fadeIn" alt="itiraf.me" width="100%" />

<p>
  <a href="https://itiraf.me"><img alt="Web sitesi" src="https://img.shields.io/badge/Web%20Sitesi-itiraf.me-111827?style=for-the-badge&logo=google-chrome&logoColor=white"></a>
  <img alt="Platform" src="https://img.shields.io/badge/Platform-Anonim%20%C4%B0tiraf-e11d48?style=for-the-badge">
  <img alt="Teknoloji" src="https://img.shields.io/badge/Teknoloji-Next.js%20%2B%20Node.js-0f172a?style=for-the-badge&logo=nextdotjs&logoColor=white">
  <img alt="Çalışma zamanı" src="https://img.shields.io/badge/%C3%87al%C4%B1%C5%9Fma%20Zaman%C4%B1-Node%2022-16a34a?style=for-the-badge&logo=nodedotjs&logoColor=white">
</p>

<h3>Okullar için anonim, güvenli ve gerçek zamanlı itiraf akışı.</h3>

<p>
  itiraf.me; her okulun kendi alt alan adında yaşadığı, itirafların moderasyon
  onayından geçtiği, gerçek zamanlı akışın Socket.IO ile beslendiği ve
  anonimliğin tasarımın merkezinde durduğu çok kiracılı bir sosyal platformdur.
</p>

</div>

---

## Ne Yapıyoruz?

itiraf.me organizasyonu, okul topluluklarının anonim olarak paylaşım
yapabildiği, güvenli ve iyi tasarlanmış web ürünleri geliştirir.

Platform; subdomain tabanlı tenant çözümleme, moderasyon onaylı içerik akışı,
gerçek zamanlı bildirimler ve kimliği asla açığa çıkarmayan anonim aktör
mimarisi üzerine kurulur.

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>Ürün Deneyimi</h3>
      <p>Her okula özel <code>&lt;okul&gt;.itiraf.me</code> alt alan adı; keşif, itiraf paylaşımı ve gerçek zamanlı akışla sade ama bağımlılık yapan bir topluluk deneyimi.</p>
    </td>
    <td width="50%" valign="top">
      <h3>Anonimlik Altyapısı</h3>
      <p>IP adresleri ham saklanmaz; hash + fingerprint tabanlı anonim aktör modeli kimliği açığa çıkarmadan kötüye kullanımı engeller.</p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>Multi-Tenant Mimarisi</h3>
      <p>Tek kod tabanı, sınırsız okul: middleware katmanında çözülen tenant bağlamı tüm API ve arayüz akışlarına otomatik taşınır.</p>
    </td>
    <td width="50%" valign="top">
      <h3>Güvenli Moderasyon</h3>
      <p>Her itiraf yayınlanmadan önce moderasyon onayından geçer; rate limit, ban ve içerik kuralları test edilebilir saf servisler olarak yaşar.</p>
    </td>
  </tr>
</table>

## Teknoloji Haritası

<div align="center">

| Alan | Teknolojiler |
| --- | --- |
| Web | Next.js 15 App Router, React, Tailwind CSS |
| API | Node.js, Express, Mongoose, Zod, pino |
| Gerçek Zamanlı | Socket.IO, tenant bazlı odalar, canlı itiraf akışı |
| Veri | MongoDB, IP hash + fingerprint anonim aktör modeli |
| Operasyon | Docker, GHCR, GitHub Actions, environment sync deploy akışları |

</div>

## Depolar

| Repo | Rol |
| --- | --- |
| `web` | itiraf.me web istemcisi, tenant çözümleme ve ürün arayüzü |
| `backend` | API, anonim aktör, moderasyon, rate limit ve gerçek zamanlı servisler |
| `.github` | Organizasyon profil README'si ve topluluk görünümü |

## Tasarım İlkelerimiz

- Anonimlik bir özellik değil, mimarinin temelidir; kimliği çözebilecek hiçbir veri ham saklanmaz.
- Her okul kendi alanında yaşar; tenant sınırları veri ve deneyim düzeyinde nettir.
- Moderasyon görünmez ama her yerdedir; topluluk güvenliği üründen ödün vermeden sağlanır.
- Mobil deneyim masaüstü deneyiminin küçültülmüş hali değil, kendi başına hızlı ve rahat olmalı.
- Her yeni özellik test edilebilir, gözlemlenebilir ve deploy edilebilir bir sözleşmeyle gelmeli.

## Geliştirme Kültürü

Kodda sade mimariyi, net sahiplik sınırlarını ve kullanıcıya doğrudan dokunan
kalite iyileştirmelerini önemsiyoruz. Anonimlik, güvenlik, performans ve
tasarım aynı ürünün parçaları; biri bittikten sonra diğeri başlamıyor.

<br />

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=rect&height=2&color=0:e11d48,50:8b5cf6,100:22d3ee" alt="" width="100%" />

<p>
  <strong>itiraf.me</strong><br />
  Okul toplulukları için anonim, güvenli ve gerçek zamanlı bir itiraf platformu.
</p>

</div>
