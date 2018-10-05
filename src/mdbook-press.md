# mdbook-press

𝗠⬇️📖🦀
> Travis, make me an mdbook

`mdbook-press` aims to allow you get started with an mdBook by using pre-existing templates.

## Motivation

[mdBook](https://github.com/rust-lang-nursery/mdBook) is an awesome tool for making online books and documentation from Markdown files. 

Currently, to get started you can use a precompiled binary if it exists for your platform, otherwise you have to install from source, which can be daunting for some people.  

`mdbook-press` exists to facilitate creating an mdbook and also automate the building and publishing of your awesome content. It also aims to make it easier to build from **themes**. It leverages `Travis CI` to automatically publish to `github-pages`. So instead of fiddling around your `$PATH` or compiling from source, you can focus on writing your book/documentation.




## Acknowledgement

The CI workflow is based on the following instructions:
* https://github.com/rust-lang-nursery/mdBook/issues/714
* https://github.com/rust-lang-nursery/mdBook/pull/715
* https://rust-lang-nursery.github.io/mdBook/continuous-integration.html