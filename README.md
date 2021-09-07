# Simple Ruby on Rails Blog App

- start [Puma](https://github.com/puma/puma) web server
  - `bin/rails server`

## Hello World

### Routes

- `config/routes.rb`

### Generate Controller

- `bin/rails generate controller Articles index --skip-routes`

### Generate Model

- `bin/rails generate model Article title:string body:text`

### Migrate DB

- `bin/rails db:migrate`

# References

- [Getting Started with Rails](https://guides.rubyonrails.org/getting_started.html)
