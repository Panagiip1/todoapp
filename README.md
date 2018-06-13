- MVC
- Model, View, Controller
-

Ksekina ton Server

rails s -b 127.0.0.1 -p 8888

Snake case: hello_world my_name_is articles_controller

CameCase: HelloWorld MyNameIs ArticlesController


---Section 2

Gia mia nea Todo:

Initiate a Todo instance variable

@todo1 = Todo.new
instance variable

corresponding actions:
new - form na dhmiourghsoun mia new todo
submits to create hits the database with patch or gives an error

edit - form to edit an existing todo
submit to update - hits the database with patch or gives an error

index
lists all todos

show
displays an individual todo

delete 
destroys a todo

VERSION CONTROL! - git

Git einai ena version control system that lets you save your work among other thing 
You can push your code and save it to online repositories
You can push your code to production hosting services like heroku
You can collaborate with others since they can grab code and clone it etc...

Github, bitbucket

- Initialize a git repository for the application
- Made an initial commit


hash {key: value}


Flash 

Prosthetoume messages ston flash (to opoio einai hash)

Meta kanoume display ta contents twn mhmumatwn ta opoia einai ston flash

Todo.find(params[:id])






# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version

* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...
