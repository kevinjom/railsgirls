### RailsGrils Demo

### Run
1. Clone this repo
2. Install gems `bundle install`
2. Migrate database `rails db:migrate`
3. Start the server `rails s`

### Deploy to Heroku
#### PreCondition
 - Registered a heroku account
 - Got [Heroku toolbelt](https://toolbelt.heroku.com/) installed

#### Steps
1. Run `heroku create` to create an app on heroku, this will also create a git repo in heroku and add it to your remote list
2. Push the code to heroku git repo `git push heroku master`, heroku will know this is a ruby/rails project, and run `bundle` and `rails s` automatically
3. Migrate db with `heroku run rake db:migrate`
4. Open with `heroku open`

For further infomation of heroku deployment, click to [go](https://devcenter.heroku.com/articles/getting-started-with-ruby#introduction)
