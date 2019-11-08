# Capistrano Sidekiq Test

To test

- sidekiq (6.0.3)
- capistrano-sidekiq (1.0.3)

```
vagrant up
bundle install
cap production sidekiq:install
cap production deploy
```
