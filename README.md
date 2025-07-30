# Delotha Consulting Website

## Repo Info

This is the repository for Image Collection store in Mississauga, Ontario, Canada. This website is hosted on GitHub Pages.

You can find it at [imagecollections.ca](https://www.imagecollections.ca).

This site uses the [Minimal Jekyll theme](https://pages-themes.github.io/minimal/)

## Development

These are the commands required to develop this website locally:

```sudo apt install ruby-full```

Don't install Ruby gems as root, though. Put this into your .bashrc to configure where to install gems for your user:

```markdown
# Install Ruby Gems to ~/gems
export GEM_HOME="$HOME/gems"
export PATH="$HOME/gems/bin:$PATH"
```

Go to the folder where the website is
```bundle install```

This is the repeatable command to build the site and view it:  ```bundle exec jekyll serve```  
Or use this to get live reload capabilities, while designing the site:  ```bundle exec jekyll serve --force_polling --livereload```
