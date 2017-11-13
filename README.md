# gerenciador_projetos
REDMINE CUSTOM

Após fazer o clone do projeto, execute:

$ rake db:create
$ rake db:migrate
$ bundle exec rake redmine:plugins NAME=redmine_agile RAILS_ENV=development

Envio o projeto ao heroku e execute:

$ heroku run rake db:migrate
$ heroku run bundle exec rake redmine:plugins NAME=redmine_agile RAILS_ENV=production
