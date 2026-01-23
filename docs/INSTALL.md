# Préparer son environnemnt

Pour plus de simplicité et éviter des setups longs et fastidieux, nous allons nous servir des Github CodeSpaces pour réaliser cet atelier.

> **GitHub Codespaces** est un environnement de développement complet hébergé dans le cloud, accessible directement depuis ton navigateur ou VSCode. Il te permet de coder sans installer quoi que ce soit localement : tu ouvres un dépôt GitHub, tu lances un Codespace, et tu te retrouves instantanément dans un environnement préconfiguré avec tous tes outils, extensions et dépendances déjà installés. C'est comme avoir une machine de dev préconfigurée qui démarre en quelques secondes, que tu peux utiliser depuis n'importe où, et qui s'éteint automatiquement quand tu ne l'utilises plus pour économiser les ressources.

## Prérequis

Voici les pré-requis pour cet atelier :
- Un ordinateur (Windows, Linux ou Mac, peu importe)
- Un compte Github

## Préparer l'atelier

Pour cet atelier, vous allez devoir "fork" (reprendre pour vous) le dépôt des sources mis à votre disposition.

Pour cela :
- Rendez-vous sur [https://github.com/Hodson-Thomas/Codatelier-Rust](https://github.com/Hodson-Thomas/Codatelier-Rust)
- Cliquez sur le bouton `Fork` en haut à droite.
- Validez les paramètres.

Vous aurez accès à votre propre copie des sources de l'atelier.

En suite, vous allez devoir lancer votre codespace pour qu'il se construise. Pour cela, depuis votre dépôt forké :
- Cliquez sur `Code` en vert.
- Cliquez sur `Codespaces`.
- Cliquez sur le `+`.
- Laissez en suite l'environnement se construire tout seul.

> La construction peut prendre jusqu'à 10 minutes ; laissez simplement votre navigateur ouvert.

Une fois construit, vous devirez voir apparaitre dans le terminal en bas une sortie similaire à celle-ci :

```txt
rustc --version && cargo --version && trunk --version
rustc 1.92.0 (ded5c06cf 2025-12-08)
cargo 1.92.0 (344c4567c 2025-10-21)
trunk 0.21.14
Outcome: success User: vscode WorkspaceFolder: /workspaces/Codatelier-Rust
```

## Le jour de l'atelier

Vous pouvez retrouver votre codespace à cette adresse : [https://github.com/codespaces](https://github.com/codespaces).

Il vous suffira de cliquer sur son nom (en gras) pour le ré-ouvrir.