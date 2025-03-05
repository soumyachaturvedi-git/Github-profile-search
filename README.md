an interactive GitHub Profile Search application using HTML, CSS, and JavaScript Language. In this application, there is a search bar where users can enter the username that they want to view. After entering the username, an API call is been triggered, and the details of the inputted user are returned to the user along with the repositories.
Create the GitHub Profile Search layout and structure using HTML tags. We have used the <input> tag to take the input from the user.
The entire styling of the application is done through the CSS file. All the colors, card layout, alignment, and heading are managed through the CSS file.
In JavaScript code, we define the API URL and axioms script in the variables, and then we store the reference of HTML elements like the search bar and in variables.
The user-defined function named "userGetFunction" makes an API call by taking the username as the parameter and also catches the error in case of profile is not present.
Then repoGetFunction is used to fetch the repos of the user searched through the search bar.
All this information is displayed in the attractive card component using the function "userCard".
In the "repoCardFunction", the repositories which are fetched can be visited by clicking on the repo. We are fetching and displaying 5 repositories of the user in the card.
