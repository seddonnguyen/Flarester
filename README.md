*Flarester* is a versatile and dynamic platform that lets users create or join events in their local area. The platform operates similarly to the popular "Meetup" service but with a unique twist: it caters to events scheduled within the next two hours. This feature ensures that users can quickly and easily engage with timely and relevant events.

Once an event is created, it is automatically added to the local event list, providing visibility to all nearby users. This feature helps users connect to their local community and discover new events or experiences. Moreover, once the event's scheduled time has elapsed, it is automatically removed from the list, ensuring that the platform remains up-to-date and only shows relevant events to its users.

Flarester's primary objective is to create opportunities for casual networking, facilitate new friendships, and expand the user's horizons. The platform provides an ideal space for users to interact with their local community and build new relationships with people who share similar interests.

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
