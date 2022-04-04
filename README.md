# Name-your-cocktail - Project 2
 
This cocktail-themed project was the creation of a 48 hour pair programming challenge with [@marilynpoku](https://github.com/marilynpoku), where we had to build a React app and use data from a public API.
 
![Cocktails](https://i.imgur.com/Cwe8yHd.png)
## Deployment
 
This project is deployed with Netlify, [click here](https://name-your-cocktail.netlify.app/) to try it out.
 
 
## Technologies used
 
**Frontend:** React, SASS, React Bootstrap
 
**API:** [https://www.thecocktaildb.com/api.php](https://www.thecocktaildb.com/api.php)
 
 
## Brief
 
The brief was to pair programme to build a front end application in 48 hours by using ReactJS and at least one public API. 
 
We decided to build an app that would generate a cocktail menu based on your name.

## Planning
 
As this project was only for 48 hours, we decided to take the opportunity and pair
programme together and join to tackle the new topic at the time, React.
 
We started with our planning first and the idea for us was to create a website that would return personalised data for each user.\
After finding CocktailDB, one of the endpoints had a possibility to search the database by first letter which gave us the final idea to generate cocktail menus by each letter of the user's name.
 
![Cocktail- wireframe](https://i.imgur.com/dr72kVG.png)
 
 

## Process

Throughout this project as we worked remotely and we were both pretty new to using ReactJS at the time, we decided to work with one of us sharing a screen and together come up with the code we wanted to write. I found this was a great opportunity to brush up my knowledge on correct terminology as well as get better at explaining my code and reasoning my decisions around code.
 
We started our coding off by laying a basic file structure to get a good visual of the flow and pages we were going to build.\
Once we had a rough text and component layout ready we decided to connect to the api and start testing the data and how we would like to display it. Soon we were faced with our first blocker which had to do with trying to save the data with unresolved promises. This was due to needing to make an API request per each letter so often it would return undefined or the data was nested within the promises and making it hard to loop through.
The solution came in a pretty package of wrapping the requests (request per letter) to an array which we then were able to pair with asynchronous methods. This then would allow us to wait for the promises to be resolved until moving forward by setting the data to our state.
 
![Code snippet - promises](https://i.imgur.com/cPCqE36.png)
 
As the theme for our app was cocktails, dark colours came as a no brainer in the styling and allowed us to add bright coloured borders to resemble neon lights of the nightlife.
 
![Cocktail- Menu](https://i.imgur.com/VwNDiJq.png)
 
## Bugs and Challenges
 
Our biggest struggle or bug was to get our API requests to return back with data simultaneously with resolved promises. Solving this took enough time for us to contemplate changing the theme for this project multiple times.
 
## Wins
 
Following up on the bugs and challenges, needless to say that once the bug was fixed and the data was saved to a state correctly I could’ve cried from happiness.
 
## Future Add-ons
 
- Responsive for mobile
- Add custom drinks for few missing letters
- Add animations to create better user experience
 
## Key Learnings
 
The biggest take away from this project for me was understanding promises and how asynchronous functions execute.\
I also really enjoyed how pair programming gave me the opportunity to brush up my technical vocabulary and practise better communication when we would at times have to explain parts of the code to each other and share ideas of building our code.

