# Thème pour Pelican

Ce thème a été en premier designé par [Eban](https://eban.bzh) avant d’être refait à ma sauce. Je me suis aussi beaucoup inspiré de [medius](https://github.com/onur/medius).

## Installation

Pour l’installation, suivez la [documentation officielle](https://docs.getpelican.com/en/4.5.4/pelican-themes.html).

## Variables

Vous pouvez définir une description sur la page auteur ainsi que des liens vers Twitter, Github, Mastodon et Gitea : 

```
NUIR_AUTHORS = {
    'John': {
        "description": "Lorem ipsum",
        "links": (('mastodon', 'link'),
                  ('github', 'link')),
    }
}
```

## Support de plugins

Ce thème supporte les plugins suivant :

* [Series](https://github.com/getpelican/pelican-plugins/tree/master/series).
* [Drafts](https://github.com/noirbizarre/pelican-drafts)
