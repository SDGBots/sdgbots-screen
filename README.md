# Screen

![github pages](https://github.com/scp-079/screen/workflows/github%20pages/badge.svg)

SCP-079 website is generated by [Hakyll], hosted on GitHub Pages.

---

## Site

This project's static Pages are built by [GitHub Actions][actions], following 
the steps defined in [`.github/workflows/gh-pages.yml`](.github/workflows/gh-pages.yml).

## Theme

We call this Hakyll theme `Screen`. 

This is a theme intended to use on [SCP-079](https://scp-079.org) website. 
The theme is converted from a Jekyll theme [darcli](https://github.com/gildasio/darcli). 
We made some changes to make it responsive and more suitable for our site.

There is a post [demo](https://scp-079.org/posts/2019-03-29-post-test/).

## How to use

To use this project as your user or group website, you will need 
additional steps to modify some source code files.

- `templates/archives.html`
- `templates/head.html`
- `templates/open_graph.html`
- `templates/header.html`
- `site.hs`

Also, you should delete some `.md` files in `pages/` and `posts/`.

## Building locally

To work locally with this project, you'll have to follow the steps below:

1. Fork, clone or download this project
2. Modify some files
3. Use stack:
    1. `stack setup`
    2. `stack install --only-dependencies`
    3. `stack build`
    4. `stack exec site build`
    5. `stack exec site watch`
4. View the site locally

Read more at Hakyll's [documentation][hakyll].

## Be Better

Contributions are always welcome, whether it's modifying source code to add new features or bug fixes, documenting new file formats or simply editing some grammar.

You can also join the [discuss group](https://t.me/SCP_079_CHAT) if you are unsure of anything.

## Getting help

* [Tutorials](https://jaspervdj.be/hakyll/tutorials.html)
* [Google discussion group](https://groups.google.com/forum/#!forum/hakyll)
* [Hakyll on StackOverflow](https://stackoverflow.com/questions/tagged/hakyll)

## Credit
This is a fork (forked on 1/26/2021 PST) of the repo from scp-079 (https://github.com/scp-079) project.

## License

This theme is under [GPLv3](LICENSES/GPL-3.0).
The theme is based on [darcli](https://github.com/gildasio/darcli).

All documents of this project is under [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/).

All the sound effects in `static/audio/` are under 
[CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/), 
and come from 
[SCP - Containment Breach](http://www.scpcbgame.com/) 
game.

[actions]: https://github.com/features/actions
[hakyll]: https://jaspervdj.be/hakyll/
[install]: https://jaspervdj.be/hakyll/tutorials/01-installation.html
