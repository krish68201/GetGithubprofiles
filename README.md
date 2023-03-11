#Get User from GitHub
This project allows users to easily find information about a GitHub user. By simply entering a GitHub username, the API call will retrieve and display information about the user, including their username, user ID, number of repositories, number of followers, and number of users they are following. Additionally, the project offers a convenient feature to switch between dark mode and light mode.

#How to Use
To use this project, follow these simple steps:

#Clone or download the project to your local machine.
Open the terminal and navigate to the project directory.
Install the necessary dependencies by running the following command:
Copy code
npm install
Run the project using the following command:
sql
Copy code
npm start
Open your web browser and navigate to http://localhost:3000.
Enter a GitHub username in the input field and click on the "Get User" button.
The project will retrieve and display information about the user, including their username, user ID, number of repositories, number of followers, and number of users they are following.
To switch between dark mode and light mode, click on the toggle button in the top right corner of the page.

Copy code
npm install
API
This project uses the GitHub API to retrieve information about a user. The API endpoint used is:

javascript
Copy code
https://api.github.com/users/{username}
Where {username} is the GitHub username entered by the user.

License
This project is licensed under the MIT License. See the LICENSE file for more information.
