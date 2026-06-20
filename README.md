# KDL Security Free

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
