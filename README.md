# Digital garden repository
This is the repository which contains all the notes and code to create my digital garden, available at [wesleyfinck.org](https://wesleyfinck.org).

# references
To set this up, I followed the guide at [Setting up your own digital garden with Jekyll](https://maximevaillancourt.com/blog/setting-up-your-own-digital-garden-with-jekyll) and forked the template directory available here: https://github.com/maximevaillancourt/digital-garden-jekyll-template

# Getting Started
- create a subdirectory inside your obsidian vault (I call mine `digital-garden`)
- move any notes you want to publish inside that vault
- copy `file_sync_template.sh` into a new file `file_sync.sh`
- replace `SRC` and `DEST` in `file_sync.sh` with the path to you obsidian subdirectory and the path to `_notes/` in this directory
- run `./file_sync.sh` whenener new notes are in your obsidian subdirectory, and then commit and push to your github repo

## License

Source code is available under the [MIT license](LICENSE.md).
