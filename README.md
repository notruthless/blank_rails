#Basic Rails app to start a new app
- Rails 4.2
- Adds minitest-reporters and mini-backtrace gems
- Adds bootstrap
- Has initial static pages 
- Has basic user framework, including (optional) account activation

###Configuration settings (set in config/environments files):
```
    # whether to send a validation email for new accounts
  Rails.configuration.x.validate_account_activation = false

    # the name of the app (to use for the title, etc)
  Rails.configuration.x.app_title = "Starter App"
```
