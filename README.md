# 🌐 IT Portfolio – Orhan Fevzi Karakas

> Persönliche Portfolio-Website mit tokenbasiertem Zugangssystem, gebaut als Cloudflare Worker. Zeigt Projekte, Werdegang und praktische Erfahrung in einem sauberen, responsiven Design.

![Status](https://img.shields.io/badge/Status-Live-success) ![Platform](https://img.shields.io/badge/Platform-Cloudflare_Workers-F38020?logo=cloudflare&logoColor=white) ![Frontend](https://img.shields.io/badge/Frontend-Tailwind_CSS-38BDF8?logo=tailwindcss&logoColor=white) ![Security](https://img.shields.io/badge/Security-Token_Auth_%2B_CSP-green)

---

## 🖼️ Showcase

<!-- Screenshot hier per Drag & Drop in den GitHub-Editor einfügen -->
<div align="center">
  <img src="LINK_ZUM_SCREENSHOT_HIER" width="100%" alt="Portfolio Startseite" />
  <br>
  <p><i>Login-Seite mit tokenbasiertem Zugangssystem.</i></p>
</div>

<img width="100%" alt="Portfolio Übersicht" src="LINK_ZUM_SCREENSHOT_HIER" />
<img width="100%" alt="Erfahrungen Sektion" src="LINK_ZUM_SCREENSHOT_HIER" />

### Live ansehen:
🔗 [DEINE-URL-HIER.workers.dev](https://okarakas.de)

---

## 🎯 Über das Projekt

Das Portfolio dient als zentrale Anlaufstelle für Projektanfragen und Bewerbungen. Statt einer offenen, öffentlich indexierbaren Seite nutzt es ein **individuelles Zugangstoken pro Empfänger** – jeder Interessent (z. B. ein Unternehmen) erhält einen eigenen Zugangscode, über den die Seite personalisiert begrüßt und der Zugriff nachvollzogen wird.

### Features

* **Tokenbasierter Zugang:** Jeder Zugangscode ist einem Empfänger zugeordnet und kann ein individuelles Ablaufdatum haben.
* **Sliding Sessions:** Die Sitzung verlängert sich automatisch bei aktiver Nutzung, statt starr nach fester Zeit abzulaufen.
* **Responsive Design:** Vollständig angepasst für Mobile, Tablet und Desktop – inklusive eigenem mobilen Navigationsmenü.
* **Interaktive Projekt-Galerie:** Bildergalerie mit Swipe-Unterstützung und Lightbox-Ansicht für Screenshots.
* **Strukturierte Accordion-Bereiche:** Übersichtliche, aufklappbare Sektionen für Werdegang und Erfahrungen.

---

## 🛡️ Sicherheit

* **Security Headers:** Strikte Content-Security-Policy, `X-Frame-Options: DENY`, `X-Content-Type-Options: nosniff`.
* **HttpOnly-Cookies:** Session-Handling über sichere, JavaScript-unzugängliche Cookies (`Secure`, `SameSite=Strict`).
* **Server-seitige Validierung:** Token-Prüfung und Ablaufdatum-Kontrolle laufen vollständig serverseitig in der Edge-Function.

---

## 🛠️ Tech Stack

| Bereich | Technologie |
| :--- | :--- |
| **Hosting** | Cloudflare Workers (Edge Computing) |
| **Datenhaltung** | Cloudflare KV (Token- & Session-Daten) |
| **Frontend** | Tailwind CSS, Vanilla JavaScript |
| **Icons** | Font Awesome |
| **Fonts** | Google Fonts (Plus Jakarta Sans) |

---
*Hinweis: Der vollständige Quellcode liegt in einem privaten Repository, da er Zugangs- und Sicherheitslogik enthält. Dieses Repository dient als reines Showcase.*
