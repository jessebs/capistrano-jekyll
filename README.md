# Capistrano-Jekyll

Jekyll support for Capistrano 3.x.

## Installation

Add this line to your application's Gemfile:

```ruby
gem 'capistrano-jekyll'
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install capistrano-jekyll

## Usage

Require in *Capfile* to use the default task:

```ruby
require 'capistrano/jekyll'
```  
**jekyll:build** task will run after **deploy:updated** as part of Capistrano's default deploy, or can be run in isolation with `bundle exec cap production jekyll:build`

### List of tasks
* `cap jekyll:build # Build the website using Jekyll`
* `cap jekyll:doctor # Print Jekyll deprecation warnings`

## Contributing

1. Fork it ( https://github.com/ne1ro/capistrano-jekyll/fork )
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create a new Pull Request
