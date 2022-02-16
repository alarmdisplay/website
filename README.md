# Website
The website for the project, hosted at https://alarmdisplay.org/.

Built with [Hugo](https://gohugo.io/), using the [Syna](https://github.com/okkur/syna) theme.

## Development
The theme is referenced as a [submodule](https://git-scm.com/book/en/v2/Git-Tools-Submodules).
Use the following command to clone this repository including the theme submodule:
```
git clone --recurse-submodules https://github.com/alarmdisplay/website.git
```

Use `make serve` or `hugo server -D` for a live preview while editing the files.

## Deployment
Use `make build` or simply `hugo` to generate the static files.
They get stored in a directory called _public_, from where they can be uploaded to a web server.

The main branch is automatically built and deployed.

[![Build Status](https://drone.abrain.dev/api/badges/alarmdisplay/website/status.svg?ref=refs/heads/main)](https://drone.abrain.dev/alarmdisplay/website)
