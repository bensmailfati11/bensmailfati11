# Bonjour 👋 — Fatima Zahra Bensmail (bensmailfati11)

<div align="center">
  <!-- Animated SVG banner : gradient + subtle floating -->
  <svg width="90%" height="160" viewBox="0 0 900 160" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Fatima Zahra Bensmail">
    <defs>
      <linearGradient id="grad" x1="0%" y1="0%" x2="100%" y2="0%">
        <stop offset="0%" stop-color="#7b2ff7">
          <animate attributeName="stop-color" values="#7b2ff7;#ff6b6b;#7b2ff7" dur="6s" repeatCount="indefinite" />
        </stop>
        <stop offset="100%" stop-color="#ff6b6b">
          <animate attributeName="stop-color" values="#ff6b6b;#ffd166;#ff6b6b" dur="6s" repeatCount="indefinite" />
        </stop>
      </linearGradient>

      <!-- small floating animation for the subtitle -->
      <g id="float">
        <animateTransform attributeName="transform" type="translate" values="0 0; 0 6; 0 0" dur="4s" repeatCount="indefinite" />
      </g>
    </defs>

    <rect width="100%" height="100%" rx="12" fill="#0b1220" opacity="0.06"/>

    <text x="50%" y="56" font-family="Helvetica, Arial, sans-serif" font-size="36" font-weight="700" text-anchor="middle" fill="url(#grad)">
      Fatima Zahra Bensmail
    </text>

    <!-- subtitle with floating -->
    <g transform="translate(0,0)">
      <text x="50%" y="100" font-family="Inter, Helvetica, Arial" font-size="16" text-anchor="middle" fill="#94a3b8" opacity="0.95">
        <tspan>Développeuse Front‑end · UI/UX · Animations</tspan>
      </text>
      <!-- attach small floating envelope to the right -->
      <g transform="translate(560,70)">
        <g>
          <rect x="-12" y="-10" width="24" height="18" rx="3" fill="#ffffff" opacity="0.06" />
          <polyline points="-10,-8 0,0 10,-8" fill="none" stroke="#ffffff" stroke-width="1" opacity="0.12"/>
        </g>
        <!-- subtle up-down float -->
        <animateTransform attributeName="transform" type="translate" values="0 0; 0 4; 0 0" dur="3s" repeatCount="indefinite" />
      </g>
    </g>

    <!-- subtle shimmer line -->
    <rect x="120" y="120" width="660" height="4" rx="2" fill="url(#grad)" opacity="0.06">
      <animate attributeName="x" values="120;120;120" dur="6s" repeatCount="indefinite" />
    </rect>
  </svg>
</div>

Salut ! Je suis Fatima Zahra — développeuse web front‑end. J'aime transformer des idées en interfaces claires et agréables à utiliser. Je porte une attention particulière à l'accessibilité, la performance et aux micro‑interactions qui donnent vie à un produit.

Ce README est une version plus personnelle de mon profil : il présente qui je suis, ce que je fais, comment je travaille et comment me contacter.

- 🔭 Actuellement : j'améliore l'accessibilité et la performance de mes projets personnels, et je retravaille mon portfolio pour mieux montrer mes animations et petits prototypes.
- 🌱 En apprentissage : Three.js pour des animations 3D légères, et meilleures pratiques d'architecture front-end (modularité, tests, CI).
- ⚡ Intérêts : UI/UX, motion design, optimisation, automatisation des workflows développeur, et petites touches visuelles qui améliorent l'expérience.

---

## 🧩 À propos de mes compétences

Je construis des interfaces modernes en privilégiant la simplicité, la robustesse et l'accessibilité.

- Langages : JavaScript (ES6+), TypeScript, HTML, CSS  
- Frameworks & libs : React, Vite, Tailwind CSS, Framer Motion  
- Graphismes & 3D : Three.js (notions), SVG animé (SMIL)  
- Outils : Git, GitHub, NPM/Yarn, VS Code, Lighthouse  
- Intégrations/API : REST API, EmailJS, services externes (analytics, forms)

Je veille à :
- des temps de chargement raisonnables (lazy-loading, optimisation des assets),
- une sémantique HTML correcte pour l'accessibilité,
- des animations subtiles qui renforcent l'UX sans nuire aux performances.

---

## 🔭 Projets en vedette

- portfolio — Mon site personnel / vitrine (https://github.com/bensmailfati11/portfolio)  
  Statut : en cours d'amélioration — objectif : montrer des cas pratiques, animations et démos interactives.

Ajoute ici d'autres projets que tu veux mettre en avant (librairies, templates, démos d'animations, etc.). Si tu veux, je peux lister automatiquement les repos publics les plus pertinents et les classer par technologie.

---

## 🛠️ Workflow & bonnes pratiques

Voici comment j'aime travailler sur un projet :
- prototypage rapide (Figma / maquettes légères) → composant par composant en React,
- styling utilitaire (Tailwind) pour la cohérence et la vélocité,
- animation progressive (Framer Motion / CSS / SVG) — toujours testée sans animations pour l'accessibilité,
- CI légère (lint, build, tests basiques) avant chaque PR.

---

## ✨ Notes techniques sur les animations dans le README

Petite info utile : GitHub supprime la plupart des <style> et @keyframes dans les README. C'est pourquoi :
- j'utilise des SVG animés (SMIL) — ils s'affichent bien dans les README et restent performants,
- si tu préfères GIF / Lottie / web-embeds, je peux ajouter des visuels externes ou indiquer comment intégrer une version adaptée pour un site web.

Si tu veux voir un exemple d'animation CSS à coller dans un site réel, dis "montre CSS" et je fournis le snippet prêt à l'emploi.

---

## 📫 Contact & liens

Remplace les placeholders ci‑dessous par tes coordonnées réelles pour que je puisse les pousser dans le README (ou dis-moi si tu veux que je le fasse directement) :

- Email : fatimazahra@example.com
- Portfolio : https://github.com/bensmailfati11/portfolio
- LinkedIn : https://www.linkedin.com/in/votre-profil
- Twitter / X : @votre_compte

Tu peux aussi me contacter via GitHub (issues / discussions / PR) — c'est la voie que je préfère pour les contributions techniques.

---

## ✅ Comment contribuer

- Signale un bug ou propose une amélioration via une issue.
- Ouvre une PR avec une description claire et un petit guide pour tester la modification.
- Pour de petites corrections (typos, liens), une PR simple suffit — je merge rapidement si tout est OK.

---

## 📄 Licence

MIT License © Fatima Zahra Bensmail

---

Si tu veux que je personnalise encore plus ce README (remplacer les placeholders, ajouter une version anglaise, inclure des captures d'écran, ou commit direct sur main ou une branche nommée), dis le nom des éléments à remplacer et la branche — je peux préparer le commit et l'ouvrir en PR si tu veux.
