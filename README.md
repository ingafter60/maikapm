# BUILDING Rails Application using Ruby 2.5.1 and Rails 5.2.0

## 3. Start the new SaaS App

1. Setting up the development environment in Ubuntu Windows Subsystem
2. Create the app using postgresql
3. Create the database
4. Test it out
5. Relevan source: https://github.com/udemyrailscourse/saas-project-app
6. Push to github
7. Create home page: > rails g controller home index
8. Create home route: root 'home#index'
9. Add gem group production
10. Update gem: > bundle install --without production
11. STEPS TO PUSH THE APP TO HEROKU
11.1 > Create account to Heroku
11.2 > Install The Heroku CLI
11.3 > Heroku login
11.4 > heroku create
11.5 > heroku rename saas-projectmanager
11.6 >  git push heroku master
