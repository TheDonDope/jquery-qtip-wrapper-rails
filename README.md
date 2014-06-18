# Jquery::Qtip::Wrapper::Rails

This gem is a simple wrapper around the jQuery qTip plugin.
It is bundled as a gem to be able to include this 3rd party asset into the asset pipeline, without having to locally import the actual CSS and JavaScript into your project.
Please see hhttp://craigsworks.com/projects/qtip for the original plugin.

## Installation

Add this line to your application's Gemfile:

    gem 'jquery-qtip-wrapper-rails'

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install jquery-qtip-wrapper-rails

## Usage

1. In your `app/assets/javascripts/application.js` include the following line:

    `//= require jquery.qtip`

For further HTML and CSS examples, please see: http://craigsworks.com/projects/qtip/docs/

## Contributing

1. Fork it ( https://github.com/[my-github-username]/jquery-qtip-wrapper-rails/fork )
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create a new Pull Request
