# Pet Adoption React Routing Program

This is a pet adoption program built using React Router. The program includes four pages that allow users to search for and view details on pets available for adoption.

## Pages

### Home Page

The Home Page is the starting point of the application. The page displays a list of pets available for adoption based on the type of pet (e.g., dog, cat, rabbit) selected by the user. Users can click on any pet to view more details. If no pets are available for the selected type, a message is displayed to indicate that no pets are currently available.

### Pet Details Page

The Pet Details Page displays detailed information about a selected pet, including the pet's name, breed, color, gender, and description. The page also includes an image of the pet. If the pet details are not available, users are redirected to the Pet Details Not Found Page.

### Pet Details Not Found Page

The Pet Details Not Found Page is displayed when the details for a pet are not available. Users are encouraged to check back later and are provided with a button to go back to the previous page.

### Search Page

The Search Page allows users to search for pets by name. The page displays a list of pets that match the search term entered by the user.

## How to Run the Program

To run the program, clone the repository and run `npm install` to install the necessary dependencies. Then, run `npm start` to start the development server.