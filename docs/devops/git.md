# Git

> Comme dirait Karadoc, **c'est la vie !**

- [Git](#git)
  - [Objectifs](#objectifs)
  - [Installation](#installation)
    - [Sous Linux (ubuntu)](#sous-linux-ubuntu)
  - [Syntaxe tableau](#syntaxe-tableau)
  - [Mise en forme du texte](#mise-en-forme-du-texte)

## Objectifs

[Git](https://git-scm.com/) sert à:

- suivre des modifications textuelle
- définir des versions
- a être utilisé avec des plaformes comme [Gitlab](./gitlab.md)
- ...

## Installation

### Sous Linux (ubuntu)

[![tux](./images/tux.png)](http://tux.org)

1. apt update
2. apt install git
3. git --version

## Syntaxe tableau

| Commande | Description |
| --- | --- |
| ls | Liste les fichiers |
| cat | affiche les contenus |

## Mise en forme du texte

On peut mettre **en gras**, *en italique*, ~~en barré~~, en rusant, <span style="text-decoration: underline;">en souligné aussi</span>.

Utilisez `npm run dev` pour lancer l'application, utilisez l'option `--port` pour choisir le port.

```jsx
function Video({ video }) {
  return (
    <div>
      <Thumbnail video={video} />
      <a href={video.url}>
        <h3>{video.title}</h3>
        <p>{video.description}</p>
      </a>
      <LikeButton video={video} />
    </div>
  );
}
```

- [ ] Item 1
- [x] Item 2
- [ ] Item 3