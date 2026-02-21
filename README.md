# 🚗 Compact Drive - Școala de Șoferi Roman

Website oficial al școlii de șoferi **Compact Drive** din Roman, Neamț.

🌐 **Live:** [compactdrive.ro](https://compactdrive.ro)

---

## 📋 Despre Proiect

Compact Drive este un proiect web full-stack dezvoltat de la zero pentru o școală de șoferi din Roman, Neamț. Clientul dorea o prezență solidă în mediul online — un site profesional care să reprezinte firma, să apară în căutările Google și să transforme vizitatorii în înscrieri reale.

**Ce am construit:**

- Site multi-pagină cu animații scroll, galerie dinamică și formular de înscriere funcțional cu trimitere email în timp real
- Panou de administrare complet — clientul poate adăuga poze cu elevi promovați și gestiona promoțiile active direct din browser, fără cunoștințe tehnice
- Strategie SEO locală completă: meta tags, Open Graph, schema JSON-LD (AutomotiveBusiness, FAQPage, BreadcrumbList), sitemap.xml și robots.txt — optimizat pentru a poziționa firma în primele rezultate Google pentru căutări locale

**Provocări rezolvate:**

- Integrare Supabase pentru conținut dinamic fără backend propriu
- Optimizare layout responsive pentru mobil și desktop
- Securizarea cheilor API prin variabile de mediu și restricții de domeniu

---

## 🛠️ Tech Stack

| Tehnologie | Utilizare |
|------------|-----------|
| **Next.js 14** | Framework React, routing, SSR |
| **React 18** | UI Components, Hooks |
| **Tailwind CSS** | Stilizare |
| **Supabase** | Baza de date (galerie, promoții) |
| **EmailJS** | Trimitere emailuri din formular |
| **Lucide React** | Iconițe |

---

## 📁 Structura Proiectului

```
compact-drive/
├── pages/
│   ├── index.jsx              # Pagina principală
│   ├── despre-noi.jsx         # Despre Compact Drive
│   ├── preturi.jsx            # Tarife și autovehicule
│   ├── promotii.jsx           # Promoții active (Supabase)
│   ├── informatii-utile.jsx   # Pași obținere permis, FAQ
│   ├── inscriere.jsx          # Formular înscriere (EmailJS)
│   ├── admin-dashboard.jsx    # Admin panel
│   ├── admin-gallery.jsx      # Gestionare galerie
│   └── admin-promotii.jsx     # Gestionare promoții
├── public/
│   ├── robots.txt
│   ├── sitemap.xml
│   └── ...imagini
├── styles/
│   └── globals.css
└── lib/
    └── supabaseClient.js
```
