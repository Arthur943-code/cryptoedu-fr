# Crypto Edu

Simulateur éducatif de trading crypto — **100 % statique** (GitHub Pages).

## Utilisation
- Aucun compte, aucune base de données
- Portefeuille virtuel sauvegardé dans le navigateur (`localStorage`)
- Prix live : CoinGecko

## Fonctionnalités
- Capital 50 € → 5000 €
- 15 cryptomonnaies
- Achat / vente + ordres programmés (montants en €)
- Courbes : 1 jour, 7j, 30j, 90j, 1 an, depuis création
- Stratégie éducative DCA + SMA 200

## GitHub Pages
1. Settings → Pages → Branch **main** → folder **/ (root)** → Save
2. URL : https://Arthur943-code.github.io/cryptoedu-fr/

## Conformité légale (France)
- `mentions-legales.html` : éditeur, hébergeur, avertissement sur les risques (LCEN)
- `confidentialite.html` : RGPD, stockage local, services tiers
- Hébergement : GitHub Pages uniquement (aucun Netlify)
- Chart.js hébergé en local (`vendor/`) : aucun CDN tiers
- CSP et referrer définis par balises `<meta>` (GitHub Pages n'accepte pas d'en-têtes personnalisés)
- Seul appel externe : API CoinGecko (voir politique de confidentialité)
- **À compléter** avant mise en ligne : nom, prénom et e-mail de contact dans les deux pages légales (repérés `[À COMPLÉTER ...]`)

## Avertissement
Outil éducatif uniquement. Trading virtuel. Pas un conseil en investissement. Les crypto-actifs sont risqués : perte totale possible.
