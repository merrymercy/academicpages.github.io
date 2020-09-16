
## Help

- Top navigation bar : `_data/navigation.yml`
- About page : `_pages/About.md`

## Run locally 

### Ubuntu

* Clone the repository and made updates as detailed above
* Make sure you have ruby-dev, bundler, and nodejs installed: `sudo apt install ruby-dev ruby-bundler nodejs`
* Run `bundle clean` to clean up the directory (no need to run `--force`)
* Run `bundle install` to install ruby dependencies. If you get errors, delete Gemfile.lock and try again.
* Run `bundle exec jekyll serve` to generate the HTML and serve it from `localhost:4000` the local server will automatically rebuild and refresh the pages on change.

### Mac
* Install
```
sudo brew install rbenv
sudo gem install bundle
bundle clean
bundle install
```
* Serve
```
bundle exec jekyll serve
```
 
