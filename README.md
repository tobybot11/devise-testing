# README

## Rails install notes

```
 $ rvm list
 $ rvm use 2.4.3
 $ rvm gemset list
 $ rvm gemset create a-testing
 $ rvm gemset use a-testing
 $ gem list
 $ gem install rails
 $ rails new a --database=postgresql
 $ cd a
 $ cat Gemfile
 $ rvm --default use 2.4.3
 $ rvm gemset list_all
 $ gem list
 $ rvm use 2.4.3@a-testing --create --ruby-version 
 $ rvm gemset name
 $ cat .ruby-gemset .ruby-version
 $ bundle install
```

## Git work .. after creating new repo in github
```
 $ git status
 $ vi README.md
 $ git add -A
 $ git commit -a -m "initial commit afer rails new app --database=postgresql and rvm work"
 $ git commit --amend
 $ git remote add origin https://github.com/tobybot11/devise-testing.git
 $ git push -u origin master
```

## Bootstrap
```
 $ vi Gemfile
# toby adds
gem 'bootstrap', '~> 4.0.0'
 $ bundle install
```

## gpg interlude
```
 $ gpg --edit-keys toby.ford@pobox.com
 > passwd
 > save
```

## TODO
Things you may want to cover:

* Ruby version , System dependencies , Configuration , Database creation , Database initialization
* How to run the test suite, Services (job queues, cache servers, search engines, etc.)
* Deployment instructions
