# ArtistsWebsite

Artist Project Documentation
Project Structure
Here is an overview of the key directories and files:
artists/
├── public/
├── src/
│   ├── assets/                # Folder for images and other static assets
│   │   └── scan.png           # Sample image used in the HomePage component
│   ├── components/            # Folder for all React components
│   │   ├── HomePage.js        # Main home page component with artist and      artwork sections
│   │ 
│   │  └── WelcomePage.js     # Welcome page with login choices for different user roles
│   ├── style/                 # Folder for custom CSS files
│   │   ├── HomePage.css       # CSS for HomePage styling
│   │   └── Welcome.css        # CSS for WelcomePage styling
│   ├── App.js                 # Main application component
│   └── index.js               # Application entry point
└── package.json               # Project dependencies and scripts

1.Install Dependencies: Install all necessary packages by running:
      npm install
2. Required Libraries
The project uses the following libraries:
•	React: For building user interfaces.
•	Bootstrap: For styling and responsive layout.
•	Bootstrap Icons: For including icons.
•	FontAwesome (Optional): For additional icons.
Install Bootstrap and Bootstrap Icons:
(“npm install bootstrap bootstrap-icons”)

3. Running the Project
  To start the development server:
     (“npm start”)
The app will be accessible at http://localhost:3000.

Components
1. App.js
•	The main application component.
•	Imports the HomePage component and sets it up as the main view.
. HomePage.js
This is the primary component for the home page, where users can:
•	Explore different artists and artworks.
•	Search for artists or artworks.
•	Access navigation links to Explore, Artists, and About.
•	Access features such as Search, Cart, and User Profile.
Key Sections in HomePage.js
•	Header: Contains the website title, navigation links, and action buttons.
•	Hero Section: Welcomes users with a title and a search bar.
•	Featured Artists Section: Displays featured artists with their names and specializations.
•	Latest Artworks Section: Shows recent artworks with artist names and descriptions.
•	Footer: Contains links to Terms of Service and Privacy Policy
3. WelcomePage.js
•	The landing page component.
•	Displays a welcome message and login options (using LoginOption component).
•	Displays login options for different user roles (e.g., Artist, Customer).
•	Accepts props for role, description, buttonLabel, and icon.
•	Uses bi class for icons from Bootstrap Icons.
Custom Styling
•	HomePage.css: Contains styling specific to HomePage.js.
•	Welcome.css: Contains styling for WelcomePage.js 
Resources Used
•	Bootstrap: Bootstrap Documentation
•	Bootstrap Icons: Bootstrap Icons
•	React Documentation: React Docs
•	W3Schools: For general HTML, CSS, and JavaScript references.
•	Stack Overflow & ChatGPT: For troubleshooting and specific component queries.



