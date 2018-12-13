# faq  with added feature
#installation
1.Clone given GitHub repository to local computer
https://github.com/zangjiahou/faq.git

2 .Generate an app encryption key(php artisan key:generate

3 .In the .env file  allow laravel to connect to local database
  DB_CONNECTION=sqlite
  DB_DATABASE=Full path of database.sqlite
  DB_HOST=127.0.0.1
  DB_PORT=3306
  DB_USERNAME=homestead
  DB_PASSWORD=secret

4 .migrate database and seeds

5 .start the project to use the features.

# Features
 Basic user Registration and Login
 
 Asking questions
 
 Posting answer
 
 Creating Profile
 
 
 Voting answers
 （add two buttons to vote the answer UP or DOWN for like and dislike in the answer page）