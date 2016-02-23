# dev-recipes
My itamae recipes for develop server

## Install tools
* [tig](https://github.com/jonas/tig)
  * https://github.com/sue445/itamae-plugin-recipe-tig
* [git-now](https://github.com/iwata/git-now)
  * https://github.com/sue445/itamae-plugin-recipe-git_now
* [tmux](https://tmux.github.io/) (without package)

## Setup
```sh
bundle install
```

## Usage
### ssh
```sh
bundle exec itamae ssh install.rb --node-yaml=node.yml --port=22 --host=<HOST>
```

### local
```sh
sudo bundle exec itamae local install.rb --node-yaml=node.yml
```
