
 User Stories

## Details and Assumptions

- The application is a full-stack web application using React (frontend) and Express (backend).
- MongoDB is used as the database.
- Users can browse, search, and view gifts.
- Authentication will be implemented using a secure approach (e.g., JWT).
- The application will be deployed and accessible via a public URL.
- Docker will be used for containerization.
- The development follows Agile methodology and is driven by user stories.

---

## User Story #1 – Finish defining user stories

As a product owner, I need all user stories to be clearly defined so that the development team understands the full scope of the project.

### Acceptance Criteria

Given the project documentation  
When all user stories are written  
Then each story must follow the required template  

Given a defined user story  
When acceptance criteria are added  
Then they must clearly describe expected behavior  

Given all user stories  
When they are reviewed  
Then they must be approved by stakeholders  

### Definition of Done

- All user stories are documented  
- All acceptance criteria are defined  
- Stories are reviewed and approved  

---

## User Story #2 – Initialize and populate MongoDB

As a developer, I need to set up and populate MongoDB so that the application has initial data to work with.

### Acceptance Criteria

Given the application is started  
When the MongoDB server is running  
Then the application should connect successfully  

Given the database is connected  
When setup is executed  
Then the database schema should be created  

Given the database is initialized  
When sample data is inserted  
Then the data should be available for the backend  

### Definition of Done

- Database is accessible  
- Data exists in collections  
- No connection errors

---

## User Story #3 – Run skeleton application

As a developer, I want to run the base application so that I can verify the initial setup works correctly.

### Acceptance Criteria

Given the application codebase  
When the application is started  
Then it should run without errors  

Given frontend and backend services  
When both are running  
Then they should connect successfully  

Given the app is loaded  
When the default route is accessed  
Then the landing page should display  

### Definition of Done

- Application runs locally  
- No crashes or errors  

---

## User Story #4 – Implement landing page and navigation

As a user, I want a landing page with navigation so that I can easily move through the app.

### Acceptance Criteria

Given the application is opened  
When the landing page loads  
Then it should be visible to the user  

Given a navigation menu  
When a user clicks a link  
Then it should redirect correctly  

Given different sections of the app  
When navigation is used  
Then pages should load without errors  

### Definition of Done

- Navigation works correctly  
- UI is responsive  

---

# User Story #5 – Implement authentication

As a user, I want to register and log in so that I can access protected features.

### Acceptance Criteria

Given a new user  
When valid registration data is submitted  
Then a new account should be created  

Given a registered user  
When correct login credentials are entered  
Then the user should be authenticated  

Given a logged-in user  
When the user logs out  
Then the session should be terminated  

### Definition of Done

- Authentication works  
- Access is secured  

---

## User Story #6 – Gifts details page

As a user, I want to view details of a gift so that I understand its information.

### Acceptance Criteria

Given a gift item  
When the user accesses the details page  
Then gift information should be displayed  

Given gift data exists  
When the page loads  
Then data should be fetched dynamically  

Given the UI  
When details are shown  
Then information must be clear and structured  

### Definition of Done

- Page loads correctly  
- Data is displayed  

---

## User Story #7 – Search functionality

As a user, I want to search for gifts so that I can find items quickly.

### Acceptance Criteria

Given the user is on the gifts page  
When a search query is entered  
Then relevant results should appear  

Given no matching items  
When a search is performed  
Then a "No results" message should be shown  

Given search input  
When text is changed  
Then results should update dynamically  

### Definition of Done

- Search works correctly  
- Results update dynamically  

---

## User Story #8 – Comments system

As a user, I want to add comments to gifts so that I can share feedback.

### Acceptance Criteria

Given a logged-in user  
When a comment is submitted  
Then it should be saved in the database  

Given a gift page  
When comments exist  
Then they should be displayed  

Given comments are added  
When the page is refreshed  
Then comments should persist  

### Definition of Done

- Comments are stored  
- Comments are displayed  

---

## User Story #9 – Containerize application

As a developer, I want to containerize the app so that it runs consistently across environments.

### Acceptance Criteria

Given the project setup  
When Dockerfiles are created  
Then services should be containerized  

Given the application  
When containers are started  
Then services should run correctly  

Given environment variables  
When containers are configured  
Then the application should run without issues  

### Definition of Done

- App runs in Docker  
- Configuration works  

---

## User Story #10 – Deploy application

As a user, I want the application to be deployed so that I can access it online.

### Acceptance Criteria

Given the application  
When deployment is executed  
Then backend should be accessible  

Given frontend deployment  
When accessed via browser  
Then the UI should load correctly  

Given the deployed app  
When used by users  
Then functionality should work without major issues  

### Definition of Done

- Application is live  
- No critical bugs  

---

## User Story #11 – Research authentication

As a developer, I want to research authentication in React and Express so that I can implement a secure solution.

### Acceptance Criteria

Given authentication methods  
When research is conducted  
Then JWT and sessions should be analyzed  

Given documentation  
When findings are recorded  
Then clear notes should be produced  

Given the research results  
When evaluated  
Then a solution should be selected  

### Definition of Done

- Documentation is complete  
- Final solution is chosen  



