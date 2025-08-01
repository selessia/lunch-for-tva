# Lunch för två
Recipe blog (Jekyll)

## Tips
[Recipe at Schema.org](https://schema.org/Recipe)

## Setting up the dev env
1. Install rbenv (a Ruby version manager)
```sh
brew install rbenv
```
2. Set up rbenv to load with your shell
```sh
echo 'eval "$(rbenv init -)"' >> ~/.zshrc
source ~/.zshrc
```

3.  Install a specific version of Ruby and set it as the global default
```sh
rbenv install 3.3.0
rbenv global 3.3.0
rbenv rehash
```

4. Verify the installation
```sh
ruby -v
which ruby
```

5. Install the Bundler and Jekyll gems
```sh
gem install bundler jekyll
```

## Starting the server
```sh
bundle exec jekyll serve
```
