# ONVIDA — Brand Identity System
> **"saúde que cabe na sua vida"**  
> Single source of truth for all design, development, marketing, and AI-assisted work.  
> Version 2.1 · March 2026

---

## 0. Brand Assets

| Asset | Preview | Raw URL |
|---|---|---|
| Full Logo (dark text) | ![Onvida Logo](https://raw.githubusercontent.com/lineroapp-star/onvida-brand/main/assets/brand/ONVIDA-LOGO.png) | `https://raw.githubusercontent.com/lineroapp-star/onvida-brand/main/assets/brand/ONVIDA-LOGO.png` |
| Full Logo (white text) | ![Onvida Logo White Text](https://raw.githubusercontent.com/lineroapp-star/onvida-brand/main/assets/brand/onvida-logo-white-text.png) | `https://raw.githubusercontent.com/lineroapp-star/onvida-brand/main/assets/brand/onvida-logo-white-text.png` |
| Icon / Favicon | ![Icon](https://raw.githubusercontent.com/lineroapp-star/onvida-brand/main/assets/brand/ICON-FAVCON.png) | `https://raw.githubusercontent.com/lineroapp-star/onvida-brand/main/assets/brand/ICON-FAVCON.png` |
| White Leaf | ![White Leaf](https://raw.githubusercontent.com/lineroapp-star/onvida-brand/main/assets/brand/WHITE-LEAF.png) | `https://raw.githubusercontent.com/lineroapp-star/onvida-brand/main/assets/brand/WHITE-LEAF.png` |
| Black Leaf | ![Black Leaf](https://raw.githubusercontent.com/lineroapp-star/onvida-brand/main/assets/brand/BLACK-LEAF.png) | `https://raw.githubusercontent.com/lineroapp-star/onvida-brand/main/assets/brand/BLACK-LEAF.png` |

> **Public repo:** [github.com/lineroapp-star/onvida-brand](https://github.com/lineroapp-star/onvida-brand)

---

## 0.1 How to Use This Document

### In VS Code / Cursor / any editor
Place this file at the root of your repo as `BRAND.md`. Reference it in your README:
```md
> Brand guidelines: see [BRAND.md](./BRAND.md)
```

### AI Prompt Snippet
Paste this block at the top of any AI prompt to instantly give brand context:
```
BRAND CONTEXT — ONVIDA
Company: Onvida — Solução Nacional de Saúde
Tagline: "saúde que cabe na sua vida"
Category: Corporate health & benefits platform, Brazil
Primary color: #034E52 (dark teal) · Accent: #2EA89A · Gold: #C8A96E
Logo font: El Messiri (humanist serif, Arabic-influenced roots)
Website fonts: Lora (headlines/display, serif) + Source Sans 3 (body/UI)
Logo: Two-leaf V icon in lime-to-teal gradient + lowercase "onvida" in El Messiri
Tone: Warm, trustworthy, accessible, human — not clinical or corporate-cold
Plans: ESSENCIAL / CUIDA+ / TOTAL
Language: Brazilian Portuguese
Key message: One integrated health solution — 24/7 access, NR-1 compliant, cost-efficient
Logo assets: https://github.com/lineroapp-star/onvida-brand
```

---

## 1. Brand Overview

| Field | Value |
|---|---|
| **Company Name** | Onvida |
| **Full Brand Name** | Onvida — Solução Nacional de Saúde |
| **Tagline** | saúde que cabe na sua vida |
| **Category** | Corporate Health & Benefits Platform (B2B2C) |
| **Market** | Brazil — national coverage |
| **Language** | Brazilian Portuguese (primary) |
| **Website** | onvida.com.br |
| **Phone** | +55 11 5028-2025 |
| **Email (general)** | contato@onvida.com.br |
| **Email (partners)** | parceiros@onvida.com.br |

### Brand Personality
Warm · Trustworthy · Accessible · Modern · Human

**Tone:** Empathetic · Direct · Reassuring · Solution-oriented · Inclusive  
**Not:** Clinical, cold, jargon-heavy, fear-based, or overly corporate.

---

## 2. Logo

### Logo Files

| File | Description | Use When |
|---|---|---|
| `ONVIDA-LOGO.png` | Full logo — colored leaves + **dark teal wordmark** | ✅ Light backgrounds only: white `#FFFFFF`, cream `#FAF9F6`, mint `#E8F4F5` |
| `onvida-logo-white-text.png` | Full logo — colored leaves + **white wordmark** | ✅ Dark/teal backgrounds: `#034E52`, `#0A3D42`, `#051E20`, any dark gradient or overlay |
| `ICON-FAVCON.png` | Icon only, color (1080×1080px square) | Favicon, app icon, social avatar, watermark |
| `WHITE-LEAF.png` | Icon only, white silhouette | Dark backgrounds, overlays, reversed usage |
| `BLACK-LEAF.png` | Icon only, black silhouette | Single-color print, stamps, legal documents |

> **⚠️ Background Rule:** Always match the logo version to the background brightness.  
> Dark or teal background → use `onvida-logo-white-text.png`  
> Light background → use `ONVIDA-LOGO.png`  
> When in doubt: if you can't read dark teal text on the background, switch to the white-text version.

### Wordmark
- Always lowercase: **`onvida`**
- Font: **El Messiri** — humanist serif with Arabic calligraphic origins; warm, distinctive, approachable
- The dot on the `i` acts as a subtle characteristic brand accent
- Never stretch, recolor outside the brand palette, or alter letter-spacing

### Icon / Symbol
- Two stylized **leaves forming a V-shape** — the V of Onvida
- Left leaf: lime-to-teal gradient (lighter, more yellow-green at top)
- Right leaf: deeper teal with a reflective glassy highlight
- Leaves cross slightly at base — symbolizes connection, unity, and growth
- Standalone icon works at any size ≥ 24px digital / 8mm print

### Clear Space & Minimum Sizes
- Clear space = height of the `o` in "onvida" on all sides
- Full logo: min 120px wide (digital) · 30mm (print)
- Icon only: min 24px (digital) · 8mm (print)

### Logo Don'ts
- ❌ Do not rotate, flip, or skew
- ❌ Do not apply drop shadows, glows, or filters
- ❌ Do not recolor the leaves outside the green-teal gradient
- ❌ Do not use on busy photographic backgrounds without a container or overlay
- ❌ Do not uppercase or title-case the wordmark
- ❌ Do not place the icon on a background color that matches the leaves
- ❌ **Do not use `ONVIDA-LOGO.png` (dark teal wordmark) on teal, dark, or dark-gradient backgrounds** — the text becomes invisible. Use `onvida-logo-white-text.png` instead.

---

## 3. Color Palette

### Primary Brand Colors

```
--ov-teal:         #034E52   /* Primary dark teal — buttons, headers, featured cards */
--ov-teal-light:   #12747D   /* Secondary teal — hover states, active elements */
--ov-accent:       #2EA89A   /* Accent teal-green — icons, checkmarks, section labels */
--ov-gold:         #C8A96E   /* Gold — Total plan, premium indicators, italic emphasis */
```

### Background & Surface Colors

```
--ov-cream:        #FAF9F6   /* Warmest page background */
--ov-mint:         #E8F4F5   /* Section tint, pricing blocks, card fills */
--ov-white:        #FFFFFF   /* Default card and content background */
```

### Text Colors

```
--ov-dark:         #1A2A2B   /* Primary body text (near-black, teal undertone) */
--ov-mid:          #4A6568   /* Secondary/muted text, captions */
--ov-on-dark:      rgba(255,255,255,0.7)   /* Body text on dark/featured cards */
```

### Semantic Colors

```
--ov-success:      #2EA89A   /* Matches accent — positive states */
--ov-warning:      #F0A830   /* Alerts, attention */
--ov-error:        #E74C3C   /* Errors, discount badges */
--ov-gold-subtle:  rgba(200,169,110,0.15)  /* Subtle gold bg — Total plan rows */
```

### CSS Gradients

```css
/* Hero / section backgrounds */
background: linear-gradient(135deg, #034E52 0%, #0A3D42 60%, #051E20 100%);

/* Featured card (Total plan) */
background: linear-gradient(160deg, #034E52 0%, #083C41 100%);

/* Hero radial overlay */
background:
  radial-gradient(ellipse at 70% 30%, rgba(46,168,154,0.25) 0%, transparent 60%),
  radial-gradient(ellipse at 20% 80%, rgba(200,169,110,0.15) 0%, transparent 50%);

/* Leaf icon — left leaf */
background: linear-gradient(135deg, #8BC34A 0%, #2E7D4F 50%, #1A5C5A 100%);

/* Leaf icon — right leaf */
background: linear-gradient(135deg, #26A69A 0%, #1A7A6A 50%, #0D5C50 100%);
```

---

## 4. Typography

### Three Font Roles

| Role | Font | Purpose |
|---|---|---|
| **Logo / Wordmark** | **El Messiri** | The "onvida" wordmark only |
| **Display / Headlines** | **Lora** | All section headings, hero text, card titles, editorial serif |
| **Body / UI** | **Source Sans 3** | Body copy, buttons, labels, navigation, data, pricing |

### Why These Fonts
- **El Messiri** — Humanist Arabic-Latin serif. Rounded, warm, and distinctive. Gives the brand name a calligraphic quality without looking ornate.
- **Lora** — Classical transitional serif with brushed strokes. Lora Italic is the brand's emotional emphasis voice: *saúde*, *empresa*, *cuidar*, *inclui*.
- **Source Sans 3** — Paul Hunt's humanist sans-serif. Highly legible at small sizes, clean yet warm. Perfect for pricing, benefit lists, and UI controls.

### Google Fonts Import
```html
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=El+Messiri:wght@400;500;600;700&family=Lora:ital,wght@0,400;0,600;0,700;1,400&family=Source+Sans+3:wght@300;400;600;700&display=swap" rel="stylesheet">
```

### CSS Variables
```css
--font-logo:    'El Messiri', Georgia, serif;
--font-display: 'Lora', Georgia, serif;
--font-body:    'Source Sans 3', Helvetica Neue, sans-serif;
```

### Type Scale

```css
--text-micro:   11px / 1.4   /* Fine print, micro-labels, letter-spaced eyebrows */
--text-xs:      12px / 1.5   /* Footnotes, legal text */
--text-sm:      13px / 1.5   /* Captions, plan labels, tags */
--text-base:    14px / 1.6   /* Benefit items, table cells, buttons */
--text-md:      16px / 1.6   /* Body text default */
--text-lg:      18px / 1.6   /* Lead paragraphs, hero subtitle */
--text-xl:      22px / 1.4   /* Volume section titles */
--text-2xl:     30px / 1.2   /* Plan card headings */
--text-3xl:     34px / 1.2   /* Section headlines */
--text-hero:    clamp(38px, 6vw, 68px) / 1.1  /* Hero h1 */
```

### Typography Rules
- **Lora Italic** = brand keyword emphasis. Wrap key words in `<em>`: *saúde*, *empresa*, *cuidar*, *sua vida*, *inclui*
- **Source Sans 3** weights: 300 for subtitles/muted · 400 for body · 600 for labels/buttons · 700 for prices/strong
- **El Messiri** is reserved for the wordmark — do not use as general display font
- Always pair Lora headlines with Source Sans 3 body — never mix two serifs
- Section eyebrow labels: `Source Sans 3 700 · 11px · letter-spacing: 4px · uppercase · color: var(--ov-accent)`

---

## 5. Plans & Pricing (March 2026)

### Plan Overview

| Plan | Subtitle |
|---|---|
| **ESSENCIAL** | Saúde, cuidado e proteção para você e sua família |
| **CUIDA+** | Acesso ao tratamento e monitoramento contínuo da saúde |
| **TOTAL** *(featured)* | Saúde médica, mental, bucal e proteção familiar — tudo em um plano |

### Pricing by Volume (per person / month)

| Volume | ESSENCIAL | CUIDA+ | TOTAL |
|---|---|---|---|
| 2–29 vidas (lançamento) | R$ 66,90 | R$ 85,90 | R$ 104,90 |
| 30–99 vidas | R$ 62,90 | R$ 80,90 | R$ 99,90 |
| 100–299 vidas | R$ 59,90 | R$ 77,90 | R$ 94,90 |
| 300+ vidas | R$ 54,90 | R$ 69,90 | R$ 84,90 |
| **Tabela regular** | **R$ 69,90** | **R$ 89,90** | **R$ 109,90** |

> **+Marca add-on** (Cuida+ and Total only): +R$ 30/mês → bumps medication credit to R$ 150, covers branded medications across all therapeutic classes.

### Included in All Plans
- **Telemedicina 24/7 — 22 especialidades:** Clínica Geral, Pediatria, Psicologia (20min), Psiquiatria Adultos e Pediátrico, Cardiologia, Dermatologia, Nutrição (15min), Endocrinologia, Neurologia, Gastroenterologia, Ginecologia, Geriatria, Homeopatia, Nutrologia, Med. da Família, Reumatologia, Ortopedia, Urologia, Otorrinolaringologia, Traumatologia
- **Saúde Mental NR-1:** Plantão Psicológico e Psiquiátrico (Seg–Sáb 08h–18h), Psicoterapia (30min), Consultas Psiquiátricas, Mapa de Cuidado Integral
- **Assistência Funerária Nacional** (Grupo Zelo) — urna, traslado aéreo, cremação, suporte completo

### ESSENCIAL adds
- Medicamentos: R$ 50 crédito mensal · genéricos · saúde mental e neurologia · reembolso incluso
- Odontologia Convencional (182 eventos, Odontoprev): restaurações, canal, extrações, odontopediatria, gengival, próteses básicas

### CUIDA+ adds over ESSENCIAL
- Saúde Mental: +1 Treinamento ou Palestra com psicólogo/ano
- Medicamentos: R$ 100 crédito · genéricos · todas as classes terapêuticas
- Relatórios de Saúde da Empresa
- Odontologia Doc Plus (212 eventos): + clareamento, documentação ortodôntica, placa de bruxismo

### TOTAL adds over CUIDA+
- Saúde Mental: +2 Treinamentos ou Palestras/ano + Relatórios emocionais da equipe
- Medicamentos: R$ 150 crédito · genéricos + opção marca
- Gestão de Saúde Corporativa+ — indicadores consolidados
- Odontologia Superior (235 eventos): + prótese cerâmica/cerômero, dentadura, prótese parcial, coroa

### Medication Exclusions (all plans)
Not covered: Ozempic, Saxenda, Wegovy, Mounjaro, Rybelsus, vitaminas, suplementos, manipulados, fitoterápicos, oncológicos orais, cosméticos, preservativos, disfunção erétil, vacinas, imunossupressores, dermocosméticos. Crédito mensal não é cumulativo.

---

## 6. UI Components

### Buttons
```css
/* Primary */
background: #034E52;  color: white;
border-radius: 10px;  padding: 15px 32px;
font: 600 14px 'Source Sans 3';
box-shadow: 0 4px 14px rgba(13,92,99,0.25);
transition: all 0.25s;

/* Primary hover */
background: #12747D;  transform: translateY(-2px);

/* Reversed (on dark/featured card) */
background: white;  color: #034E52;
```

### Cards
```css
/* Standard */
background: #FFFFFF;  border-radius: 16px;  padding: 44px 36px;
border-right: 1px solid rgba(0,0,0,0.06);

/* Featured (Total plan) */
background: linear-gradient(160deg, #034E52 0%, #083C41 100%);
color: white;

/* Pricing block inside card */
background: #E8F4F5;  border-radius: 12px;  padding: 20px 22px;
```

### Volume Tab Switcher
```css
/* Container */
background: white;  border-radius: 60px;  padding: 6px;
box-shadow: 0 8px 32px rgba(13,92,99,0.14);

/* Active tab */
background: #034E52;  color: white;  border-radius: 50px;
padding: 10px 22px;  font: 600 13px 'Source Sans 3';
```

### Tags & Chips
```css
/* Standard */
background: rgba(13,92,99,0.08);  color: #034E52;
border-radius: 20px;  padding: 2px 8px;
font: 600 9-11px 'Source Sans 3';

/* Gold / Total premium */
background: rgba(200,169,110,0.15);  color: #7A5010;

/* Success / savings */
background: rgba(46,168,154,0.12);  color: #2EA89A;
```

### Section Eyebrow Label
```css
font: 700 11px 'Source Sans 3';
letter-spacing: 4px;  text-transform: uppercase;
color: #2EA89A;  margin-bottom: 12px;
```

---

## 7. Layout & Spacing

```css
max-width:     1200px;
border-radius: 16px;    /* plan grid with overflow: hidden */

/* Hero */
padding: 80px 40px 110px;

/* Section */
padding: 72px 24px;

/* Spacing scale (8px base) */
4 · 8 · 12 · 16 · 20 · 24 · 28 · 32 · 44 · 48 · 72 · 80px
```

### Responsive
```css
@media (max-width: 860px) {
  .plans-grid { grid-template-columns: 1fr; }
}
```

---

## 8. Key Statistics

| Metric | Value | Source |
|---|---|---|
| Atendimentos pela rede credenciada | 20 milhões | Onvida |
| Farmácias credenciadas | 45.000 | Onvida |
| Especialidades médicas | 22 | Onvida |
| Satisfação dos usuários | 97% | Onvida |
| Acesso | 24/7 | Onvida |
| Afastamentos por saúde mental (2024) | 472.000 | Min. Previdência Social |
| Crescimento YoY em afastamentos | +68% | Min. Previdência Social |
| Colaboradores que consideram saúde essencial para ficar | 56% | SHRM |
| NR-1 gestão psicossocial obrigatória desde | 2025 | Min. Trabalho e Emprego |

---

## 9. Messaging

### Core Value Proposition
> Onvida é uma solução nacional de saúde e benefícios que simplifica o cuidado ao longo da vida — conectando atendimento médico, prevenção, saúde mental e proteção para pessoas e empresas, com acesso rápido, orientação segura e suporte contínuo.

### Key Headlines
- **Hero:** "Saúde completa para você e sua *empresa*"
- **Vision:** "Cuidando da sua saúde ao longo da vida, onde você estiver."
- **B2B close:** "Sua empresa merece *cuidar* de quem faz ela funcionar."
- **Problem frame:** "A saúde corporativa ainda é fragmentada."
- **Value:** "Mais acesso, mais cuidado e mais tranquilidade."

### B2B Value Pillars

| Pillar | Label | Message |
|---|---|---|
| Retenção | `RETENÇÃO` | Colaboradores que se sentem protegidos permanecem |
| Produtividade | `PRODUTIVIDADE` | Cuidado contínuo reduz ausências e perdas ocultas |
| Conformidade | `CONFORMIDADE` | Estrutura preventiva alinhada à NR-1 |
| Employer Branding | `EMPLOYER BRANDING` | Segurança real sem os custos de um plano tradicional |

---

## 10. Developer Quick Reference

### CSS Design Tokens
```css
:root {
  /* Colors */
  --ov-teal:          #034E52;
  --ov-teal-light:    #12747D;
  --ov-accent:        #2EA89A;
  --ov-gold:          #C8A96E;
  --ov-cream:         #FAF9F6;
  --ov-mint:          #E8F4F5;
  --ov-dark:          #1A2A2B;
  --ov-mid:           #4A6568;

  /* Fonts */
  --font-logo:        'El Messiri', Georgia, serif;
  --font-display:     'Lora', Georgia, serif;
  --font-body:        'Source Sans 3', Helvetica Neue, sans-serif;

  /* Radius */
  --radius-sm:        8px;
  --radius-md:        12px;
  --radius-lg:        16px;
  --radius-pill:      50px;

  /* Shadows */
  --shadow-card:      0 24px 70px rgba(13,92,99,0.15);
  --shadow-float:     0 8px 32px rgba(13,92,99,0.14);
  --shadow-btn:       0 4px 14px rgba(13,92,99,0.25);
}
```

### Tailwind Config
```js
module.exports = {
  theme: {
    extend: {
      colors: {
        ov: {
          teal:         '#034E52',
          'teal-light': '#12747D',
          accent:       '#2EA89A',
          gold:         '#C8A96E',
          cream:        '#FAF9F6',
          mint:         '#E8F4F5',
          dark:         '#1A2A2B',
          mid:          '#4A6568',
        }
      },
      fontFamily: {
        logo:    ['El Messiri', 'Georgia', 'serif'],
        display: ['Lora', 'Georgia', 'serif'],
        sans:    ['Source Sans 3', 'Helvetica Neue', 'sans-serif'],
      },
    }
  }
}
```

---

## 11. Contact & Email Signature

```
Phone:    +55 11 5028-2025
General:  contato@onvida.com.br
Partners: parceiros@onvida.com.br
Web:      onvida.com.br
```

**Email signature structure:**
```
[Nome] | [Cargo]
Onvida | Solução Nacional de Saúde
[Área, ex: Relações Estratégicas & Parcerias]
+55 11 5028-2025
parceiros@onvida.com.br
onvida.com.br
```

---

*Version 2.1 · March 2026 · Onvida*  
*Changes: Real GitHub asset URLs added · planos.onvida.com.br removed · Asset table with previews added to Section 0*
