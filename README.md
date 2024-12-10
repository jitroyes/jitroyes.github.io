# Site web

Pour servir en local:

```bash
# En administrateur
apt install ruby-dev
gem update bundler

# POur initialiser
export GEM_HOME=$HOME/.gem
bundle install

PAGES_REPO_NWO=jitroyes/jitroyes.github.io bundle exec jekyll serve
```
