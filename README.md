# ChainSafe Systems Protocol Engineering

:scroll: ChainSafe Protocol resources.

* <https://chainsafe.github.io/protocol>

### Instalation

This repo suses Jekyll static website generator, so first you needto install

- [Ruby](https://www.ruby-lang.org/en/documentation/installation/)
- Jekyll with `gem install bundler jekyll`
- Install gems with `gem install`

### Build
 You need to translate html file to md locally with running

 `./script/cibuild`

### Usage

Boilerplate can be placed in `includes/` as markdown and will be available as `include #{file}.html` after build.

To list jobs on the ChainSafe website, add them to `assets/jobs.json`.

To test result locally use

`jekyll serve`