#Education Management System

This system is the open-source application which was developed by using [Ruby On Rails](http://rubyonrails.org)

## Getting Started

[Ruby On Rails](http://rubyonrails.org) is web development framework which has the giant cummunity in the world. Let's start install some prerequisites before running project.

### Prerequisites

Install Ruby Programming

```
sudo apt-get install ruby-full
```

Install Bundler

```
gem install bundler
```

Install Rails

```
gem install rails
```

Install PostgresSQL and Create Owner Database

```
sudo apt-get install postgresql postgresql-contrib libpq-dev
sudo -u postgres createuser $USER
```

### Installing

Before running the project, you have to run some command to install third library gems which are from [RubyGems](https://rubygems.org), and create database.

Install Third Party Library Gems
```
bundle install
```

Create Database and Tables
```
rails db:migrate
```

***Congratulation!*** Now you are ready to run the Education Management System!

## Running the tests

Running or hosting the system by this command:
```
rails s
```

## Versioning

The Education Management System's version is ***1.0.9***


See also the list of [contributors](https://github.com/your/project/contributors) who participated in this project.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details
