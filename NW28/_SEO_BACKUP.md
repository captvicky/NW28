# SEO & Schema Markup Backup — NW28.id

> Diambil dari `index.html` (ID) & `en/index.html` (EN) — 22 Juni 2026
> Simpan ini sebelum publish ulang dari Nicepage.

---

## 1. Meta Tags (ID — index.html)

```html
<title>Kontraktor Bangun Rumah &amp; Desain Interior Terbaik di Jakarta &amp; Bandung | NW28 ID</title>
<meta name="keywords" content="kontraktor interior bandung, jasa renovasi rumah jakarta, pembuatan booth pameran, desain build terpadu, kontraktor jakarta selatan, kontraktor bandung, jasa bangun rumah bandung, renovasi rumah bandung, jasa konstruksi bandung, NW28, NW28.id, CV Natawira Dwi Ashta, kontraktor ruko bandung, pemborong bangunan bandung, arsitek bandung, jasa design and build bandung.">
<meta name="description" content="NW28 ID Kontraktor resmi berlisensi dengan 500+ proyek. Jasa bangun rumah, renovasi, desain interior terpercaya di Jakarta &amp; Bandung. Free konsultasi &amp; RAB transparan.">
<meta name="robots" content="index, follow, max-image-preview:large">
<link rel="canonical" href="https://www.nw28.co.id/">
<link rel="icon" href="images/nw28logo.jpg">
<meta name="theme-color" content="#478ac9">
```

---

## 2. Open Graph (ID — index.html)

```html
<meta property="og:title" content="NW28.ID">
<meta property="og:description" content="Kontraktor Jasa Pembangunan Rumah, Renovasi Rumah hingga Design and build">
<meta property="og:image" content="https://www.nw28.co.id/images/kantorNW28.idBandung.webp">
<meta property="og:url" content="https://www.nw28.co.id/">
<meta property="og:image:width" content="1200">
<meta property="og:image:height" content="630">
<meta property="og:type" content="website">
```

---

## 3. Schema — Organization (ID — index.html)

```json
{
  "@context": "https://schema.org",
  "@type": "Organization",
  "@id": "https://www.nw28.co.id/#organization",
  "name": "NW28 ID",
  "alternateName": "CV Natawira Dwi Ashta",
  "url": "https://www.nw28.co.id/",
  "logo": "https://www.nw28.co.id/images/nw28LOGO.png",
  "image": "https://www.nw28.co.id/images/nw28LOGO.png",
  "sameAs": ["https://www.instagram.com/nw28.id"],
  "contactPoint": {
    "@type": "ContactPoint",
    "telephone": "+6281312364679",
    "contactType": "sales",
    "availableLanguage": ["Indonesian"]
  }
}
```

---

## 4. Schema — HomeAndConstructionBusiness + FAQPage (Graph — ID index.html)

