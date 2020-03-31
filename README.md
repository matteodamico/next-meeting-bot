# BOT Slack [JS]

This slack bot receives the "/next-meet" command and answer with some info regarding the next dockeroma community meetup will be held.

Inspired from the startbot example

### Deploy the Bot in Heroku with GIT

Download Heroku CLI [here](https://devcenter.heroku.com/articles/heroku-cli)

Login
```sh
heroku login
```
Clone the repository
Use Git to clone source code to your local machine.
```sh
 heroku git:clone -a <REPOSITORY_NAME>
```

```sh
cd <REPOSITORY_NAME>
```

Deploy your changes
Make some changes to the code you just cloned and deploy them to Heroku using Git.

```sh
git add .
git commit -am "make it better"
git push heroku master
```


### Note

```
### License

**[This project is licensed under the terms of the MIT license.]**
