[Français](README.md) · **English**

# KDL Security Free

A guided security self-check for individuals and small businesses. One HTML page,
no server, nothing ever leaves the browser.

**[Open the tool](https://security.kdl-tech.fr/free)** · or download `index.html` and
double-click it. It works offline.

![KDL Security Free interface: profile selection between individual, small business and website, then a checklist to tick — antivirus, updates, unique passwords, two-factor authentication, backups](docs/interface.png)

<sub>The interface is in French.</sub>

---

## The problem it solves

Security advice written for non-technical people is either terrifying or
useless. You are told to "enable two-factor authentication" without ever being
told where to start, or what actually matters in your situation.

This page asks concrete questions, adapted to your context, gives an
**indicative score out of 100**, and above all **ranks what to fix first**.

> ⚠️ **Indicative and educational.** It does not replace a professional audit.

## What it does

| | |
|---|---|
| **Three profiles** | individual, small business, website — the questions adapt |
| **Guided checklist** | antivirus, updates, passwords, 2FA, backups, screen lock |
| **Score out of 100** | with ranked priorities, not just a number |
| **Password check** | entropy computed locally, never transmitted |
| **Downloadable report** | generated in the browser |

## Why you can trust it

**There is no server to send anything to.** No dependency, no tracker, no cookie,
no account. It is HTML, CSS and JavaScript in a single file — you can read every
line before trusting it with anything.

For a security tool, that is the bare minimum: software that asks you to assess
your passwords while calling home would be exactly what it claims to protect you
from.

The password check estimates entropy **in your browser**. Nothing is sent,
nothing is stored, nothing survives closing the tab.

## What it does not do

It does not scan your machine, detect malware, or check whether your accounts
have been breached. It gives you a **declarative snapshot**: it is only as good
as the honesty of your answers.

It does not replace an audit. Scoring 100/100 does not mean you are
invulnerable — it means the basics are in place.

## Usage

Open `index.html` in a browser. Or serve the folder:

```bash
python3 -m http.server 8080
```

## Contributing

The most useful additions are checklist items that reflect real risk for a small
organisation — not laboratory recommendations. Open an issue describing the
concrete risk the item helps avoid.

## Licence

MIT. Take it, adapt it, fold it into your own tooling.

---

By [**KDL TECH**](https://kdl-tech.fr) — IT support, software development,
security. Guadeloupe and remote.
