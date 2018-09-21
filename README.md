# plugin_people_redmine
The plugin was edited for KAP Tech

after instaling, put it into the directory: /{:root}/plugin 

If the plugin requires a migration, run the following command in #{RAILS_ROOT} to upgrade your database (make a db backup before).

For Redmine 1.x:
bundle exec rake db:migrate_plugins RAILS_ENV=production

For Redmine 2.x:
bundle exec rake redmine:plugins:migrate RAILS_ENV=production

restart your redmine) 
