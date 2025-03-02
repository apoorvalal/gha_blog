# `gha_blog`: a lean blogging setup powered by github actions and pandoc

Your blog is a directory markdown files. Github actions will render them into webpages and host.

First-time (and only-time) setup
- enable github action
- edit `templates/index_template.md` (and not `index.md` in root; the latter is overwritten on every render) to your heart's content.
- add some posts in `posts/` 
- Enable github pages
    - Settings > Pages > Branch (main) > root


For subsequent uses, just add your post in markdown and let github do the rest. 
