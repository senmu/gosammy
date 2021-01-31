# samlu.ca

Personal portfolio of Sam Lu. It is based on [Pineapple](https://github.com/arnolds/pineapple), a minimalistic [Jekyll](https://jekyllrb.com) portfolio theme that focuses on putting your projects in the spotlight.

## Contents

- [Setup](#setup)
- [Deploy to Github Pages](#deploy-to-github-pages)
- [Creating projects](#creating-projects)
- [Resources](#resources)
- [License](#license)

## Setup

Install dependencies:

```
$ gem install jekyll bundler
```

Pulldown the project:

```
$ git clone git@github.com:senmu/samlu-portfolio.git
$ cd samlu-portfolio
```

Start Jekyll:

```
$ jekyll serve
```

Browse to http://127.0.0.1:4000/samlu/ for some portfolio goodness.

## Deploy to Github Pages

1. Fork this repository, then rename the repository to yourgithubusername.github.io.
2. Update user configuration values in `_config.yml`, and also set `baseurl: ""`.

## Creating projects

Projects are created as `.md` documents within the `_posts/projects` directory. They follow the same naming conventions as regular [Jekyll posts](https://jekyllrb.com/docs/posts/). Pineapple comes with four example projects, which you should use as a guide for creating your own e.g. [Red Pineapple](_posts/projects/2017-04-01-redpineapple.md).

## Resources

- [Apple Devices PSD Mockup Templates](https://www.graphicsfuel.com/2016/04/apple-devices-psd-mockup-templates/)

## License

Open sourced under the [MIT license](LICENSE.md).
