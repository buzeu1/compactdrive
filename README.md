# Compact Drive - Driving School Website

Official website for **Compact Drive**, a driving school based in Roman, Neamț, Romania.

🌐 **Live:** [compactdrive.ro](https://compactdrive.ro)

---

## About the Project

Compact Drive is a full-stack web project built from scratch for a driving school in Roman, Neamț. The client needed a strong online presence — a professional website that represents the business, ranks on Google, and converts visitors into real enrollments.

**What was built:**

- Website with scroll animations, dynamic gallery, and a fully functional enrollment form with real-time email delivery
- Complete admin panel — the client can add photos of students who passed their exam and manage active promotions directly from the browser, without any technical knowledge
- Full local SEO strategy: meta tags, Open Graph, JSON-LD schema (AutomotiveBusiness, FAQPage, BreadcrumbList), sitemap.xml and robots.txt — optimized to rank in the top Google results for local searches

**Challenges solved:**

- Supabase integration for dynamic content without a custom backend
- Responsive layout optimization for mobile and desktop
- API key security through environment variables and domain restrictions

---

## Tech Stack

| Technology | Usage |
|------------|-------|
| **Next.js 14** | React framework, routing, SSR |
| **React 18** | UI Components, Hooks |
| **Tailwind CSS** | Styling |
| **Supabase** | Database (gallery, promotions) |
| **EmailJS** | Email sending from the enrollment form |
| **Lucide React** | Icons |

---

## Project Structure

```
compact-drive/
├── pages/
│   ├── index.jsx              # Home page
│   ├── despre-noi.jsx         # About Compact Drive
│   ├── preturi.jsx            # Pricing and vehicles
│   ├── promotii.jsx           # Active promotions (Supabase)
│   ├── informatii-utile.jsx   # License steps, FAQ
│   ├── inscriere.jsx          # Enrollment form (EmailJS)
│   ├── admin-dashboard.jsx    # Admin panel
│   ├── admin-gallery.jsx      # Gallery management
│   └── admin-promotii.jsx     # Promotions management
├── public/
│   ├── robots.txt
│   ├── sitemap.xml
│   └── ...images
├── styles/
│   └── globals.css
└── lib/
    └── supabaseClient.js
```

---

---

# Compact Drive - Site Școală de Șoferi

Website oficial al școlii de șoferi **Compact Drive** din Roman, Neamț.

🌐 **Live:** [compactdrive.ro](https://compactdrive.ro)

---

## Despre Proiect

Compact Drive este un proiect web full-stack dezvoltat de la zero pentru o școală de șoferi din Roman, Neamț. Clientul dorea o prezență solidă în mediul online — un site profesional care să reprezinte firma, să apară în căutările Google și să transforme vizitatorii în înscrieri reale.

**Ce am construit:**

- Site cu animații scroll, galerie dinamică și formular de înscriere funcțional cu trimitere email în timp real
- Panou de administrare complet — clientul poate adăuga poze cu elevi promovați și gestiona promoțiile active direct din browser, fără cunoștințe tehnice
- Strategie SEO locală completă: meta tags, Open Graph, schema JSON-LD (AutomotiveBusiness, FAQPage, BreadcrumbList), sitemap.xml și robots.txt — optimizat pentru a poziționa firma în primele rezultate Google pentru căutări locale

**Provocări rezolvate:**

- Integrare Supabase pentru conținut dinamic fără backend propriu
- Optimizare layout responsive pentru mobil și desktop
- Securizarea cheilor API prin variabile de mediu și restricții de domeniu

---

## Tech Stack

| Tehnologie | Utilizare |
|------------|-----------|
| **Next.js 14** | Framework React, routing, SSR |
| **React 18** | UI Components, Hooks |
| **Tailwind CSS** | Stilizare |
| **Supabase** | Baza de date (galerie, promoții) |
| **EmailJS** | Trimitere emailuri din formular |
| **Lucide React** | Iconițe |

---

## Structura Proiectului

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

---

*Compact Drive © 2025. Toate drepturile rezervate.*
