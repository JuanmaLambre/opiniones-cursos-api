# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...


## System dependencies

* Ruby 2.3
* SQLite3

To install Rails you can simply execute  
```gem install rails```  
Check that installation was successful by running  
```rails --version```  


## Rails "Getting Started"

[Here](http://guides.rubyonrails.org/getting_started.html) you can find the official starting tutorial for Ruby on Rails.  
You can also take a look at Michael Hartl's ["Ruby on Rails Tutorial"](https://www.railstutorial.org/book). The book offers a detailed tutorial for building a whole application from scratch. It is available online for free.


## Database creation

Install project dependencies:  
```bundle install```  

And then create the database:  
```rake db:create```  

Finally, migrate the database  
```rake db:migrate```  

To populate the database run  
```rake db:seed```  
Note that this will execute db/seeds.rb


## Debugging

To insert a breakpoint you must invoke ```byebug``` at desired line. This will open a debugging console where the server is running


## Testing

To run the tests execute  
```rake test```  

For more information consult the [official testing guide](http://guides.rubyonrails.org/testing.html)
