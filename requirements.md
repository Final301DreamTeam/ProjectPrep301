#  Software Requirements 

## Product vision
- Being new or not knowing the place your in,it can be very difficult to find good quality food. We will help guide and educate users, on the best resturants in there location based on their cravings and let them choose the one they like.



## Pain point this project solves
- We help. educate are users to better understand the enviroment of food that there in, so they can make the best choise based on there cravings.


## The why behind our product
- To help local moms and pops shops be discover by either local or new people visiting the city, and also help educate pepole of restueants near them.


### Scope (In/Out)
- IN - What will your product do
  - website will have landing page that requires you to login with Auth0
  - After logging in user can input a city and food type of their choice which then displays  restaurants in their location that match their discription.
  - a user can add restaurants in their save for later
  - the user can edit saved resturant


- OUT - What will your product not do.
  - website will not turn into an IOS or android app
  - you will not be able to change the restaurant data.



## MVP functionality

- Initial page(home page with auth0 login)
- On login it displays a page with a form that allows the user to input a city
- Once a city is entered the page renders a map and a  form that allows you to add/create  trip data
- Button to redirect to profile(page) that has saved trip data
- User then can read update and delete trip data from profile  page
About us page.



## Stretch goals
- filter by rating
- cache the api calls 

## Functional Requirements

- user can search city and food type
- user can save restaurants
- user can update restuarant
- user can delete a restaurant

## Data Flow

1. user arrives at home page, shown an auth0 login
2. user then is shown after logging in with aut0 a form that accepts city and food type as input.
3. user then is shown a list of restaurants from input. 
4. user can click on a restaurant and add it to saves 
5. user then navigates to their saves and is shown added restaurants.
6. user can make notes on their saved restaurants. 
7. user then can choose to delete their saved restaurant.

## Non-Functional Requirements 
  
  ### Testing
      
  - manual test it and check for bug there and test how fast the api is when doing calls multiple times. 

  ### Security
  - If auth0 is down the user won't able to login to our site and
       access the data correctly. Make sure our .env file is not on 
       our github only the sample one.
