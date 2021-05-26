# Website
The website for the project, hosted at https://alarmdisplay.org/.

Build with [Hugo](https://gohugo.io/), using the [Syna](https://github.com/okkur/syna) theme.

## Development
The theme is referenced as a [submodule](https://git-scm.com/book/en/v2/Git-Tools-Submodules).
Use the following command to clone this repository including the theme submodule:
```
git clone --recurse-submodules https://github.com/alarmdisplay/website.git
```

Use `hugo server -D` for a live preview while editing the files.

Execute `hugo` to build the static files.

## Deployment
The main branch is automatically built and deployed.

[![Build Status](https://drone.abrain.dev/api/badges/alarmdisplay/website/status.svg?ref=refs/heads/main)](https://drone.abrain.dev/alarmdisplay/website)
