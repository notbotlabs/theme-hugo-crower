# theme-hugo-crower

A simple and clean blog theme for Hugo.

![](https://github.com/luizdepra/hugo-coder/blob/master/images/screenshot.png)

## How to use this theme

To use `crower` go through the following steps.

### Download

Clone this repository into your Hugo project.

```
git clone https://github.com/notbotlabs/theme-hugo-crower.git themes/crower
```

### Configuration

Add the following lines to your `config.toml`.

```toml
theme = "crower" # set the theme

[params] # theme parameters
    author = "John Doe" # author's name
    info = "Full Stack DevOps and Magician" # author's job title or info
    description = "John Doe's personal website" # site description
    keywords = "blog,developer,personal" # site keywords

# Social links
[[params.social]]
    name = "Github"
    weight = 1
    url = "https://github.com/johndoe/"
[[params.social]]
    name = "Twitter"
    weight = 2
    url = "https://twitter.com/johndoe/"
[[params.social]]
    name = "LinkedIn"
    weight = 3
    url = "https://www.linkedin.com/in/johndoe/"

# Menu links
[[menu.main]]
    name = "Blog"
    weight = 1
    url  = "/posts/"
[[menu.main]]
    name = "About"
    weight = 2
    url = "/about/"
```

You can look at full working [`config.toml`](https://github.com/luizdepra/hugo-coder/blob/master/exampleSite/config.toml) inside the [exampleSite](https://github.com/luizdepra/hugo-coder/tree/master/exampleSite) folder.

### Build & Test

To update or generate the minified CSS file:

```
make build
```

To build your site and test, run:

```
hugo server
```

## To Do

- Comments (probably not Disqus, sorry)
- Tags, Categories and Series


## Thanks to...

[Luiz de Prá](https://luizdepra.com) for his theme [Coder](https://github.com/luizdepra/hugo-coder), on which Crower is based.
