# Flarester
Get ready to experience Flarester – the ultimate dynamic platform for creating and joining engaging events in your local area! It's like "Meetup," but with a twist: it's all about events happening within the next two hours. This means you can instantly connect with the most exciting and relevant events around you! Flarester's mission is to spark casual networking, ignite new friendships, and expand your horizons. It's the perfect stage for interacting with your local community and forming connections with like-minded individuals who share your passions. Get ready to dive into a world of endless opportunities and meaningful connections with Flarester!

## Features
- **Discover Real-Time Event Listings**: Instantly see what's happening nearby and watch events disappear as they come to a close.
- **Engage with Your Community**: Make new friends and create connections at local events.
- **Sleek User-Friendly Interface**: Creating, joining, and managing events has never been easier.
- **Location-Based Services**: Utilizes geolocation to show events happening near you.
- **Receive Instant Notifications**: Stay in the loop and get notified the moment new events are created.

## Getting Started
### Prerequisites
Ensure you have the following installed:
- Ruby 2.6.1
- Rails 5.2 or higher
- Bundler

### Installation
Follow these steps to set up the project on your local machine:
1. **Clone the repository**:
   ```sh
   git clone https://github.com/seddonnguyen/Flarester.git
   cd Flarester
   ```
2. **Install dependencies**:
   ```sh
   bundle install
   ```
3. **Set up the database**:
   ```sh
   rails db:create
   rails db:migrate
   rails db:seed
   ```

### Running the Application
To start the Rails server, run:
```sh
rails s
```
Visit `http://localhost:3000` in your web browser to use the application.

## Contributing
I'd love your help to improve the Flarester! Whether it's bug fixes, new features, or enhancements, your contributions are incredibly valuable. Here’s how you can contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Open a pull request.

## License
This project is licensed under the MIT License, making it free to use and modify. See the [LICENSE](https://github.com/seddonnguyen/Flarester/blob/main/LICENSE) file for details.

## Contact
Your engagement is important to me. Please feel free to reach out with any questions or feedback by opening an issue on the repository. Your input is highly valued.

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