```json
{
  "@context": "https://schema.org",
  "@graph": [
    {
      "@type": "HomeAndConstructionBusiness",
      "@id": "https://www.nw28.co.id/",
      "name": "NW28 ID - CV Natawira Dwi Ashta",
      "alternateName": "NW28.id",
      "url": "https://www.nw28.co.id/",
      "description": "Kontraktor jasa Renovasi Rumah dan Kontraktor Bangunan Hingga Arsitek di Jakarta dan Bandung. Fokus pada Specialized dan Design-Sensitive Contractor yg memiliki kepekaan desain tinggi. Bukanhanya ahli dalam teknis, tapi juga paham seni dan estetika konstruksi.",
      "image": "https://www.nw28.co.id/images/nw28logo.jpg",
      "telephone": "+6281312364679",
      "priceRange": "$$",
      "address": {
        "@type": "PostalAddress",
        "streetAddress": "Jl. Gudang Utara No.28",
        "addressLocality": "Bandung",
        "addressRegion": "Jawa Barat",
        "postalCode": "40113",
        "addressCountry": "ID"
      },
      "geo": {
        "@type": "GeoCoordinates",
        "latitude": -6.91618666224166,
        "longitude": 107.62312745421322
      },
      "aggregateRating": {
        "@type": "AggregateRating",
        "ratingValue": "4.9",
        "bestRating": "5",
        "worstRating": "1",
        "reviewCount": 25
      },
      "openingHoursSpecification": [
        {
          "@type": "OpeningHoursSpecification",
          "dayOfWeek": ["Monday","Tuesday","Wednesday","Thursday","Friday"],
          "opens": "09:00",
          "closes": "17:30"
        },
        {
          "@type": "OpeningHoursSpecification",
          "dayOfWeek": "Saturday",
          "opens": "09:00",
          "closes": "16:00"
        }
      ],
      "areaServed": [
        { "@type": "City", "name": "Bandung" },
        { "@type": "City", "name": "Jakarta" }
      ],
      "hasMap": "https://maps.google.com/maps?q=NW28+Jl.+Gudang+Utara+No.28+Bandung",
      "sameAs": ["https://www.instagram.com/nw28.id"]
    },
    {
      "@type": "FAQPage",
      "@id": "https://www.nw28.co.id/#block-12",
      "mainEntity": [
        {
          "@type": "Question",
          "name": "Apa keunggulan jasa Design & Build di NW28 ID?",
          "acceptedAnswer": {
            "@type": "Answer",
            "text": "Sistem Design & Build di NW28 ID mengintegrasikan perencanaan arsitektur dan pembangunan dalam satu pintu untuk menjamin efisiensi biaya dan hasil presisi."
          }
        },
        {
          "@type": "Question",
          "name": "Bagaimana cara NW28 ID mengatur anggaran biaya pembangunan?",
          "acceptedAnswer": {
            "@type": "Answer",
            "text": "Kami menyediakan RAB yang transparan dan melakukan eksplorasi material fungsional untuk memastikan nilai bangunan maksimal tanpa pembengkakan biaya."
          }
        }
      ]
    }
  ]
}
```

---

## 5. Schema — WebSite (ID — index.html)

```json
{
  "@context": "https://schema.org",
  "@type": "WebSite",
  "@id": "https://www.nw28.co.id/#website",
  "url": "https://www.nw28.co.id/",
  "name": "NW28 ID - Kontraktor Bangun Rumah & Desain Interior",
  "description": "Kontraktor resmi berlisensi dengan 500+ proyek. Jasa bangun rumah, renovasi, desain interior terpercaya di Jakarta & Bandung.",
  "inLanguage": "id-ID",
  "publisher": { "@id": "https://www.nw28.co.id/#organization" }
}
```

---

## 6. Meta Tags (EN — en/index.html)

```html
<title>Kontraktor Interior Bandung | Jasa Desain &amp; Build Jakarta - NW28.ID</title>
<meta name="keywords" content="kontraktor interior bandung, jasa renovasi rumah jakarta, pembuatan booth pameran, desain build terpadu, kontraktor jakarta selatan">
<meta name="description" content="Solusi Design &amp; Build terpadu untuk renovasi rumah dan interior bisnis di Bandung &amp; Jakarta. Tim profesional 10+ tahun, teknologi 3D design Virtual Tour, garansi 5 tahun. Konsultasi gratis &amp; RAB transparan. Portfolio 200+ proyek sukses di Jakarta dan Bandung.">
<link rel="canonical" href="https://nw28.co.id/">
<link rel="icon" href="../images/nw28logo.jpg">
<meta name="theme-color" content="#478ac9">
```

---

## 7. Open Graph (EN — en/index.html)

```html
<meta property="og:title" content="NW28.ID">
<meta property="og:description" content="Solusi Design &amp; Build terpadu untuk renovasi rumah dan interior bisnis di Bandung &amp; Jakarta. Tim profesional 10+ tahun, teknologi 3D design Virtual Tour, garansi 5 tahun. Konsultasi gratis &amp; RAB transparan. Portfolio 200+ proyek sukses di Jakarta dan Bandung.">
<meta property="og:image" content="https://www.nw28.co.id/images/kantorNW28.idBandung.webp">
<meta property="og:url" content="https://www.nw28.co.id">
<meta property="og:type" content="website">
```

---

## 8. Schema — Organization (EN — en/index.html)

```json
{
  "@context": "http://schema.org",
  "@type": "Organization",
  "name": "NW28",
  "url": "NW28 ID",
  "logo": "../images/nw28LOGO.png"
}
```

---

