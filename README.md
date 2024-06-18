Introducing Flarester – the ultimate dynamic platform for creating and joining exciting events in your local area! Imagine a platform similar to "Meetup," but with an electrifying twist: it's all about events happening within the next two hours. That means you can instantly connect with the most engaging and relevant events around you!

Once an event is created, it's immediately added to the local event list, making it visible to all nearby users. This means endless possibilities for discovering new experiences and connecting with your local community. And the best part? After the event's scheduled time has passed, it magically disappears from the list, keeping the platform fresh and filled with only the most exciting events.

Flarester's mission is to spark casual networking, ignite new friendships, and expand your horizons. It's the perfect stage for interacting with your local community and forming connections with like-minded individuals who share your passions. Get ready to dive into a world of endless opportunities and meaningful connections with Flarester!

                                                 Create an account
                                                  
![](eventFlare_create.gif)

-----------------------------------------------------------------------------------------------------------------------------------

                                      Log in to view current events in your area
                                                       
![](eventFlare_loginAndView.gif)

-----------------------------------------------------------------------------------------------------------------------------------

                                                   Join an event
                                                   
![](eventFlare_joinEvent.gif)  

-----------------------------------------------------------------------------------------------------------------------------------

                                              Create and list an event
                                              
![](eventFlare_createYourOwnEvent.gif)

-----------------------------------------------------------------------------------------------------------------------------------

![](eventFlare_seeYourEvent.gif)

-----------------------------------------------------------------------------------------------------------------------------------

                                                Back out of an event
                                                
![](eventFlare_backOut.gif)

-----------------------------------------------------------------------------------------------------------------------------------

                                             View and edit your profile
                                             
![](eventFlare_viewEditProfile.gif)

-----------------------------------------------------------------------------------------------------------------------------------

The application is built using Ruby version 2.6.1. Once you have cloned the repository, please navigate to the application's directory and run the following commands:

- `bundle install`: This command installs the required gems and dependencies for the application to function correctly.
- `rails db:create`: This command creates the application's database.
- `rails db:migrate`: This command runs any pending migrations on the database.
- `rails db:seed`: This command seeds the database with the initial data.
  - If you have added new city and location objects in `app/db/seed.rb`, you must run `rails db:seed` again to ensure the database is seeded with the new data.

To run the application, type `rails s` into your command line (from the application's directory) and hit return. This command starts the application server, and you should be able to use the application.

Note that the application has a test suite you can run using RSpec. To install RSpec, type `rails g rspec:install` into your command line after cloning the repository. Once installed, type `rspec` into the command line and hit return to run the test suite.


-----------------------------------------------------------------------------------------------------------------------

We're thrilled to announce that our application is now available on Heroku! With our app, you can save a considerable amount of time, and you can access it by clicking on the link provided below:

https://powerful-eyrie-94140.herokuapp.com/

We want to express our gratitude to the following sources for their incredible contributions:

- The login page image is courtesy of https://unsplash.com/. It's a beautiful image representing our app's sleek, modern design.
- We used Racing Sans One for our logo, which can be found at https://fonts.google.com/. It's a unique font that helps our logo stand out.

Thank you for stopping by our page! We hope you find our app helpful and user-friendly. Feel free to leave any feedback you have. We're always looking for ways to improve.

As Patrick McKenzie once said, "Every great developer you know got there by solving problems they were unqualified to solve until they did it." We're confident that we're on the right path and can't wait to see where this journey takes us.
