# setup

### Start Here
- https://c9.io/new

### Fill out UI
- Name: -Whatever you want-
- Public
- Template: Blank

### Ruby & Rails Setup
```
rvm install 2.4.1
rvm use 2.4.1
rvm gemset create alpha
rvm use 2.4.1@alpha --default
gem install rails pry pry-byebug rspec httparty
```

### Config Files
```
cd ~
rm .bash_aliases .gitconfig
wget https://raw.githubusercontent.com/chyld/devops/master/dotfiles/c9/.bash_aliases
wget https://raw.githubusercontent.com/chyld/devops/master/dotfiles/c9/.gitconfig
```

### Final
- Edit the `~/.gitconfig` file in your home directory
- Close all Terminal windows and reopen

# database

### Postgres Setup
- `sudo service postgresql start`
- `psql`

# new app

- `rails new APP_NAME -d postgresql --skip-action-mailer --skip-action-cable --skip-coffee --skip-test --skip-system-test`
- edit Gemfile
```
gem 'pry'
gem 'pry-byebug'
gem 'pry-rails'
bundle install
```






http://guides.rubyonrails.org/active_record_migrations.html
http://api.rubyonrails.org/v5.1.3/classes/ActiveRecord/ConnectionAdapters/Table.html
http://api.rubyonrails.org/v5.1.3/classes/ActiveRecord/ConnectionAdapters/TableDefinition.html
http://api.rubyonrails.org/v5.1.3/classes/ActiveRecord/ConnectionAdapters/SchemaStatements.html
