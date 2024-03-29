# Liubomyr Antonyk Chat Application Overview

#### Student ID: 52320605

 I started creating my project by creating the about page and adding all the bootstrap and design features.
 Added new logic to chat page: 
 - is_typing
 - notificaiton of new users
 - list active users 
 - random name generator in case guest haven't type it etc.

## Development Approach

- **Page Design:** Utilized Bootstrap for responsive design across the application. I decided to use white and mix of blue shades, because it looks more formal and luxury.
- **User Interface:** I created navigation bar, that helps client to navigate throut different pages. Also, I added some animation to split the page into different topics. I did it by divs that slightly and smoothly change their colours. Despite that, I love hovering animation when some content
zooms smoothly, that’s what I implemented in some of the divs and my picture.
- **Chat Functionality:** Developed the chat feature to support multiple users, allowing for real-time messaging, room selection, active user display and ability to see who is currently typing message.

## Challenges

- **Real-Time Communication:** Implementing a responsive and real-time chat system posed a challenge, requiring understanding in JavaScript and knowledge of client-server architecture.
- **Room Management:** The most challenging for me in the web application part was creating rooms for users because there you have to
put everything into a specific object and you have to create a separate file to get the data out of there. That was quite challenging
for me. Also, broadcasting the notification wasn’t a simple task as well, because I had to use specific functions to complete it.
- **UI Responsiveness:** I had to make sure that contant nad all features work smoothly with different screen sizes.

## Technical Details

- **Client-Server Communication:** Leveraged WebSockets for real-time async communication between the client and server.
- **Front-End Development:** Utilized HTML, CSS (with multiple stylesheets for specific sections), and Bootstrap for the front-end design, ensuring a responsive and intuitive layout.
- **Server-Side Logic:** Server-side scripts were developed to handle connections, manage chat rooms, and broadcast messages to the appropriate recipients.
- **JavaScript:** Employed JavaScript extensively to dynamically update the chat interface, manage user interactions, and communicate with the server.

## Conclusion

Overall, this project tought me how client-server architecture works. I was amazed, how we can edit html by adding blocks of messages into it to show it on the screeen. Also it was nice to get hands dirty in JavaScript library called WebSockets. I am sure that this website will come handy in the future as the portfolio/CV.
