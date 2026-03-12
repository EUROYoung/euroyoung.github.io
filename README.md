# For Future Website Maintainers

This repository contains a website built with Jekyll.

## Previewing the Website Locally

To see your modifications in the browser, run:

```bash
bundle exec jekyll serve
```

Then open the local address shown in the terminal.

If this command does not work, you may be missing some dependencies.

### Installing the required dependencies

1. Install **Ruby**
   Follow the official guide: https://jekyllrb.com/docs/installation/

2. Install Jekyll and Bundler

```bash
gem install jekyll bundler
```

3. Install the project dependencies

```bash
bundle install
```

4. If necessary, update the dependencies

```bash
bundle update
```

## Warnings

⚠️ **Do not push `Gemfile.lock`** to the repository.

⚠️ The theme is stored **locally**, so it does not update automatically.
To remove the permalink icon from section titles, we modified:

```
./_sass/minimal_mistakes/_utilities.scss
```

## Credits

❤️ This README was written with love by
Eleonora Vercesi and Tullio Villa to help future maintainers of the website.
