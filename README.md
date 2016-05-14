Prerequisites:

- [www.restsecured.xyz account](www.restsecured.xyz)
- [heroku account](https://heroku.com/)
- [heroku toolbelt](https://toolbelt.heroku.com/)

Steps:

1. Grab it (Fork it or clone it), go to directory

2. heroku create

3. heroku labs:enable runtime-dyno-metadata

4. git push heroku master

5. just schedule scan by pointing out {your app name}.herokuapp.com/swagger.json path
