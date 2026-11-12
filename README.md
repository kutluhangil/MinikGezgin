<div align="center">

<img src="docs/media/hero.svg" alt="MinikGezgin — your pet's AI-powered passport to the world" width="100%">

<p>
  <a href="https://minik-gezgin.vercel.app"><img alt="Live" src="https://img.shields.io/badge/live-pack%20the%20bags-ff9f5a?style=for-the-badge&labelColor=0e0815"></a>
  <img alt="Gemini" src="https://img.shields.io/badge/Gemini-image%20composites-7dd3fc?style=for-the-badge&labelColor=0e0815">
  <img alt="React" src="https://img.shields.io/badge/React-Vite-f9a8d4?style=for-the-badge&labelColor=0e0815">
  <img alt="Languages" src="https://img.shields.io/badge/UI-TR%20%2F%20EN-ff9f5a?style=for-the-badge&labelColor=0e0815">
</p>

<p><em>Turn everyday pet photos into photorealistic travel memories.<br>
Machu Picchu, a gondola in Venice or a walk on Mars, without leaving the garden.</em></p>

</div>

<img src="docs/media/divider.svg" width="100%" alt="">

## What it is

MinikGezgin (also called PawPassport) is an AI travel album studio. Upload one photo of your pet, type a destination, and Gemini places them there with matching light, perspective and atmosphere. Every result lands in a travel album you can browse, favourite and export.

| | |
|---|---|
| **AI image generation** | Photorealistic composites from a single upload with Gemini's image model. |
| **Any destination** | Type a landmark, a scene or a concept, from the Colosseum to a cyberpunk city. |
| **Inspiration engine** | Travel ideas tailored to your pet's name and style. |
| **Travel album** | An auto-saved gallery with filters, favourites and sorting. |
| **Export** | Download single images, a ZIP of the album or a PDF travel book. |
| **Accounts** | Optional Firebase sign-in to keep albums across devices. |

```mermaid
flowchart LR
  P[Pet photo] --> G[Gemini image model]
  D[Destination prompt] --> G
  I[Inspiration engine] --> D
  G --> A[Travel album<br/>filters · favourites]
  A --> X[PNG · ZIP · PDF]
  A <--> FB[(Firebase · optional)]
```

<img src="docs/media/divider.svg" width="100%" alt="">

## Türkçe özet

**MinikGezgin**, evcil hayvanlarının fotoğraflarını yapay zekâ ile dünyanın ikonik mekânlarına yerleştiren bir seyahat albümü uygulaması. Tek bir fotoğraf yükleyip hedefi yazıyorsun; Gemini dostunu o mekâna ışığı ve perspektifiyle birlikte yerleştiriyor. Sonuçlar albümde saklanıyor, tek tek ya da ZIP ve PDF olarak indirilebiliyor.

<img src="docs/media/divider.svg" width="100%" alt="">

## Development

```sh
npm install
cp .env.example .env.local   # GEMINI_API_KEY, Firebase config
npm run dev                  # http://localhost:3000
npm run build
```

<div align="center">
<br>
<a href="https://github.com/kutluhangil"><img src="docs/media/signature.svg" width="100%" alt="Built by kutluhangil"></a>
<sub>Every pet deserves a passport.</sub>
</div>
