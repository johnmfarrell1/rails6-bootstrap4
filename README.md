Rails 6 - Bootstrap 4
========

Blank Rails 6.0.2 example application that integrates Rails and Bootstrap 4.0 via Webpacker.
Bundled with [High Voltage](https://github.com/thoughtbot/high_voltage) also for easy static page generation.

#### Rails
Ruby on Rails, or Rails, is a server-side web application framework written in Ruby under the MIT License. 
Rails is a model–view–controller framework, providing default structures for a database, a web service, and web pages.
View the [Getting Started with Rails](https://guides.rubyonrails.org/getting_started.html) page for more information.

#### Bootstrap
Bootstrap is a free and open-source CSS framework directed at responsive, mobile-first front-end web development. 
It contains CSS- and JavaScript-based design templates for typography, forms, buttons, navigation, and other interface components.
View the [Introduction to Bootstrap](https://getbootstrap.com/docs/4.0/getting-started/introduction/) for more information

This application can be used as a starting position to quickly create new Rails applications which come with bootstrap.

Screenshots
--------
![Welcome Screenshot](https://raw.githubusercontent.com/johnmfarrell1/rails6-bootstrap4/master/screenshots/welcome_screenshot.png)

Getting Started
---

- [Fork this repository](https://github.com/johnmfarrel1/rails6-bootstrap4) OR alternatively [duplicate it](https://help.github.com/en/github/creating-cloning-and-archiving-repositories/duplicating-a-repository)
- Clone your repo: `git clone https://github.com/YOUR-USER/rails6-bootstrap4`
- Setup the application

```ruby
bundle exec bundle install
yarn install
rails db:create
rails server
```

Once complete, point your browser to http://localhost:3000 to view the application.

## Development
Bootstrap 4 was enabled via the [following steps](https://gist.github.com/bazzel/2c64e2e5804077f9a61938a93ed54823).
After checking out the repo and running over the installation steps, you can run `rails test` to run the tests via the web container. 
You can also run `bin/console` for an interactive prompt that will allow you to experiment.

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/johnmfarrell1/rails6-bootstrap4

## License

The gem is available as open source under the terms of the [MIT License](https://opensource.org/licenses/MIT).