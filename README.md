# Quill Editor Rails

The repository just wrap [Quill Reich Text Editor](https://quilljs.com/docs/quickstart/) in Rails. And the package just wrap quill.min.js and quill stylesheets. You can use [quilljs-rails](https://github.com/abhinavmathur/quilljs-rails) or [quill-rails5](https://github.com/paul-at/quill-rails5) if you need view_helper or something else to help you render Quill editor easily.

## Installation

Add this line to your application's Gemfile:

```ruby
gem 'quill-editor-rails'
```

And then execute:

    $ bundle install

Or install it yourself as:

    $ gem install quill-editor-rails

## Usage

- app/assets/javascripts/application.js
```
//= require quill.min
```

- app/assets/stylesheets/application.scss
```
@import 'quill.snow.css';
// or
@import 'quill.bubble.css';
```
