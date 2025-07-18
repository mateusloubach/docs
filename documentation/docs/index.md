# Welcome to MkDocs

For full documentation visit [mkdocs.org](https://www.mkdocs.org).

_Current build:_ `BUILD_SHA_HERE`

## Commands

* `mkdocs new [dir-name]` - Create a new project.
* `mkdocs serve` - Start the live-reloading docs server.
* `mkdocs build` - Build the documentation site.
* `mkdocs -h` - Print help message and exit.

## Project layout

    mkdocs.yml    # The configuration file.
    docs/
        index.md  # The documentation homepage.
        ...       # Other markdown pages, images and other files.

    init commit - worked as expected. created gh-pages, jumped mikeScripts, completed.
    update commit #1 - gh-pages redirection worked as expected. slug worked, but wrong format.
    update commit #2 - checked for continuous workflow, and redirection from last commit to new commit;
    update commit #2* - added versioning tab. worked perfectly! it also organized by oldest to newest
    update commit #4 - checking if max number of commits in tabs is 3.
    update commit #5* - max # of displayed commits is 3. Confirmed issue that displayed only 3 items.
    update commit #6 - changed version slug creation in ci. worked perfectly!
    update commit #7 - try git tag to update major, minor, or feature addition; tag went, but wasn't added to version;
    update commit #8 - checking if tag applies on next commit. it applied, but slug is displaying the first format of verions;
    update commit #9 - going to see if commits follow new rule; commits followed new rule. - although I lose commit `8ba73bc`
    update commit #10 - recognized error in ci, fixed space. checking if worked. It didn't! - changed ci for correct results.
    update commit #11 - changed ci. expecting updated version. didn't work. changed the "determine version from tags"
    update commit #12 - last try.
    update commit #13 - going to try new tag with v0.2.0. did not work. broke logic.
    update commit #14 - applied new logic for version deployment. ok. back on track!
    update commit #15 - now am going to try to apply git tag.
    update commit #16 - trying new logic. - worked. updated verson with git tag
    update commit #17 - see if new version applied normal commits. broke.