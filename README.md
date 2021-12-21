# Introduction

This repository holds the HUGO source code for the website [arminkekic.com](https://arminkekic.com/).

# Repository structure

After building the website via

```bash
hugo
```

the output will be stored in `./public/`. The github pages website is launched from [this repository](https://github.com/akekic/akekic.github.io) which is a submodule in this repository under `./public/`. So after building the website we can push the output to the other repository via

```bash
cd public
git add .
git commit -m "<COMMIT MESSAGE FOR BUILD OUTPUT>"
```

Then go back and push the source repository:
```bash
cd ..
git add .
git commit -m "<COMMIT MESSAGE FOR SOURCE>"
```
Note that we **first push the build output and then the source**. Also make sure that you **always push both the build output and the source**.


Read more about how to set up the repository structure for HUGO and gihub pages in [this blogpost](https://www.adamormsby.com/posts/000/how-to-set-up-a-hugo-site-on-github-pages-with-submodules/).