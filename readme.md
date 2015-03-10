# base-meteor

## initialize meteor project on your machine

````
meteor create <app_name>
cd <app_name>
meteor
````
(to stop the server hit ctrl + c on a Mac)

## copy the base scaffold

  - download this repo to your desktop
  - remove \<app_name\>.\* files from the \<app_name\> folder
  - copy the folder and file structure given to your \<app_name\> folder
  - point the browser at: http://localhost:3000/

## add or remove packages at your will

````
meteor add/remove <package_name>
````
[browse the packages here](https://atmospherejs.com/packages/most-used)

I often use these:
  - [iron:router](https://atmospherejs.com/iron/router) for routing
  - [accounts-base](https://atmospherejs.com/meteor/accounts-base) for user management
  - [twbs:bootstrap-noglyph](https://atmospherejs.com/twbs/bootstrap-noglyph) to include bootstrap
  - [sacha:spin](https://atmospherejs.com/sacha/spin) for a loading spinner
  - [fortawesome:fontawesome](https://atmospherejs.com/fortawesome) to include fontawesome (!note foRt)

## on deploy
on deploying to production don't forget to remove autopublish and insecure packages
````
meteor remove autopublish && meteor remove insecure
````
