**Home Assessment Task for FullStack Team Leader**

**Task Overview:**
Your objective is to create a simple web application allowing users to maintain a list of image URLs and play a slideshow with crossfade transitions.

**Requirements:**

1. **Frontend Part:**
   - Develop a UI application using Angular.
   - UI features
      - register new user (username, password)
      - login and logout functionality
      - manage list of image urls: add, delete, shuffle
      - play a slideshow of existing images with configurable delay (each 2 sec, each 5 sec)

2. **Backend Part:**
   - Create a Java Spring Boot application and implement a RESTful APIs.
   - Secure image URL management APIs using a token obtained upon login.
   - Implement the following RESTful API endpoints:
      - `POST /register`: Register a new user.
      - `POST /login`: Login a user.
      - `POST /logout`: Logout a user.
      - `POST /addImage`: Add a new image URL.
      - `DELETE /deleteImage/{id}`: Delete an existing image URL.
      - `POST /shuffleImages`: Shuffle existing images.
      - `GET /images`: Retrieve a list of image URLs.

3. **Database:**
   - Use a relational database (e.g., MySQL, PostgreSQL) to store project data, or in-memory database (e.g., H2).

4. **Documentation:**
   - Include user-friendly instructions in the README.md file.
   - Provide examples of API requests for demonstration (e.g., using cURL or Postman) in the README.md file.

**Submission Guidelines:**

1. **Code Submission:**
   - Share the source code of your web application in a public GitHub repository.

**Evaluation Criteria:**

1. **Functionality:**
   - Use modern versions of backend/frontend frameworks.
   - The REST APIs should follow best practices. 
   - Implement proper HTTP status codes and error handling consistently on both frontend and backend.
   - The application should handle errors gracefully.
   - Do not overcomplicate the application, this is not be supposed a task of days, but hours. Do not cut cornerns when it could impact on the application functionality and user experience.
   - Develop a functional UI with minimal yet aesthetically pleasing design using minimal CSS.

2. **Code Quality:**
   - Organize code effectively, adhering to best practices.
   - Include necessary comments for code clarity.

**Additional Notes:**

   - Feel free to use any additional libraries or tools that you think would be beneficial.
   - If you encounter any challenges or limitations during the process, document them in the README.md file.

Best of luck!