# Rails application template

Rails Application Template. - [Rails Application Templates — Ruby on Rails Guides](http://guides.rubyonrails.org/rails_application_templates.html)

It's easy to start Rails application with useful gems.

## Preparation

### Upgrading ruby version in rbenv

Fill following commands:

```
# Update Homebrew
$ brew update

# Generate modern .gitignore
$ brew install wget gibo

# Update ruby-build
$ brew upgrade ruby-build

# Show some ruby versions which rbenv can install
$ rbenv install --list

# Install ruby which you want(e.g. 2.3.1)
$ rbenv install 2.3.1

# Set ruby version
$ rbenv global 2.3.1
```

### Install latest Rails gem

```
# Set to use rails latest version(e.g. 5.0.2)
$ gem install rails -v 5.0.2
```

## Execution command

Execute following commands:

```
$ rails new app_name --database=mysql -T --skip-bundle -m https://raw.githubusercontent.com/tackeyy/rails_template/master/template.rb
```

## Supported versions

- Ruby 2.3.1
- Rails 5.0.2
