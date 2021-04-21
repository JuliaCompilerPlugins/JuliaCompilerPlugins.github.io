# JuliaCompilerPlugins website

This repository hosts the landing page of the JuliaCompilerPlugins organization.

The website is built with [Franklin.jl](https://github.com/tlienart/Franklin.jl), and the
master branch is automatically deployed by Github Actions.

## Quick start

To view the site locally, install Franklin and run `serve()` in the root of this repository.

For deploying to `juliacompilerplugins.github.io`, just create a pull request. A comment will appear with a
link to a preview of the website. Once the PR is merged to master, CI will automatically
build the website and deploy to Github pages.