## 9. Schema — HomeAndConstructionBusiness + Geo + Address (EN — en/index.html)

```json
{
  "@context": "https://schema.org",
  "@graph": [
    {
      "@type": "HomeAndConstructionBusiness",
      "@id": "https://www.nw28.co.id/",
      "name": "NW28 ID - CV Natawira Dwi Ashta",
      "alternateName": "NW28.id",
      "url": "https://www.nw28.co.id/",
      "description": "Kontraktor jasa Renovasi Rumah dan Kontraktor Bangunan Hingga Arsitek di Jakarta dan Bandung. Fokus pada Specialized dan Design-Sensitive Contractor yg memiliki kepekaan desain tinggi. Bukanhanya ahli dalam teknis, tapi juga paham seni dan estetika konstruksi.",
      "image": "https://www.nw28.co.id/images/nw28logo.jpg",
      "telephone": "+6281312364679",
      "priceRange": "$$",
      "address": {
        "@type": "PostalAddress",
        "streetAddress": "Jl. Gudang Utara No.28",
        "addressLocality": "Bandung",
        "addressRegion": "Jawa Barat",
        "postalCode": "40113",
        "addressCountry": "ID"
      }
    }
  ]
}
```

---

## 10. Google Tag Manager

```
GTM ID: GTM-PW2BLH4F
```

---

## 11. Google Analytics

```
Measurement ID: G-P1FCCFBKDM
```

---

## 12. Google Adsense

```
Publisher ID: ca-pub-5041604293723622
ads.txt: google.com, pub-5041604293723622, DIRECT, f08c47fec0942fa0
```

---

## 13. Sitemap (`sitemap.xml`)

```
22 URLs terdaftar — mencakup halaman ID, EN, blog posts, About-us, Jasa pages.
Lihat file sitemap.xml untuk detail lengkap.
```

---

## 14. Nicepage Generator Info

```html
<meta name="generator" content="Nicepage 7.8.23, nicepage.com">
```

---

## 15. Fonts used

```html
<link id="u-theme-google-font" rel="stylesheet" href="https://fonts.googleapis.com/css?family=Roboto:100,100i,300,300i,400,400i,500,500i,700,700i,900,900i|Open+Sans:300,300i,400,400i,500,500i,600,600i,700,700i,800,800i">
<link id="u-page-google-font" rel="stylesheet" href="https://fonts.googleapis.com/css?family=League+Spartan:100,200,300,400,500,600,700,800,900|Inclusive+Sans:400,400i|Braah+One:400|Alata:400">
```

---

## 16. Jasa-Arsitektur---NW28-ID.html

**Service Schema:**
```json
{
  "@context": "https://schema.org",
  "@type": "Service",
  "serviceType": "Jasa Konstruksi Sipil & Arsitektur",
  "provider": { "@type": "HomeAndConstructionBusiness", "@id": "https://www.nw28.co.id/" },
  "areaServed": [{ "@type": "City", "name": "Bandung" }, { "@type": "City", "name": "Jakarta" }],
  "description": "Layanan jasa konstruksi sipil dan arsitektur profesional di Bandung & Jakarta. Kami ahli dalam pembangunan rumah mewah, gedung komersial, dan infrastruktur dengan fokus pada kekuatan struktur material dan estetika arsitektur modern.",
  "offers": { "@type": "Offer", "description": "Konsultasi arsitektur, jasa gambar kerja konstruksi sipil, perencanaan bangunan, dan pengawasan proyek." },
  "mainEntityOfPage": { "@type": "WebPage", "@id": "https://www.nw28.co.id/Jasa-Arsitektur---NW28-ID.html" }
}
```
**Title:** Jasa Konstruksi Sipil & Arsitektur Bandung Jakarta | NW28 ID
**Meta Description:** NW28 ID menyediakan jasa konstruksi sipil dan arsitektur profesional di Bandung & Jakarta. Ahli dalam pembangunan rumah mewah, gedung, dan struktur komersial dengan fokus pada kekuatan material dan estetika arsitektur modern.
**Canonical:** https://www.nw28.co.id/Jasa-Arsitektur---NW28-ID.html

---

## 17. Jasa-Design-Perencanaan.html

