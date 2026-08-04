<div align="center">

# 🔐 KDL Security Free

**A guided security self-check for individuals and small businesses — checklist, indicative score and password-strength testing. One HTML file, no backend, nothing leaves the browser.**

[![License: MIT](https://img.shields.io/badge/License-MIT-1F5278.svg)](LICENSE)
[![No backend](https://img.shields.io/badge/Backend-none-22c55e.svg)](#privacy)
[![Zero dependencies](https://img.shields.io/badge/Dependencies-zero-blue.svg)]()
[![Defensive only](https://img.shields.io/badge/Scope-defensive-1F5278.svg)]()

*🇫🇷 [Documentation française complète plus bas](#-documentation-française)*

</div>

---

## What it does

Most security advice aimed at non-technical people is either terrifying or
useless. This is a single self-contained page that asks concrete questions
(website, accounts, backups), gives an **indicative score out of 100**, and
explains what to fix first.

> ⚠️ **Indicative and educational.** It does not replace a professional audit.

### Features

- ✅ **Nothing is sent anywhere** — everything runs in the browser
- ✅ **Guided security checklist** (website, accounts, backups…) with a /100 score
- ✅ **Password check** — entropy estimated locally, never transmitted
- ✅ **Downloadable report**, generated client-side
- ✅ **Zero trackers, zero cookies, zero backend**

## Quick start

Open `index.html` in a browser, or serve the folder statically:

```bash
python3 -m http.server 8080
```

## Privacy

There is no server to send anything to. The whole tool is HTML/CSS/JS with no
dependency — you can read every line before trusting it, which is rather the
point for a security tool.

## Contributing

Checklist items that reflect real-world small-business risk are the most useful
contribution. ⭐ helps others find it.

---

<a id="-documentation-française"></a>

## 🇫🇷 Documentation française

Diagnostic de sécurité **gratuit, défensif et 100 % local** par l'atelier
[KDL TECH](https://kdl-tech.fr).

Une page autonome (HTML/CSS/JS, sans dépendance ni serveur) qui aide
particuliers et petites structures à faire un premier point sécurité :
checklist guidée, score indicatif et vérification de robustesse de mot de passe.

> ⚠️ Outil **indicatif** à visée pédagogique et défensive. Il ne remplace pas
> un audit professionnel.

## Caractéristiques

- ✅ **Aucune donnée envoyée** : tout s'exécute dans le navigateur.
- ✅ **Checklist de sécurité** (site web, comptes, sauvegardes…) avec score /100.
- ✅ **Vérification de mot de passe** (entropie estimée localement, jamais transmise).
- ✅ **Rapport téléchargeable** généré côté client.
- ✅ **Zéro tracker, zéro cookie, zéro backend.**

## Utilisation

Ouvrir `index.html` dans un navigateur, ou servir le dossier en statique :

```bash
python3 -m http.server 8080
# puis http://localhost:8080
```

La version en ligne est disponible sur
**<https://security.kdl-tech.fr/free>**.

## Version Pro

Pour le suivi avancé (scans automatisés, modules d'analyse, alertes et
rapports PDF), voir **[KDL Security](https://security.kdl-tech.fr)**.

## Structure

```
index.html        # page complète (markup + styles + logique)
assets/           # logo et favicon
```

## Licence

[MIT](LICENSE) — © 2026 KDL TECH (Karim DeLucia).

---

<div align="center">

**Other tools by [KDL TECH](https://kdl-tech.fr)** — an independent computer repair
and software workshop in Guadeloupe 🇬🇵

[Anti-arnaque](https://github.com/Kdl-Tech/kdl-anti-arnaque) ·
[Privacy Dev Browser](https://github.com/Kdl-Tech/kdl-privacy-dev-browser) ·
[Prompt Studio](https://github.com/Kdl-Tech/kdl-prompt-studio) ·
[DNS Shield](https://github.com/Kdl-Tech/kdl-dns-shield) ·
[Security Free](https://github.com/Kdl-Tech/kdl-security-free) ·
[MAIA Conky](https://github.com/Kdl-Tech/maia-conky)

</div>
