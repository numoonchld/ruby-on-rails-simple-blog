# Simple Ruby on Rails Blog App

- start [Puma](https://github.com/puma/puma) web server
  - `bin/rails server`

## Notes

### Routes

- `config/routes.rb`

### Generate Controller

- `bin/rails generate controller Articles index --skip-routes`

### Generate Model

- `bin/rails generate model Article title:string body:text`

### Migrate DB

- `bin/rails db:migrate`

## Generate a new Model

- `bin/rails generate model Comment commenter:string body:text article:references`

## Generate Controller for new Model

- `bin/rails generate controller Comments`

# References

- [Getting Started with Rails](https://guides.rubyonrails.org/getting_started.html)