**Service Schema:**
```json
{
  "@context": "https://schema.org",
  "@type": "Service",
  "serviceType": "Jasa Design and Planning Konstruksi",
  "provider": { "@type": "HomeAndConstructionBusiness", "@id": "https://www.nw28.co.id/" },
  "areaServed": { "@type": "City", "name": "Bandung" },
  "description": "Layanan perencanaan arsitektur dan desain bangunan terintegrasi. Fokus pada optimalisasi fungsi spasial dan eksplorasi material untuk efisiensi biaya serta kekuatan struktur.",
  "offers": { "@type": "Offer", "description": "Konsultasi desain, perencanaan anggaran (RAB), dan gambar kerja teknis." },
  "mainEntityOfPage": { "@type": "WebPage", "@id": "https://www.nw28.co.id/Jasa-Design-Perencanaan.html" }
}
```
**Title:** Jasa Design dan Perencanaan Konstruksi - NW28 ID
**Meta Description:** Dapatkan jasa design dan perencanaan konstruksi profesional di Bandung dari NW28 ID. Kami ahli dalam desain arsitektur, perencanaan fungsi spasial, dan penyusunan RAB transparan untuk rumah maupun bangunan komersial. Wujudkan rencana bangunan yang kokoh dan estetik bersama tim ahli kami.
**Canonical:** https://www.nw28.co.id/Jasa-Design-Perencanaan.html

---

## 18. Jasa-Kontraktor-Pameran.html

**Service Schema:**
```json
{
  "@context": "https://schema.org",
  "@type": "Service",
  "serviceType": "Jasa Kontraktor Pameran dan Pembuatan Booth Event",
  "provider": { "@type": "HomeAndConstructionBusiness", "@id": "https://www.nw28.co.id/" },
  "areaServed": [{ "@type": "City", "name": "Bandung" }, { "@type": "City", "name": "Jakarta" }],
  "description": "Kontraktor dan Layanan jasa pembuatan booth pameran exhibition custom di Jakarta & Bandung. Kami spesialis dalam desain dan konstruksi booth pameran, exhibition booth, stand pameran, dan event production.",
  "offers": { "@type": "Offer", "description": "Konsultasi renovasi, desain 3D interior, pengerjaan konstruksi, dan pembuatan furniture custom (built-in)." },
  "mainEntityOfPage": { "@type": "WebPage", "@id": "https://www.nw28.co.id/Jasa-Kebutuhan-Event-Pameran.html" }
}
```
**Title:** Jasa Kontraktor Pameran | NW28 ID
**Meta Description:** NW28 ID jasa kontraktor pameran profesional. Melayani pembuatan booth custom, desain 3D, produksi hingga bongkar pasang. Konsultasi gratis!
**Canonical:** https://www.nw28.co.id/Jasa-Kontraktor-Pameran.html

---

## 19. Jasa-Renovasi-Interior.html

**Service Schema:**
```json
{
  "@context": "https://schema.org",
  "@type": "Service",
  "serviceType": "Jasa Renovasi Rumah & Design Interior",
  "provider": { "@type": "HomeAndConstructionBusiness", "@id": "https://www.nw28.co.id/" },
  "areaServed": [{ "@type": "City", "name": "Bandung" }, { "@type": "City", "name": "Jakarta" }],
  "description": "Layanan jasa renovasi rumah total, renovasi kantor, dan design interior profesional di Bandung & Jakarta. Kami ahli dalam transformasi ruang, desain interior modern, hingga pengerjaan bangunan dengan RAB transparan dan kualitas material terbaik.",
  "offers": { "@type": "Offer", "description": "Konsultasi renovasi, desain 3D interior, pengerjaan konstruksi, dan pembuatan furniture custom (built-in)." },
  "mainEntityOfPage": { "@type": "WebPage", "@id": "https://www.nw28.co.id/Jasa-Renovasi-Interior.html" }
}
```
**Title:** Jasa Renovasi Interior
**Meta Description:** Wujudkan rumah impian dengan jasa renovasi rumah & design interior profesional dari NW28 ID. Kami melayani renovasi total, interior modern, hingga custom furniture di Bandung & Jakarta dengan RAB transparan dan mutu terjamin.
**Canonical:** https://www.nw28.co.id/Jasa-Renovasi-Interior.html
```
