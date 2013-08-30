# JScrollPane::Rails

A ruby gem that uses the Rails asset pipeline to include the jScrollPane plugin by Kelvin Luck
 (www.kelvinluck.com):

* Homepage: http://jscrollpane.kelvinluck.com/
* Source Code: https://github.com/vitch/jScrollPane

## Installation

Add this line to your application's Gemfile:

    gem 'jscrollpane-rails'

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install jscrollpane-rails

NOTE: this is a jQuery plugin so you will also need the `jquery-rails` gem:

* https://github.com/rails/jquery-rails

## Usage

In your `application.js` you will need to add this line:

    //= require jscrollpane
   
And in your `application.css` you will need to add this line:

    *= require jscrollpane

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Added some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request
