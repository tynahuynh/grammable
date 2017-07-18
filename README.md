# [Grammable](https://grammable-tyna-huynh.herokuapp.com/)
An Instagram clone that was built using industry-standard, test-driven development following numerous red/green/refactor cycles.

![alt tag](https://user-images.githubusercontent.com/14388583/28289139-61201e20-6af6-11e7-942e-5bbfdf1ee4a1.png)

## Running Locally
Make sure you have Ruby installed.
Clone or download the repository.

Run the following code to install the application's dependencies:
```
bundle install
```
Create initial database:
```
rake db:create
```
Run the migration:
```
rake db:migrate
```

The application should now be running on your localhost.

## Testing
To run test suite:
```
bundle exec rspec
```

## Deployment
To deploy on Heroku. Adjust the APP_NAME to your project name.
```
heroku create APP_NAME
```
Now push it up to Heroku with the following command:
```
git push heroku master
```
It should take a few moments to run, and when it finishes it should say "Launching..." along with a URL.

To easily see you heroku url you can type:
```
heroku apps:info
```
The application can now be found at the URL returned.
