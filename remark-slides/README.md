# Remark assets for slides management at Bluewind

Please include this repository as a submodule in your slides project
and enjoy using Markdown for easy preparation of HTML based slides
at Bluewind.

# Starting a new slides set

  - start a new repository for the slides project
  - include this repository as a submodule
  - create a few useful folders
  - copy a few useful files from this repository up to the new project
    and modify if needed according to the needs
  - edit an initial README.md for this new repository
  - start adding new slides or modifying existing slides (see below)

```bash
$ mkdir slides-set && cd $_
$ touch README.md
$ git init
$ git add . && git commit -m "new slides set"
$ git submodule add git@git.bwlocal.it:BWTEACH/remark-slides.git
$ mkdir assets && touch assets/.keepme
$ mkdir stuff && touch stuff/.keepme
$ mkdir pdf && touch pdf/.keepme
$ cp remark-slides/example.* .
$ cp remark-slides/.gitlab-ci.yml.example .gitlab-ci.yml
$ cp remark-slides/.gitignore.example .gitignore
$ cp remark-slides/reamrk-README.md.example remark-README.md
$ cp remark-slides/README.md.example README.md && nano README.md
$ git add . && git commit -m "new slides set ready to start"
```

# Slides preparation and usage workflow

Please read the enclosed specific manual `remark-README.md.example`.

### Credits

- 2017 Stefano Costa, Bluewind
- https://github.com/gnab/remark/wiki
- http://tech.graze.com/2015/07/31/easily-create-slideshow-presentations-from-markdown-with-remark-js/
