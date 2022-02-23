# first-10-stories
User Story 1: Welcome Page
```
As a visitor, when I visit 
"/"
I see link to login,
a link to register as a new user,
and a link to search for adventures. 
```
User Story 2: Register Page 
```
As a visitor, when I visit 
"/register", 
I see a form to enter my email, password, password confirmation, adventure preferences(checkboxes), address, username,
and a link back to the welcome screen. When I register with an email already in use, I receive an error message. 
If successful, I am taken to my user show page and shown a confirmation message. 
```
User Story 3: Login Page 
```
As a user, when I visit 
"/login", 
I see a form to enter my email OR username and password
and a link back to the welcome screen. When I login, I see a successful or failed login message. 
If successful, I am routed to my user show page. 
``` 
User Story 4: User Show Page 
```
As a user, when I visit 
"/user", 
I see my first and last name, a link to plan an adventure, my past adventures, and my upcoming adventures. 
I also see a link to update my account and a link to delete my account. 
I also see a link to return to the welcome screen. 
``` 
User Story 5: User Edit 
```
As a user, when I visit 
"/user/edit",
I see a form to update my username, email, password, address, and adventure preferences. 
I also see a link to return to the welcome screen. 
``` 
User Story 6: User Delete
```
As a user, when I visit 
"/user",
I see a button to delete my account, that when clicked displays
an "are you sure" message, and when confirmed deletes my account, and reroutes to the welcome page. 
``` 
User Story 7: Unregistrered Adventure Search 
```
As an unregistered visitor, when I visit 
"/adventure/new",
I see a form to search adventures based on my location,
and I am NOT able to specify activities, and page convinces me to register for better functionality, 
and links to the register page.
``` 
User Story 8: Unregistered Adventure Search Submit
```
As an unregistered visitor, when I visit 
"/adventure/new",
and fill in the form with my location, 
I see a list of the 10 closests recreation areas to my location,
and am again prompted to register for increased functionality to see the 50 closest. 
``` 
User Story 9: Registered Adventure Search 
```
As an registered visitor, when I visit 
"/adventure/new", 
I see a personalized greeting, a form to search for adventures by location AND/OR preferences, 
and a button for "random adventure for you!" 
``` 

User Story 10: Registered Random Adventure within Radius
```
As an registered visitor, when I visit 
"/adventure/new", and click on "random adventure for you!",
I see a form that lets me specify radius from my location that have activities that match a random preference of mine, 
a button to "plan an adventure" for that area. 
``` 



