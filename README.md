# SafeCoon — site officiel

Page publique de **SafeCoon**, coffre-fort numérique de documents *par Bengacoon*.

➡️ **https://jdviallat.github.io/safecoon-site/**

| Page | Contenu |
|---|---|
| `index.html` | vitrine, en **9 langues** (fr, en, de, it, pt, es, sv, no, fi) |
| `securite.html` | note technique : algorithmes, hiérarchie des clés, **et ce que nous ne pouvons pas garantir** |
| `privacy.html` | politique de confidentialité (RGPD) |
| `i18n.js` | dictionnaire des 9 langues — le français est la référence, toute clé absente y retombe |

## État

L'application est **en cours de développement**. Cette page est publiée avant elle,
volontairement : elle dit ce qui existe et ce qui n'existe pas encore.

Le code source vit dans un dépôt privé séparé (`jdviallat/safecoon`), conformément à la
règle de la gamme : **un dépôt privé pour le code, un dépôt public pour la vitrine**.

## À venir dans ce dépôt

- `latest.json` — manifeste de mise à jour pour l'APK public Android. Il sera créé **avec la
  première release**, pas avant : un manifeste annonçant une version inexistante ferait
  échouer la vérification de mise à jour dans l'application.
- Les **Releases** GitHub porteront l'APK public (jamais d'AAB ni d'IPA : ceux-là vont aux stores).

## Modifier les traductions

Tout le texte visible vit dans `i18n.js`. Les clés sont partagées par les 9 langues ; en
ajouter une suppose de la renseigner partout, sinon elle s'affichera en français.
