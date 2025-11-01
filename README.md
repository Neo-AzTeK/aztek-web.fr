# aztek-web.fr

[![Dernière release](https://img.shields.io/github/v/release/Neo-AzTeK/aztek-web.fr?style=for-the-badge)](https://github.com/Neo-AzTeK/aztek-web.fr/releases)
[![Issues](https://img.shields.io/github/issues/Neo-AzTeK/aztek-web.fr?style=for-the-badge)](https://github.com/Neo-AzTeK/aztek-web.fr/issues)
[![License](https://img.shields.io/github/license/Neo-AzTeK/aztek-web.fr?style=for-the-badge)](https://github.com/Neo-AzTeK/aztek-web.fr/blob/main/LICENSE)

## Présentation

Mon site web personnel, développé avec **Angular**.

## Packages principaux

- **SCSS** : personnalisation du thème et des composants
- **Angular Material** : composants UI et thèmes réactifs

## Mise en production

La mise en production se fait avec docker/podman. Voici les commandes:
```bash
git clone https://github.com/Neo-AzTeK/aztek-web.fr.git
cd aztek-web.fr
docker build -t aztek-web.fr .
docker run -d -p 127.0.0.1:80:80 aztek-web.fr
```

## Règles de contribution

Utiliser le fichier `.editorconfig` ou voici un résumé des règles:
- **Indentation** : deux espaces
- Insérer une **nouvelle ligne** en **fin de fichier**
- Fichiers `.ts` : préférer les simples apostrophes `'`
- Pas de **whitespace characters** en fin de ligne

## Licence

Ce projet est sous licence [MIT](https://github.com/Neo-AzTeK/aztek-web.fr/blob/main/LICENSE).
